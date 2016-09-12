#### Test 84639099bbd10c6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 07:31:05.653  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:05.670  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 07:31:05.676  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 07:31:05.746  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 07:31:05.746  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:31:05.747  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:31:05.747  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 07:31:05.779  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 07:31:05.779  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:31:05.780  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 07:31:06.316  3925  3925 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 07:31:06.321  3925  3925 D AndroidRuntime: CheckJNI is OFF
09-12 07:31:06.364  3925  3925 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 07:31:06.414  3925  3925 I Radio-JNI: register_android_hardware_Radio DONE
09-12 07:31:06.434  3925  3925 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 07:31:06.439   874  1598 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 07:31:06.481  3925  3925 D AndroidRuntime: Shutting down VM
09-12 07:31:06.484  2026  2045 W SearchService: Abort, client detached.
09-12 07:31:06.489  2026  2026 I HotwordDetector: Closing mic
09-12 07:31:06.489  2026  2343 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@784c264
09-12 07:31:06.490  2026  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 07:31:06.546   376  2354 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 07:31:06.549   376  2354 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 07:31:06.562   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 07:31:06.566   874  2126 I ActivityManager: Start proc 3935:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 07:31:06.567  2026  2346 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 07:31:06.568  2026  2349 I MicroRecognitionRnrImpl: Detection finished
09-12 07:31:06.641  3935  3935 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 07:31:06.682  3935  3935 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 07:31:06.693  3935  3935 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 708-712)
09-12 07:31:06.693  3935  3935 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 07:31:06.718  3935  3935 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cca0e21}
09-12 07:31:06.718  3935  3935 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 07:31:06.718  3935  3935 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 07:31:06.726  3935  3935 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 07:31:06.728  3935  3935 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 07:31:06.753  3935  3935 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 07:31:06.779  3935  3935 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 07:31:06.779  3935  3935 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 07:31:06.779  3935  3935 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 07:31:06.779  3935  3935 I Adreno  : Build Date                       : 10/20/15
09-12 07:31:06.779  3935  3935 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 07:31:06.779  3935  3935 I Adreno  : Local Branch                     : M14
09-12 07:31:06.779  3935  3935 I Adreno  : Remote Branch                    : 
09-12 07:31:06.779  3935  3935 I Adreno  : Remote Branch                    : 
09-12 07:31:06.779  3935  3935 I Adreno  : Reconstruct Branch               : 
,09-12 07:31:06.873   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f0320b8:true
,09-12 07:31:06.906  3935  3935 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 07:31:06.925  3935  3935 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 07:31:06.976  3935  3973 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 07:31:06.985  3935  3960 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 07:31:07.008  3935  3973 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 07:31:07.077   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms
,09-12 07:31:07.079  1880  1880 I Keyboard.Facilitator: onFinishInput()
,09-12 07:31:07.191  3935  3935 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3935
,09-12 07:31:07.374   874  1695 I ActivityManager: Killing 3326:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 07:31:07.377  3935  3935 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 07:31:07.430   874  1695 I ActivityManager: Killing 2639:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-12 07:31:07.549  3935  3975 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1698694864
,09-12 07:31:07.554  3935  3975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 07:31:07.554  3935  3975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 07:31:07.554  3935  3975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 07:31:07.554  3935  3975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 07:31:07.554  3935  3975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 07:31:07.554  3935  3975 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b2fb8c added. We now have 1 listener(s)
,09-12 07:31:07.557  3935  3975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 07:31:07.559  3935  3975 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:07.559  3935  3975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 07:31:07.560  3935  3975 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 07:31:07.563  3935  3975 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a6d1db added. We now have 1 listener(s)
,09-12 07:31:07.564  3935  3975 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:07.567   874  1305 D WifiService: New client listening to asynchronous messages
,09-12 07:31:07.568  3935  3975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 07:31:07.568  3935  3975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 07:31:07.568  3935  3975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 07:31:07.569  3935  3975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-12 07:31:07.569  3935  3975 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 07:31:07.572  3935  3975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:07.572  3935  3975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 07:31:07.579  3935  3975 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:07.579  3935  3975 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:07.579  3935  3975 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 07:31:07.579  3935  3975 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:07.580  3935  3975 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 07:31:07.581  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:07.583  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:07.616  3935  3935 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 07:31:07.791   874  2095 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:31:08.240  3935  3943 I art     : Background sticky concurrent mark sweep GC freed 71789(7MB) AllocSpace objects, 18(1604KB) LOS objects, 29% free, 23MB/32MB, paused 991us total 157.943ms
,09-12 07:31:08.677  3935  3984 E filemap : mmap(18165760,0) failed: Invalid argument
,09-12 07:31:08.677  3935  3984 W asset   : create map from entry failed
09-12 07:31:08.677  3935  3984 W jxcore-FileManager: aproxFileSize failed
09-12 07:31:08.678  3935  3984 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/thali/node_modules/hoek/test/modules/ignore.txt
09-12 07:31:08.678  3935  3984 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
,09-12 07:31:08.678  3935  3984 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
09-12 07:31:08.679  3935  3984 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
,09-12 07:31:08.679  3935  3984 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
09-12 07:31:08.680  3935  3984 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
,09-12 07:31:08.680  3935  3984 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
,09-12 07:31:08.680  3935  3984 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 07:31:08.680  3935  3984 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 07:31:08.680  3935  3984 W System.err: 	at android.os.Looper.loop(Looper.java:148)
,09-12 07:31:08.681  3935  3984 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-12 07:31:08.793  3935  3984 W jxcore-log: Initializing JXcore engine
,09-12 07:31:08.793  3935  3984 W jxcore-log: JXcore engine is ready
,09-12 07:31:08.860  3984  3984 W Thread-358: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 07:31:08.860  3984  3984 W Thread-358: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10685]" dev="sockfs" ino=10685 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-12 07:31:08.860  3984  3984 W Thread-358: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 07:31:08.860  3984  3984 W Thread-358: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26727]" dev="sockfs" ino=26727 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 07:31:08.879  3935  3984 W jxcore-log: Starting JXcore engine
,09-12 07:31:08.956  3935  3984 W jxcore-log: Platform android
09-12 07:31:08.956  3935  3984 W jxcore-log: 
,09-12 07:31:08.956  3935  3984 W jxcore-log: Process ARCH arm,
09-12 07:31:08.956  3935  3984 W jxcore-log: 
,09-12 07:31:09.142  3935  3984 I jxcore-log: JXcore Cordova bridge is ready!
09-12 07:31:09.142  3935  3984 I jxcore-log: 
09-12 07:31:09.143  3935  3984 W jxcore-log: JXcore engine is started
,09-12 07:31:09.154  3935  3975 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 07:31:09.161  3935  3935 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 07:31:09.329   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 07:31:09.585   874  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 07:31:12.355   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 07:31:15.865  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:15.870  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:15.906  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:31:15.906  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:31:15.906  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:31:15.906  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:15.934  3126  3994 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 07:31:15.934  3126  3994 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at blb.a(PG:3937)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at czp.a(PG:18188)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:31:15.934  3126  3994 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	... 12 more
09-12 07:31:15.934  3126  3994 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at fal.a(PG:38)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:31:15.934  3126  3994 E HttpOperation: 	... 14 more
,09-12 07:31:16.006  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:31:16.006  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 07:31:16.007  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:31:16.007  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:16.040  3126  3994 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 07:31:16.040  3126  3994 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at hec.a(PG:42)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at hee.a(PG:102)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at czr.a(PG:65)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at kka.a(PG:108)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at czp.a(PG:19176)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:31:16.040  3126  3994 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	... 15 more
09-12 07:31:16.040  3126  3994 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at fal.a(PG:38)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:31:16.040  3126  3994 E HttpOperation: 	... 17 more
,09-12 07:31:16.040  3126  3994 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 07:31:16.040  3126  3994 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at hec.a(PG:42)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at hee.a(PG:102)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at czr.a(PG:65)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at kka.a(PG:108)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	... 15 more
09-12 07:31:16.040  3126  3994 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at fal.a(PG:38)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 07:31:16.040  3126  3994 E ExperimentLoader: 	... 17 more
,09-12 07:31:16.176   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129669, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:31:18.416   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 07:31:19.028  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 07:31:19.028  3935  3984 I jxcore-log: 
,09-12 07:31:19.030  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 07:31:19.030  3935  3984 I jxcore-log: 
,09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:19.058  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:19.060  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:19.063  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 07:31:19.063  3935  3984 I jxcore-log: 
,09-12 07:31:19.065  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 07:31:19.065  3935  3984 I jxcore-log: 
,09-12 07:31:19.558  3935  3984 D executeNativeTests: Running unit tests
,09-12 07:31:19.616  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 07:31:19.616  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c added. We now have 2 listener(s)
09-12 07:31:19.617  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 07:31:19.617  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 07:31:19.618  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:19.618  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:19.618  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 added. We now have 2 listener(s)
09-12 07:31:19.618  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:19.618  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 07:31:19.622  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:19.634  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:19.638  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:19.638  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:19.640  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 07:31:19.642  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 07:31:19.642  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 07:31:19.644  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:19.646  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:19.647  3935  3984 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 07:31:19.648  3935  3984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 07:31:19.648  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 07:31:19.648  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 07:31:19.649  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 07:31:19.650  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.652  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:19.652  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.653  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.653  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.653  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:19.653  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:19.653  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c removed from the list
,09-12 07:31:19.653  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.653  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 removed from the list
,09-12 07:31:19.653  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.653  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:19.654  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.654  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.654  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:19.654  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 07:31:19.655  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.655  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
,09-12 07:31:19.656  3935  3984 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 07:31:19.656  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 07:31:19.656  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:19.656  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.657  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 07:31:19.657  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.657  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:19.657  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.657  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:19.657  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.657  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.657  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.657  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.657  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.657  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.662  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:19.662  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.662  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.662  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.667  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 07:31:19.667  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 07:31:19.667  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 07:31:19.668  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 07:31:19.669  3935  3984 D io.jxco,re.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 07:31:19.669  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 07:31:19.669  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.669  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.669  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.669  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.669  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.669  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.670  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.670  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.670  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.670  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.670  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.670  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.670  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.670  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.672  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.672  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.672  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.672  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.673  3935  3984 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 07:31:19.674  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:19.678  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 07:31:19.681  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.681  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 07:31:19.682  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:19.682  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 07:31:19.682  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 07:31:19.682  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:19.682  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 07:31:19.683  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:19.688  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 07:31:19.688  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 07:31:19.688  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:19.695  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 07:31:19.699  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 07:31:19.700  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 07:31:19.705  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 07:31:19.711  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 07:31:19.711  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 07:31:19.712  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 07:31:19.713  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 07:31:19.716  3935  3984 D BluetoothAdapter: STATE_ON
,09-12 07:31:19.726  2822  3025 D BtGatt.GattService: registerClient() - UUID=a7139e85-d9b1-4e89-91a3-490530e4afd7
09-12 07:31:19.728  2822  2874 D BtGatt.GattService: onClientRegistered() - UUID=a7139e85-d9b1-4e89-91a3-490530e4afd7, clientIf=5
09-12 07:31:19.729  3935  3983 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 07:31:19.732  2822  3045 D BtGatt.GattService: start scan with filters
09-12 07:31:19.737  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 07:31:19.738  2822  2887 D BtGatt.ScanManager: handling starting scan
09-12 07:31:19.738  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 07:31:19.738  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 07:31:19.738  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 07:31:19.741  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 07:31:19.742  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 07:31:19.742  2822  2887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:19.742  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 07:31:19.743  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 07:31:19.746  3935  3984 I io.jxcore.node.ConnectionHelper: start: OK
09-12 07:31:19.750  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.750  3935  3984 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 07:31:19.750  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.750  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 07:31:19.750  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.750  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 07:31:19.750  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 07:31:19.750  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 07:31:19.750  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 07:31:19.750  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 07:31:19.751  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 07:31:19.751  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 07:31:19.754  2822  2874 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 07:31:19.757  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.754  3935  3984 D BluetoothAdapter: STATE_ON
,09-12 07:31:19.757  2822  2887 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 07:31:19.761  2822  3045 D BtGatt.GattService: stopScan() - queue size =1
,09-12 07:31:19.774  2822  2839 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 07:31:19.776  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 07:31:19.776  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 07:31:19.776  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 07:31:19.777  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 07:31:19.777  2822  2874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 07:31:19.777  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 07:31:19.777  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.778  2822  2887 D BtGatt.ScanManager: Starting BLE batch scan
09-12 07:31:19.778  2822  2887 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 07:31:19.778  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 07:31:19.779  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 07:31:19.779  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 07:31:19.779  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 07:31:19.780  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:19.781  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.781  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.781  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:19.781  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.781  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.781  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
,09-12 07:31:19.781  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.781  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.782  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 07:31:19.782  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:19.782  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:19.784  3935  3984 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 07:31:19.787  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 07:31:19.795  2822  2874 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 07:31:19.795  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:19.801  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:19.804  2822  2874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 07:31:19.804  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.811  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:19.812  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:19.812  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:19.812  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 07:31:19.812  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 07:31:19.812  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 07:31:19.813  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 07:31:19.815  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:19.819  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:19.821  2822  2874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 07:31:19.821  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.821  2822  2887 D BtGatt.ScanManager: stopping BLe Batch
09-12 07:31:19.822  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 07:31:19.822  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 07:31:19.832  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 07:31:19.832  2822  2874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 07:31:19.832  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.832  2822  2887 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 07:31:19.833  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 07:31:19.833  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 07:31:19.837  2822  2874 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 07:31:19.837  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.844  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 07:31:19.844  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 07:31:19.844  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 07:31:19.847  3935  3984 D BluetoothAdapter: STATE_ON
,09-12 07:31:19.851  2822  2839 D BtGatt.GattService: registerClient() - UUID=724bf63c-b4af-4129-a42f-730e5d073563
,09-12 07:31:19.851  2822  2874 D BtGatt.GattService: onClientRegistered() - UUID=724bf63c-b4af-4129-a42f-730e5d073563, clientIf=5
09-12 07:31:19.852  3935  3946 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 07:31:19.852  2822  2835 D BtGatt.GattService: start scan with filters
09-12 07:31:19.854  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 07:31:19.854  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 07:31:19.855  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 07:31:19.855  2822  2887 D BtGatt.ScanManager: handling starting scan
,09-12 07:31:19.855  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 07:31:19.861  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:19.862  2822  2874 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 07:31:19.862  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.862  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 07:31:19.862  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:19.862  2822  2887 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 07:31:19.866  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 07:31:19.871  2822  2874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 07:31:19.871  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.871  2822  2887 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 07:31:19.871  2822  2887 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 07:31:19.871  3935  3984 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 07:31:19.877  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 07:31:19.877  3935  3984 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 07:31:19.878  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:19.878  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 07:31:19.878  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 07:31:19.878  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 07:31:19.878  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 07:31:19.878  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 07:31:19.879  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 07:31:19.879  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 07:31:19.879  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 07:31:19.879  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 07:31:19.881  3935  3984 D BluetoothAdapter: STATE_ON
09-12 07:31:19.882  2822  2839 D BtGatt.GattService: stopScan() - queue size =1
09-12 07:31:19.882  2822  2874 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 07:31:19.882  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:19.883  2822  3025 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 07:31:19.883  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 07:31:19.884  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 07:31:19.884  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 07:31:19.884  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 07:31:19.884  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 07:31:19.885  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:19.885  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 07:31:19.885  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 07:31:19.885  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 07:31:19.885  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:19.886  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.886  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.886  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 07:31:19.886  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:19.886  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.886  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.886  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.886  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:19.886  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:19.887  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.887  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.887  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.887  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.888  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.888  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.888  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.888  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.888  3935  3984 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 07:31:19.890  2822  2874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 07:31:19.890  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.891  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:19.898  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 07:31:19.899  2822  2874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 07:31:19.899  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.899  2822  2887 D BtGatt.ScanManager: stopping BLe Batch
09-12 07:31:19.901  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:19.901  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 07:31:19.901  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:19.902  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 07:31:19.902  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 07:31:19.902  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:19.902  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 07:31:19.905  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 07:31:19.905  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 07:31:19.906  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:19.908  2822  2874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 07:31:19.908  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 07:31:19.908  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 07:31:19.908  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.909  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 07:31:19.909  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:19.909  2822  2887 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 07:31:19.913  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 07:31:19.914  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 07:31:19.915  2822  2874 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 07:31:19.914  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 07:31:19.916  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.917  3935  3984 D BluetoothAdapter: STATE_ON
09-12 07:31:19.918  2822  3025 D BtGatt.GattService: registerClient() - UUID=193395c7-c1d3-4ffb-8cc9-601bd167b0fe
09-12 07:31:19.918  2822  2874 D BtGatt.GattService: onClientRegistered() - UUID=193395c7-c1d3-4ffb-8cc9-601bd167b0fe, clientIf=5
09-12 07:31:19.919  3935  3983 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 07:31:19.919  2822  2839 D BtGatt.GattService: start scan with filters
09-12 07:31:19.921  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 07:31:19.921  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 07:31:19.921  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 07:31:19.921  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 07:31:19.922  2822  2887 D BtGatt.ScanManager: handling starting scan
09-12 07:31:19.923  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 07:31:19.923  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 07:31:19.923  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 07:31:19.924  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 07:31:19.926  3935  3984 I io.jxcore.node.ConnectionHelper: start: OK
09-12 07:31:19.926  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.926  3935  3984 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 07:31:19.926  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:19.926  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 07:31:19.926  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.926  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 07:31:19.926  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 07:31:19.926  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 07:31:19.926  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 07:31:19.926  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 07:31:19.926  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 07:31:19.926  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 07:31:19.927  3935  3984 D BluetoothAdapter: STATE_ON
09-12 07:31:19.927  2822  2839 D BtGatt.GattService: stopScan() - queue size =1
09-12 07:31:19.929  2822  3045 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 07:31:19.929  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 07:31:19.929  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 07:31:19.929  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 07:31:19.929  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 07:31:19.929  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 07:31:19.931  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:19.931  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 07:31:19.931  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 07:31:19.931  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 07:31:19.931  2822  2874 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 07:31:19.931  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.932  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:19.932  2822  2887 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 07:31:19.933  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.933  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:19.933  3935  3984 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 07:31:19.933  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.933  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.933  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:19.933  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.933  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.933  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:19.933  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:19.933  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.933  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.933  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.933  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.933  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.936  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.936  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.937  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.937  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.937  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.937  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.937  3935  3984 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 07:31:19.938  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.938  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.938  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.938  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.938  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.938  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.938  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.938  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.938  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.938  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.938  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.938  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.938  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.938  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.939  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.939  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.940  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.940  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.940  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 07:31:19.940  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.940  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.941  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.941  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.941  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.941  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.941  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.941  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.941  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.941  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.941  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.941  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.941  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.941  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.945  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.945  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.945  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.946  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.946  3935  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 07:31:19.946  2822  2874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 07:31:19.946  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.946  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.946  2822  2887 D BtGatt.ScanManager: Starting BLE batch scan
09-12 07:31:19.947  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.947  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.947  2822  2887 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 07:31:19.947  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.947  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.947  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.947  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.947  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.947  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.947  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.947  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.947  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.947  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.947  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.948  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.948  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.948  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.948  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.949  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 07:31:19.949  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.949  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.949  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.949  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.949  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.949  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.949  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.949  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.949  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.949  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.949  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.949  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.949  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.949  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.950  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.950  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.950  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:19.950  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.951  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 07:31:19.952  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 07:31:19.952  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 07:31:19.952  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 07:31:19.952  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 07:31:19.952  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 07:31:19.952  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.952  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.952  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.953  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.953  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.953  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.953  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.953  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.953  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.953  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.953  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.953  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.953  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.953  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.954  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.955  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.955  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.955  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.956  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 07:31:19.958  3935  3984 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 07:31:19.958  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 07:31:19.961  2822  2874 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 07:31:19.962  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.967  2822  2874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 07:31:19.967  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.971  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 07:31:19.971  3935  3984 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 07:31:19.971  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 07:31:19.972  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 07:31:19.973  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 07:31:19.973  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 07:31:19.974  3935  3984 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 07:31:19.974  3935  3984 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 07:31:19.974  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 07:31:19.974  2822  2874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 07:31:19.974  3935  3984 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 07:31:19.974  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.974  3935  3984 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 07:31:19.974  2822  2887 D BtGatt.ScanManager: stopping BLe Batch
09-12 07:31:19.974  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 07:31:19.974  3935  3984 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 07:31:19.974  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 07:31:19.977  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 07:31:19.979  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 07:31:19.979  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 07:31:19.979  2822  2874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 07:31:19.979  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.979  2822  2887 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 07:31:19.979  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 07:31:19.979  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 07:31:19.979  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 07:31:19.979  3935  3984 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 07:31:19.980  3935  3984 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 07:31:19.980  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.980  3935  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 422)
09-12 07:31:19.980  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.981  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.981  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.981  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.981  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.981  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 07:31:19.981  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.981  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.982  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.982  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.982  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.982  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.982  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.982  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.982  3935  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 07:31:19.983  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.983  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.983  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.983  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.983  2822  2874 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 07:31:19.983  2822  2874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:19.984  3935  3984 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 07:31:19.984  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.984  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop ,everything
09-12 07:31:19.984  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.984  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.984  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.984  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.985  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.985  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.985  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.985  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 07:31:19.985  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.985  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.985  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.985  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.986  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.986  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.986  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.986  3935  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 422
,09-12 07:31:19.986  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.986  3935  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 422)
09-12 07:31:19.986  2822  3022 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-12 07:31:19.986  3935  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 422)
09-12 07:31:19.987  3935  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 422)
09-12 07:31:19.987  3935  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 07:31:19.988  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.988  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:19.988  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.989  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.989  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.989  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.989  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.989  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.989  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.989  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 07:31:19.989  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.989  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.989  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.989  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.990  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.990  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 07:31:19.990  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.990  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.991  3935  3984 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 07:31:19.991  3935  3984 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-12 07:31:19.991  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 07:31:19.991  3935  3984 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 07:31:19.991  3935  3984 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 07:31:19.991  3935  3984 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 07:31:19.991  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 07:31:19.991  3935  3984 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 07:31:19.991  3935  3984 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 07:31:19.991  3935  3984 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 07:31:19.991  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 07:31:19.991  3935  3984 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 07:31:19.991  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.992  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.992  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.992  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.992  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.992  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.992  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
,09-12 07:31:19.992  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.992  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.992  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.992  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.992  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.992  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.992  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.993  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.993  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.993  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:19.993  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.994  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.994  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.994  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.994  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.994  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.994  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.994  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.994  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.994  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.994  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.994  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.994  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:19.994  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.994  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.994  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.995  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:19.995  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:19.995  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:19.995  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 07:31:19.995  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.995  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.995  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:19.995  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:19.995  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.995  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:19.995  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:19.995  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.995  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:19.995  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:19.997  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:19.997  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:19.997  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:19.997  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:19.998  3935  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 07:31:19.998  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:19.999  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 07:31:20.000  3935  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 07:31:20.000  3935  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 07:31:20.000  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 07:31:20.000  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 07:31:20.000  3935  3935 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 07:31:20.000  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:20.000  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 07:31:20.000  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 07:31:20.000  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 07:31:20.000  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.000  3935  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 07:31:20.001  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
,09-12 07:31:20.001  3935  3935 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 07:31:20.001  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.001  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 07:31:20.001  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 07:31:20.001  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 07:31:20.001  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.001  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:20.001  3935  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 07:31:20.001  3935  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 07:31:20.002  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:20.002  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:20.002  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 07:31:20.002  3935  3935 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 07:31:20.002  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.002  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 07:31:20.002  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:20.002  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:20.002  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:20.002  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:20.002  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.003  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:20.003  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:20.003  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.003  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.003  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:20.003  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.003  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.003  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:20.003  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.004  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:20.004  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:20.004  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.004  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
,09-12 07:31:20.005  3935  3984 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 07:31:20.005  3935  3984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 07:31:20.005  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 07:31:20.005  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 07:31:20.005  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:20.005  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:20.005  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:20.005  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:20.005  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.005  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.006  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:20.006  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.006  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
,09-12 07:31:20.006  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:20.006  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.006  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.006  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:20.006  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.007  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:20.007  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 07:31:20.007  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.007  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.010  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:20.010  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:20.010  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:20.010  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:20.010  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.010  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.010  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
09-12 07:31:20.010  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.010  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.010  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 07:31:20.011  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.011  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.011  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.011  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.011  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:20.011  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 07:31:20.012  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:20.012  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.012  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:20.012  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:20.012  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:20.012  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 07:31:20.012  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:20.013  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.013  3935  3984 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5edd75c not in the list
,09-12 07:31:20.013  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:20.013  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.013  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:20.013  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.013  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.013  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:20.013  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:20.014  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:20.014  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 07:31:20.014  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:20.014  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0aea65 not in the list
09-12 07:31:20.015  3935  3984 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 07:31:20.015  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 07:31:20.015  3935  3984 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 07:31:20.015  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 07:31:20.015  3935  3984 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 07:31:20.015  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 07:31:20.016  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 07:31:20.016  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 07:31:20.017  3935  3984 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-12 07:31:20.017  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 07:31:20.017  3935  3984 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-12 07:31:20.017  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 07:31:20.017  3935  3984 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 07:31:20.017  3935  3984 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 07:31:20.018  3935  3984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 07:31:20.018  3935  3984 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 07:31:20.018  3935  3984 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 07:31:20.018  3935  3984 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 07:31:20.018  3935  3984 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 07:31:20.018  3935  3984 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 07:31:20.019  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:20.019  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@72a0cbf added. We now have 2 listener(s)
09-12 07:31:20.019  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:20.020  3935  3984 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 07:31:20.021   874  2128 D WifiService: setWifiEnabled: true pid=3935, uid=10000
09-12 07:31:20.021   874  2128 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 07:31:20.022  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:20.022  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@783cf8c added. We now have 3 listener(s)
09-12 07:31:20.022  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:20.026  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 07:31:20.026  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea436d5 added. We now have 4 listener(s)
09-12 07:31:20.026  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:20.028  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:20.028  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25e6eea added. We now have 5 listener(s)
09-12 07:31:20.028  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:20.030   874   885 D WifiService: setWifiEnabled: false pid=3935, uid=10000
09-12 07:31:20.030   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 07:31:20.035  2822  2869 D BluetoothAdapterState: Current state: ON, message: 23
09-12 07:31:20.035  2822  2869 D BluetoothAdapterProperties: Setting state to 13
,09-12 07:31:20.035  2822  2869 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 07:31:20.036  2822  2869 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 07:31:20.036  2822  2869 I BluetoothAdapterState: Entering PendingCommandState
09-12 07:31:20.036  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:20.037  2822  2874 D BluetoothAdapterProperties: Scan Mode:20
09-12 07:31:20.037  2822  2869 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 07:31:20.038  2822  2822 D BluetoothMapService: onReceive
09-12 07:31:20.038  2822  2822 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 07:31:20.038  2822  2822 D BluetoothMapService: STATE_TURNING_OFF
09-12 07:31:20.038  2822  2822 D BluetoothMapService: MAP Service closeService in
09-12 07:31:20.038  2822  2822 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 07:31:20.039  2822  2822 D ObexServerSockets0: shutdown(block = true)
09-12 07:31:20.039  2822  2822 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 07:31:20.039  2822  2822 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 07:31:20.039  2822  3022 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 07:31:20.039  2822  3046 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 07:31:20.040  2822  3047 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 07:31:20.040  2822  2822 I BtOppRfcommListener: stopping Accept Thread
09-12 07:31:20.041  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:20.041  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 07:31:20.042  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.042  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:20.042  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 07:31:20.042  2822  3573 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 07:31:20.042  2822  3573 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 07:31:20.046  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:20.047  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 07:31:20.049  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:20.050   874  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 07:31:20.050   874  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 07:31:20.050   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 07:31:20.050   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 07:31:20.052   874   887 I ActivityManager: Start proc 4004:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 07:31:20.058  2822  2822 D HeadsetService: Received stop request...Stopping profile...
09-12 07:31:20.060  1362  1375 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:20.060  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-12 07:31:20.060  1961  1976 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:20.061  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:20.061  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 07:31:20.062  2822  2822 D A2dpService: Received stop request...Stopping profile...
09-12 07:31:20.062   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:20.062   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:20.062   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:20.062  2822  3040 D A2dpStateMachine: Exit Disconnected: -1
09-12 07:31:20.063  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:20.063  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:20.063   874  2098 D DhcpClient: Clearing IP address
09-12 07:31:20.064   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 07:31:20.064  1362  1362 D BluetoothA2dp: Proxy object disconnected
09-12 07:31:20.064   874   874 D BluetoothA2dp: Proxy object disconnected
09-12 07:31:20.065  2822  2822 D HidService: Received stop request...Stopping profile...
09-12 07:31:20.066  2822  2822 D HidService: Stopping Bluetooth HidService
09-12 07:31:20.066  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:20.068  1362  1362 D BluetoothInputDevice: Proxy object disconnected
09-12 07:31:20.068  1362  1362 D HidProfile: Bluetooth service disconnected
09-12 07:31:20.069  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:20.069   372   872 D CommandListener: Setting iface cfg
09-12 07:31:20.071  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:20.071  1501  2555 V NativeCrypto: Read error: ssl=0x9a6ae200: I/O error during system call, Connection timed out
09-12 07:31:20.071  2822  2822 D HealthService: Received stop request...Stopping profile...
09-12 07:31:20.071   874  2102 D DhcpClient: Receive thread stopped
09-12 07:31:20.072  1501  2555 V NativeCrypto: SSL shutdown failed: ssl=0x9a6ae200: I/O error during system call, Broken pipe
09-12 07:31:20.073   874   885 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-12 07:31:20.074   874  2091 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-12 07:31:20.075   874  2091 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-12 07:31:20.076   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-12 07:31:20.076   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-12 07:31:20.080   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 07:31:20.080  2822  2822 D PanService: Received stop request...Stopping profile...
09-12 07:31:20.081   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 07:31:20.081   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-12 07:31:20.084   398   398 E Parcel  : Reading a NULL string not supported here.
09-12 07:31:20.085   874  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 07:31:20.085   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 07:31:20.087   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 07:31:20.087  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 07:31:20.087  1362  1362 D PanProfile: Bluetooth service disconnected
09-12 07:31:20.088   874  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 07:31:20.089  2822  2822 D BluetoothMapService: Received stop request...Stopping profile...
09-12 07:31:20.089  2822  2822 D BluetoothMapService: stop()
09-12 07:31:20.090  2822  2822 D BluetoothMapAppObserver: deinitObservers()
09-12 07:31:20.090  2822  2822 D BluetoothMapAppObserver: removeReceiver()
,09-12 07:31:20.092  2822  2822 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:20.092  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.092  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:20.092  2822  2822 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:20.093  2822  2822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 07:31:20.093  2822  2822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 07:31:20.094  2822  3017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:20.094  2822  3017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:20.094  2822  3017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:20.094  2822  2822 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:20.094  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.094  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:20.094  2822  2874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-12 07:31:20.094  2822  2822 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:20.094  2822  2874 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-12 07:31:20.096  2822  2822 V BluetoothAdapterState: isTurningOff()=true
,09-12 07:31:20.096  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.096  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 07:31:20.096  2822  2822 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:20.097  2822  2874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 07:31:20.097  2822  3017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:20.097  2822  3017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:20.097  2822  2822 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 07:31:20.097  2822  3017 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 07:31:20.097  2822  3017 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 07:31:20.097  2822  3017 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 07:31:20.097  2822  3017 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 07:31:20.097  2822  2874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 07:31:20.097  2822  2822 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 07:31:20.099  2822  2822 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:20.099  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.099  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:20.099  2822  2822 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:20.099  2822  2822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 07:31:20.100  2822  2874 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 07:31:20.100  2822  2822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 07:31:20.100  2822  2822 V BluetoothAdapterState: isTurningOff()=true
,09-12 07:31:20.100  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.100  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:20.101  2822  2822 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:20.101  2822  2822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 07:31:20.101  2822  2822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 07:31:20.103  2822  2822 D BluetoothMapService: MAP Service closeService in
,09-12 07:31:20.103  2822  2822 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:20.103  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.103  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:20.103  2822  2822 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:20.103  2822  2869 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-12 07:31:20.103  2822  2869 D BluetoothAdapterProperties: Setting state to 15
09-12 07:31:20.104  2822  2869 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 07:31:20.104  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:20.105  1362  2064 D BluetoothPan: onBluetoothStateChange on: false
09-12 07:31:20.105  1362  1386 D BluetoothMap: onBluetoothStateChange: up=false
09-12 07:31:20.106  2822  2869 I BluetoothAdapterState: Entering BleOnState
09-12 07:31:20.106   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 07:31:20.106  2822  2822 D BluetoothMapService: cleanup()
09-12 07:31:20.106  1961  1975 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:20.106  2822  2822 D BluetoothMapService: MAP Service closeService in
,09-12 07:31:20.106   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:20.106   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:20.106   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 07:31:20.107  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 07:31:20.107  1362  2064 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 07:31:20.108   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:20.108  1362  1386 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 07:31:20.109  2822  2869 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 07:31:20.109  2822  2869 D BluetoothAdapterProperties: Setting state to 16
,09-12 07:31:20.109  2822  2869 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 07:31:20.111  2822  2869 D BluetoothAdapterProperties: onBleDisable
,09-12 07:31:20.111  2822  2869 I BluetoothAdapterState: Entering PendingCommandState
,09-12 07:31:20.111  2822  2870 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 07:31:20.112  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:20.112  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:20.112  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.112  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:20.113  2822  3017 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 07:31:20.113  2822  3017 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:20.113  2822  2874 D BluetoothAdapterProperties: Scan Mode:20
,09-12 07:31:20.114  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:20.114  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:20.114  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.114  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:20.115  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:20.116  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:20.129  4004  4004 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 07:31:20.134   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:20.135   874  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 07:31:20.135   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:20.137   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 07:31:20.139   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 07:31:20.140  3539  3539 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7419963 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-12 07:31:20.142  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:20.142  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:20.143  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:20.143  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:20.144  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:20.145  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:20.145  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:20.145  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:20.146  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 07:31:20.146   874  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 07:31:20.147  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:20.148  1894  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 07:31:20.156  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 07:31:20.160  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 07:31:20.171   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc52aa7:true
,09-12 07:31:20.173   874  1695 I ActivityManager: Start proc 4023:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 07:31:20.182  4004  4004 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 07:31:20.183  4004  4004 D BluetoothMap: Create BluetoothMap proxy object
,09-12 07:31:20.192  4004  4004 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 07:31:20.202   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 07:31:20.202  4023  4023 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
09-12 07:31:20.203   874  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 07:31:20.203   874  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 07:31:20.206  4004  4004 D DockEventReceiver: finishStartingService: stopping service
,09-12 07:31:20.212   874  2005 I ActivityManager: Killing 2782:com.google.android.talk/u0a61 (adj 15): empty #17
,09-12 07:31:20.316  2822  2874 I bt_hci  : shut_down
,09-12 07:31:20.316  2822  2892 D bt_hwcfg: hw_epilog_process
09-12 07:31:20.317  2822  2892 I bt_vendor: low_power_mode_cb
,09-12 07:31:20.343  2822  2892 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 07:31:20.343  2822  2892 I bt_vendor: epilog_cb
09-12 07:31:20.343  2822  2892 I bt_hci  : epilog_finished_callback
,09-12 07:31:20.357  2822  2874 I bt_hci_h4: hal_close
,09-12 07:31:20.357  2822  2874 I bt_userial_vendor: device fd = 51 close
,09-12 07:31:20.464  4023  4023 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.464  4023  4023 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.464  4023  4023 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.464  4023  4023 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.464  4023  4023 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.464  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.466  4023  4023 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.466  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.467  4023  4023 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 07:31:20.467  4023  4023 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704),
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:31:20.467  4023  4023 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 07:31:20.504  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 07:31:20.518   874   885 I ActivityManager: Start proc 4055:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-12 07:31:20.519   874   885 I ActivityManager: Killing 3539:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 07:31:20.589  2822  2870 D bt_stack_manager: event_shut_down_stack finished.
,09-12 07:31:20.590  2822  2869 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 07:31:20.592  2822  2869 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 07:31:20.592  2822  2822 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 07:31:20.593  2822  2822 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 07:31:20.593  2822  2822 D BtGatt.GattService: stop()
,09-12 07:31:20.593  2822  2822 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 07:31:20.596  2822  2822 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:20.597  2822  2822 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:20.597  2822  2822 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:20.597  2822  2822 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 07:31:20.597  2822  2869 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 07:31:20.598  2822  2869 D BluetoothAdapterProperties: Setting state to 10
09-12 07:31:20.598  2822  2869 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 07:31:20.599  4055  4055 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-12 07:31:20.599  2822  2869 I BluetoothAdapterState: Entering OffState
09-12 07:31:20.599   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 07:31:20.609  2822  2822 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 07:31:20.609  2822  2822 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 07:31:20.609  2822  2822 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 07:31:20.610  2822  2870 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 07:31:20.613  2822  2870 D bt_stack_manager: event_clean_up_stack finished.
,09-12 07:31:20.624  2822  2822 I art     : System.exit called, status: 0
,09-12 07:31:20.624  2822  2822 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 07:31:20.690   874  2127 I ActivityManager: Process com.android.bluetooth (pid 2822) has died
,09-12 07:31:20.858  4055  4075 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-12 07:31:20.858  4055  4075 I Babel_SMS: MmsConfig.loadMmsSettings
,09-12 07:31:20.866  4055  4075 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 07:31:20.866  4055  4075 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 07:31:20.899  4055  4075 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-12 07:31:20.900  4055  4075 I Babel_SMS: MmsConfig.loadFromResources
09-12 07:31:20.901  4055  4075 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-12 07:31:20.901  4055  4075 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-12 07:31:20.928  4023  4048 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 07:31:20.930  4055  4055 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 07:31:20.932  4055  4055 I Babel_Crash: startup - clean
,09-12 07:31:20.949  4055  4055 I Babel_telephony: TeleModule.launchCompleted
,09-12 07:31:20.958   874  2128 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 07:31:20.972  4055  4055 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-12 07:31:20.979  4055  4055 W Babel   : BAM#gBA: invalid account id: -1
,09-12 07:31:20.979  4055  4055 W Babel   : BAM#gBA: invalid account id: -1
09-12 07:31:20.979  4055  4055 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-12 07:31:20.984  4055  4080 I Babel   : deleted: false for 0
,09-12 07:31:20.991   874   885 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-12 07:31:21.002  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 07:31:21.040   874  2127 I ActivityManager: Start proc 4083:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-12 07:31:21.041  4004  4004 D DockEventReceiver: finishStartingService: stopping service
,09-12 07:31:21.064  4055  4055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 07:31:21.134   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ea054c:true
,09-12 07:31:21.144  4055  4055 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 07:31:21.158  4055  4055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 07:31:21.160  4055  4055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 07:31:21.182  4055  4055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 07:31:21.199  4055  4055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 07:31:21.207  4055  4055 I vclib   : onServiceConnected
,09-12 07:31:21.228  4083  4083 D AdapterServiceConfig: Adding HeadsetService
09-12 07:31:21.228  4083  4083 D AdapterServiceConfig: Adding A2dpService
09-12 07:31:21.228  4083  4083 D AdapterServiceConfig: Adding HidService
09-12 07:31:21.228  4083  4083 D AdapterServiceConfig: Adding HealthService
09-12 07:31:21.228  4083  4083 D AdapterServiceConfig: Adding PanService
09-12 07:31:21.229  4083  4083 D AdapterServiceConfig: Adding GattService
09-12 07:31:21.229  4083  4083 D AdapterServiceConfig: Adding BluetoothMapService
09-12 07:31:21.231   874  1694 I ActivityManager: Killing 3698:com.google.android.deskclock/u0a44 (adj 15): empty #17
,09-12 07:31:21.322  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 07:31:21.341  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 07:31:21.347  1719  1719 D SystemUpdateService: onCreate
,09-12 07:31:21.352  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 07:31:21.361  1719  4095 I SystemUpdateService: active receiver: enabled
,09-12 07:31:21.370  1719  4095 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 07:31:21.374  1719  4095 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 07:31:21.374  1719  4095 I SystemUpdateService: now status is 0 (complete)
09-12 07:31:21.374  1719  4095 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 07:31:21.374  1719  4095 I SystemUpdateService: file has been verified
09-12 07:31:21.374  1719  4095 I SystemUpdateService: OTA package size = 12249756
,09-12 07:31:21.379  1719  4095 I SystemUpdateService: showing system update notification
09-12 07:31:21.379  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 07:31:21.386  1719  2520 I iu.UploadsManager: num queued entries: 0
,09-12 07:31:21.387  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-12 07:31:21.389  1719  2520 I iu.SyncManager: NEXT; no task
,09-12 07:31:21.399  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 07:31:21.402  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 07:31:21.420   874  1387 I ActivityManager: Start proc 4097:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 07:31:21.424  1719  1719 D SystemUpdateService: onDestroy
,09-12 07:31:21.472  4097  4097 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 07:31:21.474  4097  4097 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:21.481  4097  4097 D SprintDMHelper: simOperator: 
,09-12 07:31:21.481  4097  4097 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 07:31:21.502   874  2006 I ActivityManager: Start proc 4109:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 07:31:21.505   874  2006 I ActivityManager: Killing 3382:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 07:31:21.673   874  1598 I ActivityManager: Start proc 4124:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 07:31:21.680  4055  4123 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 07:31:21.711   874  1387 I ActivityManager: Killing 3176:android.process.acore/u0a5 (adj 15): empty #17
,09-12 07:31:21.721  4124  4124 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 07:31:21.815  4124  4124 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 07:31:21.815  4124  4124 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 07:31:21.815  4124  4124 I GAv4    :   adb logcat -s GAv4
,09-12 07:31:21.833  4124  4124 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 07:31:21.840  4124  4124 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 07:31:21.864  4124  4141 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 07:31:21.979  4124  4124 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 07:31:22.015  4124  4124 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 07:31:22.034  4124  4124 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 6040-6053)
,09-12 07:31:22.034  4124  4124 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 07:31:22.044  4124  4124 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4863b45}
,09-12 07:31:22.044  4124  4124 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 07:31:22.045  4124  4124 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 07:31:22.054  4124  4124 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 07:31:22.056  4124  4124 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 07:31:22.073  4124  4124 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 07:31:22.090  4124  4124 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 07:31:22.090  4124  4124 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 07:31:22.090  4124  4124 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 07:31:22.090  4124  4124 I Adreno  : Build Date                       : 10/20/15
09-12 07:31:22.090  4124  4124 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 07:31:22.090  4124  4124 I Adreno  : Local Branch                     : M14
09-12 07:31:22.090  4124  4124 I Adreno  : Remote Branch                    : 
09-12 07:31:22.090  4124  4124 I Adreno  : Remote Branch                    : 
09-12 07:31:22.090  4124  4124 I Adreno  : Reconstruct Branch               : 
,09-12 07:31:22.149  4124  4124 I NSApplication: Starting up...
,09-12 07:31:22.159  4124  4170 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 07:31:22.189   874  2126 I ActivityManager: Start proc 4175:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-12 07:31:22.190   874  2126 I ActivityManager: Killing 3766:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 07:31:22.273  4175  4175 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 07:31:22.459   874  1694 I ActivityManager: Killing 3781:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 07:31:22.532   874  1695 I ActivityManager: Start proc 4189:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 07:31:22.613  4189  4189 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 07:31:22.667  4189  4189 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 07:31:22.732   874  2125 I ActivityManager: Killing 3604:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 07:31:23.045   874  1387 D WifiService: setWifiEnabled: true pid=3935, uid=10000
,09-12 07:31:23.045   874  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 07:31:23.058   874  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-12 07:31:23.066  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:23.067  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:23.067  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:23.067  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:23.070  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:23.071  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:23.071  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:23.071  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:23.109   874  1304 D WifiConfigStore: loaded 0 passpoint configs
,09-12 07:31:23.110   874  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 07:31:23.110   874  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 07:31:23.111   874  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 07:31:23.111   874  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 07:31:23.112   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 07:31:23.112   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 07:31:23.126   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 07:31:23.127   372   872 D CommandListener: Setting iface cfg
,09-12 07:31:23.128   874  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-12 07:31:23.128   874  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 07:31:23.128   874  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.00 rxSuccessRate=16.38 delta 1000 -> 994
,09-12 07:31:23.131   874  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 07:31:23.131   874  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 07:31:23.150   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 07:31:23.150   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 07:31:23.155   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 07:31:23.199   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 07:31:23.201  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 07:31:23.620  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 07:31:23.668  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 07:31:23.669  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 07:31:23.681   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 07:31:23.690   874  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 07:31:23.690   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 07:31:23.691   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 07:31:23.709   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 07:31:23.721   372   872 D CommandListener: Setting iface cfg
,09-12 07:31:23.723   874  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 07:31:23.734   874  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-12 07:31:23.735   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 07:31:23.744   874  4223 D DhcpClient: Receive thread started
,09-12 07:31:23.823   874  1304 E native  : do suspend false
,09-12 07:31:23.841   874  2098 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 07:31:23.866   874  4223 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,09-12 07:31:23.867   874  2098 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,09-12 07:31:23.871   874  2098 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 07:31:23.884   874  4223 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 07:31:23.885   874  2098 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 07:31:23.890   372   872 D CommandListener: Setting iface cfg
,09-12 07:31:23.901   874  2098 D DhcpClient: Scheduling renewal in 86399s
,09-12 07:31:23.902   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 07:31:23.918   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 07:31:23.920   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 07:31:23.920   874  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 07:31:23.921   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 07:31:23.923   874  1307 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 07:31:23.938   874  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 07:31:24.000   874  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 07:31:24.000   874  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 07:31:24.005   874  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 07:31:24.011   874  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 07:31:24.014   874  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 07:31:24.025   874  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 07:31:24.029   874  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 07:31:24.030   874  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-12 07:31:24.030   874  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 07:31:24.031   874  1307 D ConnectivityService:    accepting network in place of null
,09-12 07:31:24.032   874  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 07:31:24.032   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 07:31:24.033   874  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 07:31:24.038   874  4222 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138057, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 07:31:24.078   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:24.112   874  4221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 07:31:24.113   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:24.119   874  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 07:31:24.119   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:24.124   874  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 07:31:24.128   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 07:31:24.140  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:24.140  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:24.141  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:24.141  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:24.146  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:24.146  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 07:31:24.146  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:24.146  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:24.155  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 07:31:24.159  1719  1719 D SystemUpdateService: onCreate
,09-12 07:31:24.164  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 07:31:24.170  1719  4234 I SystemUpdateService: active receiver: enabled
,09-12 07:31:24.174  1719  4234 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 07:31:24.175  1719  4234 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 07:31:24.175  1719  4234 I SystemUpdateService: now status is 0 (complete)
09-12 07:31:24.175  1719  4234 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 07:31:24.176  1719  4234 I SystemUpdateService: file has been verified
09-12 07:31:24.176  1719  4234 I SystemUpdateService: OTA package size = 12249756
,09-12 07:31:24.178   874  4221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 05:31:24 GMT], X-Android-Received-Millis=[1473658284177], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473658284153]}
,09-12 07:31:24.179   874  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 07:31:24.179   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-12 07:31:24.181   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 07:31:24.182   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 07:31:24.187  1719  4234 I SystemUpdateService: showing system update notification
,09-12 07:31:24.189  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 07:31:24.191  1719  2520 I iu.UploadsManager: num queued entries: 0
09-12 07:31:24.191  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-12 07:31:24.192  1719  2520 I iu.SyncManager: NEXT; no task
,09-12 07:31:24.202  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 07:31:24.203  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 07:31:24.205  4097  4097 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:24.207  1719  1719 D SystemUpdateService: onDestroy
,09-12 07:31:24.211  1719  4238 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 07:31:24.211  1719  4238 W BaseAppContext: Using Auth Proxy for data requests.
09-12 07:31:24.212  4097  4097 D SprintDMHelper: simOperator: 
09-12 07:31:24.212  4097  4097 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 07:31:24.212  1719  4238 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 07:31:24.222  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:24.223  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:24.268  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 07:31:24.268  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 07:31:24.268  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:31:24.268  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:24.284  1719  4238 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-12 07:31:24.345  4055  4240 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 07:31:25.121   874  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 07:31:25.977  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:26.025  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:31:26.025  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:31:26.026  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:31:26.026  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:26.051   874  2006 D WifiService: setWifiEnabled: false pid=3935, uid=10000
,09-12 07:31:26.052   874  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 07:31:26.071  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:31:26.072  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:31:26.072  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 07:31:26.084  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 07:31:26.086   874  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 07:31:26.086   874  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 07:31:26.087   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 07:31:26.087   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 07:31:26.090   874   885 I ActivityManager: Killing 3805:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 07:31:26.102   874  2098 D DhcpClient: Clearing IP address
,09-12 07:31:26.102   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 07:31:26.109  1501  4246 V NativeCrypto: Read error: ssl=0x9a685e00: I/O error during system call, Connection timed out
,09-12 07:31:26.111   372   872 D CommandListener: Setting iface cfg
,09-12 07:31:26.111  1501  4246 V NativeCrypto: SSL shutdown failed: ssl=0x9a685e00: I/O error during system call, Broken pipe
09-12 07:31:26.113   874  4223 D DhcpClient: Receive thread stopped
,09-12 07:31:26.117   874  2125 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-12 07:31:26.117   874  4221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-12 07:31:26.120   874  4221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 07:31:26.121   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-12 07:31:26.121   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 07:31:26.124   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 07:31:26.161   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 07:31:26.162   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 07:31:26.167   874  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 07:31:26.168   398   398 E Parcel  : Reading a NULL string not supported here.
09-12 07:31:26.168   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 07:31:26.175   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 07:31:26.187   874  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 07:31:26.188   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 07:31:26.191  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:26.191  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 07:31:26.191  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:26.191  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:26.192  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:26.192  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:26.192  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:26.192  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:26.195  1894  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 07:31:26.199   874  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 07:31:26.217   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:26.244   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:26.245   874  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 07:31:26.245   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:26.251   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 07:31:26.253  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:26.253  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:26.253  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:26.258  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 07:31:26.261  1719  1719 D SystemUpdateService: onCreate
09-12 07:31:26.263  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 07:31:26.273  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-12 07:31:26.274  1719  4257 I SystemUpdateService: active receiver: enabled
09-12 07:31:26.276  1719  2520 I iu.UploadsManager: num queued entries: 0
09-12 07:31:26.277  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-12 07:31:26.281  1719  4257 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 07:31:26.283  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 07:31:26.284  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 07:31:26.285  4097  4097 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:26.289  4097  4097 D SprintDMHelper: simOperator: 
,09-12 07:31:26.289  4097  4097 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 07:31:26.295  1719  2520 I iu.SyncManager: NEXT; no task
,09-12 07:31:26.298  1719  4257 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 07:31:26.299  1719  4257 I SystemUpdateService: now status is 0 (complete)
,09-12 07:31:26.299  1719  4257 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 07:31:26.299  1719  4257 I SystemUpdateService: file has been verified
,09-12 07:31:26.303  4055  4261 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 07:31:26.299  1719  4257 I SystemUpdateService: OTA package size = 12249756
,09-12 07:31:26.315   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 07:31:26.316   874  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 07:31:26.316   874  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 07:31:26.327  1719  4257 I SystemUpdateService: showing system update notification
,09-12 07:31:26.335  1719  1719 D SystemUpdateService: onDestroy
,09-12 07:31:29.110   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c01eee9:true
,09-12 07:31:29.110  4083  4083 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 07:31:29.116  4083  4083 I bt_bluedroid: init
,09-12 07:31:29.117  4083  4266 I BluetoothAdapterState: Entering OffState
,09-12 07:31:29.121  4083  4267 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 07:31:29.122  4083  4267 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 07:31:29.122  4083  4267 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 07:31:29.123  4083  4267 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 07:31:29.124  4083  4083 I bt_bluedroid: get_profile_interface socket
,09-12 07:31:29.127  4083  4083 I bt_bluedroid: get_profile_interface sdp
,09-12 07:31:29.130  4083  4270 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 07:31:29.131  4083  4094 I bt_bluedroid: config_hci_snoop_log
,09-12 07:31:29.133  4083  4270 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 07:31:29.133   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 07:31:29.139  4083  4266 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 07:31:29.140  4083  4266 D BluetoothAdapterProperties: Setting state to 14
09-12 07:31:29.140  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 07:31:29.144  4083  4266 D BluetoothBondStateMachine: make
,09-12 07:31:29.147  4083  4271 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 07:31:29.150  4083  4266 I BluetoothAdapterState: Entering PendingCommandState
09-12 07:31:29.151  4083  4083 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 07:31:29.154  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:29.154  4083  4083 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 07:31:29.155  4083  4083 D BtGatt.GattService: Received start request. Starting profile...
09-12 07:31:29.155  4083  4083 D BtGatt.GattService: start()
09-12 07:31:29.155  4083  4083 I bt_bluedroid: get_profile_interface gatt
09-12 07:31:29.156  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:29.156  4083  4083 D BtGatt.AdvertiseManager: advertise manager created
09-12 07:31:29.161  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-12 07:31:29.161  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:29.161  4083  4083 V BluetoothAdapterState: isBleTurningOn()=true
09-12 07:31:29.161  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:29.161  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 07:31:29.162  4083  4266 I bt_bluedroid: enable
09-12 07:31:29.162  4083  4267 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 07:31:29.162  4083  4267 I bt_hci  : start_up
,09-12 07:31:29.168  4083  4267 I bt_vendor: alloc value 0xb3a29189
,09-12 07:31:29.168  4083  4267 I bt_vendor: init
09-12 07:31:29.168  4083  4267 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 07:31:29.168  4083  4267 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 07:31:29.276  4083  4267 D bt_hci  : start_up starting async portion
09-12 07:31:29.276  4083  4274 I bt_hci  : event_finish_startup
,09-12 07:31:29.276  4083  4274 I bt_hci_h4: hal_open,
,09-12 07:31:29.276  4083  4274 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 07:31:29.285  4083  4274 I bt_userial_vendor: device fd = 51 open
,09-12 07:31:29.317  4083  4274 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 07:31:29.349  4083  4274 D bt_hwcfg: Chipset BCM4354A2
,09-12 07:31:29.350  4083  4274 D bt_hwcfg: Target name = [BCM4354A2]
09-12 07:31:29.350  4083  4274 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 07:31:30.030  4083  4274 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 07:31:30.031  4083  4274 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 07:31:30.031  4083  4274 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 07:31:30.148  4083  4274 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 07:31:30.149  4083  4274 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 07:31:30.178  4083  4274 I bt_hwcfg: vendor lib fwcfg completed
,09-12 07:31:30.179  4083  4274 I bt_vendor: firmware callback
09-12 07:31:30.179  4083  4274 I bt_hci  : firmware_config_callback
,09-12 07:31:30.190  4083  4276 I bt_btu  : btu_task pending for preload complete event
,09-12 07:31:30.191  4083  4276 I bt_btu_task: Bluetooth chip preload is complete
09-12 07:31:30.191  4083  4276 I bt_btu  : btu_task received preload complete event
,09-12 07:31:30.201  4083  4276 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 07:31:30.201  4083  4276 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 07:31:30.201  4083  4276 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 07:31:30.201  4083  4276 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 07:31:30.202  4083  4276 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 07:31:30.202  4083  4276 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 07:31:30.202  4083  4276 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 07:31:30.203  4083  4276 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 07:31:30.203  4083  4276 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 07:31:30.203  4083  4276 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 07:31:30.203  4083  4276 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 07:31:30.204  4083  4276 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 07:31:30.204  4083  4276 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 07:31:30.204  4083  4276 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 07:31:30.204  4083  4276 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 07:31:30.338  4083  4276 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a6d9d
,09-12 07:31:30.339  4083  4276 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a6d9d 
,09-12 07:31:30.350  4083  4270 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 07:31:30.351  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 07:31:30.352  4083  4270 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 07:31:30.356  4083  4270 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 07:31:30.361  4083  4270 D BluetoothAdapterProperties: Scan Mode:20
,09-12 07:31:30.362  4083  4270 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 07:31:30.362  4083  4270 D bt_hci  : do_postload posting postload work item
09-12 07:31:30.362  4083  4274 I bt_hci  : event_postload
09-12 07:31:30.362  4083  4274 I bt_vendor: sco_config_cb
09-12 07:31:30.363  4083  4274 I bt_hci  : sco_config_callback postload finished.
,09-12 07:31:30.366  4083  4270 D bt_bte_conf: Device ID record 1 : primary
,09-12 07:31:30.366  4083  4270 D bt_bte_conf:   vendorId            = 000f
09-12 07:31:30.367  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:30.367  4083  4270 D bt_bte_conf:   vendorIdSource      = 0001
09-12 07:31:30.368  4083  4270 D bt_bte_conf:   product             = 1200
,09-12 07:31:30.371  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:30.368  4083  4270 D bt_bte_conf:   version             = 1436
,09-12 07:31:30.372  4083  4270 D bt_bte_conf:   clientExecutableURL = 
09-12 07:31:30.374  4083  4270 D bt_bte_conf:   serviceDescription  = 
09-12 07:31:30.374  4083  4270 D bt_bte_conf:   documentationURL    = 
,09-12 07:31:30.374  4083  4270 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 07:31:30.375  4083  4274 I bt_vendor: low_power_mode_cb
,09-12 07:31:30.375  4083  4267 D bt_stack_manager: event_start_up_stack finished
09-12 07:31:30.376  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 07:31:30.378  4083  4266 D BluetoothAdapterProperties: Setting state to 15
09-12 07:31:30.378  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 07:31:30.379  4083  4266 I BluetoothAdapterState: Entering BleOnState
,09-12 07:31:30.382  4083  4266 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 07:31:30.382  4083  4266 D BluetoothAdapterProperties: Setting state to 11
09-12 07:31:30.382  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 07:31:30.392  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:30.394  4083  4083 D HeadsetService: Received start request. Starting profile...
09-12 07:31:30.394  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:30.396  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:30.399  4083  4083 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 07:31:30.400  4083  4083 D HeadsetStateMachine: make
,09-12 07:31:30.408  4083  4266 I BluetoothAdapterState: Entering PendingCommandState
09-12 07:31:30.410  4083  4083 D HeadsetStateMachine: max_hf_connections = 1
09-12 07:31:30.410  4083  4083 I bt_bluedroid: get_profile_interface handsfree
09-12 07:31:30.411  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 07:31:30.411  4083  4270 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 07:31:30.414  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:30.415  4083  4083 D A2dpService: Received start request. Starting profile...
,09-12 07:31:30.415  4083  4083 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 07:31:30.415  4083  4083 I bt_bluedroid: get_profile_interface avrcp
09-12 07:31:30.421  4083  4083 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 07:31:30.421  4083  4083 I BluetoothA2dpServiceJni: classInitNative: succeeds,
09-12 07:31:30.421  4083  4083 D A2dpStateMachine: make
09-12 07:31:30.422  4083  4083 I bt_bluedroid: get_profile_interface a2dp
09-12 07:31:30.422  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 07:31:30.426  4083  4083 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 07:31:30.427  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:30.428  4083  4285 D A2dpStateMachine: Enter Disconnected: -2
,09-12 07:31:30.428  4083  4083 D HidService: Received start request. Starting profile...
09-12 07:31:30.429  4004  4004 D BluetoothInputDevice: Proxy object connected
09-12 07:31:30.429  4083  4083 I bt_bluedroid: get_profile_interface hidhost
,09-12 07:31:30.429  4083  4270 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39883e5
09-12 07:31:30.429  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 07:31:30.429  4004  4004 D HidProfile: Bluetooth service connected
,09-12 07:31:30.429  4083  4083 D HidService: setHidService(): set to: null
09-12 07:31:30.431  4083  4083 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 07:31:30.431  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 07:31:30.432  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:30.432  4083  4083 D HealthService: Received start request. Starting profile...
,09-12 07:31:30.434  4083  4083 I bt_bluedroid: get_profile_interface health
,09-12 07:31:30.435  4083  4083 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 07:31:30.435  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:30.437  4083  4083 D PanService: Received start request. Starting profile...
,09-12 07:31:30.437  4004  4004 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 07:31:30.437  4083  4083 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 07:31:30.437  4083  4083 I bt_bluedroid: get_profile_interface pan
09-12 07:31:30.437  4004  4004 D PanProfile: Bluetooth service connected
,09-12 07:31:30.437  4083  4270 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 07:31:30.440  4083  4083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:30.441  4004  4004 D BluetoothMap: Proxy object connected
,09-12 07:31:30.441  4083  4083 D BluetoothMapService: Received start request. Starting profile...
09-12 07:31:30.441  4083  4083 D BluetoothMapService: start()
09-12 07:31:30.441  4004  4004 D MapProfile: Bluetooth service connected
,09-12 07:31:30.442  4004  4004 D BluetoothMap: getConnectedDevices()
09-12 07:31:30.442  4004  4004 D BluetoothMap: Bluetooth is Not enabled
,09-12 07:31:30.443  4083  4083 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 07:31:30.444  4083  4083 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 07:31:30.444  4083  4083 D BluetoothMapAppObserver: createReceiver()
,09-12 07:31:30.445  4083  4083 D BluetoothMapAppObserver: initObservers()
,09-12 07:31:30.445  4083  4083 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 07:31:30.454  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:30.454  4083  4083 V BluetoothAdapterState: isTurningOn()=true
09-12 07:31:30.454  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false,
09-12 07:31:30.454  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isTurningOn()=true
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:30.456  4083  4283 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isTurningOn()=true
,09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:30.456  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:30.457  4083  4083 V BluetoothAdapterState: isTurningOff()=false
09-12 07:31:30.457  4083  4083 V BluetoothAdapterState: isTurningOn()=true
,09-12 07:31:30.457  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:30.457  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:30.457  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:30.458  4083  4083 V BluetoothAdapterState: isTurningOn()=true
,09-12 07:31:30.458  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:30.458  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:30.458  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:30.458  4083  4083 V BluetoothAdapterState: isTurningOn()=true
,09-12 07:31:30.458  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 07:31:30.459  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:30.459  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 07:31:30.459  4083  4266 D BluetoothAdapterProperties: ScanMode =  20
,09-12 07:31:30.459  4083  4266 D BluetoothAdapterProperties: State =  11
,09-12 07:31:30.464  4083  4270 D BluetoothAdapterProperties: Scan Mode:21
,09-12 07:31:30.464  4083  4270 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 07:31:30.464  4083  4266 D BluetoothAdapterProperties: Setting state to 12
09-12 07:31:30.464  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 07:31:30.465  4083  4266 I BluetoothAdapterState: Entering OnState
09-12 07:31:30.465  1362  2064 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:30.465  1362  1375 D BluetoothPan: onBluetoothStateChange on: true
09-12 07:31:30.467  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 07:31:30.467  1362  1362 D PanProfile: Bluetooth service connected
09-12 07:31:30.467  4004  4014 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 07:31:30.468  1362  2064 D BluetoothMap: onBluetoothStateChange: up=true
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:30.468  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:30.469  1362  1362 D BluetoothMap: Proxy object connected
09-12 07:31:30.469  1362  1362 D MapProfile: Bluetooth service connected
,09-12 07:31:30.469  1362  1362 D BluetoothMap: getConnectedDevices()
09-12 07:31:30.469  1961  2120 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:30.470   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:30.470   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:30.470   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 07:31:30.470  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:30.472   874   874 D BluetoothA2dp: Proxy object connected
09-12 07:31:30.472  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 07:31:30.473  4083  4083 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 07:31:30.474  1362  1362 D BluetoothInputDevice: Proxy object connected
09-12 07:31:30.474  1362  1362 D HidProfile: Bluetooth service connected
09-12 07:31:30.474  4083  4083 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:30.475  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:30.475  4083  4083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 07:31:30.476  4004  4015 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 07:31:30.477  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:30.479  4083  4083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 07:31:30.479  4004  4014 D BluetoothMap: onBluetoothStateChange: up=true
09-12 07:31:30.479  1362  1386 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 07:31:30.480  4083  4083 D ObexServerSockets: Succeed to create listening sockets 
,09-12 07:31:30.480  4083  4083 D ObexServerSockets0: startAccept()
09-12 07:31:30.480  4083  4083 D ObexServerSockets0: prepareForNewConnect()
09-12 07:31:30.481   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:30.481  1362  2064 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 07:31:30.482  4083  4083 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 07:31:30.482  4083  4083 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 07:31:30.482  1362  1362 D BluetoothA2dp: Proxy object connected
09-12 07:31:30.483  4004  4015 D BluetoothPan: onBluetoothStateChange on: true
09-12 07:31:30.483  4083  4292 D ObexServerSockets0: Accepting socket connection...
09-12 07:31:30.484  4083  4293 D ObexServerSockets0: Accepting socket connection...
,09-12 07:31:30.485   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 07:31:30.486  4083  4083 D BluetoothMapService: onReceive
,09-12 07:31:30.487  4083  4083 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 07:31:30.487  4083  4083 D BluetoothMapService: STATE_ON
,09-12 07:31:30.487  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:30.489  4004  4004 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-12 07:31:30.489  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:30.492  4004  4004 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 07:31:30.497  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 07:31:30.499  4004  4004 D BluetoothA2dp: Proxy object connected
,09-12 07:31:30.503  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 07:31:30.508  4004  4004 D DockEventReceiver: finishStartingService: stopping service
,09-12 07:31:30.512  4004  4004 D BluetoothPbap: Proxy object connected
,09-12 07:31:30.512  1362  1362 D BluetoothPbap: Proxy object connected
09-12 07:31:30.512  1362  1362 D PbapServerProfile: Bluetooth service connected
,09-12 07:31:30.513  4004  4004 D PbapServerProfile: Bluetooth service connected
,09-12 07:31:30.517  4083  4083 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 07:31:30.518  4083  4083 D ObexServerSockets0: prepareForNewConnect()
,09-12 07:31:30.521  4083  4297 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 07:31:30.534  4083  4301 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 07:31:30.535  4083  4301 I BtOppRfcommListener: Accept thread started.
,09-12 07:31:30.566  1362  2064 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.566  1362  1362 D HeadsetProfile: Bluetooth service connected
09-12 07:31:30.566  1961  2364 D BluetoothHeadset: Proxy object connected
09-12 07:31:30.566   874   874 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.566   874   874 D BluetoothHeadset: Proxy object connected
09-12 07:31:30.566   874   874 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.570  1961  2363 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.570   874   891 D BluetoothHeadset: Proxy object connected
09-12 07:31:30.570   874   891 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.580   874   891 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.594  4004  4014 D BluetoothHeadset: Proxy object connected
,09-12 07:31:30.595  4004  4004 D HeadsetProfile: Bluetooth service connected
,09-12 07:31:32.036   874  1307 D ConnectivityService: handlePromptUnvalidated 101
,09-12 07:31:32.075  4083  4266 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 07:31:32.075  4083  4266 D BluetoothAdapterProperties: Setting state to 13
,09-12 07:31:32.075  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 07:31:32.077  4083  4266 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 07:31:32.084  4083  4083 D BluetoothMapService: onReceive
,09-12 07:31:32.085  4083  4083 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 07:31:32.085  4083  4083 D BluetoothMapService: STATE_TURNING_OFF
,09-12 07:31:32.086  4083  4083 D BluetoothMapService: MAP Service closeService in
,09-12 07:31:32.086  4083  4083 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 07:31:32.086  4083  4083 D ObexServerSockets0: shutdown(block = true)
,09-12 07:31:32.087  4083  4292 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 07:31:32.089  4083  4266 I BluetoothAdapterState: Entering PendingCommandState
09-12 07:31:32.091  4083  4270 D BluetoothAdapterProperties: Scan Mode:20
,09-12 07:31:32.092  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 07:31:32.093  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:32.093  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:32.095  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:32.095  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:32.103  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
09-12 07:31:32.106  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:32.106  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:32.107  3935  3935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 07:31:32.107  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:32.107  4083  4083 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 07:31:32.108  4083  4293 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 07:31:32.108  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:32.108  4083  4279 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 07:31:32.109  4083  4083 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 07:31:32.109  4083  4083 I BtOppRfcommListener: stopping Accept Thread
09-12 07:31:32.109  4083  4301 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 07:31:32.110  4083  4301 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 07:31:32.110  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:32.112  4083  4083 D HeadsetService: Received stop request...Stopping profile...
09-12 07:31:32.115  1362  1375 D BluetoothHeadset: Proxy object disconnected
,09-12 07:31:32.115  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-12 07:31:32.116  4083  4083 D A2dpService: Received stop request...Stopping profile...
09-12 07:31:32.116  1961  1975 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:32.116   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:32.116  4083  4285 D A2dpStateMachine: Exit Disconnected: -1
,09-12 07:31:32.116  4004  4015 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:32.117   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:32.117   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 07:31:32.118   874   874 D BluetoothA2dp: Proxy object disconnected
09-12 07:31:32.119  1362  1362 D BluetoothA2dp: Proxy object disconnected,
09-12 07:31:32.119  4004  4004 D DockEventReceiver: finishStartingService: stopping service
09-12 07:31:32.120  4004  4004 D HeadsetProfile: Bluetooth service disconnected
,09-12 07:31:32.121  4004  4004 D BluetoothA2dp: Proxy object disconnected
09-12 07:31:32.121  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 07:31:32.122  4083  4083 D HidService: Received stop request...Stopping profile...
09-12 07:31:32.122  4083  4083 D HidService: Stopping Bluetooth HidService,
09-12 07:31:32.125  4004  4004 D BluetoothInputDevice: Proxy object disconnected
09-12 07:31:32.125  4004  4004 D HidProfile: Bluetooth service disconnected
,09-12 07:31:32.125  1362  1362 D BluetoothInputDevice: Proxy object disconnected
09-12 07:31:32.125  1362  1362 D HidProfile: Bluetooth service disconnected
09-12 07:31:32.125  4083  4083 D HealthService: Received stop request...Stopping profile...
09-12 07:31:32.127  4083  4083 D PanService: Received stop request...Stopping profile...
,09-12 07:31:32.128  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 07:31:32.128  1362  1362 D PanProfile: Bluetooth service disconnected
09-12 07:31:32.129  4083  4083 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 07:31:32.129  4083  4083 D BluetoothMapService: stop()
09-12 07:31:32.129  4004  4004 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 07:31:32.129  4083  4083 D BluetoothMapAppObserver: deinitObservers()
,09-12 07:31:32.129  4004  4004 D PanProfile: Bluetooth service disconnected
09-12 07:31:32.129  4083  4083 D BluetoothMapAppObserver: removeReceiver()
09-12 07:31:32.131  4004  4004 D BluetoothMap: Proxy object disconnected
,09-12 07:31:32.131  4004  4004 D MapProfile: Bluetooth service disconnected
09-12 07:31:32.131  1362  1362 D BluetoothMap: Proxy object disconnected
09-12 07:31:32.131  1362  1362 D MapProfile: Bluetooth service disconnected
09-12 07:31:32.131  4083  4083 V BluetoothAdapterState: isTurningOff()=true
,09-12 07:31:32.131  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.132  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:32.132  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:32.133  4083  4083 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 07:31:32.133  4083  4276 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:32.133  4083  4276 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 07:31:32.133  4083  4276 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:32.133  4083  4083 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 07:31:32.134  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:32.134  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.134  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 07:31:32.134  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:32.133  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 07:31:32.135  4083  4270 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,09-12 07:31:32.135  4083  4276 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:32.135  4083  4276 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:32.135  4083  4276 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 07:31:32.136  4083  4276 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 07:31:32.136  4083  4276 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 07:31:32.136  4083  4276 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 07:31:32.136  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 07:31:32.138  4004  4004 D BluetoothPbap: Proxy object disconnected
09-12 07:31:32.138  4004  4004 D PbapServerProfile: Bluetooth service disconnected
,09-12 07:31:32.138  1362  1362 D BluetoothPbap: Proxy object disconnected
09-12 07:31:32.139  1362  1362 D PbapServerProfile: Bluetooth service disconnected
09-12 07:31:32.139  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:32.139  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.139  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:32.139  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false,
09-12 07:31:32.142  4083  4083 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 07:31:32.142  4083  4270 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 07:31:32.142  4083  4083 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 07:31:32.144  4083  4083 V BluetoothAdapterState: isTurningOff()=true
,09-12 07:31:32.144  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.144  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:32.144  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:32.144  4083  4083 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 07:31:32.144  4083  4270 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 07:31:32.144  4083  4083 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 07:31:32.145  4083  4083 V BluetoothAdapterState: isTurningOff()=true
,09-12 07:31:32.145  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.145  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:32.145  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:32.145  4083  4083 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 07:31:32.145  4083  4083 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object,
09-12 07:31:32.146  4083  4083 D BluetoothMapService: MAP Service closeService in
09-12 07:31:32.146  4083  4083 V BluetoothAdapterState: isTurningOff()=true
09-12 07:31:32.146  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.146  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 07:31:32.146  4083  4083 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:32.146  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 07:31:32.147  4083  4266 D BluetoothAdapterProperties: Setting state to 15
09-12 07:31:32.147  4083  4083 D BluetoothMapService: cleanup()
09-12 07:31:32.147  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 07:31:32.147  4083  4083 D BluetoothMapService: MAP Service closeService in
09-12 07:31:32.147  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:32.148  1362  1386 D BluetoothPan: onBluetoothStateChange on: false
09-12 07:31:32.148  4083  4266 I BluetoothAdapterState: Entering BleOnState
,09-12 07:31:32.148  4004  4014 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 07:31:32.149  1362  2064 D BluetoothMap: onBluetoothStateChange: up=false
09-12 07:31:32.149  1961  1976 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:32.150   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 07:31:32.150   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:32.150   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 07:31:32.150  4004  4015 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 07:31:32.150  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 07:31:32.151  4004  4014 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 07:31:32.151  4004  4015 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 07:31:32.152  1362  1386 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 07:31:32.152   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 07:31:32.152  4004  4014 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 07:31:32.153  1362  2064 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 07:31:32.153  4004  4015 D BluetoothPan: onBluetoothStateChange on: false
,09-12 07:31:32.154  4083  4266 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 07:31:32.154  4083  4266 D BluetoothAdapterProperties: Setting state to 16
09-12 07:31:32.154  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 07:31:32.154  4083  4266 D BluetoothAdapterProperties: onBleDisable
09-12 07:31:32.154  4083  4266 I BluetoothAdapterState: Entering PendingCommandState
09-12 07:31:32.155  4083  4267 D bt_stack_manager: event_shut_down_stack is bringing down the stack.,
09-12 07:31:32.156  4083  4276 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 07:31:32.156  4083  4276 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 07:31:32.156  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:32.156  4083  4270 D BluetoothAdapterProperties: Scan Mode:20
,09-12 07:31:32.157  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:32.159  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:32.159  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 07:31:32.160  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:32.165  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 07:31:32.170  4004  4004 D DockEventReceiver: finishStartingService: stopping service
,09-12 07:31:32.356  4083  4270 I bt_hci  : shut_down
,09-12 07:31:32.365  4083  4274 D bt_hwcfg: hw_epilog_process
09-12 07:31:32.365  4083  4274 I bt_vendor: low_power_mode_cb
,09-12 07:31:32.384  4083  4274 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 07:31:32.384  4083  4274 I bt_vendor: epilog_cb
09-12 07:31:32.384  4083  4274 I bt_hci  : epilog_finished_callback
,09-12 07:31:32.392  4083  4270 I bt_hci_h4: hal_close
,09-12 07:31:32.393  4083  4270 I bt_userial_vendor: device fd = 51 close
,09-12 07:31:32.511  4083  4267 D bt_stack_manager: event_shut_down_stack finished.
,09-12 07:31:32.512  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 07:31:32.518  4083  4266 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 07:31:32.518  4083  4083 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 07:31:32.520  4083  4083 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 07:31:32.520  4083  4083 D BtGatt.GattService: stop()
09-12 07:31:32.521  4083  4083 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 07:31:32.526  4083  4083 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:32.526  4083  4083 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:32.526  4083  4083 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:32.527  4083  4083 V BluetoothAdapterState: isBleTurningOff()=true
09-12 07:31:32.528  4083  4266 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 07:31:32.528  4083  4266 D BluetoothAdapterProperties: Setting state to 10
,09-12 07:31:32.529  4083  4266 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 07:31:32.530  4083  4266 I BluetoothAdapterState: Entering OffState
,09-12 07:31:32.532   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 07:31:32.560  4083  4083 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 07:31:32.560  4083  4083 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 07:31:32.561  4083  4267 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 07:31:32.575  4083  4083 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 07:31:32.579  4083  4267 D bt_stack_manager: event_clean_up_stack finished.
,09-12 07:31:32.585  4083  4083 I art     : System.exit called, status: 0
,09-12 07:31:32.585  4083  4083 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 07:31:32.651   874  2125 I ActivityManager: Process com.android.bluetooth (pid 4083) has died
,09-12 07:31:35.072  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 07:31:35.072  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:38.080  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 07:31:38.081  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f645878 added. We now have 6 listener(s)
09-12 07:31:38.081  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:38.086  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 07:31:38.087  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57e6b51 added. We now have 7 listener(s)
,09-12 07:31:38.087  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:38.089  3935  3984 I System.out: IsBluetoothEnabled
,09-12 07:31:38.100  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:38.151   874   891 I ActivityManager: Start proc 4314:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 07:31:38.279  4314  4314 D AdapterServiceConfig: Adding HeadsetService
,09-12 07:31:38.279  4314  4314 D AdapterServiceConfig: Adding A2dpService
,09-12 07:31:38.279  4314  4314 D AdapterServiceConfig: Adding HidService
09-12 07:31:38.279  4314  4314 D AdapterServiceConfig: Adding HealthService
09-12 07:31:38.280  4314  4314 D AdapterServiceConfig: Adding PanService
09-12 07:31:38.280  4314  4314 D AdapterServiceConfig: Adding GattService
09-12 07:31:38.280  4314  4314 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 07:31:38.297  4314  4314 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 07:31:38.296   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e2fd9e2:true
,09-12 07:31:38.302  4314  4314 I bt_bluedroid: init
,09-12 07:31:38.303  4314  4326 I BluetoothAdapterState: Entering OffState
,09-12 07:31:38.310  4314  4327 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 07:31:38.310  4314  4327 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 07:31:38.311  4314  4327 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 07:31:38.312  4314  4327 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 07:31:38.315  4314  4314 I bt_bluedroid: get_profile_interface socket
,09-12 07:31:38.318  4314  4314 I bt_bluedroid: get_profile_interface sdp
,09-12 07:31:38.322  4314  4330 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 07:31:38.322  4314  4325 I bt_bluedroid: config_hci_snoop_log
,09-12 07:31:38.327  4314  4330 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 07:31:38.329   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 07:31:38.340  4314  4326 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 07:31:38.341  4314  4326 D BluetoothAdapterProperties: Setting state to 14
,09-12 07:31:38.341  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 07:31:38.345  4314  4326 D BluetoothBondStateMachine: make
,09-12 07:31:38.351  4314  4331 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 07:31:38.356  4314  4326 I BluetoothAdapterState: Entering PendingCommandState
,09-12 07:31:38.358  4314  4314 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 07:31:38.361  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:38.362  4314  4314 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 07:31:38.363  4314  4314 D BtGatt.GattService: Received start request. Starting profile...
,09-12 07:31:38.363  4314  4314 D BtGatt.GattService: start()
,09-12 07:31:38.363  4314  4314 I bt_bluedroid: get_profile_interface gatt
09-12 07:31:38.364  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:38.364  4314  4314 D BtGatt.AdvertiseManager: advertise manager created
,09-12 07:31:38.374  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:38.374  4314  4314 V BluetoothAdapterState: isTurningOn()=false
09-12 07:31:38.374  4314  4314 V BluetoothAdapterState: isBleTurningOn()=true
09-12 07:31:38.374  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:38.375  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 07:31:38.375  4314  4326 I bt_bluedroid: enable
09-12 07:31:38.376  4314  4327 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 07:31:38.376  4314  4327 I bt_hci  : start_up
,09-12 07:31:38.385  4314  4327 I bt_vendor: alloc value 0xb3a84189
,09-12 07:31:38.385  4314  4327 I bt_vendor: init
09-12 07:31:38.385  4314  4327 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 07:31:38.386  4314  4327 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 07:31:38.494  4314  4327 D bt_hci  : start_up starting async portion
,09-12 07:31:38.494  4314  4334 I bt_hci  : event_finish_startup
09-12 07:31:38.495  4314  4334 I bt_hci_h4: hal_open
09-12 07:31:38.495  4314  4334 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 07:31:38.502  4314  4334 I bt_userial_vendor: device fd = 51 open
,09-12 07:31:38.534  4314  4334 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 07:31:38.566  4314  4334 D bt_hwcfg: Chipset BCM4354A2
,09-12 07:31:38.566  4314  4334 D bt_hwcfg: Target name = [BCM4354A2]
09-12 07:31:38.567  4314  4334 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 07:31:38.959   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 07:31:38.968  1880  1880 I Keyboard.Facilitator: onFinishInput()
,09-12 07:31:38.992   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 07:31:38.992   874   894 I Adreno  : Build Date                       : 10/20/15
09-12 07:31:38.992   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 07:31:38.992   874   894 I Adreno  : Local Branch                     : M14
09-12 07:31:38.992   874   894 I Adreno  : Remote Branch                    : 
09-12 07:31:38.992   874   894 I Adreno  : Remote Branch                    : 
09-12 07:31:38.992   874   894 I Adreno  : Reconstruct Branch               : 
,09-12 07:31:39.031   282  1296 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (171 us)
,09-12 07:31:39.243  4314  4334 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 07:31:39.243  4314  4334 D bt_hwcfg: Settlement delay -- 100 ms
09-12 07:31:39.243  4314  4334 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 07:31:39.360  4314  4334 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 07:31:39.363  4314  4334 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 07:31:39.392  4314  4334 I bt_hwcfg: vendor lib fwcfg completed
,09-12 07:31:39.392  4314  4334 I bt_vendor: firmware callback
09-12 07:31:39.393  4314  4334 I bt_hci  : firmware_config_callback
,09-12 07:31:39.405  4314  4337 I bt_btu  : btu_task pending for preload complete event
,09-12 07:31:39.405  4314  4337 I bt_btu_task: Bluetooth chip preload is complete
,09-12 07:31:39.405  4314  4337 I bt_btu  : btu_task received preload complete event
,09-12 07:31:39.414  4314  4337 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 07:31:39.415  4314  4337 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 07:31:39.415  4314  4337 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 07:31:39.415  4314  4337 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 07:31:39.415  4314  4337 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 07:31:39.416  4314  4337 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 07:31:39.416  4314  4337 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 07:31:39.416  4314  4337 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 07:31:39.416  4314  4337 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 07:31:39.416  4314  4337 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 07:31:39.417  4314  4337 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 07:31:39.418  4314  4337 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 07:31:39.418  4314  4337 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 07:31:39.418  4314  4337 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 07:31:39.418  4314  4337 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 07:31:39.555  4314  4337 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a01d9d
,09-12 07:31:39.555  4314  4337 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a01d9d 
,09-12 07:31:39.568  4314  4330 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 07:31:39.570  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 07:31:39.571  4314  4330 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 07:31:39.574  4314  4330 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 07:31:39.580  4314  4330 D BluetoothAdapterProperties: Scan Mode:20
,09-12 07:31:39.581  4314  4330 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 07:31:39.581  4314  4330 D bt_hci  : do_postload posting postload work item
,09-12 07:31:39.582  4314  4334 I bt_hci  : event_postload
09-12 07:31:39.582  4314  4334 I bt_vendor: sco_config_cb
,09-12 07:31:39.582  4314  4334 I bt_hci  : sco_config_callback postload finished.
,09-12 07:31:39.584  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:39.589  4314  4330 D bt_bte_conf: Device ID record 1 : primary
,09-12 07:31:39.589  4314  4330 D bt_bte_conf:   vendorId            = 000f
,09-12 07:31:39.589  4314  4330 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 07:31:39.589  4314  4334 I bt_vendor: low_power_mode_cb
,09-12 07:31:39.589  4314  4330 D bt_bte_conf:   product             = 1200
,09-12 07:31:39.589  4314  4330 D bt_bte_conf:   version             = 1436
09-12 07:31:39.589  4314  4330 D bt_bte_conf:   clientExecutableURL = 
09-12 07:31:39.590  4314  4330 D bt_bte_conf:   serviceDescription  = 
,09-12 07:31:39.590  4314  4330 D bt_bte_conf:   documentationURL    = 
09-12 07:31:39.590  4314  4330 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 07:31:39.590  4314  4327 D bt_stack_manager: event_start_up_stack finished
09-12 07:31:39.591  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 07:31:39.591  4314  4326 D BluetoothAdapterProperties: Setting state to 15
09-12 07:31:39.592  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 07:31:39.594  4314  4326 I BluetoothAdapterState: Entering BleOnState
,09-12 07:31:39.597  4314  4326 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 07:31:39.598  4314  4326 D BluetoothAdapterProperties: Setting state to 11
,09-12 07:31:39.598  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 07:31:39.603  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 07:31:39.608  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:39.609  4314  4314 D HeadsetService: Received start request. Starting profile...
,09-12 07:31:39.611  4314  4314 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 07:31:39.612  4314  4314 D HeadsetStateMachine: make
09-12 07:31:39.620  4314  4326 I BluetoothAdapterState: Entering PendingCommandState
,09-12 07:31:39.624  4314  4314 D HeadsetStateMachine: max_hf_connections = 1
09-12 07:31:39.624  4314  4314 I bt_bluedroid: get_profile_interface handsfree
09-12 07:31:39.625  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 07:31:39.625  4314  4330 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 07:31:39.629  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
09-12 07:31:39.630  4314  4314 D A2dpService: Received start request. Starting profile...
,09-12 07:31:39.631  4314  4314 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 07:31:39.632  4314  4314 I bt_bluedroid: get_profile_interface avrcp
,09-12 07:31:39.638  4314  4314 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 07:31:39.638  4314  4314 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 07:31:39.638  4314  4314 D A2dpStateMachine: make
,09-12 07:31:39.639  4314  4314 I bt_bluedroid: get_profile_interface a2dp
,09-12 07:31:39.640  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 07:31:39.642  4314  4345 D A2dpStateMachine: Enter Disconnected: -2
,09-12 07:31:39.643  4314  4314 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 07:31:39.646  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:39.647  4314  4314 D HidService: Received start request. Starting profile...
,09-12 07:31:39.647  4314  4314 I bt_bluedroid: get_profile_interface hidhost
,09-12 07:31:39.647  4314  4330 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e33e5
09-12 07:31:39.647  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 07:31:39.647  4314  4314 D HidService: setHidService(): set to: null
,09-12 07:31:39.648  4314  4314 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 07:31:39.649  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:39.649  4314  4314 D HealthService: Received start request. Starting profile...
,09-12 07:31:39.651  4314  4314 I bt_bluedroid: get_profile_interface health
,09-12 07:31:39.652  4314  4314 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 07:31:39.652  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:39.653  4314  4314 D PanService: Received start request. Starting profile...
,09-12 07:31:39.653  4314  4314 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 07:31:39.653  4314  4314 I bt_bluedroid: get_profile_interface pan
09-12 07:31:39.654  4314  4330 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 07:31:39.656  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:39.656  4314  4314 D BluetoothMapService: Received start request. Starting profile...
,09-12 07:31:39.656  4314  4314 D BluetoothMapService: start()
,09-12 07:31:39.658  4314  4314 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 07:31:39.659  4314  4314 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 07:31:39.659  4314  4314 D BluetoothMapAppObserver: createReceiver()
,09-12 07:31:39.660  4314  4314 D BluetoothMapAppObserver: initObservers()
09-12 07:31:39.660  4314  4314 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 07:31:39.669  4314  4343 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 07:31:39.670  4314  4314 V BluetoothAdapterState: isTurningOff()=false,
09-12 07:31:39.670  4314  4314 V BluetoothAdapterState: isTurningOn()=true
,09-12 07:31:39.670  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 07:31:39.670  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:39.684  3935  3935 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 07:31:39.684  3935  3935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 07:31:39.715   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 07:31:39.720   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 07:31:39.722  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 07:31:39.727  4314  4314 V BluetoothAdapterState: isTurningOff()=false
09-12 07:31:39.727  4314  4314 V BluetoothAdapterState: isTurningOn()=true
09-12 07:31:39.727  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:39.728  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:39.728  4314  4314 V BluetoothAdapterState: isTurningOff()=false
09-12 07:31:39.728   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 07:31:39.728  4314  4314 V BluetoothAdapterState: isTurningOn()=true
09-12 07:31:39.728  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:39.728   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-12 07:31:39.728  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:39.729  4314  4314 V BluetoothAdapterState: isTurningOff()=false
09-12 07:31:39.729  4314  4314 V BluetoothAdapterState: isTurningOn()=true
09-12 07:31:39.729  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:39.729  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:39.730  4314  4314 V BluetoothAdapterState: isTurningOff()=false
09-12 07:31:39.730  4314  4314 V BluetoothAdapterState: isTurningOn()=true
09-12 07:31:39.731   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-12 07:31:39.731  3935  3935 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9095ca0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d2c8fb6, 16908290=android.view.AbsSavedState$1@d2c8fb6}, android:focusedViewId=100}]}]
09-12 07:31:39.731  3935  3935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 07:31:39.731  3935  3935 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 07:31:39.731  3935  3935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 07:31:39.742  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 07:31:39.742  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 07:31:39.742  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,09-12 07:31:39.742  4314  4314 V BluetoothAdapterState: isTurningOn()=true
09-12 07:31:39.742  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
09-12 07:31:39.742  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
09-12 07:31:39.743  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 07:31:39.743  4314  4326 D BluetoothAdapterProperties: ScanMode =  20
09-12 07:31:39.743  4314  4326 D BluetoothAdapterProperties: State =  11
,09-12 07:31:39.743  4314  4326 D BluetoothAdapterProperties: Setting state to 12
09-12 07:31:39.743  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 07:31:39.744  4314  4326 I BluetoothAdapterState: Entering OnState
09-12 07:31:39.744  1362  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:39.744  4314  4330 D BluetoothAdapterProperties: Scan Mode:21
,09-12 07:31:39.744  4314  4330 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 07:31:39.744  4314  4314 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 07:31:39.745  4314  4314 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 07:31:39.745  1362  2064 D BluetoothPan: onBluetoothStateChange on: true
09-12 07:31:39.746  4314  4314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 07:31:39.746  4004  4014 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:39.749  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:39.750  1362  2064 D BluetoothMap: onBluetoothStateChange: up=true
09-12 07:31:39.751  1961  1976 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:39.752   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:39.752   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 07:31:39.752   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 07:31:39.752  4004  4015 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:39.753  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:39.753  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 07:31:39.753  4314  4314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 07:31:39.754  4004  4014 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 07:31:39.754  4314  4314 D ObexServerSockets: Succeed to create listening sockets 
09-12 07:31:39.754  4314  4314 D ObexServerSockets0: startAccept()
09-12 07:31:39.754  4314  4314 D ObexServerSockets0: prepareForNewConnect()
09-12 07:31:39.756  4004  4015 D BluetoothMap: onBluetoothStateChange: up=true
09-12 07:31:39.756  4314  4314 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 07:31:39.756  4314  4314 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 07:31:39.757  4314  4354 D ObexServerSockets0: Accepting socket connection...
,09-12 07:31:39.758  4314  4355 D ObexServerSockets0: Accepting socket connection...
09-12 07:31:39.760  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 07:31:39.760  1362  1362 D PanProfile: Bluetooth service connected
09-12 07:31:39.760  1362  1362 D BluetoothInputDevice: Proxy object connected
09-12 07:31:39.760  1362  2064 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 07:31:39.760  1362  1362 D HidProfile: Bluetooth service connected
09-12 07:31:39.761   874   874 D BluetoothA2dp: Proxy object connected
,09-12 07:31:39.762  1362  1362 D BluetoothMap: Proxy object connected
09-12 07:31:39.762  1362  1362 D MapProfile: Bluetooth service connected
09-12 07:31:39.762   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 07:31:39.763  1362  1362 D BluetoothMap: getConnectedDevices()
09-12 07:31:39.763  4004  4015 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 07:31:39.765  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 07:31:39.765  4004  4004 D BluetoothInputDevice: Proxy object connected
09-12 07:31:39.765  4004  4004 D HidProfile: Bluetooth service connected
,09-12 07:31:39.766  1362  1362 D BluetoothA2dp: Proxy object connected
09-12 07:31:39.766  4004  4014 D BluetoothPan: onBluetoothStateChange on: true
,09-12 07:31:39.768  4004  4004 D BluetoothMap: Proxy object connected,
09-12 07:31:39.768  4004  4004 D MapProfile: Bluetooth service connected
09-12 07:31:39.768  4004  4004 D BluetoothMap: getConnectedDevices()
,09-12 07:31:39.770   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 07:31:39.771  4314  4314 D BluetoothMapService: onReceive
09-12 07:31:39.771  4314  4314 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 07:31:39.771  4314  4314 D BluetoothMapService: STATE_ON
09-12 07:31:39.771  4004  4004 D BluetoothA2dp: Proxy object connected
,09-12 07:31:39.772  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:39.774  4004  4004 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 07:31:39.774  4004  4004 D PanProfile: Bluetooth service connected
,09-12 07:31:39.778  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 07:31:39.782  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 07:31:39.789  4004  4004 D DockEventReceiver: finishStartingService: stopping service
,09-12 07:31:39.790  4004  4004 D BluetoothPbap: Proxy object connected
,09-12 07:31:39.790  4004  4004 D PbapServerProfile: Bluetooth service connected
,09-12 07:31:39.793  1362  1362 D BluetoothPbap: Proxy object connected
09-12 07:31:39.793  1362  1362 D PbapServerProfile: Bluetooth service connected
,09-12 07:31:39.795  4314  4361 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 07:31:39.808  4314  4314 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 07:31:39.808  4314  4314 D ObexServerSockets0: prepareForNewConnect()
,09-12 07:31:39.813  4314  4365 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 07:31:39.815  4314  4365 I BtOppRfcommListener: Accept thread started.
,09-12 07:31:39.846  1362  2064 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.846  1362  1362 D HeadsetProfile: Bluetooth service connected
09-12 07:31:39.846  1961  2120 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.847   874   874 D BluetoothHeadset: Proxy object connected
09-12 07:31:39.847  4004  4351 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.847   874   874 D BluetoothHeadset: Proxy object connected
09-12 07:31:39.847  4004  4004 D HeadsetProfile: Bluetooth service connected
,09-12 07:31:39.847   874   874 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.852  1961  2364 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.852   874   891 D BluetoothHeadset: Proxy object connected
09-12 07:31:39.852   874   891 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.853  4004  4014 D BluetoothHeadset: Proxy object connected
09-12 07:31:39.853  4004  4004 D HeadsetProfile: Bluetooth service connected
,09-12 07:31:39.863   874   891 D BluetoothHeadset: Proxy object connected
,09-12 07:31:39.964   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 07:31:39.968   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 07:31:39.970   874  1331 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,09-12 07:31:39.974   874   894 I DreamManagerService: Entering dreamland.
,09-12 07:31:39.975   874   894 I PowerManagerService: Dozing...
,09-12 07:31:39.977   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 07:31:40.025   376  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 07:31:40.026   376  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 07:31:40.029   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 07:31:40.032   874  1304 E native  : do suspend false
,09-12 07:31:40.035  1948  4367 D NfcService: Discovery configuration equal, not updating.
,09-12 07:31:40.051   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 07:31:40.055   874  1304 E native  : do suspend true
,09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:40.122  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:40.129  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:40.133  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 07:31:40.133  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c86d4b7 added. We now have 8 listener(s)
,09-12 07:31:40.134  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:40.139   874   885 D WifiService: setWifiEnabled: false pid=3935, uid=10000
,09-12 07:31:40.139   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 07:31:40.152  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:40.153   874  2127 D WifiService: setWifiEnabled: true pid=3935, uid=10000
09-12 07:31:40.153   874  2127 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 07:31:40.168   874  1304 D WifiConfigStore: Loading config and enabling all networks 
09-12 07:31:40.168   376  1276 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-12 07:31:40.169   376  1276 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:40.182  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:40.189  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:40.202   874  1304 D WifiConfigStore: loaded 0 passpoint configs
,09-12 07:31:40.203   874  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 07:31:40.204   874  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 07:31:40.205   874  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 07:31:40.206   874  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-12 07:31:40.206   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 07:31:40.206   874  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 07:31:40.233   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 07:31:40.233   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 07:31:40.235   372   872 D CommandListener: Setting iface cfg
,09-12 07:31:40.242   874  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 07:31:40.242   874  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 07:31:40.244   874  1304 E native  : do suspend true
,09-12 07:31:40.245   874  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 07:31:40.251   874  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 07:31:40.258   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:41.175  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:41.182  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:41.195  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 07:31:41.197  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 07:31:41.202  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9095ca0 Bundle[{}]
,09-12 07:31:41.203  3935  3984 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 07:31:41.203  3935  3984 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 07:31:41.203  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 07:31:41.204  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 07:31:41.204  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 07:31:41.205  3935  3984 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 07:31:41.209  3935  3984 I System.out: Running OutgoingSocketThread
,09-12 07:31:41.212  3935  4376 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 452)
,09-12 07:31:41.214  3935  4376 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40400
,09-12 07:31:41.215  3935  4376 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 07:31:41.546   874  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 07:31:41.643   874  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.01 rxSuccessRate=0.01 delta 1000 -> 1000
,09-12 07:31:41.645   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 07:31:41.645   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 07:31:41.664   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 07:31:41.719   874  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 07:31:41.725  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 07:31:42.159  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 07:31:42.197  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 07:31:42.197  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 07:31:42.207   874  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 07:31:42.212  3935  3984 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 453)
,09-12 07:31:42.212  3935  3984 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 453)
,09-12 07:31:42.222   874  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 07:31:42.222  3935  3984 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 458)
09-12 07:31:42.222   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 07:31:42.223   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 07:31:42.224  3935  3984 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 07:31:42.225  3935  3984 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 459)
,09-12 07:31:42.231  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 07:31:42.232  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c28424 added. We now have 2 listener(s)
,09-12 07:31:42.238  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:42.239  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 07:31:42.239  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 07:31:42.240  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 07:31:42.240  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced6b8d added. We now have 9 listener(s)
,09-12 07:31:42.240  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:42.241  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 07:31:42.245   874  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 07:31:42.246  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 07:31:42.255   372   872 D CommandListener: Setting iface cfg
09-12 07:31:42.256   874  1304 D WifiStateMachine: Start Dhcp Watchdog 3
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:42.256  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 07:31:42.261  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:42.261  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:42.261  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 07:31:42.261  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2a0553 added. We now have 3 listener(s)
,09-12 07:31:42.263  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:42.263   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 07:31:42.265  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:42.265  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:42.265  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 07:31:42.265  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 07:31:42.266  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.266  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b5be90 added. We now have 10 listener(s)
,09-12 07:31:42.266  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.266  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 07:31:42.267  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:42.267  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 07:31:42.267  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.267  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:42.267  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:42.267  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 07:31:42.267  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c28424 removed from the list
,09-12 07:31:42.268  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:42.268  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced6b8d removed from the list,
09-12 07:31:42.268  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 07:31:42.268  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:42.269  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:42.269  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.271  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:42.271  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.271  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.271  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced6b8d not in the list
09-12 07:31:42.271  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.271  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.273  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.273  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:42.273  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.273  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b5be90 removed from the list
09-12 07:31:42.273  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.273   874  4382 D DhcpClient: Receive thread started
09-12 07:31:42.273  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.274  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.274  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.274  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2a0553 removed from the list
09-12 07:31:42.275  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 07:31:42.275  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d23389 added. We now have 2 listener(s)
09-12 07:31:42.277  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 07:31:42.278  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 07:31:42.278  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.278  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.278  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29df8e added. We now have 9 listener(s)
09-12 07:31:42.278  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.278  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 07:31:42.281  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertiseme,nt supported: SUPPORTED
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:42.285  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:42.287  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 07:31:42.288  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 07:31:42.288  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 07:31:42.288  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6033bc added. We now have 3 listener(s)
09-12 07:31:42.289  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:42.290  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 07:31:42.290  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 07:31:42.290  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.290  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.290  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4217f45 added. We now have 10 listener(s)
09-12 07:31:42.290  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.290  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:42.290  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:42.291  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 07:31:42.291  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 07:31:42.291  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:42.291  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 07:31:42.294  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 07:31:42.294  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 07:31:42.298  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 07:31:42.298  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 07:31:42.298  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 07:31:42.302  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 07:31:42.302  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 07:31:42.302  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 07:31:42.303  3935  3984 D BluetoothAdapter: STATE_ON
,09-12 07:31:42.307  4314  4324 D BtGatt.GattService: registerClient() - UUID=14f5a7a9-2baf-4065-baa3-e90910ea4f63
,09-12 07:31:42.308  4314  4330 D BtGatt.GattService: onClientRegistered() - UUID=14f5a7a9-2baf-4065-baa3-e90910ea4f63, clientIf=5
,09-12 07:31:42.309  3935  3945 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 07:31:42.311  4314  4353 D BtGatt.GattService: start scan with filters
,09-12 07:31:42.316  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 07:31:42.316  4314  4333 D BtGatt.ScanManager: handling starting scan
09-12 07:31:42.316  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 07:31:42.317  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 07:31:42.317  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 07:31:42.319  4314  4333 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4d011a3
,09-12 07:31:42.324  4314  4330 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 07:31:42.324  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:42.325  4314  4333 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 07:31:42.325  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 07:31:42.325  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 07:31:42.326  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:42.331  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 07:31:42.335  4314  4330 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 07:31:42.336  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.336  4314  4333 D BtGatt.ScanManager: Starting BLE batch scan
09-12 07:31:42.336  4314  4333 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 07:31:42.338  3935  3984 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 07:31:42.338  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:42.338  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 07:31:42.338  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.338  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 07:31:42.338  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 07:31:42.338  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 07:31:42.339  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 07:31:42.339  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 07:31:42.339  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 07:31:42.339  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 07:31:42.340  3935  3984 D BluetoothAdapter: STATE_ON
,09-12 07:31:42.341  4314  4324 D BtGatt.GattService: stopScan() - queue size =1
09-12 07:31:42.341  4314  4353 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 07:31:42.342  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 07:31:42.342  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 07:31:42.342  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 07:31:42.342  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 07:31:42.342  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 07:31:42.344  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 07:31:42.344  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 07:31:42.344  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 07:31:42.345  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 07:31:42.345  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 07:31:42.347  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 07:31:42.347  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:42.348  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 07:31:42.351  4314  4330 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 07:31:42.351  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.352  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:42.352  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:42.352  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 07:31:42.352  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 07:31:42.352  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 07:31:42.352  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 07:31:42.353  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 07:31:42.353  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d23389 removed from the list
,09-12 07:31:42.353  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:42.353  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29df8e removed from the list
,09-12 07:31:42.353  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:42.353  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.354  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.354  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.355   874  1304 E native  : do suspend false
09-12 07:31:42.355  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:42.355  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.355  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:42.355  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29df8e not in the list
09-12 07:31:42.355  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.355  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.356  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.357  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:42.357  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:42.357  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4217f45 removed from the list
09-12 07:31:42.357  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.357  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.357  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.357  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.357  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6033bc removed from the list
09-12 07:31:42.358  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 07:31:42.358  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5fcac1 added. We now have 2 listener(s)
09-12 07:31:42.359  4314  4330 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 07:31:42.359  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.360  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 07:31:42.360  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 07:31:42.360  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.360  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.360  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d65266 added. We now have 9 listener(s)
09-12 07:31:42.360  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.361  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 07:31:42.363  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:42.367  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:42.367  4314  4330 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 07:31:42.367  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:42.368  4314  4333 D BtGatt.ScanManager: stopping BLe Batch
09-12 07:31:42.369   874  2098 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 07:31:42.370  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:42.370  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:42.372  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:42.373  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 07:31:42.373  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe13e54 added. We now have 3 listener(s)
09-12 07:31:42.373  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:42.375  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 07:31:42.375  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 07:31:42.375  4314  4330 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 07:31:42.375  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 07:31:42.375  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.375  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.376  4314  4333 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 07:31:42.376  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdd51fd added. We now have 10 listener(s)
09-12 07:31:42.376  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.376  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 07:31:42.377  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:42.377  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 07:31:42.377  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 07:31:42.377  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:42.377  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 07:31:42.383  4314  4330 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 07:31:42.383  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:42.383  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 07:31:42.383  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 07:31:42.387  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 07:31:42.388  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 07:31:42.388  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 07:31:42.389   874  4382 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172781, domain null
,09-12 07:31:42.389   874  2098 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172781 seconds
,09-12 07:31:42.390   874  2098 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 07:31:42.392  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 07:31:42.392  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 07:31:42.392  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 07:31:42.393  3935  3984 D BluetoothAdapter: STATE_ON
,09-12 07:31:42.395  4314  4357 D BtGatt.GattService: registerClient() - UUID=6102294e-9c5f-4194-bae9-16acd639892d
,09-12 07:31:42.395  4314  4330 D BtGatt.GattService: onClientRegistered() - UUID=6102294e-9c5f-4194-bae9-16acd639892d, clientIf=5
09-12 07:31:42.395  3935  3983 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 07:31:42.396  4314  4324 D BtGatt.GattService: start scan with filters
,09-12 07:31:42.399  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 07:31:42.399  4314  4333 D BtGatt.ScanManager: handling starting scan
09-12 07:31:42.399  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 07:31:42.399  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 07:31:42.399  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 07:31:42.403  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:42.403  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:42.403  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 07:31:42.405   874  4382 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 07:31:42.405   874  2098 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 07:31:42.406  4314  4330 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 07:31:42.406  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.406  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 07:31:42.407  4314  4333 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 07:31:42.407   372   872 D CommandListener: Setting iface cfg
,09-12 07:31:42.411  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 07:31:42.411  3935  3984 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 07:31:42.411  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:42.411  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:42.411  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 07:31:42.412   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 07:31:42.412  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.412  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.412  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 07:31:42.412  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 07:31:42.412  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5fcac1 removed from the list
09-12 07:31:42.412  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.412  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d65266 removed from the list
09-12 07:31:42.413  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:42.413  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:42.414  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.414   874  1304 E native  : do suspend true
09-12 07:31:42.414  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 07:31:42.414  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.414  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:42.414  4314  4330 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 07:31:42.414  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.415  4314  4333 D BtGatt.ScanManager: Starting BLE batch scan
09-12 07:31:42.415  4314  4333 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 07:31:42.415  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:42.415  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.416  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.416  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d65266 not in the list
09-12 07:31:42.415   874  2098 D DhcpClient: Scheduling renewal in 86399s
09-12 07:31:42.416  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 07:31:42.416  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 07:31:42.416  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 07:31:42.416  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 07:31:42.416  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 07:31:42.417  3935  3984 D BluetoothAdapter: STATE_ON
09-12 07:31:42.418  4314  4324 D BtGatt.GattService: stopScan() - queue size =1
09-12 07:31:42.419  4314  4353 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 07:31:42.419  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 07:31:42.419  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 07:31:42.419  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 07:31:42.420  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 07:31:42.420  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 07:31:42.421  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 07:31:42.421  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 07:31:42.421  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 07:31:42.422  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-12 07:31:42.422  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-12 07:31:42.424  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-12 07:31:42.424  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:42.424  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 07:31:42.424  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.424  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:42.424  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.425  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdd51fd removed from the list
,09-12 07:31:42.425  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.425  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 07:31:42.425  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.425  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.425  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe13e54 removed from the list
09-12 07:31:42.426   874  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-12 07:31:42.426  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 07:31:42.426  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb210f9 added. We now have 2 listener(s)
09-12 07:31:42.427   874  1304 D WifiConfigStore: No blacklist allowed without epno enabled
09-12 07:31:42.427   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 07:31:42.429   874  1307 D ConnectivityService: Adding iface wlan0 to network 102
09-12 07:31:42.429  4314  4330 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 07:31:42.429  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:42.432  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:42.432  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 07:31:42.433  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.433  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.434  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c93483e added. We now have 9 listener(s)
09-12 07:31:42.434  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.435  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-12 07:31:42.435   874  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 07:31:42.439  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 07:31:42.440  4314  4330 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 07:31:42.440  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 07:31:42.443  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 07:31:42.445  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 07:31:42.445  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:42.445  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 07:31:42.446  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:42.447  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f603ec added. We now have 3 listener(s)
,09-12 07:31:42.448  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:42.448  4314  4330 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 07:31:42.448  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 07:31:42.448  4314  4333 D BtGatt.ScanManager: stopping BLe Batch
,09-12 07:31:42.449  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:42.449  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 07:31:42.449  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.450  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.450  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a79c3b5 added. We now have 10 listener(s)
09-12 07:31:42.450  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 07:31:42.450  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 07:31:42.450  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 07:31:42.450  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 07:31:42.450  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 07:31:42.450  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 07:31:42.455  4314  4330 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 07:31:42.455  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.455  4314  4333 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 07:31:42.457  3935  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 07:31:42.457  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 07:31:42.461  4314  4330 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 07:31:42.461  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.461  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 07:31:42.461  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 07:31:42.461  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 07:31:42.464  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 07:31:42.464  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 07:31:42.464  3935  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 07:31:42.465  3935  3984 D BluetoothAdapter: STATE_ON
09-12 07:31:42.466  4314  4357 D BtGatt.GattService: registerClient() - UUID=be78ef78-71af-4592-8fa7-122408e4e250
,09-12 07:31:42.467  4314  4330 D BtGatt.GattService: onClientRegistered() - UUID=be78ef78-71af-4592-8fa7-122408e4e250, clientIf=5
09-12 07:31:42.467  3935  3946 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 07:31:42.467  4314  4353 D BtGatt.GattService: start scan with filters
,09-12 07:31:42.469  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 07:31:42.469  4314  4333 D BtGatt.ScanManager: handling starting scan
09-12 07:31:42.469  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 07:31:42.469  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 07:31:42.469  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 07:31:42.472  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:42.472  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 07:31:42.472  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 07:31:42.474  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 07:31:42.475  4314  4330 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 07:31:42.476  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.476  4314  4333 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 07:31:42.478   874  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 07:31:42.478   874  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 07:31:42.478  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:42.478  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:42.478  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 07:31:42.479  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 07:31:42.479  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.479  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 07:31:42.479  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.479  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb210f9 removed from the list
09-12 07:31:42.479  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 07:31:42.479  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c93483e removed from the list
,09-12 07:31:42.479  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 07:31:42.479  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:42.479   874  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 07:31:42.480  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.480  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 07:31:42.480  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.480  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:42.481   874  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-12 07:31:42.481  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:42.481  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.481  4314  4330 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 07:31:42.481  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.481  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.482  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c93483e not in the list
09-12 07:31:42.482  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 07:31:42.482  4314  4333 D BtGatt.ScanManager: Starting BLE batch scan
09-12 07:31:42.482  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 07:31:42.482  4314  4333 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 07:31:42.482  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 07:31:42.482  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 07:31:42.482  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 07:31:42.482   874  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-12 07:31:42.482  3935  3984 D BluetoothAdapter: STATE_ON
09-12 07:31:42.483  4314  4324 D BtGatt.GattService: stopScan() - queue size =1
09-12 07:31:42.484  4314  4357 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 07:31:42.490   874  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 07:31:42.490  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 07:31:42.490  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 07:31:42.490  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 07:31:42.490  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 07:31:42.490  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 07:31:42.491  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:42.491  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 07:31:42.491  3935  3984 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 07:31:42.491  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 07:31:42.492  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.493  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:42.493  3935  3935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 07:31:42.493  3935  3935 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 07:31:42.493  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.493  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 07:31:42.493  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.494  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a79c3b5 removed from the list
,09-12 07:31:42.494  4314  4330 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 07:31:42.494  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.494  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.494  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.494  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.494  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.494  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f603ec removed from the list
09-12 07:31:42.495   874  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-12 07:31:42.495   874  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 07:31:42.495   874  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 07:31:42.495   874  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 07:31:42.495   874  1307 D ConnectivityService:    accepting network in place of null
09-12 07:31:42.496   874  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 07:31:42.496  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 07:31:42.496  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccfe631 added. We now have 2 listener(s)
,09-12 07:31:42.496   874  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 07:31:42.498  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:42.498  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 07:31:42.499  4314  4330 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 07:31:42.498  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.499  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.499  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 07:31:42.500  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78e2116 added. We now have 9 listener(s)
09-12 07:31:42.500  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-12 07:31:42.500  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 07:31:42.502  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 07:31:42.505  4314  4330 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 07:31:42.505  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.505  4314  4333 D BtGatt.ScanManager: stopping BLe Batch
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:42.506  3935  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:42.507  3935  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:42.508  3935  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 07:31:42.509  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 07:31:42.509  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fae484 added. We now have 3 listener(s)
,09-12 07:31:42.510  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 07:31:42.510  4314  4330 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 07:31:42.510  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.510  4314  4333 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 07:31:42.512  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 07:31:42.513  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 07:31:42.513  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 07:31:42.513  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 07:31:42.513  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-12 07:31:42.513  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68bb46d added. We now have 10 listener(s)
09-12 07:31:42.513  3935  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 07:31:42.514  3935  3984 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 07:31:42.514  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:42.514  3935  3984 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 07:31:42.515  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.515  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.515  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 07:31:42.515  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.515  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccfe631 removed from the list
09-12 07:31:42.515  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.515  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78e2116 removed from the list
09-12 07:31:42.515  3935  3984 D io.jxcore.node.ConnectivityMonitor: stop
09-12 07:31:42.515  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:42.515  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.515  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.516  4314  4330 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 07:31:42.516  4314  4330 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 07:31:42.516  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:42.516  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.516  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.516  3935  3984 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78e2116 not in the list
09-12 07:31:42.516  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.516  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 07:31:42.517   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156536, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-12 07:31:42.517  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 07:31:42.517  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 07:31:42.517  3935  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 07:31:42.518  3935  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68bb46d removed from the list
09-12 07:31:42.518  3935  3984 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 07:31:42.518  3935  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 07:31:42.518  3935  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 07:31:42.518  3935  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 07:31:42.518  3935  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fae484 removed from the list
,09-12 07:31:42.519  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 07:31:42.519  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 07:31:42.519  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-12 07:31:42.519  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:42.519  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 07:31:42.519  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 07:31:42.524  3935  4388 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,09-12 07:31:42.524  3935  4388 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 466, thread name: My test thread name)
09-12 07:31:42.524  3935  4388 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 07:31:42.526   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:42.526  3935  4389 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: My test thread name)
09-12 07:31:42.526  3935  4389 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 468, thread name: My test thread name)
09-12 07:31:42.526  3935  4389 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 07:31:42.527  3935  3984 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 07:31:42.527  3935  3984 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 07:31:42.527  3935  3984 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-12 07:31:42.527  3935  3984 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 07:31:42.528  3935  3984 D com.test.thalitest.ThaliTestRunner: Total duration: 22913 ms
,09-12 07:31:42.529  3935  3984 I jxcore-log: *Native tests were executed*
09-12 07:31:42.529  3935  3984 I jxcore-log: 
,09-12 07:31:42.529  3935  3984 I jxcore-log: Total number of executed tests:  80
09-12 07:31:42.529  3935  3984 I jxcore-log: 
09-12 07:31:42.529  3935  3984 I jxcore-log: Number of passed tests:  80
09-12 07:31:42.529  3935  3984 I jxcore-log: 
09-12 07:31:42.530  3935  3984 I jxcore-log: Number of failed tests:  0
09-12 07:31:42.530  3935  3984 I jxcore-log: 
09-12 07:31:42.530  3935  3984 I jxcore-log: Number of ignored tests:  0
09-12 07:31:42.530  3935  3984 I jxcore-log: 
,09-12 07:31:42.530  3935  3984 I jxcore-log: Total duration:  22913
09-12 07:31:42.530  3935  3984 I jxcore-log: 
,09-12 07:31:42.532  3935  3984 I jxcore-log: Unit Test app is loaded
09-12 07:31:42.532  3935  3984 I jxcore-log: 
,09-12 07:31:42.538  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.538  3935  3984 I jxcore-log: 
,09-12 07:31:42.538  3935  3935 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 07:31:42.542  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.542  3935  3984 I jxcore-log: 
,09-12 07:31:42.543  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.543  3935  3984 I jxcore-log: 
,09-12 07:31:42.543  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.543  3935  3984 I jxcore-log: 
,09-12 07:31:42.544  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.544  3935  3984 I jxcore-log: 
,09-12 07:31:42.545  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.545  3935  3984 I jxcore-log: 
,09-12 07:31:42.547  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.547  3935  3984 I jxcore-log: 
,09-12 07:31:42.549  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.549  3935  3984 I jxcore-log: 
,09-12 07:31:42.549  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.549  3935  3984 I jxcore-log: 
,09-12 07:31:42.550  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.550  3935  3984 I jxcore-log: 
,09-12 07:31:42.551  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.551  3935  3984 I jxcore-log: 
,09-12 07:31:42.552  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 07:31:42.552  3935  3984 I jxcore-log: 
,09-12 07:31:42.553  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.553  3935  3984 I jxcore-log: 
,09-12 07:31:42.553  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.553  3935  3984 I jxcore-log: 
,09-12 07:31:42.554  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.554  3935  3984 I jxcore-log: 
,09-12 07:31:42.555  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.555  3935  3984 I jxcore-log: 
,09-12 07:31:42.555   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 07:31:42.556  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.556  3935  3984 I jxcore-log: 
,09-12 07:31:42.557  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.557  3935  3984 I jxcore-log: 
,09-12 07:31:42.557   874  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 07:31:42.557  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.557  3935  3984 I jxcore-log: 
,09-12 07:31:42.558   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 07:31:42.558  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.558  3935  3984 I jxcore-log: 
09-12 07:31:42.559  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.559  3935  3984 I jxcore-log: 
,09-12 07:31:42.559   874  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 07:31:42.559   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 07:31:42.565  3935  3935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 07:31:42.563  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.563  3935  3984 I jxcore-log: 
,09-12 07:31:42.566  3935  3935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 07:31:42.566  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.566  3935  3984 I jxcore-log: 
,09-12 07:31:42.567  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 07:31:42.567  3935  3984 I jxcore-log: 
,09-12 07:31:42.568  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.568  3935  3984 I jxcore-log: 
,09-12 07:31:42.568  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.568  3935  3984 I jxcore-log: 
09-12 07:31:42.569  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.569  3935  3984 I jxcore-log: 
09-12 07:31:42.570  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.570  3935  3984 I jxcore-log: 
09-12 07:31:42.570  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.570  3935  3984 I jxcore-log: 
09-12 07:31:42.571  1719  1719 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 07:31:42.571  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 07:31:42.571  3935  3984 I jxcore-log: 
09-12 07:31:42.572  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:42.572  3935  3984 I jxcore-log: 
09-12 07:31:42.576  1719  1719 D SystemUpdateService: onCreate
09-12 07:31:42.578  1719  1719 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-12 07:31:42.579  3935  3984 I jxcore-log: My device name is: motorola-Nexus 6
09-12 07:31:42.579  3935  3984 I jxcore-log: 
09-12 07:31:42.584   874  4380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 07:31:42.596  1719  4393 I SystemUpdateService: active receiver: enabled
,09-12 07:31:42.600  1719  1719 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 07:31:42.602  1719  2520 I iu.UploadsManager: num queued entries: 0
09-12 07:31:42.602  1719  2520 I iu.UploadsManager: num updated entries: 0
,09-12 07:31:42.613  1719  1719 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 07:31:42.616  1719  4393 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-12 07:31:42.617  1719  1719 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 07:31:42.619  4097  4097 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 07:31:42.626  1719  4396 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 07:31:42.626  1719  4396 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 07:31:42.631  1719  4396 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 07:31:42.632  4097  4097 D SprintDMHelper: simOperator: 
09-12 07:31:42.633  4097  4097 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 07:31:42.642   874  4380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 05:31:42 GMT], X-Android-Received-Millis=[1473658302642], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473658302621]}
,09-12 07:31:42.643   874  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 07:31:42.643   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 07:31:42.643   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 07:31:42.644   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 07:31:42.666  1719  2520 I iu.SyncManager: NEXT; no task
,09-12 07:31:42.668  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:42.670  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:42.676  1719  4393 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 07:31:42.678  1719  4393 I SystemUpdateService: now status is 0 (complete)
09-12 07:31:42.678  1719  4393 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 07:31:42.679  1719  4393 I SystemUpdateService: file has been verified
,09-12 07:31:42.683  1719  4393 I SystemUpdateService: OTA package size = 12249756
,09-12 07:31:42.690  1719  4393 I SystemUpdateService: showing system update notification
,09-12 07:31:42.699  1719  1719 D SystemUpdateService: onDestroy
,09-12 07:31:42.703  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 07:31:42.703  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 07:31:42.703  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:31:42.705  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:42.719  1719  4396 E MDM     : [187] SitrepService.a: Error sending sitrep.
,09-12 07:31:42.753  4055  4399 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 07:31:42.848  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 07:31:42.925  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 07:31:42.993  3935  3935 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 07:31:43.558   874  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 07:31:44.002   874  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-12 07:31:44.671  1894  2743 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 07:31:46.202  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:46.310  1501  4406 I VacuumService: Vacuum at: now=1473658306310 tag=VacuumService
,09-12 07:31:46.312  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:31:46.345  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:31:46.345  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 07:31:46.345  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:31:46.346  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 07:31:46.359  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 07:31:46.360  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:31:46.360  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 07:31:46.416  1501  4407 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 07:31:46.419  1501  4407 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 07:31:46.441  1501  4407 W Uploader:  no longer exists, so no auth token.
,09-12 07:31:46.724  3935  3984 I jxcore-log: Use thaliTape
09-12 07:31:46.724  3935  3984 I jxcore-log: 
,09-12 07:31:46.728  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-12 07:31:46.728  3935  3984 I jxcore-log: 
,09-12 07:31:47.747  1501  4407 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 07:31:47.748  1501  4407 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 07:31:47.748  1501  4407 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:31:47.748  1501  4407 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:47.749  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-12 07:31:47.749  3935  3984 I jxcore-log: 
,09-12 07:31:47.776  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-12 07:31:47.776  3935  3984 I jxcore-log: 
,09-12 07:31:47.782  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-12 07:31:47.782  3935  3984 I jxcore-log: 
,09-12 07:31:47.795  1501  4407 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 07:31:47.795  1501  4407 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 07:31:47.795  1501  4407 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 07:31:47.801  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-12 07:31:47.801  3935  3984 I jxcore-log: 
,09-12 07:31:47.806  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-12 07:31:47.806  3935  3984 I jxcore-log: 
,09-12 07:31:48.217  1501  4407 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 07:31:48.217  1501  4407 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 07:31:48.217  1501  4407 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:31:48.217  1501  4407 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:48.249  1501  4407 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 07:31:48.249  1501  4407 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 07:31:48.249  1501  4407 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 07:31:48.617  1501  4407 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 07:31:48.617  1501  4407 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 07:31:48.617  1501  4407 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:31:48.618  1501  4407 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:31:48.658  1501  4407 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 07:31:48.658  1501  4407 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 07:31:48.658  1501  4407 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 07:31:50.500   874  1307 D ConnectivityService: handlePromptUnvalidated 102
,09-12 07:31:51.118  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-12 07:31:51.118  3935  3984 I jxcore-log: 
,09-12 07:31:51.130  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-12 07:31:51.130  3935  3984 I jxcore-log: 
,09-12 07:31:51.140  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-12 07:31:51.140  3935  3984 I jxcore-log: 
,09-12 07:31:51.298  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-12 07:31:51.298  3935  3984 I jxcore-log: 
,09-12 07:31:52.087  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-12 07:31:52.087  3935  3984 I jxcore-log: 
,09-12 07:31:52.149  1501  2035 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 07:31:52.329  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-12 07:31:52.329  3935  3984 I jxcore-log: 
,09-12 07:31:52.336  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-12 07:31:52.336  3935  3984 I jxcore-log: 
,09-12 07:31:52.529  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-12 07:31:52.529  3935  3984 I jxcore-log: 
,09-12 07:31:52.550  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-12 07:31:52.550  3935  3984 I jxcore-log: 
,09-12 07:31:52.555  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-12 07:31:52.555  3935  3984 I jxcore-log: 
,09-12 07:31:52.561  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-12 07:31:52.561  3935  3984 I jxcore-log: 
,09-12 07:31:52.576  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-12 07:31:52.576  3935  3984 I jxcore-log: 
,09-12 07:31:52.595  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-12 07:31:52.595  3935  3984 I jxcore-log: 
,09-12 07:31:52.676  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-12 07:31:52.676  3935  3984 I jxcore-log: 
,09-12 07:31:52.682  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-12 07:31:52.682  3935  3984 I jxcore-log: 
,09-12 07:31:52.707  3935  3984 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-12 07:31:52.707  3935  3984 I jxcore-log: 
,09-12 07:31:52.724  3935  3984 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 07:31:52.725  3935  3984 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 07:31:52.725  3935  3984 I jxcore-log: 
,09-12 07:31:52.727  3935  3984 I jxcore-log: thaliTape.begin
09-12 07:31:52.727  3935  3984 I jxcore-log: 
,09-12 07:31:52.773  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 07:31:52.773  3935  3984 I jxcore-log: 
,09-12 07:31:52.774  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 07:31:52.774  3935  3984 I jxcore-log: 
09-12 07:31:52.774  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 07:31:52.774  3935  3984 I jxcore-log: 
09-12 07:31:52.775  3935  3984 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 07:31:52.775  3935  3984 I jxcore-log: 
,09-12 07:31:52.775  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 07:31:52.775  3935  3984 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-12 07:31:52.775  3935  3984 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 07:31:52.775  3935  3984 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-12 07:32:10.468  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:10.484  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:10.492  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:10.587  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:32:10.588  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 07:32:10.588  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:32:10.589  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:10.660  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:32:10.661  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 07:32:10.662  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 07:32:11.978   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=185997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:32:12.686  3875  4420 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 07:32:12.722  3875  4422 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 07:32:12.766  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 07:32:12.766  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 07:32:12.766  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:32:12.766  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:12.787  3864  4421 V KeepSync: Connecting to GoogleApiClient
,09-12 07:32:12.787   874  2125 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 07:32:12.845  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 07:32:12.845  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 07:32:12.845  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:32:12.845  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:12.879  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 07:32:12.879  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 07:32:12.879  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:32:12.879  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:12.883  3875  4422 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 07:32:12.886  3875  4420 E BooksSync: Soft error
09-12 07:32:12.886  3875  4420 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:32:12.886  3875  4420 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 07:32:12.886  3875  4420 E BooksSync: Sync error
09-12 07:32:12.886  3875  4420 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:32:12.886  3875  4420 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 07:32:12.886  3875  4420 I BooksSync: Finished books sync
,09-12 07:32:12.899  1719  4423 V BaseAuthAsyncOperation: access token request failed
,09-12 07:32:12.900   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162938, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:32:12.901  3864  4421 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 07:32:12.968  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 07:32:12.968  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 07:32:12.968  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:32:12.968  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:12.986  3864  4421 E KeepSync: IOException
09-12 07:32:12.986  3864  4421 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 07:32:12.986  3864  4421 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:32:12.986  3864  4421 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 07:32:12.986  3864  4421 E KeepSync: 	... 10 more
,09-12 07:32:12.986  3864  4421 W KeepSync: Sync result 2
,09-12 07:32:12.994   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 163916, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:32:38.971  1880  3599 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-12 07:32:38.971  1880  3599 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 07:32:39.013  1501  1501 I ConfigService: onCreate
,09-12 07:32:43.074  3875  4426 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 07:32:43.091  3875  4427 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 07:32:43.104  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:43.106  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:43.128  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 07:32:43.128  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 07:32:43.128  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:32:43.128  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:43.163  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:43.165  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:32:43.194  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 07:32:43.194  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 07:32:43.194  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:32:43.195  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:32:43.209  3875  4427 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 07:32:43.209  3875  4426 E BooksSync: Soft error
09-12 07:32:43.209  3875  4426 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:32:43.209  3875  4426 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 07:32:43.211  3875  4426 E BooksSync: Sync error
09-12 07:32:43.211  3875  4426 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:32:43.211  3875  4426 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 07:32:43.211  3875  4426 I BooksSync: Finished books sync
,09-12 07:32:43.222   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 216968, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:32:44.085  1501  1501 I ConfigService: onDestroy
,09-12 07:32:46.432   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=220450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:33:10.191   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:33:13.492  3864  4430 V KeepSync: Connecting to GoogleApiClient
,09-12 07:33:13.492   874  2005 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 07:33:13.552  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:33:13.554  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:33:13.590  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 07:33:13.590  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 07:33:13.590  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:33:13.590  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:33:13.613  1719  4431 V BaseAuthAsyncOperation: access token request failed
,09-12 07:33:13.614  3864  4430 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 07:33:13.692  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 07:33:13.693  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 07:33:13.693  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:33:13.693  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:33:13.719  3864  4430 E KeepSync: IOException
09-12 07:33:13.719  3864  4430 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 07:33:13.719  3864  4430 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:33:13.719  3864  4430 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 07:33:13.719  3864  4430 E KeepSync: 	... 10 more
,09-12 07:33:13.720  3864  4430 W KeepSync: Sync result 2
,09-12 07:33:13.737   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 219221, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:33:34.978   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:33:44.078  3875  4434 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 07:33:44.169  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:33:44.171  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:33:44.178  3875  4436 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 07:33:44.242  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:33:44.242  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:33:44.243  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:33:44.243  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:33:44.321  3126  4435 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 07:33:44.321  3126  4435 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at blb.a(PG:3937)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at czp.a(PG:18188)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:33:44.321  3126  4435 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	... 12 more
09-12 07:33:44.321  3126  4435 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at fal.a(PG:38)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:33:44.321  3126  4435 E HttpOperation: 	... 14 more
,09-12 07:33:44.326  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 07:33:44.327  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 07:33:44.327  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:33:44.327  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:33:44.396  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:33:44.396  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:33:44.396  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:33:44.397  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:33:44.413  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 07:33:44.413  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 07:33:44.413  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:33:44.413  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:33:44.419  3126  4435 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 07:33:44.419  3126  4435 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at hec.a(PG:42)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at hee.a(PG:102)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at czr.a(PG:65)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at kka.a(PG:108)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at czp.a(PG:19176)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:33:44.419  3126  4435 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	... 15 more
09-12 07:33:44.419  3126  4435 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at fal.a(PG:38)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:33:44.419  3126  4435 E HttpOperation: 	... 17 more
09-12 07:33:44.419  3126  4435 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 07:33:44.419  3126  4435 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at hec.a(PG:42)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at hee.a(PG:102)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at czr.a(PG:65)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at kka.a(PG:108)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	... 15 more
09-12 07:33:44.419  3126  4435 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at fal.a(PG:38)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 07:33:44.419  3126  4435 E ExperimentLoader: 	... 17 more
,09-12 07:33:44.459  3875  4436 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 07:33:44.463  3875  4434 E BooksSync: Soft error
09-12 07:33:44.463  3875  4434 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:33:44.463  3875  4434 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 07:33:44.463  3875  4434 E BooksSync: Sync error
09-12 07:33:44.463  3875  4434 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:33:44.463  3875  4434 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 07:33:44.463  3875  4434 I BooksSync: Finished books sync
,09-12 07:33:44.469   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277338, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:33:44.569   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 254124, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:33:58.244   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=292263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:34:16.831  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:34:16.833  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:34:16.872  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:34:16.872  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:34:16.872  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:34:16.872  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:34:16.896  3126  4448 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 07:34:16.896  3126  4448 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at blb.a(PG:3937)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at czp.a(PG:18188)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:34:16.896  3126  4448 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	... 12 more
09-12 07:34:16.896  3126  4448 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at fal.a(PG:38)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:34:16.896  3126  4448 E HttpOperation: 	... 14 more
,09-12 07:34:16.935  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:34:16.935  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:34:16.935  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:34:16.935  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:34:16.950  3126  4448 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 07:34:16.950  3126  4448 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at hec.a(PG:42)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at hee.a(PG:102)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at czr.a(PG:65)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at kka.a(PG:108)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at czp.a(PG:19176)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:34:16.950  3126  4448 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	... 15 more
09-12 07:34:16.950  3126  4448 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at fal.a(PG:38)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:34:16.950  3126  4448 E HttpOperation: 	... 17 more
,09-12 07:34:16.951  3126  4448 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 07:34:16.951  3126  4448 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at hec.a(PG:42)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at hee.a(PG:102)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at czr.a(PG:65)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at kka.a(PG:108)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	... 15 more
09-12 07:34:16.951  3126  4448 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at fal.a(PG:38)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 07:34:16.951  3126  4448 E ExperimentLoader: 	... 17 more
,09-12 07:34:17.057   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 310466, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:34:30.898   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:34:43.185  1501  2035 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 07:34:47.219  3864  4452 V KeepSync: Connecting to GoogleApiClient
,09-12 07:34:47.219   874  2127 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 07:34:47.279  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:34:47.284  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:34:47.326  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 07:34:47.327  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 07:34:47.327  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:34:47.327  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:34:47.351  1719  4453 V BaseAuthAsyncOperation: access token request failed
,09-12 07:34:47.353  3864  4452 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 07:34:47.430  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 07:34:47.431  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 07:34:47.431  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:34:47.431  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:34:47.456  3864  4452 E KeepSync: IOException
09-12 07:34:47.456  3864  4452 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 07:34:47.456  3864  4452 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:34:47.456  3864  4452 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 07:34:47.456  3864  4452 E KeepSync: 	... 10 more
,09-12 07:34:47.456  3864  4452 W KeepSync: Sync result 2
,09-12 07:34:47.466   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 312170, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:34:50.415  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:34:50.520  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 07:34:50.521  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 07:34:50.521  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:34:50.522  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:34:50.576  1501  2410 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 07:34:50.576  1501  2410 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 07:34:50.576  1501  2410 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 07:34:50.576  1501  2410 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 07:34:50.576  1501  2410 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 07:34:50.576  1501  2410 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 07:34:50.576  1501  2410 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 07:34:50.594  3639  3669 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 07:34:50.594  3639  3669 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 07:34:50.594  3639  3669 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 07:34:50.594  3639  3669 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 07:34:50.594  3639  3669 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 07:34:50.594  3639  3669 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 07:34:50.594  3639  3669 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 07:34:50.982   874  1598 I ActivityManager: Start proc 4457:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-12 07:34:51.088  4457  4457 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,09-12 07:34:51.181  4457  4469 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-12 07:34:51.293  4457  4469 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-12 07:34:51.346  4457  4469 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-12 07:34:51.400  4457  4457 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-12 07:34:51.578  4489  4489 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1591186071.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1591186071.dex
,09-12 07:34:51.639  4457  4457 W InstanceID/Rpc: Found 10011
,09-12 07:34:51.833  4489  4489 I dex2oat : dex2oat took 257.286ms (threads: 4) arena alloc=275KB java alloc=37KB native alloc=1386KB free=1429KB
,09-12 07:35:15.525   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=369544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:35:21.098  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 07:35:21.100  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:35:21.137  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:35:21.137  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:35:21.138  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:35:21.138  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:35:21.152  3126  4544 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 07:35:21.152  3126  4544 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at blb.a(PG:3937)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at czp.a(PG:18188)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:35:21.152  3126  4544 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	... 12 more
09-12 07:35:21.152  3126  4544 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at fal.a(PG:38)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:35:21.152  3126  4544 E HttpOperation: 	... 14 more
,09-12 07:35:21.211  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:35:21.211  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 07:35:21.211  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:35:21.211  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:35:21.226  3126  4544 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 07:35:21.226  3126  4544 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at hec.a(PG:42)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at hee.a(PG:102)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at czr.a(PG:65)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at kka.a(PG:108)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at czp.a(PG:19176)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:35:21.226  3126  4544 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	... 15 more
09-12 07:35:21.226  3126  4544 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at fal.a(PG:38)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:35:21.226  3126  4544 E HttpOperation: 	... 17 more
,09-12 07:35:21.227  3126  4544 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 07:35:21.227  3126  4544 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at hec.a(PG:42)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at hee.a(PG:102)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at czr.a(PG:65)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at kka.a(PG:108)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	... 15 more
09-12 07:35:21.227  3126  4544 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at fal.a(PG:38)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 07:35:21.227  3126  4544 E ExperimentLoader: 	... 17 more
,09-12 07:35:21.319   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 374831, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:35:29.565   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=383583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:35:51.409  3875  4549 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 07:35:51.443  3875  4550 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 07:35:51.455  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:35:51.461  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:35:51.491  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 07:35:51.491  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 07:35:51.491  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:35:51.491  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:35:51.519  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:35:51.521  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:35:51.549  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 07:35:51.549  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 07:35:51.549  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:35:51.549  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:35:51.566  3875  4550 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 07:35:51.567  3875  4549 E BooksSync: Soft error
09-12 07:35:51.567  3875  4549 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:35:51.567  3875  4549 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 07:35:51.567  3875  4549 E BooksSync: Sync error
09-12 07:35:51.567  3875  4549 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 07:35:51.567  3875  4549 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 07:35:51.567  3875  4549 I BooksSync: Finished books sync
,09-12 07:35:51.579   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 398681, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:36:10.778   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=424797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:36:47.658   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=461677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:36:56.531  3864  4553 V KeepSync: Connecting to GoogleApiClient
,09-12 07:36:56.531   874  1598 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 07:36:56.575  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:36:56.578  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:36:56.602  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 07:36:56.603  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 07:36:56.603  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:36:56.603  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:36:56.621  1719  4554 V BaseAuthAsyncOperation: access token request failed
,09-12 07:36:56.623  3864  4553 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 07:36:56.666  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 07:36:56.666  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 07:36:56.666  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:36:56.666  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:36:56.680  3864  4553 E KeepSync: IOException
09-12 07:36:56.680  3864  4553 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 07:36:56.680  3864  4553 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 07:36:56.680  3864  4553 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 07:36:56.680  3864  4553 E KeepSync: 	... 10 more
,09-12 07:36:56.680  3864  4553 W KeepSync: Sync result 2
,09-12 07:36:56.687   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 470314, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:37:10.938   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=484957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:37:17.605   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=491623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:37:29.086  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:37:29.087  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:37:29.133  1501  2278 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:37:29.133  1501  2278 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:37:29.133  1501  2278 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:37:29.134  1501  2278 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:37:29.149  3126  4558 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 07:37:29.149  3126  4558 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at blb.a(PG:3937)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at czp.a(PG:18188)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:37:29.149  3126  4558 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	... 12 more
09-12 07:37:29.149  3126  4558 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at fal.a(PG:38)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:37:29.149  3126  4558 E HttpOperation: 	... 14 more
,09-12 07:37:29.220  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 07:37:29.220  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 07:37:29.221  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:37:29.221  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:37:29.243  3126  4558 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 07:37:29.243  3126  4558 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jdm.a(PG:82)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jcs.o(PG:406)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jcn.a(PG:1379)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jcs.i(PG:143)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at hec.a(PG:42)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at hee.a(PG:102)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at czr.a(PG:65)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at kka.a(PG:108)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at czp.a(PG:19176)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at czp.a(PG:9081)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at czq.run(PG:1686)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:37:29.243  3126  4558 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jdj.a(PG:4091)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jdj.a(PG:1125)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jdm.a(PG:77)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	... 15 more
09-12 07:37:29.243  3126  4558 E HttpOperation: Caused by: faj: BadAuthentication
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at fal.a(PG:38)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	at jdj.a(PG:4089)
09-12 07:37:29.243  3126  4558 E HttpOperation: 	... 17 more
,09-12 07:37:29.244  3126  4558 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 07:37:29.244  3126  4558 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at hec.a(PG:42)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at hee.a(PG:102)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at czr.a(PG:65)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at kka.a(PG:108)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	... 15 more
09-12 07:37:29.244  3126  4558 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at fal.a(PG:38)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 07:37:29.244  3126  4558 E ExperimentLoader: 	... 17 more
,09-12 07:37:29.334   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 502847, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 07:37:41.125   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=515144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:37:47.525   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=521544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:38:10.778   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=544797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:38:56.152   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:39:19.418   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=613437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:39:55.912   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=649931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 07:40:18.654   874  1288 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
09-12 07:40:18.655   874  1288 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,09-12 07:40:19.205   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=673223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:40:53.060   874  1288 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
09-12 07:40:53.061   874  1288 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,09-12 07:46:39.621   874  1987 I ActivityManager: Start proc 4626:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-12 07:46:39.674  4626  4626 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-12 07:46:39.705  4626  4626 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-12 07:46:39.705  4626  4626 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 07:46:39.705  4626  4626 I GAv4    :   adb logcat -s GAv4
,09-12 07:46:39.742  4626  4626 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 07:46:39.747  4626  4626 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 07:46:39.762  4626  4641 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 07:46:39.852   874  2128 I ActivityManager: Killing 3731:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-12 07:46:42.908  3639  3639 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-12 07:46:42.940  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:42.953  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:42.958  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:43.028  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 07:46:43.028  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 07:46:43.028  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:46:43.029  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:46:43.093  3639  3639 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 07:46:43.122  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:43.202  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 07:46:43.202  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 07:46:43.202  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:46:43.203  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:46:43.286  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:43.312  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 07:46:43.312  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 07:46:43.312  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:46:43.312  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:46:43.336  3639  3639 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 07:46:43.613  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:43.692  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 07:46:43.693  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 07:46:43.693  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:46:43.693  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:46:43.759  3639  3639 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-12 07:46:43.762  3639  3639 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-12 07:46:43.768  3639  3639 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-12 07:46:43.783  3639  3693 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-12 07:46:43.786  3639  3639 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,09-12 07:46:47.938   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1061957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 07:46:53.604   874  4381 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1067623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 07:46:58.536  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:58.548  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:58.553  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:46:58.608  1501  1988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:46:58.609  1501  1988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:46:58.609  1501  1988 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:46:58.609  1501  1988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:46:58.649  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:46:58.649  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:46:58.649  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-12 07:47:18.862  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:18.870  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:18.871  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:18.916  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:47:18.917  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:47:18.917  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:47:18.917  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:47:18.959  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:47:18.959  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:47:18.960  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-12 07:47:39.144  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:39.156  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:39.160  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:39.204  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:47:39.204  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:47:39.204  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 07:47:39.205  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:47:39.251  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 07:47:39.251  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:47:39.251  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-12 07:47:59.566  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:59.583  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:59.589  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:47:59.663  1501  3719 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 07:47:59.664  1501  3719 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:47:59.664  1501  3719 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:47:59.664  1501  3719 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:47:59.725  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:47:59.726  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:47:59.727  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 07:48:20.015  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:48:20.028  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:48:20.031  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:48:20.069  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:48:20.069  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 07:48:20.069  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:48:20.069  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:48:20.099  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:48:20.099  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 07:48:20.100  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 07:48:40.340  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:48:40.353  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:48:40.356  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 07:48:40.419  1501  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 07:48:40.420  1501  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 07:48:40.420  1501  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 07:48:40.420  1501  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 07:48:40.468  3639  3639 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 07:48:40.469  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 07:48:40.470  3639  3639 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 07:49:24.840   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-12 07:54:37.379  4715  4715 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 07:54:37.383  4715  4715 D AndroidRuntime: CheckJNI is OFF
09-12 07:54:37.419  4715  4715 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 07:54:37.461  4715  4715 I Radio-JNI: register_android_hardware_Radio DONE
09-12 07:54:37.482  4715  4715 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 07:54:37.488   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 07:54:37.489   874   887 I ActivityManager: Killing 3935:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-12 07:54:37.602   874  2005 D GraphicsStats: Buffer count: 2
09-12 07:54:37.603   874   884 I WindowState: WIN DEATH: Window{6dc27e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 07:54:37.603   874  1305 D WifiService: Client connection lost with reason: 4
09-12 07:54:37.614   874   897 W PackageSettings: Skipping PackageSetting{a967784 com.example.hello/10273} due to missing metadata
09-12 07:54:37.651   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 07:54:37.651   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 07:54:37.652   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-12 07:54:37.652   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 07:54:37.652   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:37.652   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:37.652   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 07:54:37.652   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 07:54:37.653   874   887 I ActivityManager:   Force finishing activity ActivityRecord{b7a77e9 u0 com.test.thalitest/.MainActivity t4}
09-12 07:54:37.654   874   897 I art     : Starting a blocking GC Explicit
09-12 07:54:37.667   874  2005 W ActivityManager: Spurious death for ProcessRecord{c6507f8 0:com.test.thalitest/u0a0}, curProc for 3935: null
09-12 07:54:37.711   874   897 I art     : Explicit concurrent mark sweep GC freed 40148(3MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 794us total 55.528ms
09-12 07:54:37.731   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 07:54:37.734  4715  4715 I art     : System.exit called, status: 0
09-12 07:54:37.734  4715  4715 I AndroidRuntime: VM exiting with result code 0.
09-12 07:54:37.746   874   897 I ActivityManager: Start proc 4728:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-12 07:54:37.747   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 07:54:37.760   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 07:54:37.763  4314  4314 D BluetoothMapAppObserver: onReceive
09-12 07:54:37.764  4314  4314 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 07:54:37.765  1880  1880 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 07:54:37.765  1894  2204 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 07:54:37.768   874  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 07:54:37.783  3752  3752 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 07:54:37.799  1961  1961 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-12 07:54:37.803  1880  4740 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 07:54:37.826   874  2006 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3935 uid 10000
09-12 07:54:37.834   874  1302 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-12 07:54:37.830  1880  1880 I Keyboard.Facilitator: onFinishInput()
09-12 07:54:37.838  1880  4740 E native  : dynamic-lm.cc:252 Cannot rename /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict
09-12 07:54:37.838  1880  4740 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 07:54:37.839  1880  4740 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 07:54:37.839  1880  4740 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 07:54:37.839  1880  4740 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 07:54:37.841  1880  4740 I Decoder : createOrResetDecoder
09-12 07:54:37.852   874  1987 I ActivityManager: Start proc 4745:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 07:54:37.858   874  2125 I ActivityManager: Killing 2026:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-12 07:54:37.863  1501  1501 I ConfigService: onCreate
09-12 07:54:37.865   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 07:54:37.880  1501  4757 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 07:54:37.880  1501  4757 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-12 07:54:37.882  1501  4757 W SQLiteOpenHelper: Opened config.db in read-only mode
09-12 07:54:37.915   874  1305 D WifiService: Client connection lost with reason: 4
09-12 07:54:37.927  1880  4740 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-12 07:54:37.948  4745  4745 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-12 07:54:37.958  1880  4740 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 07:54:37.959  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 07:54:37.960  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 07:54:37.961  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 07:54:37.961  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 07:54:37.962  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 07:54:37.962  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 07:54:37.962  1880  4740 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 07:54:37.962  1880  4740 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 07:54:37.963  1880  4740 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 07:54:37.963  1880  4740 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 07:54:37.963  1880  4740 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 07:54:37.963  1880  4740 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 07:54:37.967  1977  2062 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 07:54:37.970   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 07:54:37.971   874   886 E PackageManager: Failed to write settings, restoring backup
09-12 07:54:37.971   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 07:54:37.971   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 07:54:37.971   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 07:54:37.971   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 07:54:37.971   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 07:54:37.971   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:37.971   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:37.971   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 07:54:37.981   874  2125 I ActivityManager: Start proc 4761:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-12 07:54:37.981   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-12 07:54:37.981   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 07:54:37.981   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 07:54:37.981   874   887 E DropBoxManagerService: 	... 13 more
--------- beginning of crash
09-12 07:54:37.982  1977  2062 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 07:54:37.982  1977  2062 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1977
09-12 07:54:37.982  1977  2062 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:37.982  1977  2062 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 07:54:37.984   874  1598 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 07:54:37.984   874  4769 E DropBoxManagerService: Can't write: system_app_crash
09-12 07:54:37.984   874  4769 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 07:54:37.984   874  4769 E DropBoxManagerService: 	... 5 more
09-12 07:54:37.988  1977  2062 I Process : Sending signal. PID: 1977 SIG: 9
09-12 07:54:38.011  4745  4745 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-12 07:54:38.027   874  2051 I ActivityManager: Start proc 4775:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-12 07:54:38.029  4745  4778 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:38.049  4745  4778 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 07:54:38.049  4745  4778 E AndroidRuntime: Process: android.process.acore, PID: 4745
09-12 07:54:38.049  4745  4778 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:38.049  4745  4778 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: Can't write: system_app_crash
09-12 07:54:38.052   874  4789 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 07:54:38.052   874  4789 E DropBoxManagerService: 	... 5 more
09-12 07:54:38.065   874  1294 W InputDispatcher: channel 'a8d9a8c com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-12 07:54:38.065   874  1294 E InputDispatcher: channel 'a8d9a8c com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-12 07:54:38.065   874   885 D GraphicsStats: Buffer count: 1
09-12 07:54:38.065   874  2051 I WindowState: WIN DEATH: Window{a8d9a8c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-12 07:54:38.065   874  2051 W InputDispatcher: Attempted to unregister already unregistered input channel 'a8d9a8c com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-12 07:54:38.073  4745  4778 I Process : Sending signal. PID: 4745 SIG: 9
09-12 07:54:38.076   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1977) has died
09-12 07:54:38.077   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-12 07:54:38.078   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-12 07:54:38.082   280   280 E lowmemorykiller: Error writing /proc/4745/oom_score_adj; errno=22
09-12 07:54:38.095  4775  4775 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-12 07:54:38.098   874   887 I ActivityManager: Start proc 4791:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 07:54:38.141  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 07:54:38.142   280   280 E lowmemorykiller: Error writing /proc/4745/oom_score_adj; errno=22
09-12 07:54:38.142   280   280 E lowmemorykiller: Error writing /proc/4745/oom_score_adj; errno=22
09-12 07:54:38.143  1501  1501 D AndroidRuntime: Shutting down VM
09-12 07:54:38.143  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
09-12 07:54:38.143  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
09-12 07:54:38.143  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 07:54:38.143  1501  1501 E AndroidRuntime: 	... 8 more
09-12 07:54:38.147   874  4806 E DropBoxManagerService: Can't write: system_app_crash
09-12 07:54:38.147   874  4806 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 07:54:38.147   874  4806 E DropBoxManagerService: 	... 5 more
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:54:38.147  4791  4791 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 07:54:38.147  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
09-12 07:54:38.147  4791  4791 D AndroidRuntime: Shutting down VM
09-12 07:54:38.154  4791  4791 E AndroidRuntime: FATAL EXCEPTION: main
09-12 07:54:38.154  4791  4791 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4791
09-12 07:54:38.154  4791  4791 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 07:54:38.154  4791  4791 E AndroidRuntime: 	... 10 more
09-12 07:54:38.156   874  2006 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 07:54:38.156  4791  4791 I Process : Sending signal. PID: 4791 SIG: 9
09-12 07:54:38.157   874  4807 E DropBoxManagerService: Can't write: system_app_crash
09-12 07:54:38.157   874  4807 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 07:54:38.157   874  4807 E DropBoxManagerService: 	... 5 more
09-12 07:54:38.168   280   280 E lowmemorykiller: Error writing /proc/4745/oom_score_adj; errno=22
09-12 07:54:38.186   280   280 E lowmemorykiller: Error writing /proc/4745/oom_score_adj; errno=22
09-12 07:54:38.187   874  2005 I ActivityManager: Killing 4004:com.android.settings/1000 (adj 15): empty #17
09-12 07:54:38.217   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
