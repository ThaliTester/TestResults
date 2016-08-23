#### Test 817387969d88798_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 03:27:21.871   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 03:27:22.074  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 03:27:22.086  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 03:27:22.088  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 03:27:22.114  1490  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 03:27:22.114  1490  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 03:27:22.114  1490  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:27:22.114  1490  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-23 03:27:22.125  3695  3695 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 03:27:22.125  3695  3695 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 03:27:22.125  3695  3695 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-23 03:27:22.552  4002  4002 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 03:27:22.556  4002  4002 D AndroidRuntime: CheckJNI is OFF
08-23 03:27:22.599  4002  4002 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 03:27:22.647  4002  4002 I Radio-JNI: register_android_hardware_Radio DONE
08-23 03:27:22.670  4002  4002 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 03:27:22.674   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 03:27:22.711  2002  3926 W SearchService: Abort, client detached.
08-23 03:27:22.718  2002  2314 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fa8351b
08-23 03:27:22.718  2002  2002 I HotwordDetector: Closing mic
08-23 03:27:22.718  2002  2322 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 03:27:22.732  4002  4002 D AndroidRuntime: Shutting down VM
08-23 03:27:22.751   873  1948 I ActivityManager: Start proc 4011:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 03:27:22.788   374  2325 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 03:27:22.789   374  2325 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 03:27:22.795   374  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 03:27:22.797  2002  2320 I MicroRecognitionRnrImpl: Detection finished
08-23 03:27:22.798  2002  2317 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 03:27:22.824  4011  4011 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 03:27:22.847  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 03:27:22.855  4011  4011 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3408-3411)
08-23 03:27:22.855  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 03:27:22.871  4011  4011 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a1acc7a}
08-23 03:27:22.871  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 03:27:22.872  4011  4011 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 03:27:22.878  4011  4011 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 03:27:22.880  4011  4011 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 03:27:22.899  4011  4011 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 03:27:22.910  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 03:27:22.910  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 03:27:22.910  4011  4011 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 03:27:22.910  4011  4011 I Adreno  : Build Date                       : 10/20/15
08-23 03:27:22.910  4011  4011 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 03:27:22.910  4011  4011 I Adreno  : Local Branch                     : M14
08-23 03:27:22.910  4011  4011 I Adreno  : Remote Branch                    : 
08-23 03:27:22.910  4011  4011 I Adreno  : Remote Branch                    : 
08-23 03:27:22.910  4011  4011 I Adreno  : Reconstruct Branch               : 
,08-23 03:27:22.986   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b303f9a:true
,08-23 03:27:23.015  4011  4011 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 03:27:23.027  4011  4011 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 03:27:23.096  4011  4049 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 03:27:23.103  4011  4036 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 03:27:23.140  4011  4049 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 03:27:23.197   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +465ms
,08-23 03:27:23.202  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-23 03:27:23.259  4011  4011 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4011
,08-23 03:27:23.373  4011  4011 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 03:27:23.542   873  1966 I ActivityManager: Killing 3105:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 03:27:23.585   873  1966 I ActivityManager: Killing 3390:com.google.android.gm/u0a78 (adj 15): empty #18
,08-23 03:27:23.592  4011  4052 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1695614672
,08-23 03:27:23.597  4011  4052 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 03:27:23.597  4011  4052 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 03:27:23.597  4011  4052 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 03:27:23.597  4011  4052 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 03:27:23.597  4011  4052 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 03:27:23.597  4011  4052 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@405219 added. We now have 1 listener(s)
,08-23 03:27:23.603  4011  4052 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 03:27:23.607  4011  4052 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 03:27:23.608  4011  4052 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 03:27:23.608  4011  4052 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 03:27:23.611  4011  4052 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd8f8c added. We now have 1 listener(s)
08-23 03:27:23.612  4011  4052 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:27:23.616   873  1306 D WifiService: New client listening to asynchronous messages
,08-23 03:27:23.618  4011  4052 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:27:23.618  4011  4052 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 03:27:23.618  4011  4052 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 03:27:23.618  4011  4052 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 03:27:23.618  4011  4052 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 03:27:23.639  4011  4052 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:27:23.639  4011  4052 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-23 03:27:23.645  4011  4052 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:23.646  4011  4052 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:27:23.646  4011  4052 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 03:27:23.646  4011  4052 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 03:27:23.647  4011  4052 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 03:27:23.647  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:23.649  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:23.846  4011  4011 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 03:27:24.622  4011  4062 W jxcore-log: Initializing JXcore engine
08-23 03:27:24.622  4011  4062 W jxcore-log: JXcore engine is ready
,08-23 03:27:24.658  4062  4062 W Thread-370: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 03:27:24.658  4062  4062 W Thread-370: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10809]" dev="sockfs" ino=10809 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 03:27:24.674  4011  4062 W jxcore-log: Starting JXcore engine
,08-23 03:27:24.658  4062  4062 W Thread-370: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 03:27:24.658  4062  4062 W Thread-370: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25224]" dev="sockfs" ino=25224 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 03:27:24.757  4011  4062 W jxcore-log: Platform android
08-23 03:27:24.757  4011  4062 W jxcore-log: 
,08-23 03:27:24.757  4011  4062 W jxcore-log: Process ARCH arm
08-23 03:27:24.757  4011  4062 W jxcore-log: 
,08-23 03:27:25.056  4011  4062 I jxcore-log: JXcore Cordova bridge is ready!
08-23 03:27:25.056  4011  4062 I jxcore-log: 
,08-23 03:27:25.056  4011  4062 W jxcore-log: JXcore engine is started
,08-23 03:27:25.066  4011  4052 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 03:27:25.069  4011  4011 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 03:27:28.465  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:27:28.470  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:27:28.518  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 03:27:28.518  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 03:27:28.518  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:27:28.518  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:27:28.541  3732  4070 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 03:27:28.541  3732  4070 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at blb.a(PG:3937)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at czp.a(PG:18188)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:27:28.541  3732  4070 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	... 12 more
08-23 03:27:28.541  3732  4070 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at fal.a(PG:38)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:27:28.541  3732  4070 E HttpOperation: 	... 14 more
,08-23 03:27:28.568  1490  3099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 03:27:28.569  1490  3099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 03:27:28.569  1490  3099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:27:28.569  1490  3099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:27:28.585  3732  4070 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 03:27:28.585  3732  4070 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at hec.a(PG:42)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at hee.a(PG:102)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at czr.a(PG:65)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at kka.a(PG:108)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at czp.a(PG:19176)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:27:28.585  3732  4070 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	... 15 more
08-23 03:27:28.585  3732  4070 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at fal.a(PG:38)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:27:28.585  3732  4070 E HttpOperation: 	... 17 more
,08-23 03:27:28.585  3732  4070 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 03:27:28.585  3732  4070 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at hec.a(PG:42)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at hee.a(PG:102)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at czr.a(PG:65)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at kka.a(PG:108)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	... 15 more
08-23 03:27:28.585  3732  4070 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at fal.a(PG:38)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 03:27:28.585  3732  4070 E ExperimentLoader: 	... 17 more
,08-23 03:27:28.695   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128879, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:27:29.947   873  2054 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 03:27:41.618  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 03:27:41.618  4011  4062 I jxcore-log: 
,08-23 03:27:41.620  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 03:27:41.620  4011  4062 I jxcore-log: 
,08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:41.633  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:27:41.637  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:27:41.640  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 03:27:41.640  4011  4062 I jxcore-log: 
,08-23 03:27:41.642  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 03:27:41.642  4011  4062 I jxcore-log: 
,08-23 03:27:41.995  4011  4062 I jxcore-log: Running unit tests
08-23 03:27:41.995  4011  4062 I jxcore-log: 
,08-23 03:27:41.995  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 03:27:41.995  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73ef9dd added. We now have 2 listener(s)
,08-23 03:27:41.997  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 03:27:41.997  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:27:41.997  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 03:27:41.997  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:27:41.997  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dfe952 added. We now have 2 listener(s)
08-23 03:27:41.997  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:27:41.997  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 03:27:42.000  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:42.009  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:27:42.011  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:27:42.011  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:27:42.014  4011  4062 D ExecuteNativeTests: Running unit tests
,08-23 03:27:42.022  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:42.028  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:42.104  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 03:27:42.105  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 added. We now have 3 listener(s)
08-23 03:27:42.106  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 03:27:42.106  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:27:42.106  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:27:42.106  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:27:42.106  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 added. We now have 3 listener(s)
,08-23 03:27:42.106  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:27:42.106  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:27:42.111  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:42.126  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:27:42.129  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:27:42.130  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:27:42.134  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:42.136  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:42.138  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 03:27:42.140  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 03:27:42.140  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 03:27:42.140  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 03:27:42.142  4011  4062 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-23 03:27:42.142  4011  4062 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 03:27:42.142  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 03:27:42.142  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 03:27:42.142  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 03:27:42.143  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 03:27:42.143  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:27:42.143  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:27:42.143  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:27:42.144  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:27:42.144  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.144  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:27:42.144  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 03:27:42.144  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 removed from the list
08-23 03:27:42.144  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:42.144  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 removed from the list
08-23 03:27:42.144  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:27:42.144  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.145  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.145  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.146  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:27:42.146  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:27:42.146  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:42.146  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:42.148  4011  4062 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 03:27:42.148  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:27:42.148  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:27:42.148  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:27:42.149  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:27:42.149  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.149  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.149  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:27:42.149  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:42.149  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:42.149  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:27:42.149  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.149  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.149  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.149  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.150  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:27:42.150  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:27:42.150  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:42.150  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:42.154  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 03:27:42.155  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 03:27:42.156  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 03:27:42.156  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:27:42.156  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:27:42.156  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:27:42.156  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:27:42.157  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.157  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.157  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:27:42.157  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:42.157  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:42.157  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:27:42.157  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.157  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.157  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:42.157  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:42.158  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:27:42.158  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:27:42.158  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:42.158  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:42.159  4011  4062 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 03:27:42.160  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:42.165  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:27:42.167  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:42.167  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 03:27:42.168  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 03:27:42.168  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 03:27:42.168  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 03:27:42.168  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:27:42.168  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 03:27:42.169  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:27:42.172  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:27:42.173  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 03:27:42.173  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 03:27:42.179  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 03:27:42.181  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 03:27:42.181  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 03:27:42.184  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-23 03:27:42.187  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-23 03:27:42.187  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 03:27:42.187  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 03:27:42.188  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 03:27:42.189  4011  4062 D BluetoothAdapter: STATE_ON
08-23 03:27:42.192  2746  2756 D BtGatt.GattService: registerClient() - UUID=4e2de962-ba87-4e3a-a352-825e0b342e84
08-23 03:27:42.193  2746  2775 D BtGatt.GattService: onClientRegistered() - UUID=4e2de962-ba87-4e3a-a352-825e0b342e84, clientIf=5
08-23 03:27:42.194  4011  4023 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 03:27:42.194  2746  2898 D BtGatt.GattService: start scan with filters
08-23 03:27:42.197  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 03:27:42.197  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 03:27:42.197  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 03:27:42.197  2746  2806 D BtGatt.ScanManager: handling starting scan
08-23 03:27:42.197  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 03:27:42.199  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 03:27:42.199  2746  2806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
08-23 03:27:42.199  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 03:27:42.200  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 03:27:42.200  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-23 03:27:42.202  4011  4062 I io.jxcore.node.ConnectionHelper: start: OK
08-23 03:27:42.208  2746  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 03:27:42.209  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:42.209  2746  2806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 03:27:42.217  2746  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 03:27:42.218  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:42.218  2746  2806 D BtGatt.ScanManager: Starting BLE batch scan
08-23 03:27:42.218  2746  2806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 03:27:42.232  2746  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 03:27:42.233  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:42.243  2746  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 03:27:42.243  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:42.703  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-23 03:27:42.704  4011  4011 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 03:27:42.704  4011  4011 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 03:27:43.750  2746  2746 D BtGatt.ScanManager: awakened up at time 144307
,08-23 03:27:43.758  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:43.807  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-23 03:27:43.807  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:43.808  2746  2775 D BtGatt.GattService: current time is 144364601734
08-23 03:27:43.809  2746  2775 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -70, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-23 03:27:43.813  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-23 03:27:43.815  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-23 03:27:43.816  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 03:27:43.817  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-23 03:27:43.818  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-23 03:27:43.818  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-23 03:27:45.309  2746  2746 D BtGatt.ScanManager: awakened up at time 145865
,08-23 03:27:45.314  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:45.343  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-23 03:27:45.343  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:45.344  2746  2775 D BtGatt.GattService: current time is 145900628982
,08-23 03:27:45.344  2746  2775 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -98, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,08-23 03:27:45.345  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-23 03:27:45.346  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-23 03:27:45.347  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-23 03:27:46.848  2746  2746 D BtGatt.ScanManager: awakened up at time 147404
,08-23 03:27:46.850  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:46.888  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-23 03:27:46.888  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:46.888  2746  2775 D BtGatt.GattService: current time is 147445125208
,08-23 03:27:46.889  2746  2775 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -96, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -86, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -97, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-23 03:27:46.890  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-23 03:27:46.891  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-23 03:27:46.892  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 03:27:46.892  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 03:27:46.893  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-23 03:27:46.894  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-23 03:27:47.212  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:27:47.212  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 03:27:47.213  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 03:27:47.213  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:27:47.214  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 03:27:47.214  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 03:27:47.214  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 03:27:47.214  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 03:27:47.215  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 03:27:47.217  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 03:27:47.217  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 03:27:47.219  4011  4062 D BluetoothAdapter: STATE_ON
08-23 03:27:47.221  2746  2758 D BtGatt.GattService: stopScan() - queue size =1
,08-23 03:27:47.224  2746  2756 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 03:27:47.225  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 03:27:47.225  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 03:27:47.225  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 03:27:47.226  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 03:27:47.226  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 03:27:47.230  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 03:27:47.231  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 03:27:47.232  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 03:27:47.233  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 03:27:47.235  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 03:27:47.239  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 03:27:47.239  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:27:47.239  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-23 03:27:47.239  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:47.240  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:27:47.240  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:27:47.240  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:27:47.241  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-23 03:27:47.241  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:47.241  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:27:47.241  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:47.245  2746  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 03:27:47.245  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:47.246  2746  2806 D BtGatt.ScanManager: stopping BLe Batch
,08-23 03:27:47.259  2746  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 03:27:47.260  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:47.261  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:47.267  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 03:27:47.268  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:47.742  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 03:27:49.706   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-23 03:27:49.715  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-23 03:27:49.731   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 03:27:49.731   873   893 I Adreno  : Build Date                       : 10/20/15
08-23 03:27:49.731   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 03:27:49.731   873   893 I Adreno  : Local Branch                     : M14
08-23 03:27:49.731   873   893 I Adreno  : Remote Branch                    : 
08-23 03:27:49.731   873   893 I Adreno  : Remote Branch                    : 
08-23 03:27:49.731   873   893 I Adreno  : Reconstruct Branch               : 
,08-23 03:27:49.765   281   299 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (194 us)
,08-23 03:27:50.433  4011  4011 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 03:27:50.434  4011  4011 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 03:27:50.492   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-23 03:27:50.495  4011  4011 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@39eb0a0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4149a8b, 16908290=android.view.AbsSavedState$1@4149a8b}, android:focusedViewId=100}]}]
08-23 03:27:50.495  4011  4011 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-23 03:27:50.495  4011  4011 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 03:27:50.495  4011  4011 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 03:27:50.500   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-23 03:27:50.504   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-23 03:27:50.506   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-23 03:27:50.506   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-23 03:27:50.733   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 03:27:50.735   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-23 03:27:50.736   873  1332 D SurfaceControl: Excessive delay in setPowerMode(): 232ms
08-23 03:27:50.741   873   893 I DreamManagerService: Entering dreamland.
08-23 03:27:50.743   873   893 I PowerManagerService: Dozing...
,08-23 03:27:50.744   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-23 03:27:50.819   374  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-23 03:27:50.819   374  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-23 03:27:50.837   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:27:50.853  1907  4079 D NfcService: Discovery configuration equal, not updating.
,08-23 03:27:50.858   873  1305 E native  : do suspend false
,08-23 03:27:50.884   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 03:27:50.904   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:27:50.915   873  1305 E native  : do suspend true
,08-23 03:27:50.945   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-23 03:27:50.945   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-23 03:27:51.344   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-23 03:27:52.243  4011  4062 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 03:27:52.250  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:52.264  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:27:52.270  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:27:52.271  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:27:52.271  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 03:27:52.272  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 03:27:52.272  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 03:27:52.272  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:27:52.273  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 03:27:52.279  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:52.286  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 03:27:52.286  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 03:27:52.288  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:52.299  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 03:27:52.302  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 03:27:52.302  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 03:27:52.305  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 03:27:52.305  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 03:27:52.305  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 03:27:52.306  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:27:52.309  2746  2756 D BtGatt.GattService: registerClient() - UUID=2ee7f910-94e0-4198-80f5-087cf7657f1c
,08-23 03:27:52.310  2746  2775 D BtGatt.GattService: onClientRegistered() - UUID=2ee7f910-94e0-4198-80f5-087cf7657f1c, clientIf=5
,08-23 03:27:52.311  4011  4058 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 03:27:52.311  2746  2897 D BtGatt.GattService: start scan with filters
,08-23 03:27:52.316  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 03:27:52.317  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 03:27:52.317  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 03:27:52.317  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 03:27:52.319  2746  2806 D BtGatt.ScanManager: handling starting scan
,08-23 03:27:52.321  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 03:27:52.322  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 03:27:52.322  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 03:27:52.324  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 03:27:52.330  2746  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 03:27:52.330  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:52.330  4011  4062 I io.jxcore.node.ConnectionHelper: start: OK
08-23 03:27:52.331  2746  2806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 03:27:52.334  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:27:52.334  4011  4062 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 03:27:52.334  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:27:52.334  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 03:27:52.335  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:52.335  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 03:27:52.335  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 03:27:52.335  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 03:27:52.335  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 03:27:52.335  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 03:27:52.335  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 03:27:52.335  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 03:27:52.337  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:27:52.338  2746  2756 D BtGatt.GattService: stopScan() - queue size =1
08-23 03:27:52.339  2746  2758 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 03:27:52.339  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 03:27:52.339  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 03:27:52.339  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 03:27:52.339  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 03:27:52.340  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 03:27:52.341  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:27:52.341  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 03:27:52.341  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 03:27:52.341  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 03:27:52.341  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:27:52.344  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 03:27:52.344  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 03:27:52.344  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 03:27:52.344  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:27:52.344  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:52.344  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:27:52.344  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:27:52.344  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:27:52.345  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:27:52.345  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:27:52.345  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:52.345  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:27:52.345  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:27:52.346  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:27:52.346  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:27:52.346  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:27:52.346  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:27:52.350  2746  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 03:27:52.350  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:52.350  2746  2806 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 03:27:52.350  2746  2806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 03:27:52.351  4011  4062 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 03:27:52.355  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:27:52.362  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:27:52.363  2746  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 03:27:52.363  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:52.364  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:27:52.365  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:27:52.367  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:52.368  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:27:52.367  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 03:27:52.369  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 03:27:52.369  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 03:27:52.369  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:27:52.369  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 03:27:52.370  2746  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 03:27:52.370  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:52.372  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 03:27:52.372  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 03:27:52.375  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 03:27:52.376  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 03:27:52.376  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 03:27:52.377  2746  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 03:27:52.378  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:52.378  2746  2806 D BtGatt.ScanManager: stopping BLe Batch
,08-23 03:27:52.379  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 03:27:52.379  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 03:27:52.379  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 03:27:52.380  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:27:52.383  2746  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 03:27:52.383  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:52.383  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:52.385  2746  2898 D BtGatt.GattService: registerClient() - UUID=1f8738f2-c0b0-4e43-84d3-7a22fa16aaf5
,08-23 03:27:52.386  2746  2775 D BtGatt.GattService: onClientRegistered() - UUID=1f8738f2-c0b0-4e43-84d3-7a22fa16aaf5, clientIf=5
08-23 03:27:52.386  4011  4058 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 03:27:52.386  2746  2897 D BtGatt.GattService: start scan with filters
,08-23 03:27:52.388  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 03:27:52.388  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:52.390  2746  2806 D BtGatt.ScanManager: handling starting scan
,08-23 03:27:52.389  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 03:27:52.390  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 03:27:52.391  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 03:27:52.391  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 03:27:52.394  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 03:27:52.394  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 03:27:52.394  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 03:27:52.395  2746  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 03:27:52.395  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:52.396  2746  2806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 03:27:52.396  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 03:27:52.398  4011  4062 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 03:27:52.401  2746  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 03:27:52.401  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:52.401  2746  2806 D BtGatt.ScanManager: Starting BLE batch scan
08-23 03:27:52.401  2746  2806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 03:27:52.411  2746  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 03:27:52.411  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:52.417  2746  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 03:27:52.417  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:52.895  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-23 03:27:52.896  4011  4011 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 03:27:52.896  4011  4011 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 03:27:53.928  2746  2746 D BtGatt.ScanManager: awakened up at time 154484
,08-23 03:27:53.932  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:53.975  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-23 03:27:53.975  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:53.976  2746  2775 D BtGatt.GattService: current time is 154532346132
,08-23 03:27:53.977  2746  2775 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -92, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-23 03:27:53.977  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-23 03:27:53.979  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 03:27:53.980  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 03:27:53.981  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-23 03:27:53.981  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-23 03:27:53.982  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-23 03:27:55.478  2746  2746 D BtGatt.ScanManager: awakened up at time 156034
,08-23 03:27:55.480  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:55.537  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-23 03:27:55.537  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:55.538  2746  2775 D BtGatt.GattService: current time is 156094561445
08-23 03:27:55.539  2746  2775 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -97, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -99, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-23 03:27:55.540  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-23 03:27:55.541  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-23 03:27:55.542  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-23 03:27:55.543  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-23 03:27:55.544  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-23 03:27:56.875  1983  2712 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 03:27:57.040  2746  2746 D BtGatt.ScanManager: awakened up at time 157596
,08-23 03:27:57.042  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:57.096  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-23 03:27:57.096  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:57.096  2746  2775 D BtGatt.GattService: current time is 157653082718
,08-23 03:27:57.097  2746  2775 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -96, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -98, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 03:27:57.099  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 03:27:57.100  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-23 03:27:57.102  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-23 03:27:57.103  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-23 03:27:57.104  2746  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-23 03:27:57.399  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:27:57.399  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:27:57.400  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 03:27:57.400  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:27:57.400  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-23 03:27:57.401  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 03:27:57.401  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 03:27:57.401  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 03:27:57.401  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 03:27:57.402  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 03:27:57.403  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 03:27:57.406  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:27:57.409  2746  2897 D BtGatt.GattService: stopScan() - queue size =1
,08-23 03:27:57.411  2746  2758 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 03:27:57.412  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 03:27:57.413  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 03:27:57.413  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 03:27:57.413  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 03:27:57.414  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 03:27:57.417  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:27:57.418  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 03:27:57.419  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 03:27:57.419  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 03:27:57.421  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 03:27:57.423  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 03:27:57.424  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 03:27:57.424  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:27:57.426  2746  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 03:27:57.426  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:57.427  2746  2806 D BtGatt.ScanManager: stopping BLe Batch
,08-23 03:27:57.436  2746  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 03:27:57.436  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:27:57.437  2746  2806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:27:57.445  2746  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 03:27:57.445  2746  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:27:57.925  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 03:27:57.926  4011  4011 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:27:57.926  4011  4011 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 03:27:58.871  3932  4084 V KeepSync: Connecting to GoogleApiClient
,08-23 03:27:58.872   873  1952 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 03:27:58.938  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:27:58.945  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:27:58.985  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 03:27:58.985  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 03:27:58.985  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:27:58.985  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:27:59.016  1708  4085 V BaseAuthAsyncOperation: access token request failed
,08-23 03:27:59.018  3932  4084 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 03:27:59.124  1490  3099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 03:27:59.124  1490  3099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 03:27:59.124  1490  3099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:27:59.125  1490  3099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:27:59.179  3932  4084 E KeepSync: IOException
08-23 03:27:59.179  3932  4084 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 03:27:59.179  3932  4084 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:27:59.179  3932  4084 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 03:27:59.179  3932  4084 E KeepSync: 	... 10 more
08-23 03:27:59.179  3932  4084 W KeepSync: Sync result 2
,08-23 03:27:59.194   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 158221, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:28:01.885   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-23 03:28:02.424  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.425  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.425  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:02.426  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.426  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.426  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:28:02.427  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.427  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.427  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.428  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.428  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.430  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.430  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.433  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-23 03:28:02.434  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:02.434  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.434  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.436  4011  4062 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-23 03:28:02.438  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.439  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.439  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 03:28:02.440  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.440  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:02.440  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.441  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.441  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.441  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.442  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.442  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.442  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.442  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.443  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.447  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.447  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:02.447  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.447  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.448  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 03:28:02.448  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.448  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.448  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 03:28:02.449  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:02.449  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.449  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.449  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.449  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:02.449  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:02.449  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.449  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:02.449  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.449  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:02.449  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.451  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:28:02.451  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:02.451  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-23 03:28:02.451  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:02.452  4011  4062 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
08-23 03:28:02.452  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.452  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:28:02.452  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 03:28:02.452  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:02.453  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.453  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.453  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.453  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:02.453  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.453  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:02.453  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.453  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.453  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:02.453  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.455  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.455  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:02.455  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.455  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:02.456  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 03:28:02.456  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.456  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:28:02.456  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:02.456  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.456  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.456  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.456  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.456  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:02.456  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.457  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.457  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.457  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.457  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.457  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.458  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.458  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:02.458  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.458  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.459  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 03:28:02.459  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 03:28:02.459  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 03:28:02.459  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-23 03:28:02.459  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 03:28:02.459  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 03:28:02.460  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 03:28:02.460  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 03:28:02.460  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 03:28:02.460  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:28:02.460  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:28:02.464  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:02.464  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.465  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.465  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.465  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.465  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.465  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.465  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.465  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.465  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.465  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.465  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.467  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.467  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:02.467  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.467  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.469  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 03:28:02.469  4011  4062 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-23 03:28:02.469  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-23 03:28:02.479  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 03:28:02.479  4011  4062 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 03:28:02.479  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 03:28:02.479  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 03:28:02.479  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-23 03:28:02.479  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 03:28:02.480  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 03:28:02.480  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 03:28:02.480  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 03:28:02.480  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 03:28:02.480  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-23 03:28:02.481  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 03:28:02.481  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 03:28:02.481  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 03:28:02.481  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 03:28:02.482  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-23 03:28:02.482  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 03:28:02.483  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 03:28:02.483  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 03:28:02.484  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 03:28:02.485  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-23 03:28:02.485  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 03:28:02.485  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 03:28:02.485  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 03:28:02.485  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 03:28:02.487  4011  4062 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-23 03:28:02.488  4011  4062 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-23 03:28:02.488  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 03:28:02.489  4011  4062 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 03:28:02.489  4011  4062 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 03:28:02.490  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 03:28:02.490  4011  4062 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 03:28:02.491  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-23 03:28:02.495  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 03:28:02.498  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 03:28:02.498  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 03:28:02.499  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 03:28:02.500  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 03:28:02.500  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 03:28:02.501  4011  4086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 434)
,08-23 03:28:02.502  4011  4062 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 03:28:02.502  4011  4062 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 03:28:02.503  4011  4086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:02.504  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.504  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.504  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 03:28:02.505  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:02.505  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.505  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.506  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 03:28:02.506  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.506  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.507  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:02.507  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.507  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.507  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.507  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.507  4011  4087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 434
08-23 03:28:02.507  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.507  4011  4087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 434)
08-23 03:28:02.507  4011  4086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 434)
08-23 03:28:02.508  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.508  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:02.508  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.508  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.508  2746  2877 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-23 03:28:02.509  4011  4087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 434)
08-23 03:28:02.509  4011  4062 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 03:28:02.509  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:28:02.509  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.509  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:02.510  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.510  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.510  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.510  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.510  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.510  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:02.510  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.510  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.510  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.510  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.511  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.511  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.512  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:02.512  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:02.512  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.513  4011  4062 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 03:28:02.513  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:02.513  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.513  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:02.513  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.513  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.513  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.514  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:28:02.514  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.514  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.514  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.514  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.514  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.514  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.514  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:02.517  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.517  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:02.517  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.517  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:02.527  4011  4062 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-23 03:28:02.527  4011  4062 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 03:28:02.527  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 03:28:02.527  4011  4062 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 03:28:02.527  4011  4062 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 03:28:02.527  4011  4062 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 03:28:02.528  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-23 03:28:02.528  4011  4062 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 03:28:02.528  4011  4062 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-23 03:28:02.528  4011  4062 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 03:28:02.528  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 03:28:02.528  4011  4062 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 03:28:02.528  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:28:02.528  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:02.528  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:02.528  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:02.529  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.529  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.529  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.529  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:02.529  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.529  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.529  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.529  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.529  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.529  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.530  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:02.530  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:02.530  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.530  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.531  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:02.531  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:02.531  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:02.531  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:02.531  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:02.531  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:02.531  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:02.531  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:02.531  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.533  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.533  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:07.533  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:07.534  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.534  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.534  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:28:07.535  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:28:07.535  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:07.536  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 03:28:07.537  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:07.537  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.537  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.538  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:07.538  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:07.538  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.538  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:07.539  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.539  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.539  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.540  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.547  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:28:07.547  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:07.547  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:07.548  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.552  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-23 03:28:07.553  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:28:07.554  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-23 03:28:07.555  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-23 03:28:07.555  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 03:28:07.556  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-23 03:28:07.556  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 03:28:07.556  4011  4011 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-23 03:28:07.556  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:07.556  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-23 03:28:07.556  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 03:28:07.556  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-23 03:28:07.557  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.557  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-23 03:28:07.557  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:28:07.557  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.557  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 03:28:07.560  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 03:28:07.566  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 03:28:07.557  4011  4088 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 03:28:07.557  4011  4011 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-23 03:28:07.567  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.567  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-23 03:28:07.567  4011  4088 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-23 03:28:07.569  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:28:07.569  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.569  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:28:07.569  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-23 03:28:07.570  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:07.570  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 03:28:07.571  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:07.571  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:07.571  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 03:28:07.571  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.571  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:28:07.571  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.571  4011  4011 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 03:28:07.571  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:07.571  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:07.571  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.571  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.571  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 03:28:07.571  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.571  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.573  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:07.573  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:07.573  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.573  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:07.575  4011  4062 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 03:28:07.575  4011  4062 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 03:28:07.575  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 03:28:07.575  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 03:28:07.575  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 03:28:07.575  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:28:07.576  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:07.576  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:07.576  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:07.576  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.577  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.577  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:28:07.577  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.577  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:07.577  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:07.577  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.577  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.578  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.578  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.580  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:07.581  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:28:07.581  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.582  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.593  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:07.593  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:07.593  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:07.593  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:28:07.594  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.594  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.594  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
08-23 03:28:07.594  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.594  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.594  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:07.594  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.594  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.594  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.594  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.596  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:28:07.597  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:07.597  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.597  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.599  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:28:07.600  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:28:07.600  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:28:07.600  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:28:07.601  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.601  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.601  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd70e50 not in the list
,08-23 03:28:07.601  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.602  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
08-23 03:28:07.602  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:07.602  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:07.602  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:07.603  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:07.603  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:07.605  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:28:07.605  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:28:07.606  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:07.606  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccda849 not in the list
,08-23 03:28:07.609  4011  4062 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-23 03:28:07.609  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 03:28:07.609  4011  4062 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-23 03:28:07.610  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 03:28:07.610  4011  4062 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 03:28:07.610  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-23 03:28:07.617  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-23 03:28:07.617  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 03:28:07.618  4011  4062 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 03:28:07.618  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-23 03:28:07.618  4011  4062 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 03:28:07.619  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 03:28:07.619  4011  4062 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 03:28:07.619  4011  4062 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-23 03:28:07.619  4011  4062 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 03:28:07.619  4011  4062 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-23 03:28:07.620  4011  4062 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 03:28:07.620  4011  4062 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 03:28:07.620  4011  4062 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 03:28:07.620  4011  4062 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-23 03:28:07.622  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 03:28:07.622  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a32ab80 added. We now have 3 listener(s)
08-23 03:28:07.622  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:28:07.624  4011  4062 D BluetoothAdapter: enable(): BT is already enabled..!
,08-23 03:28:07.625   873  1951 D WifiService: setWifiEnabled: true pid=4011, uid=10000
,08-23 03:28:07.625   873  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 03:28:07.635  2746  2846 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-23 03:28:07.635  2746  2846 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-23 03:28:08.072  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 03:28:12.632  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 03:28:12.633  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd435b9 added. We now have 4 listener(s)
,08-23 03:28:12.634  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:28:12.649  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:12.650  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd435b9 removed from the list
,08-23 03:28:12.650  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:12.650  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:12.651  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:12.653  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:28:12.653  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cf6dfe added. We now have 4 listener(s)
08-23 03:28:12.654  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:28:12.658  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:12.658  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cf6dfe removed from the list
08-23 03:28:12.659  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:12.659  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:12.659  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:12.662  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:28:12.662  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@49695f added. We now have 4 listener(s)
,08-23 03:28:12.662  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:28:12.669   873  3272 D WifiService: setWifiEnabled: false pid=4011, uid=10000
,08-23 03:28:12.669   873  3272 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 03:28:12.688  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:28:12.691  2746  2771 D BluetoothAdapterState: Current state: ON, message: 23
08-23 03:28:12.691  2746  2771 D BluetoothAdapterProperties: Setting state to 13
08-23 03:28:12.692  2746  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-23 03:28:12.694  2746  2771 D BluetoothAdapterProperties: onBluetoothDisable(),
,08-23 03:28:12.699  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:12.700  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:12.700  2746  2775 D BluetoothAdapterProperties: Scan Mode:20
,08-23 03:28:12.701  2746  2771 I BluetoothAdapterState: Entering PendingCommandState,
,08-23 03:28:12.701  2746  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-23 03:28:12.706  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.706  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:12.708  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:28:12.713  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:12.713  2746  2746 D HeadsetService: Received stop request...Stopping profile...
,08-23 03:28:12.715  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1,
,08-23 03:28:12.717  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:12.717   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-23 03:28:12.718   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-23 03:28:12.718   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 03:28:12.718   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:12.726  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:12.727  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:12.727   873  1305 E native  : do suspend true
08-23 03:28:12.729  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.729  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:12.735  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:12.735  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:12.737  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.737  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:12.740   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-23 03:28:12.740   873  2058 D DhcpClient: Clearing IP address
,08-23 03:28:12.742   873   886 I ActivityManager: Start proc 4092:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-23 03:28:12.742   370   871 D CommandListener: Setting iface cfg
08-23 03:28:12.744   873   873 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:12.745  2746  2746 D BluetoothMapService: onReceive
08-23 03:28:12.746  2746  2746 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 03:28:12.746  1920  2065 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:12.746  2746  2746 D BluetoothMapService: STATE_TURNING_OFF
,08-23 03:28:12.746  2746  2746 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:12.746  2746  2746 V BluetoothAdapterState: isTurningOn()=false
,08-23 03:28:12.746  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:12.746  2746  2746 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:12.747  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.748   873   873 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:12.749  2746  2746 D A2dpService: Received stop request...Stopping profile...
08-23 03:28:12.749  2746  2892 D A2dpStateMachine: Exit Disconnected: -1
08-23 03:28:12.750   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-23 03:28:12.750   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 03:28:12.750   873  1305 E native  : do suspend true
08-23 03:28:12.750   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-23 03:28:12.751   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-23 03:28:12.751  1352  2021 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:12.752   873   873 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:12.753  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:12.753  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:28:12.754  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.754  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:12.755   873   873 D BluetoothA2dp: Proxy object disconnected
08-23 03:28:12.755   394   394 E Parcel  : Reading a NULL string not supported here.
08-23 03:28:12.757  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.757  2746  2746 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.757  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:28:12.757  2746  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-23 03:28:12.757  2746  2746 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-23 03:28:12.757  2746  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:12.757  2746  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:12.757  2746  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:12.757  2746  2775 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-23 03:28:12.757  1352  1352 D HeadsetProfile: Bluetooth service disconnected
08-23 03:28:12.758  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.758  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:12.758  2746  2746 D BluetoothMapService: MAP Service closeService in
08-23 03:28:12.759  1352  1352 D BluetoothA2dp: Proxy object disconnected
,08-23 03:28:12.758  2746  2746 D BluetoothMapMasInstance0: MAP Service shutdown
08-23 03:28:12.759  2746  2746 D ObexServerSockets0: shutdown(block = true)
08-23 03:28:12.760  2746  2899 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-23 03:28:12.760  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.761  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:12.761  2746  2746 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 03:28:12.761  2746  2900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-23 03:28:12.761  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.761  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:12.759   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-23 03:28:12.763   873  2068 D DhcpClient: Receive thread stopped
08-23 03:28:12.765  2746  2877 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 03:28:12.765  2746  2746 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 03:28:12.765  2746  2746 I BtOppRfcommListener: stopping Accept Thread
08-23 03:28:12.765  2746  3598 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 03:28:12.766  2746  3598 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 03:28:12.767  2746  2746 D HidService: Received stop request...Stopping profile...
08-23 03:28:12.768  2746  2746 D HidService: Stopping Bluetooth HidService
,08-23 03:28:12.769  1490  2914 V NativeCrypto: Read error: ssl=0x9b27a000: I/O error during system call, Connection timed out
08-23 03:28:12.769  2746  2746 D HealthService: Received stop request...Stopping profile...
08-23 03:28:12.770  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-23 03:28:12.770  1352  1352 D HidProfile: Bluetooth service disconnected
08-23 03:28:12.770  2746  2746 D PanService: Received stop request...Stopping profile...
08-23 03:28:12.771  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 03:28:12.771  1352  1352 D PanProfile: Bluetooth service disconnected
,08-23 03:28:12.771  1490  2914 V NativeCrypto: SSL shutdown failed: ssl=0x9b27a000: I/O error during system call, Broken pipe
08-23 03:28:12.772  2746  2746 D BluetoothMapService: Received stop request...Stopping profile...
08-23 03:28:12.772  2746  2746 D BluetoothMapService: stop()
08-23 03:28:12.772  2746  2746 D BluetoothMapAppObserver: deinitObservers()
08-23 03:28:12.772  2746  2746 D BluetoothMapAppObserver: removeReceiver()
08-23 03:28:12.774  2746  2746 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:12.774  2746  2746 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:12.774  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 03:28:12.774  2746  2746 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:12.775  2746  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:12.775  2746  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-23 03:28:12.775  2746  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:12.775  2746  2846 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 03:28:12.775  2746  2846 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 03:28:12.775  2746  2846 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 03:28:12.775  2746  2846 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 03:28:12.776  2746  2746 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:12.776  2746  2746 V BluetoothAdapterState: isTurningOn()=false
,08-23 03:28:12.776  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:12.776  2746  2746 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:12.776  2746  2746 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 03:28:12.776  2746  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 03:28:12.776  2746  2746 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 03:28:12.777  2746  2746 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:12.777  2746  2746 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:12.777  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:12.777  2746  2746 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:12.777  2746  2746 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 03:28:12.777  2746  2775 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-23 03:28:12.777  2746  2746 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 03:28:12.778  2746  2746 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:12.778  2746  2746 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:12.778  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:12.778  2746  2746 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:12.778  2746  2746 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 03:28:12.778  2746  2746 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 03:28:12.779  2746  2746 D BluetoothMapService: MAP Service closeService in
08-23 03:28:12.779  2746  2746 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:12.779  2746  2746 V BluetoothAdapterState: isTurningOn()=false
,08-23 03:28:12.779  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:12.779  2746  2746 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:12.780  2746  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 03:28:12.780  2746  2771 D BluetoothAdapterProperties: Setting state to 15
08-23 03:28:12.780  2746  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 03:28:12.781  2746  2771 I BluetoothAdapterState: Entering BleOnState
08-23 03:28:12.781  1920  2195 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:12.781  1352  1364 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 03:28:12.782   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:12.782  1352  1363 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 03:28:12.782   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:12.782  1352  2021 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 03:28:12.782   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:12.783  1352  1364 D BluetoothPan: onBluetoothStateChange on: false
08-23 03:28:12.783  1352  1363 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 03:28:12.783   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 03:28:12.783  1352  2021 D BluetoothMap: onBluetoothStateChange: up=false
08-23 03:28:12.781  2746  2746 D BluetoothMapService: cleanup()
08-23 03:28:12.784  2746  2746 D BluetoothMapService: MAP Service closeService in
,08-23 03:28:12.784  2746  2771 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-23 03:28:12.784  2746  2771 D BluetoothAdapterProperties: Setting state to 16
08-23 03:28:12.784  2746  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-23 03:28:12.785  2746  2771 D BluetoothAdapterProperties: onBleDisable
08-23 03:28:12.785  2746  2771 I BluetoothAdapterState: Entering PendingCommandState
08-23 03:28:12.785  2746  2772 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 03:28:12.786  2746  2846 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-23 03:28:12.786  2746  2846 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:12.787  2746  2775 D BluetoothAdapterProperties: Scan Mode:20
08-23 03:28:12.790  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.790  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:12.792  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.792  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:12.793  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.793  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:12.795  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.796  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.797  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.803   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:12.809  4092  4092 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-23 03:28:12.818  4092  4092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 03:28:12.822   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:12.823   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-23 03:28:12.823   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-23 03:28:12.824   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:12.824   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 03:28:12.826  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 03:28:12.826   873   890 D Tethering: MasterInitialState.processMessage what=3
08-23 03:28:12.829  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.831  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.832  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:12.832  3590  3590 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@cbcc2de and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-23 03:28:12.829  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-23 03:28:12.839   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4dcad1a:true
,08-23 03:28:12.846   873  3272 I ActivityManager: Start proc 4110:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-23 03:28:12.847   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:28:12.849  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.850  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:12.851  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.851  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:12.852  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.852  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:12.853  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.853  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:12.853   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 03:28:12.855  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:12.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:12.855  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:12.855  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:12.860  1983  2299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 03:28:12.876  4092  4092 D LocalBluetoothProfileManager: Adding local MAP profile
,08-23 03:28:12.878  4092  4092 D BluetoothMap: Create BluetoothMap proxy object
,08-23 03:28:12.880   370   871 E Netd    : netlink response contains error (No such file or directory)
,08-23 03:28:12.884  4110  4110 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-23 03:28:12.888  4092  4092 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-23 03:28:12.904  4092  4092 D DockEventReceiver: finishStartingService: stopping service
,08-23 03:28:12.907   873  3273 I ActivityManager: Killing 3217:com.google.android.talk/u0a61 (adj 15): empty #17
,08-23 03:28:12.987  2746  2775 I bt_hci  : shut_down
,08-23 03:28:12.988  2746  2807 D bt_hwcfg: hw_epilog_process
,08-23 03:28:12.998  2746  2807 I bt_vendor: low_power_mode_cb
,08-23 03:28:13.017  2746  2807 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 03:28:13.018  2746  2807 I bt_vendor: epilog_cb
,08-23 03:28:13.018  2746  2807 I bt_hci  : epilog_finished_callback
,08-23 03:28:13.024  2746  2775 I bt_hci_h4: hal_close
,08-23 03:28:13.025  2746  2775 I bt_userial_vendor: device fd = 51 close
,08-23 03:28:13.087  4110  4110 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 03:28:13.087  4110  4110 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.087  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 03:28:13.088  4110  4110 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 03:28:13.088  4110  4110 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 03:28:13.088  4110  4110 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.k.d(PG:583)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 03:28:13.088  4110  4110 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at an,droid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 03:28:13.088  4110  4110 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.088  4110  4110 D StrictM,ode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 03:28:13.088  4110  4110 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:28:13.088  4110  4110 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 03:28:13.136   873  1942 I ActivityManager: Start proc 4142:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-23 03:28:13.137   873  1942 I ActivityManager: Killing 3748:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-23 03:28:13.178  2746  2772 D bt_stack_manager: event_shut_down_stack finished.
,08-23 03:28:13.179  2746  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 03:28:13.185  2746  2771 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 03:28:13.186  2746  2746 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 03:28:13.188  2746  2746 D BtGatt.GattService: Received stop request...Stopping profile...
,08-23 03:28:13.188  2746  2746 D BtGatt.GattService: stop()
,08-23 03:28:13.188  2746  2746 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 03:28:13.190  2746  2746 V BluetoothAdapterState: isTurningOff()=false
,08-23 03:28:13.190  2746  2746 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:13.190  2746  2746 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 03:28:13.190  2746  2746 V BluetoothAdapterState: isBleTurningOff()=true
08-23 03:28:13.191  2746  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-23 03:28:13.191  2746  2771 D BluetoothAdapterProperties: Setting state to 10
,08-23 03:28:13.191  2746  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-23 03:28:13.192  2746  2771 I BluetoothAdapterState: Entering OffState
08-23 03:28:13.194   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-23 03:28:13.207  2746  2746 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-23 03:28:13.207  2746  2746 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 03:28:13.207  2746  2746 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 03:28:13.207  2746  2772 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-23 03:28:13.211  2746  2772 D bt_stack_manager: event_clean_up_stack finished.
,08-23 03:28:13.215  4142  4142 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-23 03:28:13.224  2746  2746 I art     : System.exit called, status: 0
,08-23 03:28:13.224  2746  2746 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 03:28:13.288   873  1952 I ActivityManager: Process com.android.bluetooth (pid 2746) has died
,08-23 03:28:13.437  4142  4161 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-23 03:28:13.437  4142  4161 I Babel_SMS: MmsConfig.loadMmsSettings
,08-23 03:28:13.444  4142  4161 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-23 03:28:13.444  4142  4161 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 03:28:13.491  4142  4161 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-23 03:28:13.491  4142  4161 I Babel_SMS: MmsConfig.loadFromResources
08-23 03:28:13.492  4142  4161 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-23 03:28:13.492  4142  4161 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-23 03:28:13.510  4142  4142 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 03:28:13.513  4142  4142 I Babel_Crash: startup - clean
,08-23 03:28:13.540  4142  4142 I Babel_telephony: TeleModule.launchCompleted
,08-23 03:28:13.549   873   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null,
,08-23 03:28:13.561  4142  4142 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-23 03:28:13.569  4142  4142 W Babel   : BAM#gBA: invalid account id: -1
,08-23 03:28:13.569  4142  4142 W Babel   : BAM#gBA: invalid account id: -1
,08-23 03:28:13.569  4142  4142 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-23 03:28:13.574  4142  4166 I Babel   : deleted: false for 0
,08-23 03:28:13.582   873  1680 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-23 03:28:13.598  4092  4092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 03:28:13.635   873  1942 I ActivityManager: Start proc 4169:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-23 03:28:13.637  4092  4092 D DockEventReceiver: finishStartingService: stopping service
,08-23 03:28:13.659  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 03:28:13.734  4142  4142 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 03:28:13.748  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 03:28:13.752  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 03:28:13.768  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 03:28:13.777  4142  4142 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 03:28:13.791   873  1681 I ActivityManager: Killing 3590:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 03:28:13.885  4169  4169 D AdapterServiceConfig: Adding HeadsetService
08-23 03:28:13.885  4169  4169 D AdapterServiceConfig: Adding A2dpService
,08-23 03:28:13.886  4169  4169 D AdapterServiceConfig: Adding HidService
08-23 03:28:13.886  4169  4169 D AdapterServiceConfig: Adding HealthService
08-23 03:28:13.886  4169  4169 D AdapterServiceConfig: Adding PanService
08-23 03:28:13.886  4169  4169 D AdapterServiceConfig: Adding GattService
08-23 03:28:13.886  4169  4169 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 03:28:13.890  4142  4142 I vclib   : onServiceConnected
08-23 03:28:13.893   873  1966 I ActivityManager: Killing 3647:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-23 03:28:13.940  4110  4131 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 03:28:13.949  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 03:28:13.987   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82ab35d:true
,08-23 03:28:14.080  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-23 03:28:14.081  1708  2503 I iu.UploadsManager: num queued entries: 0
08-23 03:28:14.081  1708  2503 I iu.UploadsManager: num updated entries: 0
,08-23 03:28:14.082  1708  2503 I iu.SyncManager: NEXT; no task
,08-23 03:28:14.085  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 03:28:14.087  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 03:28:14.103   873  1966 I ActivityManager: Start proc 4183:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-23 03:28:14.150  4183  4183 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-23 03:28:14.152  4183  4183 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:14.157  4183  4183 D SprintDMHelper: simOperator: 
08-23 03:28:14.157  4183  4183 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 03:28:14.171   873   883 I ActivityManager: Start proc 4195:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-23 03:28:14.263   873   883 I ActivityManager: Start proc 4210:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-23 03:28:14.266  4142  4209 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-23 03:28:14.270   873   884 I ActivityManager: Killing 3675:android.process.acore/u0a5 (adj 15): empty #17
,08-23 03:28:14.354  4210  4210 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-23 03:28:14.413  4210  4210 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 03:28:14.413  4210  4210 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 03:28:14.413  4210  4210 I GAv4    :   adb logcat -s GAv4
,08-23 03:28:14.431  4210  4210 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 03:28:14.438  4210  4210 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 03:28:14.474  4210  4227 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 03:28:14.583  4210  4210 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-23 03:28:14.623  4210  4210 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 03:28:14.631  4210  4210 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5184-5187)
,08-23 03:28:14.631  4210  4210 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 03:28:14.642  4210  4210 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a8d9f8e}
,08-23 03:28:14.642  4210  4210 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 03:28:14.643  4210  4210 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 03:28:14.652  4210  4210 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 03:28:14.657  4210  4210 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 03:28:14.672  4210  4210 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 03:28:14.687  4210  4210 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 03:28:14.687  4210  4210 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 03:28:14.687  4210  4210 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 03:28:14.687  4210  4210 I Adreno  : Build Date                       : 10/20/15
08-23 03:28:14.687  4210  4210 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 03:28:14.687  4210  4210 I Adreno  : Local Branch                     : M14
08-23 03:28:14.687  4210  4210 I Adreno  : Remote Branch                    : 
08-23 03:28:14.687  4210  4210 I Adreno  : Remote Branch                    : 
08-23 03:28:14.687  4210  4210 I Adreno  : Reconstruct Branch               : 
,08-23 03:28:14.750  4210  4210 I NSApplication: Starting up...
,08-23 03:28:14.762  4210  4256 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-23 03:28:14.802   873  1952 I ActivityManager: Start proc 4261:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-23 03:28:14.803   873  1952 I ActivityManager: Killing 3833:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-23 03:28:14.899  4261  4261 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-23 03:28:15.094   873  1971 I ActivityManager: Killing 3847:com.android.musicfx/u0a18 (adj 15): empty #17
,08-23 03:28:15.201   873  3273 I ActivityManager: Start proc 4275:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-23 03:28:15.286  4275  4275 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-23 03:28:15.339  4275  4275 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-23 03:28:15.406   873  1394 I ActivityManager: Killing 2150:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-23 03:28:17.710   873  3272 D WifiService: setWifiEnabled: true pid=4011, uid=10000
08-23 03:28:17.711   873  3272 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 03:28:17.723   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-23 03:28:17.734  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:17.734  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:17.734  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:17.735  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:17.738  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:17.738  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:17.739  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:17.739  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:17.742  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:17.742  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:17.743  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:17.743  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:17.755   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-23 03:28:17.756   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 03:28:17.757   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 03:28:17.758   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-23 03:28:17.758   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-23 03:28:17.758   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-23 03:28:17.759   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 03:28:17.771   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-23 03:28:17.771   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 03:28:17.774   370   871 D CommandListener: Setting iface cfg
,08-23 03:28:17.781   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-23 03:28:17.781   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 03:28:17.781   873  1305 E native  : do suspend true
,08-23 03:28:17.800   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:28:17.803   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 03:28:17.812   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 03:28:19.070   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 03:28:19.150   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.50 rxSuccessRate=8.00 delta 1000 -> 994
,08-23 03:28:19.155   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-23 03:28:19.155   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:19.160   873  1371 I ActivityManager: Killing 3799:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-23 03:28:19.179   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 03:28:19.289   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 03:28:19.292  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 03:28:19.755  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 03:28:19.823  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 03:28:19.826  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 03:28:19.834   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:28:19.853   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 03:28:19.853   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 03:28:19.853   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:19.869   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:19.882   370   871 D CommandListener: Setting iface cfg
,08-23 03:28:19.883   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-23 03:28:19.891   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 03:28:19.911   873  4310 D DhcpClient: Receive thread started
,08-23 03:28:19.995   873  1305 E native  : do suspend false
,08-23 03:28:20.004   873  2058 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 03:28:20.020   873  4310 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,08-23 03:28:20.021   873  2058 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,08-23 03:28:20.023   873  2058 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 03:28:20.056   873  4310 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 03:28:20.057   873  2058 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 03:28:20.065   370   871 D CommandListener: Setting iface cfg
,08-23 03:28:20.076   873  2058 D DhcpClient: Scheduling renewal in 86399s
,08-23 03:28:20.077   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 03:28:20.080   873  1305 E native  : do suspend true
,08-23 03:28:20.095   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 03:28:20.098   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 03:28:20.100   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 03:28:20.102   873  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-23 03:28:20.115   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 03:28:20.164   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-23 03:28:20.164   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-23 03:28:20.167   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-23 03:28:20.169   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-23 03:28:20.170   873  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-23 03:28:20.182   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 03:28:20.187   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-23 03:28:20.188   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-23 03:28:20.188   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-23 03:28:20.188   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-23 03:28:20.188   873  1307 D ConnectivityService:    accepting network in place of null
08-23 03:28:20.189   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 03:28:20.189   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 03:28:20.209   873  4309 D NetlinkSocketObserver: NeighborEvent{elapsedMs=180765, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 03:28:20.253   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:20.283   873  4308 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-23 03:28:20.289   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:20.298   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-23 03:28:20.300   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 03:28:20.303   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-23 03:28:20.305   873   890 D Tethering: MasterInitialState.processMessage what=3
08-23 03:28:20.319  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:20.319  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:28:20.320  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:20.320  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:20.325  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:20.325  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:28:20.325  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:20.325  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:20.327  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:20.327  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:28:20.327  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:20.327  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:20.338  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-23 03:28:20.359   873  4308 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 01:28:20 GMT], X-Android-Received-Millis=[1471915700359], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471915700327]}
,08-23 03:28:20.361   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-23 03:28:20.361   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-23 03:28:20.361   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-23 03:28:20.362   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-23 03:28:20.358  3963  4320 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 03:28:20.402  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:28:20.445  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 03:28:20.450  1708  2503 I iu.UploadsManager: num queued entries: 0
,08-23 03:28:20.453  1708  2503 I iu.UploadsManager: num updated entries: 0
,08-23 03:28:20.458  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 03:28:20.461  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 03:28:20.463  4183  4183 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:20.469  1708  4327 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-23 03:28:20.469  1708  4327 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 03:28:20.471  1708  4327 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 03:28:20.472  4183  4183 D SprintDMHelper: simOperator: 
,08-23 03:28:20.472  4183  4183 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 03:28:20.517  1708  2503 I iu.SyncManager: NEXT; no task
,08-23 03:28:20.533  3963  4330 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 03:28:20.597  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:28:20.598  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:28:20.632  1490  4334 I VacuumService: Vacuum at: now=1471915700605 tag=VacuumService
,08-23 03:28:20.655  4142  4329 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 03:28:20.670  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:28:20.670  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:28:20.670  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:28:20.671  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:20.748  1490  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:28:20.748  1490  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 03:28:20.748  1490  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:28:20.748  1490  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:20.768  3963  4330 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 03:28:20.769  3963  4320 E BooksSync: Soft error
08-23 03:28:20.769  3963  4320 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:28:20.769  3963  4320 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:28:20.769  3963  4320 E BooksSync: Sync error
08-23 03:28:20.769  3963  4320 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:28:20.769  3963  4320 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:28:20.769  3963  4320 I BooksSync: Finished books sync
,08-23 03:28:20.780   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160416, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:28:20.848  1490  2377 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-23 03:28:20.848  1490  2377 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 03:28:20.849  1490  2377 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:28:20.849  1490  2377 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:20.879  1708  4327 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-23 03:28:20.932  1490  4336 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-23 03:28:20.934  1490  4336 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 03:28:20.965  1490  4336 W Uploader:  no longer exists, so no auth token.
,08-23 03:28:21.298   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-23 03:28:21.519  1490  1490 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:28:21.521  1490  4343 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-23 03:28:21.827  1490  4336 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-23 03:28:21.827  1490  4336 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-23 03:28:21.827  1490  4336 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:28:21.827  1490  4336 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:21.841  1490  4336 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 03:28:21.841  1490  4336 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 03:28:21.841  1490  4336 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 03:28:22.717   873  1371 D WifiService: setWifiEnabled: false pid=4011, uid=10000
,08-23 03:28:22.717   873  1371 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 03:28:22.755  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-23 03:28:22.765   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-23 03:28:22.766   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-23 03:28:22.767   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 03:28:22.767   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:22.792   873  1305 E native  : do suspend true
,08-23 03:28:22.811   873  2058 D DhcpClient: Clearing IP address
,08-23 03:28:22.812   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-23 03:28:22.819   370   871 D CommandListener: Setting iface cfg
,08-23 03:28:22.832  1490  4333 V NativeCrypto: Read error: ssl=0x9b099600: I/O error during system call, Connection timed out
,08-23 03:28:22.839   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 03:28:22.840   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-23 03:28:22.848   394   394 E Parcel  : Reading a NULL string not supported here.
08-23 03:28:22.852   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-23 03:28:22.856   873  4310 D DhcpClient: Receive thread stopped
,08-23 03:28:22.856   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 03:28:22.857   873  1305 E native  : do suspend true
,08-23 03:28:22.863   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-23 03:28:22.863  1490  4333 V NativeCrypto: SSL shutdown failed: ssl=0x9b099600: I/O error during system call, Broken pipe
,08-23 03:28:22.898   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:22.928   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:22.930   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 03:28:22.930   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:22.930   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-23 03:28:22.936   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-23 03:28:22.940  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-23 03:28:22.944  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:22.945  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:22.945  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:22.945  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:22.947  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:22.948  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:22.948  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.948  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:22.951  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:22.951  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:22.951  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.952  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:22.954   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 03:28:22.976   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:28:22.981  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:22.981  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:22.981  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.981  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:22.981  1983  2299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-23 03:28:22.981  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:22.982  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:22.982  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:22.982  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:22.982  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:22.983  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:22.983  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:22.983  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:22.985   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-23 03:28:22.992  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-23 03:28:22.997  1708  2503 I iu.UploadsManager: num queued entries: 0
,08-23 03:28:22.999  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 03:28:23.000  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 03:28:23.001  4183  4183 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:23.005  4183  4183 D SprintDMHelper: simOperator: 
,08-23 03:28:23.005  4183  4183 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 03:28:22.997  1708  2503 I iu.UploadsManager: num updated entries: 0
,08-23 03:28:23.007  1708  2503 I iu.SyncManager: NEXT; no task
,08-23 03:28:23.011   370   871 E Netd    : netlink response contains error (No such file or directory)
,08-23 03:28:23.013   873  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-23 03:28:23.016  4142  4359 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-23 03:28:24.866  1490  4336 E Uploader: Failed to get server token: Status{statusCode=TIMEOUT, resolution=null}
,08-23 03:28:24.888  1490  4336 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-23 03:28:25.507  1490  1498 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/user/0/com.google.android.gms/databases/phenotype.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-23 03:28:27.769   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6db319e:true
08-23 03:28:27.770  4169  4169 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 03:28:27.775  4169  4169 I bt_bluedroid: init
,08-23 03:28:27.776  4169  4367 I BluetoothAdapterState: Entering OffState
,08-23 03:28:27.781  4169  4368 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-23 03:28:27.782  4169  4368 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 03:28:27.782  4169  4368 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 03:28:27.782  4169  4368 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 03:28:27.784  4169  4169 I bt_bluedroid: get_profile_interface socket
,08-23 03:28:27.787  4169  4169 I bt_bluedroid: get_profile_interface sdp
,08-23 03:28:27.790  4169  4371 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 03:28:27.792  4169  4371 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 03:28:27.792  4169  4180 I bt_bluedroid: config_hci_snoop_log
,08-23 03:28:27.794   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 03:28:27.802  4169  4367 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 03:28:27.803  4169  4367 D BluetoothAdapterProperties: Setting state to 14
08-23 03:28:27.803  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 03:28:27.808  4169  4367 D BluetoothBondStateMachine: make
,08-23 03:28:27.814  4169  4372 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 03:28:27.823  4169  4169 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 03:28:27.825  4169  4367 I BluetoothAdapterState: Entering PendingCommandState
,08-23 03:28:27.831  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:27.833  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 03:28:27.835  4169  4169 D BtGatt.GattService: Received start request. Starting profile...
,08-23 03:28:27.835  4169  4169 D BtGatt.GattService: start()
08-23 03:28:27.836  4169  4169 I bt_bluedroid: get_profile_interface gatt
,08-23 03:28:27.838  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:27.838  4169  4169 D BtGatt.AdvertiseManager: advertise manager created
,08-23 03:28:27.850  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:27.850  4169  4169 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:27.851  4169  4169 V BluetoothAdapterState: isBleTurningOn()=true
08-23 03:28:27.851  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:27.851  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-23 03:28:27.852  4169  4367 I bt_bluedroid: enable
,08-23 03:28:27.852  4169  4368 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-23 03:28:27.853  4169  4368 I bt_hci  : start_up
,08-23 03:28:27.860  4169  4368 I bt_vendor: alloc value 0xb3969189
,08-23 03:28:27.861  4169  4368 I bt_vendor: init
08-23 03:28:27.861  4169  4368 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-23 03:28:27.861  4169  4368 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 03:28:27.968  4169  4368 D bt_hci  : start_up starting async portion
,08-23 03:28:27.968  4169  4375 I bt_hci  : event_finish_startup
08-23 03:28:27.969  4169  4375 I bt_hci_h4: hal_open
08-23 03:28:27.969  4169  4375 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 03:28:27.974  4169  4375 I bt_userial_vendor: device fd = 51 open
,08-23 03:28:28.010  4169  4375 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 03:28:28.042  4169  4375 D bt_hwcfg: Chipset BCM4354A2
,08-23 03:28:28.043  4169  4375 D bt_hwcfg: Target name = [BCM4354A2]
,08-23 03:28:28.044  4169  4375 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 03:28:28.194   873  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-23 03:28:28.700  4169  4375 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 03:28:28.701  4169  4375 D bt_hwcfg: Settlement delay -- 100 ms
08-23 03:28:28.701  4169  4375 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 03:28:28.818  4169  4375 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 03:28:28.819  4169  4375 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 03:28:28.848  4169  4375 I bt_hwcfg: vendor lib fwcfg completed
,08-23 03:28:28.849  4169  4375 I bt_vendor: firmware callback
08-23 03:28:28.849  4169  4375 I bt_hci  : firmware_config_callback
,08-23 03:28:28.862  4169  4377 I bt_btu  : btu_task pending for preload complete event
,08-23 03:28:28.863  4169  4377 I bt_btu_task: Bluetooth chip preload is complete
,08-23 03:28:28.863  4169  4377 I bt_btu  : btu_task received preload complete event
,08-23 03:28:28.875  4169  4377 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 03:28:28.876  4169  4377 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 03:28:28.876  4169  4377 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 03:28:28.877  4169  4377 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 03:28:28.877  4169  4377 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 03:28:28.877  4169  4377 I         : BTE_InitTraceLevels -- TRC_A2D
,08-23 03:28:28.877  4169  4377 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 03:28:28.878  4169  4377 I         : BTE_InitTraceLevels -- TRC_BTM
,08-23 03:28:28.878  4169  4377 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 03:28:28.878  4169  4377 I         : BTE_InitTraceLevels -- TRC_PAN
,08-23 03:28:28.879  4169  4377 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 03:28:28.880  4169  4377 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 03:28:28.880  4169  4377 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 03:28:28.881  4169  4377 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-23 03:28:28.881  4169  4377 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 03:28:29.014  4169  4377 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-23 03:28:29.014  4169  4377 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-23 03:28:29.026  4169  4371 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-23 03:28:29.029  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 03:28:29.030  4169  4371 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 03:28:29.035  4169  4371 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 03:28:29.040  4169  4371 D BluetoothAdapterProperties: Scan Mode:20
,08-23 03:28:29.041  4169  4371 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 03:28:29.041  4169  4371 D bt_hci  : do_postload posting postload work item
08-23 03:28:29.042  4169  4375 I bt_hci  : event_postload
08-23 03:28:29.042  4169  4375 I bt_vendor: sco_config_cb
08-23 03:28:29.042  4169  4375 I bt_hci  : sco_config_callback postload finished.
08-23 03:28:29.044  4169  4371 D bt_bte_conf: Device ID record 1 : primary
08-23 03:28:29.045  4169  4371 D bt_bte_conf:   vendorId            = 000f
08-23 03:28:29.045  4169  4371 D bt_bte_conf:   vendorIdSource      = 0001
08-23 03:28:29.045  4169  4371 D bt_bte_conf:   product             = 1200
08-23 03:28:29.045  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:29.045  4169  4371 D bt_bte_conf:   version             = 1436
08-23 03:28:29.045  4169  4371 D bt_bte_conf:   clientExecutableURL = 
08-23 03:28:29.046  4169  4371 D bt_bte_conf:   serviceDescription  = 
08-23 03:28:29.046  4169  4371 D bt_bte_conf:   documentationURL    = 
08-23 03:28:29.046  4169  4371 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-23 03:28:29.046  4169  4368 D bt_stack_manager: event_start_up_stack finished
08-23 03:28:29.047  4169  4375 I bt_vendor: low_power_mode_cb
,08-23 03:28:29.048  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-23 03:28:29.049  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:29.049  4169  4367 D BluetoothAdapterProperties: Setting state to 15
08-23 03:28:29.049  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-23 03:28:29.050  4169  4367 I BluetoothAdapterState: Entering BleOnState
,08-23 03:28:29.054  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:29.055  4169  4367 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-23 03:28:29.056  4169  4367 D BluetoothAdapterProperties: Setting state to 11
08-23 03:28:29.056  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 03:28:29.061  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:29.063  4169  4169 D HeadsetService: Received start request. Starting profile...
,08-23 03:28:29.063  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:29.065  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:29.066  4169  4169 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 03:28:29.066  4169  4169 D HeadsetStateMachine: make
,08-23 03:28:29.067  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:29.079  4169  4367 I BluetoothAdapterState: Entering PendingCommandState
,08-23 03:28:29.083  4169  4169 D HeadsetStateMachine: max_hf_connections = 1
,08-23 03:28:29.084  4169  4169 I bt_bluedroid: get_profile_interface handsfree
,08-23 03:28:29.084  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-23 03:28:29.085  4169  4371 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-23 03:28:29.092  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:29.092  4169  4169 D A2dpService: Received start request. Starting profile...
,08-23 03:28:29.093  4169  4169 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 03:28:29.093  4169  4169 I bt_bluedroid: get_profile_interface avrcp
,08-23 03:28:29.101  4169  4169 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 03:28:29.102  4169  4169 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 03:28:29.102  4169  4169 D A2dpStateMachine: make
,08-23 03:28:29.104  4169  4169 I bt_bluedroid: get_profile_interface a2dp
,08-23 03:28:29.105  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 03:28:29.106  4169  4386 D A2dpStateMachine: Enter Disconnected: -2
,08-23 03:28:29.108  4169  4169 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 03:28:29.109  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 03:28:29.109  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
08-23 03:28:29.110  4092  4092 D BluetoothInputDevice: Proxy object connected
08-23 03:28:29.110  4169  4169 D HidService: Received start request. Starting profile...
,08-23 03:28:29.111  4169  4169 I bt_bluedroid: get_profile_interface hidhost
08-23 03:28:29.111  4169  4169 D HidService: setHidService(): set to: null
,08-23 03:28:29.111  4092  4092 D HidProfile: Bluetooth service connected
08-23 03:28:29.111  4169  4371 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
08-23 03:28:29.111  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-23 03:28:29.112  4169  4169 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 03:28:29.112  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
08-23 03:28:29.113  4169  4169 D HealthService: Received start request. Starting profile...
,08-23 03:28:29.116  4169  4169 I bt_bluedroid: get_profile_interface health
,08-23 03:28:29.116  4169  4169 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 03:28:29.117  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:29.118  4169  4169 D PanService: Received start request. Starting profile...
08-23 03:28:29.119  4169  4169 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-23 03:28:29.119  4169  4169 I bt_bluedroid: get_profile_interface pan
,08-23 03:28:29.120  4169  4371 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 03:28:29.119  4092  4092 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 03:28:29.121  4092  4092 D PanProfile: Bluetooth service connected
,08-23 03:28:29.122  4169  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:29.124  4169  4169 D BluetoothMapService: Received start request. Starting profile...
,08-23 03:28:29.124  4169  4169 D BluetoothMapService: start()
08-23 03:28:29.124  4092  4092 D BluetoothMap: Proxy object connected
08-23 03:28:29.125  4092  4092 D MapProfile: Bluetooth service connected
,08-23 03:28:29.125  4092  4092 D BluetoothMap: getConnectedDevices()
08-23 03:28:29.126  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-23 03:28:29.127  4092  4092 D BluetoothMap: Bluetooth is Not enabled
,08-23 03:28:29.127  4169  4169 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-23 03:28:29.127  4169  4169 D BluetoothMapAppObserver: createReceiver()
,08-23 03:28:29.129  4169  4169 D BluetoothMapAppObserver: initObservers()
08-23 03:28:29.129  4169  4169 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 03:28:29.136  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:29.137  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:29.137  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 03:28:29.137  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:29.138  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:29.139  4169  4169 V BluetoothAdapterState: isTurningOn()=true
,08-23 03:28:29.139  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:29.139  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:29.139  4169  4384 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:29.141  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:29.142  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:29.143  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-23 03:28:29.143  4169  4367 D BluetoothAdapterProperties: ScanMode =  20
08-23 03:28:29.143  4169  4367 D BluetoothAdapterProperties: State =  11
08-23 03:28:29.143  4169  4367 D BluetoothAdapterProperties: Setting state to 12
08-23 03:28:29.144  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 03:28:29.144  4169  4367 I BluetoothAdapterState: Entering OnState
08-23 03:28:29.144  4092  4103 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 03:28:29.146  4169  4371 D BluetoothAdapterProperties: Scan Mode:21
08-23 03:28:29.147  1920  2147 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 03:28:29.149  4169  4371 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:29.149  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:29.150  1352  1363 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 03:28:29.151   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 03:28:29.152  4092  4104 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 03:28:29.152  1352  2021 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 03:28:29.153   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 03:28:29.153  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:29.153  1352  1364 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 03:28:29.155  1352  1352 D BluetoothInputDevice: Proxy object connected
,08-23 03:28:29.155  1352  1352 D HidProfile: Bluetooth service connected
08-23 03:28:29.155   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 03:28:29.155  1352  2021 D BluetoothPan: onBluetoothStateChange on: true
08-23 03:28:29.157  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 03:28:29.157  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 03:28:29.157  1352  1352 D PanProfile: Bluetooth service connected
08-23 03:28:29.158  1352  1364 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 03:28:29.158  4169  4169 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:29.159  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:29.160  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:29.160   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 03:28:29.161  4092  4103 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 03:28:29.161  4092  4104 D BluetoothPan: onBluetoothStateChange on: true
,08-23 03:28:29.162  1352  1363 D BluetoothMap: onBluetoothStateChange: up=true,
,08-23 03:28:29.162  4169  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:29.164  4169  4169 D ObexServerSockets: Succeed to create listening sockets 
08-23 03:28:29.164  1352  1352 D BluetoothMap: Proxy object connected,
,08-23 03:28:29.164  4169  4169 D ObexServerSockets0: startAccept()
08-23 03:28:29.164  1352  1352 D MapProfile: Bluetooth service connected,
08-23 03:28:29.164  4169  4169 D ObexServerSockets0: prepareForNewConnect()
,08-23 03:28:29.164  1352  1352 D BluetoothMap: getConnectedDevices()
,08-23 03:28:29.164  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:29.167   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 03:28:29.169  4169  4169 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-23 03:28:29.169  4169  4169 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-23 03:28:29.172   873   873 D BluetoothA2dp: Proxy object connected
08-23 03:28:29.173  1352  1352 D BluetoothA2dp: Proxy object connected
08-23 03:28:29.173  4169  4393 D ObexServerSockets0: Accepting socket connection...
08-23 03:28:29.173  4169  4169 D BluetoothMapService: onReceive
08-23 03:28:29.173  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 03:28:29.174  4169  4169 D BluetoothMapService: STATE_ON
,08-23 03:28:29.175  4169  4394 D ObexServerSockets0: Accepting socket connection...
,08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:29.177  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:29.178  4092  4092 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 03:28:29.179  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:29.180  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:29.181  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:29.182  4092  4092 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-23 03:28:29.182  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:29.188  4092  4092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 03:28:29.192  4092  4092 D BluetoothA2dp: Proxy object connected
,08-23 03:28:29.195  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 03:28:29.200  4092  4092 D DockEventReceiver: finishStartingService: stopping service
,08-23 03:28:29.202  4092  4092 D BluetoothPbap: Proxy object connected
,08-23 03:28:29.202  1352  1352 D BluetoothPbap: Proxy object connected
08-23 03:28:29.202  4169  4169 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 03:28:29.202  4169  4169 D ObexServerSockets0: prepareForNewConnect()
08-23 03:28:29.202  1352  1352 D PbapServerProfile: Bluetooth service connected
,08-23 03:28:29.203  4092  4092 D PbapServerProfile: Bluetooth service connected
,08-23 03:28:29.209  4169  4400 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:29.225  4169  4404 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:29.226  4169  4404 I BtOppRfcommListener: Accept thread started.
,08-23 03:28:29.251   873   873 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.252  1920  1935 D BluetoothHeadset: Proxy object connected
08-23 03:28:29.252   873   890 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.252   873   873 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.252  1352  2021 D BluetoothHeadset: Proxy object connected
08-23 03:28:29.253  1352  1352 D HeadsetProfile: Bluetooth service connected
08-23 03:28:29.253   873   873 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.253  1352  1364 D BluetoothHeadset: Proxy object connected
08-23 03:28:29.253   873   890 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.255  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-23 03:28:29.256   873   890 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.284  4092  4103 D BluetoothHeadset: Proxy object connected
,08-23 03:28:29.285  4092  4092 D HeadsetProfile: Bluetooth service connected
,08-23 03:28:32.736  4169  4367 D BluetoothAdapterState: Current state: ON, message: 23
,08-23 03:28:32.736  4169  4367 D BluetoothAdapterProperties: Setting state to 13
,08-23 03:28:32.736  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-23 03:28:32.738  4169  4367 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 03:28:32.744  4169  4367 I BluetoothAdapterState: Entering PendingCommandState
,08-23 03:28:32.745  4169  4169 D BluetoothMapService: onReceive
,08-23 03:28:32.745  4169  4169 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-23 03:28:32.745  4169  4169 D BluetoothMapService: STATE_TURNING_OFF
08-23 03:28:32.746  4169  4169 D BluetoothMapService: MAP Service closeService in
08-23 03:28:32.746  4169  4169 D BluetoothMapMasInstance0: MAP Service shutdown
08-23 03:28:32.749  4169  4169 D ObexServerSockets0: shutdown(block = true)
,08-23 03:28:32.750  4169  4393 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-23 03:28:32.754  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:32.754  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:32.755  4169  4169 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 03:28:32.755  4169  4394 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-23 03:28:32.758  4169  4371 D BluetoothAdapterProperties: Scan Mode:20
08-23 03:28:32.758  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-23 03:28:32.761  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:32.762  4169  4169 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 03:28:32.762  4169  4380 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 03:28:32.762  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:32.763  4169  4169 D HeadsetService: Received stop request...Stopping profile...
08-23 03:28:32.765   873   873 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:32.766  1920  2195 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:32.766  4169  4169 I BtOppRfcommListener: stopping Accept Thread
08-23 03:28:32.766  4169  4404 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 03:28:32.767  4092  4104 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:32.767   873   873 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:32.767  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:32.767  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:32.767  4169  4404 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 03:28:32.768  1352  2021 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:32.768  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 03:28:32.768  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:32.768   873   873 D BluetoothHeadset: Proxy object disconnected
08-23 03:28:32.771  4169  4169 D A2dpService: Received stop request...Stopping profile...
08-23 03:28:32.771  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:32.771  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 03:28:32.771  4092  4092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 03:28:32.771  4169  4386 D A2dpStateMachine: Exit Disconnected: -1
,08-23 03:28:32.771  4011  4011 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 03:28:32.771  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:32.773  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:32.775  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:32.775   873   873 D BluetoothA2dp: Proxy object disconnected
08-23 03:28:32.776  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:32.777  4092  4092 D HeadsetProfile: Bluetooth service disconnected
,08-23 03:28:32.778  4169  4169 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:32.778  4169  4169 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:32.778  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:32.778  1352  1352 D HeadsetProfile: Bluetooth service disconnected
08-23 03:28:32.778  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:32.778  1352  1352 D BluetoothA2dp: Proxy object disconnected
08-23 03:28:32.778  4169  4169 D HidService: Received stop request...Stopping profile...
08-23 03:28:32.778  4169  4169 D HidService: Stopping Bluetooth HidService
08-23 03:28:32.780  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-23 03:28:32.780  1352  1352 D HidProfile: Bluetooth service disconnected
,08-23 03:28:32.781  4169  4169 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 03:28:32.781  4169  4169 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 03:28:32.781  4169  4377 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:32.781  4169  4377 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 03:28:32.781  4169  4377 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:32.781  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-23 03:28:32.781  4169  4371 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-23 03:28:32.782  4169  4169 D HealthService: Received stop request...Stopping profile...
,08-23 03:28:32.784  4092  4092 D DockEventReceiver: finishStartingService: stopping service
,08-23 03:28:32.785  4169  4169 D PanService: Received stop request...Stopping profile...
,08-23 03:28:32.787  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 03:28:32.787  4169  4169 D BluetoothMapService: Received stop request...Stopping profile...
08-23 03:28:32.787  1352  1352 D PanProfile: Bluetooth service disconnected
,08-23 03:28:32.787  4169  4169 D BluetoothMapService: stop()
08-23 03:28:32.787  4169  4169 D BluetoothMapAppObserver: deinitObservers()
08-23 03:28:32.787  4169  4169 D BluetoothMapAppObserver: removeReceiver()
,08-23 03:28:32.788  4092  4092 D BluetoothA2dp: Proxy object disconnected
08-23 03:28:32.788  4092  4092 D BluetoothInputDevice: Proxy object disconnected
,08-23 03:28:32.788  1352  1352 D BluetoothMap: Proxy object disconnected
08-23 03:28:32.789  1352  1352 D MapProfile: Bluetooth service disconnected
08-23 03:28:32.789  4092  4092 D HidProfile: Bluetooth service disconnected
08-23 03:28:32.789  4169  4169 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:32.789  4169  4169 V BluetoothAdapterState: isTurningOn()=false
,08-23 03:28:32.789  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:32.789  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:32.791  4092  4092 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 03:28:32.791  4092  4092 D PanProfile: Bluetooth service disconnected
,08-23 03:28:32.791  4169  4377 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:32.792  4169  4377 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 03:28:32.792  4092  4092 D BluetoothMap: Proxy object disconnected,
08-23 03:28:32.792  4092  4092 D MapProfile: Bluetooth service disconnected
08-23 03:28:32.792  4169  4377 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 03:28:32.792  4169  4377 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-23 03:28:32.792  4169  4377 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
,08-23 03:28:32.792  4169  4377 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-23 03:28:32.792  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-23 03:28:32.797  4169  4169 V BluetoothAdapterState: isTurningOff()=true
,08-23 03:28:32.797  4169  4169 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:32.797  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 03:28:32.797  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:32.797  4169  4169 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 03:28:32.797  4169  4169 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 03:28:32.798  4169  4371 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 03:28:32.798  4169  4169 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:32.798  4169  4169 V BluetoothAdapterState: isTurningOn()=false
,08-23 03:28:32.798  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:32.798  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:32.798  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 03:28:32.798  4169  4169 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-23 03:28:32.799  4169  4371 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-23 03:28:32.799  4169  4169 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-23 03:28:32.799  4169  4169 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:32.799  4169  4169 V BluetoothAdapterState: isTurningOn()=false
,08-23 03:28:32.799  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:32.799  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:32.800  4169  4169 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 03:28:32.801  4169  4169 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-23 03:28:32.801  4169  4169 D BluetoothMapService: MAP Service closeService in
,08-23 03:28:32.802  4169  4169 V BluetoothAdapterState: isTurningOff()=true
08-23 03:28:32.802  4169  4169 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:32.802  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:32.802  4169  4169 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:32.802  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 03:28:32.802  4169  4367 D BluetoothAdapterProperties: Setting state to 15
08-23 03:28:32.802  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-23 03:28:32.803  4169  4367 I BluetoothAdapterState: Entering BleOnState
08-23 03:28:32.803  4169  4169 D BluetoothMapService: cleanup()
08-23 03:28:32.803  4092  4103 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 03:28:32.803  4169  4169 D BluetoothMapService: MAP Service closeService in
,08-23 03:28:32.805  4092  4104 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:32.805  1920  2065 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:32.805  1352  2021 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 03:28:32.806   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 03:28:32.806  4092  4103 D BluetoothMap: onBluetoothStateChange: up=false
08-23 03:28:32.807  1352  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:32.808   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:32.808  1352  1363 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 03:28:32.812  4092  4104 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 03:28:32.812   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 03:28:32.812  1352  2021 D BluetoothPan: onBluetoothStateChange on: false
08-23 03:28:32.813  1352  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 03:28:32.813   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 03:28:32.814  4092  4103 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 03:28:32.814  4092  4104 D BluetoothPan: onBluetoothStateChange on: false
08-23 03:28:32.814  1352  1363 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 03:28:32.815  4169  4367 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-23 03:28:32.815  4169  4367 D BluetoothAdapterProperties: Setting state to 16
,08-23 03:28:32.815  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-23 03:28:32.816  4169  4367 D BluetoothAdapterProperties: onBleDisable
08-23 03:28:32.817  4169  4368 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 03:28:32.818  4169  4377 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-23 03:28:32.818  4169  4377 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 03:28:32.817  4169  4367 I BluetoothAdapterState: Entering PendingCommandState
08-23 03:28:32.818  4092  4092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 03:28:32.819  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:32.820  4169  4371 D BluetoothAdapterProperties: Scan Mode:20
,08-23 03:28:32.821  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:32.824  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:32.824  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 03:28:32.825  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:32.828  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:32.829  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:32.841  4092  4092 D DockEventReceiver: finishStartingService: stopping service
,08-23 03:28:33.026  4169  4371 I bt_hci  : shut_down
,08-23 03:28:33.038  4169  4375 D bt_hwcfg: hw_epilog_process
,08-23 03:28:33.039  4169  4375 I bt_vendor: low_power_mode_cb
,08-23 03:28:33.067  4169  4375 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 03:28:33.067  4169  4375 I bt_vendor: epilog_cb
,08-23 03:28:33.067  4169  4375 I bt_hci  : epilog_finished_callback
,08-23 03:28:33.076  4169  4371 I bt_hci_h4: hal_close
,08-23 03:28:33.078  4169  4371 I bt_userial_vendor: device fd = 51 close
,08-23 03:28:33.205  4169  4368 D bt_stack_manager: event_shut_down_stack finished.
,08-23 03:28:33.206  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 03:28:33.212  4169  4367 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 03:28:33.213  4169  4169 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 03:28:33.215  4169  4169 D BtGatt.GattService: Received stop request...Stopping profile...
,08-23 03:28:33.215  4169  4169 D BtGatt.GattService: stop()
08-23 03:28:33.216  4169  4169 D BtGatt.AdvertiseManager: advertise clients cleared
,08-23 03:28:33.220  4169  4169 V BluetoothAdapterState: isTurningOff()=false
,08-23 03:28:33.221  4169  4169 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:33.221  4169  4169 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:33.221  4169  4169 V BluetoothAdapterState: isBleTurningOff()=true
08-23 03:28:33.222  4169  4367 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-23 03:28:33.223  4169  4367 D BluetoothAdapterProperties: Setting state to 10
08-23 03:28:33.223  4169  4367 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-23 03:28:33.225  4169  4367 I BluetoothAdapterState: Entering OffState
,08-23 03:28:33.227   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 03:28:33.256  4169  4169 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-23 03:28:33.257  4169  4169 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 03:28:33.257  4169  4368 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-23 03:28:33.264  4169  4368 D bt_stack_manager: event_clean_up_stack finished.
,08-23 03:28:33.265  4169  4169 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 03:28:33.269  4169  4169 I art     : System.exit called, status: 0
08-23 03:28:33.270  4169  4169 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 03:28:33.328   873   884 I ActivityManager: Process com.android.bluetooth (pid 4169) has died
,08-23 03:28:37.732  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:37.733  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:37.737  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:37.738  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@49695f removed from the list
08-23 03:28:37.738  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:37.739  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:37.739  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:37.742  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 03:28:37.742  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7797475 added. We now have 4 listener(s)
08-23 03:28:37.743  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:28:37.744  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:37.745  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7797475 removed from the list
08-23 03:28:37.745  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:37.745  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:37.746  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:37.748  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:28:37.748  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b06c0a added. We now have 4 listener(s)
08-23 03:28:37.748  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:28:42.761  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:42.806   873   890 I ActivityManager: Start proc 4414:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-23 03:28:42.969  4414  4414 D AdapterServiceConfig: Adding HeadsetService
,08-23 03:28:42.970  4414  4414 D AdapterServiceConfig: Adding A2dpService
08-23 03:28:42.971  4414  4414 D AdapterServiceConfig: Adding HidService
,08-23 03:28:42.972  4414  4414 D AdapterServiceConfig: Adding HealthService
,08-23 03:28:42.973  4414  4414 D AdapterServiceConfig: Adding PanService
,08-23 03:28:42.974  4414  4414 D AdapterServiceConfig: Adding GattService
08-23 03:28:42.975  4414  4414 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 03:28:43.000   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99570e3:true
,08-23 03:28:43.002  4414  4414 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 03:28:43.009  4414  4414 I bt_bluedroid: init
,08-23 03:28:43.009  4414  4426 I BluetoothAdapterState: Entering OffState
,08-23 03:28:43.014  4414  4427 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 03:28:43.014  4414  4427 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 03:28:43.014  4414  4427 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 03:28:43.014  4414  4427 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 03:28:43.015  4414  4414 I bt_bluedroid: get_profile_interface socket
,08-23 03:28:43.020  4414  4414 I bt_bluedroid: get_profile_interface sdp
,08-23 03:28:43.023  4414  4430 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 03:28:43.027  4414  4430 D BluetoothAdapterProperties: Name is: Nexus 6
08-23 03:28:43.027  4414  4425 I bt_bluedroid: config_hci_snoop_log
,08-23 03:28:43.031   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 03:28:43.043  4414  4426 D BluetoothAdapterState: Current state: OFF, message: 0
08-23 03:28:43.044  4414  4426 D BluetoothAdapterProperties: Setting state to 14
,08-23 03:28:43.044  4414  4426 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 03:28:43.049  4414  4426 D BluetoothBondStateMachine: make
,08-23 03:28:43.054  4414  4431 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 03:28:43.062  4414  4426 I BluetoothAdapterState: Entering PendingCommandState
,08-23 03:28:43.064  4414  4414 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 03:28:43.073  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:43.075  4414  4414 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 03:28:43.077  4414  4414 D BtGatt.GattService: Received start request. Starting profile...
,08-23 03:28:43.078  4414  4414 D BtGatt.GattService: start()
08-23 03:28:43.078  4414  4414 I bt_bluedroid: get_profile_interface gatt
,08-23 03:28:43.081  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
08-23 03:28:43.081  4414  4414 D BtGatt.AdvertiseManager: advertise manager created
,08-23 03:28:43.100  4414  4414 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:43.100  4414  4414 V BluetoothAdapterState: isTurningOn()=false
08-23 03:28:43.101  4414  4414 V BluetoothAdapterState: isBleTurningOn()=true
08-23 03:28:43.101  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:43.101  4414  4426 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-23 03:28:43.102  4414  4426 I bt_bluedroid: enable
08-23 03:28:43.102  4414  4427 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-23 03:28:43.105  4414  4427 I bt_hci  : start_up
,08-23 03:28:43.123  4414  4427 I bt_vendor: alloc value 0xb39c7189
08-23 03:28:43.123  4414  4427 I bt_vendor: init
08-23 03:28:43.123  4414  4427 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-23 03:28:43.123  4414  4427 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 03:28:43.232  4414  4427 D bt_hci  : start_up starting async portion
08-23 03:28:43.232  4414  4434 I bt_hci  : event_finish_startup
08-23 03:28:43.232  4414  4434 I bt_hci_h4: hal_open
08-23 03:28:43.233  4414  4434 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 03:28:43.242  4414  4434 I bt_userial_vendor: device fd = 51 open
,08-23 03:28:43.274  4414  4434 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 03:28:43.306  4414  4434 D bt_hwcfg: Chipset BCM4354A2
,08-23 03:28:43.307  4414  4434 D bt_hwcfg: Target name = [BCM4354A2]
08-23 03:28:43.308  4414  4434 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 03:28:43.962  4414  4434 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 03:28:43.963  4414  4434 D bt_hwcfg: Settlement delay -- 100 ms
08-23 03:28:43.964  4414  4434 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 03:28:44.080  4414  4434 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 03:28:44.082  4414  4434 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 03:28:44.111  4414  4434 I bt_hwcfg: vendor lib fwcfg completed
,08-23 03:28:44.112  4414  4434 I bt_vendor: firmware callback
08-23 03:28:44.112  4414  4434 I bt_hci  : firmware_config_callback
,08-23 03:28:44.123  4414  4436 I bt_btu  : btu_task pending for preload complete event
,08-23 03:28:44.124  4414  4436 I bt_btu_task: Bluetooth chip preload is complete
,08-23 03:28:44.124  4414  4436 I bt_btu  : btu_task received preload complete event
,08-23 03:28:44.135  4414  4436 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 03:28:44.135  4414  4436 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-23 03:28:44.136  4414  4436 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 03:28:44.136  4414  4436 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 03:28:44.136  4414  4436 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 03:28:44.137  4414  4436 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 03:28:44.137  4414  4436 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 03:28:44.137  4414  4436 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 03:28:44.138  4414  4436 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 03:28:44.138  4414  4436 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 03:28:44.139  4414  4436 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 03:28:44.140  4414  4436 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 03:28:44.140  4414  4436 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 03:28:44.140  4414  4436 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 03:28:44.141  4414  4436 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 03:28:44.275  4414  4436 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3944d9d
,08-23 03:28:44.275  4414  4436 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3944d9d 
,08-23 03:28:44.302  4414  4430 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 03:28:44.303  4414  4430 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 03:28:44.304  4414  4430 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 03:28:44.306  4414  4430 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 03:28:44.308  4414  4430 D BluetoothAdapterProperties: Scan Mode:20
,08-23 03:28:44.310  4414  4430 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 03:28:44.310  4414  4430 D bt_hci  : do_postload posting postload work item
,08-23 03:28:44.311  4414  4434 I bt_hci  : event_postload
08-23 03:28:44.311  4414  4434 I bt_vendor: sco_config_cb
08-23 03:28:44.311  4414  4434 I bt_hci  : sco_config_callback postload finished.
,08-23 03:28:44.312  4414  4430 D bt_bte_conf: Device ID record 1 : primary
,08-23 03:28:44.312  4414  4430 D bt_bte_conf:   vendorId            = 000f,
,08-23 03:28:44.312  4414  4430 D bt_bte_conf:   vendorIdSource      = 0001
,08-23 03:28:44.313  4414  4430 D bt_bte_conf:   product             = 1200
08-23 03:28:44.313  4414  4430 D bt_bte_conf:   version             = 1436
,08-23 03:28:44.313  4414  4430 D bt_bte_conf:   clientExecutableURL = 
08-23 03:28:44.313  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:44.314  4414  4430 D bt_bte_conf:   serviceDescription  = 
,08-23 03:28:44.314  4414  4430 D bt_bte_conf:   documentationURL    = 
08-23 03:28:44.314  4414  4430 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-23 03:28:44.317  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:44.317  4414  4427 D bt_stack_manager: event_start_up_stack finished
08-23 03:28:44.318  4414  4434 I bt_vendor: low_power_mode_cb
,08-23 03:28:44.318  4414  4426 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-23 03:28:44.319  4414  4426 D BluetoothAdapterProperties: Setting state to 15
,08-23 03:28:44.319  4414  4426 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-23 03:28:44.320  4414  4426 I BluetoothAdapterState: Entering BleOnState
,08-23 03:28:44.328  4414  4426 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-23 03:28:44.328  4414  4426 D BluetoothAdapterProperties: Setting state to 11
,08-23 03:28:44.328  4414  4426 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 03:28:44.338  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:44.339  4414  4414 D HeadsetService: Received start request. Starting profile...
,08-23 03:28:44.343  4414  4414 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 03:28:44.344  4414  4414 D HeadsetStateMachine: make
,08-23 03:28:44.348  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:44.352  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-23 03:28:44.355  4414  4414 D HeadsetStateMachine: max_hf_connections = 1
,08-23 03:28:44.355  4414  4414 I bt_bluedroid: get_profile_interface handsfree
08-23 03:28:44.355  4414  4430 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-23 03:28:44.356  4414  4430 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-23 03:28:44.361  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 03:28:44.362  4414  4426 I BluetoothAdapterState: Entering PendingCommandState
,08-23 03:28:44.363  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:44.364  4414  4414 D A2dpService: Received start request. Starting profile...
08-23 03:28:44.364  4414  4414 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 03:28:44.365  4414  4414 I bt_bluedroid: get_profile_interface avrcp
,08-23 03:28:44.370  4414  4414 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 03:28:44.371  4414  4414 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-23 03:28:44.371  4414  4414 D A2dpStateMachine: make
,08-23 03:28:44.372  4414  4414 I bt_bluedroid: get_profile_interface a2dp
,08-23 03:28:44.372  4414  4430 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 03:28:44.375  4414  4445 D A2dpStateMachine: Enter Disconnected: -2
,08-23 03:28:44.377  4414  4414 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 03:28:44.378  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:44.379  4414  4414 D HidService: Received start request. Starting profile...
,08-23 03:28:44.380  4414  4414 I bt_bluedroid: get_profile_interface hidhost
,08-23 03:28:44.380  4414  4430 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39263e5
08-23 03:28:44.380  4414  4430 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-23 03:28:44.381  4414  4414 D HidService: setHidService(): set to: null
,08-23 03:28:44.382  4414  4414 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 03:28:44.383  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
08-23 03:28:44.383  4414  4414 D HealthService: Received start request. Starting profile...
,08-23 03:28:44.384  4414  4414 I bt_bluedroid: get_profile_interface health
,08-23 03:28:44.385  4414  4414 V BluetoothAdapterState: isTurningOff()=false
,08-23 03:28:44.385  4414  4414 V BluetoothAdapterState: isTurningOn()=true
,08-23 03:28:44.385  4414  4414 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 03:28:44.385  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:44.387  4414  4442 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-23 03:28:44.387  4414  4414 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 03:28:44.388  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:44.388  4414  4414 D PanService: Received start request. Starting profile...
,08-23 03:28:44.388  4414  4414 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-23 03:28:44.388  4414  4414 I bt_bluedroid: get_profile_interface pan
,08-23 03:28:44.389  4414  4430 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 03:28:44.392  4414  4414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:28:44.393  4414  4414 D BluetoothMapService: Received start request. Starting profile...
,08-23 03:28:44.393  4414  4414 D BluetoothMapService: start()
,08-23 03:28:44.395  4414  4414 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-23 03:28:44.396  4414  4414 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-23 03:28:44.396  4414  4414 D BluetoothMapAppObserver: createReceiver()
,08-23 03:28:44.397  4414  4414 D BluetoothMapAppObserver: initObservers()
,08-23 03:28:44.397  4414  4414 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isTurningOff()=false
,08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isTurningOn()=true
,08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:44.403  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:44.404  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 03:28:44.405  4414  4414 V BluetoothAdapterState: isTurningOff()=false
08-23 03:28:44.405  4414  4414 V BluetoothAdapterState: isTurningOn()=true
08-23 03:28:44.405  4414  4414 V BluetoothAdapterState: isBleTurningOn()=false
08-23 03:28:44.405  4414  4414 V BluetoothAdapterState: isBleTurningOff()=false
08-23 03:28:44.406  4414  4426 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-23 03:28:44.406  4414  4426 D BluetoothAdapterProperties: ScanMode =  20
08-23 03:28:44.406  4414  4426 D BluetoothAdapterProperties: State =  11
,08-23 03:28:44.406  4414  4426 D BluetoothAdapterProperties: Setting state to 12
08-23 03:28:44.406  4414  4426 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 03:28:44.406  4414  4426 I BluetoothAdapterState: Entering OnState
08-23 03:28:44.407  4092  4104 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 03:28:44.407  4414  4430 D BluetoothAdapterProperties: Scan Mode:21
08-23 03:28:44.407  4414  4430 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 03:28:44.409  4092  4103 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 03:28:44.410  1920  2065 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:44.410  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:44.411  1352  1364 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 03:28:44.412  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 03:28:44.413   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 03:28:44.414  4092  4104 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:44.415  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:44.416  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:44.417  1352  1363 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 03:28:44.417  4092  4092 D BluetoothMap: Proxy object connected
08-23 03:28:44.417  4092  4092 D MapProfile: Bluetooth service connected
08-23 03:28:44.417  4092  4092 D BluetoothMap: getConnectedDevices()
,08-23 03:28:44.417   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 03:28:44.417  1352  2021 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 03:28:44.418  4092  4104 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 03:28:44.419  1352  1352 D BluetoothInputDevice: Proxy object connected
08-23 03:28:44.419  1352  1352 D HidProfile: Bluetooth service connected
,08-23 03:28:44.421   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 03:28:44.422  1352  1363 D BluetoothPan: onBluetoothStateChange on: true
08-23 03:28:44.422  4092  4092 D BluetoothA2dp: Proxy object connected
,08-23 03:28:44.422  4414  4414 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 03:28:44.422  4414  4414 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-23 03:28:44.423  1352  2021 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 03:28:44.423  4414  4414 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 03:28:44.424  1352  1352 D BluetoothA2dp: Proxy object connected
,08-23 03:28:44.424   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 03:28:44.425   873   873 D BluetoothA2dp: Proxy object connected
08-23 03:28:44.426  4092  4104 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 03:28:44.428  4414  4414 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:44.429  4092  4092 D BluetoothInputDevice: Proxy object connected
,08-23 03:28:44.429  4092  4103 D BluetoothPan: onBluetoothStateChange on: true
,08-23 03:28:44.429  4414  4414 D ObexServerSockets: Succeed to create listening sockets 
08-23 03:28:44.430  4414  4414 D ObexServerSockets0: startAccept()
08-23 03:28:44.429  4092  4092 D HidProfile: Bluetooth service connected
,08-23 03:28:44.430  4414  4414 D ObexServerSockets0: prepareForNewConnect()
,08-23 03:28:44.432  4414  4414 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-23 03:28:44.432  4414  4414 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-23 03:28:44.433  4414  4451 D ObexServerSockets0: Accepting socket connection...
08-23 03:28:44.433  4414  4452 D ObexServerSockets0: Accepting socket connection...
,08-23 03:28:44.435  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 03:28:44.435  1352  1352 D PanProfile: Bluetooth service connected
08-23 03:28:44.435  1352  2021 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 03:28:44.436  1352  1352 D BluetoothMap: Proxy object connected
,08-23 03:28:44.437  1352  1352 D MapProfile: Bluetooth service connected
08-23 03:28:44.437  1352  1352 D BluetoothMap: getConnectedDevices()
08-23 03:28:44.437  4092  4092 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 03:28:44.437  4092  4092 D PanProfile: Bluetooth service connected
,08-23 03:28:44.438   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 03:28:44.439  4414  4414 D BluetoothMapService: onReceive
08-23 03:28:44.439  4414  4414 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 03:28:44.439  4414  4414 D BluetoothMapService: STATE_ON
08-23 03:28:44.439  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:28:44.440  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:44.444  4092  4092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 03:28:44.449  1490  1490 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 03:28:44.452  4092  4092 D DockEventReceiver: finishStartingService: stopping service
,08-23 03:28:44.455  4092  4092 D BluetoothPbap: Proxy object connected
,08-23 03:28:44.455  4092  4092 D PbapServerProfile: Bluetooth service connected
,08-23 03:28:44.462  1352  1352 D BluetoothPbap: Proxy object connected
08-23 03:28:44.462  1352  1352 D PbapServerProfile: Bluetooth service connected
,08-23 03:28:44.464  4414  4457 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:44.469  4414  4414 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 03:28:44.469  4414  4414 D ObexServerSockets0: prepareForNewConnect()
,08-23 03:28:44.473  4414  4461 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:28:44.474  4414  4461 I BtOppRfcommListener: Accept thread started.
,08-23 03:28:44.511   873   873 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.511  1920  1934 D BluetoothHeadset: Proxy object connected
08-23 03:28:44.511  4092  4104 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.512   873   873 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.512  4092  4092 D HeadsetProfile: Bluetooth service connected
,08-23 03:28:44.512  1352  1364 D BluetoothHeadset: Proxy object connected
08-23 03:28:44.512  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-23 03:28:44.512   873   873 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.513   873   890 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.517  1352  1363 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.517  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-23 03:28:44.517   873   890 D BluetoothHeadset: Proxy object connected
,08-23 03:28:44.521   873   890 D BluetoothHeadset: Proxy object connected
,08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:47.780  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:47.786  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:47.787  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:28:47.788  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b06c0a removed from the list
,08-23 03:28:47.788  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:28:47.788  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:28:47.789  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:28:47.791  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:28:47.792  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c53c7b added. We now have 4 listener(s)
,08-23 03:28:47.792  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:28:47.796   873  1971 D WifiService: setWifiEnabled: false pid=4011, uid=10000
08-23 03:28:47.796   873  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 03:28:49.756  1858  1887 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-23 03:28:49.756  1858  1887 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-23 03:28:49.815  1490  1490 I ConfigService: onCreate
,08-23 03:28:52.808  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:28:52.809   873  1680 D WifiService: setWifiEnabled: true pid=4011, uid=10000
08-23 03:28:52.809   873  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 03:28:52.825   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:52.841  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:52.847  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 03:28:52.855  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 03:28:52.859  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 03:28:52.864   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-23 03:28:52.865   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 03:28:52.866   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 03:28:52.867   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-23 03:28:52.867   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-23 03:28:52.867   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-23 03:28:52.867   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 03:28:52.882   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 03:28:52.883   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 03:28:52.884   370   871 D CommandListener: Setting iface cfg
,08-23 03:28:52.936   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-23 03:28:52.936   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 03:28:52.939   873  1305 E native  : do suspend true
,08-23 03:28:52.955   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:28:52.970   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 03:28:52.977   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 03:28:54.226   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-23 03:28:54.394   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=10.25 delta 1000 -> 994
,08-23 03:28:54.395   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-23 03:28:54.395   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:54.413   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 03:28:54.463   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 03:28:54.469  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 03:28:54.892  1490  1490 I ConfigService: onDestroy
,08-23 03:28:54.905  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 03:28:54.947  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 03:28:54.949  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 03:28:54.958   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 03:28:54.970   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 03:28:54.970   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 03:28:54.971   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 03:28:54.985   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 03:28:55.000   370   871 D CommandListener: Setting iface cfg
08-23 03:28:55.002   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-23 03:28:55.021   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 03:28:55.030   873  4472 D DhcpClient: Receive thread started
,08-23 03:28:55.128   873  1305 E native  : do suspend false
,08-23 03:28:55.154   873  2058 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 03:28:55.170   873  4472 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-23 03:28:55.172   873  2058 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-23 03:28:55.175   873  2058 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 03:28:55.188   873  4472 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 03:28:55.189   873  2058 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 03:28:55.195   370   871 D CommandListener: Setting iface cfg
,08-23 03:28:55.209   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 03:28:55.210   873  2058 D DhcpClient: Scheduling renewal in 86399s
,08-23 03:28:55.212   873  1305 E native  : do suspend true
,08-23 03:28:55.233   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 03:28:55.236   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 03:28:55.237   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 03:28:55.240   873  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-23 03:28:55.243   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 03:28:55.307   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 03:28:55.307   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-23 03:28:55.311   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-23 03:28:55.316   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-23 03:28:55.321   873  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-23 03:28:55.343   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 03:28:55.354   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-23 03:28:55.355   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-23 03:28:55.355   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-23 03:28:55.355   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 03:28:55.356   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-23 03:28:55.356   873  1307 D ConnectivityService:    accepting network in place of null
,08-23 03:28:55.357   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 03:28:55.376   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=215932, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 03:28:55.388   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:55.416   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 03:28:55.427   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-23 03:28:55.427   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:55.432   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-23 03:28:55.432   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:55.446  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:55.449  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:55.452   873  4470 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:55.455  4011  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:55.455  2002  2002 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-23 03:28:55.457  4011  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:55.518  1708  1708 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 03:28:55.527  1708  2503 I iu.UploadsManager: num queued entries: 0
,08-23 03:28:55.528  1708  4484 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-23 03:28:55.529  1708  4484 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 03:28:55.530  1708  4484 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 03:28:55.531  1708  1708 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 03:28:55.532  1708  1708 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 03:28:55.535  4183  4183 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 03:28:55.539  1708  2503 I iu.UploadsManager: num updated entries: 0
08-23 03:28:55.539   873  4470 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 01:28:55 GMT], X-Android-Received-Millis=[1471915735539], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471915735508]}
,08-23 03:28:55.540  1708  2503 I iu.SyncManager: NEXT; no task
,08-23 03:28:55.540  4183  4183 D SprintDMHelper: simOperator: 
08-23 03:28:55.540  4183  4183 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 03:28:55.542   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-23 03:28:55.542   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-23 03:28:55.543   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 03:28:55.546  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:28:55.548   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-23 03:28:55.548  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:28:55.674  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-23 03:28:55.674  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 03:28:55.674  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:28:55.674  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:55.697  3732  4489 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 03:28:55.697  3732  4489 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at blb.a(PG:3937)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at czp.a(PG:18188)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:28:55.697  3732  4489 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	... 12 more
08-23 03:28:55.697  3732  4489 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at fal.a(PG:38)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:28:55.697  3732  4489 E HttpOperation: 	... 14 more
,08-23 03:28:55.701  3963  4490 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 03:28:55.785  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 03:28:55.785  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 03:28:55.785  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:28:55.785  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-23 03:28:55.788  4142  4491 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 03:28:55.819  3732  4489 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 03:28:55.819  3732  4489 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at hec.a(PG:42)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at hee.a(PG:102)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at czr.a(PG:65)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at kka.a(PG:108)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	,at czp.a(PG:19176)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:28:55.819  3732  4489 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	... 15 more
08-23 03:28:55.819  3732  4489 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at fal.a(PG:38)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:28:55.819  3732  4489 E HttpOperation: 	... 17 more
08-23 03:28:55.819  3732  4489 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 03:28:55.819  3732  4489 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at hec.a(PG:42)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at hee.a(PG:102)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at czr.a(PG:65)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at kka.a(PG:108)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	... 15 more
08-23 03:28:55.819  3732  4489 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at fal.a(PG:38)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 03:28:55.819  3732  4489 E ExperimentLoader: 	... 17 more
,08-23 03:28:55.845  3963  4497 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 03:28:55.892  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:28:55.892  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:28:55.892  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:28:55.892  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:55.937  1490  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:28:55.937  1490  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:28:55.937  1490  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:28:55.937  1490  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:55.946  1490  2377 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-23 03:28:55.946  1490  2377 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 03:28:55.946  1490  2377 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:28:55.946  1490  2377 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:28:55.956  3963  4497 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 03:28:55.957  3963  4490 E BooksSync: Soft error
08-23 03:28:55.957  3963  4490 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:28:55.957  3963  4490 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:28:55.958  3963  4490 E BooksSync: Sync error
08-23 03:28:55.958  3963  4490 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:28:55.958  3963  4490 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 03:28:55.958  3963  4490 I BooksSync: Finished books sync
,08-23 03:28:55.979   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 214328, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:28:55.984  1708  4484 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-23 03:28:56.006   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 195116, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:28:56.423   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:28:57.839  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:28:57.846  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:28:57.847  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:28:57.847  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c53c7b removed from the list
,08-23 03:28:57.847  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:28:57.848  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:28:57.848  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:28:57.860  4011  4499 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-23 03:28:57.860  4011  4499 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 03:29:00.867  4011  4500 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-23 03:29:00.869  4011  4500 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-23 03:29:00.869  4011  4499 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-23 03:29:00.869  4011  4499 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-23 03:29:00.870  4011  4500 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-23 03:29:00.871  4011  4499 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 03:29:00.871  4011  4500 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 03:29:00.873  4011  4500 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-23 03:29:00.875  4011  4502 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: IncomingSocketThread/Sender)
08-23 03:29:00.875  4011  4499 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-23 03:29:00.878  4011  4499 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-23 03:29:00.882  4011  4503 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: IncomingSocketThread/Receiver)
,08-23 03:29:00.884  4011  4503 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 467, thread name: IncomingSocketThread/Receiver)
,08-23 03:29:00.884  4011  4503 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-23 03:29:00.885  4011  4503 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-23 03:29:00.885  4011  4504 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: OutgoingSocketThread/Sender)
08-23 03:29:00.886  4011  4505 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: OutgoingSocketThread/Receiver)
,08-23 03:29:00.888  4011  4505 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 468, thread name: OutgoingSocketThread/Receiver)
08-23 03:29:00.889  4011  4505 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-23 03:29:00.889  4011  4505 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-23 03:29:03.362   873  1307 D ConnectivityService: handlePromptUnvalidated 102
,08-23 03:29:03.867  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 03:29:03.869  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 03:29:03.876  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@39eb0a0 Bundle[{}]
,08-23 03:29:03.876  4011  4062 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 03:29:03.876  4011  4062 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 03:29:03.877  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-23 03:29:03.877  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 03:29:03.878  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 03:29:03.878  4011  4062 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 03:29:03.882  4011  4062 I System.out: Running OutgoingSocketThread
,08-23 03:29:03.886  4011  4506 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-23 03:29:03.886  4011  4506 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 03:29:06.895  4011  4507 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-23 03:29:06.895  4011  4507 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-23 03:29:06.896  4011  4507 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 03:29:06.896  4011  4506 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-23 03:29:06.897  4011  4506 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-23 03:29:06.897  4011  4507 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 03:29:06.897  4011  4506 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 03:29:06.900  4011  4507 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-23 03:29:06.902  4011  4509 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 477, name: IncomingSocketThread/Sender)
,08-23 03:29:06.904  4011  4506 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-23 03:29:06.907  4011  4506 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-23 03:29:06.909  4011  4510 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 478, name: IncomingSocketThread/Receiver)
,08-23 03:29:06.911  4011  4510 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 478, thread name: IncomingSocketThread/Receiver)
08-23 03:29:06.911  4011  4510 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-23 03:29:06.911  4011  4510 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 478, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-23 03:29:06.912  4011  4511 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 479, name: OutgoingSocketThread/Sender)
,08-23 03:29:06.915  4011  4512 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 480, name: OutgoingSocketThread/Receiver)
,08-23 03:29:06.916  4011  4512 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 480, thread name: OutgoingSocketThread/Receiver)
08-23 03:29:06.917  4011  4512 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-23 03:29:06.917  4011  4512 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 480, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-23 03:29:09.898  4011  4062 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 489)
,08-23 03:29:09.900  4011  4062 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-23 03:29:09.900  4011  4062 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 490)
,08-23 03:29:09.906  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 03:29:09.906  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a6a98 added. We now have 3 listener(s)
08-23 03:29:09.908  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 03:29:09.908  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 03:29:09.908  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:29:09.908  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:29:09.909  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f9e2f1 added. We now have 4 listener(s)
08-23 03:29:09.909  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:29:09.909  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 03:29:09.913  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:29:09.928  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:29:09.934  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:09.934  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:29:09.934  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:29:09.934  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:29:09.935  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:29:09.935  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:09.935  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 03:29:09.935  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:29:09.935  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 03:29:09.935  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a6a98 removed from the list
08-23 03:29:09.935  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:09.935  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f9e2f1 removed from the list
,08-23 03:29:09.942  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:29:09.950  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:29:09.951  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:29:09.951  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:09.952  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:09.952  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:09.955  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:29:09.956  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:29:09.956  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:09.956  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f9e2f1 not in the list
,08-23 03:29:09.957  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:09.957  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:09.960  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:29:09.960  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:29:09.960  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:29:09.961  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f9e2f1 not in the list
08-23 03:29:09.961  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:29:09.961  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:09.961  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:09.962  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a6a98 not in the list
08-23 03:29:09.964  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 03:29:09.964  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1612557 added. We now have 3 listener(s)
,08-23 03:29:09.971  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 03:29:09.971  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:29:09.972  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:29:09.972  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:29:09.972  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8079844 added. We now have 4 listener(s)
08-23 03:29:09.972  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:29:09.973  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:29:09.978  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:29:09.990  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:29:09.996  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:29:09.996  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:29:09.996  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 03:29:09.996  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 03:29:09.996  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 03:29:09.997  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:29:09.997  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 03:29:10.003  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 03:29:10.003  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 03:29:10.005  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:29:10.010  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:29:10.010  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 03:29:10.011  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 03:29:10.011  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 03:29:10.017  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 03:29:10.017  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 03:29:10.017  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 03:29:10.018  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:29:10.025  4414  4443 D BtGatt.GattService: registerClient() - UUID=32250f54-31a8-4f70-a802-0979a3810e02
,08-23 03:29:10.028  4414  4430 D BtGatt.GattService: onClientRegistered() - UUID=32250f54-31a8-4f70-a802-0979a3810e02, clientIf=5
,08-23 03:29:10.029  4011  4022 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 03:29:10.032  4414  4453 D BtGatt.GattService: start scan with filters
,08-23 03:29:10.041  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 03:29:10.041  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 03:29:10.041  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 03:29:10.042  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 03:29:10.042  4414  4433 D BtGatt.ScanManager: handling starting scan
,08-23 03:29:10.047  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 03:29:10.047  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 03:29:10.047  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 03:29:10.049  4414  4433 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8857534
,08-23 03:29:10.049  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 03:29:10.053  4011  4062 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 03:29:10.053  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 03:29:10.053  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 03:29:10.053  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:10.053  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-23 03:29:10.054  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 03:29:10.054  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 03:29:10.054  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 03:29:10.054  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 03:29:10.055  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 03:29:10.055  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 03:29:10.057  4011  4062 D BluetoothAdapter: STATE_ON
08-23 03:29:10.058  4414  4443 D BtGatt.GattService: stopScan() - queue size =1
08-23 03:29:10.059  4414  4453 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 03:29:10.060  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 03:29:10.061  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 03:29:10.061  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 03:29:10.061  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 03:29:10.061  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 03:29:10.063  4414  4430 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 03:29:10.063  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:29:10.063  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:10.063  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 03:29:10.064  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 03:29:10.064  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 03:29:10.064  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:29:10.064  4414  4433 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 03:29:10.067  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 03:29:10.067  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 03:29:10.067  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:29:10.082  4414  4430 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 03:29:10.082  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:10.083  4414  4433 D BtGatt.ScanManager: Starting BLE batch scan
08-23 03:29:10.084  4414  4433 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 03:29:10.117  4414  4430 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 03:29:10.117  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:10.140  4414  4430 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 03:29:10.141  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:10.166  4414  4430 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 03:29:10.167  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:10.168  4414  4433 D BtGatt.ScanManager: stopping BLe Batch
,08-23 03:29:10.175  4414  4430 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 03:29:10.175  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:10.175  4414  4433 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:29:10.183  4414  4430 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
08-23 03:29:10.183  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:10.569  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-23 03:29:10.569  4011  4011 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 03:29:10.569  4011  4011 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 03:29:13.068  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:29:13.068  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:29:13.069  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:29:13.070  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:13.070  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:13.070  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:29:13.071  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 03:29:13.071  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1612557 removed from the list
08-23 03:29:13.071  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:13.072  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8079844 removed from the list
08-23 03:29:13.072  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:29:13.072  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:13.074  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:13.074  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:13.078  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:29:13.078  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:29:13.079  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:29:13.080  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8079844 not in the list
08-23 03:29:13.080  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:13.081  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:13.085  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:29:13.085  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:29:13.086  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:29:13.086  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8079844 not in the list
08-23 03:29:13.086  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:13.087  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:13.088  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:13.088  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1612557 not in the list,
08-23 03:29:13.088  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 03:29:13.089  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@910ff29 added. We now have 3 listener(s)
08-23 03:29:13.090  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 03:29:13.091  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:29:13.091  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:29:13.091  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:29:13.091  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb152ae added. We now have 4 listener(s)
08-23 03:29:13.091  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:29:13.092  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:29:13.096  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:29:13.104  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:29:13.107  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:29:13.108  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:29:13.109  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-23 03:29:13.110  4011  4062 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-23 03:29:13.110  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-23 03:29:13.111  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-23 03:29:13.111  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-23 03:29:13.112  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 03:29:13.112  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:29:13.112  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:29:13.114  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-23 03:29:13.115  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 03:29:13.115  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:29:13.115  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 03:29:13.115  4011  4011 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 03:29:13.115  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 03:29:13.116  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-23 03:29:13.116  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:29:13.116  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 03:29:13.120  4011  4513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 03:29:13.124  4011  4513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-23 03:29:13.124  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 03:29:13.125  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 03:29:13.133  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 03:29:13.133  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 03:29:13.134  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 03:29:13.136  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-23 03:29:13.136  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 03:29:13.137  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-23 03:29:13.138  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-23 03:29:13.138  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-23 03:29:13.138  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-23 03:29:13.139  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:29:13.142  4414  4443 D BtGatt.GattService: registerClient() - UUID=debfe169-2f9d-439f-ae62-8fe068f5864f
,08-23 03:29:13.142  4414  4430 D BtGatt.GattService: onClientRegistered() - UUID=debfe169-2f9d-439f-ae62-8fe068f5864f, clientIf=5
08-23 03:29:13.142  4011  4022 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-23 03:29:13.145  4414  4432 D BtGatt.AdvertiseManager: message : 0
,08-23 03:29:13.149  4414  4432 D BtGatt.AdvertiseManager: starting multi advertising
,08-23 03:29:13.162  4414  4430 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-23 03:29:13.172  4414  4430 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-23 03:29:13.173  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-23 03:29:13.174  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 03:29:13.178  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 03:29:13.181  4011  4011 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-23 03:29:13.181  4011  4011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-23 03:29:13.181  4011  4011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-23 03:29:13.182  4011  4011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-23 03:29:13.182  4011  4011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-23 03:29:13.182  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-23 03:29:13.185  4011  4011 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-23 03:29:13.186  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-23 03:29:13.187  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 03:29:13.187  4011  4062 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 03:29:13.686  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-23 03:29:16.189  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:29:16.189  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-23 03:29:16.189  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 03:29:16.190  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-23 03:29:16.190  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 03:29:16.190  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 03:29:16.191  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-23 03:29:16.191  4011  4513 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-23 03:29:16.191  4011  4513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-23 03:29:16.191  4011  4062 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 03:29:16.192  4011  4513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 03:29:16.192  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 03:29:16.192  4011  4011 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 03:29:16.192  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 03:29:16.192  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 03:29:16.193  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 03:29:16.193  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 03:29:16.196  4011  4062 D BluetoothAdapter: STATE_ON
08-23 03:29:16.196  4011  4062 D BluetoothLeScanner: could not find callback wrapper
08-23 03:29:16.196  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 03:29:16.197  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-23 03:29:16.199  4414  4432 D BtGatt.AdvertiseManager: message : 1
08-23 03:29:16.200  4414  4432 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-23 03:29:16.210  4414  4430 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-23 03:29:16.211  4414  4430 D BtGatt.GattService: Client app is not null!
,08-23 03:29:16.211  4414  4481 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 03:29:16.212  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 03:29:16.212  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-23 03:29:16.212  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-23 03:29:16.212  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-23 03:29:16.212  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-23 03:29:16.214  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 03:29:16.214  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 03:29:16.214  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 03:29:16.214  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 03:29:16.216  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 03:29:16.216  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:16.216  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:29:16.216  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 03:29:16.216  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@910ff29 removed from the list
08-23 03:29:16.216  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:29:16.216  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb152ae removed from the list
08-23 03:29:16.217  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
08-23 03:29:16.217  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:16.217  4011  4011 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-23 03:29:16.219  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 03:29:16.219  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:16.219  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:16.221  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:29:16.221  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:29:16.222  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:16.222  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb152ae not in the list
08-23 03:29:16.222  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:16.222  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:16.223  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 03:29:16.224  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 03:29:16.224  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:29:16.224  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:29:16.224  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:16.224  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb152ae not in the list
,08-23 03:29:16.225  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:16.225  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:16.225  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:16.226  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@910ff29 not in the list
,08-23 03:29:16.228  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 03:29:16.228  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9a3a6b added. We now have 3 listener(s)
,08-23 03:29:16.235  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 03:29:16.235  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:29:16.235  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:29:16.236  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 03:29:16.236  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@539a9c8 added. We now have 4 listener(s)
08-23 03:29:16.237  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:29:16.238  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:29:16.241  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:29:16.246  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:29:16.248  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:29:16.248  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:29:16.249  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 03:29:16.249  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 03:29:16.249  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 03:29:16.249  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:29:16.249  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 03:29:16.252  4011  4062 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 03:29:16.253  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 03:29:16.253  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-23 03:29:16.257  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:29:16.257  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 03:29:16.258  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 03:29:16.259  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 03:29:16.264  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 03:29:16.264  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 03:29:16.264  4011  4062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 03:29:16.265  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:29:16.268  4414  4424 D BtGatt.GattService: registerClient() - UUID=30c87af1-85aa-4b46-9c72-7bcebcf59510
,08-23 03:29:16.268  4414  4430 D BtGatt.GattService: onClientRegistered() - UUID=30c87af1-85aa-4b46-9c72-7bcebcf59510, clientIf=5
08-23 03:29:16.269  4011  4022 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 03:29:16.269  4414  4481 D BtGatt.GattService: start scan with filters
,08-23 03:29:16.272  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 03:29:16.272  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 03:29:16.273  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 03:29:16.273  4414  4433 D BtGatt.ScanManager: handling starting scan
08-23 03:29:16.273  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 03:29:16.277  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 03:29:16.277  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 03:29:16.278  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 03:29:16.280  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 03:29:16.281  4414  4430 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 03:29:16.281  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:16.281  4414  4433 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 03:29:16.288  4414  4430 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 03:29:16.288  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:16.288  4414  4433 D BtGatt.ScanManager: Starting BLE batch scan
08-23 03:29:16.288  4414  4433 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 03:29:16.301  4414  4430 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 03:29:16.301  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:16.309  4414  4430 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 03:29:16.309  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 03:29:16.724  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 03:29:16.778  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-23 03:29:16.778  4011  4011 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 03:29:16.778  4011  4011 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-23 03:29:17.817  4414  4414 D BtGatt.ScanManager: awakened up at time 238374
,08-23 03:29:17.819  4414  4433 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 03:29:17.849  4414  4430 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-23 03:29:17.849  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:17.849  4414  4430 D BtGatt.GattService: current time is 238406093439
,08-23 03:29:17.850  4414  4430 D BtGatt.GattService: Batch record : [-126, -22, -96, 83, -39, -56, 1, -128, -58, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 87, 45, 110, 28, -13, -4, 1, -128, -69, 22, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-23 03:29:17.851  4414  4430 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
,08-23 03:29:17.852  4414  4430 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-23 03:29:17.852  4414  4430 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,08-23 03:29:17.852  4414  4430 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-23 03:29:17.853  4414  4430 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-23 03:29:17.853  4414  4430 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-23 03:29:17.853  4414  4430 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-23 03:29:17.857  4011  4011 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 1
,08-23 03:29:17.860  4011  4011 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 2
,08-23 03:29:17.860  4011  4011 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,08-23 03:29:17.861  4011  4011 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,08-23 03:29:19.297  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 03:29:19.298  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:29:19.298  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 03:29:19.298  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.299  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-23 03:29:19.299  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 03:29:19.299  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 03:29:19.299  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 03:29:19.300  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 03:29:19.301  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 03:29:19.301  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 03:29:19.303  4011  4062 D BluetoothAdapter: STATE_ON
,08-23 03:29:19.305  4414  4425 D BtGatt.GattService: stopScan() - queue size =1,
08-23 03:29:19.308  4414  4424 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 03:29:19.309  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 03:29:19.310  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 03:29:19.310  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 03:29:19.310  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 03:29:19.311  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,08-23 03:29:19.314  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:29:19.315  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 03:29:19.317  4011  4062 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 03:29:19.318  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 03:29:19.319  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:29:19.319  4011  4062 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-23 03:29:19.319  4414  4414 D BtGatt.ScanManager: awakened up at time 239876
08-23 03:29:19.325  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:19.325  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 03:29:19.325  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.325  4011  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 03:29:19.326  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 03:29:19.326  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 03:29:19.326  4011  4011 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 03:29:19.326  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9a3a6b removed from the list
08-23 03:29:19.327  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:29:19.327  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@539a9c8 removed from the list
08-23 03:29:19.328  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:29:19.328  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:19.329  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.330  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:19.331  4414  4430 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 03:29:19.332  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:19.332  4414  4433 D BtGatt.ScanManager: stopping BLe Batch
08-23 03:29:19.332  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:29:19.333  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:29:19.333  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 03:29:19.333  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@539a9c8 not in the list
,08-23 03:29:19.333  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.333  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:19.334  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:29:19.334  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:29:19.334  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:19.334  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@539a9c8 not in the list
,08-23 03:29:19.335  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:19.335  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.335  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-23 03:29:19.335  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9a3a6b not in the list
08-23 03:29:19.336  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 03:29:19.336  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9418be3 added. We now have 3 listener(s)
08-23 03:29:19.338  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 03:29:19.338  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-23 03:29:19.338  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:29:19.338  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 03:29:19.338  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19e9e0 added. We now have 4 listener(s)
,08-23 03:29:19.339  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:29:19.339  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 03:29:19.342  4414  4430 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 03:29:19.342  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:19.342  4414  4433 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-23 03:29:19.342  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:29:19.347  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 03:29:19.349  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 03:29:19.350  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 03:29:19.350  4011  4062 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 03:29:19.350  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:29:19.350  4011  4062 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 03:29:19.350  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:19.350  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.351  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 03:29:19.351  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 03:29:19.351  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9418be3 removed from the list
08-23 03:29:19.351  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:19.351  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19e9e0 removed from the list
08-23 03:29:19.353  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:29:19.356  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 03:29:19.356  4011  4062 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 03:29:19.356  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:19.357  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.357  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:19.357  4414  4430 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-23 03:29:19.357  4414  4430 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 03:29:19.357  4414  4430 D BtGatt.GattService: current time is 239914336565
,08-23 03:29:19.358  4414  4430 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 03:29:19.358  4414  4430 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-23 03:29:19.358  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 03:29:19.358  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 03:29:19.358  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:19.358  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19e9e0 not in the list
08-23 03:29:19.359  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.359  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 03:29:19.360  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 03:29:19.360  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 03:29:19.360  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 03:29:19.360  4011  4062 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19e9e0 not in the list
08-23 03:29:19.360  4011  4062 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 03:29:19.360  4011  4062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 03:29:19.360  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 03:29:19.360  4011  4062 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9418be3 not in the list
08-23 03:29:19.361  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 03:29:19.361  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 03:29:19.361  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 03:29:19.361  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 03:29:19.361  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 03:29:19.361  4011  4062 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 03:29:19.828  4011  4011 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 03:29:21.376  4011  4515 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: My test thread name)
,08-23 03:29:23.374  4011  4062 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 499
,08-23 03:29:23.374  4011  4062 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 499, name: My test thread name)
,08-23 03:29:23.380  4011  4516 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: My test thread name)
,08-23 03:29:23.381  4011  4516 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 500, thread name: My test thread name)
08-23 03:29:23.381  4011  4516 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 500, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-23 03:29:23.385  4011  4062 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-23 03:29:23.394  4011  4517 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 504, name: My test thread name)
,08-23 03:29:23.395  4011  4517 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 504, thread name: My test thread name): Test exception.
,08-23 03:29:23.395  4011  4517 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 504, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-23 03:29:23.399  4011  4515 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-23 03:29:23.405  4011  4062 I jxcore-log: Total number of executed tests:  82
08-23 03:29:23.405  4011  4062 I jxcore-log: 
,08-23 03:29:23.405  4011  4062 I jxcore-log: Number of passed tests:  82
08-23 03:29:23.405  4011  4062 I jxcore-log: 
,08-23 03:29:23.406  4011  4062 I jxcore-log: Number of failed tests:  0
08-23 03:29:23.406  4011  4062 I jxcore-log: 
08-23 03:29:23.407  4011  4062 I jxcore-log: Number of ignored tests:  0
08-23 03:29:23.407  4011  4062 I jxcore-log: 
08-23 03:29:23.409  4011  4062 I jxcore-log: Total duration:  101295
08-23 03:29:23.409  4011  4062 I jxcore-log: 
,08-23 03:29:23.415  4011  4062 I jxcore-log: Unit Test app is loaded
08-23 03:29:23.415  4011  4062 I jxcore-log: 
,08-23 03:29:23.423  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.423  4011  4062 I jxcore-log: 
,08-23 03:29:23.427  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.427  4011  4062 I jxcore-log: 
,08-23 03:29:23.430  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.430  4011  4062 I jxcore-log: 
08-23 03:29:23.432  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.432  4011  4062 I jxcore-log: 
08-23 03:29:23.433  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-23 03:29:23.433  4011  4062 I jxcore-log: 
08-23 03:29:23.435  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 03:29:23.435  4011  4062 I jxcore-log: 
,08-23 03:29:23.436  4011  4011 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-23 03:29:23.438  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.438  4011  4062 I jxcore-log: 
08-23 03:29:23.440  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.440  4011  4062 I jxcore-log: 
,08-23 03:29:23.441  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-23 03:29:23.441  4011  4062 I jxcore-log: 
,08-23 03:29:23.442  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 03:29:23.442  4011  4062 I jxcore-log: 
,08-23 03:29:23.443  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 03:29:23.443  4011  4062 I jxcore-log: 
08-23 03:29:23.443  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.443  4011  4062 I jxcore-log: 
,08-23 03:29:23.444  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.444  4011  4062 I jxcore-log: 
,08-23 03:29:23.445  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.445  4011  4062 I jxcore-log: 
08-23 03:29:23.446  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.446  4011  4062 I jxcore-log: 
,08-23 03:29:23.447  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.447  4011  4062 I jxcore-log: 
,08-23 03:29:23.448  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.448  4011  4062 I jxcore-log: 
08-23 03:29:23.449  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.449  4011  4062 I jxcore-log: 
,08-23 03:29:23.449  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.449  4011  4062 I jxcore-log: 
,08-23 03:29:23.450  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.450  4011  4062 I jxcore-log: 
08-23 03:29:23.451  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.451  4011  4062 I jxcore-log: 
,08-23 03:29:23.452  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.452  4011  4062 I jxcore-log: 
08-23 03:29:23.453  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.453  4011  4062 I jxcore-log: 
,08-23 03:29:23.455  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.455  4011  4062 I jxcore-log: 
,08-23 03:29:23.455  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.455  4011  4062 I jxcore-log: 
08-23 03:29:23.456  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.456  4011  4062 I jxcore-log: 
,08-23 03:29:23.456  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.456  4011  4062 I jxcore-log: 
08-23 03:29:23.457  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.457  4011  4062 I jxcore-log: 
,08-23 03:29:23.457  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.457  4011  4062 I jxcore-log: 
08-23 03:29:23.458  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.458  4011  4062 I jxcore-log: 
,08-23 03:29:23.458  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.458  4011  4062 I jxcore-log: 
08-23 03:29:23.459  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.459  4011  4062 I jxcore-log: 
,08-23 03:29:23.459  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.459  4011  4062 I jxcore-log: 
,08-23 03:29:23.460  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.460  4011  4062 I jxcore-log: 
08-23 03:29:23.460  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.460  4011  4062 I jxcore-log: 
,08-23 03:29:23.461  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.461  4011  4062 I jxcore-log: 
08-23 03:29:23.461  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.461  4011  4062 I jxcore-log: 
08-23 03:29:23.462  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.462  4011  4062 I jxcore-log: 
,08-23 03:29:23.462  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.462  4011  4062 I jxcore-log: 
08-23 03:29:23.463  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.463  4011  4062 I jxcore-log: 
,08-23 03:29:23.463  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 03:29:23.463  4011  4062 I jxcore-log: 
,08-23 03:29:23.464  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.464  4011  4062 I jxcore-log: 
08-23 03:29:23.464  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 03:29:23.464  4011  4062 I jxcore-log: 
,08-23 03:29:23.465  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.465  4011  4062 I jxcore-log: 
,08-23 03:29:23.465  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.465  4011  4062 I jxcore-log: 
08-23 03:29:23.466  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.466  4011  4062 I jxcore-log: 
08-23 03:29:23.466  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.466  4011  4062 I jxcore-log: 
08-23 03:29:23.467  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.467  4011  4062 I jxcore-log: 
08-23 03:29:23.467  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 03:29:23.467  4011  4062 I jxcore-log: 
08-23 03:29:23.468  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.468  4011  4062 I jxcore-log: 
08-23 03:29:23.468  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-23 03:29:23.468  4011  4062 I jxcore-log: 
,08-23 03:29:23.469  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.469  4011  4062 I jxcore-log: 
08-23 03:29:23.469  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 03:29:23.469  4011  4062 I jxcore-log: 
08-23 03:29:23.470  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-23 03:29:23.470  4011  4062 I jxcore-log: 
08-23 03:29:23.470  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-23 03:29:23.470  4011  4062 I jxcore-log: 
08-23 03:29:23.471  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-23 03:29:23.471  4011  4062 I jxcore-log: 
,08-23 03:29:23.472  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:29:23.472  4011  4062 I jxcore-log: 
08-23 03:29:23.472  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-23 03:29:23.472  4011  4062 I jxcore-log: 
08-23 03:29:23.475  4011  4062 I jxcore-log: My device name is: motorola-Nexus 6
08-23 03:29:23.475  4011  4062 I jxcore-log: 
,08-23 03:29:25.857  4011  4062 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-23 03:29:25.857  4011  4062 I jxcore-log: 
,08-23 03:29:25.874  4011  4062 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 03:29:25.875  4011  4062 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 03:29:25.875  4011  4062 I jxcore-log: 
,08-23 03:29:27.092  3963  4519 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 03:29:27.131  3963  4520 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 03:29:27.160  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:29:27.163  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:29:27.197  1490  3099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:29:27.198  1490  3099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:29:27.198  1490  3099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:29:27.198  1490  3099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:29:27.230  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:29:27.232  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:29:27.265  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:29:27.265  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:29:27.265  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:29:27.266  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:29:27.290  3963  4520 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 03:29:27.291  3963  4519 E BooksSync: Soft error
08-23 03:29:27.291  3963  4519 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:29:27.291  3963  4519 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:29:27.292  3963  4519 E BooksSync: Sync error
08-23 03:29:27.292  3963  4519 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:29:27.292  3963  4519 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:29:27.294  3963  4519 I BooksSync: Finished books sync
,08-23 03:29:27.307   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 247541, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:29:28.540  1490  2104 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 03:29:29.808   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250363, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 03:29:35.974   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=256530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 03:29:57.680  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:29:57.682  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:29:57.715  1490  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 03:29:57.715  1490  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 03:29:57.715  1490  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:29:57.715  1490  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:29:57.742  3732  4523 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 03:29:57.742  3732  4523 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at blb.a(PG:3937)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at czp.a(PG:18188)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:29:57.742  3732  4523 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	... 12 more
08-23 03:29:57.742  3732  4523 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at fal.a(PG:38)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:29:57.742  3732  4523 E HttpOperation: 	... 14 more
,08-23 03:29:57.787  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-23 03:29:57.787  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 03:29:57.787  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:29:57.787  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:29:57.802  3732  4523 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 03:29:57.802  3732  4523 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at hec.a(PG:42)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at hee.a(PG:102)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at czr.a(PG:65)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at kka.a(PG:108)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at czp.a(PG:19176)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:29:57.802  3732  4523 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	... 15 more
08-23 03:29:57.802  3732  4523 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at fal.a(PG:38)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:29:57.802  3732  4523 E HttpOperation: 	... 17 more
08-23 03:29:57.802  3732  4523 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 03:29:57.802  3732  4523 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at hec.a(PG:42)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at hee.a(PG:102)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at czr.a(PG:65)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at kka.a(PG:108)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	... 15 more
08-23 03:29:57.802  3732  4523 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at fal.a(PG:38)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 03:29:57.802  3732  4523 E ExperimentLoader: 	... 17 more
,08-23 03:29:57.964   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 249458, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:30:09.948   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=290504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 03:30:16.681   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 03:30:28.029   873   873 I ActivityManager: Start proc 4530:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-23 03:30:28.138  4530  4530 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-23 03:30:28.185  4530  4530 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-23 03:30:28.185  4530  4530 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 03:30:28.185  4530  4530 I GAv4    :   adb logcat -s GAv4
,08-23 03:30:28.200  4530  4530 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 03:30:28.204  4530  4530 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 03:30:28.216  4530  4546 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 03:30:28.229  3932  4542 V KeepSync: Connecting to GoogleApiClient
,08-23 03:30:28.230   873  1952 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 03:30:28.285  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:30:28.286  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:30:28.303  1490  3099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-23 03:30:28.303  1490  3099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 03:30:28.303  1490  3099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:30:28.303  1490  3099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:30:28.324  1708  4547 V BaseAuthAsyncOperation: access token request failed
,08-23 03:30:28.325  3932  4542 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 03:30:28.376  1490  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 03:30:28.376  1490  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 03:30:28.376  1490  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:30:28.376  1490  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:30:28.398  3932  4542 E KeepSync: IOException
08-23 03:30:28.398  3932  4542 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 03:30:28.398  3932  4542 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:30:28.398  3932  4542 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 03:30:28.398  3932  4542 E KeepSync: 	... 10 more
,08-23 03:30:28.398  3932  4542 W KeepSync: Sync result 2
,08-23 03:30:28.406   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 284735, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:30:50.588   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=331144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 03:30:57.281   873  4471 D NetlinkSocketObserver: NeighborEvent{elapsedMs=337837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 03:30:58.655  3963  4549 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 03:30:58.684  3963  4550 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 03:30:58.699  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:30:58.702  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:30:58.734  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:30:58.734  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:30:58.734  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:30:58.734  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:30:58.764  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:30:58.766  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:30:58.795  1490  2377 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:30:58.795  1490  2377 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:30:58.795  1490  2377 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:30:58.795  1490  2377 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:30:58.820  3963  4550 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 03:30:58.821  3963  4549 E BooksSync: Soft error
08-23 03:30:58.821  3963  4549 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:30:58.821  3963  4549 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:30:58.821  3963  4549 E BooksSync: Sync error
08-23 03:30:58.821  3963  4549 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:30:58.821  3963  4549 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 03:30:58.821  3963  4549 I BooksSync: Finished books sync
,08-23 03:30:58.830   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309876, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:31:02.484  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:31:02.496  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:31:02.501  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:31:02.561  1490  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 03:31:02.563  1490  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 03:31:02.563  1490  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:31:02.563  1490  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:31:02.585  1490  2060 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 03:31:02.585  1490  2060 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 03:31:02.585  1490  2060 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 03:31:02.585  1490  2060 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-23 03:31:02.585  1490  2060 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-23 03:31:02.585  1490  2060 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-23 03:31:02.585  1490  2060 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 03:31:02.594  3695  3724 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 03:31:02.594  3695  3724 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-23 03:31:02.594  3695  3724 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-23 03:31:02.594  3695  3724 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-23 03:31:02.594  3695  3724 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-23 03:31:02.594  3695  3724 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-23 03:31:02.594  3695  3724 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 03:31:29.145  3932  4564 V KeepSync: Connecting to GoogleApiClient
08-23 03:31:29.146   873  1951 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 03:31:29.218  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-23 03:31:29.223  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:31:29.297  1490  3099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 03:31:29.297  1490  3099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 03:31:29.297  1490  3099 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:31:29.297  1490  3099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:31:29.321  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-23 03:31:29.321  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 03:31:29.321  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:31:29.322  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:31:29.350  1708  4567 V BaseAuthAsyncOperation: access token request failed
,08-23 03:31:29.353  3932  4564 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 03:31:29.362  3732  4566 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 03:31:29.362  3732  4566 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at blb.a(PG:3937)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at czp.a(PG:18188)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:31:29.362  3732  4566 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	... 12 more
08-23 03:31:29.362  3732  4566 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at fal.a(PG:38)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:31:29.362  3732  4566 E HttpOperation: 	... 14 more
,08-23 03:31:29.451  1490  2377 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 03:31:29.451  1490  2377 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 03:31:29.451  1490  2377 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:31:29.451  1490  2377 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:31:29.487  3732  4566 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 03:31:29.487  3732  4566 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jdm.a(PG:82)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jcs.o(PG:406)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jcn.a(PG:1379)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jcs.i(PG:143)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at hec.a(PG:42)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at hee.a(PG:102)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at czr.a(PG:65)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at kka.a(PG:108)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at czp.a(PG:19176)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at czp.a(PG:9081)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at czq.run(PG:1686)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:31:29.487  3732  4566 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jdj.a(PG:4091)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jdj.a(PG:1125)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jdm.a(PG:77)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	... 15 more
08-23 03:31:29.487  3732  4566 E HttpOperation: Caused by: faj: BadAuthentication
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at fal.a(PG:38)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	at jdj.a(PG:4089)
08-23 03:31:29.487  3732  4566 E HttpOperation: 	... 17 more
,08-23 03:31:29.487  3732  4566 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 03:31:29.487  3732  4566 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at hec.a(PG:42)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at hee.a(PG:102)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at czr.a(PG:65)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at kka.a(PG:108)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	... 15 more
08-23 03:31:29.487  3732  4566 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at fal.a(PG:38)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 03:31:29.487  3732  4566 E ExperimentLoader: 	... 17 more
,08-23 03:31:29.555  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 03:31:29.556  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 03:31:29.556  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:31:29.556  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:31:29.581  3932  4564 E KeepSync: IOException
08-23 03:31:29.581  3932  4564 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 03:31:29.581  3932  4564 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:31:29.581  3932  4564 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 03:31:29.581  3932  4564 E KeepSync: 	... 10 more
08-23 03:31:29.582  3932  4564 W KeepSync: Sync result 2
,08-23 03:31:29.601   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 339459, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:31:29.625   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 344312, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:32:30.722  3932  4572 V KeepSync: Connecting to GoogleApiClient
,08-23 03:32:30.722   873  1942 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 03:32:30.774  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:32:30.776  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:32:30.806  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 03:32:30.807  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 03:32:30.807  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:32:30.807  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:32:30.824  1708  4573 V BaseAuthAsyncOperation: access token request failed
,08-23 03:32:30.825  3932  4572 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 03:32:30.892  1490  1501 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 03:32:30.893  1490  1501 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 03:32:30.893  1490  1501 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 03:32:30.893  1490  1501 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:32:30.910  3932  4572 E KeepSync: IOException
08-23 03:32:30.910  3932  4572 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 03:32:30.910  3932  4572 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 03:32:30.910  3932  4572 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 03:32:30.910  3932  4572 E KeepSync: 	... 10 more
,08-23 03:32:30.910  3932  4572 W KeepSync: Sync result 2
,08-23 03:32:30.915   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 431149, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:33:02.970  3963  4575 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 03:33:02.993  3963  4576 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 03:33:03.007  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:33:03.010  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:33:03.056  1490  2377 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:33:03.056  1490  2377 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:33:03.056  1490  2377 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:33:03.056  1490  2377 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:33:03.101  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:33:03.104  1490  1490 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 03:33:03.149  1490  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 03:33:03.149  1490  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 03:33:03.149  1490  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 03:33:03.149  1490  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 03:33:03.176  3963  4576 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 03:33:03.177  3963  4575 E BooksSync: Soft error
08-23 03:33:03.177  3963  4575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:33:03.177  3963  4575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 03:33:03.177  3963  4575 E BooksSync: Sync error
08-23 03:33:03.177  3963  4575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 03:33:03.177  3963  4575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 03:33:03.177  3963  4575 I BooksSync: Finished books sync
,08-23 03:33:03.188   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 463411, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 03:33:09.170  4011  4062 I jxcore-log: TAP version 13
08-23 03:33:09.170  4011  4062 I jxcore-log: 
,08-23 03:33:09.174  4011  4062 I jxcore-log: # setup
08-23 03:33:09.174  4011  4062 I jxcore-log: 
,08-23 03:33:10.283  4011  4062 I jxcore-log: # 1. onPeerLost calls jxcore
08-23 03:33:10.283  4011  4062 I jxcore-log: 
,08-23 03:33:10.349  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 03:33:10.349  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2edc35e added. We now have 3 listener(s)
08-23 03:33:10.351  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 03:33:10.351  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:33:10.351  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:33:10.352  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:33:10.352  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@977033f added. We now have 4 listener(s)
08-23 03:33:10.352  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 03:33:10.352  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:33:10.357  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:33:10.364  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:33:10.367  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:33:10.368  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 03:33:10.368  4011  4062 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
08-23 03:33:10.369  4011  4062 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-23 03:33:10.371  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:33:10.374  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:33:12.375  4011  4062 I jxcore-log: onPeerLost
08-23 03:33:12.375  4011  4062 I jxcore-log: 
,08-23 03:33:12.379  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:33:12.379  4011  4062 I jxcore-log: 
,08-23 03:33:12.397  4011  4062 I jxcore-log: # teardown
08-23 03:33:12.397  4011  4062 I jxcore-log: 
,08-23 03:33:12.409  4011  4062 I jxcore-log: ok 1 check if callback was fired by onPeerLost
08-23 03:33:12.409  4011  4062 I jxcore-log: 
,08-23 03:33:12.411  4011  4062 I jxcore-log: ok 2 check if peerAvailable is false
08-23 03:33:12.411  4011  4062 I jxcore-log: 
,08-23 03:33:13.652  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 03:33:13.652  4011  4062 I jxcore-log: 
,08-23 03:33:13.657  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 03:33:13.657  4011  4062 I jxcore-log: 
,08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:33:13.674  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:33:13.682  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:33:13.689  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 03:33:13.689  4011  4062 I jxcore-log: 
,08-23 03:33:13.694  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 03:33:13.694  4011  4062 I jxcore-log: 
,08-23 03:33:13.700  4011  4062 I jxcore-log: # setup
08-23 03:33:13.700  4011  4062 I jxcore-log: 
,08-23 03:33:13.709  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:33:13.709  4011  4062 I jxcore-log: 
,08-23 03:33:13.891  4011  4062 I jxcore-log: # 2. onPeerDiscovered calls jxcore
08-23 03:33:13.891  4011  4062 I jxcore-log: 
,08-23 03:33:14.892  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 03:33:14.892  4011  4062 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97e5155 added. We now have 4 listener(s)
,08-23 03:33:14.894  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 03:33:14.894  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 03:33:14.894  4011  4062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 03:33:14.894  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 03:33:14.894  4011  4062 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44eb76a added. We now have 5 listener(s)
08-23 03:33:14.894  4011  4062 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 03:33:14.895  4011  4062 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 03:33:14.901  4011  4062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:33:14.914  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:33:14.921  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:33:14.922  4011  4062 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 03:33:14.922  4011  4062 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-23 03:33:14.929  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:33:14.939  4011  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 03:33:16.926  4011  4062 I jxcore-log: onPeerDiscovered
08-23 03:33:16.926  4011  4062 I jxcore-log: 
,08-23 03:33:16.933  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:33:16.933  4011  4062 I jxcore-log: 
,08-23 03:33:16.948  4011  4062 I jxcore-log: # teardown
08-23 03:33:16.948  4011  4062 I jxcore-log: 
,08-23 03:33:16.955  4011  4062 I jxcore-log: ok 3 check if callback was fired by onPeerDiscovered
08-23 03:33:16.955  4011  4062 I jxcore-log: 
,08-23 03:33:16.956  4011  4062 I jxcore-log: ok 4 check if peerAvailable is true
08-23 03:33:16.956  4011  4062 I jxcore-log: 
,08-23 03:33:17.099  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 03:33:17.099  4011  4062 I jxcore-log: 
,08-23 03:33:17.105  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 03:33:17.105  4011  4062 I jxcore-log: 
,08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 03:33:17.121  4011  4062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 03:33:17.126  4011  4062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 03:33:17.127  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 03:33:17.127  4011  4062 I jxcore-log: 
,08-23 03:33:17.131  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 03:33:17.131  4011  4062 I jxcore-log: 
,08-23 03:33:17.135  4011  4062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 03:33:17.135  4011  4062 I jxcore-log: 
,08-23 03:33:17.259  4011  4062 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 03:33:17.259  4011  4062 I jxcore-log: 
,08-23 03:33:17.904  4578  4578 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 03:33:17.909  4578  4578 D AndroidRuntime: CheckJNI is OFF
,08-23 03:33:17.946  4578  4578 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 03:33:17.990  4578  4578 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 03:33:18.012  4578  4578 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 03:33:18.025   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 03:33:18.025   873   886 I ActivityManager: Killing 4011:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-23 03:33:18.101   873  1966 D GraphicsStats: Buffer count: 2
,08-23 03:33:18.101   873  1306 D WifiService: Client connection lost with reason: 4
08-23 03:33:18.102   873  1951 I WindowState: WIN DEATH: Window{467c34a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 03:33:18.152   873   896 W PackageSettings: Skipping PackageSetting{d635131 com.example.hello/10273} due to missing metadata
,08-23 03:33:18.183   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-23 03:33:18.184   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-23 03:33:18.184   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-23 03:33:18.184   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-23 03:33:18.184   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:33:18.184   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.184   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 03:33:18.184   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 03:33:18.185   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3058263 u0 com.test.thalitest/.MainActivity t2}
,08-23 03:33:18.189   873  1966 W ActivityManager: Spurious death for ProcessRecord{3a08748 0:com.test.thalitest/u0a0}, curProc for 4011: null
,08-23 03:33:18.194   873   896 I art     : Starting a blocking GC Explicit
,08-23 03:33:18.236   873   896 I art     : Explicit concurrent mark sweep GC freed 20514(1349KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 663us total 40.938ms
,08-23 03:33:18.257   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 03:33:18.264  4578  4578 I art     : System.exit called, status: 0
,08-23 03:33:18.264  4578  4578 I AndroidRuntime: VM exiting with result code 0.
,08-23 03:33:18.312   873   896 I ActivityManager: Start proc 4589:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-23 03:33:18.312   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 03:33:18.329   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-23 03:33:18.342  4414  4414 D BluetoothMapAppObserver: onReceive
,08-23 03:33:18.342  4414  4414 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 03:33:18.344  1983  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 03:33:18.347   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 03:33:18.352  3819  3819 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 03:33:18.353  1858  1858 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-23 03:33:18.377  1858  4604 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 03:33:18.390   873  1303 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-23 03:33:18.396  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 03:33:18.403   873  1966 I ActivityManager: Start proc 4605:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-23 03:33:18.407   873  1951 I ActivityManager: Killing 3871:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-23 03:33:18.411  1858  4604 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-23 03:33:18.411  1858  4604 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-23 03:33:18.411  1858  4604 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-23 03:33:18.411  1858  4604 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-23 03:33:18.411  1858  4604 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-23 03:33:18.411  1858  4604 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-23 03:33:18.414  1858  4604 I Decoder : createOrResetDecoder
,08-23 03:33:18.433   873  1952 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4011 uid 10000
,08-23 03:33:18.434  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-23 03:33:18.455   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 03:33:18.494  1936  2023 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-23 03:33:18.495   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-23 03:33:18.495   873   885 E PackageManager: Failed to write settings, restoring backup
,08-23 03:33:18.495   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 03:33:18.495   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 03:33:18.495   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 03:33:18.495   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 03:33:18.495   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 03:33:18.495   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:33:18.495   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.495   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 03:33:18.499   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-23 03:33:18.499   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 03:33:18.499   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 03:33:18.499   873   886 E DropBoxManagerService: ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 03:33:18.499   873   886 E DropBoxManagerService: 	... 13 more
,08-23 03:33:18.508  1490  1490 I ConfigService: onCreate
,08-23 03:33:18.510   873  1971 I ActivityManager: Start proc 4617:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-23 03:33:18.510  1936  2023 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 03:33:18.510  1936  2023 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1936
08-23 03:33:18.510  1936  2023 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.510  1936  2023 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 03:33:18.513   873  1942 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 03:33:18.513   873  4624 E DropBoxManagerService: Can't write: system_app_crash
08-23 03:33:18.513   873  4624 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 03:33:18.513   873  4624 E DropBoxManagerService: 	... 5 more
08-23 03:33:18.516  1936  2023 I Process : Sending signal. PID: 1936 SIG: 9
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-23 03:33:18.532  1490  4620 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-23 03:33:18.533  1490  4620 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-23 03:33:18.537  4605  4605 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-23 03:33:18.546  1490  4620 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-23 03:33:18.568  1858  4604 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 03:33:18.601  1858  4604 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-23 03:33:18.603  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-23 03:33:18.603  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-23 03:33:18.605  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-23 03:33:18.605  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-23 03:33:18.605  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-23 03:33:18.605  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-23 03:33:18.606  1858  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-23 03:33:18.606  1858  4604 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 03:33:18.606  1858  4604 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-23 03:33:18.606  1858  4604 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-23 03:33:18.606  1858  4604 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-23 03:33:18.606  1858  4604 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-23 03:33:18.618   873   883 D GraphicsStats: Buffer count: 1
08-23 03:33:18.618   873  3272 I WindowState: WIN DEATH: Window{e4cccf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-23 03:33:18.629   873  1680 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1936) has died
08-23 03:33:18.630   873  1680 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-23 03:33:18.632   873  1680 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 03:33:18.653  4605  4635 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.653  4605  4635 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.653  4605  4635 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 03:33:18.661   873   886 I ActivityManager: Start proc 4637:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 03:33:18.681  4605  4605 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-23 03:33:18.697  4605  4650 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 03:33:18.702   873  1680 I ActivityManager: Start proc 4651:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-23 03:33:18.704  4637  4637 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:33:18.704  4637  4637 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 03:33:18.704  4637  4637 D AndroidRuntime: Shutting down VM
08-23 03:33:18.714  4637  4637 E AndroidRuntime: FATAL EXCEPTION: main
08-23 03:33:18.714  4637  4637 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4637
08-23 03:33:18.714  4637  4637 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 03:33:18.714  4637  4637 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 03:33:18.714  4637  4637 E AndroidRuntime: 	... 10 more
08-23 03:33:18.718   873  4662 E DropBoxManagerService: Can't write: system_app_crash
08-23 03:33:18.718   873  4662 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 03:33:18.718   873  4662 E DropBoxManagerService: 	... 5 more
08-23 03:33:18.720   873  3272 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 03:33:18.722  4637  4637 I Process : Sending signal. PID: 4637 SIG: 9
08-23 03:33:18.731  1708  4649 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-23 03:33:18.731  1708  4649 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-23 03:33:18.736  1708  4649 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-23 03:33:18.737   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4637) has died
08-23 03:33:18.738  1708  4649 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-23 03:33:18.739   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-23 03:33:18.748  4651  4651 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-23 03:33:18.752   873   886 I ActivityManager: Start proc 4664:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 03:33:18.765   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
