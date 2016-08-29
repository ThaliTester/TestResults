#### Test 829140738625595_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 11:06:36.924  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:06:36.934  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 11:06:36.936  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 11:06:36.979  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 11:06:36.979  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 11:06:36.980  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:06:36.980  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 11:06:36.999  3589  3589 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 11:06:36.999  3589  3589 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 11:06:37.000  3589  3589 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
--------- beginning of system
08-29 11:06:37.326   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 11:06:37.543  3833  3833 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 11:06:37.548  3833  3833 D AndroidRuntime: CheckJNI is OFF
08-29 11:06:37.592  3833  3833 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 11:06:37.642  3833  3833 I Radio-JNI: register_android_hardware_Radio DONE
08-29 11:06:37.664  3833  3833 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 11:06:37.669   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 11:06:37.719  2037  2050 W SearchService: Abort, client detached.
08-29 11:06:37.723  2037  2037 I HotwordDetector: Closing mic
08-29 11:06:37.723  2037  2324 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7d214d8
08-29 11:06:37.723  2037  2333 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 11:06:37.754  3833  3833 D AndroidRuntime: Shutting down VM
08-29 11:06:37.770   872  2002 I ActivityManager: Start proc 3842:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 11:06:37.786   376  2335 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 11:06:37.787   376  2335 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 11:06:37.791   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 11:06:37.794  2037  2327 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 11:06:37.795  2037  2332 I MicroRecognitionRnrImpl: Detection finished
08-29 11:06:37.863  3842  3842 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 11:06:37.890  3842  3842 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 11:06:37.897  3842  3842 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2579-2582)
08-29 11:06:37.897  3842  3842 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:06:37.914  3842  3842 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8f81ea8}
08-29 11:06:37.914  3842  3842 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 11:06:37.915  3842  3842 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 11:06:37.940  3842  3842 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 11:06:37.945  3842  3842 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 11:06:37.962  3842  3842 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 11:06:37.972  3842  3842 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:06:37.973  3842  3842 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:06:37.973  3842  3842 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 11:06:37.973  3842  3842 I Adreno  : Build Date                       : 10/20/15
08-29 11:06:37.973  3842  3842 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 11:06:37.973  3842  3842 I Adreno  : Local Branch                     : M14
08-29 11:06:37.973  3842  3842 I Adreno  : Remote Branch                    : 
08-29 11:06:37.973  3842  3842 I Adreno  : Remote Branch                    : 
08-29 11:06:37.973  3842  3842 I Adreno  : Reconstruct Branch               : 
,08-29 11:06:38.047   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5c2cf45:true
,08-29 11:06:38.082  3842  3842 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 11:06:38.095  3842  3842 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 11:06:38.175  3842  3880 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 11:06:38.183  3842  3867 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 11:06:38.221  3842  3880 I OpenGLRenderer: Initialized EGL, version 1.4,
,08-29 11:06:38.319   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms
,08-29 11:06:38.333  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-29 11:06:38.394  3842  3842 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3842
,08-29 11:06:38.517  3842  3842 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 11:06:38.588   872  2004 I ActivityManager: Killing 3111:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-29 11:06:38.620   872  2004 I ActivityManager: Killing 3071:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-29 11:06:38.730  3842  3882 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1714161360
,08-29 11:06:38.738  3842  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 11:06:38.738  3842  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 11:06:38.738  3842  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 11:06:38.738  3842  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 11:06:38.738  3842  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 11:06:38.738  3842  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ea9bac added. We now have 1 listener(s)
08-29 11:06:38.743  3842  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-29 11:06:38.745  3842  3882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:06:38.745  3842  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:06:38.745  3842  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 11:06:38.748  3842  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@932887b added. We now have 1 listener(s)
,08-29 11:06:38.748  3842  3882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:06:38.755   872  1308 D WifiService: New client listening to asynchronous messages
,08-29 11:06:38.759  3842  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:06:38.759  3842  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 11:06:38.760  3842  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 11:06:38.760  3842  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 11:06:38.760  3842  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 11:06:38.763  3842  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:38.763  3842  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 11:06:38.768  3842  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:38.768  3842  3882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:38.768  3842  3882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 11:06:38.768  3842  3882 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:06:38.769  3842  3882 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 11:06:38.910  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:38.912  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:38.914  3842  3842 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 11:06:39.610  3842  3892 W jxcore-log: Initializing JXcore engine
,08-29 11:06:39.610  3842  3892 W jxcore-log: JXcore engine is ready
,08-29 11:06:39.646  3892  3892 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 11:06:39.646  3892  3892 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9775]" dev="sockfs" ino=9775 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 11:06:39.646  3892  3892 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 11:06:39.646  3892  3892 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25079]" dev="sockfs" ino=25079 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 11:06:39.664  3842  3892 W jxcore-log: Starting JXcore engine
,08-29 11:06:39.744  3842  3892 W jxcore-log: Platform android
08-29 11:06:39.744  3842  3892 W jxcore-log: 
,08-29 11:06:39.744  3842  3892 W jxcore-log: Process ARCH arm
08-29 11:06:39.744  3842  3892 W jxcore-log: 
,08-29 11:06:39.954  3842  3892 I jxcore-log: JXcore Cordova bridge is ready!
08-29 11:06:39.954  3842  3892 I jxcore-log: 
08-29 11:06:39.955  3842  3892 W jxcore-log: JXcore engine is started
,08-29 11:06:39.966  3842  3882 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 11:06:39.972  3842  3842 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 11:06:40.355   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 11:06:40.605   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 11:06:43.382   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 11:06:43.956  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:06:43.960  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:06:44.001  1506  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 11:06:44.001  1506  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 11:06:44.001  1506  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:06:44.001  1506  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:06:44.051  3089  3901 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 11:06:44.051  3089  3901 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jdm.a(PG:82)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jcs.o(PG:406)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jcn.a(PG:1379)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jcs.i(PG:143)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at blb.a(PG:3937)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at czp.a(PG:18188)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at czp.a(PG:9081)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at czq.run(PG:1686)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 11:06:44.051  3089  3901 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jdj.a(PG:4091)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jdj.a(PG:1125)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jdm.a(PG:77)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	... 12 more
08-29 11:06:44.051  3089  3901 E HttpOperation: Caused by: faj: BadAuthentication
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at fal.a(PG:38)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	at jdj.a(PG:4089)
08-29 11:06:44.051  3089  3901 E HttpOperation: 	... 14 more
,08-29 11:06:44.115  1506  3067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 11:06:44.115  1506  3067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 11:06:44.115  1506  3067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:06:44.115  1506  3067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:06:44.133  3089  3901 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 11:06:44.133  3089  3901 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jdm.a(PG:82)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jcs.o(PG:406)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jcn.a(PG:1379)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jcs.i(PG:143)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at hec.a(PG:42)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at hee.a(PG:102)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at czr.a(PG:65)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at kka.a(PG:108)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at czp.a(PG:19176)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at czp.a(PG:9081)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at czq.run(PG:1686)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 11:06:44.133  3089  3901 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jdj.a(PG:4091)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jdj.a(PG:1125)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jdm.a(PG:77)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	... 15 more
08-29 11:06:44.133  3089  3901 E HttpOperation: Caused by: faj: BadAuthentication
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at fal.a(PG:38)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	at jdj.a(PG:4089)
08-29 11:06:44.133  3089  3901 E HttpOperation: 	... 17 more
08-29 11:06:44.134  3089  3901 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 11:06:44.134  3089  3901 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at hec.a(PG:42)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at hee.a(PG:102)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at czr.a(PG:65)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at kka.a(PG:108)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	... 15 more
08-29 11:06:44.134  3089  3901 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at fal.a(PG:38)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 11:06:44.134  3089  3901 E ExperimentLoader: 	... 17 more
,08-29 11:06:44.257   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128426, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 11:06:46.415   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 11:06:50.321  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 11:06:50.321  3842  3892 I jxcore-log: 
,08-29 11:06:50.323  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 11:06:50.323  3842  3892 I jxcore-log: 
,08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:50.334  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:06:50.340  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:06:50.344  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 11:06:50.344  3842  3892 I jxcore-log: 
,08-29 11:06:50.347  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 11:06:50.347  3842  3892 I jxcore-log: 
,08-29 11:06:50.858  3842  3892 D executeNativeTests: Running unit tests
,08-29 11:06:50.916  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:06:50.916  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c added. We now have 2 listener(s)
,08-29 11:06:50.917  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:06:50.917  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:06:50.917  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:06:50.917  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:50.917  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 added. We now have 2 listener(s)
08-29 11:06:50.917  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:50.918  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:06:50.920  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:50.933  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:06:50.938  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:06:50.939  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:06:50.945  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:50.946  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 11:06:50.946  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:50.948  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:06:50.949  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:06:50.953  3842  3892 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 11:06:50.954  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:06:50.955  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 11:06:50.955  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:50.955  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:50.956  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:06:50.957  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:50.958  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:50.959  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:50.960  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:50.960  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:50.960  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:06:50.961  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c removed from the list
08-29 11:06:50.961  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:50.961  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 removed from the list
08-29 11:06:50.961  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:50.962  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.964  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:50.964  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.965  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:50.965  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:50.965  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:50.965  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:50.967  3842  3892 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 11:06:50.967  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:50.967  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:50.967  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:50.968  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:50.968  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:50.968  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:50.968  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:50.968  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:50.968  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:50.968  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:50.968  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:50.968  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.968  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:50.968  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.969  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:06:50.970  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:50.970  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:50.970  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 11:06:50.976  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:06:50.977  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:06:50.978  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:06:50.978  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:50.978  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:50.978  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:50.978  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:50.978  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:50.979  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.979  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:50.979  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:50.979  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:50.979  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:50.979  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:50.979  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.979  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:50.979  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:50.980  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:50.980  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:50.980  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:50.980  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:50.981  3842  3892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:06:50.983  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:50.986  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:06:50.988  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:50.988  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:06:50.989  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:06:50.989  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:06:50.990  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:06:50.990  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:50.990  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:06:50.990  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:50.992  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:50.994  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:06:50.994  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:06:50.998  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:06:50.999  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:06:51.000  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:06:51.001  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 11:06:51.004  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 11:06:51.005  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:06:51.005  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 11:06:51.006  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:06:51.007  3842  3892 D BluetoothAdapter: STATE_ON
,08-29 11:06:51.011  2659  2764 D BtGatt.GattService: registerClient() - UUID=a38c97e4-0b77-46c6-9963-b06309a8f3a0
,08-29 11:06:51.012  2659  2681 D BtGatt.GattService: onClientRegistered() - UUID=a38c97e4-0b77-46c6-9963-b06309a8f3a0, clientIf=5
08-29 11:06:51.013  3842  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 11:06:51.013  2659  2751 D BtGatt.GattService: start scan with filters
,08-29 11:06:51.016  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:06:51.016  2659  2684 D BtGatt.ScanManager: handling starting scan
08-29 11:06:51.016  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:06:51.016  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:06:51.016  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 11:06:51.017  2659  2684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
08-29 11:06:51.018  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:06:51.019  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:06:51.019  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:06:51.020  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:06:51.022  3842  3892 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:06:51.025  2659  2681 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:06:51.025  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.025  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.025  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:06:51.025  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.025  2659  2684 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:06:51.025  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:06:51.025  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.026  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:06:51.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:06:51.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:06:51.026  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:06:51.026  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:06:51.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:06:51.026  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:06:51.027  3842  3892 D BluetoothAdapter: STATE_ON
08-29 11:06:51.027  2659  2764 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:06:51.028  2659  2751 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 11:06:51.028  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:51.028  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:06:51.028  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 11:06:51.028  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:06:51.029  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:06:51.029  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:51.030  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:06:51.030  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:06:51.030  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:06:51.031  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:51.032  2659  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 11:06:51.032  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.032  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:06:51.032  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:06:51.032  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:51.032  2659  2684 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 11:06:51.032  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.032  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.032  2659  2684 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:06:51.032  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:51.032  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
,08-29 11:06:51.033  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.033  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.033  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:51.033  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.033  3842  3892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 11:06:51.034  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:51.038  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:51.039  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:06:51.039  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:06:51.041  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.041  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:06:51.041  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:06:51.041  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:06:51.041  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:51.041  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:06:51.042  2659  2681 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:06:51.042  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.044  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:06:51.044  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:06:51.045  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.047  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:06:51.048  2659  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:06:51.048  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.048  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:06:51.048  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:06:51.052  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:06:51.052  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:06:51.052  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:06:51.053  3842  3892 D BluetoothAdapter: STATE_ON
,08-29 11:06:51.056  2659  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 11:06:51.056  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.056  2659  2670 D BtGatt.GattService: registerClient() - UUID=db6a9592-0b7f-4c35-b229-7e22f2f3b2d9
08-29 11:06:51.056  2659  2681 D BtGatt.GattService: onClientRegistered() - UUID=db6a9592-0b7f-4c35-b229-7e22f2f3b2d9, clientIf=5
,08-29 11:06:51.056  2659  2684 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:06:51.057  3842  3853 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 11:06:51.057  2659  2671 D BtGatt.GattService: start scan with filters
,08-29 11:06:51.060  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 11:06:51.060  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:06:51.060  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:06:51.060  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:06:51.062  2659  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 11:06:51.062  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.062  2659  2684 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:06:51.062  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:06:51.062  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:06:51.062  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:06:51.064  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 11:06:51.066  3842  3892 I io.jxcore.node.ConnectionHelper: start: OK
08-29 11:06:51.066  2659  2681 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:06:51.066  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.068  2659  2684 D BtGatt.ScanManager: handling starting scan
08-29 11:06:51.069  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.069  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:06:51.069  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.069  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:06:51.069  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.069  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:06:51.069  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:06:51.069  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:06:51.070  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:06:51.070  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:06:51.070  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:06:51.070  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:06:51.070  3842  3892 D BluetoothAdapter: STATE_ON
08-29 11:06:51.071  2659  2670 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:06:51.071  2659  2671 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 11:06:51.072  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:51.072  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 11:06:51.072  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:06:51.072  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:06:51.072  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:06:51.073  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:51.073  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:06:51.073  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 11:06:51.073  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:06:51.074  2659  2681 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:06:51.074  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:06:51.074  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.074  2659  2684 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 11:06:51.075  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:51.075  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:06:51.075  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.075  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:06:51.075  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:06:51.075  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.075  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:51.075  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.075  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.075  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.075  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.076  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.076  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.077  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.077  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:51.077  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.077  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.080  2659  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 11:06:51.080  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.080  3842  3892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:06:51.080  2659  2684 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:06:51.080  2659  2684 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:06:51.082  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:51.087  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:06:51.088  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.088  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:06:51.089  2659  2681 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 11:06:51.089  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.089  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:06:51.089  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:06:51.089  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 11:06:51.089  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:06:51.089  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:06:51.090  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.092  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 11:06:51.092  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:06:51.092  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 11:06:51.095  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:06:51.095  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
08-29 11:06:51.096  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:06:51.097  2659  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:06:51.097  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.099  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-29 11:06:51.099  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:06:51.099  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:06:51.100  3842  3892 D BluetoothAdapter: STATE_ON
,08-29 11:06:51.101  2659  2764 D BtGatt.GattService: registerClient() - UUID=649a62ea-5d66-4b95-ab5a-2f98e73ae6e7
08-29 11:06:51.102  2659  2681 D BtGatt.GattService: onClientRegistered() - UUID=649a62ea-5d66-4b95-ab5a-2f98e73ae6e7, clientIf=5
08-29 11:06:51.102  3842  3853 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 11:06:51.103  2659  2671 D BtGatt.GattService: start scan with filters
08-29 11:06:51.103  2659  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:06:51.103  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.103  2659  2684 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:06:51.105  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 11:06:51.105  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:06:51.105  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:06:51.105  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:06:51.108  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:06:51.108  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:06:51.108  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:06:51.109  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:06:51.111  2659  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 11:06:51.111  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.111  2659  2684 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 11:06:51.111  3842  3892 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:06:51.111  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:06:51.111  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:06:51.111  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:51.112  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:06:51.112  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.112  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:06:51.112  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:06:51.112  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:06:51.112  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 11:06:51.112  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:06:51.112  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:06:51.112  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:06:51.113  3842  3892 D BluetoothAdapter: STATE_ON
08-29 11:06:51.114  2659  2671 D BtGatt.GattService: stopScan() - queue size =0
,08-29 11:06:51.116  2659  2751 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 11:06:51.116  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:06:51.116  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 11:06:51.116  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 11:06:51.116  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 11:06:51.116  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:06:51.117  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:06:51.117  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 11:06:51.117  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 11:06:51.117  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:06:51.118  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:06:51.118  2659  2681 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 11:06:51.118  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.119  2659  2684 D BtGatt.ScanManager: handling starting scan
08-29 11:06:51.120  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:06:51.120  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:06:51.120  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:06:51.120  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:06:51.122  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:06:51.122  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:51.122  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.122  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:51.122  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.122  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:06:51.123  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
,08-29 11:06:51.123  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.123  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.123  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:51.123  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.123  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.123  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.124  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:06:51.124  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:51.124  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.124  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.125  3842  3892 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 11:06:51.125  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:06:51.126  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:51.126  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:51.126  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:51.126  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.126  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.126  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
,08-29 11:06:51.126  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.126  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.126  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:51.126  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.126  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.126  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.126  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.127  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.127  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:51.128  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.128  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.128  2659  2681 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 11:06:51.128  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:06:51.128  2659  2684 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:06:51.129  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:06:51.129  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 11:06:51.129  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:06:51.129  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:06:51.129  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:51.129  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.129  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.129  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list,
08-29 11:06:51.129  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.129  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.129  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:06:51.129  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.130  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.130  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.130  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.131  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 11:06:51.131  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:06:51.131  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.131  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.132  3842  3892 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 11:06:51.132  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.132  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.132  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.133  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:51.133  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.133  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.133  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.133  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.133  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.133  2659  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 11:06:51.133  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.133  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.133  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.133  2659  2684 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:06:51.133  2659  2684 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 11:06:51.133  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.134  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.134  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.135  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.135  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.135  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.135  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.136  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 11:06:51.136  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:06:51.136  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.136  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.137  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.137  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.137  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.137  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.137  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.137  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.137  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.137  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.137  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.138  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.138  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:06:51.140  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.140  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.140  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.140  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
,08-29 11:06:51.141  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:06:51.142  2659  2681 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 11:06:51.142  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.143  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 11:06:51.143  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:06:51.143  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:51.143  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:06:51.143  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:06:51.144  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:06:51.144  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.144  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.144  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:06:51.144  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.144  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.144  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
,08-29 11:06:51.144  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:06:51.145  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.145  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.145  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:06:51.145  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.145  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.145  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.146  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.146  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.146  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.146  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.147  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 11:06:51.147  3842  3892 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:06:51.148  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 11:06:51.148  2659  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 11:06:51.149  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.151  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:51.151  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 11:06:51.151  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:06:51.151  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:06:51.152  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:06:51.153  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 11:06:51.153  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 11:06:51.154  3842  3892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:06:51.154  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 11:06:51.154  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:51.154  3842  3892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:06:51.154  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 11:06:51.154  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:51.154  3842  3892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:06:51.154  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 11:06:51.155  2659  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:06:51.155  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.156  2659  2684 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:06:51.158  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 11:06:51.158  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 11:06:51.158  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 11:06:51.159  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 11:06:51.159  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 11:06:51.159  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 11:06:51.159  3842  3892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:06:51.159  3842  3892 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 11:06:51.160  3842  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-29 11:06:51.160  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.160  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.160  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.161  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.161  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.161  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.161  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 11:06:51.161  3842  3907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:06:51.161  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.161  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.162  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.162  2659  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 11:06:51.162  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.162  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.162  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.162  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.162  3842  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-29 11:06:51.162  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.162  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.162  2659  2684 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:06:51.162  3842  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
08-29 11:06:51.163  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.163  3842  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-29 11:06:51.163  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.163  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.163  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.164  2659  2748 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-29 11:06:51.164  3842  3892 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 11:06:51.164  3842  3908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
08-29 11:06:51.164  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.164  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.164  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.164  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.165  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.165  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.165  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.166  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.166  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.166  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.166  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.166  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.167  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.167  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.167  2659  2681 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:06:51.167  2659  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:06:51.168  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.168  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.169  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.169  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.170  3842  3892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 11:06:51.170  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.171  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.171  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.171  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.171  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.171  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.172  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.172  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.172  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.172  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.172  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.173  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.173  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.173  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.175  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.175  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.175  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.175  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.175  3842  3892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 11:06:51.176  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 11:06:51.176  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:06:51.176  3842  3892 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 11:06:51.176  3842  3892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:06:51.176  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 11:06:51.176  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:06:51.176  3842  3892 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 11:06:51.176  3842  3892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:06:51.176  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:06:51.176  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:06:51.176  3842  3892 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 11:06:51.176  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.177  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.177  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.177  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.177  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.177  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.177  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.177  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.177  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.177  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.177  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.177  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.177  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.177  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.178  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.178  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.178  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.179  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.179  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.179  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.179  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.179  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.179  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.179  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.179  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.179  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.179  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.180  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.180  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.180  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.180  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.180  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.180  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.180  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.180  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.180  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.180  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.180  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.180  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.180  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
,08-29 11:06:51.180  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.181  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.181  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.181  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.181  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.181  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.181  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.182  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.182  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.182  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.182  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.183  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 11:06:51.183  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:51.184  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 11:06:51.185  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 11:06:51.185  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 11:06:51.185  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 11:06:51.185  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:06:51.185  3842  3842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 11:06:51.185  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.185  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 11:06:51.186  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 11:06:51.186  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 11:06:51.186  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.186  3842  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:06:51.186  3842  3892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 11:06:51.186  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.186  3842  3842 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 11:06:51.186  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.186  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:06:51.186  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:06:51.186  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:06:51.186  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.186  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.187  3842  3909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 11:06:51.187  3842  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 11:06:51.187  3842  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 11:06:51.187  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:51.187  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.187  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.188  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:06:51.188  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.188  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.188  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:06:51.188  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.188  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:06:51.188  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.188  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.188  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.188  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.188  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.188  3842  3842 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 11:06:51.188  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.188  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.188  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.188  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.188  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.189  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.189  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.189  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.189  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.190  3842  3892 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 11:06:51.190  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:06:51.190  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:06:51.191  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:06:51.192  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.192  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.192  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.192  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.192  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.192  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.192  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.192  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.192  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.192  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.193  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.193  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.193  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.193  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.194  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.194  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.194  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.194  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.197  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.197  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.198  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.198  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.198  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.198  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.198  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.198  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.198  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.198  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.198  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.198  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.199  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.199  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.199  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.200  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.200  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.200  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.200  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:06:51.201  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:06:51.201  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:06:51.201  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:06:51.201  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.201  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.201  3842  3892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cd2f7c not in the list
08-29 11:06:51.201  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.201  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.201  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:06:51.201  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.202  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.202  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:06:51.202  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:06:51.203  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:06:51.203  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:06:51.203  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:06:51.203  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd3005 not in the list
08-29 11:06:51.204  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 11:06:51.204  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:06:51.204  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 11:06:51.204  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:06:51.204  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 11:06:51.204  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:06:51.206  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:06:51.206  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 11:06:51.207  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 11:06:51.207  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:06:51.207  3842  3892 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 11:06:51.207  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:06:51.207  3842  3892 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 11:06:51.207  3842  3892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 11:06:51.208  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 11:06:51.208  3842  3892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 11:06:51.209  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 11:06:51.209  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 11:06:51.209  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 11:06:51.209  3842  3892 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 11:06:51.210  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:51.210  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2f995f added. We now have 2 listener(s)
08-29 11:06:51.210  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:51.212  3842  3892 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 11:06:51.213   872  1998 D WifiService: setWifiEnabled: true pid=3842, uid=10000
08-29 11:06:51.213   872  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:06:51.213  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:51.214  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c796fac added. We now have 3 listener(s)
08-29 11:06:51.214  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:51.221  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:51.221  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ac32475 added. We now have 4 listener(s),
08-29 11:06:51.221  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:51.222  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:06:51.223  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b05c0a added. We now have 5 listener(s)
08-29 11:06:51.223  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:06:51.226   872   883 D WifiService: setWifiEnabled: false pid=3842, uid=10000
08-29 11:06:51.226   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 11:06:51.231  2659  2677 D BluetoothAdapterState: Current state: ON, message: 23
08-29 11:06:51.231  2659  2677 D BluetoothAdapterProperties: Setting state to 13
08-29 11:06:51.231  2659  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:06:51.231  2659  2677 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:06:51.232  2659  2677 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:06:51.234  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:06:51.235  2659  2659 D BluetoothMapService: onReceive
08-29 11:06:51.235  2659  2659 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:06:51.235  2659  2659 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:06:51.235  2659  2659 D BluetoothMapService: MAP Service closeService in
08-29 11:06:51.235  2659  2659 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 11:06:51.235  2659  2659 D ObexServerSockets0: shutdown(block = true)
08-29 11:06:51.235  2659  2659 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 11:06:51.235  2659  2659 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 11:06:51.236  2659  2748 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 11:06:51.237  2659  2765 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 11:06:51.237  2659  2766 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 11:06:51.238  2659  2659 I BtOppRfcommListener: stopping Accept Thread
08-29 11:06:51.239  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:51.239  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:51.239  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:51.239  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.239  2659  3489 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:06:51.240  2659  3489 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:06:51.244  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:51.244  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:06:51.244  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 11:06:51.246  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:51.246  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:51.246   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 11:06:51.246   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 11:06:51.247   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 11:06:51.247  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:06:51.247   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 11:06:51.250  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.252   872  2343 D DhcpClient: Clearing IP address
08-29 11:06:51.253  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.253   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:06:51.256  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.257   372   870 D CommandListener: Setting iface cfg
08-29 11:06:51.260   872   885 I ActivityManager: Start proc 3912:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 11:06:51.260  2659  2681 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:06:51.261  2659  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 11:06:51.262  1506  2570 V NativeCrypto: Read error: ssl=0x9b635a00: I/O error during system call, Connection timed out
08-29 11:06:51.263  1506  2570 V NativeCrypto: SSL shutdown failed: ssl=0x9b635a00: I/O error during system call, Broken pipe
08-29 11:06:51.265   872  1521 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-29 11:06:51.265  2659  2659 D HeadsetService: Received stop request...Stopping profile...
,08-29 11:06:51.266  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.266   872  2338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-29 11:06:51.267  1947  2117 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:51.267   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:51.268   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:51.268  1378  1391 D BluetoothHeadset: Proxy object disconnected
,08-29 11:06:51.268  1378  1378 D HeadsetProfile: Bluetooth service disconnected
08-29 11:06:51.268   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 11:06:51.268  2659  2659 D A2dpService: Received stop request...Stopping profile...
08-29 11:06:51.269  2659  2756 D A2dpStateMachine: Exit Disconnected: -1
,08-29 11:06:51.270  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.271   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 11:06:51.273   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 11:06:51.273   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 11:06:51.273   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 11:06:51.276   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 11:06:51.277   396   396 E Parcel  : Reading a NULL string not supported here.
08-29 11:06:51.277   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:06:51.281   872   872 D BluetoothA2dp: Proxy object disconnected
08-29 11:06:51.283  2659  2659 V BluetoothAdapterState: isTurningOff()=true
08-29 11:06:51.283  2659  2659 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:06:51.283   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 11:06:51.283  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:06:51.283  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:06:51.283   872  2338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 11:06:51.285   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 11:06:51.288  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:51.288  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:06:51.288  2659  2659 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:06:51.289  2659  2681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 11:06:51.289  2659  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:06:51.289  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:51.289  2659  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:06:51.289  2659  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:06:51.289  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:51.289  2659  2659 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:06:51.289  2659  2681 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 11:06:51.291  2659  2659 D HidService: Received stop request...Stopping profile...
,08-29 11:06:51.291  2659  2659 D HidService: Stopping Bluetooth HidService
08-29 11:06:51.292  2659  2659 D HealthService: Received stop request...Stopping profile...
08-29 11:06:51.293  2659  2659 D PanService: Received stop request...Stopping profile...
,08-29 11:06:51.294  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:51.294  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:51.295  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:51.295  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:51.296   872  2349 D DhcpClient: Receive thread stopped
08-29 11:06:51.297  2659  2659 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 11:06:51.297  2659  2659 D BluetoothMapService: stop()
,08-29 11:06:51.297  1883  2282 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:06:51.298  2659  2659 D BluetoothMapAppObserver: deinitObservers()
08-29 11:06:51.298  2659  2659 D BluetoothMapAppObserver: removeReceiver()
08-29 11:06:51.298  1378  1378 D BluetoothA2dp: Proxy object disconnected
08-29 11:06:51.299  1378  1378 D BluetoothInputDevice: Proxy object disconnected
08-29 11:06:51.299  1378  1378 D HidProfile: Bluetooth service disconnected
,08-29 11:06:51.299  1378  1378 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 11:06:51.299  1378  1378 D PanProfile: Bluetooth service disconnected
08-29 11:06:51.299  2659  2659 V BluetoothAdapterState: isTurningOff()=true
08-29 11:06:51.299  2659  2659 V BluetoothAdapterState: isTurningOn()=false
08-29 11:06:51.299  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:06:51.299  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:06:51.302  1378  1378 D BluetoothMap: Proxy object disconnected
08-29 11:06:51.302  1378  1378 D MapProfile: Bluetooth service disconnected
08-29 11:06:51.302  2659  2681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 11:06:51.302  2659  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:06:51.303  2659  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 11:06:51.303  2659  2740 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:06:51.303  2659  2740 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:06:51.303  2659  2740 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:06:51.303  2659  2740 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:06:51.308  2659  2659 V BluetoothAdapterState: isTurningOff()=true
08-29 11:06:51.308  2659  2659 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:06:51.308  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:06:51.308  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:06:51.309  2659  2659 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:06:51.309  2659  2659 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:06:51.309  2659  2681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 11:06:51.309  2659  2659 V BluetoothAdapterState: isTurningOff()=true
08-29 11:06:51.309  2659  2659 V BluetoothAdapterState: isTurningOn()=false
08-29 11:06:51.309  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:06:51.309  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:06:51.310  2659  2659 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:06:51.310  2659  2681 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 11:06:51.310  2659  2659 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:06:51.312  2659  2659 V BluetoothAdapterState: isTurningOff()=true
08-29 11:06:51.312  2659  2659 V BluetoothAdapterState: isTurningOn()=false
08-29 11:06:51.312  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:06:51.312  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:06:51.312  2659  2659 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 11:06:51.312  2659  2659 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 11:06:51.314  2659  2659 D BluetoothMapService: MAP Service closeService in
08-29 11:06:51.314  2659  2659 V BluetoothAdapterState: isTurningOff()=true
08-29 11:06:51.314  2659  2659 V BluetoothAdapterState: isTurningOn()=false
08-29 11:06:51.315  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:06:51.315  2659  2659 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:06:51.315  2659  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 11:06:51.315  2659  2677 D BluetoothAdapterProperties: Setting state to 15
,08-29 11:06:51.315  2659  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 11:06:51.315  2659  2677 I BluetoothAdapterState: Entering BleOnState
,08-29 11:06:51.315   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:51.316  2659  2659 D BluetoothMapService: cleanup()
08-29 11:06:51.316  1947  2144 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:51.316  2659  2659 D BluetoothMapService: MAP Service closeService in
08-29 11:06:51.316  1378  1389 D BluetoothPan: onBluetoothStateChange on: false
,08-29 11:06:51.316  1378  1700 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:51.317   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:06:51.317   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:06:51.317  1378  1391 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:06:51.318  1378  1389 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:06:51.318   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 11:06:51.318  1378  1700 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:06:51.321  1378  1391 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:06:51.322  2659  2677 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 11:06:51.322  2659  2677 D BluetoothAdapterProperties: Setting state to 16
08-29 11:06:51.322  2659  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 11:06:51.323  2659  2677 D BluetoothAdapterProperties: onBleDisable
08-29 11:06:51.323  2659  2677 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:06:51.323  2659  2678 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 11:06:51.324  2659  2740 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 11:06:51.324  2659  2740 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:06:51.325  2659  2681 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:06:51.325   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 11:06:51.326  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.328  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.329  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.330  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.351  3912  3912 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 11:06:51.352   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:06:51.353   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-29 11:06:51.354   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:51.357   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 11:06:51.358  3494  3494 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3ea9bac and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 11:06:51.359  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:06:51.360  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:51.371  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:06:51.376  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:06:51.379   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e74798:true
,08-29 11:06:51.389   872  1961 I ActivityManager: Start proc 3931:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 11:06:51.418   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 11:06:51.420   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 11:06:51.443  3931  3931 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 11:06:51.445  3912  3912 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 11:06:51.446  3912  3912 D BluetoothMap: Create BluetoothMap proxy object
,08-29 11:06:51.451  3912  3912 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 11:06:51.467  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:06:51.472   872  2004 I ActivityManager: Killing 3292:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 11:06:51.529  2659  2681 I bt_hci  : shut_down
,08-29 11:06:51.529  2659  2685 D bt_hwcfg: hw_epilog_process
,08-29 11:06:51.533  2659  2685 I bt_vendor: low_power_mode_cb
,08-29 11:06:51.559  2659  2685 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 11:06:51.559  2659  2685 I bt_vendor: epilog_cb
08-29 11:06:51.560  2659  2685 I bt_hci  : epilog_finished_callback
,08-29 11:06:51.562  2659  2681 I bt_hci_h4: hal_close
,08-29 11:06:51.563  2659  2681 I bt_userial_vendor: device fd = 51 close
,08-29 11:06:51.613  3931  3931 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.613  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.614  3931  3931 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:06:51.614  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:06:51.637   872  1981 I ActivityManager: Start proc 3962:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-29 11:06:51.638   872  1981 I ActivityManager: Killing 3494:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 11:06:51.689  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 11:06:51.698  2659  2678 D bt_stack_manager: event_shut_down_stack finished.
08-29 11:06:51.699  2659  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 11:06:51.700  2659  2677 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 11:06:51.701  2659  2659 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:06:51.705  2659  2659 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 11:06:51.705  2659  2659 D BtGatt.GattService: stop()
,08-29 11:06:51.705  2659  2659 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 11:06:51.709  2659  2659 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:06:51.709  2659  2659 V BluetoothAdapterState: isTurningOn()=false
08-29 11:06:51.709  2659  2659 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:06:51.709  2659  2659 V BluetoothAdapterState: isBleTurningOff()=true
08-29 11:06:51.710  2659  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 11:06:51.710  2659  2677 D BluetoothAdapterProperties: Setting state to 10
08-29 11:06:51.710  2659  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 11:06:51.711  2659  2677 I BluetoothAdapterState: Entering OffState
,08-29 11:06:51.713   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 11:06:51.723  2659  2659 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 11:06:51.723  2659  2659 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 11:06:51.723  2659  2659 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 11:06:51.724  2659  2678 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 11:06:51.726  2659  2678 D bt_stack_manager: event_clean_up_stack finished.
08-29 11:06:51.730  3962  3962 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 11:06:51.736  2659  2659 I art     : System.exit called, status: 0
,08-29 11:06:51.736  2659  2659 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:06:51.789   872  1363 I ActivityManager: Process com.android.bluetooth (pid 2659) has died
,08-29 11:06:51.846  3962  3962 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 11:06:51.889  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:06:51.901  3931  3951 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 11:06:51.922   872   883 I ActivityManager: Start proc 3991:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 11:06:51.932  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:06:51.967   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69e71f8:true
,08-29 11:06:52.016  3991  3991 D AdapterServiceConfig: Adding HeadsetService
,08-29 11:06:52.016  3991  3991 D AdapterServiceConfig: Adding A2dpService
08-29 11:06:52.016  3991  3991 D AdapterServiceConfig: Adding HidService
,08-29 11:06:52.016  3991  3991 D AdapterServiceConfig: Adding HealthService
08-29 11:06:52.016  3991  3991 D AdapterServiceConfig: Adding PanService
,08-29 11:06:52.016  3991  3991 D AdapterServiceConfig: Adding GattService
,08-29 11:06:52.018  3991  3991 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 11:06:52.022   872   882 I ActivityManager: Killing 2713:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 11:06:52.056  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:06:52.106  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:06:52.122  1715  1715 D SystemUpdateService: onCreate
,08-29 11:06:52.126  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:06:52.130  1715  4003 I SystemUpdateService: active receiver: enabled
,08-29 11:06:52.137  1715  4003 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:06:52.152  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 11:06:52.152  1715  4003 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 11:06:52.153  1715  4003 I SystemUpdateService: now status is 0 (complete)
08-29 11:06:52.153  1715  4003 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 11:06:52.153  1715  4003 I SystemUpdateService: file has been verified
08-29 11:06:52.154  1715  4003 I SystemUpdateService: OTA package size = 12249756,
,08-29 11:06:52.156  1715  2548 I iu.UploadsManager: num queued entries: 0
,08-29 11:06:52.157  1715  2548 I iu.UploadsManager: num updated entries: 0
,08-29 11:06:52.158  1715  2548 I iu.SyncManager: NEXT; no task
,08-29 11:06:52.161  1715  4003 I SystemUpdateService: showing system update notification
,08-29 11:06:52.176  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:06:52.179  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 11:06:52.206   872  1933 I ActivityManager: Start proc 4005:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 11:06:52.209  1715  1715 D SystemUpdateService: onDestroy
,08-29 11:06:52.244  4005  4005 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 11:06:52.247  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:52.254  4005  4005 D SprintDMHelper: simOperator: 
,08-29 11:06:52.254  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:06:52.274   872   883 I ActivityManager: Start proc 4017:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 11:06:52.275   872   883 I ActivityManager: Killing 1693:android.process.acore/u0a5 (adj 15): empty #17
,08-29 11:06:52.382  2204  4031 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 11:06:52.426   872  1983 I ActivityManager: Start proc 4032:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 11:06:52.435   872  1983 I ActivityManager: Killing 3697:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 11:06:52.519  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 11:06:52.603  4032  4032 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 11:06:52.603  4032  4032 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 11:06:52.603  4032  4032 I GAv4    :   adb logcat -s GAv4
,08-29 11:06:52.628  4032  4032 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:06:52.634  4032  4032 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:06:52.661  4032  4049 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:06:52.766  4032  4032 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 11:06:52.807  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 11:06:52.817  4032  4032 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7497-7502)
,08-29 11:06:52.817  4032  4032 I LibraryLoader: Expected native library version number "",actual native library version number "",
,08-29 11:06:52.833  4032  4032 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4a247dc}
,08-29 11:06:52.833  4032  4032 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 11:06:52.834  4032  4032 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:06:52.844  4032  4032 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 11:06:52.846  4032  4032 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 11:06:52.861  4032  4032 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 11:06:52.878  4032  4032 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:06:52.878  4032  4032 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 11:06:52.878  4032  4032 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 11:06:52.878  4032  4032 I Adreno  : Build Date                       : 10/20/15
08-29 11:06:52.878  4032  4032 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 11:06:52.878  4032  4032 I Adreno  : Local Branch                     : M14
08-29 11:06:52.878  4032  4032 I Adreno  : Remote Branch                    : 
08-29 11:06:52.878  4032  4032 I Adreno  : Remote Branch                    : 
08-29 11:06:52.878  4032  4032 I Adreno  : Reconstruct Branch               : 
,08-29 11:06:52.935  4032  4032 I NSApplication: Starting up...
,08-29 11:06:52.947  4032  4078 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 11:06:52.985   872  1961 I ActivityManager: Start proc 4083:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 11:06:52.991   872  1961 I ActivityManager: Killing 3713:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 11:06:53.070  4083  4083 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 11:06:53.256   872  1363 I ActivityManager: Killing 3521:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 11:06:54.249   872  1521 D WifiService: setWifiEnabled: true pid=3842, uid=10000
,08-29 11:06:54.249   872  1521 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:06:54.273   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-29 11:06:54.281  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:54.282  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:06:54.282  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.282  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:54.286  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:54.286  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:54.286  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:54.287  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:06:54.302   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-29 11:06:54.303   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 11:06:54.305   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 11:06:54.305   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 11:06:54.306   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 11:06:54.306   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 11:06:54.306   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 11:06:54.324   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 11:06:54.324   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.00 rxSuccessRate=12.75 delta 1000 -> 994
08-29 11:06:54.325   372   870 D CommandListener: Setting iface cfg
08-29 11:06:54.325   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-29 11:06:54.325   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 11:06:54.329   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 11:06:54.329   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 11:06:54.337   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 11:06:54.338   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:06:54.356   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 11:06:54.406   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 11:06:54.407  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 11:06:54.833  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 11:06:54.870  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 11:06:54.870  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 11:06:54.878   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:06:54.885   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 11:06:54.885   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:06:54.887   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 11:06:54.903   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:06:54.916   372   870 D CommandListener: Setting iface cfg
,08-29 11:06:54.918   872  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 11:06:54.930   872  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 11:06:54.933   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 11:06:54.983   872  4108 D DhcpClient: Receive thread started
,08-29 11:06:55.072   872  1307 E native  : do suspend false
,08-29 11:06:55.100   872  2343 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 11:06:55.114   872  4108 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-29 11:06:55.115   872  2343 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-29 11:06:55.118   872  2343 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 11:06:55.136   872  4108 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 11:06:55.139   872  2343 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 11:06:55.148   372   870 D CommandListener: Setting iface cfg
,08-29 11:06:55.159   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 11:06:55.162   872  2343 D DhcpClient: Scheduling renewal in 86399s
,08-29 11:06:55.175   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 11:06:55.175   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 11:06:55.176   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 11:06:55.176   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 11:06:55.182   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 11:06:55.182   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 11:06:55.219   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 11:06:55.219   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 11:06:55.221   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 11:06:55.222   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 11:06:55.223   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 11:06:55.231   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 11:06:55.235   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-29 11:06:55.235   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 11:06:55.235   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 11:06:55.236   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 11:06:55.236   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 11:06:55.236   872  1309 D ConnectivityService:    accepting network in place of null
,08-29 11:06:55.237   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 11:06:55.254   872  4107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139939, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 11:06:55.290   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:06:55.325   872  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:817::200e
,08-29 11:06:55.354   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:06:55.364   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 11:06:55.364   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:55.373   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 11:06:55.381  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:55.381  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:55.381  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:55.381  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:55.383  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:06:55.384  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:06:55.384  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:55.384  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:06:55.391   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 11:06:55.401   872  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 09:06:55 GMT], X-Android-Received-Millis=[1472461615399], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472461615366]}
,08-29 11:06:55.404   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 11:06:55.404   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 11:06:55.404   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 11:06:55.405   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 11:06:55.412  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:06:55.417  1715  1715 D SystemUpdateService: onCreate,
,08-29 11:06:55.422  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:06:55.430  1715  4121 I SystemUpdateService: active receiver: enabled
,08-29 11:06:55.434  1715  4121 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:06:55.439  1715  4121 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 11:06:55.439  1715  4121 I SystemUpdateService: now status is 0 (complete)
,08-29 11:06:55.439  1715  4121 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 11:06:55.441  1715  4121 I SystemUpdateService: file has been verified
08-29 11:06:55.441  1715  4121 I SystemUpdateService: OTA package size = 12249756
,08-29 11:06:55.443  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 11:06:55.452  1715  2548 I iu.UploadsManager: num queued entries: 0
,08-29 11:06:55.452  1715  2548 I iu.UploadsManager: num updated entries: 0
,08-29 11:06:55.453  1715  2548 I iu.SyncManager: NEXT; no task
,08-29 11:06:55.457  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:06:55.457  1715  4121 I SystemUpdateService: showing system update notification
,08-29 11:06:55.458  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 11:06:55.460  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:55.462  1715  4125 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 11:06:55.463  1715  4125 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 11:06:55.464  1715  4125 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
08-29 11:06:55.464  4005  4005 D SprintDMHelper: simOperator: 
08-29 11:06:55.464  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:06:55.470  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:06:55.473  1715  1715 D SystemUpdateService: onDestroy
,08-29 11:06:55.474  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:06:55.509  1506  2392 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 11:06:55.509  1506  2392 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 11:06:55.509  1506  2392 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:06:55.509  1506  2392 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:06:55.525  1715  4125 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-29 11:06:55.528  3126  4122 V KeepSync: Connecting to GoogleApiClient
,08-29 11:06:55.529   872  2002 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 11:06:55.568  1506  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 11:06:55.568  1506  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 11:06:55.568  1506  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:06:55.568  1506  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:06:55.581  1715  4131 V BaseAuthAsyncOperation: access token request failed
08-29 11:06:55.582  3126  4122 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 11:06:55.597  2204  4127 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 11:06:55.632  1506  3067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 11:06:55.633  1506  3067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 11:06:55.633  1506  3067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 11:06:55.633  1506  3067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:06:55.657  3126  4122 E KeepSync: IOException
08-29 11:06:55.657  3126  4122 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 11:06:55.657  3126  4122 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 11:06:55.657  3126  4122 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 11:06:55.657  3126  4122 E KeepSync: 	... 10 more
,08-29 11:06:55.657  3126  4122 W KeepSync: Sync result 2
,08-29 11:06:55.672   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131053, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 11:06:56.364   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 11:06:57.170   872   881 I art     : Background partial concurrent mark sweep GC freed 52475(3MB) AllocSpace objects, 7(180KB) LOS objects, 33% free, 29MB/43MB, paused 1.098ms total 100.008ms
,08-29 11:06:57.240  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:06:57.257   872  1983 D WifiService: setWifiEnabled: false pid=3842, uid=10000
,08-29 11:06:57.257   872  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:06:57.277  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 11:06:57.287   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 11:06:57.287   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 11:06:57.287   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 11:06:57.288   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:06:57.302   872  2343 D DhcpClient: Clearing IP address
,08-29 11:06:57.302   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:06:57.308  1506  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 11:06:57.309  1506  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 11:06:57.310  1506  4132 V NativeCrypto: Read error: ssl=0x9acec000: I/O error during system call, Connection timed out
,08-29 11:06:57.311   372   870 D CommandListener: Setting iface cfg
,08-29 11:06:57.309  1506  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 11:06:57.312  1506  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:06:57.313  1506  4132 V NativeCrypto: SSL shutdown failed: ssl=0x9acec000: I/O error during system call, Broken pipe
,08-29 11:06:57.316   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 11:06:57.316   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 11:06:57.318   396   396 E Parcel  : Reading a NULL string not supported here.
08-29 11:06:57.319   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 11:06:57.320   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 11:06:57.325   872  4108 D DhcpClient: Receive thread stopped
,08-29 11:06:57.325   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:06:57.326   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 11:06:57.334   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:06:57.339  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:06:57.339  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:57.339  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:06:57.339  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:06:57.339  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:06:57.340  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:06:57.340  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:06:57.338   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 11:06:57.344  1883  2282 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:06:57.362   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:06:57.365  3589  3589 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 11:06:57.365  3589  3589 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 11:06:57.366  3589  3589 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 11:06:57.385   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:06:57.385   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true,
08-29 11:06:57.386   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:57.387   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 11:06:57.396  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:57.400  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:06:57.402   872   882 I ActivityManager: Killing 3741:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 11:06:57.441  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:06:57.443  1715  1715 D SystemUpdateService: onCreate
,08-29 11:06:57.446  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:06:57.454  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 11:06:57.455  1715  2548 I iu.UploadsManager: num queued entries: 0
08-29 11:06:57.456  1715  2548 I iu.UploadsManager: num updated entries: 0
08-29 11:06:57.456  1715  2548 I iu.SyncManager: NEXT; no task
,08-29 11:06:57.457  1715  4147 I SystemUpdateService: active receiver: enabled
,08-29 11:06:57.461  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:06:57.462   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 11:06:57.462  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 11:06:57.463   872  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 11:06:57.465  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:06:57.466  1715  4147 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:06:57.470  4005  4005 D SprintDMHelper: simOperator: 
,08-29 11:06:57.470  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:06:57.471  1715  4147 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 11:06:57.472  1715  4147 I SystemUpdateService: now status is 0 (complete)
08-29 11:06:57.472  1715  4147 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 11:06:57.472  1715  4147 I SystemUpdateService: file has been verified
,08-29 11:06:57.472  1715  4147 I SystemUpdateService: OTA package size = 12249756
,08-29 11:06:57.505  2204  4149 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 11:06:57.514  1715  4147 I SystemUpdateService: showing system update notification
,08-29 11:06:57.524  1715  1715 D SystemUpdateService: onDestroy
,08-29 11:07:00.307   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8dcc190:true
,08-29 11:07:00.307  3991  3991 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 11:07:00.313  3991  3991 I bt_bluedroid: init
,08-29 11:07:00.313  3991  4153 I BluetoothAdapterState: Entering OffState
,08-29 11:07:00.320  3991  4154 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 11:07:00.321  3991  4154 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:07:00.321  3991  4154 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 11:07:00.322  3991  4154 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 11:07:00.324  3991  3991 I bt_bluedroid: get_profile_interface socket
,08-29 11:07:00.326  3991  3991 I bt_bluedroid: get_profile_interface sdp
,08-29 11:07:00.331  3991  4002 I bt_bluedroid: config_hci_snoop_log
,08-29 11:07:00.332  3991  4157 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 11:07:00.335  3991  4157 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:07:00.335   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 11:07:00.346  3991  4153 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 11:07:00.346  3991  4153 D BluetoothAdapterProperties: Setting state to 14
,08-29 11:07:00.347  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 11:07:00.352  3991  4153 D BluetoothBondStateMachine: make
,08-29 11:07:00.358  3991  4158 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 11:07:00.366  3991  4153 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:07:00.368  3991  3991 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 11:07:00.374  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:00.375  3991  3991 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:07:00.376  3991  3991 D BtGatt.GattService: Received start request. Starting profile...
,08-29 11:07:00.376  3991  3991 D BtGatt.GattService: start()
,08-29 11:07:00.377  3991  3991 I bt_bluedroid: get_profile_interface gatt
,08-29 11:07:00.378  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:00.378  3991  3991 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:07:00.390  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:00.391  3991  3991 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:00.391  3991  3991 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 11:07:00.391  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:00.393  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 11:07:00.394  3991  4153 I bt_bluedroid: enable
08-29 11:07:00.396  3991  4154 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 11:07:00.397  3991  4154 I bt_hci  : start_up
,08-29 11:07:00.420  3991  4154 I bt_vendor: alloc value 0xb398c189
,08-29 11:07:00.420  3991  4154 I bt_vendor: init
08-29 11:07:00.420  3991  4154 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 11:07:00.420  3991  4154 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 11:07:00.528  3991  4154 D bt_hci  : start_up starting async portion
,08-29 11:07:00.529  3991  4161 I bt_hci  : event_finish_startup
,08-29 11:07:00.529  3991  4161 I bt_hci_h4: hal_open
08-29 11:07:00.529  3991  4161 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 11:07:00.537  3991  4161 I bt_userial_vendor: device fd = 51 open
,08-29 11:07:00.569  3991  4161 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:07:00.602  3991  4161 D bt_hwcfg: Chipset BCM4354A2
,08-29 11:07:00.602  3991  4161 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 11:07:00.603  3991  4161 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 11:07:01.280  3991  4161 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 11:07:01.282  3991  4161 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 11:07:01.282  3991  4161 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 11:07:01.398  3991  4161 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:07:01.400  3991  4161 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 11:07:01.430  3991  4161 I bt_hwcfg: vendor lib fwcfg completed
,08-29 11:07:01.430  3991  4161 I bt_vendor: firmware callback
08-29 11:07:01.431  3991  4161 I bt_hci  : firmware_config_callback
,08-29 11:07:01.442  3991  4163 I bt_btu  : btu_task pending for preload complete event
08-29 11:07:01.442  3991  4163 I bt_btu_task: Bluetooth chip preload is complete
,08-29 11:07:01.443  3991  4163 I bt_btu  : btu_task received preload complete event
,08-29 11:07:01.452  3991  4163 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 11:07:01.452  3991  4163 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 11:07:01.453  3991  4163 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 11:07:01.453  3991  4163 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:07:01.453  3991  4163 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 11:07:01.454  3991  4163 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:07:01.454  3991  4163 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 11:07:01.454  3991  4163 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 11:07:01.454  3991  4163 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 11:07:01.455  3991  4163 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:07:01.455  3991  4163 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:07:01.455  3991  4163 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 11:07:01.455  3991  4163 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:07:01.456  3991  4163 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:07:01.456  3991  4163 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:07:01.592  3991  4163 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3909d9d
,08-29 11:07:01.592  3991  4163 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3909d9d 
,08-29 11:07:01.603  3991  4157 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 11:07:01.604  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 11:07:01.605  3991  4157 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:07:01.609  3991  4157 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:07:01.614  3991  4157 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:07:01.614  3991  4157 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 11:07:01.615  3991  4157 D bt_hci  : do_postload posting postload work item
,08-29 11:07:01.615  3991  4161 I bt_hci  : event_postload
,08-29 11:07:01.615  3991  4161 I bt_vendor: sco_config_cb
08-29 11:07:01.615  3991  4161 I bt_hci  : sco_config_callback postload finished.
,08-29 11:07:01.618  3991  4157 D bt_bte_conf: Device ID record 1 : primary,
,08-29 11:07:01.619  3991  4157 D bt_bte_conf:   vendorId            = 000f
,08-29 11:07:01.619  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:01.619  3991  4157 D bt_bte_conf:   vendorIdSource      = 0001
08-29 11:07:01.619  3991  4157 D bt_bte_conf:   product             = 1200
08-29 11:07:01.619  3991  4157 D bt_bte_conf:   version             = 1436
08-29 11:07:01.619  3991  4157 D bt_bte_conf:   clientExecutableURL = 
,08-29 11:07:01.620  3991  4157 D bt_bte_conf:   serviceDescription  = 
08-29 11:07:01.620  3991  4157 D bt_bte_conf:   documentationURL    = 
08-29 11:07:01.620  3991  4157 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 11:07:01.620  3991  4154 D bt_stack_manager: event_start_up_stack finished
08-29 11:07:01.622  3991  4161 I bt_vendor: low_power_mode_cb
08-29 11:07:01.622  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:01.623  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 11:07:01.624  3991  4153 D BluetoothAdapterProperties: Setting state to 15
08-29 11:07:01.625  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 11:07:01.627  3991  4153 I BluetoothAdapterState: Entering BleOnState
08-29 11:07:01.634  3991  4153 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 11:07:01.635  3991  4153 D BluetoothAdapterProperties: Setting state to 11
08-29 11:07:01.635  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 11:07:01.645  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
08-29 11:07:01.646  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:01.648  3991  3991 D HeadsetService: Received start request. Starting profile...
,08-29 11:07:01.649  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:01.653  3991  3991 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:07:01.653  3991  3991 D HeadsetStateMachine: make
,08-29 11:07:01.655  3991  4153 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:07:01.664  3991  3991 D HeadsetStateMachine: max_hf_connections = 1
,08-29 11:07:01.664  3991  3991 I bt_bluedroid: get_profile_interface handsfree
08-29 11:07:01.665  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 11:07:01.665  3991  4157 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 11:07:01.670  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:01.670  3991  3991 D A2dpService: Received start request. Starting profile...
,08-29 11:07:01.671  3991  3991 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 11:07:01.671  3991  3991 I bt_bluedroid: get_profile_interface avrcp
,08-29 11:07:01.676  3991  3991 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:07:01.677  3991  3991 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:07:01.677  3991  3991 D A2dpStateMachine: make
,08-29 11:07:01.678  3991  3991 I bt_bluedroid: get_profile_interface a2dp
,08-29 11:07:01.679  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 11:07:01.682  3991  4172 D A2dpStateMachine: Enter Disconnected: -2
,08-29 11:07:01.683  3991  3991 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 11:07:01.684  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:01.685  3991  3991 D HidService: Received start request. Starting profile...
,08-29 11:07:01.685  3991  3991 I bt_bluedroid: get_profile_interface hidhost
08-29 11:07:01.686  3991  3991 D HidService: setHidService(): set to: null
08-29 11:07:01.686  3991  4157 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38eb3e5
08-29 11:07:01.686  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 11:07:01.686  3991  3991 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 11:07:01.687  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:01.685  3912  3912 D BluetoothInputDevice: Proxy object connected
08-29 11:07:01.687  3991  3991 D HealthService: Received start request. Starting profile...
08-29 11:07:01.688  3912  3912 D HidProfile: Bluetooth service connected
08-29 11:07:01.688  3991  3991 I bt_bluedroid: get_profile_interface health
08-29 11:07:01.689  3991  3991 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 11:07:01.690  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:01.691  3912  3912 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 11:07:01.691  3991  3991 D PanService: Received start request. Starting profile...
08-29 11:07:01.691  3991  3991 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:07:01.691  3991  3991 I bt_bluedroid: get_profile_interface pan
,08-29 11:07:01.692  3991  4157 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:07:01.692  3912  3912 D PanProfile: Bluetooth service connected
,08-29 11:07:01.695  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:01.696  3991  3991 D BluetoothMapService: Received start request. Starting profile...
,08-29 11:07:01.696  3912  3912 D BluetoothMap: Proxy object connected
08-29 11:07:01.696  3991  3991 D BluetoothMapService: start()
,08-29 11:07:01.696  3912  3912 D MapProfile: Bluetooth service connected
08-29 11:07:01.696  3912  3912 D BluetoothMap: getConnectedDevices()
08-29 11:07:01.697  3912  3912 D BluetoothMap: Bluetooth is Not enabled
,08-29 11:07:01.698  3991  3991 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 11:07:01.699  3991  3991 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 11:07:01.699  3991  3991 D BluetoothMapAppObserver: createReceiver()
08-29 11:07:01.700  3991  3991 D BluetoothMapAppObserver: initObservers()
08-29 11:07:01.700  3991  3991 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 11:07:01.708  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:07:01.709  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:01.709  3991  3991 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:01.709  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:01.709  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:01.711  3991  4170 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isTurningOn()=true
,08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:01.711  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isTurningOn()=true
,08-29 11:07:01.712  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:01.713  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:01.713  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 11:07:01.713  3991  4153 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:07:01.713  3991  4153 D BluetoothAdapterProperties: State =  11
08-29 11:07:01.714  3991  4153 D BluetoothAdapterProperties: Setting state to 12
,08-29 11:07:01.717  3991  4157 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:07:01.717  3991  4157 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:07:01.717  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:07:01.718   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:01.718  1947  1957 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:01.719  1378  1700 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:01.719  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:01.721  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:01.722  1378  1378 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:07:01.722  1378  1378 D PanProfile: Bluetooth service connected
08-29 11:07:01.723  3991  4153 I BluetoothAdapterState: Entering OnState
08-29 11:07:01.723  1378  1391 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:01.724   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:01.725  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:01.727  3991  3991 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:07:01.727  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:01.727  3991  3991 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 11:07:01.726   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:01.728  3912  3924 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:07:01.729  3912  3925 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 11:07:01.729  3991  3991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:01.731  1378  1389 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:07:01.732  3991  3991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:07:01.733  3991  3991 D ObexServerSockets: Succeed to create listening sockets 
08-29 11:07:01.733  3991  3991 D ObexServerSockets0: startAccept()
,08-29 11:07:01.733  3991  3991 D ObexServerSockets0: prepareForNewConnect()
,08-29 11:07:01.734  1378  1378 D BluetoothInputDevice: Proxy object connected
08-29 11:07:01.734  1378  1378 D HidProfile: Bluetooth service connected
08-29 11:07:01.734  3912  3924 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 11:07:01.735  1378  1700 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:07:01.736  3991  3991 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 11:07:01.736  3991  3991 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 11:07:01.737   872   872 D BluetoothA2dp: Proxy object connected
08-29 11:07:01.738  3991  4177 D ObexServerSockets0: Accepting socket connection...
,08-29 11:07:01.738  1378  1378 D BluetoothMap: Proxy object connected
08-29 11:07:01.738   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:01.738  1378  1378 D MapProfile: Bluetooth service connected
08-29 11:07:01.738  1378  1378 D BluetoothMap: getConnectedDevices()
08-29 11:07:01.738  1378  4137 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 11:07:01.739  3991  4178 D ObexServerSockets0: Accepting socket connection...
,08-29 11:07:01.740  3912  3925 D BluetoothPan: onBluetoothStateChange on: true
,08-29 11:07:01.741  1378  1389 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:07:01.743  1378  1378 D BluetoothA2dp: Proxy object connected
08-29 11:07:01.746  3991  3991 D BluetoothMapService: onReceive
08-29 11:07:01.746  3991  3991 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:01.747  3991  3991 D BluetoothMapService: STATE_ON
08-29 11:07:01.747   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 11:07:01.749  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:01.751  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:01.753  3912  3912 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 11:07:01.756  3912  3912 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 11:07:01.761  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:07:01.765  3912  3912 D BluetoothA2dp: Proxy object connected
,08-29 11:07:01.768  3991  3991 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:07:01.768  3991  3991 D ObexServerSockets0: prepareForNewConnect()
,08-29 11:07:01.769  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-29 11:07:01.773  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:07:01.780  3912  3912 D BluetoothPbap: Proxy object connected
08-29 11:07:01.780  1378  1378 D BluetoothPbap: Proxy object connected
,08-29 11:07:01.780  3912  3912 D PbapServerProfile: Bluetooth service connected
08-29 11:07:01.780  1378  1378 D PbapServerProfile: Bluetooth service connected
,08-29 11:07:01.788  3991  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:07:01.803  3991  4187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:07:01.805  3991  4187 I BtOppRfcommListener: Accept thread started.
,08-29 11:07:01.819  1947  2151 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.819   872   872 D BluetoothHeadset: Proxy object connected
08-29 11:07:01.819   872   872 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.819  1378  1700 D BluetoothHeadset: Proxy object connected
08-29 11:07:01.820  1947  2151 D BluetoothHeadset: Proxy object connected
08-29 11:07:01.820  1378  1378 D HeadsetProfile: Bluetooth service connected
08-29 11:07:01.820   872   872 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.824  1378  4137 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.824  1378  1378 D HeadsetProfile: Bluetooth service connected
,08-29 11:07:01.829   872   889 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.838   872   889 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.859  3912  3924 D BluetoothHeadset: Proxy object connected
,08-29 11:07:01.860  3912  3912 D HeadsetProfile: Bluetooth service connected
,08-29 11:07:03.241   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-29 11:07:03.274  3991  4153 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 11:07:03.274  3991  4153 D BluetoothAdapterProperties: Setting state to 13
,08-29 11:07:03.274  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 11:07:03.276  3991  4153 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 11:07:03.279  3991  4153 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:07:03.289  3991  3991 D BluetoothMapService: onReceive
,08-29 11:07:03.290  3991  3991 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:03.290  3991  3991 D BluetoothMapService: STATE_TURNING_OFF
08-29 11:07:03.291  3991  3991 D BluetoothMapService: MAP Service closeService in
,08-29 11:07:03.291  3991  3991 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 11:07:03.292  3991  3991 D ObexServerSockets0: shutdown(block = true)
08-29 11:07:03.292  3991  4177 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 11:07:03.295  3991  4157 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:07:03.296  3991  3991 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 11:07:03.296  3991  3991 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 11:07:03.297  3991  4166 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 11:07:03.298  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 11:07:03.299  3991  4178 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 11:07:03.301  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:03.302  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:07:03.302  3991  3991 I BtOppRfcommListener: stopping Accept Thread
08-29 11:07:03.303  3991  4187 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 11:07:03.304  3991  4187 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:07:03.304  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:07:03.304  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:07:03.306  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 11:07:03.307  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:07:03.307  3991  3991 D HeadsetService: Received stop request...Stopping profile...
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:03.307  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:07:03.308  3842  3842 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:07:03.308  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:03.310  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:03.311  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:03.315  1947  1958 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:03.315   872   872 D BluetoothHeadset: Proxy object disconnected
,08-29 11:07:03.315   872   872 D BluetoothHeadset: Proxy object disconnected
,08-29 11:07:03.315  1378  4137 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:03.316  3991  3991 D A2dpService: Received stop request...Stopping profile...
08-29 11:07:03.316  3912  3924 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:03.317  3991  4172 D A2dpStateMachine: Exit Disconnected: -1
,08-29 11:07:03.317   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 11:07:03.316  1378  1378 D HeadsetProfile: Bluetooth service disconnected
08-29 11:07:03.318  1378  1378 D BluetoothA2dp: Proxy object disconnected
08-29 11:07:03.318   872   872 D BluetoothA2dp: Proxy object disconnected
08-29 11:07:03.318  3991  3991 V BluetoothAdapterState: isTurningOff()=true
08-29 11:07:03.318  3991  3991 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:03.318  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:03.319  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:03.319  3991  3991 D HidService: Received stop request...Stopping profile...
,08-29 11:07:03.319  3991  3991 D HidService: Stopping Bluetooth HidService
08-29 11:07:03.321  1378  1378 D BluetoothInputDevice: Proxy object disconnected
08-29 11:07:03.321  1378  1378 D HidProfile: Bluetooth service disconnected
,08-29 11:07:03.322  3991  3991 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:07:03.322  3991  3991 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 11:07:03.322  3991  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:07:03.322  3991  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:07:03.322  3991  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:07:03.323  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 11:07:03.323  3991  4157 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 11:07:03.323  3991  3991 D HealthService: Received stop request...Stopping profile...
08-29 11:07:03.325  3991  3991 D PanService: Received stop request...Stopping profile...
,08-29 11:07:03.325  1378  1378 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 11:07:03.325  1378  1378 D PanProfile: Bluetooth service disconnected
08-29 11:07:03.326  3912  3912 D DockEventReceiver: finishStartingService: stopping service
08-29 11:07:03.326  3991  3991 V BluetoothAdapterState: isTurningOff()=true
,08-29 11:07:03.326  3991  3991 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:03.326  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:03.326  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:03.326  3991  3991 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:07:03.327  3991  3991 D BluetoothMapService: stop()
08-29 11:07:03.327  3912  3912 D HeadsetProfile: Bluetooth service disconnected
,08-29 11:07:03.327  3912  3912 D BluetoothA2dp: Proxy object disconnected
08-29 11:07:03.327  3991  3991 D BluetoothMapAppObserver: deinitObservers()
08-29 11:07:03.327  3912  3912 D BluetoothInputDevice: Proxy object disconnected
,08-29 11:07:03.327  3991  3991 D BluetoothMapAppObserver: removeReceiver()
,08-29 11:07:03.327  3912  3912 D HidProfile: Bluetooth service disconnected
08-29 11:07:03.328  3912  3912 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 11:07:03.328  3912  3912 D PanProfile: Bluetooth service disconnected
08-29 11:07:03.329  1378  1378 D BluetoothMap: Proxy object disconnected
08-29 11:07:03.329  1378  1378 D MapProfile: Bluetooth service disconnected
,08-29 11:07:03.330  3912  3912 D BluetoothMap: Proxy object disconnected
08-29 11:07:03.330  3912  3912 D MapProfile: Bluetooth service disconnected
,08-29 11:07:03.330  3991  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:07:03.331  3991  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:07:03.331  3991  4163 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:07:03.331  3991  4163 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 11:07:03.331  3991  4163 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:07:03.331  3991  4163 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:07:03.331  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 11:07:03.333  3991  3991 V BluetoothAdapterState: isTurningOff()=true
,08-29 11:07:03.333  3991  3991 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:03.333  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:03.333  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:03.334  3991  3991 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:07:03.334  3991  3991 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 11:07:03.334  3991  3991 V BluetoothAdapterState: isTurningOff()=true
08-29 11:07:03.334  3991  3991 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:03.334  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:03.334  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:03.334  3991  3991 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:07:03.335  3991  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 11:07:03.335  3991  4157 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 11:07:03.335  3991  3991 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 11:07:03.336  3991  3991 V BluetoothAdapterState: isTurningOff()=true
08-29 11:07:03.336  3991  3991 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:07:03.336  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:03.336  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:03.336  3991  3991 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:07:03.337  3991  3991 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 11:07:03.337  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 11:07:03.338  3991  3991 D BluetoothMapService: MAP Service closeService in
08-29 11:07:03.338  3991  3991 V BluetoothAdapterState: isTurningOff()=true
08-29 11:07:03.338  3991  3991 V BluetoothAdapterState: isTurningOn()=false
,08-29 11:07:03.338  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:07:03.338  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:03.339  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 11:07:03.339  3991  4153 D BluetoothAdapterProperties: Setting state to 15
,08-29 11:07:03.339  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 11:07:03.340  3991  4153 I BluetoothAdapterState: Entering BleOnState
08-29 11:07:03.340  3991  3991 D BluetoothMapService: cleanup()
08-29 11:07:03.340  3991  3991 D BluetoothMapService: MAP Service closeService in
08-29 11:07:03.343   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:03.343  1947  2148 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:03.343  1378  1378 D BluetoothPbap: Proxy object disconnected
08-29 11:07:03.343  1378  1378 D PbapServerProfile: Bluetooth service disconnected
,08-29 11:07:03.343  1378  1700 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:07:03.344  3912  3924 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:07:03.346  3912  3925 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:03.346  1378  1391 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 11:07:03.346   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:07:03.349   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 11:07:03.349  3912  3924 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:07:03.350  3912  3925 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:07:03.353  1378  1389 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:07:03.354  3912  3924 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:07:03.355  3912  3912 D BluetoothPbap: Proxy object disconnected
08-29 11:07:03.355  1378  4137 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:07:03.355  3912  3912 D PbapServerProfile: Bluetooth service disconnected
08-29 11:07:03.355   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 11:07:03.355  1378  1700 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:07:03.356  3912  4192 D BluetoothPan: onBluetoothStateChange on: false
08-29 11:07:03.356  1378  1391 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:07:03.357  3991  4153 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 11:07:03.357  3991  4153 D BluetoothAdapterProperties: Setting state to 16
08-29 11:07:03.357  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 11:07:03.357  3991  4153 D BluetoothAdapterProperties: onBleDisable
08-29 11:07:03.358  3991  4153 I BluetoothAdapterState: Entering PendingCommandState
08-29 11:07:03.358  3991  4154 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 11:07:03.359  3991  4163 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 11:07:03.359  3991  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 11:07:03.359  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:03.361  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:03.362  3991  4157 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:07:03.363  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:03.364  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:03.365  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:07:03.369  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:07:03.370  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:07:03.561  3991  4157 I bt_hci  : shut_down
,08-29 11:07:03.582  3991  4161 I bt_vendor: low_power_mode_cb
,08-29 11:07:03.587  3991  4161 D bt_hwcfg: hw_epilog_process
,08-29 11:07:03.598  3991  4161 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 11:07:03.598  3991  4161 I bt_vendor: epilog_cb
08-29 11:07:03.599  3991  4161 I bt_hci  : epilog_finished_callback
,08-29 11:07:03.606  3991  4157 I bt_hci_h4: hal_close
,08-29 11:07:03.608  3991  4157 I bt_userial_vendor: device fd = 51 close
,08-29 11:07:03.734  3991  4154 D bt_stack_manager: event_shut_down_stack finished.
,08-29 11:07:03.735  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 11:07:03.745  3991  4153 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 11:07:03.746  3991  3991 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:07:03.749  3991  3991 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 11:07:03.749  3991  3991 D BtGatt.GattService: stop()
08-29 11:07:03.750  3991  3991 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 11:07:03.756  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:03.756  3991  3991 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:03.756  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:03.757  3991  3991 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 11:07:03.758  3991  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 11:07:03.758  3991  4153 D BluetoothAdapterProperties: Setting state to 10
08-29 11:07:03.759  3991  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 11:07:03.760  3991  4153 I BluetoothAdapterState: Entering OffState
,08-29 11:07:03.764   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 11:07:03.784  3991  3991 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 11:07:03.784  3991  3991 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 11:07:03.784  3991  3991 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 11:07:03.786  3991  4154 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 11:07:03.789  3991  4154 D bt_stack_manager: event_clean_up_stack finished.
08-29 11:07:03.790  3991  3991 I art     : System.exit called, status: 0
,08-29 11:07:03.790  3991  3991 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:07:03.850   872  1998 I ActivityManager: Process com.android.bluetooth (pid 3991) has died
,08-29 11:07:05.405   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 11:07:05.415  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-29 11:07:05.423   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 11:07:05.423   872   892 I Adreno  : Build Date                       : 10/20/15
08-29 11:07:05.423   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 11:07:05.423   872   892 I Adreno  : Local Branch                     : M14
08-29 11:07:05.423   872   892 I Adreno  : Remote Branch                    : 
08-29 11:07:05.423   872   892 I Adreno  : Remote Branch                    : 
08-29 11:07:05.423   872   892 I Adreno  : Reconstruct Branch               : 
,08-29 11:07:05.452   282   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (386 us)
,08-29 11:07:06.105  3842  3842 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 11:07:06.106  3842  3842 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 11:07:06.144   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 11:07:06.146  3842  3842 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b448f3e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ee3da98, 16908290=android.view.AbsSavedState$1@ee3da98}, android:focusedViewId=100}]}]
,08-29 11:07:06.146  3842  3842 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 11:07:06.147  3842  3842 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 11:07:06.147  3842  3842 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 11:07:06.163   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 11:07:06.167   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-29 11:07:06.168   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 11:07:06.168   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 11:07:06.270  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:07:06.270  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:06.397   282   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 11:07:06.402   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 11:07:06.403   872  1332 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,08-29 11:07:06.406   872   892 I DreamManagerService: Entering dreamland.
,08-29 11:07:06.407   872   892 I PowerManagerService: Dozing...
,08-29 11:07:06.409   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 11:07:06.497   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-29 11:07:06.497   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 11:07:06.501   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:07:06.511   872  1307 E native  : do suspend false
,08-29 11:07:06.536  1934  4201 D NfcService: Discovery configuration equal, not updating.
,08-29 11:07:06.570   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:07:06.580   872  1307 E native  : do suspend true,
,08-29 11:07:06.625   376  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-29 11:07:06.625   376  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 11:07:09.277  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:09.277  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2e92f1 added. We now have 6 listener(s)
08-29 11:07:09.278  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:09.280  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:09.281  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5002ed6 added. We now have 7 listener(s)
08-29 11:07:09.281  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:09.282  3842  3892 I System.out: IsBluetoothEnabled
,08-29 11:07:09.287  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:09.333   872   889 I ActivityManager: Start proc 4207:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 11:07:09.458  4207  4207 D AdapterServiceConfig: Adding HeadsetService
08-29 11:07:09.458  4207  4207 D AdapterServiceConfig: Adding A2dpService
08-29 11:07:09.458  4207  4207 D AdapterServiceConfig: Adding HidService
08-29 11:07:09.459  4207  4207 D AdapterServiceConfig: Adding HealthService
08-29 11:07:09.459  4207  4207 D AdapterServiceConfig: Adding PanService
08-29 11:07:09.459  4207  4207 D AdapterServiceConfig: Adding GattService
08-29 11:07:09.459  4207  4207 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 11:07:09.475   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c7bc768:true
08-29 11:07:09.475  4207  4207 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 11:07:09.480  4207  4207 I bt_bluedroid: init
,08-29 11:07:09.480  4207  4219 I BluetoothAdapterState: Entering OffState
,08-29 11:07:09.484  4207  4220 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 11:07:09.484  4207  4220 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 11:07:09.484  4207  4220 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 11:07:09.484  4207  4220 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 11:07:09.485  4207  4207 I bt_bluedroid: get_profile_interface socket
,08-29 11:07:09.487  4207  4207 I bt_bluedroid: get_profile_interface sdp
,08-29 11:07:09.490  4207  4218 I bt_bluedroid: config_hci_snoop_log
,08-29 11:07:09.492  4207  4223 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:07:09.494   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.,
,08-29 11:07:09.497  4207  4223 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:07:09.503  4207  4219 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 11:07:09.503  4207  4219 D BluetoothAdapterProperties: Setting state to 14
08-29 11:07:09.503  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 11:07:09.509  4207  4219 D BluetoothBondStateMachine: make
,08-29 11:07:09.513  4207  4224 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 11:07:09.521  4207  4207 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 11:07:09.522  4207  4219 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:07:09.529  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:09.529  4207  4207 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:07:09.530  4207  4207 D BtGatt.GattService: Received start request. Starting profile...
,08-29 11:07:09.530  4207  4207 D BtGatt.GattService: start()
08-29 11:07:09.530  4207  4207 I bt_bluedroid: get_profile_interface gatt
,08-29 11:07:09.531  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:09.531  4207  4207 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:07:09.539  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:09.540  4207  4207 V BluetoothAdapterState: isTurningOn()=false
08-29 11:07:09.540  4207  4207 V BluetoothAdapterState: isBleTurningOn()=true
08-29 11:07:09.540  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:09.540  4207  4219 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 11:07:09.542  4207  4219 I bt_bluedroid: enable
,08-29 11:07:09.542  4207  4220 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 11:07:09.543  4207  4220 I bt_hci  : start_up
,08-29 11:07:09.558  4207  4220 I bt_vendor: alloc value 0xb399c189
,08-29 11:07:09.558  4207  4220 I bt_vendor: init
08-29 11:07:09.558  4207  4220 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 11:07:09.558  4207  4220 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 11:07:09.666  4207  4220 D bt_hci  : start_up starting async portion
,08-29 11:07:09.667  4207  4227 I bt_hci  : event_finish_startup
08-29 11:07:09.668  4207  4227 I bt_hci_h4: hal_open
,08-29 11:07:09.669  4207  4227 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 11:07:09.678  4207  4227 I bt_userial_vendor: device fd = 51 open
,08-29 11:07:09.709  4207  4227 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:07:09.740  4207  4227 D bt_hwcfg: Chipset BCM4354A2
,08-29 11:07:09.741  4207  4227 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 11:07:09.742  4207  4227 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 11:07:10.389  4207  4227 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 11:07:10.391  4207  4227 D bt_hwcfg: Settlement delay -- 100 ms
08-29 11:07:10.391  4207  4227 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 11:07:10.508  4207  4227 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 11:07:10.509  4207  4227 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 11:07:10.539  4207  4227 I bt_hwcfg: vendor lib fwcfg completed
,08-29 11:07:10.539  4207  4227 I bt_vendor: firmware callback
08-29 11:07:10.539  4207  4227 I bt_hci  : firmware_config_callback
,08-29 11:07:10.550  4207  4231 I bt_btu  : btu_task pending for preload complete event
,08-29 11:07:10.551  4207  4231 I bt_btu_task: Bluetooth chip preload is complete
,08-29 11:07:10.551  4207  4231 I bt_btu  : btu_task received preload complete event
,08-29 11:07:10.561  4207  4231 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 11:07:10.561  4207  4231 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:07:10.561  4207  4231 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 11:07:10.562  4207  4231 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 11:07:10.562  4207  4231 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 11:07:10.562  4207  4231 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 11:07:10.562  4207  4231 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:07:10.563  4207  4231 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 11:07:10.564  4207  4231 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 11:07:10.565  4207  4231 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:07:10.565  4207  4231 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:07:10.567  4207  4231 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 11:07:10.567  4207  4231 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:07:10.568  4207  4231 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:07:10.569  4207  4231 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 11:07:10.703  4207  4231 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-29 11:07:10.704  4207  4231 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-29 11:07:10.716  4207  4223 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-29 11:07:10.718  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 11:07:10.719  4207  4223 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 11:07:10.725  4207  4223 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 11:07:10.728  4207  4223 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:07:10.730  4207  4223 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 11:07:10.731  4207  4223 D bt_hci  : do_postload posting postload work item
,08-29 11:07:10.731  4207  4227 I bt_hci  : event_postload
08-29 11:07:10.731  4207  4227 I bt_vendor: sco_config_cb
,08-29 11:07:10.732  4207  4227 I bt_hci  : sco_config_callback postload finished.
08-29 11:07:10.732  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:10.735  4207  4223 D bt_bte_conf: Device ID record 1 : primary
08-29 11:07:10.735  4207  4223 D bt_bte_conf:   vendorId            = 000f
08-29 11:07:10.735  4207  4223 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 11:07:10.735  4207  4223 D bt_bte_conf:   product             = 1200
08-29 11:07:10.735  4207  4223 D bt_bte_conf:   version             = 1436
08-29 11:07:10.736  4207  4223 D bt_bte_conf:   clientExecutableURL = 
08-29 11:07:10.736  4207  4223 D bt_bte_conf:   serviceDescription  = 
,08-29 11:07:10.736  4207  4223 D bt_bte_conf:   documentationURL    = 
08-29 11:07:10.737  4207  4223 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 11:07:10.737  4207  4227 I bt_vendor: low_power_mode_cb
,08-29 11:07:10.737  4207  4220 D bt_stack_manager: event_start_up_stack finished
08-29 11:07:10.739  4207  4219 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 11:07:10.739  4207  4219 D BluetoothAdapterProperties: Setting state to 15
08-29 11:07:10.739  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 11:07:10.740  4207  4219 I BluetoothAdapterState: Entering BleOnState
,08-29 11:07:10.742  4207  4219 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 11:07:10.742  4207  4219 D BluetoothAdapterProperties: Setting state to 11
08-29 11:07:10.742  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 11:07:10.746  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
08-29 11:07:10.750  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:10.751  4207  4207 D HeadsetService: Received start request. Starting profile...
08-29 11:07:10.755  4207  4207 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 11:07:10.755  4207  4207 D HeadsetStateMachine: make
08-29 11:07:10.760  4207  4219 I BluetoothAdapterState: Entering PendingCommandState
,08-29 11:07:10.765  4207  4207 D HeadsetStateMachine: max_hf_connections = 1
,08-29 11:07:10.766  4207  4207 I bt_bluedroid: get_profile_interface handsfree
,08-29 11:07:10.766  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 11:07:10.767  4207  4223 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 11:07:10.772  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:10.773  4207  4207 D A2dpService: Received start request. Starting profile...
,08-29 11:07:10.773  4207  4207 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 11:07:10.774  4207  4207 I bt_bluedroid: get_profile_interface avrcp
,08-29 11:07:10.780  4207  4207 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:07:10.780  4207  4207 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:07:10.781  4207  4207 D A2dpStateMachine: make
,08-29 11:07:10.782  4207  4207 I bt_bluedroid: get_profile_interface a2dp
08-29 11:07:10.782  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 11:07:10.786  4207  4241 D A2dpStateMachine: Enter Disconnected: -2
,08-29 11:07:10.788  4207  4207 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 11:07:10.789  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
08-29 11:07:10.789  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:07:10.790  4207  4207 D HidService: Received start request. Starting profile...
,08-29 11:07:10.790  4207  4207 I bt_bluedroid: get_profile_interface hidhost
08-29 11:07:10.790  4207  4207 D HidService: setHidService(): set to: null
08-29 11:07:10.790  4207  4223 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-29 11:07:10.790  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 11:07:10.791  4207  4207 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 11:07:10.793  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
08-29 11:07:10.793  4207  4207 D HealthService: Received start request. Starting profile...
,08-29 11:07:10.795  4207  4207 I bt_bluedroid: get_profile_interface health
,08-29 11:07:10.795  4207  4207 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 11:07:10.796  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
08-29 11:07:10.797  4207  4207 D PanService: Received start request. Starting profile...
,08-29 11:07:10.797  4207  4207 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:07:10.797  4207  4207 I bt_bluedroid: get_profile_interface pan
08-29 11:07:10.797  4207  4223 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 11:07:10.800  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:10.801  4207  4207 D BluetoothMapService: Received start request. Starting profile...
08-29 11:07:10.801  4207  4207 D BluetoothMapService: start()
,08-29 11:07:10.803  4207  4207 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 11:07:10.804  4207  4207 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 11:07:10.804  4207  4207 D BluetoothMapAppObserver: createReceiver()
,08-29 11:07:10.805  4207  4207 D BluetoothMapAppObserver: initObservers()
,08-29 11:07:10.805  4207  4207 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 11:07:10.813  4207  4207 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:10.813  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:10.813  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:10.813  4207  4239 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:07:10.813  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 11:07:10.815  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:10.815  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:10.816  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:10.816  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false,
,08-29 11:07:10.817  4207  4207 V BluetoothAdapterState: isTurningOff()=false
,08-29 11:07:10.817  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:10.817  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:10.817  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:10.817  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isTurningOn()=true
,08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 11:07:10.818  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:10.819  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 11:07:10.819  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 11:07:10.819  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 11:07:10.819  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 11:07:10.819  4207  4219 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 11:07:10.819  4207  4219 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:07:10.819  4207  4219 D BluetoothAdapterProperties: State =  11
08-29 11:07:10.823  4207  4223 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:07:10.823  4207  4219 D BluetoothAdapterProperties: Setting state to 12
08-29 11:07:10.823  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 11:07:10.824  4207  4223 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:07:10.824   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:10.824  1947  2144 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:10.825  4207  4219 I BluetoothAdapterState: Entering OnState
08-29 11:07:10.825  1378  4137 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:07:10.828  3912  3924 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:10.828  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:10.829  1378  1378 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:07:10.829  1378  1378 D PanProfile: Bluetooth service connected
,08-29 11:07:10.831  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:10.832  3912  4192 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 11:07:10.833  4207  4207 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:07:10.833  1378  1700 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:10.833   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:07:10.834   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:10.834  4207  4207 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 11:07:10.834  3912  3925 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 11:07:10.836  3912  3924 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:07:10.837  4207  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:07:10.838  1378  1389 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 11:07:10.840  4207  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:07:10.840  3912  4192 D BluetoothMap: onBluetoothStateChange: up=true
08-29 11:07:10.841  4207  4207 D ObexServerSockets: Succeed to create listening sockets 
,08-29 11:07:10.841  4207  4207 D ObexServerSockets0: startAccept()
08-29 11:07:10.841  4207  4207 D ObexServerSockets0: prepareForNewConnect()
,08-29 11:07:10.843  1378  4137 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 11:07:10.845  4207  4207 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 11:07:10.845  4207  4207 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 11:07:10.845  4207  4246 D ObexServerSockets0: Accepting socket connection...
,08-29 11:07:10.846   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 11:07:10.846  4207  4247 D ObexServerSockets0: Accepting socket connection...
08-29 11:07:10.846  1378  1391 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:07:10.846   872   872 D BluetoothA2dp: Proxy object connected
08-29 11:07:10.847  3912  3912 D BluetoothA2dp: Proxy object connected
,08-29 11:07:10.848  1378  1378 D BluetoothInputDevice: Proxy object connected
08-29 11:07:10.848  1378  1378 D HidProfile: Bluetooth service connected
08-29 11:07:10.849  3912  3912 D BluetoothInputDevice: Proxy object connected
,08-29 11:07:10.849  3912  3912 D HidProfile: Bluetooth service connected
08-29 11:07:10.850  3912  3925 D BluetoothPan: onBluetoothStateChange on: true
08-29 11:07:10.850  1378  1378 D BluetoothMap: Proxy object connected
,08-29 11:07:10.850  1378  1378 D MapProfile: Bluetooth service connected
08-29 11:07:10.850  1378  1378 D BluetoothMap: getConnectedDevices()
,08-29 11:07:10.852  3912  3912 D BluetoothMap: Proxy object connected
08-29 11:07:10.852  3912  3912 D MapProfile: Bluetooth service connected
,08-29 11:07:10.853  1378  1700 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:07:10.853  3912  3912 D BluetoothMap: getConnectedDevices()
,08-29 11:07:10.855  3912  3912 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 11:07:10.855  3912  3912 D PanProfile: Bluetooth service connected
,08-29 11:07:10.855  1378  1378 D BluetoothA2dp: Proxy object connected
,08-29 11:07:10.857   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 11:07:10.859  4207  4207 D BluetoothMapService: onReceive
08-29 11:07:10.859  4207  4207 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:07:10.859  4207  4207 D BluetoothMapService: STATE_ON
,08-29 11:07:10.860  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:10.866  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:07:10.871  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:07:10.875  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 11:07:10.884  3912  3912 D BluetoothPbap: Proxy object connected
,08-29 11:07:10.884  3912  3912 D PbapServerProfile: Bluetooth service connected
,08-29 11:07:10.885  1378  1378 D BluetoothPbap: Proxy object connected
,08-29 11:07:10.885  1378  1378 D PbapServerProfile: Bluetooth service connected
,08-29 11:07:10.890  4207  4207 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 11:07:10.890  4207  4207 D ObexServerSockets0: prepareForNewConnect()
08-29 11:07:10.892  4207  4252 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:07:10.918  4207  4256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:07:10.921  4207  4256 I BtOppRfcommListener: Accept thread started.
,08-29 11:07:10.927  1947  1957 D BluetoothHeadset: Proxy object connected
,08-29 11:07:10.927   872   872 D BluetoothHeadset: Proxy object connected
08-29 11:07:10.927   872   872 D BluetoothHeadset: Proxy object connected
08-29 11:07:10.928  1378  1700 D BluetoothHeadset: Proxy object connected
08-29 11:07:10.928  1378  1378 D HeadsetProfile: Bluetooth service connected
,08-29 11:07:10.929  3912  3925 D BluetoothHeadset: Proxy object connected
,08-29 11:07:10.929  3912  3912 D HeadsetProfile: Bluetooth service connected
08-29 11:07:10.929   872   872 D BluetoothHeadset: Proxy object connected
,08-29 11:07:10.933  3912  3924 D BluetoothHeadset: Proxy object connected
08-29 11:07:10.933  3912  3912 D HeadsetProfile: Bluetooth service connected
,08-29 11:07:10.934  1378  1389 D BluetoothHeadset: Proxy object connected
08-29 11:07:10.935  1378  1378 D HeadsetProfile: Bluetooth service connected
08-29 11:07:10.935   872   889 D BluetoothHeadset: Proxy object connected
,08-29 11:07:10.946   872   889 D BluetoothHeadset: Proxy object connected
,08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:11.309  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:11.317  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:11.321  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:11.321  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@edd5557 added. We now have 8 listener(s)
08-29 11:07:11.322  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:11.327   872  2006 D WifiService: setWifiEnabled: false pid=3842, uid=10000
,08-29 11:07:11.327   872  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:07:11.340  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:11.341   872  1933 D WifiService: setWifiEnabled: true pid=3842, uid=10000
08-29 11:07:11.341   872  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 11:07:11.356   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:11.376  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:11.382  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:11.390   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-29 11:07:11.391   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 11:07:11.392   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 11:07:11.392   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 11:07:11.393   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 11:07:11.393   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 11:07:11.393   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 11:07:11.414   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 11:07:11.415   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,08-29 11:07:11.415   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 11:07:11.416   372   870 D CommandListener: Setting iface cfg
,08-29 11:07:11.428   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-29 11:07:11.428   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 11:07:11.432   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 11:07:11.432   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 11:07:11.433   872  1307 E native  : do suspend true
,08-29 11:07:11.464   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 11:07:11.464   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:07:11.473   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 11:07:11.538   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 11:07:11.540  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 11:07:11.969  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 11:07:12.021  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 11:07:12.021  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 11:07:12.031   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 11:07:12.039   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 11:07:12.039   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:07:12.039   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 11:07:12.060   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:07:12.075   372   870 D CommandListener: Setting iface cfg
,08-29 11:07:12.076   872  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 11:07:12.084   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 11:07:12.130   872  4265 D DhcpClient: Receive thread started
,08-29 11:07:12.218   872  1307 E native  : do suspend false
,08-29 11:07:12.240   872  2343 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 11:07:12.262   872  4265 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 11:07:12.263   872  2343 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 11:07:12.266   872  2343 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 11:07:12.279   872  4265 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 11:07:12.280   872  2343 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 11:07:12.285   372   870 D CommandListener: Setting iface cfg
,08-29 11:07:12.297   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 11:07:12.297   872  2343 D DhcpClient: Scheduling renewal in 86399s
,08-29 11:07:12.303   872  1307 E native  : do suspend true
,08-29 11:07:12.321   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 11:07:12.322   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 11:07:12.323   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 11:07:12.328   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 11:07:12.330   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:07:12.362  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:07:12.367  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:07:12.371  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 11:07:12.372  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 11:07:12.374  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b448f3e Bundle[{}]
,08-29 11:07:12.376  3842  3892 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 11:07:12.376  3842  3892 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 11:07:12.376  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 11:07:12.377  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 11:07:12.378  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 11:07:12.378  3842  3892 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 11:07:12.387  3842  3892 I System.out: Running OutgoingSocketThread
,08-29 11:07:12.392  3842  4268 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 431)
,08-29 11:07:12.394   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 11:07:12.395   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 11:07:12.396  3842  4268 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38741
08-29 11:07:12.397   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 11:07:12.397  3842  4268 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 11:07:12.398   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 11:07:12.400   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 11:07:12.421   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 11:07:12.433   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 11:07:12.434   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-29 11:07:12.434   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-29 11:07:12.435   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 11:07:12.435   872  1309 D ConnectivityService:    accepting network in place of null
08-29 11:07:12.436   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 11:07:12.437   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 11:07:12.457   872  4264 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157142, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 11:07:12.474   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:07:12.520   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 11:07:12.526   872  4263 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:816::200e
,08-29 11:07:12.528   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 11:07:12.528   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:07:12.530   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 11:07:12.532   872   889 D Tethering: MasterInitialState.processMessage what=3
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:12.545  3842  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:07:12.547  3842  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:07:12.565  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 11:07:12.570  1715  1715 D SystemUpdateService: onCreate
,08-29 11:07:12.573  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 11:07:12.586  1715  4275 I SystemUpdateService: active receiver: enabled
,08-29 11:07:12.593   872  4263 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 09:07:12 GMT], X-Android-Received-Millis=[1472461632592], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472461632566]}
,08-29 11:07:12.594   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 11:07:12.594   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-29 11:07:12.594   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 11:07:12.598  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 11:07:12.598   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 11:07:12.601  1715  2548 I iu.UploadsManager: num queued entries: 0
,08-29 11:07:12.601  1715  2548 I iu.UploadsManager: num updated entries: 0
,08-29 11:07:12.606  1715  4275 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 11:07:12.611  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 11:07:12.613  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 11:07:12.615  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:07:12.620  1715  4278 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 11:07:12.621  1715  4278 W BaseAppContext: Using Auth Proxy for data requests.
08-29 11:07:12.622  1715  4278 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 11:07:12.623  4005  4005 D SprintDMHelper: simOperator: 
,08-29 11:07:12.623  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 11:07:12.632  1715  4275 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 11:07:12.633  1715  4275 I SystemUpdateService: now status is 0 (complete)
08-29 11:07:12.633  1715  4275 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 11:07:12.633  1715  4275 I SystemUpdateService: file has been verified
08-29 11:07:12.633  1715  4275 I SystemUpdateService: OTA package size = 12249756
,08-29 11:07:12.659  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:07:12.663  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 11:07:12.667  1715  2548 I iu.SyncManager: NEXT; no task
,08-29 11:07:12.680  1715  4275 I SystemUpdateService: showing system update notification
,08-29 11:07:12.709  1715  1715 D SystemUpdateService: onDestroy
,08-29 11:07:12.730  1506  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-29 11:07:12.730  1506  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 11:07:12.731  1506  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 11:07:12.731  1506  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 11:07:12.757  1715  4278 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-29 11:07:12.802  2204  4281 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 11:07:13.249  1883  2518 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 11:07:13.391  3842  3892 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 432)
08-29 11:07:13.392  3842  3892 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 432)
,08-29 11:07:13.401  3842  3892 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,08-29 11:07:13.403  3842  3892 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 11:07:13.404  3842  3892 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-29 11:07:13.410  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:13.410  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c880844 added. We now have 2 listener(s)
,08-29 11:07:13.412  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:07:13.412  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:13.412  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:07:13.412  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:13.412  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1086d2d added. We now have 9 listener(s)
,08-29 11:07:13.413  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:13.413  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:07:13.416  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:13.423  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:07:13.426  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:07:13.426  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:07:13.427  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:13.427  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277eff3 added. We now have 3 listener(s)
08-29 11:07:13.429  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:13.432  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:07:13.432  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:13.432  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:07:13.432  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:13.433  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:13.433  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f64b0 added. We now have 10 listener(s)
08-29 11:07:13.433  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:13.433  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:07:13.434  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:13.434  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:13.434  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:13.434  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.434  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:13.434  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:13.434  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c880844 removed from the list
08-29 11:07:13.434  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:13.435  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1086d2d removed from the list
08-29 11:07:13.435  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:13.435  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.435  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.435  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.437  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.437  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:13.437  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:13.437  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1086d2d not in the list
08-29 11:07:13.437  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.437  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.438  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:13.438  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager:, stopAdvertising
08-29 11:07:13.438  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.438  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f64b0 removed from the list
08-29 11:07:13.438  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:07:13.438  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.439  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:13.439  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:07:13.439  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277eff3 removed from the list
08-29 11:07:13.440  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:13.440  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2baf29 added. We now have 2 listener(s)
,08-29 11:07:13.441  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:07:13.442  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.442  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:13.442  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:13.442  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae42ae added. We now have 9 listener(s),
08-29 11:07:13.442  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:13.443  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:07:13.445  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-29 11:07:13.453  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:07:13.454  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:07:13.455  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:07:13.456  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:13.456  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88e1bdc added. We now have 3 listener(s)
08-29 11:07:13.457  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:13.462  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:07:13.462  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.463  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:13.463  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-29 11:07:13.463  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:13.463  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92714e5 added. We now have 10 listener(s)
,08-29 11:07:13.464  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:13.464  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:07:13.464  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:07:13.464  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:07:13.465  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:13.465  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:07:13.471  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 11:07:13.471  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:07:13.475  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:07:13.476  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 11:07:13.476  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:07:13.479  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:07:13.479  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 11:07:13.479  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 11:07:13.480  3842  3892 D BluetoothAdapter: STATE_ON
,08-29 11:07:13.483  4207  4237 D BtGatt.GattService: registerClient() - UUID=cb0a3094-5ef0-404c-89d8-7f502988465e
,08-29 11:07:13.484  4207  4223 D BtGatt.GattService: onClientRegistered() - UUID=cb0a3094-5ef0-404c-89d8-7f502988465e, clientIf=5
,08-29 11:07:13.485  3842  3853 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 11:07:13.486  4207  4248 D BtGatt.GattService: start scan with filters
,08-29 11:07:13.489  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:07:13.489  4207  4226 D BtGatt.ScanManager: handling starting scan
,08-29 11:07:13.490  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:07:13.490  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:07:13.490  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:07:13.492  4207  4226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4005f2
,08-29 11:07:13.493  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:07:13.496  4207  4223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 11:07:13.496  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:07:13.496  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.497  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:07:13.497  4207  4226 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 11:07:13.504  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 11:07:13.505  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.504  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:07:13.505  4207  4226 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:07:13.505  4207  4226 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 11:07:13.515  3842  3892 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:07:13.515  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:07:13.515  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 11:07:13.516  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.516  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 11:07:13.516  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:07:13.516  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 11:07:13.517  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:07:13.517  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:07:13.519  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:07:13.519  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:07:13.520  4207  4223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 11:07:13.520  3842  3892 D BluetoothAdapter: STATE_ON
08-29 11:07:13.520  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.521  4207  4237 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:07:13.522  4207  4248 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 11:07:13.524  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:07:13.524  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 11:07:13.524  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:07:13.524  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 11:07:13.525  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:07:13.527  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:07:13.528  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 11:07:13.528  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 11:07:13.528   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-29 11:07:13.528  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.528  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:07:13.529  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:07:13.529  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:13.533  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:07:13.533  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:07:13.533  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:07:13.536  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:07:13.536  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:07:13.536  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:07:13.537  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:13.537  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.537  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:13.537  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:07:13.537  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2baf29 removed from the list
08-29 11:07:13.538  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:13.538  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae42ae removed from the list
08-29 11:07:13.538  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:13.538  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.539  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.539  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.540  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:07:13.540  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.540  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.540  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:13.540  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:13.540  4207  4226 D BtGatt.ScanManager: stopping BLe Batch
08-29 11:07:13.541  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae42ae not in the list
08-29 11:07:13.541  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.541  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:13.543  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:07:13.543  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.543  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:13.543  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92714e5 removed from the list
08-29 11:07:13.543  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:07:13.543  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.543  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:13.543  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:13.543  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88e1bdc removed from the list
,08-29 11:07:13.544  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:13.544  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b91a61 added. We now have 2 listener(s)
,08-29 11:07:13.546  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:07:13.547  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.547  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:07:13.547  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:13.547  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dff986 added. We now have 9 listener(s)
08-29 11:07:13.547  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:13.548  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:07:13.548  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-29 11:07:13.548  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.549  4207  4226 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:07:13.552  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:13.559  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:07:13.561  4207  4223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 11:07:13.561  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.561  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:07:13.562  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:07:13.562  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:13.562  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a00a74 added. We now have 3 listener(s)
08-29 11:07:13.564  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:07:13.564  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.564  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:07:13.565  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:13.565  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0bfb9d added. We now have 10 listener(s)
,08-29 11:07:13.565  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:13.565  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:07:13.566  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 11:07:13.566  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:07:13.566  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:07:13.566  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:07:13.566  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:13.566  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:07:13.569  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:13.572  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:07:13.572  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-29 11:07:13.576  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:07:13.577  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:07:13.577  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:07:13.581  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:07:13.581  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 11:07:13.581  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 11:07:13.582  3842  3892 D BluetoothAdapter: STATE_ON
08-29 11:07:13.584  4207  4238 D BtGatt.GattService: registerClient() - UUID=4b101bec-88f3-45d6-a1a2-c1a65a41de39
,08-29 11:07:13.585  4207  4223 D BtGatt.GattService: onClientRegistered() - UUID=4b101bec-88f3-45d6-a1a2-c1a65a41de39, clientIf=5
08-29 11:07:13.586  3842  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 11:07:13.586  4207  4237 D BtGatt.GattService: start scan with filters
,08-29 11:07:13.590  4207  4226 D BtGatt.ScanManager: handling starting scan
08-29 11:07:13.591  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:07:13.591  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:07:13.591  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:07:13.591  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:07:13.594  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:07:13.595  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:07:13.595  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:07:13.597  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:07:13.600  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:07:13.600  3842  3892 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 11:07:13.601  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:07:13.601  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:07:13.601  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:07:13.601  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:13.602  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.602  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:07:13.602  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:13.602  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b91a61 removed from the list
08-29 11:07:13.602  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.602  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dff986 removed from the list
08-29 11:07:13.602  4207  4223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 11:07:13.602  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.603  4207  4226 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 11:07:13.603  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:07:13.603  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:07:13.604  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.604  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 11:07:13.604  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.604  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:13.606  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.606  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:13.607  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.607  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dff986 not in the list
,08-29 11:07:13.607  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 11:07:13.607  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:07:13.608  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:07:13.608  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:07:13.608  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:07:13.610  3842  3892 D BluetoothAdapter: STATE_ON,
08-29 11:07:13.612  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 11:07:13.611  4207  4248 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:07:13.612  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.612  4207  4226 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 11:07:13.612  4207  4226 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:07:13.614  4207  4217 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 11:07:13.614  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:07:13.614  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:07:13.615  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 11:07:13.615  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:07:13.615  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:07:13.616  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:07:13.617  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:07:13.617  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 11:07:13.617  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:07:13.618  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:07:13.619  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:07:13.619  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.619  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:07:13.619  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.620  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:07:13.620  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0bfb9d removed from the list
08-29 11:07:13.620  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:07:13.620  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:13.620  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.620  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.620  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:07:13.620  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a00a74 removed from the list
,08-29 11:07:13.621  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:13.622  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb1b499 added. We now have 2 listener(s)
08-29 11:07:13.624  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:07:13.625  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.625  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:13.625  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:13.625  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b06b35e added. We now have 9 listener(s)
,08-29 11:07:13.625  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:13.626  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:07:13.630  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:13.634  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:07:13.636  4207  4223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 11:07:13.637  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.637  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:13.637  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:07:13.637  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:13.637  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efe340c added. We now have 3 listener(s)
,08-29 11:07:13.639  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:13.640  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:07:13.640  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-29 11:07:13.640  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:07:13.640  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:07:13.640  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3600155 added. We now have 10 listener(s),
,08-29 11:07:13.640  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:13.641  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:07:13.641  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 11:07:13.641  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:07:13.641  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:07:13.641  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:07:13.643  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:07:13.643  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 11:07:13.643  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.645  3842  3892 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 11:07:13.645  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:07:13.650  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:07:13.651  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 11:07:13.651  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:07:13.652  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 11:07:13.652  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.652  4207  4226 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:07:13.655  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:07:13.655  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:07:13.656  3842  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:07:13.656  3842  3892 D BluetoothAdapter: STATE_ON
,08-29 11:07:13.658  4207  4237 D BtGatt.GattService: registerClient() - UUID=10e4f86e-f99e-4542-a909-e495e2e4be17
08-29 11:07:13.659  4207  4223 D BtGatt.GattService: onClientRegistered() - UUID=10e4f86e-f99e-4542-a909-e495e2e4be17, clientIf=5
,08-29 11:07:13.659  3842  3853 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 11:07:13.659  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 11:07:13.659  4207  4217 D BtGatt.GattService: start scan with filters
08-29 11:07:13.659  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.660  4207  4226 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 11:07:13.662  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:07:13.662  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:07:13.662  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:07:13.662  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 11:07:13.666  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:07:13.666  4207  4223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:07:13.666  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 11:07:13.666  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:07:13.666  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:07:13.667  4207  4226 D BtGatt.ScanManager: handling starting scan
08-29 11:07:13.668  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:07:13.672  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:07:13.672  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:07:13.672  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:13.673  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:13.673  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:07:13.673  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:07:13.673  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:13.673  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb1b499 removed from the list
08-29 11:07:13.673  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:07:13.673  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b06b35e removed from the list
08-29 11:07:13.673  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:07:13.673  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:13.674  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.674  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 11:07:13.674  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.674  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:07:13.674  4207  4223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 11:07:13.674  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.674  4207  4226 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 11:07:13.674  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:07:13.675  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:07:13.675  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.675  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b06b35e not in the list
,08-29 11:07:13.675  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 11:07:13.675  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:07:13.675  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:07:13.675  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:07:13.675  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:07:13.676  3842  3892 D BluetoothAdapter: STATE_ON,
08-29 11:07:13.676  4207  4218 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:07:13.677  4207  4237 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 11:07:13.677  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:07:13.677  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 11:07:13.677  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:07:13.677  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:07:13.677  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:07:13.678  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:07:13.678  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:07:13.678  3842  3892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,08-29 11:07:13.678  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:07:13.679  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.680  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:07:13.680  3842  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:07:13.680  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 11:07:13.680  3842  3842 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:07:13.680  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.680  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:07:13.680  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.680  4207  4226 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 11:07:13.680  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.680  4207  4226 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 11:07:13.680  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3600155 removed from the list
,08-29 11:07:13.680  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:07:13.680  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:07:13.680  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 11:07:13.680  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:13.681  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efe340c removed from the list
,08-29 11:07:13.681  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:07:13.681  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6c5dd1 added. We now have 2 listener(s),
08-29 11:07:13.683  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 11:07:13.683  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.683  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:07:13.683  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:13.683  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95fd036 added. We now have 9 listener(s)
,08-29 11:07:13.683  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:07:13.683  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:07:13.685  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:07:13.693  3842  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:07:13.694  3842  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:07:13.695  3842  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:07:13.696  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 11:07:13.696  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d94f8a4 added. We now have 3 listener(s)
,08-29 11:07:13.697  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:13.697  4207  4223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 11:07:13.697  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.699  3842  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:07:13.700  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 11:07:13.700  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:07:13.700  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:07:13.700  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:07:13.700  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f08060d added. We now have 10 listener(s)
,08-29 11:07:13.700  3842  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:07:13.701  3842  3892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:07:13.701  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:07:13.701  3842  3892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:07:13.701  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:07:13.701  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.701  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:07:13.701  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:07:13.701  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6c5dd1 removed from the list
,08-29 11:07:13.702  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.702  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95fd036 removed from the list
,08-29 11:07:13.702  3842  3892 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:07:13.702  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.702  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.702  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.703  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 11:07:13.703  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:07:13.703  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.703  3842  3892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95fd036 not in the list
08-29 11:07:13.703  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.704  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.704  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 11:07:13.704  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.704  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:07:13.704  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:07:13.704  3842  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:07:13.704  3842  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f08060d removed from the list
08-29 11:07:13.705  3842  3892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:07:13.705  3842  3892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:07:13.705  3842  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:07:13.705  3842  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:07:13.705  3842  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d94f8a4 removed from the list
08-29 11:07:13.706  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 11:07:13.706  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 11:07:13.706  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 11:07:13.706  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:07:13.706  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 11:07:13.706  3842  3892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 11:07:13.712  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 11:07:13.712  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.712  4207  4226 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:07:13.714  3842  4287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: My test thread name)
,08-29 11:07:13.715  3842  4287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: My test thread name)
08-29 11:07:13.715  3842  4287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 11:07:13.718  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 11:07:13.718  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 11:07:13.718  4207  4226 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 11:07:13.718  3842  4288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,08-29 11:07:13.718  3842  4288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: My test thread name)
,08-29 11:07:13.719  3842  4288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:07:13.720  3842  3892 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 11:07:13.721  3842  3892 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 11:07:13.721  3842  3892 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 11:07:13.721  3842  3892 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 11:07:13.721  3842  3892 D com.test.thalitest.ThaliTestRunner: Total duration: 22806 ms
,08-29 11:07:13.723  3842  3892 I jxcore-log: *Native tests were executed*
08-29 11:07:13.723  3842  3892 I jxcore-log: 
08-29 11:07:13.723  3842  3892 I jxcore-log: Total number of executed tests:  80
08-29 11:07:13.723  3842  3892 I jxcore-log: 
,08-29 11:07:13.723  3842  3892 I jxcore-log: Number of passed tests:  80
08-29 11:07:13.723  3842  3892 I jxcore-log: 
08-29 11:07:13.723  3842  3892 I jxcore-log: Number of failed tests:  0
08-29 11:07:13.723  3842  3892 I jxcore-log: 
08-29 11:07:13.723  3842  3892 I jxcore-log: Number of ignored tests:  0
08-29 11:07:13.723  3842  3892 I jxcore-log: 
08-29 11:07:13.724  3842  3892 I jxcore-log: Total duration:  22806
08-29 11:07:13.724  3842  3892 I jxcore-log: 
08-29 11:07:13.724  4207  4223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 11:07:13.724  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 11:07:13.724  3842  3892 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 11:07:13.724  3842  3892 I jxcore-log: 
08-29 11:07:13.730  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.730  3842  3892 I jxcore-log: 
,08-29 11:07:13.731  3842  3842 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 11:07:13.732  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.732  3842  3892 I jxcore-log: 
08-29 11:07:13.733  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.733  3842  3892 I jxcore-log: 
08-29 11:07:13.734  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.734  3842  3892 I jxcore-log: 
08-29 11:07:13.735  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.735  3842  3892 I jxcore-log: 
08-29 11:07:13.737  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.737  3842  3892 I jxcore-log: 
08-29 11:07:13.739  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.739  3842  3892 I jxcore-log: 
08-29 11:07:13.740  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.740  3842  3892 I jxcore-log: 
08-29 11:07:13.741  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.741  3842  3892 I jxcore-log: 
08-29 11:07:13.742  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:07:13.742  3842  3892 I jxcore-log: 
08-29 11:07:13.743  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:07:13.743  3842  3892 I jxcore-log: 
08-29 11:07:13.744  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:07:13.744  3842  3892 I jxcore-log: 
08-29 11:07:13.745  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.745  3842  3892 I jxcore-log: 
08-29 11:07:13.745  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.745  3842  3892 I jxcore-log: 
08-29 11:07:13.746  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.746  3842  3892 I jxcore-log: 
08-29 11:07:13.747  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.747  3842  3892 I jxcore-log: 
08-29 11:07:13.748  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.748  3842  3892 I jxcore-log: 
08-29 11:07:13.749  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.749  3842  3892 I jxcore-log: 
08-29 11:07:13.750  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.750  3842  3892 I jxcore-log: 
08-29 11:07:13.750  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.750  3842  3892 I jxcore-log: 
08-29 11:07:13.752  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.752  3842  3892 I jxcore-log: 
08-29 11:07:13.752  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:07:13.752  3842  3892 I jxcore-log: 
08-29 11:07:13.753  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:07:13.753  3842  3892 I jxcore-log: 
08-29 11:07:13.758  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:07:13.758  3842  3892 I jxcore-log: 
,08-29 11:07:13.759  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.759  3842  3892 I jxcore-log: 
,08-29 11:07:13.760  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.760  3842  3892 I jxcore-log: 
,08-29 11:07:13.762  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.762  3842  3892 I jxcore-log: 
08-29 11:07:13.763  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.763  3842  3892 I jxcore-log: 
08-29 11:07:13.764  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.764  3842  3892 I jxcore-log: 
08-29 11:07:13.765  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:07:13.765  3842  3892 I jxcore-log: 
,08-29 11:07:14.033  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:07:14.038  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:07:14.038  3842  3892 I jxcore-log: 
,08-29 11:07:14.120  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:07:14.124  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:07:14.124  3842  3892 I jxcore-log: 
,08-29 11:07:14.180  3842  3842 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:07:14.184  3842  3892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:07:14.184  3842  3892 I jxcore-log: 
,08-29 11:07:14.408  4289  4289 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 11:07:14.413  4289  4289 D AndroidRuntime: CheckJNI is OFF
,08-29 11:07:14.456  4289  4289 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 11:07:14.504  4289  4289 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 11:07:14.526  4289  4289 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 11:07:14.536   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 11:07:14.537   872   885 I ActivityManager: Killing 3842:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 11:07:14.641   872   895 W PackageSettings: Skipping PackageSetting{bf0ca37 com.example.hello/10273} due to missing metadata
,08-29 11:07:14.653   872   882 D GraphicsStats: Buffer count: 2
08-29 11:07:14.653   872  1984 I WindowState: WIN DEATH: Window{f0f13b5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 11:07:14.655   872  1308 D WifiService: Client connection lost with reason: 4
,08-29 11:07:14.702   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 11:07:14.702   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 11:07:14.702   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-29 11:07:14.702   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 11:07:14.702   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:14.702   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:14.702   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 11:07:14.702   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 11:07:14.704   872   885 I ActivityManager:   Force finishing activity ActivityRecord{b5f8f92 u0 com.test.thalitest/.MainActivity t2}
,08-29 11:07:14.704   872   895 I art     : Starting a blocking GC Explicit
,08-29 11:07:14.718   872   882 W ActivityManager: Spurious death for ProcessRecord{b907cd 0:com.test.thalitest/u0a0}, curProc for 3842: null
,08-29 11:07:14.746   872   895 I art     : Explicit concurrent mark sweep GC freed 14082(980KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 798us total 41.370ms
,08-29 11:07:14.767   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 11:07:14.769  4289  4289 I art     : System.exit called, status: 0
08-29 11:07:14.770  4289  4289 I AndroidRuntime: VM exiting with result code 0.
,08-29 11:07:14.774   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 11:07:14.786   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 11:07:14.794  4207  4207 D BluetoothMapAppObserver: onReceive
,08-29 11:07:14.794  4207  4207 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 11:07:14.796  1883  2258 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 11:07:14.797   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 11:07:14.801  3683  3683 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 11:07:14.820  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 11:07:14.836  1947  1947 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 11:07:14.836   872  2006 I ActivityManager: Start proc 4303:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 11:07:14.846  1870  4313 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 11:07:14.852  1870  4313 I Decoder : createOrResetDecoder
,08-29 11:07:14.881  4303  4303 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 11:07:14.885  1506  1506 I ConfigService: onCreate
,08-29 11:07:14.887   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 11:07:14.902   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 11:07:14.903   872   884 E PackageManager: Failed to write settings, restoring backup
08-29 11:07:14.903   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 11:07:14.903   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 11:07:14.903   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 11:07:14.903   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 11:07:14.903   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 11:07:14.903   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:14.903   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:14.903   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:07:14.905   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-29 11:07:14.905   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 11:07:14.905   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:07:14.905   872   885 E DropBoxManagerService: 	... 13 more
,08-29 11:07:14.906   872  2006 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3842 uid 10000
08-29 11:07:14.907  1964  2071 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-29 11:07:14.907  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-29 11:07:14.910  1870  4313 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 11:07:14.921   872  1933 I ActivityManager: Start proc 4317:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 11:07:14.921  1964  2071 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 11:07:14.921  1964  2071 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1964
08-29 11:07:14.921  1964  2071 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:14.921  1964  2071 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:07:14.924   872  1983 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 11:07:14.925   872  4325 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:07:14.925   872  4325 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:07:14.925   872  4325 E DropBoxManagerService: 	... 5 more
,08-29 11:07:14.927  1964  2071 I Process : Sending signal. PID: 1964 SIG: 9
,08-29 11:07:14.960  1870  4313 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 11:07:14.962  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 11:07:14.962  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 11:07:14.965  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 11:07:14.965  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 11:07:14.966  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 11:07:14.966  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 11:07:14.967  1870  4313 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 11:07:14.968  1870  4313 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 11:07:14.968  1870  4313 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 11:07:14.968  1870  4313 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 11:07:14.968  1870  4313 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 11:07:14.968  1870  4313 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 11:07:15.033   872  1520 D GraphicsStats: Buffer count: 1
08-29 11:07:15.033   872  1521 I WindowState: WIN DEATH: Window{cceb989 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-29 11:07:15.050   872  2002 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1964) has died
08-29 11:07:15.053   872  2002 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-29 11:07:15.058   872  2002 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 11:07:15.060  4303  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.060  4303  4332 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.062  4303  4332 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:07:15.080  4303  4303 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 11:07:15.089   872   885 I ActivityManager: Start proc 4335:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 11:07:15.103  4303  4345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 11:07:15.112   872  1520 I ActivityManager: Start proc 4349:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 11:07:15.153  4349  4349 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 11:07:15.160  4335  4335 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:07:15.160  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 11:07:15.160  4335  4335 D AndroidRuntime: Shutting down VM
,08-29 11:07:15.168  4335  4335 E AndroidRuntime: FATAL EXCEPTION: main
08-29 11:07:15.168  4335  4335 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4335
08-29 11:07:15.168  4335  4335 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 11:07:15.168  4335  4335 E AndroidRuntime: 	... 10 more
,08-29 11:07:15.171   872  1521 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 11:07:15.172  4335  4335 I Process : Sending signal. PID: 4335 SIG: 9
,08-29 11:07:15.172   872  4363 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:07:15.172   872  4363 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:07:15.172   872  4363 E DropBoxManagerService: 	... 5 more
,08-29 11:07:15.185   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
08-29 11:07:15.187  1715  4361 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-29 11:07:15.187  1715  4361 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-29 11:07:15.191  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 11:07:15.191  1506  1506 D AndroidRuntime: Shutting down VM
08-29 11:07:15.192  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
08-29 11:07:15.192  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
08-29 11:07:15.192  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 11:07:15.192  1506  1506 E AndroidRuntime: 	... 8 more
,08-29 11:07:15.196  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
,08-29 11:07:15.197   872  4365 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:07:15.197   872  4365 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:07:15.197   872  4365 E DropBoxManagerService: 	... 5 more
,08-29 11:07:15.201  1715  4361 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-29 11:07:15.202  1715  4361 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-29 11:07:15.206   872  1363 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4335) has died
,08-29 11:07:15.207   872  1363 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 11:07:15.217  4303  4332 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-29 11:07:15.224   872   885 I ActivityManager: Start proc 4367:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 11:07:15.227  4303  4345 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.227  4303  4345 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 11:07:15.230  4303  4345 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 11:07:15.230  4303  4345 E AndroidRuntime: Process: android.process.acore, PID: 4303
08-29 11:07:15.230  4303  4345 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 11:07:15.230  4303  4345 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: Can't write: system_app_crash
08-29 11:07:15.233   872  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 11:07:15.233   872  4377 E DropBoxManagerService: 	... 5 more
,08-29 11:07:15.235  4303  4345 I Process : Sending signal. PID: 4303 SIG: 9
08-29 11:07:15.270   872  1308 D WifiService: Client connection lost with reason: 4
08-29 11:07:15.275   872  1933 I ActivityManager: Process com.google.process.gapps (pid 1506) has died
08-29 11:07:15.275   872  1933 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms

```
