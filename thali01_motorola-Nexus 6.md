#### Test 836273370459b7a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 16:33:51.990   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-13 16:33:53.797  3850  3850 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 16:33:53.803  3850  3850 D AndroidRuntime: CheckJNI is OFF
09-13 16:33:53.847  3850  3850 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 16:33:53.899  3850  3850 I Radio-JNI: register_android_hardware_Radio DONE
09-13 16:33:53.922  3850  3850 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 16:33:53.931   873  3804 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 16:33:53.972  2122  2418 W SearchService: Abort, client detached.
09-13 16:33:53.980  3850  3850 D AndroidRuntime: Shutting down VM
09-13 16:33:53.986  2122  2122 I HotwordDetector: Closing mic
09-13 16:33:53.986  2122  2311 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@28dcf12
09-13 16:33:53.986  2122  2318 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 16:33:53.998   873  1383 I ActivityManager: Start proc 3859:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 16:33:54.052   377  2320 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 16:33:54.054   377  2320 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 16:33:54.058   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 16:33:54.060  2122  2317 I MicroRecognitionRnrImpl: Detection finished
09-13 16:33:54.060  2122  2315 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 16:33:54.082  3859  3859 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 16:33:54.110  3859  3859 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 16:33:54.117  3859  3859 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7661-7664)
09-13 16:33:54.117  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:33:54.135  3859  3859 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dfc892d}
09-13 16:33:54.135  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:33:54.136  3859  3859 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 16:33:54.142  3859  3859 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 16:33:54.143  3859  3859 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 16:33:54.156  3859  3859 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 16:33:54.166  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:33:54.166  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:33:54.166  3859  3859 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 16:33:54.166  3859  3859 I Adreno  : Build Date                       : 10/20/15
09-13 16:33:54.166  3859  3859 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 16:33:54.166  3859  3859 I Adreno  : Local Branch                     : M14
09-13 16:33:54.166  3859  3859 I Adreno  : Remote Branch                    : 
09-13 16:33:54.166  3859  3859 I Adreno  : Remote Branch                    : 
09-13 16:33:54.166  3859  3859 I Adreno  : Reconstruct Branch               : 
,09-13 16:33:54.236   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@868a905:true
,09-13 16:33:54.291  3859  3859 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:33:54.303  3859  3859 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 16:33:54.372  3859  3899 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 16:33:54.379  3859  3885 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 16:33:54.414  3859  3899 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:33:54.484   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +500ms
,09-13 16:33:54.486  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-13 16:33:54.534  3859  3859 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3859
,09-13 16:33:54.615  3859  3859 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:33:54.802   873  2009 I ActivityManager: Killing 3177:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 16:33:54.809  3859  3901 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1680738000
,09-13 16:33:54.815  3859  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:33:54.815  3859  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:33:54.815  3859  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:33:54.815  3859  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:33:54.815  3859  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 16:33:54.815  3859  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2991a88 added. We now have 1 listener(s)
09-13 16:33:54.818  3859  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 16:33:54.820  3859  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:33:54.820  3859  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:54.820  3859  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:33:54.824  3859  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127ca07 added. We now have 1 listener(s)
09-13 16:33:54.824  3859  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:54.830   873  1316 D WifiService: New client listening to asynchronous messages
,09-13 16:33:54.830  3859  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:33:54.830  3859  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:33:54.831  3859  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:33:54.831  3859  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:33:54.831  3859  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 16:33:54.844   873  2009 I ActivityManager: Killing 3416:com.android.cellbroadcastreceiver/u0a4 (adj 15): empty #18
,09-13 16:33:54.895  3859  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:54.895  3859  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 16:33:54.906  3859  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:54.907  3859  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:54.907  3859  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 16:33:54.907  3859  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:54.907  3859  3901 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:33:54.985  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:54.989  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:54.991  3859  3859 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:33:55.770  3859  3910 W jxcore-log: Initializing JXcore engine
,09-13 16:33:55.770  3859  3910 W jxcore-log: JXcore engine is ready
,09-13 16:33:55.809  3910  3910 W Thread-338: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 16:33:55.809  3910  3910 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13205]" dev="sockfs" ino=13205 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 16:33:55.809  3910  3910 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 16:33:55.809  3910  3910 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27354]" dev="sockfs" ino=27354 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 16:33:55.819  3859  3910 W jxcore-log: Starting JXcore engine
,09-13 16:33:55.898  3859  3910 W jxcore-log: Platform android
09-13 16:33:55.898  3859  3910 W jxcore-log: 
09-13 16:33:55.898  3859  3910 W jxcore-log: Process ARCH arm
09-13 16:33:55.898  3859  3910 W jxcore-log: 
,09-13 16:33:56.097  3859  3910 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:33:56.097  3859  3910 I jxcore-log: 
,09-13 16:33:56.097  3859  3910 W jxcore-log: JXcore engine is started
,09-13 16:33:56.111  3859  3901 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 16:33:56.116  3859  3859 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:33:58.035   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:33:58.321   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 16:34:01.064   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:34:04.247  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:34:04.252  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:34:04.254  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:34:04.276  1513  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 16:34:04.276  1513  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 16:34:04.277  1513  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 16:34:04.277  1513  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:34:04.293  3593  3593 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 16:34:04.293  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 16:34:04.293  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 16:34:05.916  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:34:05.916  3859  3910 I jxcore-log: 
,09-13 16:34:05.918  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:34:05.918  3859  3910 I jxcore-log: 
,09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:05.955  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:05.965  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:05.968  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:34:05.968  3859  3910 I jxcore-log: 
,09-13 16:34:05.970  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:34:05.970  3859  3910 I jxcore-log: 
,09-13 16:34:05.998  1513  2141 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 16:34:05.998  1513  2141 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 16:34:05.999  1513  2141 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 16:34:05.999  1513  2141 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:34:06.031  3632  3923 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 16:34:06.031  3632  3923 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jdm.a(PG:82)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jcs.o(PG:406)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jcn.a(PG:1379)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jcs.i(PG:143)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at blb.a(PG:3937)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at czp.a(PG:18188)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at czp.a(PG:9081)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at czq.run(PG:1686)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:34:06.031  3632  3923 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jdj.a(PG:4091)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jdj.a(PG:1125)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jdm.a(PG:77)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	... 12 more
09-13 16:34:06.031  3632  3923 E HttpOperation: Caused by: faj: BadAuthentication
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at fal.a(PG:38)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	at jdj.a(PG:4089)
09-13 16:34:06.031  3632  3923 E HttpOperation: 	... 14 more
,09-13 16:34:06.103  1513  2989 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 16:34:06.103  1513  2989 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 16:34:06.103  1513  2989 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 16:34:06.103  1513  2989 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:34:06.141  3632  3923 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 16:34:06.141  3632  3923 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jdm.a(PG:82)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jcs.o(PG:406)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jcn.a(PG:1379)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jcs.i(PG:143)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at hec.a(PG:42)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at hee.a(PG:102)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at czr.a(PG:65)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at kka.a(PG:108)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at czp.a(PG:19176)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at czp.a(PG:9081)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at czq.run(PG:1686)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:34:06.141  3632  3923 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jdj.a(PG:4091)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jdj.a(PG:1125)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jdm.a(PG:77)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	... 15 more
09-13 16:34:06.141  3632  3923 E HttpOperation: Caused by: faj: BadAuthentication
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at fal.a(PG:38)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	at jdj.a(PG:4089)
09-13 16:34:06.141  3632  3923 E HttpOperation: 	,... 17 more
09-13 16:34:06.141  3632  3923 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 16:34:06.141  3632  3923 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at hec.a(PG:42)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at hee.a(PG:102)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at czr.a(PG:65)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at kka.a(PG:108)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	... 15 more
09-13 16:34:06.141  3632  3923 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at fal.a(PG:38)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 16:34:06.141  3632  3923 E ExperimentLoader: 	... 17 more
,09-13 16:34:06.329   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129296, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 16:34:06.469  3859  3910 I jxcore-log: Unit Test app is loaded
09-13 16:34:06.469  3859  3910 I jxcore-log: 
,09-13 16:34:06.475  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:06.475  3859  3910 I jxcore-log: 
,09-13 16:34:06.481  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:34:06.481  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69c6c7d added. We now have 2 listener(s)
,09-13 16:34:06.483  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:34:06.483  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:06.483  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:34:06.483  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 16:34:06.483  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f567772 added. We now have 2 listener(s)
,09-13 16:34:06.483  3859  3910 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:06.484  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:06.489  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:06.499  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:06.505  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:06.505  3859  3910 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:06.506  3859  3910 D ExecuteNativeTests: Running unit tests
,09-13 16:34:06.523  3859  3910 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:34:06.525  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:06.525   873   883 D WifiService: setWifiEnabled: true pid=3859, uid=10000
09-13 16:34:06.525   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:34:06.531  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:06.531  3859  3859 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 16:34:06.534  3859  3910 I System.out: Running UT
,09-13 16:34:13.194   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:34:16.634  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:34:16.634  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 added. We now have 3 listener(s)
,09-13 16:34:16.636  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:34:16.636  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:34:16.636  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:34:16.636  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:16.636  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 added. We now have 3 listener(s)
,09-13 16:34:16.636  3859  3910 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:34:16.638  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:16.644  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:16.656  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:16.663  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:16.663  3859  3910 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:16.684  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:16.689  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:34:16.689  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:16.689  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:16.689  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:16.691  3859  3910 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 16:34:16.691  3859  3910 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:34:16.691  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:34:16.691  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:16.691  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:16.691  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:16.691  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:16.692  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:16.692  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:16.692  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:34:16.692  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 removed from the list
,09-13 16:34:16.692  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:16.692  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 removed from the list
09-13 16:34:16.692  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:16.693  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:16.693  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:16.702  3859  3910 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 16:34:16.703  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:16.703  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:16.703  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:16.704  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:16.704  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:16.704  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:16.704  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:16.704  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:16.704  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:16.709  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-13 16:34:16.709  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:34:16.710  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:34:16.711  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:34:16.711  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-13 16:34:16.711  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:34:16.711  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:34:16.711  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:34:16.711  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 16:34:16.712  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:34:16.712  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:16.712  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:16.712  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:16.713  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:16.713  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:16.713  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:16.714  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:16.714  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:16.714  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:16.715  3859  3910 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:34:16.719  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:16.727  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:16.731  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:16.733  3859  3910 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:16.735  3859  3910 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-13 16:34:16.735  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 16:34:16.736  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:16.737  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:16.738  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:16.738  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:16.738  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:16.741  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:16.742  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:16.745  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:16.746  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:16.746  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:16.747  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:16.747  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:16.747  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:16.747  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:16.750  3859  3927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:16.759  3859  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:16.765  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:16.765  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:16.779  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:16.785  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 16:34:16.786  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:16.789  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:16.790  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:34:16.791  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-13 16:34:16.793  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:16.794  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:16.794  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:16.796  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:16.802  2637  2652 D BtGatt.GattService: registerClient() - UUID=db43ab63-65bf-4601-b4c9-f9fe9fb9af97
09-13 16:34:16.804  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=db43ab63-65bf-4601-b4c9-f9fe9fb9af97, clientIf=5
09-13 16:34:16.805  3859  3869 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:16.810  2637  2693 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:16.817  2637  2693 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:16.841  2637  2688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:34:16.857  2637  2688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:34:16.860  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:16.861  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:16.867  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:16.872  3859  3910 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:16.873  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:16.874  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:16.874  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:34:16.874  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:16.875  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:16.875  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:16.883  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:16.884  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:17.380  3859  3910 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:34:17.381  3859  3910 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 16:34:17.381  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:34:17.382  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:34:17.382  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:17.383  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:17.383  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:17.386  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:34:17.386  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:17.386  3859  3927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:17.387  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:17.387  3859  3927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:17.387  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:17.387  3859  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:17.387  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:17.387  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:17.388  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:17.389  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:17.393  3859  3910 D BluetoothAdapter: STATE_ON
09-13 16:34:17.393  3859  3910 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:17.394  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:17.394  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:17.397  2637  2693 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:17.398  2637  2693 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:34:17.418  2637  2688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:34:17.418  2637  2688 D BtGatt.GattService: Client app is not null!
,09-13 16:34:17.420  2637  2885 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:34:17.421  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:17.421  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:17.421  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:17.422  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:17.422  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:17.425  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:17.425  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:17.426  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:17.427  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:17.430  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:34:17.430  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:17.432  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:17.432  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:17.432  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:17.433  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:17.433  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:17.434  3859  3910 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:34:17.434  3859  3910 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:34:17.435  3859  3910 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 16:34:17.435  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-13 16:34:17.435  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:17.435  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:17.435  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:17.435  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:17.436  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:34:17.437  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:17.437  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:17.437  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:17.437  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:17.437  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:17.437  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:17.438  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:17.441  3859  3930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:17.443  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:34:17.443  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:34:17.447  3859  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:17.453  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:17.454  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:17.454  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:17.457  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:17.457  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:34:17.457  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-13 16:34:17.457  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:17.457  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:17.458  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:34:17.458  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:17.463  2637  2652 D BtGatt.GattService: registerClient() - UUID=5ca39690-1ed8-4eec-8c4b-69475165f3fc
09-13 16:34:17.463  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=5ca39690-1ed8-4eec-8c4b-69475165f3fc, clientIf=5
09-13 16:34:17.464  3859  3870 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:17.465  2637  2693 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:17.468  2637  2693 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:17.504  2637  2688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:34:17.527  2637  2688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:34:17.529  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:17.529  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:17.536  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:17.539  3859  3910 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:17.540  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:17.541  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:17.541  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:17.541  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:17.542  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:17.542  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:17.555  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:17.557  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:18.047  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:18.047  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:18.047  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:18.048  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:18.050  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:18.050  3859  3930 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:18.050  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:18.051  3859  3930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:18.051  3859  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:18.051  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:18.051  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:18.051  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:18.051  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:18.052  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:18.052  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:18.052  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:18.053  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:18.055  3859  3910 D BluetoothAdapter: STATE_ON
09-13 16:34:18.056  3859  3910 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:18.057  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:18.057  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:18.060  2637  2693 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:18.061  2637  2693 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:34:18.089  2637  2688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 16:34:18.089  2637  2688 D BtGatt.GattService: Client app is not null!
,09-13 16:34:18.092  2637  2885 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:34:18.093  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:18.093  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:18.093  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:18.093  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:18.094  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:18.096  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:18.096  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:18.097  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:18.097  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:18.099  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:18.099  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:18.099  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:34:18.100  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:18.100  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:18.100  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:18.100  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.103  3859  3910 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:34:18.105  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:18.119  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:18.124  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:18.124  3859  3910 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:18.124  3859  3910 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-13 16:34:18.124  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-13 16:34:18.124  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:18.125  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:18.125  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:18.125  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:18.129  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:18.130  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:18.130  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:18.130  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:18.131  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:18.131  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:18.131  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:18.131  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:18.134  3859  3932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:18.135  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:18.135  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:18.141  3859  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:18.143  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:18.144  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:18.152  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:18.154  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 16:34:18.154  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:18.159  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:18.159  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:34:18.159  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-13 16:34:18.159  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:18.159  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:18.159  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:34:18.161  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.166  2637  2655 D BtGatt.GattService: registerClient() - UUID=25d45531-cbb4-4cb7-af76-04826658bc67
09-13 16:34:18.166  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=25d45531-cbb4-4cb7-af76-04826658bc67, clientIf=5
,09-13 16:34:18.167  3859  3869 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:18.170  2637  2693 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:18.175  2637  2693 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:18.188  2637  2688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:34:18.199  2637  2688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:34:18.201  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:18.201  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:18.206  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:18.210  3859  3910 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:18.210  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:18.210  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:18.210  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:18.210  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:18.211  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:18.211  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:18.214  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:18.214  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:18.715  3859  3910 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:34:18.715  3859  3910 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:34:18.716  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:34:18.716  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:34:18.716  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:34:18.716  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:18.716  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:18.717  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:18.719  3859  3932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:18.720  3859  3932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:18.720  3859  3932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:18.722  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:18.723  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:18.723  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:18.723  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:18.724  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:18.724  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:18.724  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:18.727  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.727  3859  3910 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:18.728  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:18.728  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:18.731  2637  2693 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:18.733  2637  2693 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:34:18.750  2637  2688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:34:18.751  2637  2688 D BtGatt.GattService: Client app is not null!
,09-13 16:34:18.754  2637  2886 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:34:18.755  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:18.755  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:18.756  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:18.756  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:18.756  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:18.760  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:18.760  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:18.760  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:34:18.761  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:18.762  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:34:18.763  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:34:18.763  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:18.763  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:18.764  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:18.764  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:18.764  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:18.764  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.765  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.765  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:18.765  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:18.765  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.765  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:18.765  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.765  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.768  3859  3910 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 16:34:18.770  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.771  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:18.771  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.771  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:18.771  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.772  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:18.772  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.772  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.772  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.775  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 16:34:18.775  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:18.776  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:18.776  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.776  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:18.777  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.777  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:18.777  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.777  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:18.777  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.779  3859  3910 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:34:18.780  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.780  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.780  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.780  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:18.781  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.782  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:18.782  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:18.782  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.783  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.783  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:34:18.784  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.784  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.784  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.784  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:18.784  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:18.784  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:18.784  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.784  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.784  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.785  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:34:18.788  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:18.788  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:18.788  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:34:18.788  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:18.788  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:18.788  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:34:18.788  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:18.789  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:18.789  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.789  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.789  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.789  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:18.789  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.789  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:18.789  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.789  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.790  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.790  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:18.791  3859  3910 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:34:18.791  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:34:18.798  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:34:18.798  3859  3910 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-13 16:34:18.798  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:34:18.799  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:34:18.800  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 16:34:18.801  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:34:18.801  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 16:34:18.801  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:34:18.801  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 16:34:18.801  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 16:34:18.801  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:34:18.802  3859  3910 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 16:34:18.802  3859  3910 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:34:18.802  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:34:18.803  3859  3910 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:18.803  3859  3910 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
09-13 16:34:18.804  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:34:18.804  3859  3910 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:18.804  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:34:18.817  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-13 16:34:18.818  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-13 16:34:18.818  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-13 16:34:18.820  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:34:18.820  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:34:18.821  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-13 16:34:18.821  3859  3910 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 16:34:18.822  3859  3910 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:34:18.822  3859  3935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 439)
,09-13 16:34:18.824  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:18.825  3859  3935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:18.825  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:18.825  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.825  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-13 16:34:18.827  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:18.827  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.827  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:18.828  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.828  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.828  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.829  3859  3936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 439
09-13 16:34:18.829  3859  3936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 439)
09-13 16:34:18.829  3859  3936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 439)
,09-13 16:34:18.830  3859  3935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 439)
,09-13 16:34:18.832  3859  3910 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-13 16:34:18.832  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:18.832  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.832  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.832  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:18.832  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.833  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:18.833  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.833  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.833  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:18.833  3859  3910 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:34:18.834  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.834  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:18.834  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.834  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:18.834  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.834  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:18.834  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.834  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.834  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.836  3859  3910 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-13 16:34:18.836  3859  3910 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:34:18.836  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:34:18.836  3859  3910 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:34:18.836  3859  3910 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:34:18.836  3859  3910 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:34:18.836  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:34:18.836  3859  3910 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:34:18.836  3859  3910 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:34:18.837  3859  3910 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-13 16:34:18.837  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:34:18.837  3859  3910 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:34:18.837  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.837  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.837  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.837  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:18.837  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.837  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:18.837  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.837  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:18.837  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.838  3859  3910 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:34:18.840  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:18.846  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:18.850  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:18.850  3859  3910 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:34:18.850  3859  3910 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 16:34:18.850  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 16:34:18.850  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:18.850  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:18.850  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:18.850  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:18.853  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:34:18.853  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:18.853  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:18.853  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:18.853  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 16:34:18.853  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:18.853  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:18.854  3859  3937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:18.856  3859  3937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:34:18.858  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:18.859  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:18.859  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:34:18.861  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:18.862  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:18.866  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:18.867  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:18.867  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:18.872  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:34:18.872  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:34:18.872  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
,09-13 16:34:18.872  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:18.873  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:18.873  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:34:18.873  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:18.880  2637  2885 D BtGatt.GattService: registerClient() - UUID=e3d0df33-f426-407e-b11e-e4fdc3f90f30
,09-13 16:34:18.881  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=e3d0df33-f426-407e-b11e-e4fdc3f90f30, clientIf=5
,09-13 16:34:18.881  3859  3869 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:18.883  2637  2693 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:18.888  2637  2693 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:18.912  2637  2688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:34:18.925  2637  2688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:34:18.927  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:18.928  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:18.932  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:18.937  3859  3910 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:18.937  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:18.937  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:18.938  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:18.938  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:18.938  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:34:18.938  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:18.948  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:18.948  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:19.247   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:34:19.443  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.443  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:19.443  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:19.443  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:19.444  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 16:34:19.444  3859  3937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:19.445  3859  3937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:19.445  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:19.445  3859  3937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:19.446  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:19.446  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:19.446  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:19.447  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.447  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:19.448  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:19.448  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:19.448  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:19.449  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:34:19.451  3859  3910 D BluetoothAdapter: STATE_ON
09-13 16:34:19.451  3859  3910 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:19.452  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:19.452  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:19.455  2637  2693 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:19.456  2637  2693 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:34:19.477  2637  2688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 16:34:19.477  2637  2688 D BtGatt.GattService: Client app is not null!
,09-13 16:34:19.479  2637  2652 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:34:19.482  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:19.482  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:19.482  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:19.483  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:19.484  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:34:19.487  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.487  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:19.489  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:19.491  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:19.495  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:19.495  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:19.496  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:19.496  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:19.496  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:19.496  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.504  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.505  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.505  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.505  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:19.505  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:19.506  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
09-13 16:34:19.506  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.506  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.506  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.509  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:19.510  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:19.511  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:19.512  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:19.512  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:19.512  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:19.513  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:34:19.513  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:19.513  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:19.514  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:19.514  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:19.514  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:19.514  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.514  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:19.515  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:19.515  3859  3940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:19.515  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:19.515  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-13 16:34:19.515  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:19.515  3859  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:19.515  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:19.515  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:19.516  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:19.516  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.516  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.518  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:19.518  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:19.518  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:19.519  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:19.519  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.519  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:19.519  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.519  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:19.521  3859  3910 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 16:34:19.522  3859  3910 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 16:34:19.522  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:34:19.523  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:19.523  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:19.523  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.523  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.523  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.523  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:19.523  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.523  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:19.524  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:19.524  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.524  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.529  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.529  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:19.530  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:19.530  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
,09-13 16:34:19.530  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.530  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:19.531  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.531  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.531  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.535  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:19.535  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.535  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.536  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab427b3 not in the list
09-13 16:34:19.536  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:19.537  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3fa170 not in the list
,09-13 16:34:19.537  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:19.537  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:19.537  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:19.540  3859  3910 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:34:19.540  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:34:19.541  3859  3910 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-13 16:34:19.541  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:34:19.541  3859  3910 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:34:19.542  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:34:19.550  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 16:34:19.550  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 16:34:19.552  3859  3910 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 16:34:19.552  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:34:19.553  3859  3910 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 16:34:19.553  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 16:34:19.553  3859  3910 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:34:19.553  3859  3910 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-13 16:34:19.555  3859  3910 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-13 16:34:19.556  3859  3910 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 16:34:19.557  3859  3910 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-13 16:34:19.558  3859  3910 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:34:19.558  3859  3910 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 16:34:19.558  3859  3910 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 16:34:19.566  3859  3941 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 16:34:19.566  3859  3941 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:34:20.021  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:34:20.083  3859  3943 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 16:34:20.084  3859  3941 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:34:20.084  3859  3943 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:34:20.085  3859  3941 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:34:20.086  3859  3943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.086  3859  3941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.088  3859  3943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.089  3859  3941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:20.090  3859  3943 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:34:20.092  3859  3946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: IncomingSocketThread/Sender)
09-13 16:34:20.093  3859  3947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 493, name: OutgoingSocketThread/Sender)
09-13 16:34:20.094  3859  3941 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:34:20.098  3859  3949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 495, name: OutgoingSocketThread/Receiver)
09-13 16:34:20.099  3859  3948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 494, name: IncomingSocketThread/Receiver)
09-13 16:34:20.099  3859  3948 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 494, thread name: IncomingSocketThread/Receiver)
09-13 16:34:20.100  3859  3948 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:34:20.100  3859  3948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 494, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:34:20.100  3859  3949 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 495, thread name: OutgoingSocketThread/Receiver)
09-13 16:34:20.101  3859  3949 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:34:20.101  3859  3949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 495, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:34:20.588  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 16:34:20.590  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 16:34:20.597  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b4a666b Bundle[{}]
,09-13 16:34:20.598  3859  3910 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:34:20.598  3859  3910 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 16:34:20.598  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:34:20.599  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 16:34:20.599  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 16:34:20.600  3859  3910 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:34:20.610  3859  3950 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 16:34:20.611  3859  3950 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:34:21.120  3859  3952 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 16:34:21.121  3859  3952 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:34:21.121  3859  3952 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:34:21.122  3859  3950 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 16:34:21.122  3859  3950 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:34:21.123  3859  3950 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:34:21.123  3859  3952 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:21.124  3859  3950 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:21.124  3859  3952 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 16:34:21.129  3859  3954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 506, name: IncomingSocketThread/Sender)
,09-13 16:34:21.129  3859  3950 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:34:21.133  3859  3957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 509, name: OutgoingSocketThread/Receiver)
09-13 16:34:21.134  3859  3957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 509, thread name: OutgoingSocketThread/Receiver)
09-13 16:34:21.134  3859  3957 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:34:21.134  3859  3957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 509, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:34:21.135  3859  3955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 507, name: OutgoingSocketThread/Sender)
09-13 16:34:21.139  3859  3956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 508, name: IncomingSocketThread/Receiver)
09-13 16:34:21.140  3859  3956 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 508, thread name: IncomingSocketThread/Receiver)
09-13 16:34:21.140  3859  3956 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:34:21.140  3859  3956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 508, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:34:21.633  3859  3910 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 518)
,09-13 16:34:21.636  3859  3910 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 16:34:21.636  3859  3910 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 519)
,09-13 16:34:21.641  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:34:21.641  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3210259 added. We now have 3 listener(s)
,09-13 16:34:21.643  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:34:21.643  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:21.644  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:34:21.644  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:21.644  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9b4e1e added. We now have 3 listener(s)
09-13 16:34:21.644  3859  3910 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:21.645  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:21.651  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:21.659  3859  3910 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:21.663  3859  3910 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:21.664  3859  3910 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:21.670  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:21.673  3859  3859 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:21.676  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:21.676  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:21.677  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:21.677  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:34:21.678  3859  3910 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3210259 removed from the list
09-13 16:34:21.678  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:21.678  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9b4e1e removed from the list
09-13 16:34:21.681  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:21.681  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:21.685  3859  3910 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-13 16:34:21.685  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 16:34:21.686  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:21.687  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:21.687  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:21.687  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:21.688  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:21.690  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:21.691  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:21.691  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:21.691  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:21.692  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 16:34:21.693  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:21.693  3859  3958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:21.693  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:21.696  3859  3958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:34:21.702  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:34:21.702  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:21.707  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:21.708  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 16:34:21.708  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:21.711  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:34:21.711  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:34:21.711  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
,09-13 16:34:21.712  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:21.712  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:21.712  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:34:21.713  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:21.716  2637  2655 D BtGatt.GattService: registerClient() - UUID=829f7c70-2e56-409c-b215-f9857d2ae0a1
,09-13 16:34:21.717  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=829f7c70-2e56-409c-b215-f9857d2ae0a1, clientIf=5
09-13 16:34:21.717  3859  3869 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:21.719  2637  2693 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:21.722  2637  2693 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:21.733  2637  2688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:34:21.742  2637  2688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:34:21.742  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:21.742  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 16:34:21.744  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:21.746  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:21.747  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:34:21.747  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:21.747  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:21.747  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:21.748  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:21.752  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:21.752  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:22.253  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:22.254  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:22.254  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:23.965  2637  2841 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 16:34:23.966  2637  2860 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-13 16:34:25.250  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:34:25.251  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:34:25.251  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:25.251  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:25.252  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:25.253  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:25.253  3859  3958 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:25.253  3859  3958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:25.253  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:25.253  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:25.253  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:25.255  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:25.255  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:25.253  3859  3958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:25.255  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:25.256  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:25.258  3859  3910 D BluetoothAdapter: STATE_ON
09-13 16:34:25.258  3859  3910 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:25.259  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:25.259  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:25.261  2637  2693 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:25.263  2637  2693 D BtGatt.AdvertiseManager: stop advertise for client 5
09-13 16:34:25.274  2637  2688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 16:34:25.274  2637  2688 D BtGatt.GattService: Client app is not null!
09-13 16:34:25.277  2637  2886 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:34:25.278  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:25.278  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:25.278  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:25.279  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:25.279  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:25.280  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:25.281  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:25.281  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:25.281  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:25.282  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:25.283  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:34:25.283  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:25.283  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:25.283  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:25.283  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:25.285  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:25.285  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:25.285  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:25.285  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3210259 not in the list
09-13 16:34:25.285  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:25.285  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9b4e1e not in the list
09-13 16:34:25.285  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:25.285  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:25.285  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:25.286  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:34:25.287  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:25.287  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:34:25.287  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 16:34:25.287  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:25.287  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:25.291  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:34:25.291  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:25.296  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:25.297  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:34:25.297  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:25.299  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 16:34:25.304  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 16:34:25.304  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 16:34:25.304  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,09-13 16:34:25.305  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 16:34:25.306  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:25.309  2637  2885 D BtGatt.GattService: registerClient() - UUID=cedc57ff-15bc-4e0c-9851-b4442540c550
,09-13 16:34:25.312  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=cedc57ff-15bc-4e0c-9851-b4442540c550, clientIf=5
,09-13 16:34:25.312  3859  3905 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:25.314  2637  2655 D BtGatt.GattService: start scan with filters
,09-13 16:34:25.317  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 16:34:25.317  2637  2694 D BtGatt.ScanManager: handling starting scan
,09-13 16:34:25.318  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 16:34:25.318  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 16:34:25.318  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 16:34:25.319  2637  2694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@90ad44f
,09-13 16:34:25.321  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 16:34:25.321  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:34:25.321  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:25.323  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:25.326  2637  2688 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 16:34:25.326  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 16:34:25.326  2637  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 16:34:25.332  2637  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 16:34:25.332  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:25.332  2637  2694 D BtGatt.ScanManager: Starting BLE batch scan
09-13 16:34:25.332  2637  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 16:34:25.342  2637  2688 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 16:34:25.342  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:25.347  2637  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 16:34:25.348  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:25.822  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 16:34:25.823  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:25.823  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:26.690   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 16:34:26.704  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-13 16:34:26.720   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 16:34:26.720   873   893 I Adreno  : Build Date                       : 10/20/15
09-13 16:34:26.720   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 16:34:26.720   873   893 I Adreno  : Local Branch                     : M14
09-13 16:34:26.720   873   893 I Adreno  : Remote Branch                    : 
09-13 16:34:26.720   873   893 I Adreno  : Remote Branch                    : 
09-13 16:34:26.720   873   893 I Adreno  : Reconstruct Branch               : 
,09-13 16:34:26.759   281  2115 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (185 us)
,09-13 16:34:26.873  2637  2637 D BtGatt.ScanManager: awakened up at time 150421
09-13 16:34:26.875  2637  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 16:34:26.915  2637  2688 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-13 16:34:26.916  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:26.917  2637  2688 D BtGatt.GattService: current time is 150465226820
,09-13 16:34:26.918  2637  2688 D BtGatt.GattService: Batch record : [-31, -113, 113, -21, 16, 88, 1, -128, -54, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, -46, -4, -117, 6, 105, -37, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 87, 45, 110, 28, -13, -4, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -103, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 16:34:26.920  2637  2688 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
,09-13 16:34:26.921  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 16:34:26.922  2637  2688 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
,09-13 16:34:26.922  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 16:34:26.923  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 16:34:26.923  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 16:34:26.924  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 16:34:26.930  3859  3859 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 6], added - the peer count is 1
,09-13 16:34:26.931  3859  3859 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 5], added - the peer count is 2
,09-13 16:34:26.932  3859  3859 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 6], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
09-13 16:34:26.934  3859  3859 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 5], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-13 16:34:27.012  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:34:27.034  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:34:27.037  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:34:27.055  1513  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 16:34:27.056  1513  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 16:34:27.056  1513  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 16:34:27.056  1513  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:34:27.069  3593  3593 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 16:34:27.069  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 16:34:27.070  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 16:34:27.359  3859  3859 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:34:27.359  3859  3859 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 16:34:27.395  3859  3859 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b4a666b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@51d66f7, 16908290=android.view.AbsSavedState$1@51d66f7}, android:focusedViewId=100}]}]
,09-13 16:34:27.395  3859  3859 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 16:34:27.395  3859  3859 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 16:34:27.395  3859  3859 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 16:34:27.397   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 16:34:27.411   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 16:34:27.417   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 16:34:27.419   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
09-13 16:34:27.420   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 16:34:27.654   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 16:34:27.657   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 16:34:27.663   873  1339 D SurfaceControl: Excessive delay in setPowerMode(): 245ms
,09-13 16:34:27.667   873   893 I DreamManagerService: Entering dreamland.
,09-13 16:34:27.669   873   893 I PowerManagerService: Dozing...
09-13 16:34:27.670   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 16:34:27.765   377  1323 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 16:34:27.766   377  1323 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 16:34:27.774  2637  2637 D BtGatt.ScanManager: awakened up at time 151321
,09-13 16:34:27.776  2637  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 16:34:27.787   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:34:27.811  2042  3965 D NfcService: Discovery configuration equal, not updating.
,09-13 16:34:27.813   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:34:27.820   873  1315 E native  : do suspend false
,09-13 16:34:27.825  2637  2688 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-13 16:34:27.825  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:27.825  2637  2688 D BtGatt.GattService: current time is 151373023838,
09-13 16:34:27.825  2637  2688 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -67, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -88, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 16:34:27.826  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-13 16:34:27.827  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 16:34:27.827  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 16:34:27.827  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 16:34:27.839   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 16:34:27.851   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:34:27.854   873  1315 E native  : do suspend true
,09-13 16:34:27.891   377  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 16:34:27.892   377  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 16:34:28.302   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 16:34:28.326  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:28.326  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:28.327  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:28.327  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3210259 not in the list
,09-13 16:34:28.327  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:28.328  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:28.328  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:28.328  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:28.329  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:28.330  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 16:34:28.333  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.335  2637  2885 D BtGatt.GattService: stopScan() - queue size =1
,09-13 16:34:28.340  2637  2886 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 16:34:28.341  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:28.342  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:28.342  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 16:34:28.342  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 16:34:28.343  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 16:34:28.347  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:28.348  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:28.349  2637  2637 D BtGatt.ScanManager: awakened up at time 151896
09-13 16:34:28.349  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:28.349  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:34:28.355  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:28.356  3859  3910 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-13 16:34:28.357  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:28.358  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:28.358  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:28.358  2637  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 16:34:28.358  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:28.358  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9b4e1e not in the list
09-13 16:34:28.358  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:28.358  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:28.358  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:28.359  2637  2694 D BtGatt.ScanManager: stopping BLe Batch
09-13 16:34:28.360  3859  3910 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-13 16:34:28.360  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-13 16:34:28.363  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:28.363  3859  3910 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:28.363  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:28.363  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:28.365  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:28.366  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:28.366  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:28.366  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:28.366  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:28.366  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:28.366  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:28.366  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:28.372  3859  3969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:28.373  3859  3910 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:34:28.373  3859  3910 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:28.376  3859  3969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:28.381  2637  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 16:34:28.381  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:28.381  2637  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 16:34:28.382  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:28.383  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 16:34:28.383  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:28.387  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:28.388  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:34:28.388  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-13 16:34:28.388  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:28.389  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:28.389  3859  3910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:28.390  3859  3910 D BluetoothAdapter: STATE_ON
,09-13 16:34:28.395  2637  2652 D BtGatt.GattService: registerClient() - UUID=98c7c523-1f5e-44ae-aee8-515e930ce748
,09-13 16:34:28.396  2637  2688 D BtGatt.GattService: onClientRegistered() - UUID=98c7c523-1f5e-44ae-aee8-515e930ce748, clientIf=5
,09-13 16:34:28.396  3859  3869 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:34:28.399  2637  2693 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:28.403  2637  2688 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-13 16:34:28.403  2637  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:34:28.403  2637  2688 D BtGatt.GattService: current time is 151951237906
09-13 16:34:28.403  2637  2688 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -90, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
09-13 16:34:28.404  2637  2693 D BtGatt.AdvertiseManager: starting multi advertising
09-13 16:34:28.404  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 16:34:28.404  2637  2688 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-13 16:34:28.428  2637  2688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:34:28.446  2637  2688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:34:28.447  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:28.447  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:28.452  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:28.457  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:28.457  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:28.458  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:28.458  3859  3859 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:28.459  3859  3859 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:34:28.460  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:28.472  3859  3859 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:28.473  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:28.973  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:28.974  3859  3859 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:28.974  3859  3859 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:31.963  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:31.964  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:31.964  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:31.964  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:31.965  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:31.965  3859  3910 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:31.966  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3210259 not in the list
,09-13 16:34:31.966  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:31.967  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:31.967  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:34:31.967  3859  3859 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:31.967  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:31.968  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:31.968  3859  3969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:31.970  3859  3969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:31.970  3859  3910 D BluetoothAdapter: STATE_ON
09-13 16:34:31.971  3859  3910 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:31.971  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:31.971  3859  3969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:31.972  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:31.975  2637  2693 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:31.977  2637  2693 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:34:31.988  2637  2688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:34:31.988  2637  2688 D BtGatt.GattService: Client app is not null!
,09-13 16:34:31.989  2637  2652 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:34:31.989  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:31.989  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:31.989  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:31.990  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:31.990  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:31.991  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:31.992  3859  3910 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:31.992  3859  3910 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:31.993  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:31.998  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:31.998  3859  3859 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:31.998  3859  3859 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:31.998  3859  3859 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:31.999  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9b4e1e not in the list
09-13 16:34:32.000  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:32.000  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:32.000  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:32.002  3859  3910 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:32.002  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:32.003  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:32.003  3859  3910 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3210259 not in the list
09-13 16:34:32.003  3859  3910 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:32.003  3859  3910 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9b4e1e not in the list
09-13 16:34:32.003  3859  3910 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:32.004  3859  3910 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:32.004  3859  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:32.006  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:32.006  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:32.007  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:32.007  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:32.007  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 16:34:32.008  3859  3910 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:32.023  3859  3972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 539, name: My test thread name)
,09-13 16:34:32.114  1859  2575 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 16:34:32.500  3859  3859 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:34:32.877   873  1880 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 16:34:34.022  3859  3910 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 539
,09-13 16:34:34.023  3859  3910 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 539, name: My test thread name)
,09-13 16:34:34.029  3859  3973 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 540, name: My test thread name)
09-13 16:34:34.030  3859  3973 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 540, thread name: My test thread name)
09-13 16:34:34.030  3859  3973 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 540, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 16:34:34.034  3859  3910 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:34.043  3859  3974 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 544, name: My test thread name)
,09-13 16:34:34.044  3859  3974 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 544, thread name: My test thread name): Test exception.
,09-13 16:34:34.046  3859  3974 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 544, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 16:34:34.055  3859  3910 I jxcore-log: Total number of executed tests:  76
09-13 16:34:34.055  3859  3910 I jxcore-log: 
,09-13 16:34:34.057  3859  3910 I jxcore-log: Number of passed tests:  76
09-13 16:34:34.057  3859  3910 I jxcore-log: 
09-13 16:34:34.057  3859  3910 I jxcore-log: Number of failed tests:  0
09-13 16:34:34.057  3859  3910 I jxcore-log: 
,09-13 16:34:34.060  3859  3910 I jxcore-log: Number of ignored tests:  0
09-13 16:34:34.060  3859  3910 I jxcore-log: 
,09-13 16:34:34.060  3859  3910 I jxcore-log: Total duration:  17418
09-13 16:34:34.060  3859  3910 I jxcore-log: 
,09-13 16:34:34.066  3859  3910 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:34:34.066  3859  3910 I jxcore-log: 
,09-13 16:34:34.069  3859  3910 I jxcore-log: My device name is: motorola-Nexus 6
09-13 16:34:34.069  3859  3910 I jxcore-log: 
,09-13 16:34:34.079  3859  3910 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 16:34:34.079  3859  3910 I jxcore-log: 
,09-13 16:34:34.083  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.083  3859  3910 I jxcore-log: 
09-13 16:34:34.084  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.084  3859  3910 I jxcore-log: 
,09-13 16:34:34.085  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.085  3859  3910 I jxcore-log: 
,09-13 16:34:34.087  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.087  3859  3910 I jxcore-log: 
,09-13 16:34:34.091  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.091  3859  3910 I jxcore-log: 
,09-13 16:34:34.093  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.093  3859  3910 I jxcore-log: 
,09-13 16:34:34.093  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.093  3859  3910 I jxcore-log: 
,09-13 16:34:34.094  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.094  3859  3910 I jxcore-log: 
,09-13 16:34:34.095  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.095  3859  3910 I jxcore-log: 
,09-13 16:34:34.096  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:34.096  3859  3910 I jxcore-log: 
,09-13 16:34:34.097  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:34.097  3859  3910 I jxcore-log: 
09-13 16:34:34.097  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.097  3859  3910 I jxcore-log: 
09-13 16:34:34.098  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 16:34:34.098  3859  3910 I jxcore-log: 
,09-13 16:34:34.099  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 16:34:34.099  3859  3910 I jxcore-log: 
09-13 16:34:34.100  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 16:34:34.100  3859  3910 I jxcore-log: 
,09-13 16:34:34.101  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:34.101  3859  3910 I jxcore-log: 
,09-13 16:34:34.102  3859  3910 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:34.102  3859  3910 I jxcore-log: 
,09-13 16:34:34.106  3859  3972 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 539, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-13 16:34:34.755  3975  3975 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 16:34:34.761  3975  3975 D AndroidRuntime: CheckJNI is OFF
,09-13 16:34:34.804  3975  3975 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 16:34:34.849  3975  3975 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 16:34:34.872  3975  3975 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:34:34.881   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 16:34:34.882   873   886 I ActivityManager: Killing 3859:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 16:34:35.001   873   896 W PackageSettings: Skipping PackageSetting{ae19800 com.example.hello/10273} due to missing metadata
,09-13 16:34:35.014   873  1402 D GraphicsStats: Buffer count: 2
,09-13 16:34:35.014   873  1402 I WindowState: WIN DEATH: Window{ebedd75 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 16:34:35.017   873  1316 D WifiService: Client connection lost with reason: 4
,09-13 16:34:35.059   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-13 16:34:35.060   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 16:34:35.062   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-13 16:34:35.062   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 16:34:35.062   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.062   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.062   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:35.062   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 16:34:35.063   873   896 I art     : Starting a blocking GC Explicit
09-13 16:34:35.063   873   886 I ActivityManager:   Force finishing activity ActivityRecord{def7e52 u0 com.test.thalitest/.MainActivity t4}
,09-13 16:34:35.078   873  2011 W ActivityManager: Spurious death for ProcessRecord{f93cce7 0:com.test.thalitest/u0a0}, curProc for 3859: null
,09-13 16:34:35.122   873   896 I art     : Explicit concurrent mark sweep GC freed 20191(1288KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 820us total 59.045ms
,09-13 16:34:35.153   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 16:34:35.157  3975  3975 I art     : System.exit called, status: 0
,09-13 16:34:35.157  3975  3975 I AndroidRuntime: VM exiting with result code 0.
,09-13 16:34:35.169   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 16:34:35.195   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 16:34:35.204   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:34:35.215  1859  2226 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 16:34:35.216  1904  1904 I Keyboard.Facilitator: resetDictionaries() : en_US
09-13 16:34:35.232  2637  2637 D BluetoothMapAppObserver: onReceive
,09-13 16:34:35.232  2637  2637 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-13 16:34:35.234  2054  2054 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 16:34:35.242  3713  3713 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 16:34:35.245  1904  3988 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 16:34:35.247  1904  3988 I Decoder : createOrResetDecoder
,09-13 16:34:35.291  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-13 16:34:35.292  1513  1513 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
09-13 16:34:35.293  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:34:35.293  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
09-13 16:34:35.293  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 16:34:35.293  1513  1513 E AndroidRuntime: 	... 8 more
,09-13 16:34:35.299  1513  1513 I Process : Sending signal. PID: 1513 SIG: 9
09-13 16:34:35.300   873  3992 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.300   873  3992 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.300   873  3992 E DropBoxManagerService: 	... 5 more
09-13 16:34:35.302  1695  1735 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
09-13 16:34:35.303  1695  1735 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjA3C175939) - 
09-13 16:34:35.308  1695  3990 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 16:34:35.312  1695  1735 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-13 16:34:35.312  1695  1735 E AndroidRuntime: Process: android.process.acore, PID: 1695
09-13 16:34:35.312  1695  1735 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.312  1695  1735 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:35.316   873  1690 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1752)
09-13 16:34:35.316   873  1690 W ActivityManager: Application dead when creating service ServiceRecord{7e24d66 u0 com.google.android.gms/.config.ConfigService}
09-13 16:34:35.318   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:34:35.327   873  1316 D WifiService: Client connection lost with reason: 4
,09-13 16:34:35.333   873  1690 I ActivityManager: Process com.google.process.gapps (pid 1513) has died
09-13 16:34:35.333   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
09-13 16:34:35.333   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-13 16:34:35.334   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-13 16:34:35.334   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
09-13 16:34:35.334   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 41000ms
09-13 16:34:35.335   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 124000ms
09-13 16:34:35.335   873  1690 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
09-13 16:34:35.335   873  1690 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-13 16:34:35.335   873  1690 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:15988)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-13 16:34:35.335   873  1690 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.342   873  3993 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.342   873  3993 E DropBoxManagerService: 	... 5 more
09-13 16:34:35.343  1711  1711 W RocketImpressions: ClearcutLogger connection suspended: 1
09-13 16:34:35.345  1695  3990 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-13 16:34:35.345  1695  3990 I Process : Sending signal. PID: 1695 SIG: 9
09-13 16:34:35.347   873  1402 I ActivityManager: Start proc 3994:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
09-13 16:34:35.347   279   279 E lowmemorykiller: Error writing /proc/1695/oom_score_adj; errno=22
09-13 16:34:35.348   873  2068 W ActivityManager: Spurious death for ProcessRecord{1fbe54d 0:com.google.process.gapps/u0a11}, curProc for 1513: null
09-13 16:34:35.359  2069  2145 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-13 16:34:35.360   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 16:34:35.362   873   885 E PackageManager: Failed to write settings, restoring backup
09-13 16:34:35.362   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 16:34:35.362   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 16:34:35.362   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 16:34:35.362   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 16:34:35.362   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 16:34:35.362   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.362   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.362   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:35.364   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-13 16:34:35.364   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 16:34:35.364   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.364   873   886 E DropBoxManagerService: 	... 13 more
,09-13 16:34:35.371   873  2068 I ActivityManager: Start proc 4008:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-13 16:34:35.372  2069  2145 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 16:34:35.372  2069  2145 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2069
09-13 16:34:35.372  2069  2145 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.372  2069  2145 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:35.380   873  2009 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 16:34:35.381   873  4019 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.381   873  4019 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.381   873  4019 E DropBoxManagerService: 	... 5 more
09-13 16:34:35.385  2069  2145 I Process : Sending signal. PID: 2069 SIG: 9
09-13 16:34:35.388  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-13 16:34:35.388  1711  1711 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-13 16:34:35.397  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-13 16:34:35.404  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 16:34:35.404  1711  1711 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 16:34:35.407  3994  3994 I MultiDex: VM with version 2.1.0 has multidex support
09-13 16:34:35.407  3994  3994 I MultiDex: install
09-13 16:34:35.407  3994  3994 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 16:34:35.411  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-13 16:34:35.415  3994  3994 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-13 16:34:35.416   279   279 E lowmemorykiller: Error writing /proc/2069/oom_score_adj; errno=22
09-13 16:34:35.416   279   279 E lowmemorykiller: Error writing /proc/1695/oom_score_adj; errno=22
09-13 16:34:35.416   873  1402 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,09-13 16:34:35.416   873  1402 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-13 16:34:35.416   873  1402 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-13 16:34:35.416   873  1402 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:34:35.417  3994  3994 E SQL,iteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:34:35.417  3994  3994 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:34:35.417  3994  3994 D AndroidRuntime: Shutting down VM
09-13 16:34:35.417  1711  4022 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 16:34:35.418  3994  3994 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:34:35.418  3994  3994 E AndroidRuntime: Process: com.google.process.gapps, PID: 3994
09-13 16:34:35.418  3994  3994 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:,806)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:34:35.418  3994  3994 E AndroidRuntime: 	... 10 more
09-13 16:34:35.427  1711  4022 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-13 16:34:35.427  1711  4022 E AndroidRuntime: Process: com.google.android.gms, PID: 1711
09-13 16:34:35.427  1711  4022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:34:35.427  1711  4022 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,09-13 16:34:35.476   873  1690 I WindowState: WIN DEATH: Window{7a04340 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-13 16:34:35.476   873  1990 D GraphicsStats: Buffer count: 1
09-13 16:34:35.484   873  1402 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 16:34:35.496   873  1402 I ActivityManager: Start proc 4025:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,09-13 16:34:35.496   279   279 E lowmemorykiller: Error opening /proc/1695/oom_score_adj; errno=2
,09-13 16:34:35.497   873  2007 W ActivityManager: Spurious death for ProcessRecord{1e9bcc2 4025:com.google.android.googlequicksearchbox/u0a28}, curProc for 2069: null
09-13 16:34:35.498  3994  3994 I Process : Sending signal. PID: 3994 SIG: 9
09-13 16:34:35.499  2122  4021 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 16:34:35.500   873  3804 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
09-13 16:34:35.501   873  3804 I ActivityManager: Killing 1711:com.google.android.gms/u0a11 (adj 5): crash
09-13 16:34:35.502   873  4031 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.502   873  4031 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.502   873  4031 E DropBoxManagerService: 	... 5 more
09-13 16:34:35.503   873  4032 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.503   873  4032 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.503   873  4032 E DropBoxManagerService: 	... 5 more
,09-13 16:34:35.533  2122  4021 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 16:34:35.561   873   884 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f8b1687)
,09-13 16:34:35.562   873  1317 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:34:35.562   873  1317 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:34:35.566   873  3804 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 16:34:35.580   873   883 I ActivityManager: Start proc 4041:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,09-13 16:34:35.590   873  2007 I ActivityManager: Process com.google.process.gapps (pid 3994) has died
09-13 16:34:35.590   873  2007 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{dd6b2e7 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
09-13 16:34:35.591   873  2007 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{c37bae6 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
09-13 16:34:35.591   873  2007 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{80aef87 u0 com.google.android.gms/.gcm.GcmService},
09-13 16:34:35.591   873  2007 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 496000ms
09-13 16:34:35.591   873  2007 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{315a67c u0 com.google.android.gms/.gcm.http.GoogleHttpService}
09-13 16:34:35.593   873  1990 W ActivityManager: Spurious death for ProcessRecord{5fac1a2 0:com.google.android.gms/u0a11}, curProc for 1711: null
,09-13 16:34:35.594   873  2011 I ActivityManager: Process android.process.acore (pid 1695) has died
09-13 16:34:35.594   873  2011 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-13 16:34:35.596  2122  4021 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
09-13 16:34:35.597  2122  4021 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
09-13 16:34:35.597  2122  4021 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2122
,09-13 16:34:35.597  2122  4021 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.597  2122  4021 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:34:35.599  2122  4021 I Process : Sending signal. PID: 2122 SIG: 9
09-13 16:34:35.602   873  4054 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.602   873  4054 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.602   873  4054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.602   873  4054 E Dro,pBoxManagerService: 	... 5 more
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:34:35.617  4025  4025 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:34:35.617  4025  4025 D AndroidRuntime: Shutting down VM
,09-13 16:34:35.623  4025  4025 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:34:35.623  4025  4025 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4025
09-13 16:34:35.623  4025  4025 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:34:35.623  4025  4025 E AndroidRuntime: 	... 10 more
09-13 16:34:35.625   873  1690 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
09-13 16:34:35.625   873  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 16:34:35.625   873  4055 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:34:35.625   873  4055 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:34:35.625   873  4055 E DropBoxManagerService: 	... 5 more
,09-13 16:34:35.627   873  1690 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 16:34:35.630   873  1690 I ActivityManager: Killing 4025:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,09-13 16:34:35.649  4041  4041 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-13 16:34:35.657  4041  4041 I MultiDex: VM with version 2.1.0 has multidex support
,09-13 16:34:35.657  4041  4041 I MultiDex: install
09-13 16:34:35.657  4041  4041 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 16:34:35.666   873  1316 D WifiService: Client connection lost with reason: 4
,09-13 16:34:35.678   873  1690 I ActivityManager: Start proc 4056:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 16:34:35.679   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
