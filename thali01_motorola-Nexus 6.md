#### Test 832729920321fb3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-30 17:24:26.315   874  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-30 17:24:26.991  3826  3826 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 17:24:26.995  3826  3826 D AndroidRuntime: CheckJNI is OFF
08-30 17:24:27.031  3826  3826 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 17:24:27.073  3826  3826 I Radio-JNI: register_android_hardware_Radio DONE
08-30 17:24:27.094  3826  3826 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 17:24:27.105   874  1678 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:24:27.163  2000  2011 W SearchService: Abort, client detached.
08-30 17:24:27.170  2000  2312 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8cca676
08-30 17:24:27.170  2000  2000 I HotwordDetector: Closing mic
08-30 17:24:27.170  2000  2337 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 17:24:27.175  3826  3826 D AndroidRuntime: Shutting down VM
08-30 17:24:27.188   874  1949 I ActivityManager: Start proc 3835:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 17:24:27.235   376  2339 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 17:24:27.238   376  2339 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 17:24:27.245   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 17:24:27.248  2000  2322 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 17:24:27.248  2000  2335 I MicroRecognitionRnrImpl: Detection finished
08-30 17:24:27.294  3835  3835 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 17:24:27.319  3835  3835 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 17:24:27.326  3835  3835 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7399-7401)
08-30 17:24:27.326  3835  3835 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:24:27.341  3835  3835 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6853125}
08-30 17:24:27.342  3835  3835 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:24:27.342  3835  3835 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:24:27.349  3835  3835 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 17:24:27.350  3835  3835 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 17:24:27.364  3835  3835 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 17:24:27.373  3835  3835 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:24:27.373  3835  3835 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:24:27.374  3835  3835 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:24:27.374  3835  3835 I Adreno  : Build Date                       : 10/20/15
08-30 17:24:27.374  3835  3835 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:24:27.374  3835  3835 I Adreno  : Local Branch                     : M14
08-30 17:24:27.374  3835  3835 I Adreno  : Remote Branch                    : 
08-30 17:24:27.374  3835  3835 I Adreno  : Remote Branch                    : 
08-30 17:24:27.374  3835  3835 I Adreno  : Reconstruct Branch               : 
,08-30 17:24:27.423   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b58192:true
,08-30 17:24:27.468  3835  3835 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 17:24:27.481  3835  3835 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 17:24:27.564  3835  3873 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 17:24:27.574  3835  3860 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 17:24:27.612  3835  3873 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:24:27.704   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +530ms
,08-30 17:24:27.708  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-30 17:24:27.802  3835  3835 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3835
,08-30 17:24:27.951  3835  3835 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:24:28.035   874   885 I ActivityManager: Killing 3407:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 17:24:28.079   874   885 I ActivityManager: Killing 3564:com.google.process.gapps/u0a99 (adj 15): empty #18
,08-30 17:24:28.179  3835  3875 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680148176
08-30 17:24:28.189  3835  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:24:28.189  3835  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:24:28.189  3835  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:24:28.189  3835  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:24:28.189  3835  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:24:28.190  3835  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6a07e0 added. We now have 1 listener(s)
08-30 17:24:28.192  3835  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 17:24:28.193  3835  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 17:24:28.194  3835  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:24:28.194  3835  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:24:28.197  3835  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e24393f added. We now have 1 listener(s)
08-30 17:24:28.197  3835  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:24:28.202   874  1307 D WifiService: New client listening to asynchronous messages
08-30 17:24:28.206  3835  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:24:28.206  3835  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:24:28.207  3835  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:24:28.207  3835  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:24:28.208  3835  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:24:28.211  3835  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:24:28.212  3835  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-30 17:24:28.219  3835  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:24:28.219  3835  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:24:28.219  3835  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:24:28.219  3835  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:24:28.221  3835  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:24:28.223  3835  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:24:28.225  3835  3875 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:24:28.454  3835  3835 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 17:24:29.340   874  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-30 17:24:29.594  3835  3883 W jxcore-log: Initializing JXcore engine
08-30 17:24:29.594  3835  3883 W jxcore-log: JXcore engine is ready
08-30 17:24:29.629  3883  3883 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-30 17:24:29.629  3883  3883 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10698]" dev="sockfs" ino=10698 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 17:24:29.629  3883  3883 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:24:29.629  3883  3883 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26833]" dev="sockfs" ino=26833 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-30 17:24:29.644  3835  3883 W jxcore-log: Starting JXcore engine
08-30 17:24:29.722  3835  3883 W jxcore-log: Platform android
08-30 17:24:29.722  3835  3883 W jxcore-log: 
08-30 17:24:29.722  3835  3883 W jxcore-log: Process ARCH arm
08-30 17:24:29.722  3835  3883 W jxcore-log: 
08-30 17:24:29.914  3835  3883 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:24:29.914  3835  3883 I jxcore-log: 
08-30 17:24:29.915  3835  3883 W jxcore-log: JXcore engine is started
08-30 17:24:29.923  3835  3875 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 17:24:29.930  3835  3835 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:24:32.673   874  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 17:24:35.384   874  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 17:24:37.209  1565  1565 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:24:37.211  1565  1565 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 17:24:37.268  1565  1579 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 17:24:37.268  1565  1579 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 17:24:37.268  1565  1579 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:24:37.268  1565  1579 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:24:37.284  3550  3893 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 17:24:37.284  3550  3893 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jdm.a(PG:82)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jcs.o(PG:406)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jcn.a(PG:1379)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jcs.i(PG:143)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at blb.a(PG:3937)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at czp.a(PG:18188)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at czp.a(PG:9081)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at czq.run(PG:1686)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:37.284  3550  3893 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jdj.a(PG:4091)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jdj.a(PG:1125)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jdm.a(PG:77)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	... 12 more
08-30 17:24:37.284  3550  3893 E HttpOperation: Caused by: faj: BadAuthentication
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at fal.a(PG:38)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	at jdj.a(PG:4089)
08-30 17:24:37.284  3550  3893 E HttpOperation: 	... 14 more
,08-30 17:24:37.313  1565  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 17:24:37.313  1565  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 17:24:37.314  1565  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 17:24:37.314  1565  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 17:24:37.326  3550  3893 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 17:24:37.326  3550  3893 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jdm.a(PG:82)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jcs.o(PG:406)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jcn.a(PG:1379)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jcs.i(PG:143)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at hec.a(PG:42)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at hee.a(PG:102)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at czr.a(PG:65)
,08-30 17:24:37.326  3550  3893 E HttpOperation: 	at kka.a(PG:108)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at czp.a(PG:19176)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at czp.a(PG:9081)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at czq.run(PG:1686)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:37.326  3550  3893 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jdj.a(PG:4091)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jdj.a(PG:1125)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jdm.a(PG:77)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	... 15 more
08-30 17:24:37.326  3550  3893 E HttpOperation: Caused by: faj: BadAuthentication
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at fal.a(PG:38)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	at jdj.a(PG:4089)
08-30 17:24:37.326  3550  3893 E HttpOperation: 	... 17 more
08-30 17:24:37.326  3550  3893 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 17:24:37.326  3550  3893 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at hec.a(PG:42)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at hee.a(PG:102)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at czr.a(PG:65)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at kka.a(PG:108)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	... 15 more
08-30 17:24:37.326  3550  3893 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at fal.a(PG:38)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 17:24:37.326  3550  3893 E ExperimentLoader: 	... 17 more
,08-30 17:24:37.437   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127070, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 17:24:41.450   874  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 17:24:44.142  3835  3883 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:24:44.142  3835  3883 I jxcore-log: 
,08-30 17:24:44.145  3835  3883 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:24:44.145  3835  3883 I jxcore-log: 
,08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:24:44.155  3835  3883 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:24:44.163  3835  3883 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:24:44.170  3835  3883 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:24:44.170  3835  3883 I jxcore-log: 
,08-30 17:24:44.179  3835  3883 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:24:44.179  3835  3883 I jxcore-log: 
,08-30 17:24:44.532  3835  3883 I jxcore-log: Running unit tests
08-30 17:24:44.532  3835  3883 I jxcore-log: 
,08-30 17:24:44.533  3835  3883 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-30 17:24:44.533  3835  3883 I jxcore-log: Failed to execute UT.
08-30 17:24:44.533  3835  3883 I jxcore-log: 
,08-30 17:24:44.534  3835  3883 I jxcore-log: Unit Test app is loaded
08-30 17:24:44.534  3835  3883 I jxcore-log: 
08-30 17:24:44.540  3835  3883 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:24:44.540  3835  3883 I jxcore-log: 
,08-30 17:24:44.544  3835  3883 I jxcore-log: My device name is: motorola-Nexus 6
08-30 17:24:44.544  3835  3883 I jxcore-log: 
08-30 17:24:44.545  3835  3883 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 17:24:44.545  3835  3883 I jxcore-log: 
,08-30 17:24:44.567  3835  3835 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 17:24:46.976  3835  3883 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 17:24:46.976  3835  3883 I jxcore-log: 
,08-30 17:24:47.414  3835  3883 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 17:24:47.414  3835  3883 I jxcore-log: 
,08-30 17:24:47.438  3835  3883 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 17:24:47.438  3835  3883 I jxcore-log: 
,08-30 17:24:47.511   874  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 17:24:48.835  3835  3883 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 17:24:48.835  3835  3883 I jxcore-log: 
,08-30 17:24:49.066  3835  3883 I jxcore-log: ERROR runTests: 
08-30 17:24:49.066  3835  3883 I jxcore-log: 
,08-30 17:24:49.069  3835  3883 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:24:49.069  3835  3883 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 17:24:49.070  3835  3883 I jxcore-log: WARN testUtils: logCallback not set!
08-30 17:24:49.070  3835  3883 I jxcore-log: 
,08-30 17:24:49.080  3835  3883 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _functionName: 'loadFile',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _lineNumber: '26',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _columnNumber: '11',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 17:24:49.080  3835  3883 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _functionName: '',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _lineNumber: '38',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _columnNumber: '7',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 17:24:49.080  3835  3883 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _functionName: '',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _lineNumber: '35',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _columnNumber: '3',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 17:24:49.080  3835  3883 I jxcore-log:   { _fileName: 'module.js',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _lineNumber: '621',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _columnNumber: '8',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 17:24:49.080  3835  3883 I jxcore-log:   { _fileName: 'module.js',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _lineNumber: '651',
08-30 17:24:49.080  3835  3883 I jxcore-log:     _columnNumber: '1',
08-30 17:24:49.080  3835  3883 I jxcore-log:    
,08-30 17:24:49.080  3835  3883 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 17:24:49.080  3835  3883 I jxcore-log: 
,08-30 17:24:49.080  3835  3883 E jxcore-log: Error: 
08-30 17:24:49.080  3835  3883 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:24:49.080  3835  3883 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 17:24:49.080  3835  3883 E jxcore-log: 
,08-30 17:24:49.679  3899  3899 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 17:24:49.684  3899  3899 D AndroidRuntime: CheckJNI is OFF
,08-30 17:24:49.720  3899  3899 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 17:24:49.763  3899  3899 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 17:24:49.783  3899  3899 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:24:49.796   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 17:24:49.796   874   887 I ActivityManager: Killing 3835:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 17:24:49.877   874  1297 W InputDispatcher: channel '61d7342 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-30 17:24:49.877   874  1297 E InputDispatcher: channel '61d7342 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-30 17:24:49.882   874  1383 D GraphicsStats: Buffer count: 2
,08-30 17:24:49.883   874  1307 D WifiService: Client connection lost with reason: 4
,08-30 17:24:49.885   874  2193 I WindowState: WIN DEATH: Window{61d7342 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:24:49.886   874  2193 W InputDispatcher: Attempted to unregister already unregistered input channel '61d7342 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,08-30 17:24:49.902   874   887 W ActivityManager: Force removing ActivityRecord{fbcb7fb u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-30 17:24:49.921   874   897 W PackageSettings: Skipping PackageSetting{193c458 com.example.hello/10273} due to missing metadata
,08-30 17:24:49.955   874   897 I art     : Starting a blocking GC Explicit
08-30 17:24:49.955   874   885 W ActivityManager: Spurious death for ProcessRecord{a61fbfa 0:com.test.thalitest/u0a0}, curProc for 3835: null
,08-30 17:24:50.005   874  1678 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3835 uid 10000
,08-30 17:24:50.009  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-30 17:24:50.022   874   897 I art     : Explicit concurrent mark sweep GC freed 49335(3MB) AllocSpace objects, 15(336KB) LOS objects, 33% free, 29MB/43MB, paused 1.062ms total 64.388ms
,08-30 17:24:50.027   874   883 I art     : WaitForGcToComplete blocked for 6.455ms for cause Background
,08-30 17:24:50.051   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 17:24:50.055  3899  3899 I art     : System.exit called, status: 0
,08-30 17:24:50.055  3899  3899 I AndroidRuntime: VM exiting with result code 0.
,08-30 17:24:50.076  2000  3914 I MicroRecognitionRnrImpl: Starting detection.
,08-30 17:24:50.081   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 17:24:50.083  2000  3915 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@e72688f
,08-30 17:24:50.086   376  3918 I AudioFlinger: AudioFlinger's thread 0xb1c80000 ready to run
,08-30 17:24:50.092   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-30 17:24:50.093  2000  3915 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@e72688f
,08-30 17:24:50.102   376  3918 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-30 17:24:50.103   376  3918 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-30 17:24:50.103   376  3918 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-30 17:24:50.104  2634  2634 D BluetoothMapAppObserver: onReceive
,08-30 17:24:50.104  2634  2634 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 17:24:50.107   874  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 17:24:50.107  2195  2302 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:24:50.109   376  3918 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-30 17:24:50.120  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 17:24:50.123  1874  3920 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 17:24:50.126  1874  3920 I Decoder : createOrResetDecoder
,08-30 17:24:50.161  1934  1934 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 17:24:50.166  3643  3643 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 17:24:50.188  2000  2000 I HotwordWorkerImpl: onReady
,08-30 17:24:50.188   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:24:50.195  1565  1565 I ConfigService: onCreate
,08-30 17:24:50.205  1565  1565 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-30 17:24:50.205  1565  1565 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-30 17:24:50.208  3496  3922 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 17:24:50.211  1874  3920 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 17:24:50.223  1748  3927 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 17:24:50.224  1748  3927 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 17:24:50.229  3496  3510 E SQLiteLog: (1034) os_unix.c:29052: (30) full_fsync(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjAB71BD9C6) - 
,08-30 17:24:50.229  3496  3510 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjAB71BD9C6) - 
,08-30 17:24:50.233  1748  3927 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-30 17:24:50.240  1748  3931 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 17:24:50.240  1748  3931 E DriveAsyncService: disk I/O error (code 3850)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:24:50.240  1748  3931 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:50.242  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 17:24:50.242  1748  1748 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	a,t android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.244  1748  3927 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.244  1748  3927 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.246  1748  3927 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-30 17:24:50.247  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 17:24:50.247  1748  1748 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-30 17:24:50.251  2000  3935 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 17:24:50.253  1748  3936 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.256  1748  3932 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.256  1748  3932 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.258  1748  3932 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-30 17:24:50.258  1748  3932 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-30 17:24:50.258  1748  3932 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-30 17:24:50.259  1748  3932 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-30 17:24:50.259  1748  3932 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
08-30 17:24:50.259  1748  3932 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-30 17:24:50.259  1748  3932 E AndroidRuntime: Process: com.google.android.gms, PID: 1748
08-30 17:24:50.259  1748  3932 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.259  1748  3932 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-30 17:24:50.261  3496  3510 E AndroidRuntime: Process: android.process.acore, PID: 3496
08-30 17:24:50.261  3496  3510 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1034)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.261  3496  3510 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.281   874  3938 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 17:24:50.286  1748  3936 I Process : Sending signal. PID: 1748 SIG: 9
08-30 17:24:50.286  2000  3935 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 17:24:50.290  1950  3941 E ReflectionEngine: Failed to save models
08-30 17:24:50.290  1950  3941 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.290  1950  3941 E ReflectionEngine: 	... 16 more
08-30 17:24:50.290   874  3937 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.290   874  3937 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.290   874  3937 E DropBoxManagerService: 	... 5 more
08-30 17:24:50.298   874  3939 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.298   874  3939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.298   874  3939 E DropBoxManagerService: 	... 5 more
08-30 17:24:50.300   874  2990 I ActivityManager: Start proc 3942:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-30 17:24:50.301  2000  3935 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-30 17:24:50.301  2000  3935 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 17:24:50.301  2000  3935 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2000
08-30 17:24:50.301  2000  3935 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.301  2000  3935 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:24:50.312   874  2035 I ActivityManager: Start proc 3953:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-30 17:24:50.321   874  3938 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 17:24:50.321   874  3938 I Adreno  : Build Date                       : 10/20/15
08-30 17:24:50.321   874  3938 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 17:24:50.321   874  3938 I Adreno  : Local Branch                     : M14
08-30 17:24:50.321   874  3938 I Adreno  : Remote Branch                    : 
08-30 17:24:50.321   874  3938 I Adreno  : Remote Branch                    : 
08-30 17:24:50.321   874  3938 I Adreno  : Reconstruct Branch               : 
08-30 17:24:50.327   874  3938 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:24:50.333   874  3964 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.333   874  3964 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.333   874  3964 E DropBoxManagerService: 	... 5 more
08-30 17:24:50.337  3496  3922 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-30 17:24:50.337  3496  3922 I Process : Sending signal. PID: 3496 SIG: 9
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: Failed to write the stream file
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java,:588)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.338  1950  3941 E ObservedEventLogger: 	... 16 more
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: Failed to write the stream file
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.339  1950  3941 E ObservedEventLogger: 	... 16 more
,08-30 17:24:50.354  1874  3920 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 17:24:50.355  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 17:24:50.356  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 17:24:50.368  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 17:24:50.368  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 17:24:50.369  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 17:24:50.369  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 17:24:50.369  1874  3920 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 17:24:50.370  1874  3920 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 17:24:50.370  1874  3920 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-30 17:24:50.370  1874  3920 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 17:24:50.370  1874  3920 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 17:24:50.370  1874  3920 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-30 17:24:50.376  3953  3953 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-30 17:24:50.379  3953  3953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
08-30 17:24:50.406   278   278 E lowmemorykiller: Error writing /proc/1748/oom_score_adj; errno=22
08-30 17:24:50.406   874  1383 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1756)
08-30 17:24:50.406   874  1383 W ActivityManager: Application dead when creating service ServiceRecord{f02070f u0 com.google.android.gms/.feedback.FeedbackService}
,08-30 17:24:50.414   874  2194 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@69dc39c)
,08-30 17:24:50.414   874  1308 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:24:50.415   874  1308 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:24:50.417   874  1383 I ActivityManager: Process com.google.android.gms (pid 1748) has died
,08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
,08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 21000ms
08-30 17:24:50.419   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 31000ms
08-30 17:24:50.420   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 31000ms
,08-30 17:24:50.423   874  1383 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 30996ms
,08-30 17:24:50.423   874  1383 W ActivityManager: Exception when starting service com.google.android.gms/.feedback.FeedbackService
08-30 17:24:50.423   874  1383 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-30 17:24:50.423   874  1383 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:15988)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-30 17:24:50.423   874  1383 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-30 17:24:50.424   874  3908 W ActivityManager: Spurious death for ProcessRecord{cf19d20 0:com.google.android.gms/u0a11}, curProc for 1748: null
,08-30 17:24:50.437  3953  3973 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.437  3953  3973 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:24:50.444   874   874 I ActivityManager: Start proc 3977:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-30 17:24:50.452  3953  3973 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 17:24:50.452  3953  3973 E AndroidRuntime: Process: com.android.keychain, PID: 3953
08-30 17:24:50.452  3953  3973 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.452  3953  3973 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:24:50.463   874  3988 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.463   874  3988 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.463   874  3988 E DropBoxManagerService: 	... 5 more
,08-30 17:24:50.476   278   278 E lowmemorykiller: Error writing /proc/3496/oom_score_adj; errno=22
,08-30 17:24:50.478   278   278 E lowmemorykiller: Error writing /proc/3496/oom_score_adj; errno=22
,08-30 17:24:50.491  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-30 17:24:50.508  3977  3977 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.documentsui/databases/recents.db'.
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:24:50.508  3977  3977 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 17:24:50.509  3977  3977 D AndroidRuntime: Shutting down VM
,08-30 17:24:50.511  3977  3977 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:24:50.511  3977  3977 E AndroidRuntime: Process: com.android.documentsui, PID: 3977
08-30 17:24:50.511  3977  3977 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-30 17:24:50.511  3977  3977 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 17:24:5,0.511  3977  3977 E AndroidRuntime: 	... 8 more
,08-30 17:24:50.521  1950  2201 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
08-30 17:24:50.524   874  3991 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.524   874  3991 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.524   874  3991 E DropBoxManagerService: 	... 5 more
,08-30 17:24:50.528   278   278 E lowmemorykiller: Error writing /proc/3496/oom_score_adj; errno=22
,08-30 17:24:50.528   278   278 E lowmemorykiller: Error writing /proc/3496/oom_score_adj; errno=22
,08-30 17:24:50.536   874  1949 I ActivityManager: Process android.process.acore (pid 3496) has died
,08-30 17:24:50.533  1356  2403 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10000)] disk I/O error
08-30 17:24:50.538   874  1949 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40882ms
,08-30 17:24:50.538  1356  2403 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 17:24:50.538  1356  2403 E AndroidRuntime: Process: android.process.media, PID: 1356
08-30 17:24:50.538  1356  2403 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1215)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.-wrap1(DownloadReceiver.java)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.538  1356  2403 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:24:50.547  1950  2024 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 17:24:50.549   874  3992 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.549   874  3992 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.549   874  3992 E DropBoxManagerService: 	... 5 more
,08-30 17:24:50.552  1950  2024 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 17:24:50.552  1950  2024 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1950
08-30 17:24:50.552  1950  2024 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.552  1950  2024 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:24:50.558   874  3908 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-30 17:24:50.558   874  3908 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:24:50.562   874  3994 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:24:50.562   874  3994 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.562   874  3994 E DropBoxManagerService: 	... 5 more
,08-30 17:24:50.564   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 17:24:50.566   874   886 E PackageManager: Failed to write settings, restoring backup
08-30 17:24:50.566   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 17:24:50.566   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 17:24:50.566   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 17:24:50.566   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 17:24:50.566   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 17:24:50.566   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:24:50.566   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.566   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:24:50.566   874  3908 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 17:24:50.568   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-30 17:24:50.568   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 17:24:50.568   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 17:24:50.568   874   887 E DropBoxManagerService: 	... 13 more
,08-30 17:24:50.571   874  3908 I ActivityManager: Killing 1950:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-30 17:24:50.608   874  2193 D GraphicsStats: Buffer count: 2
,08-30 17:24:50.645   874  3908 I ActivityManager: Start proc 3996:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 17:24:50.647   874  2194 W ActivityManager: Spurious death for ProcessRecord{d879bc6 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1950: null
,08-30 17:24:50.652   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-30 17:24:50.652   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-30 17:24:50.652   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
,08-30 17:24:50.653   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-30 17:24:50.653   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-30 17:24:50.653   280   280 E qdoverlay: MdpCtrl close error in unset
,08-30 17:24:50.665   874  2035 I ActivityManager: Start proc 4005:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,08-30 17:24:50.875   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-30 17:24:50.875   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 17:24:50.876   280   280 E qdoverlay: MdpCtrl close error in unset

```
