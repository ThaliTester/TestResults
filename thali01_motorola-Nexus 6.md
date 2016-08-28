#### Test 82883341c6b3d90_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-28 10:31:58.247  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-28 10:31:58.260  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-28 10:31:58.264  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-28 10:31:58.317  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-28 10:31:58.317  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 10:31:58.318  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:31:58.318  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-28 10:31:58.363  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-28 10:31:58.363  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-28 10:31:58.364  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-28 10:31:58.906  3758  3758 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-28 10:31:58.910  3758  3758 D AndroidRuntime: CheckJNI is OFF
08-28 10:31:58.953  3758  3758 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-28 10:31:59.001  3758  3758 I Radio-JNI: register_android_hardware_Radio DONE
08-28 10:31:59.024  3758  3758 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-28 10:31:59.028   872  1961 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-28 10:31:59.070  2005  2015 W SearchService: Abort, client detached.
08-28 10:31:59.078  2005  2005 I HotwordDetector: Closing mic
08-28 10:31:59.079  2005  2306 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@adaed7f
08-28 10:31:59.079  2005  2314 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-28 10:31:59.081  3758  3758 D AndroidRuntime: Shutting down VM
08-28 10:31:59.114   872  1907 I ActivityManager: Start proc 3768:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-28 10:31:59.144   376  2316 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-28 10:31:59.146   376  2316 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-28 10:31:59.150   376  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-28 10:31:59.153  2005  2313 I MicroRecognitionRnrImpl: Detection finished
08-28 10:31:59.154  2005  2309 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-28 10:31:59.202  3768  3768 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-28 10:31:59.229  3768  3768 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-28 10:31:59.236  3768  3768 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4375-4378)
08-28 10:31:59.236  3768  3768 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-28 10:31:59.264  3768  3768 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24b1af0}
08-28 10:31:59.264  3768  3768 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-28 10:31:59.265  3768  3768 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-28 10:31:59.273  3768  3768 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-28 10:31:59.275  3768  3768 E SysUtils: ApplicationContext is null in ApplicationStatus
08-28 10:31:59.301  3768  3768 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-28 10:31:59.316  3768  3768 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-28 10:31:59.316  3768  3768 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-28 10:31:59.316  3768  3768 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-28 10:31:59.316  3768  3768 I Adreno  : Build Date                       : 10/20/15
08-28 10:31:59.316  3768  3768 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-28 10:31:59.316  3768  3768 I Adreno  : Local Branch                     : M14
08-28 10:31:59.316  3768  3768 I Adreno  : Remote Branch                    : 
08-28 10:31:59.316  3768  3768 I Adreno  : Remote Branch                    : 
08-28 10:31:59.316  3768  3768 I Adreno  : Reconstruct Branch               : 
,08-28 10:31:59.406   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@66def78:true
,08-28 10:31:59.481  3768  3768 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-28 10:31:59.501  3768  3768 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-28 10:31:59.589  3768  3806 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-28 10:31:59.599  3768  3793 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-28 10:31:59.646  3768  3806 I OpenGLRenderer: Initialized EGL, version 1.4
,08-28 10:31:59.746   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +655ms
,08-28 10:31:59.749  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-28 10:31:59.839  3768  3768 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3768
,08-28 10:31:59.958   872  1694 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-28 10:31:59.993  3768  3768 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-28 10:32:00.008   872  1694 I ActivityManager: Killing 3103:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-28 10:32:00.144  3768  3808 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1679099600
,08-28 10:32:00.151  3768  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-28 10:32:00.151  3768  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-28 10:32:00.151  3768  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-28 10:32:00.151  3768  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-28 10:32:00.151  3768  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-28 10:32:00.151  3768  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd95147 added. We now have 1 listener(s)
,08-28 10:32:00.156  3768  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-28 10:32:00.156  3768  3808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 10:32:00.157  3768  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-28 10:32:00.157  3768  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-28 10:32:00.160  3768  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@905c312 added. We now have 1 listener(s)
08-28 10:32:00.161  3768  3808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:32:00.164   872  1302 D WifiService: New client listening to asynchronous messages
,08-28 10:32:00.165  3768  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-28 10:32:00.165  3768  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-28 10:32:00.165  3768  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-28 10:32:00.165  3768  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-28 10:32:00.165  3768  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-28 10:32:00.170  3768  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 10:32:00.170  3768  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-28 10:32:00.175  3768  3808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:00.176  3768  3808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:00.176  3768  3808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-28 10:32:00.176  3768  3808 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 10:32:00.176  3768  3808 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-28 10:32:00.178  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:00.179  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:00.205  3768  3768 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-28 10:32:01.111  3768  3816 W jxcore-log: Initializing JXcore engine
,08-28 10:32:01.111  3768  3816 W jxcore-log: JXcore engine is ready
,08-28 10:32:01.158  3816  3816 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8955 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-28 10:32:01.158  3816  3816 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10076]" dev="sockfs" ino=10076 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-28 10:32:01.158  3816  3816 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-28 10:32:01.158  3816  3816 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25979]" dev="sockfs" ino=25979 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,08-28 10:32:01.172  3768  3816 W jxcore-log: Starting JXcore engine
,08-28 10:32:01.255  3768  3816 W jxcore-log: Platform android
08-28 10:32:01.255  3768  3816 W jxcore-log: 
,08-28 10:32:01.255  3768  3816 W jxcore-log: Process ARCH arm
08-28 10:32:01.255  3768  3816 W jxcore-log: 
,08-28 10:32:01.457  3768  3816 I jxcore-log: JXcore Cordova bridge is ready!
08-28 10:32:01.457  3768  3816 I jxcore-log: 
08-28 10:32:01.457  3768  3816 W jxcore-log: JXcore engine is started
,08-28 10:32:01.463  3768  3808 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-28 10:32:01.468  3768  3768 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-28 10:32:09.459   872  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-28 10:32:11.387  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:11.392  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:11.410  3768  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-28 10:32:11.410  3768  3816 I jxcore-log: 
,08-28 10:32:11.413  3768  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-28 10:32:11.413  3768  3816 I jxcore-log: 
,08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:11.432  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:11.438  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:11.443  3768  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-28 10:32:11.443  3768  3816 I jxcore-log: 
,08-28 10:32:11.448  3768  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-28 10:32:11.448  3768  3816 I jxcore-log: 
,08-28 10:32:11.448  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-28 10:32:11.448  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:32:11.449  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:32:11.449  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:11.482  3003  3830 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-28 10:32:11.482  3003  3830 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at blb.a(PG:3937)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at czp.a(PG:18188)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:32:11.482  3003  3830 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	... 12 more
08-28 10:32:11.482  3003  3830 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at fal.a(PG:38)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:32:11.482  3003  3830 E HttpOperation: 	... 14 more
,08-28 10:32:11.548  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:32:11.548  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:32:11.548  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:32:11.548  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:11.563  3003  3830 E HttpOperation: [getmobileexperiments] Unexpected exception
08-28 10:32:11.563  3003  3830 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at hec.a(PG:42)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at hee.a(PG:102)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at czr.a(PG:65)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at kka.a(PG:108)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at czp.a(PG:19176)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:32:11.563  3003  3830 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	... 15 more
08-28 10:32:11.563  3003  3830 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at fal.a(PG:38)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:32:11.563  3003  3830 E HttpOperation: 	... 17 more
08-28 10:32:11.564  3003  3830 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-28 10:32:11.564  3003  3830 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jdm.a(PG:82)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jcs.o(PG:406)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jcn.a(PG:1379)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jcs.i(PG:143)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at hec.a(PG:42)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at hee.a(PG:102)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at czr.a(PG:65)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at kka.a(PG:108)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at czp.a(PG:19176)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at czp.a(PG:9081)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at czq.run(PG:1686)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
,08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jdj.a(PG:4091)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jdj.a(PG:1125)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jdm.a(PG:77)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	... 15 more
08-28 10:32:11.564  3003  3830 E ExperimentLoader: Caused by: faj: BadAuthentication
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at fal.a(PG:38)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	at jdj.a(PG:4089)
08-28 10:32:11.564  3003  3830 E ExperimentLoader: 	... 17 more
,08-28 10:32:11.662   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 125684, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:32:11.971  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 10:32:11.972  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0fc5bd added. We now have 2 listener(s)
,08-28 10:32:11.973  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 10:32:11.973  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 10:32:11.973  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-28 10:32:11.973  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:32:11.973  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@124f7b2 added. We now have 2 listener(s)
,08-28 10:32:11.973  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:32:11.974  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-28 10:32:11.976  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:11.983  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:11.984  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:11.984  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 10:32:11.985  3768  3816 D ExecuteNativeTests: Running unit tests
,08-28 10:32:11.995  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:12.002  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:12.049  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-28 10:32:12.049  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 added. We now have 3 listener(s)
,08-28 10:32:12.050  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 10:32:12.050  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-28 10:32:12.050  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 10:32:12.050  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:32:12.050  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 added. We now have 3 listener(s)
,08-28 10:32:12.050  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:32:12.051  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 10:32:12.057  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:12.070  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:12.080  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:12.080  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 10:32:12.082  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:12.085  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:12.090  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-28 10:32:12.091  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 10:32:12.091  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-28 10:32:12.091  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-28 10:32:12.095  3768  3816 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-28 10:32:12.095  3768  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-28 10:32:12.095  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-28 10:32:12.096  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:12.096  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:12.096  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:12.096  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:12.096  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:12.097  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:12.097  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:12.097  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.097  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:32:12.097  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 10:32:12.097  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 removed from the list
08-28 10:32:12.097  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:12.097  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 removed from the list
08-28 10:32:12.097  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 10:32:12.098  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:12.098  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.098  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:12.101  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:12.101  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:32:12.101  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:12.101  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:12.103  3768  3816 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-28 10:32:12.103  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-28 10:32:12.103  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:12.104  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:12.104  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:12.104  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.104  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:12.104  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:12.104  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:12.104  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:12.104  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:12.104  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.104  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:12.105  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.105  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:12.105  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:12.105  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:32:12.105  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:12.106  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-28 10:32:12.110  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-28 10:32:12.111  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-28 10:32:12.111  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:12.111  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:32:12.111  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:12.111  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:12.111  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.112  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:12.112  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:12.112  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:12.112  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:12.112  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 10:32:12.112  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.112  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:12.112  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:12.112  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:12.113  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:12.113  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:12.113  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:12.113  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:12.114  3768  3816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-28 10:32:12.115  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:12.118  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:12.119  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:12.120  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 10:32:12.121  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 10:32:12.121  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-28 10:32:12.121  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-28 10:32:12.121  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 10:32:12.121  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-28 10:32:12.121  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:12.124  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:12.125  3768  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-28 10:32:12.125  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 10:32:12.130  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 10:32:12.132  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 10:32:12.133  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 10:32:12.136  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-28 10:32:12.140  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-28 10:32:12.140  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-28 10:32:12.140  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-28 10:32:12.141  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-28 10:32:12.142  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:32:12.145  2691  2703 D BtGatt.GattService: registerClient() - UUID=c7ce4ed3-7b7b-472a-9ecb-b0fd4ad8a711
,08-28 10:32:12.146  2691  2729 D BtGatt.GattService: onClientRegistered() - UUID=c7ce4ed3-7b7b-472a-9ecb-b0fd4ad8a711, clientIf=5
08-28 10:32:12.146  3768  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-28 10:32:12.147  2691  2702 D BtGatt.GattService: start scan with filters
,08-28 10:32:12.149  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-28 10:32:12.150  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-28 10:32:12.150  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-28 10:32:12.150  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-28 10:32:12.150  2691  2750 D BtGatt.ScanManager: handling starting scan
,08-28 10:32:12.152  2691  2750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:32:12.152  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-28 10:32:12.153  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-28 10:32:12.154  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-28 10:32:12.155  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-28 10:32:12.157  3768  3816 I io.jxcore.node.ConnectionHelper: start: OK
,08-28 10:32:12.162  2691  2729 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-28 10:32:12.163  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:12.164   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-28 10:32:12.165  2691  2750 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-28 10:32:12.170  2691  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-28 10:32:12.170  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:12.170  2691  2750 D BtGatt.ScanManager: Starting BLE batch scan
08-28 10:32:12.170  2691  2750 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-28 10:32:12.181  2691  2729 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-28 10:32:12.181  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:12.187  2691  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-28 10:32:12.187  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:12.655  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-28 10:32:12.655  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-28 10:32:12.656  3768  3768 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 10:32:13.695  2691  2691 D BtGatt.ScanManager: awakened up at time 128837
08-28 10:32:13.697  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:13.767  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-28 10:32:13.768  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:13.769  2691  2729 D BtGatt.GattService: current time is 128911972277
,08-28 10:32:13.774  2691  2729 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -64, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -69, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 53, 33, -121, 80, 73, -44, 1, 0, -108, 16, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -84, -4, -21, 2, 2, -29, 21, 63, -18, 79, -22, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 116, -43, -111, -91, -20, -29, 1, -128, -90, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -88, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 10:32:13.780  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-28 10:32:13.785  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 10:32:13.785  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:13.785  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -84, -4, -21, 2, 2, -29, 21, 63, -18, 79, -22, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-28 10:32:13.786  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-28 10:32:13.786  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-28 10:32:13.786  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 10:32:15.269  2691  2691 D BtGatt.ScanManager: awakened up at time 130411
,08-28 10:32:15.272  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:15.318  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-28 10:32:15.318  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:15.319  2691  2729 D BtGatt.GattService: current time is 130461474828
08-28 10:32:15.319  2691  2729 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -94, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-28 10:32:15.319  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-28 10:32:15.319  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-28 10:32:15.320  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 10:32:15.320  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-28 10:32:15.320  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:16.824  2691  2691 D BtGatt.ScanManager: awakened up at time 131966
,08-28 10:32:16.826  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:16.876  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-28 10:32:16.877  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:16.877  2691  2729 D BtGatt.GattService: current time is 132020161804
,08-28 10:32:16.878  2691  2729 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -94, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -68, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:16.879  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-28 10:32:16.880  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-28 10:32:16.881  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-28 10:32:16.882  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:17.166  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:32:17.167  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:32:17.167  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-28 10:32:17.168  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:17.168  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-28 10:32:17.169  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 10:32:17.169  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 10:32:17.169  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 10:32:17.170  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 10:32:17.172  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 10:32:17.172  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-28 10:32:17.175  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:32:17.177  2691  2703 D BtGatt.GattService: stopScan() - queue size =1
,08-28 10:32:17.179  2691  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-28 10:32:17.181  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-28 10:32:17.184  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-28 10:32:17.185  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-28 10:32:17.185  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-28 10:32:17.185  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-28 10:32:17.189  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 10:32:17.190  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 10:32:17.191  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 10:32:17.192  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-28 10:32:17.194  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 10:32:17.198  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 10:32:17.198  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 10:32:17.199  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:32:17.199  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 10:32:17.199  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:17.199  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:32:17.199  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:17.199  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:17.200  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:17.200  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:17.200  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:17.204  2691  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-28 10:32:17.204  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:17.205  2691  2750 D BtGatt.ScanManager: stopping BLe Batch
,08-28 10:32:17.221  2691  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-28 10:32:17.221  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:17.222  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:17.236  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-28 10:32:17.236  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:17.700  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 10:32:18.218   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-28 10:32:18.782  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:18.792  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:18.798  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:18.857  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:32:18.857  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-28 10:32:18.858  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:32:18.858  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:18.909  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:32:18.910  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-28 10:32:18.911  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-28 10:32:22.202  3768  3816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-28 10:32:22.208  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:22.223  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:22.230  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:22.231  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 10:32:22.232  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-28 10:32:22.232  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-28 10:32:22.232  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-28 10:32:22.233  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 10:32:22.233  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-28 10:32:22.239  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:22.243  3768  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-28 10:32:22.243  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 10:32:22.246  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:22.253  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 10:32:22.254  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 10:32:22.254  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 10:32:22.261  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-28 10:32:22.261  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-28 10:32:22.261  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-28 10:32:22.262  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:32:22.265  2691  2835 D BtGatt.GattService: registerClient() - UUID=44554571-5de7-488e-b52b-3f200e0c12ef
,08-28 10:32:22.266  2691  2729 D BtGatt.GattService: onClientRegistered() - UUID=44554571-5de7-488e-b52b-3f200e0c12ef, clientIf=5
08-28 10:32:22.266  3768  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-28 10:32:22.266  2691  2845 D BtGatt.GattService: start scan with filters
,08-28 10:32:22.274  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-28 10:32:22.274  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 10:32:22.274  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-28 10:32:22.274  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-28 10:32:22.274  2691  2750 D BtGatt.ScanManager: handling starting scan
,08-28 10:32:22.277  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 10:32:22.277  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 10:32:22.278  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-28 10:32:22.279  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 10:32:22.282  3768  3816 I io.jxcore.node.ConnectionHelper: start: OK
,08-28 10:32:22.286  2691  2729 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-28 10:32:22.286  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:22.287  2691  2750 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-28 10:32:22.291  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:32:22.291  3768  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-28 10:32:22.291  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:22.292  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-28 10:32:22.292  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:22.293  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-28 10:32:22.293  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-28 10:32:22.293  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 10:32:22.294  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 10:32:22.295  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 10:32:22.296  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 10:32:22.296  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-28 10:32:22.301  3768  3816 D BluetoothAdapter: STATE_ON
08-28 10:32:22.303  2691  2835 D BtGatt.GattService: stopScan() - queue size =1
,08-28 10:32:22.304  2691  2703 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-28 10:32:22.304  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-28 10:32:22.305  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-28 10:32:22.305  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-28 10:32:22.305  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-28 10:32:22.305  2691  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-28 10:32:22.305  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.305  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-28 10:32:22.305  2691  2750 D BtGatt.ScanManager: Starting BLE batch scan
08-28 10:32:22.305  2691  2750 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-28 10:32:22.306  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:32:22.306  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 10:32:22.306  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 10:32:22.307  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 10:32:22.307  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:32:22.308  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 10:32:22.308  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 10:32:22.308  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 10:32:22.309  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:22.309  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:22.309  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:32:22.309  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
,08-28 10:32:22.309  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:22.309  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:22.309  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 10:32:22.309  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:22.310  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:22.310  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:22.311  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:22.311  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:32:22.311  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:22.311  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:22.312  3768  3816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-28 10:32:22.314  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:22.319  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 10:32:22.319  2691  2729 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-28 10:32:22.320  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.322  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:22.322  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-28 10:32:22.323  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-28 10:32:22.323  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-28 10:32:22.323  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-28 10:32:22.324  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:22.325  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:22.326  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-28 10:32:22.326  2691  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-28 10:32:22.326  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:22.328  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:22.335  3768  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-28 10:32:22.335  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-28 10:32:22.335  2691  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-28 10:32:22.335  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:22.336  2691  2750 D BtGatt.ScanManager: stopping BLe Batch
,08-28 10:32:22.341  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 10:32:22.342  2691  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-28 10:32:22.342  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.342  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:22.342  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 10:32:22.342  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 10:32:22.348  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-28 10:32:22.348  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-28 10:32:22.348  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-28 10:32:22.349  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-28 10:32:22.349  3768  3816 D BluetoothAdapter: STATE_ON
08-28 10:32:22.349  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.352  2691  2702 D BtGatt.GattService: registerClient() - UUID=70ba7b6f-8569-4ca6-a0e7-323968cc14cc
,08-28 10:32:22.352  2691  2729 D BtGatt.GattService: onClientRegistered() - UUID=70ba7b6f-8569-4ca6-a0e7-323968cc14cc, clientIf=5
08-28 10:32:22.353  3768  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-28 10:32:22.353  2691  2845 D BtGatt.GattService: start scan with filters
,08-28 10:32:22.356  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-28 10:32:22.356  2691  2750 D BtGatt.ScanManager: handling starting scan
08-28 10:32:22.356  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 10:32:22.356  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-28 10:32:22.356  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-28 10:32:22.360  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 10:32:22.361  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 10:32:22.361  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-28 10:32:22.362  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 10:32:22.364  2691  2729 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-28 10:32:22.364  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.365  2691  2750 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-28 10:32:22.365  3768  3816 I io.jxcore.node.ConnectionHelper: start: OK
,08-28 10:32:22.372  2691  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-28 10:32:22.372  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:22.373  2691  2750 D BtGatt.ScanManager: Starting BLE batch scan
,08-28 10:32:22.373  2691  2750 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-28 10:32:22.387  2691  2729 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-28 10:32:22.387  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.395  2691  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-28 10:32:22.395  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:22.862  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-28 10:32:22.862  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-28 10:32:22.862  3768  3768 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 10:32:23.903  2691  2691 D BtGatt.ScanManager: awakened up at time 139045
,08-28 10:32:23.905  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:23.940  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-28 10:32:23.940  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:23.941  2691  2729 D BtGatt.GattService: current time is 139083459697
,08-28 10:32:23.942  2691  2729 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -90, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -89, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-28 10:32:23.942  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-28 10:32:23.943  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-28 10:32:23.944  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-28 10:32:23.945  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 10:32:23.945  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 10:32:23.946  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:25.446  2691  2691 D BtGatt.ScanManager: awakened up at time 140589
,08-28 10:32:25.449  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:25.485  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-28 10:32:25.486  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:32:25.486  2691  2729 D BtGatt.GattService: current time is 140628958813
08-28 10:32:25.487  2691  2729 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -95, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:25.488  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-28 10:32:25.489  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-28 10:32:25.489  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 10:32:25.490  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 10:32:25.491  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-28 10:32:26.991  2691  2691 D BtGatt.ScanManager: awakened up at time 142133
,08-28 10:32:26.994  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:27.046  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-28 10:32:27.047  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:27.048  2691  2729 D BtGatt.GattService: current time is 142191015371
08-28 10:32:27.049  2691  2729 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -94, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 10:32:27.050  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-28 10:32:27.051  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-28 10:32:27.052  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-28 10:32:27.053  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-28 10:32:27.054  2691  2729 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-28 10:32:27.366  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:32:27.366  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:27.367  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-28 10:32:27.367  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:27.368  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-28 10:32:27.368  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 10:32:27.368  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-28 10:32:27.368  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 10:32:27.369  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-28 10:32:27.370  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 10:32:27.370  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-28 10:32:27.372  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:32:27.375  2691  2835 D BtGatt.GattService: stopScan() - queue size =1
,08-28 10:32:27.380  2691  2702 D BtGatt.GattService: unregisterClient() - clientIf=5
08-28 10:32:27.381  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-28 10:32:27.381  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-28 10:32:27.381  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-28 10:32:27.382  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-28 10:32:27.382  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-28 10:32:27.385  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 10:32:27.386  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 10:32:27.386  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 10:32:27.386  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-28 10:32:27.388  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 10:32:27.391  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 10:32:27.391  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 10:32:27.392  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:32:27.397  2691  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-28 10:32:27.397  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:27.398  2691  2750 D BtGatt.ScanManager: stopping BLe Batch
,08-28 10:32:27.413  2691  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-28 10:32:27.413  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:27.414  2691  2750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:32:27.430  2691  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-28 10:32:27.430  2691  2729 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:32:27.893  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 10:32:27.893  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:32:27.894  3768  3768 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 10:32:32.393  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:32:32.394  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.394  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:32.396  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.396  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:32.396  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 10:32:32.396  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.397  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.397  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.397  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 10:32:32.398  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.399  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:32.400  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.403  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.403  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.404  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:32.404  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.406  3768  3816 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-28 10:32:32.408  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:32:32.409  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:32:32.409  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:32.410  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 10:32:32.410  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.411  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.412  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
,08-28 10:32:32.412  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.412  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.412  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.412  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.412  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.412  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:32.413  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.415  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.415  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.415  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.415  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.416  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-28 10:32:32.416  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.416  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.416  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:32.417  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.417  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.417  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.417  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
,08-28 10:32:32.417  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.417  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.417  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.417  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.418  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:32.418  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.418  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.419  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.419  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.419  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.419  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.420  3768  3816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-28 10:32:32.420  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.420  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.420  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:32.420  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.420  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.420  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.421  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.421  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.421  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.421  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.421  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.421  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.421  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.421  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:32.422  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.422  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.422  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.423  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.423  3768  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-28 10:32:32.423  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.423  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.424  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:32.424  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.424  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.424  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:32.424  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.424  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.424  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.424  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.425  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.425  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:32.425  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.425  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.426  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.426  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.426  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:32.426  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.427  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-28 10:32:32.427  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 10:32:32.427  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 10:32:32.427  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-28 10:32:32.427  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:32.427  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:32.427  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-28 10:32:32.427  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-28 10:32:32.428  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-28 10:32:32.428  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.428  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.428  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:32.428  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.428  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.428  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.429  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.429  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:32.429  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.429  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.429  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.429  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:32.429  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.429  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.430  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.430  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:32:32.430  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.430  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:32.431  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 10:32:32.432  3768  3816 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-28 10:32:32.432  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-28 10:32:32.435  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 10:32:32.435  3768  3816 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-28 10:32:32.436  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-28 10:32:32.437  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-28 10:32:32.438  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-28 10:32:32.438  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-28 10:32:32.439  3768  3816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-28 10:32:32.439  3768  3816 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-28 10:32:32.439  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 10:32:32.439  3768  3816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-28 10:32:32.439  3768  3816 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-28 10:32:32.439  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 10:32:32.440  3768  3816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-28 10:32:32.440  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-28 10:32:32.443  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-28 10:32:32.444  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-28 10:32:32.444  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-28 10:32:32.445  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-28 10:32:32.445  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-28 10:32:32.445  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-28 10:32:32.445  3768  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-28 10:32:32.446  3768  3816 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-28 10:32:32.446  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.446  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.447  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:32.447  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.447  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.447  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.447  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-28 10:32:32.448  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.448  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.448  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.448  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.448  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.449  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.449  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.449  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.450  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.450  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.450  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.450  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.452  3768  3816 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-28 10:32:32.452  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.452  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.452  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:32.453  3768  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-28 10:32:32.454  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.454  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.454  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.454  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.454  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.454  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.454  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.454  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.454  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.454  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.454  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.455  3768  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-28 10:32:32.456  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.456  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.456  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.456  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.457  3768  3816 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-28 10:32:32.457  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.457  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.457  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:32.457  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.457  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.457  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.457  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.457  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.457  3768  3834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 10:32:32.458  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.458  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.458  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.458  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.458  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.458  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.460  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.460  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.460  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.460  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.464  3768  3816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-28 10:32:32.464  3768  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-28 10:32:32.464  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-28 10:32:32.465  3768  3816 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-28 10:32:32.465  3768  3816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-28 10:32:32.465  3768  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-28 10:32:32.465  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-28 10:32:32.467  3768  3816 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-28 10:32:32.467  3768  3816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-28 10:32:32.467  3768  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-28 10:32:32.468  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-28 10:32:32.468  3768  3816 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-28 10:32:32.468  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:32.468  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:32.468  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:32.469  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.469  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.469  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.469  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.469  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.469  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.469  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.469  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.469  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.469  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:32.469  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.474  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:32.474  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:32.474  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.474  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.475  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:32.475  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.475  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:32.475  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:32.475  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:32.475  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:32.475  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:32.475  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:32.475  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:34.956   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-28 10:32:34.968  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-28 10:32:34.976   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-28 10:32:34.976   872   892 I Adreno  : Build Date                       : 10/20/15
08-28 10:32:34.976   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-28 10:32:34.976   872   892 I Adreno  : Local Branch                     : M14
08-28 10:32:34.976   872   892 I Adreno  : Remote Branch                    : 
08-28 10:32:34.976   872   892 I Adreno  : Remote Branch                    : 
08-28 10:32:34.976   872   892 I Adreno  : Reconstruct Branch               : 
,08-28 10:32:35.013   280   363 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (281 us)
,08-28 10:32:35.680  3768  3768 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-28 10:32:35.680  3768  3768 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-28 10:32:35.720   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-28 10:32:35.722  3768  3768 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@13001c6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c451ee3, 16908290=android.view.AbsSavedState$1@c451ee3}, android:focusedViewId=100}]}]
08-28 10:32:35.722  3768  3768 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-28 10:32:35.722  3768  3768 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-28 10:32:35.723  3768  3768 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-28 10:32:35.737   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-28 10:32:35.745   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-28 10:32:35.748   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-28 10:32:35.748   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-28 10:32:35.982   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-28 10:32:35.986   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-28 10:32:35.987   872  1327 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,08-28 10:32:35.991   872   892 I DreamManagerService: Entering dreamland.
,08-28 10:32:35.993   872   892 I PowerManagerService: Dozing...
,08-28 10:32:35.994   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-28 10:32:36.032   376  1309 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-28 10:32:36.032   376  1309 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-28 10:32:36.044  1928  3840 D NfcService: Discovery configuration equal, not updating.
,08-28 10:32:36.046   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:32:36.059   872  1301 E native  : do suspend false
,08-28 10:32:36.080   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-28 10:32:36.094   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:32:36.100   872  1301 E native  : do suspend true
,08-28 10:32:36.174   376  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-28 10:32:36.175   376  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-28 10:32:36.551   872  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-28 10:32:37.476  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.477  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:37.477  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:37.477  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.478  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.478  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
,08-28 10:32:37.478  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:37.479  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:37.479  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-28 10:32:37.480  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 10:32:37.480  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:37.481  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.481  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:37.481  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.482  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:37.482  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:37.482  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.482  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.483  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.483  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.486  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 10:32:37.487  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:37.487  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:37.488  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.492  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-28 10:32:37.493  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 10:32:37.495  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-28 10:32:37.496  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-28 10:32:37.497  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-28 10:32:37.497  3768  3768 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-28 10:32:37.497  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-28 10:32:37.497  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-28 10:32:37.498  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 10:32:37.498  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-28 10:32:37.498  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-28 10:32:37.498  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-28 10:32:37.498  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.498  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-28 10:32:37.498  3768  3768 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-28 10:32:37.499  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
,08-28 10:32:37.499  3768  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-28 10:32:37.499  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.499  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-28 10:32:37.499  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 10:32:37.499  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 10:32:37.499  3768  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-28 10:32:37.499  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.499  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.500  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:32:37.501  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 10:32:37.501  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-28 10:32:37.501  3768  3768 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-28 10:32:37.501  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:32:37.501  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.501  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:37.501  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:37.502  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:37.502  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:37.502  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.502  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.502  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:37.502  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.502  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.502  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:37.502  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.502  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.503  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.503  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.504  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:37.504  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:37.504  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.504  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.506  3768  3816 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-28 10:32:37.506  3768  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-28 10:32:37.506  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-28 10:32:37.506  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:37.507  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-28 10:32:37.507  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:37.507  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:37.507  3768  3816 V io.jxcore.node.StartStopOperationHandl,er: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:37.507  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:32:37.507  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.507  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.508  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:37.508  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.508  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
,08-28 10:32:37.508  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:37.508  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.508  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.508  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.508  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.510  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 10:32:37.510  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:37.510  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:37.510  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.514  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-28 10:32:37.514  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:32:37.515  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:37.515  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 10:32:37.515  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.515  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.516  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:37.516  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.516  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list,
08-28 10:32:37.516  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:37.516  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:37.516  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.516  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:37.516  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.517  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:37.517  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-28 10:32:37.517  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.517  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.518  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:32:37.519  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:32:37.519  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:32:37.519  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-28 10:32:37.519  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.519  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.519  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@433cbb0 not in the list
08-28 10:32:37.519  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:37.519  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.520  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 10:32:37.520  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:37.520  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:32:37.520  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:32:37.520  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:37.521  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:32:37.521  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:32:37.521  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:37.521  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3d8a29 not in the list
08-28 10:32:37.522  3768  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-28 10:32:37.523  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-28 10:32:37.523  3768  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-28 10:32:37.523  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-28 10:32:37.523  3768  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-28 10:32:37.523  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-28 10:32:37.526  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-28 10:32:37.526  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-28 10:32:37.527  3768  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-28 10:32:37.527  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-28 10:32:37.527  3768  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-28 10:32:37.527  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-28 10:32:37.527  3768  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-28 10:32:37.527  3768  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-28 10:32:37.528  3768  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-28 10:32:37.528  3768  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-28 10:32:37.529  3768  3816 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-28 10:32:37.529  3768  3816 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-28 10:32:37.529  3768  3816 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-28 10:32:37.529  3768  3816 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-28 10:32:37.530  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:32:37.530  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6980e0 added. We now have 3 listener(s)
08-28 10:32:37.530  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:32:37.532  3768  3816 D BluetoothAdapter: enable(): BT is already enabled..!
08-28 10:32:37.533   872  1962 D WifiService: setWifiEnabled: true pid=3768, uid=10000
08-28 10:32:37.533   872  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 10:32:37.604  2691  2806 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40,
,08-28 10:32:37.605  3768  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
,08-28 10:32:37.607  2691  2830 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-28 10:32:38.002  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-28 10:32:38.935   872  2342 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:32:40.204  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:40.215  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:40.219  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:40.276  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:32:40.276  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-28 10:32:40.277  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:32:40.277  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:40.333  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:32:40.334  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:32:40.340  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-28 10:32:41.648  1884  2509 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-28 10:32:42.541  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 10:32:42.542  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2704f99 added. We now have 4 listener(s)
08-28 10:32:42.542  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:32:42.559  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:32:42.559  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2704f99 removed from the list
08-28 10:32:42.560  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:42.560  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:42.560  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:42.562  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 10:32:42.563  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b68b25e added. We now have 4 listener(s)
08-28 10:32:42.563  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:32:42.568  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:32:42.568  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b68b25e removed from the list
,08-28 10:32:42.568  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:32:42.569  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:32:42.569  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:32:42.571  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:32:42.572  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a0c63f added. We now have 4 listener(s)
,08-28 10:32:42.572  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:32:42.581   872  1472 D WifiService: setWifiEnabled: false pid=3768, uid=10000
,08-28 10:32:42.581   872  1472 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 10:32:42.595  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:32:42.600  2691  2725 D BluetoothAdapterState: Current state: ON, message: 23
,08-28 10:32:42.600  2691  2725 D BluetoothAdapterProperties: Setting state to 13
08-28 10:32:42.600  2691  2725 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-28 10:32:42.602  2691  2725 D BluetoothAdapterProperties: onBluetoothDisable()
,08-28 10:32:42.608  2691  2725 I BluetoothAdapterState: Entering PendingCommandState
08-28 10:32:42.608  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:42.608  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:42.613  2691  2691 D BluetoothMapService: onReceive
08-28 10:32:42.613  2691  2691 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-28 10:32:42.620  2691  2691 D BluetoothMapService: STATE_TURNING_OFF
,08-28 10:32:42.621  2691  2691 D BluetoothMapService: MAP Service closeService in
,08-28 10:32:42.621  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.621  2691  2691 D BluetoothMapMasInstance0: MAP Service shutdown
08-28 10:32:42.621  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:42.622  2691  2691 D ObexServerSockets0: shutdown(block = true)
,08-28 10:32:42.622  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 10:32:42.622  2691  2847 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-28 10:32:42.623  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-28 10:32:42.625  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.626   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-28 10:32:42.626   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-28 10:32:42.626   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 10:32:42.626   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-28 10:32:42.628  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().,
,08-28 10:32:42.628  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:42.628  2691  2848 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-28 10:32:42.631  2691  2830 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-28 10:32:42.632  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:42.632  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 10:32:42.632  2691  2691 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-28 10:32:42.632  2691  2691 I BtOppRfcommListener: stopping Accept Thread
08-28 10:32:42.633  2691  3466 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-28 10:32:42.633  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.633  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:42.633  2691  3466 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-28 10:32:42.633   872  1301 E native  : do suspend true
08-28 10:32:42.636  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:42.636  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 10:32:42.637  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:42.637  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:42.640  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:42.642   872   885 I ActivityManager: Start proc 3849:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-28 10:32:42.643  2691  2729 D BluetoothAdapterProperties: Scan Mode:20
08-28 10:32:42.643  2691  2725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-28 10:32:42.647  2691  2691 D HeadsetService: Received stop request...Stopping profile...
08-28 10:32:42.648   872  2345 D DhcpClient: Clearing IP address
08-28 10:32:42.649   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-28 10:32:42.649  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:42.650   872   872 D BluetoothHeadset: Proxy object disconnected
08-28 10:32:42.650  1357  3767 D BluetoothHeadset: Proxy object disconnected
,08-28 10:32:42.651  1357  1357 D HeadsetProfile: Bluetooth service disconnected
,08-28 10:32:42.651  1944  2296 D BluetoothHeadset: Proxy object disconnected
08-28 10:32:42.652  2691  2691 D A2dpService: Received stop request...Stopping profile...
08-28 10:32:42.652   872   872 D BluetoothHeadset: Proxy object disconnected
,08-28 10:32:42.652   372   870 D CommandListener: Setting iface cfg
08-28 10:32:42.652   872   872 D BluetoothHeadset: Proxy object disconnected
08-28 10:32:42.652  2691  2840 D A2dpStateMachine: Exit Disconnected: -1
,08-28 10:32:42.653  1504  2559 V NativeCrypto: Read error: ssl=0x9ad3c600: I/O error during system call, Connection timed out
08-28 10:32:42.654  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.654  1357  1357 D BluetoothA2dp: Proxy object disconnected
,08-28 10:32:42.655   872   872 D BluetoothA2dp: Proxy object disconnected
08-28 10:32:42.655  1504  2559 V NativeCrypto: SSL shutdown failed: ssl=0x9ad3c600: I/O error during system call, Broken pipe
08-28 10:32:42.655  2691  2691 D HidService: Received stop request...Stopping profile...
08-28 10:32:42.656  2691  2691 D HidService: Stopping Bluetooth HidService
08-28 10:32:42.657  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.657  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-28 10:32:42.658  1357  1357 D HidProfile: Bluetooth service disconnected
08-28 10:32:42.658   872  1369 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-28 10:32:42.658  2691  2691 D HealthService: Received stop request...Stopping profile...
08-28 10:32:42.659   872  2339 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-28 10:32:42.662  2691  2691 D PanService: Received stop request...Stopping profile...
,08-28 10:32:42.663  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-28 10:32:42.663  1357  1357 D PanProfile: Bluetooth service disconnected
08-28 10:32:42.663  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-28 10:32:42.663  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:42.663  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:32:42.663  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:32:42.665   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-28 10:32:42.665   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-28 10:32:42.665   872  2339 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-28 10:32:42.665  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-28 10:32:42.665  2691  2806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:32:42.665  2691  2806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:32:42.665  2691  2806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:32:42.666   872  2347 D DhcpClient: Receive thread stopped
,08-28 10:32:42.666  2691  2729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-28 10:32:42.666  2691  2729 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-28 10:32:42.667   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-28 10:32:42.667   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-28 10:32:42.667   872  1301 E native  : do suspend true
08-28 10:32:42.668  2691  2691 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-28 10:32:42.668   395   395 E Parcel  : Reading a NULL string not supported here.
08-28 10:32:42.672  2691  2691 D BluetoothMapService: Received stop request...Stopping profile...
08-28 10:32:42.672  2691  2691 D BluetoothMapService: stop()
08-28 10:32:42.672  2691  2691 D BluetoothMapAppObserver: deinitObservers()
,08-28 10:32:42.673  2691  2691 D BluetoothMapAppObserver: removeReceiver()
08-28 10:32:42.673   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-28 10:32:42.674  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-28 10:32:42.675  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:42.675  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:32:42.675  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:32:42.676  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-28 10:32:42.676  2691  2691 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isTurningOff()=true
,08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:42.676  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:32:42.677  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:32:42.677  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-28 10:32:42.677  2691  2729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-28 10:32:42.677  2691  2806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:32:42.677  2691  2729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-28 10:32:42.677  2691  2806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:32:42.677  2691  2729 E bt_btif : L2CAP - PSM: 0x0019 not found for deregistration
08-28 10:32:42.677  2691  2806 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-28 10:32:42.677  2691  2806 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 10:32:42.677  2691  2806 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-28 10:32:42.677  2691  2806 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 10:32:42.678  2691  2691 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-28 10:32:42.678  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-28 10:32:42.678  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:42.678  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:32:42.678  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:32:42.679  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-28 10:32:42.679  2691  2691 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-28 10:32:42.680  2691  2691 D BluetoothMapService: MAP Service closeService in
08-28 10:32:42.680  2691  2691 V BluetoothAdapterState: isTurningOff()=true
08-28 10:32:42.680  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:42.680  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:32:42.680  2691  2691 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:42.680  2691  2725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-28 10:32:42.680  2691  2725 D BluetoothAdapterProperties: Setting state to 15
08-28 10:32:42.680  2691  2691 D BluetoothMapService: cleanup()
08-28 10:32:42.681  2691  2691 D BluetoothMapService: MAP Service closeService in
08-28 10:32:42.681  2691  2725 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-28 10:32:42.681  2691  2725 I BluetoothAdapterState: Entering BleOnState
,08-28 10:32:42.681  1357  3767 D BluetoothPbap: onBluetoothStateChange: up=false
08-28 10:32:42.682   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 10:32:42.682  1357  2036 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 10:32:42.683  1357  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:32:42.683  1357  1370 D BluetoothPan: onBluetoothStateChange on: false
,08-28 10:32:42.686   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:32:42.686  1357  3767 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-28 10:32:42.687   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:32:42.687  1357  2036 D BluetoothMap: onBluetoothStateChange: up=false
08-28 10:32:42.688   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:32:42.688  1944  2296 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-28 10:32:42.691  2691  2725 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-28 10:32:42.691  2691  2725 D BluetoothAdapterProperties: Setting state to 16
08-28 10:32:42.691  2691  2725 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-28 10:32:42.692  2691  2725 D BluetoothAdapterProperties: onBleDisable
08-28 10:32:42.692  2691  2725 I BluetoothAdapterState: Entering PendingCommandState
08-28 10:32:42.692  2691  2726 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-28 10:32:42.692  2691  2729 D BluetoothAdapterProperties: Scan Mode:20
08-28 10:32:42.696  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:42.696  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:42.697  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.697  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:42.698  2691  2806 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-28 10:32:42.698  2691  2806 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:32:42.699  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:42.699  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:42.700  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.700  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:42.702  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:42.702  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:42.702  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.702  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:42.703  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.704  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.705  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:42.715  3849  3849 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-28 10:32:42.717   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:32:42.725  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 10:32:42.730   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed8a555:true
,08-28 10:32:42.732  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 10:32:42.733   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-28 10:32:42.733   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-28 10:32:42.735   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-28 10:32:42.735   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:32:42.745   872  1694 I ActivityManager: Start proc 3866:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-28 10:32:42.749   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-28 10:32:42.751   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-28 10:32:42.753  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.754  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:42.754  3396  3396 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@356d74 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-28 10:32:42.754  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:42.767   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:32:42.769  1884  2286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-28 10:32:42.770  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:42.770  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:42.770  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.770  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:42.772  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:42.772  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:42.772   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-28 10:32:42.773  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.773  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:42.774  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:42.775  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:42.775  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:42.775  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:42.786  3866  3866 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-28 10:32:42.790  3849  3849 D LocalBluetoothProfileManager: Adding local MAP profile
,08-28 10:32:42.792  3849  3849 D BluetoothMap: Create BluetoothMap proxy object
,08-28 10:32:42.800  3849  3849 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-28 10:32:42.805   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-28 10:32:42.805   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-28 10:32:42.805   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-28 10:32:42.814  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-28 10:32:42.818   872   883 I ActivityManager: Killing 3217:com.google.android.gm/u0a78 (adj 15): empty #17
,08-28 10:32:42.899  2691  2729 I bt_hci  : shut_down
,08-28 10:32:42.900  2691  2751 D bt_hwcfg: hw_epilog_process
,08-28 10:32:42.901  2691  2751 I bt_vendor: low_power_mode_cb
,08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.exists(File.java:361)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.e.b(PG:170)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.k.d(PG:583)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.e.b(PG:170)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.exists(File.java:361)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.exists(File.java:361)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:32:42.920  3866  3866 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:32:42.920  3866  3866 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:32:42.925  2691  2751 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-28 10:32:42.925  2691  2751 I bt_vendor: epilog_cb
08-28 10:32:42.925  2691  2751 I bt_hci  : epilog_finished_callback
08-28 10:32:42.931  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-28 10:32:42.937  2691  2729 I bt_hci_h4: hal_close
08-28 10:32:42.938  3849  3849 D DockEventReceiver: finishStartingService: stopping service
08-28 10:32:42.938  2691  2729 I bt_userial_vendor: device fd = 51 close
08-28 10:32:42.942  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 10:32:42.945   872  1962 I ActivityManager: Killing 3396:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-28 10:32:43.029  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 10:32:43.036  1717  1717 D SystemUpdateService: onCreate
,08-28 10:32:43.041  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 10:32:43.045  1717  3901 I SystemUpdateService: active receiver: enabled
,08-28 10:32:43.062  1717  3901 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-28 10:32:43.065  2691  2726 D bt_stack_manager: event_shut_down_stack finished.
08-28 10:32:43.066  2691  2725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-28 10:32:43.075  1717  3901 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-28 10:32:43.076  1717  3901 I SystemUpdateService: now status is 0 (complete)
,08-28 10:32:43.075  2691  2725 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-28 10:32:43.076  2691  2691 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-28 10:32:43.076  1717  3901 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-28 10:32:43.076  1717  3901 I SystemUpdateService: file has been verified
08-28 10:32:43.076  2691  2691 D BtGatt.GattService: Received stop request...Stopping profile...
,08-28 10:32:43.076  2691  2691 D BtGatt.GattService: stop()
,08-28 10:32:43.076  2691  2691 D BtGatt.AdvertiseManager: advertise clients cleared
08-28 10:32:43.078  2691  2691 V BluetoothAdapterState: isTurningOff()=false
08-28 10:32:43.078  2691  2691 V BluetoothAdapterState: isTurningOn()=false
08-28 10:32:43.078  2691  2691 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:32:43.078  2691  2691 V BluetoothAdapterState: isBleTurningOff()=true
08-28 10:32:43.078  2691  2725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-28 10:32:43.079  2691  2725 D BluetoothAdapterProperties: Setting state to 10
08-28 10:32:43.079  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-28 10:32:43.079  2691  2725 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-28 10:32:43.079  2691  2725 I BluetoothAdapterState: Entering OffState
08-28 10:32:43.080   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-28 10:32:43.081  1717  3901 I SystemUpdateService: OTA package size = 12249756
,08-28 10:32:43.088  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-28 10:32:43.088  2691  2691 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-28 10:32:43.088  2691  2691 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-28 10:32:43.088  2691  2726 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-28 10:32:43.092  2691  2726 D bt_stack_manager: event_clean_up_stack finished.
,08-28 10:32:43.093  1717  2536 I iu.UploadsManager: num queued entries: 0
,08-28 10:32:43.094  2691  2691 I art     : System.exit called, status: 0
,08-28 10:32:43.094  2691  2691 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-28 10:32:43.104  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-28 10:32:43.105  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-28 10:32:43.104  1717  2536 I iu.UploadsManager: num updated entries: 0
,08-28 10:32:43.110  1717  3901 I SystemUpdateService: showing system update notification
,08-28 10:32:43.114  1717  2536 I iu.SyncManager: NEXT; no task
,08-28 10:32:43.121   872  1693 I ActivityManager: Start proc 3904:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-28 10:32:43.145   872  1962 I ActivityManager: Process com.android.bluetooth (pid 2691) has died
,08-28 10:32:43.167  3904  3904 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-28 10:32:43.172  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:32:43.191  3904  3904 D SprintDMHelper: simOperator: 
08-28 10:32:43.191  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-28 10:32:43.204   872  1369 I ActivityManager: Start proc 3917:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-28 10:32:43.208  1717  1717 D SystemUpdateService: onDestroy
,08-28 10:32:43.285  3866  3895 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-28 10:32:43.307  2248  3932 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-28 10:32:43.312   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a87d358:true
,08-28 10:32:43.328   872  2209 I ActivityManager: Start proc 3933:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-28 10:32:43.331   872  1961 I ActivityManager: Killing 2775:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-28 10:32:43.407  3933  3933 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-28 10:32:43.460  3933  3933 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-28 10:32:43.460  3933  3933 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-28 10:32:43.460  3933  3933 I GAv4    :   adb logcat -s GAv4
,08-28 10:32:43.472  3933  3933 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-28 10:32:43.524  3933  3933 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-28 10:32:43.551  3933  3951 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-28 10:32:43.636  3933  3933 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-28 10:32:43.667  3933  3933 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-28 10:32:43.675  3933  3933 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8815-8817)
08-28 10:32:43.675  3933  3933 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-28 10:32:43.684  3933  3933 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8c91ba4}
08-28 10:32:43.685  3933  3933 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-28 10:32:43.685  3933  3933 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-28 10:32:43.698  3933  3933 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-28 10:32:43.701  3933  3933 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-28 10:32:43.720  3933  3933 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-28 10:32:43.734  3933  3933 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-28 10:32:43.734  3933  3933 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-28 10:32:43.734  3933  3933 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-28 10:32:43.734  3933  3933 I Adreno  : Build Date                       : 10/20/15
08-28 10:32:43.734  3933  3933 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-28 10:32:43.734  3933  3933 I Adreno  : Local Branch                     : M14
08-28 10:32:43.734  3933  3933 I Adreno  : Remote Branch                    : 
08-28 10:32:43.734  3933  3933 I Adreno  : Remote Branch                    : 
08-28 10:32:43.734  3933  3933 I Adreno  : Reconstruct Branch               : 
,08-28 10:32:43.785  3933  3933 I NSApplication: Starting up...
,08-28 10:32:43.797  3933  3979 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-28 10:32:43.828   872   882 I ActivityManager: Start proc 3984:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-28 10:32:43.832   872   882 I ActivityManager: Killing 1697:android.process.acore/u0a5 (adj 15): empty #17
,08-28 10:32:43.905  3984  3984 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-28 10:32:44.118   872  1693 I ActivityManager: Killing 3623:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-28 10:32:44.210   872  1906 I ActivityManager: Start proc 3998:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-28 10:32:44.282  3998  3998 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-28 10:32:44.338  3998  3998 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-28 10:32:44.359   872  1369 I ActivityManager: Killing 3638:com.android.musicfx/u0a18 (adj 15): empty #17
,08-28 10:32:47.631   872  1693 D WifiService: setWifiEnabled: true pid=3768, uid=10000
08-28 10:32:47.631   872  1693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 10:32:47.671  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:47.671  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:32:47.671  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:47.671  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:47.672  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:47.672  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:32:47.672  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:47.673  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:47.674  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:47.674  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:32:47.674  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:47.674  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:47.675   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-28 10:32:47.691   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-28 10:32:47.692   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-28 10:32:47.693   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-28 10:32:47.694   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-28 10:32:47.694   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-28 10:32:47.694   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-28 10:32:47.695   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-28 10:32:47.709   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-28 10:32:47.710   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-28 10:32:47.710   372   870 D CommandListener: Setting iface cfg
,08-28 10:32:47.711   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-28 10:32:47.711   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-28 10:32:47.721   872  1301 E native  : do suspend true
,08-28 10:32:47.721   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-28 10:32:47.727   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-28 10:32:47.734   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:32:48.301   872  1962 I ActivityManager: Killing 3425:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-28 10:32:49.125   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 10:32:49.242   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.12 rxSuccessRate=8.75 delta 1000 -> 994
,08-28 10:32:49.244   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-28 10:32:49.244   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:32:49.258   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-28 10:32:49.315   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-28 10:32:49.317  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-28 10:32:49.750  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-28 10:32:49.799  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-28 10:32:49.800  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-28 10:32:49.812   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:32:49.825   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-28 10:32:49.827   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-28 10:32:49.828   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:32:49.844   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:32:49.855   372   870 D CommandListener: Setting iface cfg
08-28 10:32:49.856   872  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-28 10:32:49.864   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-28 10:32:49.901   872  4035 D DhcpClient: Receive thread started
,08-28 10:32:49.988   872  1301 E native  : do suspend false
,08-28 10:32:50.011   872  2345 D DhcpClient: Broadcasting DHCPDISCOVER
,08-28 10:32:50.026   872  4035 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172659, domain null
,08-28 10:32:50.028   872  2345 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172659 seconds
,08-28 10:32:50.031   872  2345 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-28 10:32:50.044   872  4035 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-28 10:32:50.045   872  2345 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-28 10:32:50.050   372   870 D CommandListener: Setting iface cfg
,08-28 10:32:50.061   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-28 10:32:50.063   872  2345 D DhcpClient: Scheduling renewal in 86399s
08-28 10:32:50.064   872  1301 E native  : do suspend true
,08-28 10:32:50.089   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-28 10:32:50.093   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-28 10:32:50.094   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-28 10:32:50.097   872  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-28 10:32:50.109   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-28 10:32:50.151   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-28 10:32:50.152   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-28 10:32:50.153   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-28 10:32:50.154   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-28 10:32:50.156   872  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-28 10:32:50.166   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-28 10:32:50.173   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-28 10:32:50.173   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-28 10:32:50.174   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-28 10:32:50.174   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-28 10:32:50.174   872  1303 D ConnectivityService:    accepting network in place of null
,08-28 10:32:50.174   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-28 10:32:50.175   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-28 10:32:50.190   872  4034 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165332, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-28 10:32:50.205   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:32:50.235   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:32:50.239   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-28 10:32:50.239   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:32:50.240   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-28 10:32:50.245   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-28 10:32:50.262  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:50.262  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 10:32:50.262  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:50.262  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:50.265  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:50.265  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-28 10:32:50.265  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:50.265  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:50.267  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:32:50.267  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:32:50.267  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:50.268  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:32:50.280  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 10:32:50.284  1717  1717 D SystemUpdateService: onCreate
,08-28 10:32:50.294  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 10:32:50.309   872  4033 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.78,2a00:1450:4001:815::200e
,08-28 10:32:50.312  1717  4045 I SystemUpdateService: active receiver: enabled
,08-28 10:32:50.319  1717  4045 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-28 10:32:50.323  1717  4045 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-28 10:32:50.323  1717  4045 I SystemUpdateService: now status is 0 (complete)
08-28 10:32:50.323  1717  4045 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-28 10:32:50.323  1717  4045 I SystemUpdateService: file has been verified
08-28 10:32:50.323  1717  4045 I SystemUpdateService: OTA package size = 12249756
,08-28 10:32:50.330  1717  4045 I SystemUpdateService: showing system update notification
,08-28 10:32:50.340  3721  4050 I BooksSync: Starting books sync for 61035162, extras: ade
,08-28 10:32:50.347  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:50.362  1717  1717 D SystemUpdateService: onDestroy
,08-28 10:32:50.379  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-28 10:32:50.393  1717  4053 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-28 10:32:50.393  1717  4053 W BaseAppContext: Using Auth Proxy for data requests.
,08-28 10:32:50.395  1717  4053 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-28 10:32:50.397  1717  2536 I iu.UploadsManager: num queued entries: 0
,08-28 10:32:50.406   872  4033 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 28 Aug 2016 08:32:50 GMT], X-Android-Received-Millis=[1472373170406], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472373170369]}
08-28 10:32:50.407  1717  2536 I iu.UploadsManager: num updated entries: 0
08-28 10:32:50.408   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-28 10:32:50.408   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-28 10:32:50.408   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-28 10:32:50.409   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-28 10:32:50.415  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-28 10:32:50.416  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-28 10:32:50.419  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:32:50.422  3904  3904 D SprintDMHelper: simOperator: 
08-28 10:32:50.422  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-28 10:32:50.462  3721  4057 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-28 10:32:50.443  1717  2536 I iu.SyncManager: NEXT; no task
,08-28 10:32:50.517  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:50.519  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:32:50.527  1504  4060 I VacuumService: Vacuum at: now=1472373170526 tag=VacuumService
,08-28 10:32:50.550  3029  4049 V KeepSync: Connecting to GoogleApiClient
,08-28 10:32:50.550   872  1907 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 10:32:50.565  2248  4056 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-28 10:32:50.582  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-28 10:32:50.582  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 10:32:50.582  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:32:50.582  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:50.657  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-28 10:32:50.657  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-28 10:32:50.658  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:32:50.658  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:50.679  3721  4057 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-28 10:32:50.680  3721  4050 E BooksSync: Soft error
08-28 10:32:50.680  3721  4050 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:32:50.680  3721  4050 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-28 10:32:50.680  3721  4050 E BooksSync: Sync error
08-28 10:32:50.680  3721  4050 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:32:50.680  3721  4050 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-28 10:32:50.680  3721  4050 I BooksSync: Finished books sync
,08-28 10:32:50.694   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161549, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:32:50.727  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-28 10:32:50.727  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-28 10:32:50.727  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:32:50.727  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:50.752  1717  4066 V BaseAuthAsyncOperation: access token request failed
,08-28 10:32:50.753  3029  4049 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 10:32:50.777  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-28 10:32:50.777  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-28 10:32:50.777  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:32:50.778  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:50.836  1717  4053 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-28 10:32:50.861  1504  4062 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-28 10:32:50.869  1504  4062 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-28 10:32:50.919  1504  4062 W Uploader:  no longer exists, so no auth token.
,08-28 10:32:50.963  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 10:32:50.963  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-28 10:32:50.963  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:32:50.964  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:50.980  3029  4049 E KeepSync: IOException
08-28 10:32:50.980  3029  4049 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 10:32:50.980  3029  4049 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:32:50.980  3029  4049 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 10:32:50.980  3029  4049 E KeepSync: 	... 10 more
,08-28 10:32:50.980  3029  4049 W KeepSync: Sync result 2
,08-28 10:32:50.994   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 161109, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:32:51.239   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-28 10:32:52.021  1504  4062 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-28 10:32:52.021  1504  4062 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 10:32:52.021  1504  4062 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:32:52.021  1504  4062 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:52.036  1504  4062 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 10:32:52.036  1504  4062 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 10:32:52.036  1504  4062 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 10:32:52.388  1504  4062 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-28 10:32:52.388  1504  4062 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 10:32:52.388  1504  4062 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:32:52.389  1504  4062 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:52.405  1504  4062 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 10:32:52.405  1504  4062 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 10:32:52.405  1504  4062 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 10:32:52.553  1504  4062 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-28 10:32:52.553  1504  4062 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-28 10:32:52.553  1504  4062 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:32:52.553  1504  4062 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:32:52.571  1504  4062 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 10:32:52.571  1504  4062 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-28 10:32:52.571  1504  4062 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-28 10:32:52.637   872  1906 D WifiService: setWifiEnabled: false pid=3768, uid=10000
08-28 10:32:52.637   872  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 10:32:52.658  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-28 10:32:52.660   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-28 10:32:52.660   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-28 10:32:52.661   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 10:32:52.661   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:32:52.681   872  1301 E native  : do suspend true
,08-28 10:32:52.690   872  2345 D DhcpClient: Clearing IP address
,08-28 10:32:52.691   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-28 10:32:52.693   372   870 D CommandListener: Setting iface cfg
,08-28 10:32:52.695  1504  4059 V NativeCrypto: Read error: ssl=0x9ad0a000: I/O error during system call, Connection timed out
08-28 10:32:52.697  1504  4059 V NativeCrypto: SSL shutdown failed: ssl=0x9ad0a000: I/O error during system call, Broken pipe
08-28 10:32:52.699   872  4035 D DhcpClient: Receive thread stopped
,08-28 10:32:52.701   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-28 10:32:52.701   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-28 10:32:52.707   395   395 E Parcel  : Reading a NULL string not supported here.
08-28 10:32:52.707   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
08-28 10:32:52.715   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-28 10:32:52.715   872  1301 E native  : do suspend true
08-28 10:32:52.718   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-28 10:32:52.744  1504  4062 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.198.138 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-28 10:32:52.747   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:32:52.773   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:32:52.773   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-28 10:32:52.774   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-28 10:32:52.774   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:32:52.776   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-28 10:32:52.778  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:52.778  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:52.778  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:52.778  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:52.780   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-28 10:32:52.780  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:52.781  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:52.781  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.781  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:52.782  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:52.782  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:52.782  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.782  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:52.791  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 10:32:52.795   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:32:52.797  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:52.798  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:52.798  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:52.798  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:52.799  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:52.799  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:52.799   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-28 10:32:52.799  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.799  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:52.799  1884  2286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-28 10:32:52.800  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:52.800  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:52.800  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:32:52.800  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:52.802  1717  1717 D SystemUpdateService: onCreate
,08-28 10:32:52.806  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 10:32:52.811  1717  4085 I SystemUpdateService: active receiver: enabled
,08-28 10:32:52.818  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-28 10:32:52.826  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-28 10:32:52.827  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-28 10:32:52.828  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:32:52.832  3904  3904 D SprintDMHelper: simOperator: 
08-28 10:32:52.832  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-28 10:32:52.834  1717  4085 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-28 10:32:52.848   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-28 10:32:52.850  2248  4089 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-28 10:32:52.850   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-28 10:32:52.851  1717  4085 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-28 10:32:52.851  1717  4085 I SystemUpdateService: now status is 0 (complete)
08-28 10:32:52.851  1717  4085 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-28 10:32:52.819  1717  2536 I iu.UploadsManager: num queued entries: 0
,08-28 10:32:52.853  1717  2536 I iu.UploadsManager: num updated entries: 0
,08-28 10:32:52.856  1717  4085 I SystemUpdateService: file has been verified
,08-28 10:32:52.857  1717  4085 I SystemUpdateService: OTA package size = 12249756
,08-28 10:32:52.863  1717  2536 I iu.SyncManager: NEXT; no task
,08-28 10:32:52.864  1717  4085 I SystemUpdateService: showing system update notification
,08-28 10:32:52.898  1717  1717 D SystemUpdateService: onDestroy
,08-28 10:32:57.673   872   889 I ActivityManager: Start proc 4093:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-28 10:32:57.806  4093  4093 D AdapterServiceConfig: Adding HeadsetService
,08-28 10:32:57.806  4093  4093 D AdapterServiceConfig: Adding A2dpService
,08-28 10:32:57.807  4093  4093 D AdapterServiceConfig: Adding HidService
,08-28 10:32:57.807  4093  4093 D AdapterServiceConfig: Adding HealthService
,08-28 10:32:57.807  4093  4093 D AdapterServiceConfig: Adding PanService
08-28 10:32:57.807  4093  4093 D AdapterServiceConfig: Adding GattService
08-28 10:32:57.807  4093  4093 D AdapterServiceConfig: Adding BluetoothMapService
,08-28 10:32:57.824   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2633767:true
,08-28 10:32:57.825  4093  4093 D BluetoothAdapterState: make() - Creating AdapterState
,08-28 10:32:57.838  4093  4093 I bt_bluedroid: init
,08-28 10:32:57.838  4093  4105 I BluetoothAdapterState: Entering OffState
,08-28 10:32:57.846  4093  4106 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-28 10:32:57.847  4093  4106 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-28 10:32:57.847  4093  4106 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-28 10:32:57.847  4093  4106 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-28 10:32:57.851  4093  4093 I bt_bluedroid: get_profile_interface socket
,08-28 10:32:57.855  4093  4109 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 10:32:57.857  4093  4109 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 10:32:57.859  4093  4093 I bt_bluedroid: get_profile_interface sdp
,08-28 10:32:57.866  4093  4104 I bt_bluedroid: config_hci_snoop_log
,08-28 10:32:57.869   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-28 10:32:57.882  4093  4105 D BluetoothAdapterState: Current state: OFF, message: 0
,08-28 10:32:57.883  4093  4105 D BluetoothAdapterProperties: Setting state to 14
,08-28 10:32:57.883  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-28 10:32:57.890  4093  4105 D BluetoothBondStateMachine: make
,08-28 10:32:57.895  4093  4110 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-28 10:32:57.905  4093  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-28 10:32:57.909  4093  4093 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-28 10:32:57.919  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:32:57.921  4093  4093 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-28 10:32:57.924  4093  4093 D BtGatt.GattService: Received start request. Starting profile...
,08-28 10:32:57.925  4093  4093 D BtGatt.GattService: start()
,08-28 10:32:57.926  4093  4093 I bt_bluedroid: get_profile_interface gatt
,08-28 10:32:57.930  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:32:57.930  4093  4093 D BtGatt.AdvertiseManager: advertise manager created
,08-28 10:32:57.942  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-28 10:32:57.942  4093  4093 V BluetoothAdapterState: isTurningOn()=false
,08-28 10:32:57.942  4093  4093 V BluetoothAdapterState: isBleTurningOn()=true
08-28 10:32:57.942  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:57.943  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-28 10:32:57.943  4093  4105 I bt_bluedroid: enable
,08-28 10:32:57.944  4093  4106 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-28 10:32:57.944  4093  4106 I bt_hci  : start_up
,08-28 10:32:57.953  4093  4106 I bt_vendor: alloc value 0xb3997189
,08-28 10:32:57.953  4093  4106 I bt_vendor: init
,08-28 10:32:57.953  4093  4106 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-28 10:32:57.953  4093  4106 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-28 10:32:58.060  4093  4106 D bt_hci  : start_up starting async portion
,08-28 10:32:58.060  4093  4113 I bt_hci  : event_finish_startup
08-28 10:32:58.061  4093  4113 I bt_hci_h4: hal_open
08-28 10:32:58.061  4093  4113 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-28 10:32:58.070  4093  4113 I bt_userial_vendor: device fd = 51 open
,08-28 10:32:58.101  4093  4113 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 10:32:58.133  4093  4113 D bt_hwcfg: Chipset BCM4354A2
08-28 10:32:58.134  4093  4113 D bt_hwcfg: Target name = [BCM4354A2]
,08-28 10:32:58.134  4093  4113 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-28 10:32:58.180   872  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-28 10:32:58.793  4093  4113 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-28 10:32:58.795  4093  4113 D bt_hwcfg: Settlement delay -- 100 ms
08-28 10:32:58.795  4093  4113 I bt_hwcfg: Setting fw settlement delay to 100 
,08-28 10:32:58.912  4093  4113 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 10:32:58.913  4093  4113 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-28 10:32:58.943  4093  4113 I bt_hwcfg: vendor lib fwcfg completed
,08-28 10:32:58.943  4093  4113 I bt_vendor: firmware callback
08-28 10:32:58.943  4093  4113 I bt_hci  : firmware_config_callback
,08-28 10:32:58.954  4093  4115 I bt_btu  : btu_task pending for preload complete event
,08-28 10:32:58.955  4093  4115 I bt_btu_task: Bluetooth chip preload is complete
,08-28 10:32:58.955  4093  4115 I bt_btu  : btu_task received preload complete event
,08-28 10:32:58.965  4093  4115 I         : BTE_InitTraceLevels -- TRC_HCI
,08-28 10:32:58.965  4093  4115 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-28 10:32:58.965  4093  4115 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-28 10:32:58.965  4093  4115 I         : BTE_InitTraceLevels -- TRC_AVDT
08-28 10:32:58.966  4093  4115 I         : BTE_InitTraceLevels -- TRC_AVRC
08-28 10:32:58.966  4093  4115 I         : BTE_InitTraceLevels -- TRC_A2D
,08-28 10:32:58.966  4093  4115 I         : BTE_InitTraceLevels -- TRC_BNEP
08-28 10:32:58.966  4093  4115 I         : BTE_InitTraceLevels -- TRC_BTM
08-28 10:32:58.967  4093  4115 I         : BTE_InitTraceLevels -- TRC_GAP
,08-28 10:32:58.967  4093  4115 I         : BTE_InitTraceLevels -- TRC_PAN
08-28 10:32:58.967  4093  4115 I         : BTE_InitTraceLevels -- TRC_SDP
08-28 10:32:58.968  4093  4115 I         : BTE_InitTraceLevels -- TRC_GATT
,08-28 10:32:58.968  4093  4115 I         : BTE_InitTraceLevels -- TRC_SMP
08-28 10:32:58.968  4093  4115 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-28 10:32:58.968  4093  4115 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-28 10:32:59.101  4093  4115 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3914d9d
,08-28 10:32:59.101  4093  4115 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3914d9d 
,08-28 10:32:59.113  4093  4109 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-28 10:32:59.115  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-28 10:32:59.116  4093  4109 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 10:32:59.122  4093  4109 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 10:32:59.125  4093  4109 D BluetoothAdapterProperties: Scan Mode:20
,08-28 10:32:59.126  4093  4109 D BluetoothAdapterProperties: Discoverable Timeout:120
08-28 10:32:59.126  4093  4109 D bt_hci  : do_postload posting postload work item
,08-28 10:32:59.126  4093  4113 I bt_hci  : event_postload
08-28 10:32:59.127  4093  4113 I bt_vendor: sco_config_cb
08-28 10:32:59.127  4093  4113 I bt_hci  : sco_config_callback postload finished.
,08-28 10:32:59.129  4093  4109 D bt_bte_conf: Device ID record 1 : primary
,08-28 10:32:59.130  4093  4109 D bt_bte_conf:   vendorId            = 000f
08-28 10:32:59.130  4093  4109 D bt_bte_conf:   vendorIdSource      = 0001
,08-28 10:32:59.130  4093  4109 D bt_bte_conf:   product             = 1200
08-28 10:32:59.130  4093  4109 D bt_bte_conf:   version             = 1436
08-28 10:32:59.130  4093  4109 D bt_bte_conf:   clientExecutableURL = 
,08-28 10:32:59.131  4093  4109 D bt_bte_conf:   serviceDescription  = 
08-28 10:32:59.131  4093  4109 D bt_bte_conf:   documentationURL    = 
08-28 10:32:59.132  4093  4109 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-28 10:32:59.132  4093  4106 D bt_stack_manager: event_start_up_stack finished
,08-28 10:32:59.135  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-28 10:32:59.135  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:59.135  4093  4105 D BluetoothAdapterProperties: Setting state to 15
,08-28 10:32:59.136  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-28 10:32:59.136  4093  4113 I bt_vendor: low_power_mode_cb
08-28 10:32:59.137  4093  4105 I BluetoothAdapterState: Entering BleOnState
08-28 10:32:59.138  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:59.141  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:59.142  4093  4105 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-28 10:32:59.142  4093  4105 D BluetoothAdapterProperties: Setting state to 11
,08-28 10:32:59.142  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-28 10:32:59.146  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:32:59.147  4093  4093 D HeadsetService: Received start request. Starting profile...
08-28 10:32:59.151  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:59.153  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:59.154  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:59.160  4093  4093 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-28 10:32:59.161  4093  4093 D HeadsetStateMachine: make
08-28 10:32:59.162  4093  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-28 10:32:59.168  4093  4093 D HeadsetStateMachine: max_hf_connections = 1
,08-28 10:32:59.168  4093  4093 I bt_bluedroid: get_profile_interface handsfree
08-28 10:32:59.169  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-28 10:32:59.169  4093  4109 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-28 10:32:59.172  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:32:59.173  4093  4093 D A2dpService: Received start request. Starting profile...
,08-28 10:32:59.174  4093  4093 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-28 10:32:59.174  4093  4093 I bt_bluedroid: get_profile_interface avrcp
,08-28 10:32:59.180  4093  4093 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-28 10:32:59.180  4093  4093 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-28 10:32:59.180  4093  4093 D A2dpStateMachine: make
,08-28 10:32:59.182  4093  4093 I bt_bluedroid: get_profile_interface a2dp
,08-28 10:32:59.183  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-28 10:32:59.184  4093  4125 D A2dpStateMachine: Enter Disconnected: -2
,08-28 10:32:59.185  4093  4093 I BluetoothHidServiceJni: classInitNative: succeeds
,08-28 10:32:59.186  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:32:59.187  4093  4093 D HidService: Received start request. Starting profile...
,08-28 10:32:59.188  3849  3849 D BluetoothInputDevice: Proxy object connected
,08-28 10:32:59.188  4093  4093 I bt_bluedroid: get_profile_interface hidhost
08-28 10:32:59.188  4093  4093 D HidService: setHidService(): set to: null
,08-28 10:32:59.188  4093  4109 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f63e5
08-28 10:32:59.188  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-28 10:32:59.188  3849  3849 D HidProfile: Bluetooth service connected
08-28 10:32:59.189  4093  4093 I BluetoothHealthServiceJni: classInitNative: succeeds,
08-28 10:32:59.189  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:32:59.190  4093  4093 D HealthService: Received start request. Starting profile...
,08-28 10:32:59.192  4093  4093 I bt_bluedroid: get_profile_interface health
08-28 10:32:59.192  4093  4093 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-28 10:32:59.193  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:32:59.194  4093  4093 D PanService: Received start request. Starting profile...
,08-28 10:32:59.194  3849  3849 D BluetoothPan: BluetoothPAN Proxy object connected
08-28 10:32:59.195  4093  4093 D BluetoothPanServiceJni: initializeNative(L110): pan
08-28 10:32:59.195  4093  4093 I bt_bluedroid: get_profile_interface pan
08-28 10:32:59.195  3849  3849 D PanProfile: Bluetooth service connected
08-28 10:32:59.195  4093  4109 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-28 10:32:59.199  4093  4093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:32:59.199  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 10:32:59.200  3849  3849 D BluetoothMap: Proxy object connected
08-28 10:32:59.200  4093  4093 D BluetoothMapService: Received start request. Starting profile...
08-28 10:32:59.200  4093  4093 D BluetoothMapService: start()
,08-28 10:32:59.201  3849  3849 D MapProfile: Bluetooth service connected
08-28 10:32:59.201  3849  3849 D BluetoothMap: getConnectedDevices()
08-28 10:32:59.202  3849  3849 D BluetoothMap: Bluetooth is Not enabled
08-28 10:32:59.203  4093  4093 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-28 10:32:59.204  4093  4093 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-28 10:32:59.204  4093  4093 D BluetoothMapAppObserver: createReceiver()
,08-28 10:32:59.206  4093  4093 D BluetoothMapAppObserver: initObservers()
,08-28 10:32:59.206  4093  4093 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-28 10:32:59.217  4093  4123 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-28 10:32:59.217  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-28 10:32:59.218  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-28 10:32:59.218  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false,
08-28 10:32:59.218  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:59.219  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-28 10:32:59.219  4093  4093 V BluetoothAdapterState: isTurningOn()=true
,08-28 10:32:59.219  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isTurningOn()=true
,08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:32:59.220  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:59.221  4093  4093 V BluetoothAdapterState: isTurningOff()=false
08-28 10:32:59.221  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-28 10:32:59.221  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:32:59.221  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:59.224  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-28 10:32:59.224  4093  4093 V BluetoothAdapterState: isTurningOn()=true
08-28 10:32:59.224  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:32:59.224  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:32:59.224  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-28 10:32:59.225  4093  4105 D BluetoothAdapterProperties: ScanMode =  20
08-28 10:32:59.225  4093  4105 D BluetoothAdapterProperties: State =  11
08-28 10:32:59.225  4093  4105 D BluetoothAdapterProperties: Setting state to 12
08-28 10:32:59.225  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-28 10:32:59.226  4093  4105 I BluetoothAdapterState: Entering OnState
08-28 10:32:59.226  1357  2036 D BluetoothPbap: onBluetoothStateChange: up=true
08-28 10:32:59.228  4093  4109 D BluetoothAdapterProperties: Scan Mode:21
08-28 10:32:59.228  4093  4109 D BluetoothAdapterProperties: Discoverable Timeout:120
08-28 10:32:59.230   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-28 10:32:59.231  3849  3861 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-28 10:32:59.232  3849  3859 D BluetoothPbap: onBluetoothStateChange: up=true
08-28 10:32:59.232   872   872 D BluetoothA2dp: Proxy object connected
08-28 10:32:59.234  4093  4093 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:59.234  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:59.234  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
08-28 10:32:59.235  4093  4093 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-28 10:32:59.237  1357  1357 D BluetoothA2dp: Proxy object connected
,08-28 10:32:59.237  1357  3767 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:32:59.238  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:32:59.239  3849  3861 D BluetoothPan: onBluetoothStateChange on: true
,08-28 10:32:59.239  1357  2036 D BluetoothPan: onBluetoothStateChange on: true
08-28 10:32:59.240  4093  4093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:32:59.243  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-28 10:32:59.243  1357  1357 D PanProfile: Bluetooth service connected
08-28 10:32:59.244   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-28 10:32:59.244  1357  3767 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-28 10:32:59.245  4093  4093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:59.246  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:59.246  1357  1357 D BluetoothInputDevice: Proxy object connected
08-28 10:32:59.246  1357  1357 D HidProfile: Bluetooth service connected
,08-28 10:32:59.246  4093  4093 D ObexServerSockets: Succeed to create listening sockets 
08-28 10:32:59.246   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-28 10:32:59.247  4093  4093 D ObexServerSockets0: startAccept()
,08-28 10:32:59.247  4093  4093 D ObexServerSockets0: prepareForNewConnect()
,08-28 10:32:59.247  1357  2036 D BluetoothMap: onBluetoothStateChange: up=true
,08-28 10:32:59.249  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:59.249  4093  4093 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-28 10:32:59.249  4093  4093 D BluetoothSdpJni: SDP Create record success - handle: 0
08-28 10:32:59.250  1357  1357 D BluetoothMap: Proxy object connected
08-28 10:32:59.250   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:32:59.250  1357  1357 D MapProfile: Bluetooth service connected
,08-28 10:32:59.251  1357  1357 D BluetoothMap: getConnectedDevices()
08-28 10:32:59.251  4093  4131 D ObexServerSockets0: Accepting socket connection...
08-28 10:32:59.251  3849  3859 D BluetoothMap: onBluetoothStateChange: up=true
08-28 10:32:59.251  4093  4130 D ObexServerSockets0: Accepting socket connection...
,08-28 10:32:59.252  1944  2071 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:32:59.253  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:32:59.255   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-28 10:32:59.255  4093  4093 D BluetoothMapService: onReceive
08-28 10:32:59.255  4093  4093 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-28 10:32:59.255  4093  4093 D BluetoothMapService: STATE_ON
08-28 10:32:59.256  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:32:59.258  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:59.258  3849  3849 D LocalBluetoothProfileManager: Adding local A2DP profile
08-28 10:32:59.259  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:32:59.261  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:32:59.265  3849  3849 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-28 10:32:59.270  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 10:32:59.272  3849  3849 D BluetoothA2dp: Proxy object connected
,08-28 10:32:59.276  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 10:32:59.279  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-28 10:32:59.285  3849  3849 D BluetoothPbap: Proxy object connected
,08-28 10:32:59.285  1357  1357 D BluetoothPbap: Proxy object connected
08-28 10:32:59.285  1357  1357 D PbapServerProfile: Bluetooth service connected
08-28 10:32:59.285  4093  4093 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-28 10:32:59.285  3849  3849 D PbapServerProfile: Bluetooth service connected
,08-28 10:32:59.285  4093  4093 D ObexServerSockets0: prepareForNewConnect()
,08-28 10:32:59.296  4093  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:32:59.315  4093  4140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:32:59.317  4093  4140 I BtOppRfcommListener: Accept thread started.
,08-28 10:32:59.339   872   872 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.340  1357  2036 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.340  1357  1357 D HeadsetProfile: Bluetooth service connected
08-28 10:32:59.341  1944  1954 D BluetoothHeadset: Proxy object connected
08-28 10:32:59.341   872   872 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.341   872   872 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.344   872   889 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.347   872   889 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.350   872   889 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.353  1944  2295 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.367  3849  3861 D BluetoothHeadset: Proxy object connected
,08-28 10:32:59.367  3849  3849 D HeadsetProfile: Bluetooth service connected
,08-28 10:33:01.416  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:01.427  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:01.431  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:01.486  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-28 10:33:01.486  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-28 10:33:01.487  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:01.487  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:01.559  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:33:01.560  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:33:01.563  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-28 10:33:02.650  4093  4105 D BluetoothAdapterState: Current state: ON, message: 23
,08-28 10:33:02.651  4093  4105 D BluetoothAdapterProperties: Setting state to 13
08-28 10:33:02.651  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-28 10:33:02.653  4093  4105 D BluetoothAdapterProperties: onBluetoothDisable()
,08-28 10:33:02.658  4093  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-28 10:33:02.668  4093  4093 D BluetoothMapService: onReceive
,08-28 10:33:02.668  4093  4093 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-28 10:33:02.668  4093  4093 D BluetoothMapService: STATE_TURNING_OFF
,08-28 10:33:02.669  4093  4093 D BluetoothMapService: MAP Service closeService in
08-28 10:33:02.669  4093  4093 D BluetoothMapMasInstance0: MAP Service shutdown
08-28 10:33:02.670  4093  4093 D ObexServerSockets0: shutdown(block = true)
08-28 10:33:02.670  4093  4109 D BluetoothAdapterProperties: Scan Mode:20
,08-28 10:33:02.671  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-28 10:33:02.670  4093  4130 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-28 10:33:02.672  4093  4093 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-28 10:33:02.673  4093  4131 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-28 10:33:02.673  4093  4117 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-28 10:33:02.679  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:02.679  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:33:02.680  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:33:02.680  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:33:02.681  4093  4093 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-28 10:33:02.681  4093  4093 I BtOppRfcommListener: stopping Accept Thread
08-28 10:33:02.682  4093  4140 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-28 10:33:02.684  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:02.684  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:33:02.684  4093  4140 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-28 10:33:02.685  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:33:02.685  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:33:02.687  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:02.687  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:33:02.687  4093  4093 D HeadsetService: Received stop request...Stopping profile...
08-28 10:33:02.688  3768  3768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-28 10:33:02.688  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:33:02.689   872   872 D BluetoothHeadset: Proxy object disconnected
,08-28 10:33:02.689  3849  3861 D BluetoothHeadset: Proxy object disconnected
08-28 10:33:02.690  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:02.690  1357  3767 D BluetoothHeadset: Proxy object disconnected
08-28 10:33:02.690  1944  2071 D BluetoothHeadset: Proxy object disconnected
08-28 10:33:02.691   872   872 D BluetoothHeadset: Proxy object disconnected
08-28 10:33:02.691   872   872 D BluetoothHeadset: Proxy object disconnected
,08-28 10:33:02.691  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 10:33:02.691  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:02.691  4093  4093 D A2dpService: Received stop request...Stopping profile...
08-28 10:33:02.692  4093  4125 D A2dpStateMachine: Exit Disconnected: -1
08-28 10:33:02.694  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:02.694   872   872 D BluetoothA2dp: Proxy object disconnected
08-28 10:33:02.695  4093  4093 D HidService: Received stop request...Stopping profile...
08-28 10:33:02.695  4093  4093 D HidService: Stopping Bluetooth HidService
,08-28 10:33:02.695  3849  3849 D HeadsetProfile: Bluetooth service disconnected
08-28 10:33:02.697  4093  4093 D HealthService: Received stop request...Stopping profile...
,08-28 10:33:02.698  4093  4093 D PanService: Received stop request...Stopping profile...
,08-28 10:33:02.698  1357  1357 D HeadsetProfile: Bluetooth service disconnected
08-28 10:33:02.699  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-28 10:33:02.699  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-28 10:33:02.699  1357  1357 D HidProfile: Bluetooth service disconnected
08-28 10:33:02.699  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-28 10:33:02.699  1357  1357 D PanProfile: Bluetooth service disconnected
08-28 10:33:02.700  4093  4093 D BluetoothMapService: Received stop request...Stopping profile...
08-28 10:33:02.700  4093  4093 D BluetoothMapService: stop()
08-28 10:33:02.700  4093  4093 D BluetoothMapAppObserver: deinitObservers()
,08-28 10:33:02.701  4093  4093 D BluetoothMapAppObserver: removeReceiver()
08-28 10:33:02.702  1357  1357 D BluetoothMap: Proxy object disconnected
08-28 10:33:02.702  1357  1357 D MapProfile: Bluetooth service disconnected
,08-28 10:33:02.703  4093  4093 V BluetoothAdapterState: isTurningOff()=true
08-28 10:33:02.703  4093  4093 V BluetoothAdapterState: isTurningOn()=false
08-28 10:33:02.703  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:02.703  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:33:02.705  4093  4093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-28 10:33:02.705  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-28 10:33:02.706  4093  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 10:33:02.706  4093  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-28 10:33:02.706  4093  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:33:02.707  4093  4109 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-28 10:33:02.707  3849  3849 D DockEventReceiver: finishStartingService: stopping service
08-28 10:33:02.708  4093  4093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-28 10:33:02.709  4093  4093 V BluetoothAdapterState: isTurningOff()=true
,08-28 10:33:02.711  3849  3849 D BluetoothA2dp: Proxy object disconnected
08-28 10:33:02.709  4093  4093 V BluetoothAdapterState: isTurningOn()=false
08-28 10:33:02.711  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:02.711  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:02.711  3849  3849 D BluetoothInputDevice: Proxy object disconnected
08-28 10:33:02.711  3849  3849 D HidProfile: Bluetooth service disconnected
,08-28 10:33:02.711  3849  3849 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-28 10:33:02.712  3849  3849 D PanProfile: Bluetooth service disconnected
08-28 10:33:02.712  3849  3849 D BluetoothMap: Proxy object disconnected
,08-28 10:33:02.712  3849  3849 D MapProfile: Bluetooth service disconnected
08-28 10:33:02.712  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-28 10:33:02.712  4093  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:33:02.712  4093  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:33:02.712  4093  4115 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-28 10:33:02.712  4093  4093 V BluetoothAdapterState: isTurningOff()=true
08-28 10:33:02.713  4093  4115 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 10:33:02.713  4093  4093 V BluetoothAdapterState: isTurningOn()=false
,08-28 10:33:02.713  4093  4115 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-28 10:33:02.713  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:02.713  4093  4115 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-28 10:33:02.713  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:33:02.716  4093  4093 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-28 10:33:02.716  4093  4093 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-28 10:33:02.717  4093  4093 V BluetoothAdapterState: isTurningOff()=true
08-28 10:33:02.717  4093  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-28 10:33:02.717  4093  4093 V BluetoothAdapterState: isTurningOn()=false
,08-28 10:33:02.717  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:02.717  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:02.717  4093  4093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-28 10:33:02.717  4093  4109 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-28 10:33:02.719  4093  4093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-28 10:33:02.719  4093  4093 V BluetoothAdapterState: isTurningOff()=true
08-28 10:33:02.719  4093  4093 V BluetoothAdapterState: isTurningOn()=false
,08-28 10:33:02.719  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:02.719  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:02.719  4093  4093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-28 10:33:02.719  4093  4093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-28 10:33:02.721  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 10:33:02.722  4093  4093 D BluetoothMapService: MAP Service closeService in
08-28 10:33:02.722  4093  4093 V BluetoothAdapterState: isTurningOff()=true
,08-28 10:33:02.722  4093  4093 V BluetoothAdapterState: isTurningOn()=false
08-28 10:33:02.722  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:02.722  4093  4093 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:02.722  4093  4093 D BluetoothMapService: cleanup()
,08-28 10:33:02.722  4093  4093 D BluetoothMapService: MAP Service closeService in
08-28 10:33:02.723  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-28 10:33:02.723  4093  4105 D BluetoothAdapterProperties: Setting state to 15
08-28 10:33:02.723  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-28 10:33:02.723  4093  4105 I BluetoothAdapterState: Entering BleOnState
08-28 10:33:02.724  1357  3767 D BluetoothPbap: onBluetoothStateChange: up=false
08-28 10:33:02.724   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 10:33:02.725  3849  3859 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-28 10:33:02.726  3849  3859 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-28 10:33:02.726  3849  3861 D BluetoothPbap: onBluetoothStateChange: up=false
08-28 10:33:02.729  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
08-28 10:33:02.730  1357  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:33:02.731  3849  3859 D BluetoothPan: onBluetoothStateChange on: false,
,08-28 10:33:02.731  1357  2036 D BluetoothPan: onBluetoothStateChange on: false
,08-28 10:33:02.732   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-28 10:33:02.732  3849  3861 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-28 10:33:02.732  1357  3767 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-28 10:33:02.733   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:33:02.733  1357  1370 D BluetoothMap: onBluetoothStateChange: up=false
08-28 10:33:02.733   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-28 10:33:02.734  3849  3859 D BluetoothMap: onBluetoothStateChange: up=false
08-28 10:33:02.734  1944  1954 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-28 10:33:02.734  4093  4105 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-28 10:33:02.735  4093  4105 D BluetoothAdapterProperties: Setting state to 16
08-28 10:33:02.735  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-28 10:33:02.735  4093  4105 D BluetoothAdapterProperties: onBleDisable
08-28 10:33:02.735  4093  4105 I BluetoothAdapterState: Entering PendingCommandState
08-28 10:33:02.735  4093  4106 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-28 10:33:02.736  4093  4115 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-28 10:33:02.736  4093  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-28 10:33:02.740  4093  4109 D BluetoothAdapterProperties: Scan Mode:20
08-28 10:33:02.741  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-28 10:33:02.742  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:02.743  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:02.744  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:02.746  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:02.746  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 10:33:02.747  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:02.748  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:02.754  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-28 10:33:02.938  4093  4109 I bt_hci  : shut_down
,08-28 10:33:02.950  4093  4113 I bt_vendor: low_power_mode_cb
,08-28 10:33:02.950  4093  4113 D bt_hwcfg: hw_epilog_process
,08-28 10:33:02.977  4093  4113 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-28 10:33:02.978  4093  4113 I bt_vendor: epilog_cb
,08-28 10:33:02.978  4093  4113 I bt_hci  : epilog_finished_callback
,08-28 10:33:02.986  4093  4109 I bt_hci_h4: hal_close
,08-28 10:33:02.988  4093  4109 I bt_userial_vendor: device fd = 51 close
,08-28 10:33:03.108  4093  4106 D bt_stack_manager: event_shut_down_stack finished.
,08-28 10:33:03.110  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-28 10:33:03.117  4093  4105 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-28 10:33:03.118  4093  4093 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-28 10:33:03.120  4093  4093 D BtGatt.GattService: Received stop request...Stopping profile...
,08-28 10:33:03.120  4093  4093 D BtGatt.GattService: stop()
08-28 10:33:03.121  4093  4093 D BtGatt.AdvertiseManager: advertise clients cleared
,08-28 10:33:03.127  4093  4093 V BluetoothAdapterState: isTurningOff()=false
,08-28 10:33:03.127  4093  4093 V BluetoothAdapterState: isTurningOn()=false
08-28 10:33:03.127  4093  4093 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:03.128  4093  4093 V BluetoothAdapterState: isBleTurningOff()=true
08-28 10:33:03.129  4093  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-28 10:33:03.129  4093  4105 D BluetoothAdapterProperties: Setting state to 10
08-28 10:33:03.129  4093  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-28 10:33:03.131  4093  4105 I BluetoothAdapterState: Entering OffState
,08-28 10:33:03.132   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-28 10:33:03.163  4093  4093 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-28 10:33:03.163  4093  4093 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-28 10:33:03.163  4093  4106 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-28 10:33:03.165  4093  4106 D bt_stack_manager: event_clean_up_stack finished.
08-28 10:33:03.166  4093  4093 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-28 10:33:03.168  4093  4093 I art     : System.exit called, status: 0
,08-28 10:33:03.169  4093  4093 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-28 10:33:03.222   872  1907 I ActivityManager: Process com.android.bluetooth (pid 4093) has died
,08-28 10:33:07.648  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-28 10:33:07.648  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:07.653  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:33:07.654  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a0c63f removed from the list
08-28 10:33:07.654  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:07.654  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:33:07.655  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:07.658  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-28 10:33:07.658  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ed4c55 added. We now have 4 listener(s)
08-28 10:33:07.658  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:33:07.660  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:33:07.660  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ed4c55 removed from the list
08-28 10:33:07.661  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:07.661  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:07.661  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:07.663  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:33:07.664  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b09966a added. We now have 4 listener(s)
,08-28 10:33:07.664  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:33:12.678  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:12.726   872   889 I ActivityManager: Start proc 4151:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-28 10:33:12.853  4151  4151 D AdapterServiceConfig: Adding HeadsetService
08-28 10:33:12.853  4151  4151 D AdapterServiceConfig: Adding A2dpService
,08-28 10:33:12.853  4151  4151 D AdapterServiceConfig: Adding HidService
08-28 10:33:12.853  4151  4151 D AdapterServiceConfig: Adding HealthService
08-28 10:33:12.853  4151  4151 D AdapterServiceConfig: Adding PanService
08-28 10:33:12.854  4151  4151 D AdapterServiceConfig: Adding GattService
,08-28 10:33:12.854  4151  4151 D AdapterServiceConfig: Adding BluetoothMapService
,08-28 10:33:12.869  4151  4151 D BluetoothAdapterState: make() - Creating AdapterState
,08-28 10:33:12.869   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8cc91ca:true
,08-28 10:33:12.877  4151  4151 I bt_bluedroid: init
,08-28 10:33:12.878  4151  4163 I BluetoothAdapterState: Entering OffState
,08-28 10:33:12.881  4151  4164 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-28 10:33:12.881  4151  4164 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-28 10:33:12.881  4151  4164 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-28 10:33:12.881  4151  4164 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-28 10:33:12.883  4151  4151 I bt_bluedroid: get_profile_interface socket
08-28 10:33:12.885  4151  4151 I bt_bluedroid: get_profile_interface sdp
,08-28 10:33:12.889  4151  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 10:33:12.891  4151  4162 I bt_bluedroid: config_hci_snoop_log
,08-28 10:33:12.892   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-28 10:33:12.892  4151  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 10:33:12.903  4151  4163 D BluetoothAdapterState: Current state: OFF, message: 0
08-28 10:33:12.903  4151  4163 D BluetoothAdapterProperties: Setting state to 14
,08-28 10:33:12.904  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-28 10:33:12.910  4151  4163 D BluetoothBondStateMachine: make
,08-28 10:33:12.914  4151  4168 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-28 10:33:12.921  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-28 10:33:12.921  4151  4151 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-28 10:33:12.926  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:33:12.927  4151  4151 D BtGatt.DebugUtils: handleDebugAction() action=null
08-28 10:33:12.928  4151  4151 D BtGatt.GattService: Received start request. Starting profile...
,08-28 10:33:12.928  4151  4151 D BtGatt.GattService: start()
08-28 10:33:12.928  4151  4151 I bt_bluedroid: get_profile_interface gatt
,08-28 10:33:12.930  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:33:12.930  4151  4151 D BtGatt.AdvertiseManager: advertise manager created
,08-28 10:33:12.942  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-28 10:33:12.942  4151  4151 V BluetoothAdapterState: isTurningOn()=false
,08-28 10:33:12.942  4151  4151 V BluetoothAdapterState: isBleTurningOn()=true
08-28 10:33:12.943  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-28 10:33:12.944  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-28 10:33:12.945  4151  4163 I bt_bluedroid: enable
08-28 10:33:12.946  4151  4164 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-28 10:33:12.947  4151  4164 I bt_hci  : start_up
,08-28 10:33:12.968  4151  4164 I bt_vendor: alloc value 0xb3997189
,08-28 10:33:12.968  4151  4164 I bt_vendor: init
08-28 10:33:12.969  4151  4164 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-28 10:33:12.969  4151  4164 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-28 10:33:13.076  4151  4164 D bt_hci  : start_up starting async portion
08-28 10:33:13.077  4151  4171 I bt_hci  : event_finish_startup
08-28 10:33:13.077  4151  4171 I bt_hci_h4: hal_open
,08-28 10:33:13.078  4151  4171 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-28 10:33:13.089  4151  4171 I bt_userial_vendor: device fd = 51 open
,08-28 10:33:13.119  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 10:33:13.151  4151  4171 D bt_hwcfg: Chipset BCM4354A2
08-28 10:33:13.151  4151  4171 D bt_hwcfg: Target name = [BCM4354A2]
,08-28 10:33:13.152  4151  4171 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-28 10:33:13.929  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-28 10:33:13.931  4151  4171 D bt_hwcfg: Settlement delay -- 100 ms
08-28 10:33:13.931  4151  4171 I bt_hwcfg: Setting fw settlement delay to 100 
,08-28 10:33:14.048  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-28 10:33:14.049  4151  4171 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-28 10:33:14.078  4151  4171 I bt_hwcfg: vendor lib fwcfg completed
08-28 10:33:14.079  4151  4171 I bt_vendor: firmware callback
,08-28 10:33:14.079  4151  4171 I bt_hci  : firmware_config_callback
,08-28 10:33:14.090  4151  4173 I bt_btu  : btu_task pending for preload complete event
,08-28 10:33:14.090  4151  4173 I bt_btu_task: Bluetooth chip preload is complete
,08-28 10:33:14.090  4151  4173 I bt_btu  : btu_task received preload complete event
,08-28 10:33:14.101  4151  4173 I         : BTE_InitTraceLevels -- TRC_HCI
,08-28 10:33:14.101  4151  4173 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-28 10:33:14.101  4151  4173 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-28 10:33:14.102  4151  4173 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-28 10:33:14.102  4151  4173 I         : BTE_InitTraceLevels -- TRC_AVRC
08-28 10:33:14.102  4151  4173 I         : BTE_InitTraceLevels -- TRC_A2D
08-28 10:33:14.102  4151  4173 I         : BTE_InitTraceLevels -- TRC_BNEP
08-28 10:33:14.103  4151  4173 I         : BTE_InitTraceLevels -- TRC_BTM
08-28 10:33:14.103  4151  4173 I         : BTE_InitTraceLevels -- TRC_GAP
,08-28 10:33:14.103  4151  4173 I         : BTE_InitTraceLevels -- TRC_PAN
08-28 10:33:14.103  4151  4173 I         : BTE_InitTraceLevels -- TRC_SDP
08-28 10:33:14.104  4151  4173 I         : BTE_InitTraceLevels -- TRC_GATT
,08-28 10:33:14.104  4151  4173 I         : BTE_InitTraceLevels -- TRC_SMP
08-28 10:33:14.104  4151  4173 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-28 10:33:14.104  4151  4173 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-28 10:33:14.239  4151  4173 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3914d9d
,08-28 10:33:14.239  4151  4173 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3914d9d 
,08-28 10:33:14.251  4151  4167 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-28 10:33:14.253  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-28 10:33:14.255  4151  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-28 10:33:14.260  4151  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-28 10:33:14.264  4151  4167 D BluetoothAdapterProperties: Scan Mode:20
,08-28 10:33:14.265  4151  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
08-28 10:33:14.265  4151  4167 D bt_hci  : do_postload posting postload work item
08-28 10:33:14.265  4151  4171 I bt_hci  : event_postload
,08-28 10:33:14.265  4151  4171 I bt_vendor: sco_config_cb
08-28 10:33:14.265  4151  4171 I bt_hci  : sco_config_callback postload finished.
,08-28 10:33:14.269  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:14.271  4151  4167 D bt_bte_conf: Device ID record 1 : primary
,08-28 10:33:14.271  4151  4167 D bt_bte_conf:   vendorId            = 000f
08-28 10:33:14.272  4151  4167 D bt_bte_conf:   vendorIdSource      = 0001
08-28 10:33:14.272  4151  4167 D bt_bte_conf:   product             = 1200
08-28 10:33:14.272  4151  4167 D bt_bte_conf:   version             = 1436
08-28 10:33:14.273  4151  4167 D bt_bte_conf:   clientExecutableURL = 
,08-28 10:33:14.273  4151  4167 D bt_bte_conf:   serviceDescription  = 
08-28 10:33:14.273  4151  4167 D bt_bte_conf:   documentationURL    = 
08-28 10:33:14.273  4151  4167 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-28 10:33:14.274  4151  4164 D bt_stack_manager: event_start_up_stack finished
08-28 10:33:14.274  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:14.275  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-28 10:33:14.275  4151  4163 D BluetoothAdapterProperties: Setting state to 15
08-28 10:33:14.276  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-28 10:33:14.277  4151  4163 I BluetoothAdapterState: Entering BleOnState
08-28 10:33:14.281  4151  4171 I bt_vendor: low_power_mode_cb
,08-28 10:33:14.285  4151  4163 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-28 10:33:14.285  4151  4163 D BluetoothAdapterProperties: Setting state to 11
08-28 10:33:14.286  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-28 10:33:14.298  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:14.300  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:14.306  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:33:14.307  4151  4151 D HeadsetService: Received start request. Starting profile...
,08-28 10:33:14.313  4151  4151 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-28 10:33:14.314  4151  4151 D HeadsetStateMachine: make
,08-28 10:33:14.321  4151  4151 D HeadsetStateMachine: max_hf_connections = 1
,08-28 10:33:14.322  4151  4151 I bt_bluedroid: get_profile_interface handsfree
,08-28 10:33:14.323  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
08-28 10:33:14.324  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-28 10:33:14.324  4151  4167 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-28 10:33:14.328  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:33:14.328  4151  4151 D A2dpService: Received start request. Starting profile...
08-28 10:33:14.329  4151  4151 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-28 10:33:14.329  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-28 10:33:14.329  4151  4151 I bt_bluedroid: get_profile_interface avrcp
,08-28 10:33:14.335  4151  4151 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-28 10:33:14.335  4151  4151 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-28 10:33:14.335  4151  4151 D A2dpStateMachine: make
,08-28 10:33:14.336  4151  4151 I bt_bluedroid: get_profile_interface a2dp
08-28 10:33:14.337  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-28 10:33:14.339  4151  4151 I BluetoothHidServiceJni: classInitNative: succeeds
,08-28 10:33:14.339  4151  4182 D A2dpStateMachine: Enter Disconnected: -2
08-28 10:33:14.340  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:33:14.340  4151  4151 D HidService: Received start request. Starting profile...
08-28 10:33:14.340  4151  4151 I bt_bluedroid: get_profile_interface hidhost
08-28 10:33:14.340  4151  4151 D HidService: setHidService(): set to: null
08-28 10:33:14.340  4151  4167 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f63e5
08-28 10:33:14.341  4151  4151 I BluetoothHealthServiceJni: classInitNative: succeeds
08-28 10:33:14.341  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-28 10:33:14.342  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:33:14.342  4151  4151 D HealthService: Received start request. Starting profile...
,08-28 10:33:14.344  4151  4151 I bt_bluedroid: get_profile_interface health
08-28 10:33:14.345  4151  4151 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-28 10:33:14.346  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:33:14.346  4151  4151 D PanService: Received start request. Starting profile...
,08-28 10:33:14.346  4151  4151 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-28 10:33:14.346  4151  4151 I bt_bluedroid: get_profile_interface pan
08-28 10:33:14.348  4151  4167 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-28 10:33:14.349  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
08-28 10:33:14.350  4151  4151 D BluetoothMapService: Received start request. Starting profile...
08-28 10:33:14.350  4151  4151 D BluetoothMapService: start()
,08-28 10:33:14.352  4151  4151 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-28 10:33:14.353  4151  4151 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-28 10:33:14.353  4151  4151 D BluetoothMapAppObserver: createReceiver()
,08-28 10:33:14.354  4151  4151 D BluetoothMapAppObserver: initObservers()
08-28 10:33:14.354  4151  4151 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-28 10:33:14.360  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-28 10:33:14.360  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-28 10:33:14.360  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:33:14.360  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:14.360  4151  4180 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-28 10:33:14.362  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-28 10:33:14.362  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-28 10:33:14.363  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:14.363  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:14.363  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-28 10:33:14.363  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-28 10:33:14.363  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:33:14.363  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:14.364  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-28 10:33:14.364  4151  4151 V BluetoothAdapterState: isTurningOn()=true
,08-28 10:33:14.364  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:14.364  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:14.364  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-28 10:33:14.364  4151  4151 V BluetoothAdapterState: isTurningOn()=true
,08-28 10:33:14.365  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-28 10:33:14.365  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:14.365  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-28 10:33:14.365  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-28 10:33:14.365  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-28 10:33:14.365  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-28 10:33:14.365  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-28 10:33:14.366  4151  4163 D BluetoothAdapterProperties: ScanMode =  20
08-28 10:33:14.366  4151  4163 D BluetoothAdapterProperties: State =  11
08-28 10:33:14.366  4151  4163 D BluetoothAdapterProperties: Setting state to 12
08-28 10:33:14.366  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-28 10:33:14.366  4151  4163 I BluetoothAdapterState: Entering OnState
08-28 10:33:14.367  1357  3767 D BluetoothPbap: onBluetoothStateChange: up=true
08-28 10:33:14.370   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-28 10:33:14.370  4151  4167 D BluetoothAdapterProperties: Scan Mode:21
,08-28 10:33:14.370  4151  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
08-28 10:33:14.370  3849  3861 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:33:14.371   872   872 D BluetoothA2dp: Proxy object connected
08-28 10:33:14.371  3849  3859 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:14.372  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-28 10:33:14.373  3849  3861 D BluetoothPbap: onBluetoothStateChange: up=true
,08-28 10:33:14.375  1357  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-28 10:33:14.375  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-28 10:33:14.375  3849  3849 D BluetoothInputDevice: Proxy object connected
08-28 10:33:14.376  3849  3849 D HidProfile: Bluetooth service connected
08-28 10:33:14.376  1357  1357 D BluetoothA2dp: Proxy object connected
08-28 10:33:14.376  1357  2036 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:33:14.377  3849  3859 D BluetoothPan: onBluetoothStateChange on: true
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:14.378  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:33:14.380  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:33:14.380  4151  4151 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-28 10:33:14.380  1357  3767 D BluetoothPan: onBluetoothStateChange on: true
08-28 10:33:14.380  4151  4151 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-28 10:33:14.382  4151  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-28 10:33:14.383   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:33:14.384  3849  3861 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-28 10:33:14.384  4151  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:33:14.385  4151  4151 D ObexServerSockets: Succeed to create listening sockets 
08-28 10:33:14.385  4151  4151 D ObexServerSockets0: startAccept()
08-28 10:33:14.385  4151  4151 D ObexServerSockets0: prepareForNewConnect()
,08-28 10:33:14.386  1357  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-28 10:33:14.387  4151  4151 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-28 10:33:14.387  4151  4151 D BluetoothSdpJni: SDP Create record success - handle: 0
08-28 10:33:14.387  1357  1357 D BluetoothInputDevice: Proxy object connected
,08-28 10:33:14.387  1357  1357 D HidProfile: Bluetooth service connected
,08-28 10:33:14.388  4151  4189 D ObexServerSockets0: Accepting socket connection...
08-28 10:33:14.388   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:33:14.389  3849  3849 D BluetoothA2dp: Proxy object connected
08-28 10:33:14.388  4151  4190 D ObexServerSockets0: Accepting socket connection...
08-28 10:33:14.389  1357  2036 D BluetoothMap: onBluetoothStateChange: up=true
08-28 10:33:14.389  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-28 10:33:14.389  1357  1357 D PanProfile: Bluetooth service connected
08-28 10:33:14.390  3849  3849 D BluetoothPan: BluetoothPAN Proxy object connected
,08-28 10:33:14.390  3849  3849 D PanProfile: Bluetooth service connected
,08-28 10:33:14.392   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-28 10:33:14.393  1357  1357 D BluetoothMap: Proxy object connected
08-28 10:33:14.393  1357  1357 D MapProfile: Bluetooth service connected
08-28 10:33:14.393  1357  1357 D BluetoothMap: getConnectedDevices()
08-28 10:33:14.393  3849  4188 D BluetoothMap: onBluetoothStateChange: up=true
,08-28 10:33:14.395  3849  3849 D BluetoothMap: Proxy object connected
08-28 10:33:14.395  3849  3849 D MapProfile: Bluetooth service connected
08-28 10:33:14.396  3849  3849 D BluetoothMap: getConnectedDevices()
08-28 10:33:14.396  1944  1954 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-28 10:33:14.397   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-28 10:33:14.398  4151  4151 D BluetoothMapService: onReceive
,08-28 10:33:14.398  4151  4151 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-28 10:33:14.398  4151  4151 D BluetoothMapService: STATE_ON
08-28 10:33:14.400  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:14.401  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:14.402  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-28 10:33:14.408  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-28 10:33:14.409  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,08-28 10:33:14.413  3849  3849 D BluetoothPbap: Proxy object connected
,08-28 10:33:14.413  3849  3849 D PbapServerProfile: Bluetooth service connected
,08-28 10:33:14.419  4151  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:33:14.422  1357  1357 D BluetoothPbap: Proxy object connected
,08-28 10:33:14.422  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-28 10:33:14.430  4151  4151 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-28 10:33:14.430  4151  4151 D ObexServerSockets0: prepareForNewConnect()
,08-28 10:33:14.438  4151  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:33:14.439  4151  4200 I BtOppRfcommListener: Accept thread started.
,08-28 10:33:14.472   872   872 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.472  3849  3859 D BluetoothHeadset: Proxy object connected
08-28 10:33:14.473  3849  3849 D HeadsetProfile: Bluetooth service connected
08-28 10:33:14.473  1357  3767 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.473  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-28 10:33:14.473  1944  2295 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.473   872   872 D BluetoothHeadset: Proxy object connected
08-28 10:33:14.474   872   872 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.477  1357  2036 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.477  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-28 10:33:14.484   872   889 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.489   872   889 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.492   872   889 D BluetoothHeadset: Proxy object connected
,08-28 10:33:14.496  1944  2296 D BluetoothHeadset: Proxy object connected
,08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:17.699  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:33:17.706  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:33:17.707  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:33:17.708  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b09966a removed from the list
08-28 10:33:17.708  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:17.709  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:17.709  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:17.712  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:33:17.712  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee5875b added. We now have 4 listener(s)
,08-28 10:33:17.712  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:33:17.716   872  1472 D WifiService: setWifiEnabled: false pid=3768, uid=10000
08-28 10:33:17.717   872  1472 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 10:33:21.975  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:21.986  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:21.987  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:22.025  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:33:22.025  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 10:33:22.025  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:22.026  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:22.054  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:33:22.054  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-28 10:33:22.054  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-28 10:33:22.729  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:22.730   872   883 D WifiService: setWifiEnabled: true pid=3768, uid=10000
08-28 10:33:22.731   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-28 10:33:22.743   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:22.762  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:33:22.768  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-28 10:33:22.777  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-28 10:33:22.778   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-28 10:33:22.779   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-28 10:33:22.780   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-28 10:33:22.781   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-28 10:33:22.782   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-28 10:33:22.782   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-28 10:33:22.782  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-28 10:33:22.782   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-28 10:33:22.799   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-28 10:33:22.801   372   870 D CommandListener: Setting iface cfg
08-28 10:33:22.801   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 10:33:22.802   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-28 10:33:22.802   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-28 10:33:22.858   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-28 10:33:22.859   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-28 10:33:22.859   872  1301 E native  : do suspend true
,08-28 10:33:22.906   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:33:24.293   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-28 10:33:24.449   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=2.36 rxSuccessRate=2.80 delta 1000 -> 1000
,08-28 10:33:24.451   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-28 10:33:24.451   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:33:24.472   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-28 10:33:24.543   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-28 10:33:24.546  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-28 10:33:24.971  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-28 10:33:25.010  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-28 10:33:25.011  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-28 10:33:25.016   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-28 10:33:25.026   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-28 10:33:25.027   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-28 10:33:25.028   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:33:25.054   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-28 10:33:25.067   372   870 D CommandListener: Setting iface cfg
,08-28 10:33:25.068   872  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-28 10:33:25.084   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-28 10:33:25.113   872  4210 D DhcpClient: Receive thread started
,08-28 10:33:25.213   872  1301 E native  : do suspend false
,08-28 10:33:25.241   872  2345 D DhcpClient: Broadcasting DHCPDISCOVER
,08-28 10:33:25.281   872  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-28 10:33:25.283   872  2345 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-28 10:33:25.286   872  2345 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-28 10:33:25.326   872  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-28 10:33:25.328   872  2345 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-28 10:33:25.332   372   870 D CommandListener: Setting iface cfg
,08-28 10:33:25.345   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-28 10:33:25.346   872  2345 D DhcpClient: Scheduling renewal in 86399s
,08-28 10:33:25.349   872  1301 E native  : do suspend true
,08-28 10:33:25.380   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-28 10:33:25.385   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-28 10:33:25.387   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-28 10:33:25.389   872  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-28 10:33:25.406   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-28 10:33:25.453   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-28 10:33:25.453   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-28 10:33:25.456   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-28 10:33:25.458   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-28 10:33:25.459   872  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-28 10:33:25.478   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-28 10:33:25.487   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-28 10:33:25.487   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-28 10:33:25.487   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-28 10:33:25.487   872  1303 D ConnectivityService:    accepting network in place of null
,08-28 10:33:25.488   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-28 10:33:25.489   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-28 10:33:25.491   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-28 10:33:25.512   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=200654, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-28 10:33:25.520   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:33:25.579   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-28 10:33:25.588   872  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.201.238,2a00:1450:400d:807::200e
,08-28 10:33:25.587   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-28 10:33:25.589   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-28 10:33:25.596   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-28 10:33:25.598   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:33:25.616  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:33:25.618  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:33:25.625  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:33:25.625  3768  3768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:33:25.628  3768  3768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:33:25.636  1717  1717 D SystemUpdateService: onCreate
,08-28 10:33:25.643  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-28 10:33:25.660  3721  4221 I BooksSync: Starting books sync for 61035162, extras: ade
,08-28 10:33:25.666  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-28 10:33:25.674  1717  4220 I SystemUpdateService: active receiver: enabled
,08-28 10:33:25.676   872  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 28 Aug 2016 08:33:25 GMT], X-Android-Received-Millis=[1472373205676], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472373205639]}
08-28 10:33:25.677   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-28 10:33:25.677   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-28 10:33:25.677   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-28 10:33:25.678  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-28 10:33:25.679   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-28 10:33:25.675  1717  2536 I iu.UploadsManager: num queued entries: 0
,08-28 10:33:25.681  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-28 10:33:25.683  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-28 10:33:25.687  1717  4223 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-28 10:33:25.687  1717  4223 W BaseAppContext: Using Auth Proxy for data requests.
,08-28 10:33:25.692  1717  4223 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-28 10:33:25.693  3904  3904 D SprintDMHelper: simOperator: 
,08-28 10:33:25.693  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-28 10:33:25.696  1717  4220 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-28 10:33:25.703  1717  2536 I iu.UploadsManager: num updated entries: 0
08-28 10:33:25.704  1717  2536 I iu.SyncManager: NEXT; no task
,08-28 10:33:25.713  1717  4220 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-28 10:33:25.714  1717  4220 I SystemUpdateService: now status is 0 (complete)
08-28 10:33:25.714  1717  4220 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-28 10:33:25.714  1717  4220 I SystemUpdateService: file has been verified
,08-28 10:33:25.727  1717  4220 I SystemUpdateService: OTA package size = 12249756
,08-28 10:33:25.766  1717  4220 I SystemUpdateService: showing system update notification
,08-28 10:33:25.774  3721  4231 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-28 10:33:25.803  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-28 10:33:25.803  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-28 10:33:25.803  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:25.803  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:25.816  2248  4227 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-28 10:33:25.849  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-28 10:33:25.849  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-28 10:33:25.849  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:25.849  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:25.858  3721  4231 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-28 10:33:25.859  3721  4221 E BooksSync: Soft error
08-28 10:33:25.859  3721  4221 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:33:25.859  3721  4221 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-28 10:33:25.859  3721  4221 E BooksSync: Sync error
08-28 10:33:25.859  3721  4221 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:33:25.859  3721  4221 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-28 10:33:25.859  3721  4221 I BooksSync: Finished books sync
,08-28 10:33:25.863   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198477, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:33:25.880  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-28 10:33:25.880  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-28 10:33:25.880  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:25.880  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:25.881  1717  1717 D SystemUpdateService: onDestroy
,08-28 10:33:25.902  1717  4223 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-28 10:33:25.905  3029  4219 V KeepSync: Connecting to GoogleApiClient
08-28 10:33:25.905   872  2209 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 10:33:25.961  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-28 10:33:25.961  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-28 10:33:25.961  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:25.961  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:25.980  1717  4234 V BaseAuthAsyncOperation: access token request failed
,08-28 10:33:25.981  3029  4219 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 10:33:26.048  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 10:33:26.048  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-28 10:33:26.048  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:26.048  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:26.073  3029  4219 E KeepSync: IOException
08-28 10:33:26.073  3029  4219 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 10:33:26.073  3029  4219 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:33:26.073  3029  4219 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 10:33:26.073  3029  4219 E KeepSync: 	... 10 more
,08-28 10:33:26.073  3029  4219 W KeepSync: Sync result 2
,08-28 10:33:26.096   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198080, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:33:26.587   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:33:27.756  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:33:27.763  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-28 10:33:27.765  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:33:27.765  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee5875b removed from the list
08-28 10:33:27.766  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:27.766  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:33:27.766  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:27.781  3768  4237 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-28 10:33:27.781  3768  4237 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-28 10:33:30.789  3768  4238 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-28 10:33:30.790  3768  4237 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-28 10:33:30.790  3768  4237 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-28 10:33:30.790  3768  4238 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-28 10:33:30.792  3768  4237 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 10:33:30.792  3768  4238 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 10:33:30.794  3768  4237 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-28 10:33:30.794  3768  4238 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 10:33:30.796  3768  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: IncomingSocketThread/Sender)
08-28 10:33:30.797  3768  4238 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-28 10:33:30.798  3768  4237 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-28 10:33:30.800  3768  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: OutgoingSocketThread/Sender)
,08-28 10:33:30.804  3768  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: OutgoingSocketThread/Receiver)
08-28 10:33:30.805  3768  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: IncomingSocketThread/Receiver)
,08-28 10:33:30.806  3768  4243 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 420, thread name: OutgoingSocketThread/Receiver)
08-28 10:33:30.806  3768  4243 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-28 10:33:30.806  3768  4243 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-28 10:33:30.807  3768  4242 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: IncomingSocketThread/Receiver)
08-28 10:33:30.807  3768  4242 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-28 10:33:30.808  3768  4242 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-28 10:33:33.495   872  1303 D ConnectivityService: handlePromptUnvalidated 102
,08-28 10:33:33.788  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-28 10:33:33.790  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-28 10:33:33.797  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@13001c6 Bundle[{}]
,08-28 10:33:33.798  3768  3816 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-28 10:33:33.798  3768  3816 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-28 10:33:33.799  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-28 10:33:33.799  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-28 10:33:33.800  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-28 10:33:33.800  3768  3816 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-28 10:33:33.805  3768  3816 I System.out: Running OutgoingSocketThread
,08-28 10:33:33.810  3768  4244 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-28 10:33:33.810  3768  4244 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-28 10:33:35.009  1861  2837 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-28 10:33:35.009  1861  2837 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-28 10:33:35.053  1504  1504 I ConfigService: onCreate
,08-28 10:33:36.819  3768  4246 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-28 10:33:36.819  3768  4246 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-28 10:33:36.820  3768  4246 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 10:33:36.820  3768  4244 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-28 10:33:36.821  3768  4244 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-28 10:33:36.822  3768  4246 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-28 10:33:36.823  3768  4246 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-28 10:33:36.823  3768  4244 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-28 10:33:36.830  3768  4248 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Sender)
,08-28 10:33:36.831  3768  4244 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-28 10:33:36.835  3768  4249 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Receiver)
,08-28 10:33:36.835  3768  4244 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-28 10:33:36.836  3768  4250 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Sender)
,08-28 10:33:36.838  3768  4249 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: IncomingSocketThread/Receiver)
08-28 10:33:36.838  3768  4249 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-28 10:33:36.839  3768  4249 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-28 10:33:36.840  3768  4251 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Receiver)
,08-28 10:33:36.841  3768  4251 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: OutgoingSocketThread/Receiver)
08-28 10:33:36.841  3768  4251 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-28 10:33:36.842  3768  4251 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-28 10:33:39.820  3768  3816 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-28 10:33:39.822  3768  3816 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-28 10:33:39.823  3768  3816 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-28 10:33:39.830  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-28 10:33:39.831  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a8bf8 added. We now have 3 listener(s)
08-28 10:33:39.832  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 10:33:39.833  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-28 10:33:39.833  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 10:33:39.833  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:33:39.833  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10358d1 added. We now have 4 listener(s)
08-28 10:33:39.833  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:33:39.834  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 10:33:39.837  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:33:39.845  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:33:39.848  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:39.849  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 10:33:39.849  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:33:39.849  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:33:39.849  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:33:39.850  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:33:39.850  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:39.850  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:33:39.850  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 10:33:39.850  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a8bf8 removed from the list
08-28 10:33:39.850  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:39.850  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10358d1 removed from the list
,08-28 10:33:39.855  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:39.860  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-28 10:33:39.861  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:39.861  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:39.862  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:39.862  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:33:39.864  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 10:33:39.864  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:33:39.864  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:39.864  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10358d1 not in the list
08-28 10:33:39.864  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:39.864  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:39.865  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:33:39.865  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:33:39.865  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:39.865  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10358d1 not in the list
08-28 10:33:39.866  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:33:39.866  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:39.866  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:33:39.866  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a8bf8 not in the list
08-28 10:33:39.867  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 10:33:39.867  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7eb3e37 added. We now have 3 listener(s)
08-28 10:33:39.869  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 10:33:39.869  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 10:33:39.869  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 10:33:39.869  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:33:39.869  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a86fa4 added. We now have 4 listener(s)
08-28 10:33:39.869  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-28 10:33:39.870  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-28 10:33:39.873  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-28 10:33:39.882  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:33:39.884  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:39.884  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 10:33:39.884  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-28 10:33:39.884  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-28 10:33:39.884  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-28 10:33:39.884  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 10:33:39.885  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-28 10:33:39.897  3768  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-28 10:33:39.897  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-28 10:33:39.899  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:39.904  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 10:33:39.906  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-28 10:33:39.906  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-28 10:33:39.908  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:39.918  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-28 10:33:39.918  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-28 10:33:39.919  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-28 10:33:39.921  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:33:39.930  4151  4191 D BtGatt.GattService: registerClient() - UUID=dda4a266-c867-43f3-a580-fc6808ed7db1
,08-28 10:33:39.932  4151  4167 D BtGatt.GattService: onClientRegistered() - UUID=dda4a266-c867-43f3-a580-fc6808ed7db1, clientIf=5
,08-28 10:33:39.934  3768  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-28 10:33:39.937  4151  4161 D BtGatt.GattService: start scan with filters
,08-28 10:33:39.948  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-28 10:33:39.949  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-28 10:33:39.949  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-28 10:33:39.949  4151  4170 D BtGatt.ScanManager: handling starting scan
,08-28 10:33:39.949  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-28 10:33:39.955  4151  4170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@993dffa
,08-28 10:33:39.963  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 10:33:39.963  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-28 10:33:39.963  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-28 10:33:39.970  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 10:33:39.975  4151  4167 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-28 10:33:39.975  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:33:39.977  4151  4170 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-28 10:33:39.982  3768  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-28 10:33:39.982  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-28 10:33:39.982  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-28 10:33:39.982  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:39.982  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-28 10:33:39.982  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 10:33:39.982  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-28 10:33:39.982  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 10:33:39.982  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-28 10:33:39.983  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-28 10:33:39.983  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-28 10:33:39.991  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:33:39.994  4151  4191 D BtGatt.GattService: stopScan() - queue size =1
,08-28 10:33:39.996  4151  4161 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-28 10:33:39.997  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-28 10:33:39.997  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-28 10:33:39.997  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-28 10:33:39.998  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-28 10:33:39.998  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-28 10:33:39.998  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:33:39.998  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-28 10:33:39.998  4151  4170 D BtGatt.ScanManager: Starting BLE batch scan
08-28 10:33:39.998  4151  4170 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-28 10:33:40.002  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-28 10:33:40.002  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 10:33:40.002  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-28 10:33:40.002  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 10:33:40.003  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:33:40.005  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 10:33:40.005  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-28 10:33:40.005  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:33:40.028  4151  4167 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-28 10:33:40.029  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:33:40.036  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-28 10:33:40.037  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:33:40.049  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-28 10:33:40.049  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:33:40.050  4151  4170 D BtGatt.ScanManager: stopping BLe Batch
,08-28 10:33:40.061  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-28 10:33:40.062  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-28 10:33:40.062  4151  4170 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-28 10:33:40.073  4151  4167 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-28 10:33:40.073  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-28 10:33:40.126  1504  1504 I ConfigService: onDestroy
,08-28 10:33:40.507  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-28 10:33:40.507  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:33:40.508  3768  3768 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 10:33:43.006  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:33:43.007  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-28 10:33:43.007  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-28 10:33:43.008  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:33:43.009  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:43.009  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-28 10:33:43.009  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 10:33:43.010  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7eb3e37 removed from the list
08-28 10:33:43.010  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:43.010  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a86fa4 removed from the list
08-28 10:33:43.011  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:43.011  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:43.013  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:43.013  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:43.017  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 10:33:43.018  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:33:43.018  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:43.018  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a86fa4 not in the list
08-28 10:33:43.018  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:33:43.019  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:33:43.022  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-28 10:33:43.022  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:33:43.023  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:43.023  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a86fa4 not in the list
08-28 10:33:43.023  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:33:43.024  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:33:43.024  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-28 10:33:43.024  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7eb3e37 not in the list
,08-28 10:33:43.026  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 10:33:43.026  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4575109 added. We now have 3 listener(s)
,08-28 10:33:43.028  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 10:33:43.028  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-28 10:33:43.028  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 10:33:43.028  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-28 10:33:43.028  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d46f0e added. We now have 4 listener(s)
08-28 10:33:43.029  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:33:43.029  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 10:33:43.033  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-28 10:33:43.038  3768  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-28 10:33:43.041  3768  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-28 10:33:43.042  3768  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-28 10:33:43.042  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-28 10:33:43.044  3768  3816 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-28 10:33:43.044  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-28 10:33:43.046  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:43.048  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-28 10:33:43.048  3768  3768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-28 10:33:43.048  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-28 10:33:43.048  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-28 10:33:43.049  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:33:43.049  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-28 10:33:43.050  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-28 10:33:43.050  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-28 10:33:43.050  3768  3768 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-28 10:33:43.051  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-28 10:33:43.051  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-28 10:33:43.051  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-28 10:33:43.052  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-28 10:33:43.058  3768  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-28 10:33:43.058  3768  4253 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-28 10:33:43.058  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-28 10:33:43.061  3768  4253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-28 10:33:43.069  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-28 10:33:43.070  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-28 10:33:43.070  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-28 10:33:43.073  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-28 10:33:43.073  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-28 10:33:43.074  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-28 10:33:43.075  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-28 10:33:43.075  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-28 10:33:43.075  3768  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-28 10:33:43.076  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:33:43.079  4151  4187 D BtGatt.GattService: registerClient() - UUID=1de12178-64a0-4da3-acce-05a28e566de7
,08-28 10:33:43.080  4151  4167 D BtGatt.GattService: onClientRegistered() - UUID=1de12178-64a0-4da3-acce-05a28e566de7, clientIf=5
,08-28 10:33:43.080  3768  3838 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-28 10:33:43.083  4151  4169 D BtGatt.AdvertiseManager: message : 0
,08-28 10:33:43.087  4151  4169 D BtGatt.AdvertiseManager: starting multi advertising
,08-28 10:33:43.099  4151  4167 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-28 10:33:43.109  4151  4167 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-28 10:33:43.110  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-28 10:33:43.111  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-28 10:33:43.114  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-28 10:33:43.115  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-28 10:33:43.116  3768  3768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-28 10:33:43.116  3768  3768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-28 10:33:43.116  3768  3768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-28 10:33:43.116  3768  3768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-28 10:33:43.116  3768  3768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-28 10:33:43.118  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-28 10:33:43.121  3768  3768 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-28 10:33:43.121  3768  3768 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-28 10:33:43.621  3768  3768 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-28 10:33:43.622  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-28 10:33:43.622  3768  3768 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-28 10:33:46.120  3768  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-28 10:33:46.120  3768  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-28 10:33:46.121  3768  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-28 10:33:46.121  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-28 10:33:46.122  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-28 10:33:46.122  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-28 10:33:46.123  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-28 10:33:46.123  3768  4253 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-28 10:33:46.123  3768  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-28 10:33:46.125  3768  4253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-28 10:33:46.125  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-28 10:33:46.125  3768  3768 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-28 10:33:46.125  3768  4253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-28 10:33:46.125  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-28 10:33:46.125  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-28 10:33:46.125  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-28 10:33:46.126  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-28 10:33:46.130  3768  3816 D BluetoothAdapter: STATE_ON
,08-28 10:33:46.131  3768  3816 D BluetoothLeScanner: could not find callback wrapper
08-28 10:33:46.132  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-28 10:33:46.132  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-28 10:33:46.135  4151  4169 D BtGatt.AdvertiseManager: message : 1
08-28 10:33:46.137  4151  4169 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-28 10:33:46.159  4151  4167 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-28 10:33:46.159  4151  4167 D BtGatt.GattService: Client app is not null!
08-28 10:33:46.161  4151  4192 D BtGatt.GattService: unregisterClient() - clientIf=5
08-28 10:33:46.162  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-28 10:33:46.162  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-28 10:33:46.163  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-28 10:33:46.163  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-28 10:33:46.163  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-28 10:33:46.167  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-28 10:33:46.167  3768  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-28 10:33:46.167  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-28 10:33:46.168  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 10:33:46.171  3768  3768 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-28 10:33:46.171  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:33:46.171  3768  3768 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-28 10:33:46.171  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:46.171  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-28 10:33:46.172  3768  3768 D AndroidRuntime: Shutting down VM
08-28 10:33:46.172  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-28 10:33:46.172  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4575109 removed from the list
08-28 10:33:46.172  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:33:46.172  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d46f0e removed from the list
08-28 10:33:46.173  3768  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-28 10:33:46.173  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
--------- beginning of crash
08-28 10:33:46.173  3768  3768 E AndroidRuntime: FATAL EXCEPTION: main
08-28 10:33:46.173  3768  3768 E AndroidRuntime: Process: com.test.thalitest, PID: 3768
08-28 10:33:46.173  3768  3768 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:33:46.173  3768  3768 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-28 10:33:46.178  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-28 10:33:46.178  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:46.180   872  1369 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity,
08-28 10:33:46.180  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-28 10:33:46.181  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:33:46.181  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-28 10:33:46.181  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d46f0e not in the list
08-28 10:33:46.181  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:33:46.181  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:46.183  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-28 10:33:46.183  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-28 10:33:46.183  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-28 10:33:46.184  3768  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d46f0e not in the list
08-28 10:33:46.184  3768  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-28 10:33:46.184  3768  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-28 10:33:46.185   872  1369 I ActivityManager: Killing 3661:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-28 10:33:46.184  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-28 10:33:46.189  3768  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4575109 not in the list
,08-28 10:33:46.191  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-28 10:33:46.191  3768  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@652fd4b added. We now have 3 listener(s)
08-28 10:33:46.195  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-28 10:33:46.195  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-28 10:33:46.196  3768  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-28 10:33:46.197  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-28 10:33:46.198  3768  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d84e328 added. We now have 4 listener(s)
08-28 10:33:46.198  3768  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-28 10:33:46.199  3768  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-28 10:33:46.282   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{d4c297c u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{635ef4e 3768 com.test.thalitest/10000/u0 remote:5c9aa49}: process crashing
08-28 10:33:46.283   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{ff9a205 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{635ef4e 3768 com.test.thalitest/10000/u0 remote:5c9aa49}: process crashing
,08-28 10:33:46.283  3768  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-28 10:33:46.287  3768  3768 I Process : Sending signal. PID: 3768 SIG: 9
,08-28 10:33:46.401   872  1302 D WifiService: Client connection lost with reason: 4
,08-28 10:33:46.401   872   882 I WindowState: WIN DEATH: Window{4f826a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-28 10:33:46.405   872  1961 D GraphicsStats: Buffer count: 2
,08-28 10:33:46.431   872  1694 I ActivityManager: Process com.test.thalitest (pid 3768) has died
,08-28 10:33:46.478   872  1907 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3768 uid 10000
,08-28 10:33:46.480  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-28 10:33:56.736  3029  4256 V KeepSync: Connecting to GoogleApiClient
08-28 10:33:56.737   872  1693 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 10:33:56.802  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:56.805  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:33:56.856  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-28 10:33:56.856  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-28 10:33:56.856  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:56.856  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:56.887  1717  4257 V BaseAuthAsyncOperation: access token request failed
,08-28 10:33:56.891  3029  4256 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 10:33:56.952  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 10:33:56.952  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-28 10:33:56.952  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:33:56.953  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:33:56.979  3029  4256 E KeepSync: IOException
08-28 10:33:56.979  3029  4256 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 10:33:56.979  3029  4256 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:33:56.979  3029  4256 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 10:33:56.979  3029  4256 E KeepSync: 	... 10 more
08-28 10:33:56.979  3029  4256 W KeepSync: Sync result 2
,08-28 10:33:56.995   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 231707, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,08-28 10:34:04.875   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=240017, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:34:27.263  3721  4259 I BooksSync: Starting books sync for 61035162, extras: ade
,08-28 10:34:27.367  3721  4262 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-28 10:34:27.391  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:34:27.393  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:34:27.481  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-28 10:34:27.481  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 10:34:27.481  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:34:27.481  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:34:27.501  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:34:27.501  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-28 10:34:27.501  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:34:27.501  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:34:27.523  3003  4261 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-28 10:34:27.523  3003  4261 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at blb.a(PG:3937)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at czp.a(PG:18188)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:34:27.523  3003  4261 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	... 12 more
08-28 10:34:27.523  3003  4261 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at fal.a(PG:38)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:34:27.523  3003  4261 E HttpOperation: 	... 14 more
,08-28 10:34:27.601  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-28 10:34:27.601  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-28 10:34:27.602  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:34:27.602  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:34:27.647  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:34:27.647  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:34:27.648  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:34:27.648  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:34:27.689  3003  4261 E HttpOperation: [getmobileexperiments] Unexpected exception
08-28 10:34:27.689  3003  4261 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at hec.a(PG:42)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at hee.a(PG:102)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at czr.a(PG:65)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at kka.a(PG:108)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at czp.a(PG:19176),
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:34:27.689  3003  4261 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	... 15 more
08-28 10:34:27.689  3003  4261 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at fal.a(PG:38)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:34:27.689  3003  4261 E HttpOperation: 	... 17 more
,08-28 10:34:27.689  3003  4261 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-28 10:34:27.689  3003  4261 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jdm.a(PG:82)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jcs.o(PG:406)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jcn.a(PG:1379)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jcs.i(PG:143)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at hec.a(PG:42)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at hee.a(PG:102)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at czr.a(PG:65)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at kka.a(PG:108)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at czp.a(PG:19176)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at czp.a(PG:9081)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at czq.run(PG:1686)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jdj.a(PG:4091)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jdj.a(PG:1125)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jdm.a(PG:77)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	... 15 more
08-28 10:34:27.689  3003  4261 E ExperimentLoader: Caused by: faj: BadAuthentication
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at fal.a(PG:38)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	at jdj.a(PG:4089)
08-28 10:34:27.689  3003  4261 E ExperimentLoader: 	... 17 more
08-28 10:34:27.690  3721  4262 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:34:27.691  3721  4259 E BooksSync: Soft error
08-28 10:34:27.691  3721  4259 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:34:27.691  3721  4259 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-28 10:34:27.691  3721  4259 E BooksSync: Sync error
08-28 10:34:27.691  3721  4259 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:34:27.691  3721  4259 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-28 10:34:27.691  3721  4259 I BooksSync: Finished books sync
,08-28 10:34:27.706   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 233332, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:34:27.823   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 247256, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:34:31.071   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=266212, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-28 10:34:46.522  1861  2837 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-28 10:34:46.523  1861  2837 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-28 10:34:46.556  1504  1504 I ConfigService: onCreate
,08-28 10:34:51.627  1504  1504 I ConfigService: onDestroy
,08-28 10:34:58.100  3029  4270 V KeepSync: Connecting to GoogleApiClient
,08-28 10:34:58.101   872  1962 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 10:34:58.164  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:34:58.167  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:34:58.204  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-28 10:34:58.204  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-28 10:34:58.204  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:34:58.204  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:34:58.248  1717  4271 V BaseAuthAsyncOperation: access token request failed
,08-28 10:34:58.249  3029  4270 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 10:34:58.331  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 10:34:58.331  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-28 10:34:58.331  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:34:58.331  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:34:58.366  3029  4270 E KeepSync: IOException
08-28 10:34:58.366  3029  4270 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 10:34:58.366  3029  4270 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:34:58.366  3029  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 10:34:58.366  3029  4270 E KeepSync: 	... 10 more
,08-28 10:34:58.366  3029  4270 W KeepSync: Sync result 2
08-28 10:34:58.381   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 293074, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:35:09.977   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305118, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:35:26.105  1504  2030 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-28 10:35:28.738  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:28.740  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:28.768  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:35:28.768  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:35:28.768  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:35:28.769  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:35:28.774   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323916, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-28 10:35:28.788  3003  4276 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-28 10:35:28.788  3003  4276 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at blb.a(PG:3937)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at czp.a(PG:18188)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:35:28.788  3003  4276 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	... 12 more
08-28 10:35:28.788  3003  4276 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at fal.a(PG:38)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:35:28.788  3003  4276 E HttpOperation: 	... 14 more
,08-28 10:35:28.881  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-28 10:35:28.881  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:35:28.881  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:35:28.881  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:35:28.909  3003  4276 E HttpOperation: [getmobileexperiments] Unexpected exception
08-28 10:35:28.909  3003  4276 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at hec.a(PG:42)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at hee.a(PG:102)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at czr.a(PG:65)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at kka.a(PG:108)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at czp.a(PG:19176)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at czq.run(PG:1686),
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:35:28.909  3003  4276 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	... 15 more
08-28 10:35:28.909  3003  4276 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at fal.a(PG:38)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:35:28.909  3003  4276 E HttpOperation: 	... 17 more
,08-28 10:35:28.909  3003  4276 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-28 10:35:28.909  3003  4276 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jdm.a(PG:82)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jcs.o(PG:406)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	,at jcn.a(PG:1379)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jcs.i(PG:143)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at hec.a(PG:42)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at hee.a(PG:102)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at czr.a(PG:65)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at kka.a(PG:108)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at czp.a(PG:19176)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at czp.a(PG:9081)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at czq.run(PG:1686)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jdj.a(PG:4091)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jdj.a(PG:1125)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jdm.a(PG:77)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	... 15 more
08-28 10:35:28.909  3003  4276 E ExperimentLoader: Caused by: faj: BadAuthentication
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at fal.a(PG:38)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	at jdj.a(PG:4089)
08-28 10:35:28.909  3003  4276 E ExperimentLoader: 	... 17 more
,08-28 10:35:29.032   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 293796, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:35:47.056  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:47.072  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:47.076  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:47.129  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-28 10:35:47.129  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-28 10:35:47.130  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:35:47.130  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:35:47.162  1504  2437 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-28 10:35:47.162  1504  2437 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-28 10:35:47.162  1504  2437 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-28 10:35:47.162  1504  2437 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-28 10:35:47.162  1504  2437 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-28 10:35:47.162  1504  2437 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-28 10:35:47.162  1504  2437 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-28 10:35:47.172  3507  3538 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-28 10:35:47.172  3507  3538 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-28 10:35:47.172  3507  3538 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-28 10:35:47.172  3507  3538 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-28 10:35:47.172  3507  3538 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-28 10:35:47.172  3507  3538 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-28 10:35:47.172  3507  3538 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-28 10:35:59.121  3721  4282 I BooksSync: Starting books sync for 61035162, extras: ade
,08-28 10:35:59.157  3721  4283 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-28 10:35:59.172  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:59.175  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:59.205  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-28 10:35:59.205  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 10:35:59.205  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:35:59.205  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:35:59.232  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:59.235  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:35:59.264  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-28 10:35:59.264  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.,
08-28 10:35:59.264  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:35:59.265  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:35:59.287  3721  4283 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-28 10:35:59.288  3721  4282 E BooksSync: Soft error
08-28 10:35:59.288  3721  4282 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:35:59.288  3721  4282 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-28 10:35:59.288  3721  4282 E BooksSync: Sync error
08-28 10:35:59.288  3721  4282 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:35:59.288  3721  4282 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-28 10:35:59.289  3721  4282 I BooksSync: Finished books sync
,08-28 10:35:59.301   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 327502, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:36:26.350   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381492, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:36:31.082  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:36:31.084  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:36:31.116  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:36:31.116  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:36:31.116  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:36:31.117  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:36:31.139  3003  4287 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-28 10:36:31.139  3003  4287 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at blb.a(PG:3937)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at czp.a(PG:18188)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:36:31.139  3003  4287 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	... 12 more
08-28 10:36:31.139  3003  4287 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at fal.a(PG:38)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:36:31.139  3003  4287 E HttpOperation: 	... 14 more
,08-28 10:36:31.195  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:36:31.195  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:36:31.195  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:36:31.195  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:36:31.222  3003  4287 E HttpOperation: [getmobileexperiments] Unexpected exception
08-28 10:36:31.222  3003  4287 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at hec.a(PG:42)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at hee.a(PG:102)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at czr.a(PG:65)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at kka.a(PG:108)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at czp.a(PG:19176)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423),
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:36:31.222  3003  4287 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	... 15 more
08-28 10:36:31.222  3003  4287 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at fal.a(PG:38)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:36:31.222  3003  4287 E HttpOperation: 	... 17 more
,08-28 10:36:31.223  3003  4287 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-28 10:36:31.223  3003  4287 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jdm.a(PG:82)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jcs.o(PG:406)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jcn.a(PG:1379)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jcs.i(PG:143)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at hec.a(PG:42)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at hee.a(PG:102)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at czr.a(PG:65)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at kka.a(PG:108)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at czp.a(PG:19176)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at czp.a(PG:9081)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at czq.run(PG:1686)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jdj.a(PG:4091)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jdj.a(PG:1125)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jdm.a(PG:77)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	... 15 more
08-28 10:36:31.223  3003  4287 E ExperimentLoader: Caused by: faj: BadAuthentication
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at fal.a(PG:38)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	at jdj.a(PG:4089)
08-28 10:36:31.223  3003  4287 E ExperimentLoader: 	... 17 more
,08-28 10:36:31.364   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 385835, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:36:55.511   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410653, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-28 10:37:01.527  3029  4290 V KeepSync: Connecting to GoogleApiClient
08-28 10:37:01.528   872  2209 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-28 10:37:01.585  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:37:01.590  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:37:01.651  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-28 10:37:01.652  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-28 10:37:01.652  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:37:01.653  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:37:01.689  1717  4291 V BaseAuthAsyncOperation: access token request failed
,08-28 10:37:01.690  3029  4290 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-28 10:37:01.763  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-28 10:37:01.763  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-28 10:37:01.763  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:37:01.763  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:37:01.788  3029  4290 E KeepSync: IOException
08-28 10:37:01.788  3029  4290 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-28 10:37:01.788  3029  4290 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-28 10:37:01.788  3029  4290 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-28 10:37:01.788  3029  4290 E KeepSync: 	... 10 more
,08-28 10:37:01.788  3029  4290 W KeepSync: Sync result 2
,08-28 10:37:01.801   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 415395, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:37:28.826  1504  2030 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-28 10:37:34.402   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:38:08.672  3721  4294 I BooksSync: Starting books sync for 61035162, extras: ade
,08-28 10:38:08.697  3721  4295 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-28 10:38:08.710  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:38:08.717  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:38:08.752  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-28 10:38:08.752  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 10:38:08.752  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:38:08.752  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:38:08.791  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:38:08.793  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:38:08.818  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-28 10:38:08.818  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-28 10:38:08.818  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:38:08.818  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:38:08.866  3721  4295 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:38:08.870  3721  4294 E BooksSync: Soft error
08-28 10:38:08.870  3721  4294 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:38:08.870  3721  4294 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-28 10:38:08.870  3721  4294 E BooksSync: Sync error
08-28 10:38:08.870  3721  4294 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-28 10:38:08.870  3721  4294 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-28 10:38:08.870  3721  4294 I BooksSync: Finished books sync
,08-28 10:38:08.885   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 483751, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:38:30.699   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=505840, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-28 10:38:39.258  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:38:39.263  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:38:39.308  1504  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:38:39.308  1504  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-28 10:38:39.308  1504  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:38:39.308  1504  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:38:39.335  3003  4298 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-28 10:38:39.335  3003  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at blb.a(PG:3937)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at czp.a(PG:18188)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:38:39.335  3003  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	... 12 more
08-28 10:38:39.335  3003  4298 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at fal.a(PG:38)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:38:39.335  3003  4298 E HttpOperation: 	... 14 more
,08-28 10:38:39.443  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-28 10:38:39.443  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-28 10:38:39.443  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:38:39.444  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:38:39.464  3003  4298 E HttpOperation: [getmobileexperiments] Unexpected exception
08-28 10:38:39.464  3003  4298 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jdm.a(PG:82)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jcs.o(PG:406)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jcn.a(PG:1379)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jcs.i(PG:143)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at hec.a(PG:42)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at hee.a(PG:102)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at czr.a(PG:65)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at kka.a(PG:108)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at czp.a(PG:19176)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at czp.a(PG:9081)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at czq.run(PG:1686)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:38:39.464  3003  4298 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jdj.a(PG:4091)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jdj.a(PG:1125)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jdm.a(PG:77)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	... 15 more
08-28 10:38:39.464  3003  4298 E HttpOperation: Caused by: faj: BadAuthentication
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at fal.a(PG:38)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	at jdj.a(PG:4089)
08-28 10:38:39.464  3003  4298 E HttpOperation: 	... 17 more
,08-28 10:38:39.464  3003  4298 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-28 10:38:39.464  3003  4298 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jdm.a(PG:82)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jcs.o(PG:406)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jcn.a(PG:1379)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jcs.i(PG:143)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at hec.a(PG:42)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at hee.a(PG:102)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at czr.a(PG:65)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at kka.a(PG:108)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at czp.a(PG:19176)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at czp.a(PG:9081)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at czq.run(PG:1686)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jdj.a(PG:4091)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jdj.a(PG:1125)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jdm.a(PG:77)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	... 15 more
08-28 10:38:39.464  3003  4298 E ExperimentLoader: Caused by: faj: BadAuthentication
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at fal.a(PG:38)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	at jdj.a(PG:4089)
08-28 10:38:39.464  3003  4298 E ExperimentLoader: 	... 17 more
,08-28 10:38:39.633   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 509827, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-28 10:39:09.551   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=544692, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:39:33.978   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=569119, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-28 10:40:12.910   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=608052, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:40:34.111  3507  3507 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-28 10:40:34.139  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:34.148  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:34.151  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:34.192  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-28 10:40:34.192  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-28 10:40:34.193  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:40:34.193  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:40:34.218  3507  3507 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-28 10:40:34.232  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:34.291  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-28 10:40:34.292  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-28 10:40:34.292  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:40:34.293  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:40:34.383  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:34.464  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-28 10:40:34.464  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-28 10:40:34.465  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:40:34.466  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:40:34.531  3507  3507 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-28 10:40:34.884  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:34.930  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-28 10:40:34.931  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-28 10:40:34.931  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:40:34.931  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:40:34.980  3507  3507 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-28 10:40:34.981  3507  3507 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-28 10:40:34.985  3507  3507 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-28 10:40:34.993  3507  3561 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-28 10:40:34.997  3507  3507 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,08-28 10:40:49.861  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:49.878  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:49.884  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:40:49.969  1504  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:40:49.969  1504  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 10:40:49.970  1504  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:40:49.970  1504  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:40:50.040  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:40:50.041  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:40:50.043  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-28 10:40:52.535   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-28 10:41:10.374  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:10.385  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:10.391  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:10.451  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:41:10.452  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 10:41:10.452  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:41:10.452  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:41:10.497  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:41:10.498  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:41:10.499  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-28 10:41:30.819  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:30.836  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:30.843  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-28 10:41:30.931  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:41:30.931  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-28 10:41:30.932  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:41:30.932  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:41:30.989  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:41:30.990  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:41:30.992  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-28 10:41:31.418   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=686560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-28 10:41:51.309  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:51.321  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:51.324  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:41:51.390  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:41:51.390  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 10:41:51.391  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:41:51.391  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:41:51.447  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:41:51.448  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:41:51.449  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-28 10:42:11.675  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:42:11.684  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:42:11.686  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:42:11.721  1504  2200 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:42:11.721  1504  2200 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-28 10:42:11.721  1504  2200 I GLSUser : [GLSUser] Extracting token using key: Auth
08-28 10:42:11.721  1504  2200 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:42:11.750  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:42:11.750  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:42:11.750  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-28 10:42:31.965  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:42:31.976  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:42:31.982  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-28 10:42:32.021  1504  2437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-28 10:42:32.021  1504  2437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-28 10:42:32.022  1504  2437 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-28 10:42:32.022  1504  2437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-28 10:42:32.088  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-28 10:42:32.088  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-28 10:42:32.088  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-28 10:42:32.130   872   881 I art     : Background partial concurrent mark sweep GC freed 37177(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 5.280ms total 95.819ms
,08-28 10:42:34.553  1504  2030 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-28 10:50:22.860   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-28 10:55:30.046  4354  4354 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-28 10:55:30.051  4354  4354 D AndroidRuntime: CheckJNI is OFF
08-28 10:55:30.086  4354  4354 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-28 10:55:30.127  4354  4354 I Radio-JNI: register_android_hardware_Radio DONE
08-28 10:55:30.147  4354  4354 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-28 10:55:30.161   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-28 10:55:30.291   872   895 W PackageSettings: Skipping PackageSetting{2a16f1f com.example.hello/10273} due to missing metadata
08-28 10:55:30.318   872   895 I art     : Starting a blocking GC Explicit
08-28 10:55:30.392   872   895 I art     : Explicit concurrent mark sweep GC freed 21349(1406KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 753us total 73.322ms
08-28 10:55:30.416   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-28 10:55:30.419  4354  4354 I art     : System.exit called, status: 0
08-28 10:55:30.419  4354  4354 I AndroidRuntime: VM exiting with result code 0.
08-28 10:55:30.422   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-28 10:55:30.442  1861  1861 I Keyboard.Facilitator: resetDictionaries() : en_US
08-28 10:55:30.445  1861  4366 I Keyboard.Facilitator.DecoderInitializer: run()
08-28 10:55:30.446   872  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-28 10:55:30.451  1861  4366 I Decoder : createOrResetDecoder
08-28 10:55:30.452  4151  4151 D BluetoothMapAppObserver: onReceive
08-28 10:55:30.452  4151  4151 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-28 10:55:30.456  1884  2263 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-28 10:55:30.469  3609  3609 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-28 10:55:30.496  1944  1944 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-28 10:55:30.502   872  1907 I ActivityManager: Start proc 4369:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-28 10:55:30.506  1504  1504 I ConfigService: onCreate
08-28 10:55:30.525  1861  4366 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-28 10:55:30.554  1861  4366 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-28 10:55:30.555   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-28 10:55:30.558  4369  4369 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-28 10:55:30.559  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-28 10:55:30.559  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-28 10:55:30.561  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-28 10:55:30.561  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-28 10:55:30.563  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-28 10:55:30.563  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-28 10:55:30.565  1861  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-28 10:55:30.565  1861  4366 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-28 10:55:30.565  1861  4366 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-28 10:55:30.571  1861  4366 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-28 10:55:30.571  1861  4366 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-28 10:55:30.571  1861  4366 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-28 10:55:30.572  1955  2037 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-28 10:55:30.572   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-28 10:55:30.573   872   884 E PackageManager: Failed to write settings, restoring backup
08-28 10:55:30.573   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-28 10:55:30.573   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-28 10:55:30.573   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-28 10:55:30.573   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-28 10:55:30.573   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-28 10:55:30.573   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.573   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.573   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.579   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-28 10:55:30.579   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-28 10:55:30.579   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 10:55:30.579   872   885 E DropBoxManagerService: 	... 13 more
08-28 10:55:30.585   872  1693 I ActivityManager: Start proc 4384:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-28 10:55:30.585  1955  2037 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-28 10:55:30.585  1955  2037 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1955
08-28 10:55:30.585  1955  2037 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.585  1955  2037 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.586   872  1962 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-28 10:55:30.587   872  4391 E DropBoxManagerService: Can't write: system_app_crash
08-28 10:55:30.587   872  4391 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 10:55:30.587   872  4391 E DropBoxManagerService: 	... 5 more
08-28 10:55:30.590  1955  2037 I Process : Sending signal. PID: 1955 SIG: 9
08-28 10:55:30.609  4369  4369 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-28 10:55:30.625  4369  4401 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-28 10:55:30.627   872  2209 I ActivityManager: Start proc 4402:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-28 10:55:30.663   872  1693 D GraphicsStats: Buffer count: 1
08-28 10:55:30.663   872  2209 I WindowState: WIN DEATH: Window{d8bbe23 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-28 10:55:30.672   872  1693 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1955) has died
08-28 10:55:30.673   872  1693 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-28 10:55:30.674   872  1693 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-28 10:55:30.693   872   885 I ActivityManager: Start proc 4415:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-28 10:55:30.707  4402  4402 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.738  4369  4390 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.741  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-28 10:55:30.742  1504  1504 D AndroidRuntime: Shutting down VM
08-28 10:55:30.743  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
08-28 10:55:30.743  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
08-28 10:55:30.743  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-28 10:55:30.743  1504  1504 E AndroidRuntime: 	... 8 more
08-28 10:55:30.748   872  4432 E DropBoxManagerService: Can't write: system_app_crash
08-28 10:55:30.748   872  4432 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 10:55:30.748   872  4432 E DropBoxManagerService: 	... 5 more
08-28 10:55:30.750  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:55:30.752  4415  4415 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:55:30.752  4415  4415 D AndroidRuntime: Shutting down VM
08-28 10:55:30.759  4415  4415 E AndroidRuntime: FATAL EXCEPTION: main
08-28 10:55:30.759  4415  4415 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4415
08-28 10:55:30.759  4415  4415 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-28 10:55:30.759  4415  4415 E AndroidRuntime: 	... 10 more
08-28 10:55:30.761   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-28 10:55:30.762  4415  4415 I Process : Sending signal. PID: 4415 SIG: 9
08-28 10:55:30.765   872  4433 E DropBoxManagerService: Can't write: system_app_crash
08-28 10:55:30.765   872  4433 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 10:55:30.765   872  4433 E DropBoxManagerService: 	... 5 more
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.779  4369  4390 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.802  4369  4390 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-28 10:55:30.805   872  2209 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4415) has died
08-28 10:55:30.806   872  2209 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.811  4369  4401 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-28 10:55:30.813  4369  4401 E AndroidRuntime: Process: android.process.acore, PID: 4369
08-28 10:55:30.813  4369  4401 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.813  4369  4401 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-28 10:55:30.814  4369  4390 I Process : Sending signal. PID: 4369 SIG: 9
08-28 10:55:30.822   872   885 I ActivityManager: Start proc 4434:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-28 10:55:30.824   872  4439 E DropBoxManagerService: Can't write: system_app_crash
08-28 10:55:30.824   872  4439 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-28 10:55:30.824   872  4439 E DropBoxManagerService: 	... 5 more
08-28 10:55:30.826   872  1302 D WifiService: Client connection lost with reason: 4
08-28 10:55:30.827  1717  4430 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@dd9c37a
08-28 10:55:30.836   872  1472 I ActivityManager: Process com.google.process.gapps (pid 1504) has died
08-28 10:55:30.836   872  1472 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-28 10:55:30.836   872  1472 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-28 10:55:30.836   872  1472 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
08-28 10:55:30.855  1717  1717 W RocketImpressions: ClearcutLogger connection suspended: 1
08-28 10:55:30.856   872   882 I ActivityManager: Start proc 4447:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-28 10:55:30.880   872  1693 I ActivityManager: Process android.process.acore (pid 4369) has died
08-28 10:55:30.880   872  1693 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30956ms
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-28 10:55:30.896  4434  4434 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-28 10:55:30.896  4434  4434 D AndroidRuntime: Shutting down VM
08-28 10:55:30.897  4447  4447 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm

```
