#### Test 82914073b4ce5c2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 15:12:40.001   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-13 15:12:40.695  3766  3766 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 15:12:40.699  3766  3766 D AndroidRuntime: CheckJNI is OFF
09-13 15:12:40.739  3766  3766 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 15:12:40.805  3766  3766 I Radio-JNI: register_android_hardware_Radio DONE
09-13 15:12:40.831  3766  3766 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 15:12:40.835   874  1430 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 15:12:40.872  2005  2019 W SearchService: Abort, client detached.
09-13 15:12:40.879  2005  2005 I HotwordDetector: Closing mic
09-13 15:12:40.879  3766  3766 D AndroidRuntime: Shutting down VM
09-13 15:12:40.882  2005  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d2b7558
09-13 15:12:40.883  2005  2360 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 15:12:40.902   874   885 I ActivityManager: Start proc 3775:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 15:12:40.945   376  2362 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 15:12:40.946   376  2362 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 15:12:40.953   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 15:12:40.955  2005  2358 I MicroRecognitionRnrImpl: Detection finished
09-13 15:12:40.955  2005  2357 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 15:12:40.986  3775  3775 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 15:12:41.007  3775  3775 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 15:12:41.013  3775  3775 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7449-7452)
09-13 15:12:41.013  3775  3775 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 15:12:41.026  3775  3775 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9f6596b}
09-13 15:12:41.026  3775  3775 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 15:12:41.027  3775  3775 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 15:12:41.032  3775  3775 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 15:12:41.033  3775  3775 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 15:12:41.046  3775  3775 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 15:12:41.055  3775  3775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 15:12:41.055  3775  3775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 15:12:41.055  3775  3775 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 15:12:41.055  3775  3775 I Adreno  : Build Date                       : 10/20/15
09-13 15:12:41.055  3775  3775 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 15:12:41.055  3775  3775 I Adreno  : Local Branch                     : M14
09-13 15:12:41.055  3775  3775 I Adreno  : Remote Branch                    : 
09-13 15:12:41.055  3775  3775 I Adreno  : Remote Branch                    : 
09-13 15:12:41.055  3775  3775 I Adreno  : Reconstruct Branch               : 
09-13 15:12:41.100   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91f0c49:true
,09-13 15:12:41.144  3775  3775 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 15:12:41.155  3775  3775 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 15:12:41.209  3775  3814 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 15:12:41.218  3775  3800 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 15:12:41.251  3775  3814 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 15:12:41.339   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +463ms
,09-13 15:12:41.343  1879  1879 I Keyboard.Facilitator: onFinishInput()
,09-13 15:12:41.439  3775  3775 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3775
09-13 15:12:41.703   874  1373 I ActivityManager: Killing 3210:com.google.android.gm/u0a78 (adj 15): empty #17
09-13 15:12:41.719  3775  3775 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-13 15:12:41.764   874  1373 I ActivityManager: Killing 3094:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-13 15:12:41.895  3775  3817 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1701054160
09-13 15:12:41.900  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 15:12:41.900  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 15:12:41.900  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 15:12:41.900  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 15:12:41.900  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 15:12:41.901  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97a75ff added. We now have 1 listener(s)
09-13 15:12:41.905  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-13 15:12:41.906  3775  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:12:41.906  3775  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:12:41.907  3775  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 15:12:41.911  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c3d92a added. We now have 1 listener(s)
09-13 15:12:41.911  3775  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:12:41.913   874  1308 D WifiService: New client listening to asynchronous messages
09-13 15:12:41.914  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:12:41.914  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 15:12:41.914  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 15:12:41.915  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 15:12:41.915  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 15:12:41.917  3775  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:41.917  3775  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-13 15:12:41.922  3775  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:41.922  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:41.922  3775  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 15:12:41.922  3775  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:12:41.923  3775  3817 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 15:12:41.965  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:41.968  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:41.971  3775  3775 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 15:12:43.028   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 15:12:43.122  3775  3828 W jxcore-log: Initializing JXcore engine
,09-13 15:12:43.122  3775  3828 W jxcore-log: JXcore engine is ready
,09-13 15:12:43.155  3828  3828 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10391 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 15:12:43.155  3828  3828 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10158]" dev="sockfs" ino=10158 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 15:12:43.155  3828  3828 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
,09-13 15:12:43.155  3828  3828 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22380]" dev="sockfs" ino=22380 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 15:12:43.167  3775  3828 W jxcore-log: Starting JXcore engine
,09-13 15:12:43.242  3775  3828 W jxcore-log: Platform android
09-13 15:12:43.242  3775  3828 W jxcore-log: 
,09-13 15:12:43.242  3775  3828 W jxcore-log: Process ARCH arm
09-13 15:12:43.242  3775  3828 W jxcore-log: 
,09-13 15:12:43.425  3775  3828 I jxcore-log: JXcore Cordova bridge is ready!
09-13 15:12:43.425  3775  3828 I jxcore-log: 
,09-13 15:12:43.425  3775  3828 W jxcore-log: JXcore engine is started
,09-13 15:12:43.433  3775  3817 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 15:12:43.440  3775  3775 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 15:12:46.412   874  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 15:12:46.824   874  2098 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 15:12:49.279  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 15:12:49.282  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 15:12:49.310  1518  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 15:12:49.311  1518  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 15:12:49.311  1518  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 15:12:49.311  1518  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:12:49.339  3544  3836 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 15:12:49.339  3544  3836 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jdm.a(PG:82)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jcs.o(PG:406)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jcn.a(PG:1379)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jcs.i(PG:143)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at blb.a(PG:3937)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at czp.a(PG:18188)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at czp.a(PG:9081)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at czq.run(PG:1686)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 15:12:49.339  3544  3836 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jdj.a(PG:4091)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jdj.a(PG:1125)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jdm.a(PG:77)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	... 12 more
09-13 15:12:49.339  3544  3836 E HttpOperation: Caused by: faj: BadAuthentication
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at fal.a(PG:38)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	at jdj.a(PG:4089)
09-13 15:12:49.339  3544  3836 E HttpOperation: 	... 14 more
,09-13 15:12:49.392  1518  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 15:12:49.392  1518  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 15:12:49.392  1518  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 15:12:49.392  1518  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:12:49.410  3544  3836 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 15:12:49.410  3544  3836 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jdm.a(PG:82)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jcs.o(PG:406)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jcn.a(PG:1379)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jcs.i(PG:143)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at hec.a(PG:42)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at hee.a(PG:102)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at czr.a(PG:65)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at kka.a(PG:108)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at czp.a(PG:19176)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at czp.a(PG:9081)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at czq.run(PG:1686)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 15:12:49.410  3544  3836 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jdj.a(PG:4091)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jdj.a(PG:1125)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jdm.a(PG:77)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	... 15 more
09-13 15:12:49.410  3544  3836 E HttpOperation: Caused by: faj: BadAuthentication
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at fal.a(PG:38)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	at jdj.a(PG:4089)
09-13 15:12:49.410  3544  3836 E HttpOperation: 	... 17 more
,09-13 15:12:49.410  3544  3836 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 15:12:49.410  3544  3836 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at hec.a(PG:42)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at hee.a(PG:102)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at czr.a(PG:65)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at kka.a(PG:108)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	... 15 more
09-13 15:12:49.410  3544  3836 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at fal.a(PG:38)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 15:12:49.410  3544  3836 E ExperimentLoader: 	... 17 more
,09-13 15:12:49.509   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 124509, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 15:12:51.107  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 15:12:51.127  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 15:12:51.127  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 15:12:51.127  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 15:12:51.127  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:12:51.146  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 15:12:51.146  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 15:12:51.146  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 15:12:52.120   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 15:12:53.476  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 15:12:53.476  3775  3828 I jxcore-log: 
,09-13 15:12:53.479  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 15:12:53.479  3775  3828 I jxcore-log: 
,09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:53.492  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:53.497  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:53.499  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 15:12:53.499  3775  3828 I jxcore-log: 
,09-13 15:12:53.501  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 15:12:53.501  3775  3828 I jxcore-log: 
,09-13 15:12:54.012  3775  3828 D executeNativeTests: Running unit tests
,09-13 15:12:54.070  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 15:12:54.070  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f added. We now have 2 listener(s)
09-13 15:12:54.071  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:12:54.071  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:12:54.071  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:12:54.071  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:54.071  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c added. We now have 2 listener(s)
09-13 15:12:54.071  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:12:54.072  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:12:54.084  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:54.091  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:54.096  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:54.096  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:12:54.099  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-13 15:12:54.100  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:12:54.100  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:12:54.102  3775  3828 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 15:12:54.102  3775  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 15:12:54.102  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:12:54.102  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:12:54.102  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:12:54.103  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.103  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.103  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.103  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.104  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.104  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.104  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:54.104  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:12:54.104  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f removed from the list
09-13 15:12:54.104  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.104  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c removed from the list
,09-13 15:12:54.109  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.109  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:12:54.109  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.110  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.110  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.112  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.113  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.113  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:54.113  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.118  3775  3828 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 15:12:54.120  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:54.120  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.120  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.121  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.121  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.121  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.121  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.122  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.122  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.122  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.122  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.122  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.123  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.123  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.125  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.126  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 15:12:54.126  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.126  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.145  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 15:12:54.145  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 15:12:54.146  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 15:12:54.146  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 15:12:54.146  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 15:12:54.146  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 15:12:54.147  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 15:12:54.147  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 15:12:54.147  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 15:12:54.147  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 15:12:54.148  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 15:12:54.148  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 15:12:54.148  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 15:12:54.148  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 15:12:54.149  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 15:12:54.149  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 15:12:54.149  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 15:12:54.149  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 15:12:54.150  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-13 15:12:54.150  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 15:12:54.150  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 15:12:54.151  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 15:12:54.151  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 15:12:54.151  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 15:12:54.151  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 15:12:54.152  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 15:12:54.152  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 15:12:54.152  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 15:12:54.152  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 15:12:54.153  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 15:12:54.153  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 15:12:54.153  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.154  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.154  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.155  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.155  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.155  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.155  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.156  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.156  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.156  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.156  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.156  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.157  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.157  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.159  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.159  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.159  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.159  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.160  3775  3828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 15:12:54.161  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:54.168  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:54.171  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.171  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:12:54.171  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:12:54.171  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:12:54.171  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:12:54.172  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:54.172  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:12:54.174  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.177  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 15:12:54.177  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:12:54.179  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.192  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:12:54.197  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 15:12:54.198  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:12:54.205  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-13 15:12:54.211  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 15:12:54.211  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:12:54.212  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:12:54.214  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 15:12:54.216  3775  3828 D BluetoothAdapter: STATE_ON
09-13 15:12:54.230  2697  2898 D BtGatt.GattService: registerClient() - UUID=7c375eb6-7b17-4273-b56d-ffdef0e58b64
,09-13 15:12:54.232  2697  2758 D BtGatt.GattService: onClientRegistered() - UUID=7c375eb6-7b17-4273-b56d-ffdef0e58b64, clientIf=5
09-13 15:12:54.233  3775  3787 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 15:12:54.237  2697  2708 D BtGatt.GattService: start scan with filters
,09-13 15:12:54.244  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:12:54.245  2697  2774 D BtGatt.ScanManager: handling starting scan
,09-13 15:12:54.245  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 15:12:54.246  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:12:54.247  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:12:54.249  2697  2774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:12:54.257  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:54.259  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:54.261  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:12:54.264  2697  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 15:12:54.265  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.266  2697  2774 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 15:12:54.268  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:12:54.277  3775  3828 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:12:54.282  2697  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 15:12:54.282  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.283  2697  2774 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 15:12:54.283  2697  2774 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 15:12:54.286  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:54.288  3775  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:12:54.288  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:54.288  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 15:12:54.289  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.289  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 15:12:54.289  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:54.289  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:12:54.289  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:54.289  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:12:54.291  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:12:54.291  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 15:12:54.292  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:12:54.294  2697  2707 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:12:54.295  2697  2899 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 15:12:54.295  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:12:54.295  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:12:54.295  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 15:12:54.296  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:12:54.296  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 15:12:54.297  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:54.297  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 15:12:54.298  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 15:12:54.298  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:12:54.299  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:54.301  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.301  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.301  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:54.301  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.301  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.302  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:54.302  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:54.302  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:54.301  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.302  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.302  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.303  3775  3828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 15:12:54.305  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:54.311  2697  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 15:12:54.312  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:54.319  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:54.323  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.324  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:12:54.324  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:12:54.325  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:12:54.325  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:12:54.325  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:54.325  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:12:54.330  2697  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 15:12:54.330  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.332  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:54.338  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 15:12:54.338  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:12:54.339  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:54.345  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:12:54.346  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 15:12:54.347  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:12:54.349  2697  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 15:12:54.350  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.350  2697  2774 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:12:54.353  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:12:54.353  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 15:12:54.354  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 15:12:54.355  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:12:54.361  2697  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 15:12:54.361  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.361  2697  2890 D BtGatt.GattService: registerClient() - UUID=740b4091-b03a-4efa-9433-4f61846feb83
09-13 15:12:54.361  2697  2774 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 15:12:54.361  2697  2758 D BtGatt.GattService: onClientRegistered() - UUID=740b4091-b03a-4efa-9433-4f61846feb83, clientIf=5
09-13 15:12:54.362  3775  3786 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 15:12:54.363  2697  2707 D BtGatt.GattService: start scan with filters
,09-13 15:12:54.370  2697  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 15:12:54.371  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.371  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:12:54.371  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:12:54.371  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:12:54.371  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 15:12:54.373  2697  2774 D BtGatt.ScanManager: handling starting scan
,09-13 15:12:54.374  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:12:54.374  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:54.374  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:12:54.376  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:12:54.379  3775  3828 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:12:54.382  2697  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 15:12:54.382  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.382  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.383  3775  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:12:54.383  2697  2774 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 15:12:54.383  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.383  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 15:12:54.383  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.384  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 15:12:54.384  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:54.384  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 15:12:54.384  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:54.385  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:12:54.385  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:12:54.386  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:12:54.388  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:12:54.388  2697  2899 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:12:54.389  2697  2890 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 15:12:54.389  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 15:12:54.390  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 15:12:54.390  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:12:54.390  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-13 15:12:54.390  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:12:54.391  2697  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 15:12:54.391  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.391  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:54.391  2697  2774 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:12:54.391  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:12:54.391  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 15:12:54.391  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:12:54.391  2697  2774 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 15:12:54.392  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:12:54.400  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:12:54.401  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:12:54.401  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:54.402  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 15:12:54.402  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.402  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:12:54.403  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.403  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:54.403  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.403  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.403  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.405  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.405  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.408  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.408  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.408  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.409  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.410  2697  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 15:12:54.410  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.411  3775  3828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 15:12:54.417  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:54.420  2697  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 15:12:54.420  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:54.423  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:54.425  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:54.425  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:12:54.425  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 15:12:54.425  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 15:12:54.426  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:12:54.426  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:54.426  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:12:54.428  2697  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 15:12:54.428  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.428  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 15:12:54.428  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:12:54.429  2697  2774 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:12:54.429  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.432  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.434  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-13 15:12:54.434  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 15:12:54.434  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:12:54.435  2697  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 15:12:54.435  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.436  2697  2774 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 15:12:54.441  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 15:12:54.441  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
09-13 15:12:54.441  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 15:12:54.441  3775  3828 D BluetoothAdapter: STATE_ON,
09-13 15:12:54.442  2697  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 15:12:54.442  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:12:54.444  2697  2890 D BtGatt.GattService: registerClient() - UUID=639704e3-3665-4ab1-beca-8e71283ac708
,09-13 15:12:54.444  2697  2758 D BtGatt.GattService: onClientRegistered() - UUID=639704e3-3665-4ab1-beca-8e71283ac708, clientIf=5
09-13 15:12:54.445  3775  3787 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 15:12:54.445  2697  2899 D BtGatt.GattService: start scan with filters
,09-13 15:12:54.448  2697  2774 D BtGatt.ScanManager: handling starting scan
,09-13 15:12:54.448  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:12:54.448  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 15:12:54.448  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:12:54.448  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:12:54.452  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:54.452  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:12:54.453  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:12:54.455  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:12:54.456  2697  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 15:12:54.456  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.456  2697  2774 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 15:12:54.458  3775  3828 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:12:54.458  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.458  3775  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:12:54.459  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.459  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 15:12:54.459  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.459  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:12:54.459  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:54.459  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 15:12:54.459  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:54.459  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:12:54.459  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 15:12:54.459  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:12:54.460  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:12:54.461  2697  2890 D BtGatt.GattService: stopScan() - queue size =1
09-13 15:12:54.461  2697  2899 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 15:12:54.462  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:12:54.462  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 15:12:54.462  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:12:54.462  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:12:54.462  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:12:54.463  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:54.463  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:12:54.463  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:12:54.463  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:12:54.463  2697  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 15:12:54.463  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.464  2697  2774 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 15:12:54.464  2697  2774 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 15:12:54.464  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:54.465  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:12:54.465  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:54.465  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:54.466  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:54.466  3775  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 15:12:54.466  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:54.466  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:54.466  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.466  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.466  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:54.467  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
,09-13 15:12:54.467  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.467  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.467  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:12:54.467  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.468  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.468  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.469  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.469  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.470  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.470  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.471  3775  3828 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 15:12:54.471  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.472  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:54.472  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.472  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.472  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.472  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.472  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.472  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.473  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.473  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:12:54.473  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.473  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.473  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.473  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.475  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.475  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.475  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:54.475  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.476  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 15:12:54.477  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:54.477  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.477  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.477  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 15:12:54.477  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.477  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.478  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.478  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.478  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.478  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:12:54.478  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.478  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.478  2697  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 15:12:54.478  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.478  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.479  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.480  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:54.481  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.481  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.481  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.482  3775  3828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 15:12:54.482  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.482  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.482  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:54.483  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.483  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.483  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.483  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.483  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.483  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.483  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.483  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.484  2697  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 15:12:54.484  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.485  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.485  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.485  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.488  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.488  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.488  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.488  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.489  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 15:12:54.489  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.489  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:54.490  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.490  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.490  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.490  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.490  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.491  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.491  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.491  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.491  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.491  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.491  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.491  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.491  2697  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 15:12:54.491  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.492  2697  2774 D BtGatt.ScanManager: stopping BLe Batch
09-13 15:12:54.492  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.492  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.492  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.492  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.493  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 15:12:54.493  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 15:12:54.493  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:12:54.493  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-13 15:12:54.493  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 15:12:54.493  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 15:12:54.493  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:54.493  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:54.494  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:54.494  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.494  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.494  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.494  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.494  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:54.494  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.494  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.494  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.494  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.494  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.494  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.495  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.496  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 15:12:54.496  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.496  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.496  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:54.496  3775  3828 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 15:12:54.497  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 15:12:54.498  2697  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 15:12:54.498  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.498  2697  2774 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 15:12:54.501  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 15:12:54.501  3775  3828 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 15:12:54.501  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 15:12:54.502  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 15:12:54.503  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 15:12:54.503  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 15:12:54.503  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 15:12:54.503  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 15:12:54.503  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-13 15:12:54.503  3775  3828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:12:54.503  3775  3828 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 15:12:54.504  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 15:12:54.504  3775  3828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:12:54.504  3775  3828 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 15:12:54.504  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-13 15:12:54.504  3775  3828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:12:54.504  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 15:12:54.508  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 15:12:54.509  2697  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-13 15:12:54.509  2697  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:12:54.509  2697  2758 D BtGatt.GattService: current time is 130948917428
09-13 15:12:54.509  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-13 15:12:54.509  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 15:12:54.509  2697  2758 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -94, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 15:12:54.510  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55,
09-13 15:12:54.510  2697  2758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 15:12:54.510  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-13 15:12:54.510  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 15:12:54.510  3775  3828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:54.510  3775  3828 E io.jxcore.node.ConnectionHelper: connect: Callback is null,
09-13 15:12:54.511  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.511  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:54.511  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.511  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 15:12:54.512  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.512  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.512  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-13 15:12:54.512  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.512  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.512  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
,09-13 15:12:54.513  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.513  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.513  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.513  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:54.513  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:54.513  3775  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
09-13 15:12:54.514  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.514  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 15:12:54.514  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.514  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.514  3775  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
09-13 15:12:54.514  3775  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
09-13 15:12:54.515  3775  3828 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 15:12:54.515  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.515  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.515  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.515  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.515  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.515  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.515  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.515  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.516  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.516  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.516  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.516  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.516  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.516  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.517  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.517  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.517  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.517  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.517  3775  3828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 15:12:54.518  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.518  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.518  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the d,esired outcome of this operation, skipping...
09-13 15:12:54.518  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.518  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.518  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.518  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.518  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.518  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.518  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.518  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.518  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.518  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.519  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.519  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.519  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.519  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.519  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.520  3775  3828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 15:12:54.520  3775  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 15:12:54.520  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:12:54.520  3775  3828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 15:12:54.520  3775  3828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 15:12:54.520  3775  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 15:12:54.521  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:12:54.521  3775  3828 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 15:12:54.521  3775  3828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 15:12:54.521  3775  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 15:12:54.521  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:12:54.521  3775  3828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or ,failed to close the connection
09-13 15:12:54.521  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.521  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.521  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.521  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.521  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.521  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.521  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.522  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.522  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.522  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.522  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.522  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.522  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.522  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.523  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.523  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.523  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.523  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.524  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.524  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.524  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.524  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.524  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.524  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.524  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.524  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.524  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.524  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.524  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.524  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.524  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.525  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.525  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.525  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.525  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.525  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.525  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.525  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.525  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.525  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.525  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.525  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.525  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.525  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.525  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.525  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.526  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.527  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.527  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.527  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.527  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.528  3775  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 15:12:54.528  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:54.529  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 15:12:54.530  3775  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 15:12:54.530  3775  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 15:12:54.530  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 15:12:54.530  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 15:12:54.530  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:54.530  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.530  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 15:12:54.531  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 15:12:54.531  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 15:12:54.531  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.531  3775  3828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 15:12:54.531  3775  3775 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 15:12:54.531  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.531  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.531  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:12:54.531  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:54.531  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:12:54.531  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.531  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.532  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:54.532  3775  3844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:12:54.532  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.532  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:54.532  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.532  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:54.532  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.532  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:54.533  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.533  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.533  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.533  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.533  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.533  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.533  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.533  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.533  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.533  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.533  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.533  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.534  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.534  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.534  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.534  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.535  3775  3844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 15:12:54.535  3775  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 15:12:54.535  3775  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 15:12:54.535  3775  3775 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 15:12:54.536  3775  3828 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 15:12:54.536  3775  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 15:12:54.536  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:12:54.536  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:12:54.536  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.536  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.536  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.536  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.536  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.536  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.537  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.537  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.537  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.537  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.537  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.537  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.537  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.537  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.538  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.538  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.538  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.538  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.541  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.541  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.541  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.541  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.541  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.541  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.541  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.541  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.542  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.542  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.542  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.542  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.542  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.542  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.543  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.543  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.543  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.543  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.543  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:54.543  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:54.544  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:54.544  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:54.544  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.544  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.544  3775  3828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcd4f0f not in the list
09-13 15:12:54.544  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.544  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.544  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:54.544  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.544  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.544  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:54.544  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:54.545  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:54.545  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:54.545  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:54.545  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b6b9c not in the list
09-13 15:12:54.546  3775  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 15:12:54.546  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:12:54.546  3775  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 15:12:54.546  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:12:54.546  3775  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 15:12:54.546  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:12:54.548  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 15:12:54.548  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 15:12:54.549  3775  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 15:12:54.549  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 15:12:54.549  3775  3828 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 15:12:54.549  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 15:12:54.549  3775  3828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 15:12:54.549  3775  3828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 15:12:54.550  3775  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 15:12:54.550  3775  3828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 15:12:54.550  3775  3828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 15:12:54.550  3775  3828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 15:12:54.550  3775  3828 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 15:12:54.550  3775  3828 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 15:12:54.551  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:54.551  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca3fd1e added. We now have 2 listener(s)
09-13 15:12:54.551  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:12:54.553  3775  3828 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 15:12:54.553   874   884 D WifiService: setWifiEnabled: true pid=3775, uid=10000
09-13 15:12:54.553   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:12:54.554  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:54.554  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2619ff added. We now have 3 listener(s)
09-13 15:12:54.554  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:12:54.558  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:54.558  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25ef3cc added. We now have 4 listener(s)
09-13 15:12:54.558  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:12:54.559  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:54.559  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7e2615 added. We now have 5 listener(s)
09-13 15:12:54.559  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:12:54.561   874  2214 D WifiService: setWifiEnabled: false pid=3775, uid=10000
09-13 15:12:54.561   874  2214 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:12:54.565  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:54.566  2697  2753 D BluetoothAdapterState: Current state: ON, message: 23
09-13 15:12:54.566  2697  2753 D BluetoothAdapterProperties: Setting state to 13
09-13 15:12:54.566  2697  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 15:12:54.566  2697  2753 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 15:12:54.568  2697  2753 I BluetoothAdapterState: Entering PendingCommandState
09-13 15:12:54.569  2697  2697 D BluetoothMapService: onReceive
,09-13 15:12:54.569  2697  2697 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:12:54.570  2697  2697 D BluetoothMapService: STATE_TURNING_OFF
09-13 15:12:54.570  2697  2697 D BluetoothMapService: MAP Service closeService in
09-13 15:12:54.570  2697  2697 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 15:12:54.570  2697  2697 D ObexServerSockets0: shutdown(block = true)
09-13 15:12:54.571  2697  2697 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 15:12:54.571  2697  2697 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 15:12:54.571  2697  2910 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 15:12:54.571  2697  2887 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 15:12:54.571  2697  2911 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 15:12:54.572  2697  2697 I BtOppRfcommListener: stopping Accept Thread
09-13 15:12:54.572  2697  3438 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:12:54.572  2697  3438 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 15:12:54.573  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:54.573  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:54.574  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.574  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.574  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:12:54.578  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.580  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.582  1479  1479 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 15:12:54.584   874  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 15:12:54.584   874  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 15:12:54.584   874  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 15:12:54.585   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 15:12:54.585  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:54.585  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:54.586  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.586  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:54.588  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.591   874   887 I ActivityManager: Start proc 3847:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-13 15:12:54.598  2697  2758 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:12:54.598  2697  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 15:12:54.601  2697  2697 D HeadsetService: Received stop request...Stopping profile...
,09-13 15:12:54.603  1364  1377 D BluetoothHeadset: Proxy object disconnected
,09-13 15:12:54.604   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 15:12:54.604   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 15:12:54.604  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.604  1956  1969 D BluetoothHeadset: Proxy object disconnected
09-13 15:12:54.605   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 15:12:54.605  2697  2697 D A2dpService: Received stop request...Stopping profile...
,09-13 15:12:54.606  2697  2893 D A2dpStateMachine: Exit Disconnected: -1
,09-13 15:12:54.607  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:54.607   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 15:12:54.608  2697  2697 D HidService: Received stop request...Stopping profile...
,09-13 15:12:54.608   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 15:12:54.608  2697  2697 D HidService: Stopping Bluetooth HidService
09-13 15:12:54.608   874  2102 D DhcpClient: Clearing IP address
,09-13 15:12:54.609  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-13 15:12:54.609  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,09-13 15:12:54.609  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:12:54.609  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:12:54.611  2697  2697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 15:12:54.611  2697  2758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 15:12:54.611  2697  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:12:54.611  2697  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:12:54.611  2697  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:12:54.612  2697  2758 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 15:12:54.612  2697  2697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:12:54.612  1518  2543 V NativeCrypto: Read error: ssl=0xaec61000: I/O error during system call, Connection timed out
09-13 15:12:54.612  2697  2697 D HealthService: Received stop request...Stopping profile...
09-13 15:12:54.613  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-13 15:12:54.613  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-13 15:12:54.613  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-13 15:12:54.613  1364  1364 D HidProfile: Bluetooth service disconnected
09-13 15:12:54.613  1518  2543 V NativeCrypto: SSL shutdown failed: ssl=0xaec61000: I/O error during system call, Broken pipe
,09-13 15:12:54.616   372   872 D CommandListener: Setting iface cfg
09-13 15:12:54.615   874  1708 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-13 15:12:54.616   874  2093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-13 15:12:54.619   874  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-13 15:12:54.619   874  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 15:12:54.622   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 15:12:54.622   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 15:12:54.623   395   395 E Parcel  : Reading a NULL string not supported here.
,09-13 15:12:54.627  2697  2697 D PanService: Received stop request...Stopping profile...
09-13 15:12:54.628  2697  2697 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 15:12:54.628  2697  2697 D BluetoothMapService: stop()
,09-13 15:12:54.628   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 15:12:54.629  2697  2697 D BluetoothMapAppObserver: deinitObservers()
,09-13 15:12:54.629  2697  2697 D BluetoothMapAppObserver: removeReceiver()
09-13 15:12:54.630   874  2093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-13 15:12:54.631   874  2130 D DhcpClient: Receive thread stopped
09-13 15:12:54.631  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-13 15:12:54.631  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,09-13 15:12:54.631  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:12:54.631  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:12:54.632  2697  2758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-13 15:12:54.632  2697  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:12:54.632  2697  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:12:54.633  2697  2881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:12:54.633  2697  2881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:12:54.633  2697  2881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:12:54.633  2697  2881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 15:12:54.633  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-13 15:12:54.633  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,09-13 15:12:54.633  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:12:54.633  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:12:54.633  2697  2697 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 15:12:54.634  2697  2758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 15:12:54.634  2697  2697 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 15:12:54.637  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-13 15:12:54.637  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-13 15:12:54.638  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 15:12:54.638  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:12:54.638  2697  2697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 15:12:54.639  2697  2758 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 15:12:54.639  2697  2697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:12:54.640  2697  2697 V BluetoothAdapterState: isTurningOff()=true
,09-13 15:12:54.640  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-13 15:12:54.640  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:12:54.641  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:12:54.641  2697  2697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 15:12:54.641  2697  2697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 15:12:54.643  2697  2697 D BluetoothMapService: MAP Service closeService in
09-13 15:12:54.644  2697  2697 V BluetoothAdapterState: isTurningOff()=true
,09-13 15:12:54.644  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-13 15:12:54.644  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:12:54.644  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:12:54.645  2697  2697 D BluetoothMapService: cleanup()
,09-13 15:12:54.645  2697  2697 D BluetoothMapService: MAP Service closeService in
09-13 15:12:54.645  2697  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 15:12:54.645  2697  2753 D BluetoothAdapterProperties: Setting state to 15
,09-13 15:12:54.645  2697  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 15:12:54.646  2697  2753 I BluetoothAdapterState: Entering BleOnState
09-13 15:12:54.651  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 15:12:54.652  1364  1364 D PanProfile: Bluetooth service disconnected
09-13 15:12:54.653   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:12:54.653  1364  1364 D BluetoothMap: Proxy object disconnected
09-13 15:12:54.653  1364  1364 D MapProfile: Bluetooth service disconnected
,09-13 15:12:54.654  1364  1377 D BluetoothMap: onBluetoothStateChange: up=false
,09-13 15:12:54.654  1364  2040 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:12:54.654  1364  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:12:54.655  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 15:12:54.655   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:12:54.656   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 15:12:54.656   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:12:54.656  1364  2040 D BluetoothPan: onBluetoothStateChange on: false
09-13 15:12:54.656  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 15:12:54.657  1956  1969 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:12:54.658  2697  2753 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 15:12:54.658  2697  2753 D BluetoothAdapterProperties: Setting state to 16
,09-13 15:12:54.658  2697  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 15:12:54.658  2697  2753 D BluetoothAdapterProperties: onBleDisable
09-13 15:12:54.659  2697  2753 I BluetoothAdapterState: Entering PendingCommandState
,09-13 15:12:54.659  2697  2755 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-13 15:12:54.659  2697  2881 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 15:12:54.659  2697  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:12:54.660  2697  2758 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:12:54.663  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:54.663  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:12:54.664  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.664  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:54.666  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:54.666  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:12:54.666  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:54.666  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:12:54.668  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.670  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:54.671   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:12:54.691   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:12:54.691   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:12:54.693   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 15:12:54.694   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:54.698   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 15:12:54.701  3387  3387 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@97a75ff and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-13 15:12:54.702  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:54.705  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:54.709   874  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 15:12:54.714  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:54.714  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:54.714  1892  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:12:54.715  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:54.715  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:12:54.715   874  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 15:12:54.717  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:54.717  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:12:54.718  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:54.718  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:54.724  3847  3847 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 15:12:54.735  3847  3847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:12:54.740  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:12:54.742   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a420e2b:true
,09-13 15:12:54.754   874  1708 I ActivityManager: Start proc 3868:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 15:12:54.782   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 15:12:54.784   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 15:12:54.812  3847  3847 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 15:12:54.820  3847  3847 D BluetoothMap: Create BluetoothMap proxy object
,09-13 15:12:54.829  3847  3847 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 15:12:54.838  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 15:12:54.846  3847  3847 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:12:54.852   874  1988 I ActivityManager: Killing 2978:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 15:12:54.863  2697  2758 I bt_hci  : shut_down
,09-13 15:12:54.864  2697  2777 D bt_hwcfg: hw_epilog_process
,09-13 15:12:54.907  2697  2777 I bt_vendor: low_power_mode_cb
,09-13 15:12:54.938  2697  2777 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 15:12:54.939  2697  2777 I bt_vendor: epilog_cb
,09-13 15:12:54.939  2697  2777 I bt_hci  : epilog_finished_callback
,09-13 15:12:54.943  2697  2758 I bt_hci_h4: hal_close
,09-13 15:12:54.943  2697  2758 I bt_userial_vendor: device fd = 51 close
,09-13 15:12:54.996  3868  3868 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 15:12:54.996  3868  3868 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 15:12:54.996  3868  3868 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.996  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 15:12:54.997  3868  3868 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:12:54.997  3868  3868 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:12:54.997  3868  3868 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-,13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:12:54.997  3868  3868 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:12:54.997  3868  3868 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:12:54.997  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:12:55.004  3847  3847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 15:12:55.019  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:12:55.025  3847  3847 D DockEventReceiver: finishStartingService: stopping service
09-13 15:12:55.033   874  1430 I ActivityManager: Killing 3387:com.google.android.music:main/u0a66 (adj 15): empty #17
09-13 15:12:55.033  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:12:55.087  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 15:12:55.091  1730  1730 D SystemUpdateService: onCreate
,09-13 15:12:55.098  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 15:12:55.099  2697  2755 D bt_stack_manager: event_shut_down_stack finished.
,09-13 15:12:55.100  2697  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 15:12:55.107  2697  2697 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 15:12:55.107  2697  2753 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 15:12:55.108  2697  2697 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 15:12:55.108  2697  2697 D BtGatt.GattService: stop()
,09-13 15:12:55.108  2697  2697 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 15:12:55.109  2697  2697 V BluetoothAdapterState: isTurningOff()=false
09-13 15:12:55.109  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-13 15:12:55.110  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 15:12:55.110  1730  3900 I SystemUpdateService: active receiver: enabled
09-13 15:12:55.110  2697  2697 V BluetoothAdapterState: isBleTurningOff()=true
09-13 15:12:55.110  2697  2753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 15:12:55.111  2697  2753 D BluetoothAdapterProperties: Setting state to 10
09-13 15:12:55.111  2697  2753 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 15:12:55.112  2697  2753 I BluetoothAdapterState: Entering OffState
09-13 15:12:55.113   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-13 15:12:55.125  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 15:12:55.127  1730  2521 I iu.UploadsManager: num queued entries: 0
09-13 15:12:55.127  1730  3900 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 15:12:55.134  2697  2697 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 15:12:55.134  2697  2697 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 15:12:55.134  2697  2697 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 15:12:55.137  2697  2755 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 15:12:55.140  2697  2755 D bt_stack_manager: event_clean_up_stack finished.
,09-13 15:12:55.142  1730  2521 I iu.UploadsManager: num updated entries: 0
,09-13 15:12:55.142  1730  2521 I iu.SyncManager: NEXT; no task
,09-13 15:12:55.142  1730  3900 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 15:12:55.143  1730  3900 I SystemUpdateService: now status is 0 (complete)
,09-13 15:12:55.143  1730  3900 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 15:12:55.144  2697  2697 I art     : System.exit called, status: 0
,09-13 15:12:55.144  2697  2697 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 15:12:55.143  1730  3900 I SystemUpdateService: file has been verified
09-13 15:12:55.149  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 15:12:55.150  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 15:12:55.151  1730  3900 I SystemUpdateService: OTA package size = 12249756
,09-13 15:12:55.174  1730  3900 I SystemUpdateService: showing system update notification
,09-13 15:12:55.183   874   885 I ActivityManager: Start proc 3903:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 15:12:55.210   874  1988 I ActivityManager: Process com.android.bluetooth (pid 2697) has died
,09-13 15:12:55.224  1730  1730 D SystemUpdateService: onDestroy
,09-13 15:12:55.256  3903  3903 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 15:12:55.259  3903  3903 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:55.287  3903  3903 D SprintDMHelper: simOperator: 
,09-13 15:12:55.287  3903  3903 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 15:12:55.341   874   884 I ActivityManager: Start proc 3917:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 15:12:55.342  3868  3888 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 15:12:55.357   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b986fe7:true
,09-13 15:12:55.497   874  1373 I ActivityManager: Start proc 3932:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 15:12:55.499   874  2214 I ActivityManager: Killing 3039:com.google.android.keep/u0a79 (adj 15): empty #17
,09-13 15:12:55.584  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 15:12:55.638  3932  3932 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 15:12:55.638  3932  3932 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 15:12:55.638  3932  3932 I GAv4    :   adb logcat -s GAv4
,09-13 15:12:55.653  3932  3932 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:55.659  3932  3932 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:55.694  3932  3949 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:55.846  3932  3932 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 15:12:55.896  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 15:12:55.904  3932  3932 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2339-2343)
09-13 15:12:55.904  3932  3932 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 15:12:55.915  3932  3932 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5a2dcef}
09-13 15:12:55.915  3932  3932 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 15:12:55.916  3932  3932 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 15:12:55.922  3932  3932 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 15:12:55.923  3932  3932 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 15:12:55.953  3932  3932 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 15:12:55.970  3932  3932 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 15:12:55.970  3932  3932 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 15:12:55.970  3932  3932 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 15:12:55.970  3932  3932 I Adreno  : Build Date                       : 10/20/15
09-13 15:12:55.970  3932  3932 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 15:12:55.970  3932  3932 I Adreno  : Local Branch                     : M14
09-13 15:12:55.970  3932  3932 I Adreno  : Remote Branch                    : 
09-13 15:12:55.970  3932  3932 I Adreno  : Remote Branch                    : 
09-13 15:12:55.970  3932  3932 I Adreno  : Reconstruct Branch               : 
,09-13 15:12:56.019  3932  3932 I NSApplication: Starting up...
,09-13 15:12:56.025  3932  3979 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 15:12:56.044   874  1430 I ActivityManager: Start proc 3984:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-13 15:12:56.045   874  1430 I ActivityManager: Killing 3459:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 15:12:56.129  3984  3984 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 15:12:56.311   874  1430 I ActivityManager: Killing 1710:android.process.acore/u0a5 (adj 15): empty #17
,09-13 15:12:56.327  3544  3553 W art     : Suspending all threads took: 5.033ms
,09-13 15:12:56.410   874  1373 I ActivityManager: Start proc 3998:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 15:12:56.519  3998  3998 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 15:12:56.579  3998  3998 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 15:12:56.605   874  1708 I ActivityManager: Start proc 4021:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-13 15:12:56.606   874  1708 I ActivityManager: Killing 3631:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 15:12:56.688  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-13 15:12:56.923   874  2039 I ActivityManager: Killing 3648:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 15:12:57.576   874  1423 D WifiService: setWifiEnabled: true pid=3775, uid=10000
,09-13 15:12:57.577   874  1423 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 15:12:57.592   874  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-13 15:12:57.601  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:57.601  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:57.602  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:57.602  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:57.606  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:57.606  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:57.606  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:57.607  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:57.617   874  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-13 15:12:57.619   874  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 15:12:57.619   874  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 15:12:57.620   874  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 15:12:57.621   874  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 15:12:57.621   874  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-13 15:12:57.621   874  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 15:12:57.641   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 15:12:57.641   874  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.25 rxSuccessRate=14.25 delta 1000 -> 994
,09-13 15:12:57.643   372   872 D CommandListener: Setting iface cfg
,09-13 15:12:57.644   874  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-13 15:12:57.644   874  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 15:12:57.653   874  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 15:12:57.653   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:57.664   874  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 15:12:57.704   874  1304 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 15:12:57.705   874  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 15:12:57.724   874  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 15:12:57.727  1479  1479 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 15:12:58.192  1479  1479 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 15:12:58.322  1479  1479 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 15:12:58.322  1479  1479 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 15:12:58.333   874  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 15:12:58.345   874  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 15:12:58.345   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:58.345   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 15:12:58.366   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:58.381   372   872 D CommandListener: Setting iface cfg
,09-13 15:12:58.384   874  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 15:12:58.397   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 15:12:58.397   874  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-13 15:12:58.400   874  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 15:12:58.407   874  4053 D DhcpClient: Receive thread started
,09-13 15:12:58.489   874  1306 E native  : do suspend false
,09-13 15:12:58.508   874  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 15:12:58.533   874  4053 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,09-13 15:12:58.536   874  2102 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,09-13 15:12:58.541   874  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 15:12:58.562   874  4053 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 15:12:58.563   874  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 15:12:58.570   372   872 D CommandListener: Setting iface cfg
,09-13 15:12:58.582   874  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 15:12:58.583   874  2102 D DhcpClient: Scheduling renewal in 86399s
,09-13 15:12:58.594   874  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 15:12:58.596   874  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 15:12:58.597   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 15:12:58.601   874  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 15:12:58.612   874  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 15:12:58.648   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 15:12:58.648   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 15:12:58.650   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 15:12:58.653   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 15:12:58.655   874  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 15:12:58.669   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 15:12:58.677   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 15:12:58.678   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 15:12:58.678   874  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 15:12:58.679   874  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 15:12:58.679   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-13 15:12:58.679   874  1309 D ConnectivityService:    accepting network in place of null
,09-13 15:12:58.681   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 15:12:58.710   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:12:58.755   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:12:58.760   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 15:12:58.760   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:58.765   874  4052 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135204, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 15:12:58.767   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 15:12:58.772  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:58.773  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:58.773  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:58.773  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:58.776   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 15:12:58.785  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:58.785  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:58.785  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:58.785  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:58.790  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 15:12:58.793  1730  1730 D SystemUpdateService: onCreate
,09-13 15:12:58.800  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 15:12:58.803  1730  4063 I SystemUpdateService: active receiver: enabled
,09-13 15:12:58.807  1730  4063 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 15:12:58.809  1730  4063 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 15:12:58.809  1730  4063 I SystemUpdateService: now status is 0 (complete)
09-13 15:12:58.809  1730  4063 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 15:12:58.809  1730  4063 I SystemUpdateService: file has been verified
09-13 15:12:58.811  1730  4063 I SystemUpdateService: OTA package size = 12249756
,09-13 15:12:58.816  1730  4063 I SystemUpdateService: showing system update notification
,09-13 15:12:58.821  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 15:12:58.823  1730  2521 I iu.UploadsManager: num queued entries: 0
,09-13 15:12:58.824  1730  2521 I iu.UploadsManager: num updated entries: 0
,09-13 15:12:58.826  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 15:12:58.826  1730  2521 I iu.SyncManager: NEXT; no task
,09-13 15:12:58.828  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 15:12:58.829  1730  4067 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 15:12:58.829  1730  4067 W BaseAppContext: Using Auth Proxy for data requests.
09-13 15:12:58.830  3903  3903 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:58.830  1730  4067 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 15:12:58.836  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 15:12:58.836  3903  3903 D SprintDMHelper: simOperator: 
09-13 15:12:58.837  3903  3903 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 15:12:58.838  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 15:12:58.845  1730  1730 D SystemUpdateService: onDestroy
,09-13 15:12:58.872  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 15:12:58.872  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 15:12:58.872  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 15:12:58.872  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:12:58.883  1730  4067 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-13 15:12:58.896  4021  4069 V KeepSync: Connecting to GoogleApiClient
,09-13 15:12:58.897   874  2214 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 15:12:58.957  1518  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 15:12:58.957  1518  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 15:12:58.958  1518  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 15:12:58.958  1518  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:12:58.970  1730  4074 V BaseAuthAsyncOperation: access token request failed
,09-13 15:12:58.972  4021  4069 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 15:12:59.077  1518  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 15:12:59.077  1518  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 15:12:59.077  1518  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 15:12:59.077  1518  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:12:59.116  4021  4069 E KeepSync: IOException
09-13 15:12:59.116  4021  4069 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 15:12:59.116  4021  4069 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 15:12:59.116  4021  4069 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 15:12:59.116  4021  4069 E KeepSync: 	... 10 more
,09-13 15:12:59.117  4021  4069 W KeepSync: Sync result 2
,09-13 15:12:59.131   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127817, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 15:12:59.760   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 15:12:59.919   874  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:400d:803::200e
,09-13 15:13:00.370  2263  4070 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 15:13:00.442   874  1988 I ActivityManager: Killing 2068:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 15:13:00.586   874  1430 D WifiService: setWifiEnabled: false pid=3775, uid=10000
,09-13 15:13:00.587   874  1430 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 15:13:00.623  1479  1479 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 15:13:00.628   874  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 15:13:00.628   874  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 15:13:00.629   874  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 15:13:00.629   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:13:00.645   874  2102 D DhcpClient: Clearing IP address
,09-13 15:13:00.646   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 15:13:00.648   372   872 D CommandListener: Setting iface cfg
,09-13 15:13:00.655  1518  4078 V NativeCrypto: Read error: ssl=0x9b067400: I/O error during system call, Connection timed out
,09-13 15:13:00.657  1518  4078 V NativeCrypto: SSL shutdown failed: ssl=0x9b067400: I/O error during system call, Broken pipe
09-13 15:13:00.657   874  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-13 15:13:00.659   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-13 15:13:00.663   874  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-13 15:13:00.663   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 15:13:00.663   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 15:13:00.670   874  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 15:13:00.672   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:13:00.673   395   395 E Parcel  : Reading a NULL string not supported here.
09-13 15:13:00.675   874  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 15:13:00.678  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:00.678  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:00.678  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:00.678  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:00.679  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:00.679  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:00.679  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:00.679  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:00.680   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 15:13:00.680   874  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 15:13:00.683  1892  2307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:13:00.684   874  4053 D DhcpClient: Receive thread stopped
,09-13 15:13:00.711   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:13:00.733   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:13:00.734   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 15:13:00.734   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:13:00.738   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 15:13:00.739  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:00.739  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:00.740  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:00.740  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:00.744  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 15:13:00.747  1730  1730 D SystemUpdateService: onCreate
,09-13 15:13:00.750  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 15:13:00.757  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 15:13:00.761  1730  4088 I SystemUpdateService: active receiver: enabled
,09-13 15:13:00.762  1730  2521 I iu.UploadsManager: num queued entries: 0
,09-13 15:13:00.765  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 15:13:00.766  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 15:13:00.768  3903  3903 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:13:00.772  3903  3903 D SprintDMHelper: simOperator: 
09-13 15:13:00.772  3903  3903 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 15:13:00.775  1730  2521 I iu.UploadsManager: num updated entries: 0
,09-13 15:13:00.778  1730  4088 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 15:13:00.787  2263  4092 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 15:13:00.790  1730  2521 I iu.SyncManager: NEXT; no task
09-13 15:13:00.790  1730  4088 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 15:13:00.791  1730  4088 I SystemUpdateService: now status is 0 (complete)
09-13 15:13:00.791  1730  4088 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 15:13:00.791  1730  4088 I SystemUpdateService: file has been verified
09-13 15:13:00.792  1730  4088 I SystemUpdateService: OTA package size = 12249756
,09-13 15:13:00.803  1730  4088 I SystemUpdateService: showing system update notification
,09-13 15:13:00.813  1730  1730 D SystemUpdateService: onDestroy
,09-13 15:13:00.843   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 15:13:00.844   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 15:13:01.783  4021  4028 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@caa128f)
,09-13 15:13:03.647   874   891 I ActivityManager: Start proc 4096:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 15:13:03.776  4096  4096 D AdapterServiceConfig: Adding HeadsetService
09-13 15:13:03.777  4096  4096 D AdapterServiceConfig: Adding A2dpService
,09-13 15:13:03.777  4096  4096 D AdapterServiceConfig: Adding HidService
09-13 15:13:03.777  4096  4096 D AdapterServiceConfig: Adding HealthService
,09-13 15:13:03.777  4096  4096 D AdapterServiceConfig: Adding PanService
09-13 15:13:03.778  4096  4096 D AdapterServiceConfig: Adding GattService
,09-13 15:13:03.778  4096  4096 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 15:13:03.793   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1a1f26:true
,09-13 15:13:03.796  4096  4096 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 15:13:03.807  4096  4096 I bt_bluedroid: init
,09-13 15:13:03.808  4096  4108 I BluetoothAdapterState: Entering OffState
,09-13 15:13:03.812  4096  4109 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 15:13:03.812  4096  4109 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 15:13:03.812  4096  4109 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 15:13:03.812  4096  4109 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 15:13:03.813  4096  4096 I bt_bluedroid: get_profile_interface socket
,09-13 15:13:03.815  4096  4096 I bt_bluedroid: get_profile_interface sdp
,09-13 15:13:03.818  4096  4107 I bt_bluedroid: config_hci_snoop_log
,09-13 15:13:03.818  4096  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-13 15:13:03.819   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 15:13:03.821  4096  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 15:13:03.826  4096  4108 D BluetoothAdapterState: Current state: OFF, message: 0
09-13 15:13:03.827  4096  4108 D BluetoothAdapterProperties: Setting state to 14
09-13 15:13:03.827  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 15:13:03.831  4096  4108 D BluetoothBondStateMachine: make
,09-13 15:13:03.836  4096  4113 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 15:13:03.842  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
09-13 15:13:03.843  4096  4096 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 15:13:03.847  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:03.848  4096  4096 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 15:13:03.848  4096  4096 D BtGatt.GattService: Received start request. Starting profile...
09-13 15:13:03.849  4096  4096 D BtGatt.GattService: start()
09-13 15:13:03.849  4096  4096 I bt_bluedroid: get_profile_interface gatt
,09-13 15:13:03.850  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
09-13 15:13:03.850  4096  4096 D BtGatt.AdvertiseManager: advertise manager created
,09-13 15:13:03.859  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:03.859  4096  4096 V BluetoothAdapterState: isTurningOn()=false
09-13 15:13:03.859  4096  4096 V BluetoothAdapterState: isBleTurningOn()=true
09-13 15:13:03.859  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:03.860  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 15:13:03.861  4096  4108 I bt_bluedroid: enable
09-13 15:13:03.861  4096  4109 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 15:13:03.861  4096  4109 I bt_hci  : start_up
,09-13 15:13:03.869  4096  4109 I bt_vendor: alloc value 0xb3a43189
,09-13 15:13:03.869  4096  4109 I bt_vendor: init
09-13 15:13:03.870  4096  4109 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 15:13:03.870  4096  4109 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 15:13:03.975  4096  4109 D bt_hci  : start_up starting async portion
,09-13 15:13:03.976  4096  4116 I bt_hci  : event_finish_startup
,09-13 15:13:03.976  4096  4116 I bt_hci_h4: hal_open
09-13 15:13:03.976  4096  4116 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 15:13:03.986  4096  4116 I bt_userial_vendor: device fd = 51 open
,09-13 15:13:04.020  4096  4116 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 15:13:04.049  4096  4116 D bt_hwcfg: Chipset BCM4354A2
,09-13 15:13:04.049  4096  4116 D bt_hwcfg: Target name = [BCM4354A2]
09-13 15:13:04.050  4096  4116 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 15:13:04.676  4096  4116 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 15:13:04.677  4096  4116 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 15:13:04.679  4096  4116 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 15:13:04.797  4096  4116 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 15:13:04.798  4096  4116 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 15:13:04.825  4096  4116 I bt_hwcfg: vendor lib fwcfg completed
,09-13 15:13:04.826  4096  4116 I bt_vendor: firmware callback
09-13 15:13:04.826  4096  4116 I bt_hci  : firmware_config_callback
,09-13 15:13:04.839  4096  4118 I bt_btu  : btu_task pending for preload complete event
,09-13 15:13:04.839  4096  4118 I bt_btu_task: Bluetooth chip preload is complete
,09-13 15:13:04.839  4096  4118 I bt_btu  : btu_task received preload complete event
,09-13 15:13:04.848  4096  4118 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 15:13:04.849  4096  4118 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 15:13:04.849  4096  4118 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 15:13:04.849  4096  4118 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 15:13:04.850  4096  4118 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 15:13:04.850  4096  4118 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 15:13:04.850  4096  4118 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 15:13:04.851  4096  4118 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 15:13:04.851  4096  4118 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 15:13:04.851  4096  4118 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 15:13:04.851  4096  4118 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 15:13:04.852  4096  4118 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 15:13:04.852  4096  4118 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 15:13:04.852  4096  4118 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 15:13:04.852  4096  4118 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 15:13:04.987  4096  4118 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c0d9d
,09-13 15:13:04.988  4096  4118 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c0d9d 
,09-13 15:13:04.999  4096  4112 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 15:13:05.001  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 15:13:05.002  4096  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 15:13:05.005  4096  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 15:13:05.014  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:05.013  4096  4112 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:13:05.018  4096  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:13:05.019  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:05.020  4096  4112 D bt_hci  : do_postload posting postload work item
09-13 15:13:05.020  4096  4116 I bt_hci  : event_postload
,09-13 15:13:05.020  4096  4116 I bt_vendor: sco_config_cb
09-13 15:13:05.020  4096  4116 I bt_hci  : sco_config_callback postload finished.
,09-13 15:13:05.024  4096  4112 D bt_bte_conf: Device ID record 1 : primary
,09-13 15:13:05.025  4096  4112 D bt_bte_conf:   vendorId            = 000f
09-13 15:13:05.025  4096  4112 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 15:13:05.025  4096  4112 D bt_bte_conf:   product             = 1200
09-13 15:13:05.025  4096  4112 D bt_bte_conf:   version             = 1436
09-13 15:13:05.026  4096  4112 D bt_bte_conf:   clientExecutableURL = 
09-13 15:13:05.026  4096  4112 D bt_bte_conf:   serviceDescription  = 
,09-13 15:13:05.026  4096  4112 D bt_bte_conf:   documentationURL    = 
09-13 15:13:05.026  4096  4112 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 15:13:05.027  4096  4109 D bt_stack_manager: event_start_up_stack finished
09-13 15:13:05.027  4096  4116 I bt_vendor: low_power_mode_cb
,09-13 15:13:05.028  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 15:13:05.028  4096  4108 D BluetoothAdapterProperties: Setting state to 15
,09-13 15:13:05.028  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 15:13:05.029  4096  4108 I BluetoothAdapterState: Entering BleOnState
,09-13 15:13:05.032  4096  4108 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 15:13:05.033  4096  4108 D BluetoothAdapterProperties: Setting state to 11
,09-13 15:13:05.033  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 15:13:05.046  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:05.047  4096  4096 D HeadsetService: Received start request. Starting profile...
,09-13 15:13:05.048  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:05.050  4096  4096 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
09-13 15:13:05.051  4096  4096 D HeadsetStateMachine: make
,09-13 15:13:05.052  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:05.058  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
,09-13 15:13:05.065  4096  4096 D HeadsetStateMachine: max_hf_connections = 1
,09-13 15:13:05.066  4096  4096 I bt_bluedroid: get_profile_interface handsfree
,09-13 15:13:05.067  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-13 15:13:05.067  4096  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-13 15:13:05.074  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:05.075  4096  4096 D A2dpService: Received start request. Starting profile...
,09-13 15:13:05.075  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:05.075  4096  4096 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 15:13:05.076  4096  4096 I bt_bluedroid: get_profile_interface avrcp
,09-13 15:13:05.086  4096  4096 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 15:13:05.086  4096  4096 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-13 15:13:05.086  4096  4096 D A2dpStateMachine: make
,09-13 15:13:05.089  4096  4096 I bt_bluedroid: get_profile_interface a2dp
,09-13 15:13:05.091  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 15:13:05.091  4096  4127 D A2dpStateMachine: Enter Disconnected: -2
09-13 15:13:05.092  4096  4096 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 15:13:05.095  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:05.097  3847  3847 D BluetoothInputDevice: Proxy object connected
,09-13 15:13:05.097  4096  4096 D HidService: Received start request. Starting profile...
,09-13 15:13:05.097  3847  3847 D HidProfile: Bluetooth service connected
09-13 15:13:05.097  4096  4096 I bt_bluedroid: get_profile_interface hidhost
,09-13 15:13:05.098  4096  4112 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a23e5
,09-13 15:13:05.098  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 15:13:05.099  4096  4096 D HidService: setHidService(): set to: null
,09-13 15:13:05.100  4096  4096 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 15:13:05.101  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:05.102  4096  4096 D HealthService: Received start request. Starting profile...
09-13 15:13:05.105  4096  4096 I bt_bluedroid: get_profile_interface health
,09-13 15:13:05.106  4096  4096 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 15:13:05.107  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:05.110  3847  3847 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 15:13:05.110  4096  4096 D PanService: Received start request. Starting profile...
09-13 15:13:05.110  3847  3847 D PanProfile: Bluetooth service connected
,09-13 15:13:05.110  4096  4096 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 15:13:05.110  4096  4096 I bt_bluedroid: get_profile_interface pan
,09-13 15:13:05.111  4096  4112 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 15:13:05.117  4096  4096 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:05.119  3847  3847 D BluetoothMap: Proxy object connected
,09-13 15:13:05.120  3847  3847 D MapProfile: Bluetooth service connected
,09-13 15:13:05.120  3847  3847 D BluetoothMap: getConnectedDevices()
09-13 15:13:05.120  4096  4096 D BluetoothMapService: Received start request. Starting profile...
,09-13 15:13:05.120  4096  4096 D BluetoothMapService: start()
09-13 15:13:05.121  3847  3847 D BluetoothMap: Bluetooth is Not enabled
,09-13 15:13:05.125  4096  4096 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 15:13:05.126  4096  4096 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 15:13:05.127  4096  4096 D BluetoothMapAppObserver: createReceiver()
,09-13 15:13:05.128  4096  4096 D BluetoothMapAppObserver: initObservers()
,09-13 15:13:05.129  4096  4096 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 15:13:05.136  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:05.136  4096  4096 V BluetoothAdapterState: isTurningOn()=true
,09-13 15:13:05.136  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:05.137  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:05.139  4096  4125 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isTurningOn()=true
,09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:05.140  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isTurningOn()=true
,09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 15:13:05.141  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:05.142  4096  4096 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:05.142  4096  4096 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:05.142  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 15:13:05.142  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:05.142  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-13 15:13:05.142  4096  4108 D BluetoothAdapterProperties: ScanMode =  20
,09-13 15:13:05.142  4096  4108 D BluetoothAdapterProperties: State =  11
09-13 15:13:05.144  4096  4112 D BluetoothAdapterProperties: Scan Mode:21
,09-13 15:13:05.144  4096  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:13:05.144  4096  4108 D BluetoothAdapterProperties: Setting state to 12
09-13 15:13:05.144  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 15:13:05.145   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:05.145  4096  4108 I BluetoothAdapterState: Entering OnState
09-13 15:13:05.146  1364  1376 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:05.148  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:05.149  1364  1364 D BluetoothMap: Proxy object connected
09-13 15:13:05.149  1364  1364 D MapProfile: Bluetooth service connected
09-13 15:13:05.149  1364  1364 D BluetoothMap: getConnectedDevices()
09-13 15:13:05.150  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:05.151  1364  2040 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:05.152  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:05.154  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:05.155  1364  1376 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 15:13:05.157  1364  1364 D BluetoothA2dp: Proxy object connected
,09-13 15:13:05.158  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:05.158  3847  3861 D BluetoothMap: onBluetoothStateChange: up=true
09-13 15:13:05.159  4096  4096 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 15:13:05.159  4096  4096 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 15:13:05.159   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:13:05.161  4096  4096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:13:05.161   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:05.161   874   874 D BluetoothA2dp: Proxy object connected
09-13 15:13:05.162   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 15:13:05.163  1364  1377 D BluetoothPan: onBluetoothStateChange on: true
09-13 15:13:05.163  4096  4096 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:05.165  4096  4096 D ObexServerSockets: Succeed to create listening sockets 
09-13 15:13:05.165  4096  4096 D ObexServerSockets0: startAccept()
09-13 15:13:05.165  4096  4096 D ObexServerSockets0: prepareForNewConnect()
,09-13 15:13:05.167  4096  4096 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-13 15:13:05.167  3847  3857 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 15:13:05.168  4096  4096 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 15:13:05.167  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 15:13:05.168  1364  1364 D PanProfile: Bluetooth service connected
09-13 15:13:05.168  3847  3861 D BluetoothPan: onBluetoothStateChange on: true
,09-13 15:13:05.168  1364  2040 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 15:13:05.170  4096  4133 D ObexServerSockets0: Accepting socket connection...
09-13 15:13:05.170  4096  4134 D ObexServerSockets0: Accepting socket connection...
09-13 15:13:05.170  1956  1970 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:05.170  1364  1364 D BluetoothInputDevice: Proxy object connected
09-13 15:13:05.170  1364  1364 D HidProfile: Bluetooth service connected
09-13 15:13:05.171  3847  3857 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 15:13:05.175   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 15:13:05.176  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:05.177  4096  4096 D BluetoothMapService: onReceive
09-13 15:13:05.177  4096  4096 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:05.177  4096  4096 D BluetoothMapService: STATE_ON
,09-13 15:13:05.178  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:05.179  3847  3847 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 15:13:05.184  3847  3847 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 15:13:05.190  3847  3847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:13:05.194  3847  3847 D BluetoothA2dp: Proxy object connected
,09-13 15:13:05.198  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:05.204  3847  3847 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:05.206  3847  3847 D BluetoothPbap: Proxy object connected
09-13 15:13:05.206  1364  1364 D BluetoothPbap: Proxy object connected
09-13 15:13:05.206  1364  1364 D PbapServerProfile: Bluetooth service connected
09-13 15:13:05.206  3847  3847 D PbapServerProfile: Bluetooth service connected
,09-13 15:13:05.206  4096  4096 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 15:13:05.207  4096  4096 D ObexServerSockets0: prepareForNewConnect()
,09-13 15:13:05.216  4096  4139 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:05.231  4096  4143 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:05.232  4096  4143 I BtOppRfcommListener: Accept thread started.
,09-13 15:13:05.246  1364  1377 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.247  1364  1364 D HeadsetProfile: Bluetooth service connected
09-13 15:13:05.247   874   874 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.247   874   874 D BluetoothHeadset: Proxy object connected
09-13 15:13:05.247  1956  2099 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.248   874   874 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.252  1364  1376 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.252  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-13 15:13:05.262   874   891 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.262   874   891 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.271  1956  2121 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.289  3847  3861 D BluetoothHeadset: Proxy object connected
,09-13 15:13:05.296  3847  3847 D HeadsetProfile: Bluetooth service connected
,09-13 15:13:06.612  4096  4108 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 15:13:06.613  4096  4108 D BluetoothAdapterProperties: Setting state to 13
,09-13 15:13:06.613  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 15:13:06.615  4096  4108 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 15:13:06.620  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
,09-13 15:13:06.628  4096  4096 D BluetoothMapService: onReceive
,09-13 15:13:06.629  4096  4096 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:06.629  4096  4096 D BluetoothMapService: STATE_TURNING_OFF
,09-13 15:13:06.630  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:06.631  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:06.630  4096  4096 D BluetoothMapService: MAP Service closeService in
09-13 15:13:06.632  4096  4096 D BluetoothMapMasInstance0: MAP Service shutdown
,09-13 15:13:06.633  4096  4096 D ObexServerSockets0: shutdown(block = true)
,09-13 15:13:06.634  4096  4133 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 15:13:06.634  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:13:06.635  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:06.636  4096  4096 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 15:13:06.637  4096  4134 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 15:13:06.639  4096  4112 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:13:06.639  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 15:13:06.640  4096  4120 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-13 15:13:06.640  4096  4096 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 15:13:06.640  3847  3847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 15:13:06.640  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:06.641  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:06.641  3775  3775 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:13:06.642  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:06.646  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:06.647  4096  4096 D HeadsetService: Received stop request...Stopping profile...
09-13 15:13:06.648  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:06.649  1364  1377 D BluetoothHeadset: Proxy object disconnected
09-13 15:13:06.649   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 15:13:06.649  4096  4096 D A2dpService: Received stop request...Stopping profile...
,09-13 15:13:06.649  4096  4127 D A2dpStateMachine: Exit Disconnected: -1
09-13 15:13:06.649  3847  3861 D BluetoothHeadset: Proxy object disconnected
09-13 15:13:06.650   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 15:13:06.650  1956  1969 D BluetoothHeadset: Proxy object disconnected
,09-13 15:13:06.650   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 15:13:06.651   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 15:13:06.652  4096  4096 I BtOppRfcommListener: stopping Accept Thread
09-13 15:13:06.653  4096  4143 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:13:06.652  3847  3847 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:06.653  4096  4143 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 15:13:06.655  4096  4096 D HidService: Received stop request...Stopping profile...
,09-13 15:13:06.655  4096  4096 D HidService: Stopping Bluetooth HidService
09-13 15:13:06.654  3847  3847 D HeadsetProfile: Bluetooth service disconnected
,09-13 15:13:06.657  4096  4096 D HealthService: Received stop request...Stopping profile...
09-13 15:13:06.659  3847  3847 D BluetoothA2dp: Proxy object disconnected
09-13 15:13:06.660  3847  3847 D BluetoothInputDevice: Proxy object disconnected
,09-13 15:13:06.660  3847  3847 D HidProfile: Bluetooth service disconnected
09-13 15:13:06.662  4096  4096 D PanService: Received stop request...Stopping profile...,
,09-13 15:13:06.662  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:06.664  4096  4096 D BluetoothMapService: Received stop request...Stopping profile...
09-13 15:13:06.664  4096  4096 D BluetoothMapService: stop()
09-13 15:13:06.664  3847  3847 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 15:13:06.664  3847  3847 D PanProfile: Bluetooth service disconnected
,09-13 15:13:06.664  4096  4096 D BluetoothMapAppObserver: deinitObservers()
,09-13 15:13:06.664  4096  4096 D BluetoothMapAppObserver: removeReceiver()
09-13 15:13:06.666  4096  4096 V BluetoothAdapterState: isTurningOff()=true
,09-13 15:13:06.666  4096  4096 V BluetoothAdapterState: isTurningOn()=false
09-13 15:13:06.666  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:06.666  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:06.666  3847  3847 D BluetoothMap: Proxy object disconnected
,09-13 15:13:06.666  3847  3847 D MapProfile: Bluetooth service disconnected
,09-13 15:13:06.667  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-13 15:13:06.667  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-13 15:13:06.667  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-13 15:13:06.668  4096  4096 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 15:13:06.667  1364  1364 D HidProfile: Bluetooth service disconnected
,09-13 15:13:06.668  4096  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:13:06.668  4096  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 15:13:06.668  4096  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:13:06.668  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 15:13:06.668  4096  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
09-13 15:13:06.668  4096  4096 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 15:13:06.669  4096  4096 V BluetoothAdapterState: isTurningOff()=true
09-13 15:13:06.669  4096  4096 V BluetoothAdapterState: isTurningOn()=false
09-13 15:13:06.669  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:06.669  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:06.670  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 15:13:06.670  1364  1364 D PanProfile: Bluetooth service disconnected
09-13 15:13:06.670  1364  1364 D BluetoothMap: Proxy object disconnected
,09-13 15:13:06.670  1364  1364 D MapProfile: Bluetooth service disconnected
09-13 15:13:06.670  4096  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:13:06.670  4096  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:13:06.671  4096  4118 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:13:06.671  4096  4118 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:13:06.671  4096  4118 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 15:13:06.671  4096  4118 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:13:06.671  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 15:13:06.673  4096  4096 V BluetoothAdapterState: isTurningOff()=true
09-13 15:13:06.673  4096  4096 V BluetoothAdapterState: isTurningOn()=false
,09-13 15:13:06.673  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:06.673  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:06.673  4096  4096 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 15:13:06.673  4096  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 15:13:06.674  4096  4096 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 15:13:06.674  4096  4096 V BluetoothAdapterState: isTurningOff()=true
09-13 15:13:06.674  4096  4096 V BluetoothAdapterState: isTurningOn()=false
09-13 15:13:06.674  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:06.674  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:06.674  4096  4096 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 15:13:06.675  4096  4112 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 15:13:06.675  4096  4096 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:13:06.676  1364  1364 D BluetoothPbap: Proxy object disconnected
09-13 15:13:06.676  1364  1364 D PbapServerProfile: Bluetooth service disconnected
09-13 15:13:06.677  3847  3847 D BluetoothPbap: Proxy object disconnected
09-13 15:13:06.677  4096  4096 V BluetoothAdapterState: isTurningOff()=true
09-13 15:13:06.677  3847  3847 D PbapServerProfile: Bluetooth service disconnected
09-13 15:13:06.677  4096  4096 V BluetoothAdapterState: isTurningOn()=false
,09-13 15:13:06.677  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:06.677  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:06.677  4096  4096 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 15:13:06.678  4096  4096 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 15:13:06.680  4096  4096 D BluetoothMapService: MAP Service closeService in
09-13 15:13:06.680  4096  4096 V BluetoothAdapterState: isTurningOff()=true
09-13 15:13:06.680  4096  4096 V BluetoothAdapterState: isTurningOn()=false
09-13 15:13:06.680  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:06.680  4096  4096 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:06.680   874  1309 D ConnectivityService: handlePromptUnvalidated 101
09-13 15:13:06.681  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 15:13:06.681  4096  4108 D BluetoothAdapterProperties: Setting state to 15
09-13 15:13:06.681  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 15:13:06.681  4096  4108 I BluetoothAdapterState: Entering BleOnState
09-13 15:13:06.681  4096  4096 D BluetoothMapService: cleanup()
09-13 15:13:06.681  4096  4096 D BluetoothMapService: MAP Service closeService in
09-13 15:13:06.682   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 15:13:06.683  3847  3857 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:13:06.683  1364  2040 D BluetoothMap: onBluetoothStateChange: up=false
09-13 15:13:06.684  1364  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:13:06.684  1364  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:13:06.684  1364  2040 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 15:13:06.685  3847  3861 D BluetoothMap: onBluetoothStateChange: up=false
09-13 15:13:06.685   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:13:06.685   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:13:06.685   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:13:06.685  1364  1377 D BluetoothPan: onBluetoothStateChange on: false
09-13 15:13:06.686  3847  3857 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 15:13:06.686  3847  3861 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 15:13:06.687  3847  3857 D BluetoothPan: onBluetoothStateChange on: false
09-13 15:13:06.688  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 15:13:06.688  1956  1970 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:13:06.689  3847  3861 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 15:13:06.689  4096  4108 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 15:13:06.689  4096  4108 D BluetoothAdapterProperties: Setting state to 16
09-13 15:13:06.689  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 15:13:06.690  4096  4108 D BluetoothAdapterProperties: onBleDisable
09-13 15:13:06.690  4096  4108 I BluetoothAdapterState: Entering PendingCommandState
09-13 15:13:06.690  4096  4109 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 15:13:06.691  4096  4118 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 15:13:06.691  4096  4118 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 15:13:06.691  4096  4112 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:13:06.693  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:06.695  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:06.696  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:06.697  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:06.697  3847  3847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:13:06.701  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:06.708  3847  3847 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:06.892  4096  4112 I bt_hci  : shut_down
,09-13 15:13:06.892  4096  4116 D bt_hwcfg: hw_epilog_process
09-13 15:13:06.894  4096  4116 I bt_vendor: low_power_mode_cb
,09-13 15:13:06.919  4096  4116 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 15:13:06.919  4096  4116 I bt_vendor: epilog_cb
09-13 15:13:06.919  4096  4116 I bt_hci  : epilog_finished_callback
,09-13 15:13:06.922  4096  4112 I bt_hci_h4: hal_close
09-13 15:13:06.922  4096  4112 I bt_userial_vendor: device fd = 51 close
,09-13 15:13:07.050  4096  4109 D bt_stack_manager: event_shut_down_stack finished.
,09-13 15:13:07.051  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 15:13:07.056  4096  4096 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 15:13:07.057  4096  4108 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 15:13:07.058  4096  4096 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 15:13:07.058  4096  4096 D BtGatt.GattService: stop()
,09-13 15:13:07.059  4096  4096 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 15:13:07.063  4096  4096 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:07.063  4096  4096 V BluetoothAdapterState: isTurningOn()=false
,09-13 15:13:07.064  4096  4096 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 15:13:07.065  4096  4096 V BluetoothAdapterState: isBleTurningOff()=true
09-13 15:13:07.065  4096  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 15:13:07.066  4096  4108 D BluetoothAdapterProperties: Setting state to 10
09-13 15:13:07.066  4096  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 15:13:07.067  4096  4108 I BluetoothAdapterState: Entering OffState
09-13 15:13:07.069   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 15:13:07.089  4096  4096 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 15:13:07.090  4096  4096 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 15:13:07.090  4096  4109 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 15:13:07.090  4096  4096 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 15:13:07.093  4096  4109 D bt_stack_manager: event_clean_up_stack finished.
,09-13 15:13:07.095  4096  4096 I art     : System.exit called, status: 0
,09-13 15:13:07.095  4096  4096 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 15:13:07.145   874   884 I ActivityManager: Process com.android.bluetooth (pid 4096) has died
,09-13 15:13:09.608  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:13:09.609  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:12.616  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:12.617  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9cc571b added. We now have 6 listener(s)
09-13 15:13:12.617  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:12.621  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:12.621  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86d80b8 added. We now have 7 listener(s)
09-13 15:13:12.622  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:12.623  3775  3828 I System.out: IsBluetoothEnabled
,09-13 15:13:12.634  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:12.693   874   891 I ActivityManager: Start proc 4155:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 15:13:12.825  4155  4155 D AdapterServiceConfig: Adding HeadsetService
,09-13 15:13:12.826  4155  4155 D AdapterServiceConfig: Adding A2dpService
09-13 15:13:12.827  4155  4155 D AdapterServiceConfig: Adding HidService
09-13 15:13:12.828  4155  4155 D AdapterServiceConfig: Adding HealthService
,09-13 15:13:12.828  4155  4155 D AdapterServiceConfig: Adding PanService
09-13 15:13:12.829  4155  4155 D AdapterServiceConfig: Adding GattService
,09-13 15:13:12.830  4155  4155 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 15:13:12.852  4155  4155 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 15:13:12.852   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@903cd4b:true
,09-13 15:13:12.859  4155  4155 I bt_bluedroid: init
,09-13 15:13:12.860  4155  4167 I BluetoothAdapterState: Entering OffState
,09-13 15:13:12.863  4155  4168 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 15:13:12.863  4155  4168 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 15:13:12.863  4155  4168 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 15:13:12.864  4155  4168 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 15:13:12.865  4155  4155 I bt_bluedroid: get_profile_interface socket
,09-13 15:13:12.867  4155  4155 I bt_bluedroid: get_profile_interface sdp
,09-13 15:13:12.871  4155  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 15:13:12.872  4155  4166 I bt_bluedroid: config_hci_snoop_log
09-13 15:13:12.873  4155  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 15:13:12.875   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 15:13:12.882  4155  4167 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 15:13:12.882  4155  4167 D BluetoothAdapterProperties: Setting state to 14
,09-13 15:13:12.882  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 15:13:12.888  4155  4167 D BluetoothBondStateMachine: make
,09-13 15:13:12.892  4155  4172 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 15:13:12.897  4155  4167 I BluetoothAdapterState: Entering PendingCommandState
,09-13 15:13:12.901  4155  4155 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 15:13:12.909  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:12.911  4155  4155 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 15:13:12.912  4155  4155 D BtGatt.GattService: Received start request. Starting profile...
09-13 15:13:12.913  4155  4155 D BtGatt.GattService: start()
09-13 15:13:12.913  4155  4155 I bt_bluedroid: get_profile_interface gatt
,09-13 15:13:12.915  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
09-13 15:13:12.915  4155  4155 D BtGatt.AdvertiseManager: advertise manager created
,09-13 15:13:12.926  4155  4155 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:12.927  4155  4155 V BluetoothAdapterState: isTurningOn()=false
09-13 15:13:12.927  4155  4155 V BluetoothAdapterState: isBleTurningOn()=true
09-13 15:13:12.928  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:12.928  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 15:13:12.929  4155  4167 I bt_bluedroid: enable
,09-13 15:13:12.929  4155  4168 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 15:13:12.930  4155  4168 I bt_hci  : start_up
,09-13 15:13:12.949  4155  4168 I bt_vendor: alloc value 0xb3a43189
,09-13 15:13:12.950  4155  4168 I bt_vendor: init
,09-13 15:13:12.950  4155  4168 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-13 15:13:12.951  4155  4168 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 15:13:13.059  4155  4168 D bt_hci  : start_up starting async portion
09-13 15:13:13.060  4155  4175 I bt_hci  : event_finish_startup
09-13 15:13:13.060  4155  4175 I bt_hci_h4: hal_open
09-13 15:13:13.060  4155  4175 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 15:13:13.071  4155  4175 I bt_userial_vendor: device fd = 51 open
,09-13 15:13:13.101  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 15:13:13.133  4155  4175 D bt_hwcfg: Chipset BCM4354A2
09-13 15:13:13.133  4155  4175 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 15:13:13.134  4155  4175 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 15:13:13.702   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 15:13:13.714  1879  1879 I Keyboard.Facilitator: onFinishInput()
,09-13 15:13:13.728   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 15:13:13.728   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 15:13:13.728   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 15:13:13.728   874   894 I Adreno  : Local Branch                     : M14
09-13 15:13:13.728   874   894 I Adreno  : Remote Branch                    : 
09-13 15:13:13.728   874   894 I Adreno  : Remote Branch                    : 
09-13 15:13:13.728   874   894 I Adreno  : Reconstruct Branch               : 
,09-13 15:13:13.772   281  1472 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (318 us)
,09-13 15:13:13.824  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 15:13:13.828  4155  4175 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 15:13:13.828  4155  4175 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 15:13:13.945  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-13 15:13:13.946  4155  4175 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 15:13:13.974  4155  4175 I bt_hwcfg: vendor lib fwcfg completed
,09-13 15:13:13.976  4155  4175 I bt_vendor: firmware callback
,09-13 15:13:13.976  4155  4175 I bt_hci  : firmware_config_callback
,09-13 15:13:13.988  4155  4179 I bt_btu  : btu_task pending for preload complete event
,09-13 15:13:13.990  4155  4179 I bt_btu_task: Bluetooth chip preload is complete
,09-13 15:13:13.990  4155  4179 I bt_btu  : btu_task received preload complete event
,09-13 15:13:13.998  4155  4179 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 15:13:13.999  4155  4179 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 15:13:14.016  4155  4179 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 15:13:14.017  4155  4179 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 15:13:14.017  4155  4179 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 15:13:14.017  4155  4179 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 15:13:14.017  4155  4179 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 15:13:14.017  4155  4179 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 15:13:14.153  4155  4179 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c0d9d
,09-13 15:13:14.153  4155  4179 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c0d9d 
,09-13 15:13:14.185  4155  4171 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 15:13:14.186  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 15:13:14.187  4155  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 15:13:14.190  4155  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 15:13:14.198  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:14.199  4155  4171 D BluetoothAdapterProperties: Scan Mode:20
,09-13 15:13:14.199  4155  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:13:14.200  4155  4171 D bt_hci  : do_postload posting postload work item
09-13 15:13:14.200  4155  4175 I bt_hci  : event_postload
09-13 15:13:14.200  4155  4175 I bt_vendor: sco_config_cb
09-13 15:13:14.200  4155  4175 I bt_hci  : sco_config_callback postload finished.
09-13 15:13:14.202  4155  4175 I bt_vendor: low_power_mode_cb
09-13 15:13:14.203  4155  4171 D bt_bte_conf: Device ID record 1 : primary
09-13 15:13:14.203  4155  4171 D bt_bte_conf:   vendorId            = 000f
09-13 15:13:14.203  4155  4171 D bt_bte_conf:   vendorIdSource      = 0001
09-13 15:13:14.203  4155  4171 D bt_bte_conf:   product             = 1200
09-13 15:13:14.204  4155  4171 D bt_bte_conf:   version             = 1436
09-13 15:13:14.204  4155  4171 D bt_bte_conf:   clientExecutableURL = 
,09-13 15:13:14.204  4155  4171 D bt_bte_conf:   serviceDescription  = 
,09-13 15:13:14.204  4155  4171 D bt_bte_conf:   documentationURL    = 
,09-13 15:13:14.205  4155  4171 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 15:13:14.205  4155  4168 D bt_stack_manager: event_start_up_stack finished
,09-13 15:13:14.208  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 15:13:14.208  4155  4167 D BluetoothAdapterProperties: Setting state to 15
,09-13 15:13:14.208  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-13 15:13:14.209  4155  4167 I BluetoothAdapterState: Entering BleOnState
,09-13 15:13:14.212  4155  4167 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 15:13:14.212  4155  4167 D BluetoothAdapterProperties: Setting state to 11
09-13 15:13:14.212  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 15:13:14.219  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:14.220  4155  4155 D HeadsetService: Received start request. Starting profile...
09-13 15:13:14.222  4155  4155 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 15:13:14.223  4155  4155 D HeadsetStateMachine: make
09-13 15:13:14.223  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:14.236  4155  4167 I BluetoothAdapterState: Entering PendingCommandState
,09-13 15:13:14.236  4155  4155 D HeadsetStateMachine: max_hf_connections = 1
,09-13 15:13:14.237  4155  4155 I bt_bluedroid: get_profile_interface handsfree
09-13 15:13:14.237  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 15:13:14.237  4155  4171 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 15:13:14.239  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:14.240  4155  4155 D A2dpService: Received start request. Starting profile...
,09-13 15:13:14.241  4155  4155 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 15:13:14.241  4155  4155 I bt_bluedroid: get_profile_interface avrcp
,09-13 15:13:14.247  4155  4155 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 15:13:14.247  4155  4155 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 15:13:14.247  4155  4155 D A2dpStateMachine: make
,09-13 15:13:14.249  4155  4155 I bt_bluedroid: get_profile_interface a2dp
,09-13 15:13:14.249  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 15:13:14.251  4155  4188 D A2dpStateMachine: Enter Disconnected: -2
,09-13 15:13:14.251  4155  4155 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 15:13:14.252  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:14.252  4155  4155 D HidService: Received start request. Starting profile...
09-13 15:13:14.252  4155  4155 I bt_bluedroid: get_profile_interface hidhost
09-13 15:13:14.253  4155  4155 D HidService: setHidService(): set to: null
,09-13 15:13:14.253  4155  4171 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a23e5
09-13 15:13:14.253  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 15:13:14.255  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:14.255  4155  4155 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 15:13:14.257  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:14.257  4155  4155 D HealthService: Received start request. Starting profile...
,09-13 15:13:14.258  4155  4155 I bt_bluedroid: get_profile_interface health
,09-13 15:13:14.260  4155  4155 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 15:13:14.261  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:14.262  4155  4155 D PanService: Received start request. Starting profile...
09-13 15:13:14.262  4155  4155 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 15:13:14.262  4155  4155 I bt_bluedroid: get_profile_interface pan
09-13 15:13:14.263  4155  4171 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 15:13:14.265  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:14.266  4155  4155 D BluetoothMapService: Received start request. Starting profile...
09-13 15:13:14.266  4155  4155 D BluetoothMapService: start()
,09-13 15:13:14.268  4155  4155 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 15:13:14.268  4155  4155 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 15:13:14.268  4155  4155 D BluetoothMapAppObserver: createReceiver()
,09-13 15:13:14.269  4155  4155 D BluetoothMapAppObserver: initObservers()
,09-13 15:13:14.269  4155  4155 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 15:13:14.275  4155  4155 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:14.275  4155  4155 V BluetoothAdapterState: isTurningOn()=true
,09-13 15:13:14.275  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 15:13:14.275  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 15:13:14.277  4155  4185 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isTurningOff()=false
,09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isTurningOn()=true
,09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:14.278  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:14.279  4155  4155 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:14.279  4155  4155 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:14.279  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:14.279  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isTurningOff()=false
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isTurningOn()=true
09-13 15:13:14.280  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
09-13 15:13:14.281  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
09-13 15:13:14.281  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 15:13:14.281  4155  4167 D BluetoothAdapterProperties: ScanMode =  20
09-13 15:13:14.281  4155  4167 D BluetoothAdapterProperties: State =  11
09-13 15:13:14.283  4155  4171 D BluetoothAdapterProperties: Scan Mode:21
09-13 15:13:14.283  4155  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:13:14.283  4155  4167 D BluetoothAdapterProperties: Setting state to 12
09-13 15:13:14.283  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 15:13:14.284   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:14.285  3847  3861 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:13:14.286  1364  1377 D BluetoothMap: onBluetoothStateChange: up=true
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:14.286  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:14.287  4155  4167 I BluetoothAdapterState: Entering OnState
09-13 15:13:14.288  1364  2040 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 15:13:14.289  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:14.289  1364  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:13:14.289  1364  1364 D BluetoothMap: Proxy object connected
09-13 15:13:14.290  1364  1364 D MapProfile: Bluetooth service connected
,09-13 15:13:14.290  1364  1364 D BluetoothMap: getConnectedDevices()
09-13 15:13:14.291  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 15:13:14.291  1364  1364 D BluetoothA2dp: Proxy object connected
,09-13 15:13:14.293  3847  3857 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 15:13:14.295  4155  4155 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 15:13:14.295   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:13:14.295  4155  4155 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 15:13:14.296   874   874 D BluetoothA2dp: Proxy object connected
09-13 15:13:14.296   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:14.296   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 15:13:14.296  1364  2040 D BluetoothPan: onBluetoothStateChange on: true
,09-13 15:13:14.298  4155  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:13:14.299  3847  4147 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:13:14.299  3847  3861 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 15:13:14.300  4155  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:14.301  4155  4155 D ObexServerSockets: Succeed to create listening sockets 
09-13 15:13:14.301  4155  4155 D ObexServerSockets0: startAccept()
09-13 15:13:14.301  4155  4155 D ObexServerSockets0: prepareForNewConnect()
09-13 15:13:14.302  3847  3857 D BluetoothPan: onBluetoothStateChange on: true
,09-13 15:13:14.303  4155  4155 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-13 15:13:14.303  4155  4155 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 15:13:14.303  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 15:13:14.304  4155  4193 D ObexServerSockets0: Accepting socket connection...
09-13 15:13:14.304  4155  4194 D ObexServerSockets0: Accepting socket connection...
09-13 15:13:14.305  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 15:13:14.305  1364  1364 D PanProfile: Bluetooth service connected
,09-13 15:13:14.307  1364  1364 D BluetoothInputDevice: Proxy object connected
,09-13 15:13:14.308  1364  1364 D HidProfile: Bluetooth service connected
09-13 15:13:14.308  1956  2099 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 15:13:14.309  3847  3857 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 15:13:14.312  3847  3847 D BluetoothA2dp: Proxy object connected
,09-13 15:13:14.312   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 15:13:14.314  4155  4155 D BluetoothMapService: onReceive
09-13 15:13:14.314  4155  4155 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:14.314  4155  4155 D BluetoothMapService: STATE_ON
,09-13 15:13:14.315  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:14.316  3847  3847 D BluetoothMap: Proxy object connected
09-13 15:13:14.316  3847  3847 D MapProfile: Bluetooth service connected
09-13 15:13:14.316  3847  3847 D BluetoothMap: getConnectedDevices()
,09-13 15:13:14.318  3847  3847 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 15:13:14.318  3847  3847 D PanProfile: Bluetooth service connected
09-13 15:13:14.318  3847  3847 D BluetoothInputDevice: Proxy object connected
09-13 15:13:14.318  3847  3847 D HidProfile: Bluetooth service connected
,09-13 15:13:14.323  3847  3847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:13:14.328  3847  3847 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:14.331  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:14.349  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 15:13:14.349  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 15:13:14.378   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 15:13:14.380  1364  1364 D BluetoothPbap: Proxy object connected
,09-13 15:13:14.380  1364  1364 D PbapServerProfile: Bluetooth service connected
09-13 15:13:14.381  4155  4155 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 15:13:14.381  4155  4155 D ObexServerSockets0: prepareForNewConnect()
09-13 15:13:14.381  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7399b99 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a280e91, 16908290=android.view.AbsSavedState$1@a280e91}, android:focusedViewId=100}]}]
09-13 15:13:14.381  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-13 15:13:14.381  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 15:13:14.381  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-13 15:13:14.385   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-13 15:13:14.387  4155  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:13:14.387  3847  3847 D BluetoothPbap: Proxy object connected
09-13 15:13:14.387  3847  3847 D PbapServerProfile: Bluetooth service connected
09-13 15:13:14.388   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-13 15:13:14.388   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-13 15:13:14.388   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 15:13:14.405  1364  1377 D BluetoothHeadset: Proxy object connected
,09-13 15:13:14.405  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-13 15:13:14.406   874   874 D BluetoothHeadset: Proxy object connected
09-13 15:13:14.406  3847  3857 D BluetoothHeadset: Proxy object connected
,09-13 15:13:14.406   874   874 D BluetoothHeadset: Proxy object connected
,09-13 15:13:14.406  1956  1969 D BluetoothHeadset: Proxy object connected
,09-13 15:13:14.406   874   874 D BluetoothHeadset: Proxy object connected
,09-13 15:13:14.407  3847  3847 D HeadsetProfile: Bluetooth service connected
09-13 15:13:14.409  1956  1970 D BluetoothHeadset: Proxy object connected
09-13 15:13:14.411  4155  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:14.412  4155  4204 I BtOppRfcommListener: Accept thread started.
,09-13 15:13:14.632   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 15:13:14.635   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-13 15:13:14.636   874  1332 D SurfaceControl: Excessive delay in setPowerMode(): 247ms
,09-13 15:13:14.643   874   894 I DreamManagerService: Entering dreamland.
,09-13 15:13:14.645   874   894 I PowerManagerService: Dozing...
09-13 15:13:14.646   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:14.663  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:14.669  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:14.672  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:14.672  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca491f6 added. We now have 8 listener(s)
,09-13 15:13:14.672  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:14.675   874  1430 D WifiService: setWifiEnabled: false pid=3775, uid=10000
,09-13 15:13:14.675   874  1430 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 15:13:14.683  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:14.684   874  2039 D WifiService: setWifiEnabled: true pid=3775, uid=10000
,09-13 15:13:14.684   874  2039 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 15:13:14.687   874  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:14.695  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:14.696  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:14.697  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:14.700  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 15:13:14.701  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:14.701  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 15:13:14.703  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7399b99 Bundle[{}]
09-13 15:13:14.704  3775  3828 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 15:13:14.704  3775  3828 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 15:13:14.704  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 15:13:14.705  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
09-13 15:13:14.705  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 15:13:14.706  3775  3828 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 15:13:14.710  3775  3828 I System.out: Running OutgoingSocketThread
,09-13 15:13:14.711  3775  4211 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,09-13 15:13:14.711   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 15:13:14.711   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 15:13:14.712  3775  4211 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47908
09-13 15:13:14.712  3775  4211 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 15:13:14.718   874  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-13 15:13:14.719   874  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 15:13:14.719   874  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 15:13:14.720   874  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 15:13:14.720   874  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 15:13:14.720   874  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 15:13:14.721   874  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 15:13:14.726  1937  4212 D NfcService: Discovery configuration equal, not updating.
,09-13 15:13:14.737   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 15:13:14.737   874  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.18 rxSuccessRate=0.26 delta 1000 -> 1000
,09-13 15:13:14.738   372   872 D CommandListener: Setting iface cfg
,09-13 15:13:14.738   874  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-13 15:13:14.739   874  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 15:13:14.749   874  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 15:13:14.751   874  1304 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 15:13:14.755   874  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 15:13:14.755   874  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 15:13:14.766   874  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 15:13:14.766   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:13:14.775   874  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 15:13:14.836   376  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 15:13:14.836   376  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 15:13:14.881   874  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 15:13:14.884  1479  1479 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 15:13:14.905   874  1306 E native  : do suspend false
,09-13 15:13:14.917   874  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 15:13:14.919   874  1306 E native  : do suspend true
,09-13 15:13:14.976  1518  2279 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 15:13:15.309  1479  1479 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 15:13:15.345  1479  1479 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 15:13:15.345  1479  1479 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 15:13:15.350   874  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 15:13:15.359   874  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 15:13:15.359   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:13:15.359   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 15:13:15.379   874  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:13:15.391   372   872 D CommandListener: Setting iface cfg
,09-13 15:13:15.391   874  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 15:13:15.401   874  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 15:13:15.441   874  4219 D DhcpClient: Receive thread started
,09-13 15:13:15.529   874  1306 E native  : do suspend false
,09-13 15:13:15.549   874  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 15:13:15.565   874  4219 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-13 15:13:15.566   874  2102 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-13 15:13:15.571   874  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 15:13:15.586   874  4219 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 15:13:15.588   874  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 15:13:15.595   372   872 D CommandListener: Setting iface cfg
,09-13 15:13:15.605   874  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 15:13:15.607   874  1306 E native  : do suspend true
,09-13 15:13:15.610   874  2102 D DhcpClient: Scheduling renewal in 86399s
,09-13 15:13:15.623   874  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 15:13:15.625   874  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 15:13:15.627   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 15:13:15.628   874  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 15:13:15.635   874  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 15:13:15.699   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 15:13:15.699   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 15:13:15.702   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 15:13:15.706   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 15:13:15.709   874  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 15:13:15.711  3775  3828 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,09-13 15:13:15.712  3775  3828 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
09-13 15:13:15.714  3775  3828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,09-13 15:13:15.715  3775  3828 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 15:13:15.715  3775  3828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
09-13 15:13:15.718  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.718  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf49f7 added. We now have 2 listener(s)
09-13 15:13:15.721  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.721  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.721  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:13:15.722  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.722  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd5f064 added. We now have 9 listener(s)
09-13 15:13:15.722  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.722  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:13:15.727   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 15:13:15.728  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:15.732   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-13 15:13:15.733   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-13 15:13:15.733   874  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 15:13:15.734   874  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 15:13:15.734   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 15:13:15.734   874  1309 D ConnectivityService:    accepting network in place of null
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:15.735  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:15.736   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 15:13:15.738  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:15.738  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:15.739  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.739  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fd782 added. We now have 3 listener(s)
09-13 15:13:15.741  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.741  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.742  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.742  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.742  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a48e93 added. We now have 10 listener(s)
09-13 15:13:15.742  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.742  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:13:15.742  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:15.743  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:15.743  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.743  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.743  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.743  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.743  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf49f7 removed from the list
09-13 15:13:15.743  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.743  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd5f064 removed from the list
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:15.748  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:15.751  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.754  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.754  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:15.755  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.756  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.756  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.757   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-13 15:13:15.758  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.758  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.759  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.759  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd5f064 not in the list
09-13 15:13:15.759  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.760  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.761  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.762  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.762  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.762  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a48e93 removed from the list
09-13 15:13:15.762  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.763  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:13:15.763  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.763  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.763  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fd782 removed from the list
09-13 15:13:15.765  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.766  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33aed0 added. We now have 2 listener(s)
09-13 15:13:15.768   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 15:13:15.772  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.772  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.772  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.773  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.773  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@324fec9 added. We now have 9 listener(s)
09-13 15:13:15.773  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.775  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:13:15.779  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:15.782  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:15.784  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.784  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:15.784  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.784  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f80ef added. We now have 3 listener(s)
09-13 15:13:15.786  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.786  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.786  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.786  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.786  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.786  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ce7fc added. We now have 10 listener(s)
09-13 15:13:15.787  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.787  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:15.787  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:13:15.787  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:13:15.787  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:15.787  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:13:15.788  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.789  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 15:13:15.789  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:13:15.793  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 15:13:15.793  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 15:13:15.793  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:13:15.795  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:13:15.796  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 15:13:15.796  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:13:15.796  3775  3828 D BluetoothAdapter: STATE_ON
09-13 15:13:15.799  4155  4196 D BtGatt.GattService: registerClient() - UUID=2fdf1f96-52d8-46b5-8388-eebca7563003
,09-13 15:13:15.800   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 15:13:15.800  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=2fdf1f96-52d8-46b5-8388-eebca7563003, clientIf=5
09-13 15:13:15.800  3775  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 15:13:15.801  4155  4165 D BtGatt.GattService: start scan with filters
09-13 15:13:15.802   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 15:13:15.802   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:13:15.806   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 15:13:15.807   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 15:13:15.810  4155  4174 D BtGatt.ScanManager: handling starting scan
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:15.811  3775  3775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:13:15.812  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:13:15.812  4155  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@413729d
,09-13 15:13:15.812  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:13:15.812  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:13:15.812  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 15:13:15.813  3775  3775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.814  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 15:13:15.814  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.814  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 15:13:15.815  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.815  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:15.815  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 15:13:15.815  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:15.816  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 15:13:15.816  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.816  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:13:15.816  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 15:13:15.818  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 15:13:15.818  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 15:13:15.818  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.820  3775  3828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:13:15.820  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:15.820  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 15:13:15.820  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.820  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:13:15.820  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:13:15.820  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:13:15.821  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:13:15.821  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 15:13:15.821  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:13:15.821  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:13:15.821  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 15:13:15.821  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.821  3775  3828 D BluetoothAdapter: STATE_ON
09-13 15:13:15.824  4155  4166 D BtGatt.GattService: stopScan() - queue size =1
09-13 15:13:15.824  4155  4196 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 15:13:15.825  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:13:15.825  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 15:13:15.825  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:13:15.825  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:13:15.825  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 15:13:15.825  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 15:13:15.825  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.825  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
09-13 15:13:15.826  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:15.826  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 15:13:15.826  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:13:15.826  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:13:15.827  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.827  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 15:13:15.828  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.828  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 15:13:15.828  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:15.828  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:13:15.828  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:15.829   874  4216 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-13 15:13:15.830  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 15:13:15.830  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.830  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:13:15.830  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:15.830  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:13:15.831  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.831  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.831  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.831  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.831  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33aed0 removed from the list
09-13 15:13:15.831  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:13:15.831  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@324fec9 removed from the list
09-13 15:13:15.831  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:15.831  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.832  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.832  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.832  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:15.832  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.832  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.833  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@324fec9 not in the list
09-13 15:13:15.833  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:13:15.833  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.833  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.833  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.833  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.833  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ce7fc removed from the list
,09-13 15:13:15.834  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.834  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.834  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.834  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.834  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f80ef removed from the list
,09-13 15:13:15.834  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.834  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9e87e8 added. We now have 2 listener(s)
,09-13 15:13:15.836  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 15:13:15.836  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.836  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.836  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.836  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@958be01 added. We now have 9 listener(s)
09-13 15:13:15.836  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:15.837  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:13:15.838  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:15.839  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:15.842  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:13:15.843  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:13:15.843  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:15.844  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.844  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a309ee7 added. We now have 3 listener(s)
,09-13 15:13:15.845  1730  1730 D SystemUpdateService: onCreate
09-13 15:13:15.845  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:15.847  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.847  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.847  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.847  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:13:15.847  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.847  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c83a94 added. We now have 10 listener(s)
09-13 15:13:15.847  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.847  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:15.848  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-13 15:13:15.848  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:15.848  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 15:13:15.848  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:13:15.848  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:15.848  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:13:15.850  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 15:13:15.850  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:13:15.852  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:13:15.853  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 15:13:15.853  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:13:15.855  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:13:15.855  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:13:15.855  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 15:13:15.856  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:13:15.857  4155  4196 D BtGatt.GattService: registerClient() - UUID=0627236c-f1cc-419c-8898-705c07c28e7b
09-13 15:13:15.857  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=0627236c-f1cc-419c-8898-705c07c28e7b, clientIf=5
09-13 15:13:15.858  3775  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 15:13:15.858  4155  4165 D BtGatt.GattService: start scan with filters
,09-13 15:13:15.860  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:13:15.860  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 15:13:15.860  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:13:15.860  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 15:13:15.860  4155  4174 D BtGatt.ScanManager: handling starting scan
,09-13 15:13:15.862  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 15:13:15.862  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.862  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 15:13:15.862  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:15.863  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:15.863  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:13:15.863  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 15:13:15.863  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.863  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:13:15.863  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 15:13:15.864  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:13:15.865  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 15:13:15.865  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.866  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 15:13:15.866  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.866  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:15.866  3775  3828 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 15:13:15.867  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:13:15.867  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:15.867  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:15.867  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 15:13:15.867  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.867  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:13:15.867  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.867  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9e87e8 removed from the list
09-13 15:13:15.867  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:13:15.868  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@958be01 removed from the list
09-13 15:13:15.868  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:15.868  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.868  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.868  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-13 15:13:15.868  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.868  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.869  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.869  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.869  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:13:15.869  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@958be01 not in the list
09-13 15:13:15.869  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:13:15.869  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:13:15.869  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:13:15.869  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:13:15.869  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:13:15.870  3775  3828 D BluetoothAdapter: STATE_ON
09-13 15:13:15.870  4155  4186 D BtGatt.GattService: stopScan() - queue size =1
09-13 15:13:15.871  4155  4166 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 15:13:15.871  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:13:15.871  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:13:15.871  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:13:15.871  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:13:15.871  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 15:13:15.871  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 15:13:15.871  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.871  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
09-13 15:13:15.872  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:15.872  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 15:13:15.872  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:13:15.872  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 15:13:15.873  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.873  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 15:13:15.873  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.873  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.873  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:15.873  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c83a94 removed from the list
09-13 15:13:15.874  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:13:15.874  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:15.874  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.874  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.874  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 15:13:15.874  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.874  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 15:13:15.874  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.874  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.874  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a309ee7 removed from the list
09-13 15:13:15.875  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 15:13:15.875  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.876  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.876  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4386c00 added. We now have 2 listener(s)
,09-13 15:13:15.877  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 15:13:15.877  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.877  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.877  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.877  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ee2c39 added. We now have 9 listener(s)
09-13 15:13:15.877  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:15.877  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-13 15:13:15.878  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:13:15.880  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:15.882  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:13:15.884  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:13:15.884  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:15.884  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.884  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3883df added. We now have 3 listener(s)
,09-13 15:13:15.885  1730  4228 I SystemUpdateService: active receiver: enabled
,09-13 15:13:15.886  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:15.887  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 15:13:15.887  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.887  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.887  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:15.887  1730  2521 I iu.UploadsManager: num queued entries: 0
09-13 15:13:15.887  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8482c added. We now have 10 listener(s)
09-13 15:13:15.887  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.887  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:15.887  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:13:15.887  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:13:15.888  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:15.888  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:13:15.888  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.889  3775  3828 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 15:13:15.889  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:13:15.890  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 15:13:15.891  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 15:13:15.892  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 15:13:15.892  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 15:13:15.893  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:13:15.893  3903  3903 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-13 15:13:15.895  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:13:15.895  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:13:15.895  3775  3828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:13:15.895  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:13:15.897  4155  4186 D BtGatt.GattService: registerClient() - UUID=8eac6a33-08e1-416e-9025-923600423c7f
,09-13 15:13:15.898  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=8eac6a33-08e1-416e-9025-923600423c7f, clientIf=5
09-13 15:13:15.898   874  4216 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 13:13:15 GMT], X-Android-Received-Millis=[1473772395897], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473772395872]}
09-13 15:13:15.898  3775  3787 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 15:13:15.898  4155  4166 D BtGatt.GattService: start scan with filters
09-13 15:13:15.899   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 15:13:15.899   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-13 15:13:15.899   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 15:13:15.900   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 15:13:15.902  4155  4174 D BtGatt.ScanManager: handling starting scan
09-13 15:13:15.903  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 15:13:15.903  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:13:15.903  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:13:15.903  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 15:13:15.903  3903  3903 D SprintDMHelper: simOperator: 
,09-13 15:13:15.903  3903  3903 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 15:13:15.904  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 15:13:15.904  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.904  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 15:13:15.905  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:13:15.905  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:15.905  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:13:15.905  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 15:13:15.906  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.906  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:13:15.906  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 15:13:15.907  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:13:15.907  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 15:13:15.907  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.908  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 15:13:15.908  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.910  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:13:15.910  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:15.910  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:15.910  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.911  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:13:15.911  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:13:15.911  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.911  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4386c00 removed from the list
09-13 15:13:15.911  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.911  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ee2c39 removed from the list
,09-13 15:13:15.911  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:15.911  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.912  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.912  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 15:13:15.912  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.912  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:15.913  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.913  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.913  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.913  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ee2c39 not in the list
,09-13 15:13:15.913  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:13:15.913  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:13:15.913  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:13:15.913  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:13:15.913  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 15:13:15.914  3775  3828 D BluetoothAdapter: STATE_ON
,09-13 15:13:15.914  4155  4166 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:13:15.915  4155  4196 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 15:13:15.915  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 15:13:15.915  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:13:15.915  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 15:13:15.916  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 15:13:15.916  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:13:15.916  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.916  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 15:13:15.916  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:13:15.916  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:15.917  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 15:13:15.917  3775  3828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:13:15.917  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 15:13:15.917  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.917  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 15:13:15.918  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 15:13:15.918  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:13:15.918  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 15:13:15.918  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.918  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:15.918  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.918  3775  3775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:15.918  3775  3775 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:15.918  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8482c removed from the list
,09-13 15:13:15.918  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.918  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.918  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.918  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.918  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3883df removed from the list
09-13 15:13:15.919  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 15:13:15.919  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 15:13:15.919  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.919  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a77bb18 added. We now have 2 listener(s)
,09-13 15:13:15.921  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.921  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.921  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:15.921  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:15.921  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c2971 added. We now have 9 listener(s)
09-13 15:13:15.921  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.922  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:13:15.923  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:15.927  1730  4231 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:15.927  3775  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:15.927  1730  4231 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 15:13:15.928  3775  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:15.928  3775  3828 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:13:15.929  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:15.929  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c90fd7 added. We now have 3 listener(s)
,09-13 15:13:15.930  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:15.930  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 15:13:15.930  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:15.930  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:13:15.931  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:15.931  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b970c4 added. We now have 10 listener(s)
09-13 15:13:15.931  3775  3828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:15.931  3775  3828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:13:15.931  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:15.931  3775  3828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:15.931  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.931  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.931  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:15.931  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.931  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a77bb18 removed from the list
,09-13 15:13:15.931  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.931  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c2971 removed from the list
09-13 15:13:15.932  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:15.932  3775  3828 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:13:15.932  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.932  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.932  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.933  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:15.933  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.933  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.933  3775  3828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8c2971 not in the list
09-13 15:13:15.933  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.933  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.933  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:15.933  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:15.933  3775  3828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:15.934  3775  3828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b970c4 removed from the list
09-13 15:13:15.934  3775  3828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:15.934  3775  3828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:15.934  3775  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:15.934  3775  3828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:15.934  3775  3828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c90fd7 removed from the list
,09-13 15:13:15.934  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 15:13:15.935  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 15:13:15.935  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 15:13:15.935  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:15.935  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 15:13:15.935  3775  3828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:13:15.936  1730  4231 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 15:13:15.939  3775  4236 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
,09-13 15:13:15.939  3775  4236 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
09-13 15:13:15.939  3775  4236 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 15:13:15.941  3775  4237 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,09-13 15:13:15.941  3775  4237 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
09-13 15:13:15.941  3775  4237 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 15:13:15.942  3775  3828 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-13 15:13:15.942  3775  3828 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 15:13:15.942  3775  3828 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 15:13:15.942  3775  3828 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 15:13:15.942  3775  3828 D com.test.thalitest.ThaliTestRunner: Total duration: 21874 ms
,09-13 15:13:15.943  3775  3828 I jxcore-log: *Native tests were executed*
09-13 15:13:15.943  3775  3828 I jxcore-log: 
,09-13 15:13:15.944  3775  3828 I jxcore-log: Total number of executed tests:  80
09-13 15:13:15.944  3775  3828 I jxcore-log: 
09-13 15:13:15.944  3775  3828 I jxcore-log: Number of passed tests:  80
09-13 15:13:15.944  3775  3828 I jxcore-log: 
09-13 15:13:15.944  3775  3828 I jxcore-log: Number of failed tests:  0
09-13 15:13:15.944  3775  3828 I jxcore-log: 
09-13 15:13:15.944  3775  3828 I jxcore-log: Number of ignored tests:  0
09-13 15:13:15.944  3775  3828 I jxcore-log: 
09-13 15:13:15.944  3775  3828 I jxcore-log: Total duration:  21874
09-13 15:13:15.944  3775  3828 I jxcore-log: 
,09-13 15:13:15.944  3775  3828 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 15:13:15.944  3775  3828 I jxcore-log: 
,09-13 15:13:15.947  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.947  3775  3828 I jxcore-log: 
09-13 15:13:15.950  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.950  3775  3828 I jxcore-log: 
09-13 15:13:15.951  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.951  3775  3828 I jxcore-log: 
09-13 15:13:15.951  3775  3775 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 15:13:15.952  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.952  3775  3828 I jxcore-log: 
09-13 15:13:15.952  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.952  3775  3828 I jxcore-log: 
09-13 15:13:15.954  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.954  3775  3828 I jxcore-log: 
,09-13 15:13:15.955  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.955  3775  3828 I jxcore-log: 
09-13 15:13:15.956  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.956  3775  3828 I jxcore-log: 
,09-13 15:13:15.957  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.957  3775  3828 I jxcore-log: 
09-13 15:13:15.958  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.958  3775  3828 I jxcore-log: 
09-13 15:13:15.954  1730  2521 I iu.UploadsManager: num updated entries: 0
09-13 15:13:15.958  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.958  3775  3828 I jxcore-log: 
09-13 15:13:15.959  1730  2521 I iu.SyncManager: NEXT; no task
09-13 15:13:15.959  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:15.959  3775  3828 I jxcore-log: 
09-13 15:13:15.960  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 15:13:15.960  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.960  3775  3828 I jxcore-log: 
09-13 15:13:15.961  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.961  3775  3828 I jxcore-log: 
09-13 15:13:15.961  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.961  3775  3828 I jxcore-log: 
09-13 15:13:15.962  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.962  3775  3828 I jxcore-log: 
09-13 15:13:15.963  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.963  3775  3828 I jxcore-log: 
09-13 15:13:15.963  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.963  3775  3828 I jxcore-log: 
,09-13 15:13:15.964  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.964  3775  3828 I jxcore-log: 
09-13 15:13:15.964  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 15:13:15.964  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.964  3775  3828 I jxcore-log: 
09-13 15:13:15.965  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.965  3775  3828 I jxcore-log: 
09-13 15:13:15.966  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.966  3775  3828 I jxcore-log: 
,09-13 15:13:15.966  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.966  3775  3828 I jxcore-log: 
,09-13 15:13:15.967  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:15.967  3775  3828 I jxcore-log: 
09-13 15:13:15.967  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.967  3775  3828 I jxcore-log: 
,09-13 15:13:15.968  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.968  3775  3828 I jxcore-log: 
09-13 15:13:15.968  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.968  3775  3828 I jxcore-log: 
09-13 15:13:15.969  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:15.969  3775  3828 I jxcore-log: 
,09-13 15:13:15.970  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.970  3775  3828 I jxcore-log: 
09-13 15:13:15.970  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.970  3775  3828 I jxcore-log: 
09-13 15:13:15.971  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.971  3775  3828 I jxcore-log: 
,09-13 15:13:15.971  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.971  3775  3828 I jxcore-log: 
09-13 15:13:15.972  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:15.972  3775  3828 I jxcore-log: 
,09-13 15:13:15.971  1730  4228 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 15:13:15.979  1730  4228 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 15:13:15.979  1730  4228 I SystemUpdateService: now status is 0 (complete)
09-13 15:13:15.979  1730  4228 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 15:13:15.979  1730  4228 I SystemUpdateService: file has been verified
09-13 15:13:15.979  1730  4228 I SystemUpdateService: OTA package size = 12249756
,09-13 15:13:15.993  1518  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 15:13:15.993  1518  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 15:13:15.993  1518  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 15:13:15.994  1518  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 15:13:15.997  1730  4228 I SystemUpdateService: showing system update notification
,09-13 15:13:16.006  1730  1730 D SystemUpdateService: onDestroy
,09-13 15:13:16.008  1730  4231 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-13 15:13:16.087  2263  4234 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 15:13:16.328  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:13:16.330  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:16.330  3775  3828 I jxcore-log: 
,09-13 15:13:16.374  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:13:16.376  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:16.376  3775  3828 I jxcore-log: 
,09-13 15:13:16.419  3775  3775 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:13:16.421  3775  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:16.421  3775  3828 I jxcore-log: 
,09-13 15:13:16.546  4241  4241 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 15:13:16.551  4241  4241 D AndroidRuntime: CheckJNI is OFF
,09-13 15:13:16.594  4241  4241 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 15:13:16.642  4241  4241 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 15:13:16.664  4241  4241 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 15:13:16.676   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 15:13:16.677   874   887 I ActivityManager: Killing 3775:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 15:13:16.759   874  1988 D GraphicsStats: Buffer count: 2
,09-13 15:13:16.759   874   885 I WindowState: WIN DEATH: Window{d04807b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 15:13:16.760   874  1308 D WifiService: Client connection lost with reason: 4
,09-13 15:13:16.803   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 15:13:16.827   874   897 W PackageSettings: Skipping PackageSetting{2c3de56 com.example.hello/10273} due to missing metadata
,09-13 15:13:16.867   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-13 15:13:16.867   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 15:13:16.868   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-13 15:13:16.868   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 15:13:16.868   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:16.868   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:16.868   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 15:13:16.868   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 15:13:16.868   874   887 I ActivityManager:   Force finishing activity ActivityRecord{4159120 u0 com.test.thalitest/.MainActivity t4}
,09-13 15:13:16.871   874   897 I art     : Starting a blocking GC Explicit
,09-13 15:13:16.879   874  2039 W ActivityManager: Spurious death for ProcessRecord{cac6ccb 0:com.test.thalitest/u0a0}, curProc for 3775: null
,09-13 15:13:16.919   874   897 I art     : Explicit concurrent mark sweep GC freed 50064(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 736us total 46.758ms
,09-13 15:13:16.979   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 15:13:16.982  4241  4241 I art     : System.exit called, status: 0
,09-13 15:13:16.982  4241  4241 I AndroidRuntime: VM exiting with result code 0.
,09-13 15:13:16.986   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 15:13:17.013   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 15:13:17.036  1879  1879 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 15:13:17.037  4155  4155 D BluetoothMapAppObserver: onReceive
09-13 15:13:17.037  4155  4155 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 15:13:17.043  1879  4255 I Keyboard.Facilitator.DecoderInitializer: run()
09-13 15:13:17.045  1892  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 15:13:17.051   874  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 15:13:17.055  1879  4255 I Decoder : createOrResetDecoder
,09-13 15:13:17.064  3617  3617 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 15:13:17.082   874  1373 I ActivityManager: Start proc 4257:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 15:13:17.112  1956  1956 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 15:13:17.114  1518  1518 I ConfigService: onCreate
,09-13 15:13:17.117  1518  4269 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 15:13:17.117  1518  4269 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 15:13:17.118  1518  4269 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818),
,09-13 15:13:17.119  1518  4269 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-13 15:13:17.131  1879  4255 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 15:13:17.139   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 15:13:17.151   874  1988 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3775 uid 10000
,09-13 15:13:17.152  1879  1879 I Keyboard.Facilitator: onFinishInput()
,09-13 15:13:17.156  4257  4257 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 15:13:17.178  1879  4255 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 15:13:17.181  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-13 15:13:17.181  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 15:13:17.184  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 15:13:17.184  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-13 15:13:17.187  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-13 15:13:17.187  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-13 15:13:17.189  1879  4255 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-13 15:13:17.189  1879  4255 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 15:13:17.189  1879  4255 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 15:13:17.189  1879  4255 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-13 15:13:17.189  1879  4255 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 15:13:17.189  1879  4255 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 15:13:17.192  1971  2052 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-13 15:13:17.195   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 15:13:17.195   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 15:13:17.195   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 15:13:17.195   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 15:13:17.195   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 15:13:17.195   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 15:13:17.195   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 15:13:17.195   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.195   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.195   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:17.203   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 15:13:17.203   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 15:13:17.203   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 15:13:17.203   874   887 E DropBoxManagerService: 	... 13 more
,09-13 15:13:17.205   874   885 I ActivityManager: Start proc 4274:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-13 15:13:17.205  1971  2052 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 15:13:17.205  1971  2052 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1971
09-13 15:13:17.205  1971  2052 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.205  1971  2052 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:17.208   874  3107 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 15:13:17.208   874  4279 E DropBoxManagerService: Can't write: system_app_crash
09-13 15:13:17.208   874  4279 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 15:13:17.208   874  4279 E DropBoxManagerService: 	... 5 more
,09-13 15:13:17.215   874  1333 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
09-13 15:13:17.215   874  1333 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-13 15:13:17.215   874  1333 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-13 15:13:17.215   874  1333 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
09-13 15:13:17.215   874  1333 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
,09-13 15:13:17.215   874  1333 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
09-13 15:13:17.215   874  1333 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-13 15:13:17.216   874  1333 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
09-13 15:13:17.216   874  1333 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,09-13 15:13:17.216   874  1333 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-13 15:13:17.216   874  1333 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-13 15:13:17.216   874  1333 W System.err: 	... 4 more
09-13 15:13:17.216   874  1333 D skia    : ------- write threw an exception
,09-13 15:13:17.224  1971  2052 I Process : Sending signal. PID: 1971 SIG: 9
,09-13 15:13:17.230  4257  4257 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 15:13:17.252  4257  4288 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 15:13:17.257   874  1373 I ActivityManager: Start proc 4289:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 15:13:17.281   874  1423 D GraphicsStats: Buffer count: 1
,09-13 15:13:17.281   874  1430 I WindowState: WIN DEATH: Window{f807a82 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-13 15:13:17.293   874  1975 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1971) has died
,09-13 15:13:17.293   874  1975 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-13 15:13:17.295   874  1975 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 15:13:17.298  4289  4289 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 15:13:17.311   874   887 I ActivityManager: Start proc 4302:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 15:13:17.326  1518  1518 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-13 15:13:17.327  1518  1518 D AndroidRuntime: Shutting down VM
,09-13 15:13:17.330  1518  1518 E AndroidRuntime: FATAL EXCEPTION: main
09-13 15:13:17.330  1518  1518 E AndroidRuntime: Process: com.google.process.gapps, PID: 1518
09-13 15:13:17.330  1518  1518 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 15:13:17.330  1518  1518 E AndroidRuntime: 	... 8 more
,09-13 15:13:17.337   874  4317 E DropBoxManagerService: Can't write: system_app_crash
09-13 15:13:17.337   874  4317 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 15:13:17.337   874  4317 E DropBoxManagerService: 	... 5 more
,09-13 15:13:17.339  1518  1518 I Process : Sending signal. PID: 1518 SIG: 9
,09-13 15:13:17.343  4257  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.343  4257  4272 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:17.360   874  1430 I ActivityManager: Killing 3679:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:13:17.361  4302  4302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:13:17.362  4302  4302 D AndroidRuntime: Shutting down VM
,09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.366  4257  4272 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:17.393  4257  4272 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-13 15:13:17.397  4257  4288 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.397  4257  4288 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:17.398   874  1308 D WifiService: Client connection lost with reason: 4
,09-13 15:13:17.401  4257  4288 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 15:13:17.401  4257  4288 E AndroidRuntime: Process: android.process.acore, PID: 4257
09-13 15:13:17.401  4257  4288 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.401  4257  4288 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:17.402  4257  4272 I Process : Sending signal. PID: 4257 SIG: 9
,09-13 15:13:17.415   874  1423 I ActivityManager: Process com.google.process.gapps (pid 1518) has died
,09-13 15:13:17.416   874  1423 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-13 15:13:17.416   874  1423 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,09-13 15:13:17.416   874  1423 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
09-13 15:13:17.416   874  1423 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
09-13 15:13:17.420  1730  1730 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-13 15:13:17.421  4302  4302 E AndroidRuntime: FATAL EXCEPTION: main
09-13 15:13:17.421  4302  4302 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4302
09-13 15:13:17.421  4302  4302 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 15:13:17.421  4302  4302 E AndroidRuntime: 	... 10 more
,09-13 15:13:17.430   874  2039 I ActivityManager: Start proc 4320:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-13 15:13:17.434   874  3109 I ActivityManager: Process android.process.acore (pid 4257) has died
,09-13 15:13:17.434   874  3109 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40982ms
,09-13 15:13:17.436   874   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 15:13:17.438  4302  4302 I Process : Sending signal. PID: 4302 SIG: 9
,09-13 15:13:17.441   874  4330 E DropBoxManagerService: Can't write: system_app_crash
09-13 15:13:17.441   874  4330 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 15:13:17.441   874  4330 E DropBoxManagerService: 	... 5 more
,09-13 15:13:17.443   874  4333 E DropBoxManagerService: Can't write: system_app_crash
09-13 15:13:17.443   874  4333 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 15:13:17.443   874  4333 E DropBoxManagerService: 	... 5 more
,09-13 15:13:17.458  4320  4320 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-13 15:13:17.463  4320  4320 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-13 15:13:17.465   874  2214 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4302) has died
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:13:17.465  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:13:17.466  4320  4320 D AndroidRuntime: Shutting down VM
09-13 15:13:17.466   874  2214 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-13 15:13:17.466  4320  4320 E AndroidRuntime: FATAL EXCEPTION: main
09-13 15:13:17.466  4320  4320 E AndroidRuntime: Process: com.google.process.gapps, PID: 4320
09-13 15:13:17.466  4320  4320 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 15:13:17.466  4320  4320 E AndroidRuntime: 	... 10 more

```
