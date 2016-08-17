#### Test 807688564f75085_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 15:18:34.629  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:18:34.636  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 15:18:34.637  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 15:18:34.657  1500  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 15:18:34.657  1500  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 15:18:34.657  1500  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:18:34.657  1500  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 15:18:34.683  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 15:18:34.683  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 15:18:34.683  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-17 15:18:34.884   874  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-17 15:18:35.212  3929  3929 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 15:18:35.217  3929  3929 D AndroidRuntime: CheckJNI is OFF
08-17 15:18:35.260  3929  3929 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 15:18:35.312  3929  3929 I Radio-JNI: register_android_hardware_Radio DONE
08-17 15:18:35.333  3929  3929 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 15:18:35.338   874  1603 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 15:18:35.366  2037  2388 W SearchService: Abort, client detached.
08-17 15:18:35.377  2037  2037 I HotwordDetector: Closing mic
08-17 15:18:35.378  2037  2341 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d7549c5
08-17 15:18:35.379  2037  2347 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 15:18:35.402  3929  3929 D AndroidRuntime: Shutting down VM
08-17 15:18:35.428   874  1965 I ActivityManager: Start proc 3938:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 15:18:35.429   374  2349 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 15:18:35.432   374  2349 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 15:18:35.437   374  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 15:18:35.452  2037  2346 I MicroRecognitionRnrImpl: Detection finished
08-17 15:18:35.453  2037  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 15:18:35.517  3938  3938 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 15:18:35.548  3938  3938 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 15:18:35.558  3938  3938 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4251-4255)
08-17 15:18:35.558  3938  3938 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:18:35.579  3938  3938 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7f66c6a}
08-17 15:18:35.580  3938  3938 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:18:35.580  3938  3938 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 15:18:35.590  3938  3938 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 15:18:35.591  3938  3938 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 15:18:35.611  3938  3938 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 15:18:35.647  3938  3938 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 15:18:35.647  3938  3938 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 15:18:35.647  3938  3938 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 15:18:35.647  3938  3938 I Adreno  : Build Date                       : 10/20/15
08-17 15:18:35.647  3938  3938 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 15:18:35.647  3938  3938 I Adreno  : Local Branch                     : M14
08-17 15:18:35.647  3938  3938 I Adreno  : Remote Branch                    : 
08-17 15:18:35.647  3938  3938 I Adreno  : Remote Branch                    : 
08-17 15:18:35.647  3938  3938 I Adreno  : Reconstruct Branch               : 
,08-17 15:18:35.748   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a66c2a:true
,08-17 15:18:35.784  3938  3938 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 15:18:35.799  3938  3938 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 15:18:35.852  3938  3977 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 15:18:35.862  3938  3963 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 15:18:35.906  3938  3977 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 15:18:36.006   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +601ms
,08-17 15:18:36.012  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-17 15:18:36.079  3938  3938 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3938
,08-17 15:18:36.199  3938  3938 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 15:18:36.269   874  1984 I ActivityManager: Killing 2636:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-17 15:18:36.311   874  1984 I ActivityManager: Killing 3217:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-17 15:18:36.416  3938  3979 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1696728784
,08-17 15:18:36.424  3938  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 15:18:36.424  3938  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 15:18:36.424  3938  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 15:18:36.424  3938  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 15:18:36.424  3938  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 15:18:36.425  3938  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f1cfce added. We now have 1 listener(s)
,08-17 15:18:36.436  3938  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 15:18:36.440  3938  3979 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:18:36.445  3938  3979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:18:36.445  3938  3979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 15:18:36.454  3938  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22d5c85 added. We now have 1 listener(s)
,08-17 15:18:36.455  3938  3979 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:18:36.458   874  1308 D WifiService: New client listening to asynchronous messages
,08-17 15:18:36.460  3938  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:18:36.460  3938  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 15:18:36.460  3938  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 15:18:36.460  3938  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
,08-17 15:18:36.460  3938  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 15:18:36.464  3938  3979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:18:36.465  3938  3979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 15:18:36.475  3938  3979 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:18:36.476  3938  3979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:18:36.476  3938  3979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-17 15:18:36.476  3938  3979 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:18:36.477  3938  3979 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 15:18:36.571  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:18:36.574  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:18:36.576  3938  3938 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 15:18:37.424  3938  3988 W jxcore-log: Initializing JXcore engine
,08-17 15:18:37.425  3938  3988 W jxcore-log: JXcore engine is ready
,08-17 15:18:37.456  3988  3988 W Thread-362: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 15:18:37.456  3988  3988 W Thread-362: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11505]" dev="sockfs" ino=11505 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 15:18:37.459  3988  3988 W Thread-362: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 15:18:37.459  3988  3988 W Thread-362: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26387]" dev="sockfs" ino=26387 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 15:18:37.472  3938  3988 W jxcore-log: Starting JXcore engine
,08-17 15:18:37.560  3938  3988 W jxcore-log: Platform android
08-17 15:18:37.560  3938  3988 W jxcore-log: 
,08-17 15:18:37.560  3938  3988 W jxcore-log: Process ARCH arm
08-17 15:18:37.560  3938  3988 W jxcore-log: 
,08-17 15:18:37.843  3938  3988 I jxcore-log: JXcore Cordova bridge is ready!
08-17 15:18:37.843  3938  3988 I jxcore-log: 
,08-17 15:18:37.843  3938  3988 W jxcore-log: JXcore engine is started
,08-17 15:18:37.851  3938  3979 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 15:18:37.857  3938  3938 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 15:18:40.764  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:18:40.770  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:18:40.834  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:18:40.835  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 15:18:40.835  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:18:40.836  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:18:40.877  3174  3998 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 15:18:40.877  3174  3998 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at blb.a(PG:3937)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at czp.a(PG:18188)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:18:40.877  3174  3998 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	... 12 more
08-17 15:18:40.877  3174  3998 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at fal.a(PG:38)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:18:40.877  3174  3998 E HttpOperation: 	... 14 more
,08-17 15:18:40.934  1500  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 15:18:40.934  1500  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 15:18:40.934  1500  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:18:40.934  1500  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:18:40.971  3174  3998 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 15:18:40.971  3174  3998 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at hec.a(PG:42)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at hee.a(PG:102)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at czr.a(PG:65)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at kka.a(PG:108)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at czp.a(PG:19176)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113),
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:18:40.971  3174  3998 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	... 15 more
08-17 15:18:40.971  3174  3998 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at fal.a(PG:38)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:18:40.971  3174  3998 E HttpOperation: 	... 17 more
08-17 15:18:40.972  3174  3998 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 15:18:40.972  3174  3998 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at hec.a(PG:42)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at hee.a(PG:102)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at czr.a(PG:65)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at kka.a(PG:108)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	... 15 more
08-17 15:18:40.972  3174  3998 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at fal.a(PG:38)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 15:18:40.972  3174  3998 E ExperimentLoader: 	... 17 more
,08-17 15:18:41.094   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128750, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:18:53.955  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 15:18:53.955  3938  3988 I jxcore-log: 
,08-17 15:18:53.957  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 15:18:53.957  3938  3988 I jxcore-log: 
,08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:18:53.967  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:18:53.972  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:18:53.974  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 15:18:53.974  3938  3988 I jxcore-log: 
,08-17 15:18:53.975  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 15:18:53.975  3938  3988 I jxcore-log: 
,08-17 15:18:54.309  3938  3988 I jxcore-log: Running unit tests
08-17 15:18:54.309  3938  3988 I jxcore-log: 
,08-17 15:18:54.310  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:18:54.310  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd04e78 added. We now have 2 listener(s)
,08-17 15:18:54.311  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:18:54.311  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:18:54.311  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:18:54.311  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:18:54.311  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a2951 added. We now have 2 listener(s)
08-17 15:18:54.311  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:18:54.312  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:18:54.313  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:18:54.322  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:18:54.323  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:18:54.323  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:18:54.324  3938  3988 D ExecuteNativeTests: Running unit tests
,08-17 15:18:54.332  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:18:54.334  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:18:54.412  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:18:54.412  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 added. We now have 3 listener(s)
,08-17 15:18:54.413  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:18:54.413  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:18:54.413  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:18:54.414  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:18:54.414  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 added. We now have 3 listener(s)
08-17 15:18:54.414  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:18:54.415  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:18:54.418  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:18:54.430  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:18:54.432  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:54.432  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:18:54.434  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:18:54.435  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 15:18:54.435  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:18:54.435  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:18:54.435  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:18:54.436  3938  3988 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 15:18:54.437  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:18:54.437  3938  3988 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:18:54.437  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:18:54.437  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:18:54.437  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:18:54.437  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:18:54.438  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:18:54.438  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:18:54.438  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:18:54.438  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:18:54.438  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.438  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:18:54.438  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:18:54.439  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 removed from the list
08-17 15:18:54.439  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:18:54.439  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 removed from the list
08-17 15:18:54.439  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:18:54.439  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.440  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.440  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.441  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:18:54.441  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:18:54.441  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:18:54.441  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:18:54.443  3938  3988 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 15:18:54.444  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:18:54.444  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:18:54.444  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:18:54.444  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:18:54.444  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.444  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.444  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:18:54.444  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:18:54.444  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:18:54.444  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:18:54.444  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.444  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 1,5:18:54.445  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.445  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.447  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:18:54.447  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:18:54.447  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:18:54.447  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:18:54.451  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:18:54.452  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:18:54.452  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:18:54.453  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:18:54.453  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:18:54.453  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:18:54.453  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.453  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.453  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:18:54.453  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:18:54.453  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:18:54.453  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:18:54.453  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.453  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.453  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:54.453  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:54.454  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:18:54.454  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:18:54.454  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:18:54.455  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:18:54.455  3938  3988 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:18:54.456  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:18:54.460  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:18:54.462  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:18:54.462  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:18:54.464  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:18:54.465  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:18:54.465  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:18:54.465  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:18:54.465  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:18:54.465  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:18:54.465  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:18:54.469  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:18:54.469  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:18:54.474  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:18:54.476  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:18:54.476  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:18:54.479  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 15:18:54.481  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 15:18:54.481  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:18:54.482  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:18:54.483  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:18:54.485  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:18:54.488  2858  2911 D BtGatt.GattService: registerClient() - UUID=ce4fb342-755a-403a-a912-4789ac9e329e
08-17 15:18:54.489  2858  2906 D BtGatt.GattService: onClientRegistered() - UUID=ce4fb342-755a-403a-a912-4789ac9e329e, clientIf=5
08-17 15:18:54.490  3938  3950 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 15:18:54.491  2858  2869 D BtGatt.GattService: start scan with filters
08-17 15:18:54.494  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:18:54.494  2858  2928 D BtGatt.ScanManager: handling starting scan
08-17 15:18:54.494  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:18:54.494  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:18:54.494  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 15:18:54.495  2858  2928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
08-17 15:18:54.496  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:18:54.496  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:18:54.497  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:18:54.498  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:18:54.501  3938  3988 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:18:54.502  2858  2906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 15:18:54.502  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:18:54.503  2858  2928 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 15:18:54.508  2858  2906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:18:54.508  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:18:54.509  2858  2928 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:18:54.509  2858  2928 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 15:18:54.518  2858  2906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 15:18:54.518  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:18:54.524  2858  2906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:18:54.524  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:18:54.998  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 15:18:54.998  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 15:18:54.999  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:18:56.047  2858  2858 D BtGatt.ScanManager: awakened up at time 144745
,08-17 15:18:56.080  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:18:56.105  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-17 15:18:56.105  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:18:56.105  2858  2906 D BtGatt.GattService: current time is 144803565734
,08-17 15:18:56.106  2858  2906 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -75, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-17 15:18:56.108  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-17 15:18:56.109  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-17 15:18:56.109  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-17 15:18:56.110  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-17 15:18:56.110  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-17 15:18:56.290  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:18:56.306  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:18:56.309  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:18:56.358  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 15:18:56.358  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 15:18:56.358  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:18:56.358  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:18:56.397  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 15:18:56.397  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 15:18:56.398  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 15:18:56.574  1460  1460 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,08-17 15:18:57.610  2858  2858 D BtGatt.ScanManager: awakened up at time 146308
,08-17 15:18:57.614  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:18:57.622  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 15:18:57.623  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:18:59.124  2858  2858 D BtGatt.ScanManager: awakened up at time 147822
,08-17 15:18:59.128  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:18:59.138  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 15:18:59.139  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:18:59.511  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:18:59.512  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:18:59.512  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:18:59.512  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:59.513  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 15:18:59.513  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:18:59.513  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:18:59.514  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:18:59.514  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 15:18:59.516  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 15:18:59.516  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:18:59.518  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:18:59.520  2858  3079 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:18:59.523  2858  2911 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 15:18:59.525  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:18:59.525  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 15:18:59.525  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:18:59.526  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:18:59.526  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:18:59.530  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:18:59.531  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:18:59.531  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 15:18:59.532  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:18:59.534  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:18:59.538  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:18:59.538  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:18:59.538  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:18:59.538  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:18:59.539  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:18:59.539  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:18:59.539  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:18:59.539  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:18:59.540  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:18:59.540  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:18:59.540  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:18:59.546  2858  2906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 15:18:59.546  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:18:59.547  2858  2928 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:18:59.559  2858  2906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 15:18:59.560  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:18:59.560  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:18:59.576  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-17 15:18:59.576  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:18:59.576  2858  2906 D BtGatt.GattService: current time is 148274237904
,08-17 15:18:59.577  2858  2906 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -95, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-17 15:18:59.577  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-17 15:19:00.040  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:19:04.289   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 15:19:04.300  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-17 15:19:04.306   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 15:19:04.306   874   894 I Adreno  : Build Date                       : 10/20/15
08-17 15:19:04.306   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 15:19:04.306   874   894 I Adreno  : Local Branch                     : M14
08-17 15:19:04.306   874   894 I Adreno  : Remote Branch                    : 
08-17 15:19:04.306   874   894 I Adreno  : Remote Branch                    : 
08-17 15:19:04.306   874   894 I Adreno  : Reconstruct Branch               : 
,08-17 15:19:04.344   280   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (326 us)
,08-17 15:19:04.542  3938  3988 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 15:19:04.549  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:04.558  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:19:04.563  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:19:04.564  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:19:04.564  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 15:19:04.564  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 15:19:04.565  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:19:04.565  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:19:04.565  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:19:04.570  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:04.575  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:19:04.575  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:19:04.577  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:04.585  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:19:04.587  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:19:04.587  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:19:04.596  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:19:04.596  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:19:04.597  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 15:19:04.598  3938  3988 D BluetoothAdapter: STATE_ON
,08-17 15:19:04.603  2858  2871 D BtGatt.GattService: registerClient() - UUID=fe370f04-8fd2-4455-b52b-e61e3324cfec
,08-17 15:19:04.604  2858  2906 D BtGatt.GattService: onClientRegistered() - UUID=fe370f04-8fd2-4455-b52b-e61e3324cfec, clientIf=5
,08-17 15:19:04.605  3938  3949 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 15:19:04.607  2858  3079 D BtGatt.GattService: start scan with filters
,08-17 15:19:04.615  2858  2928 D BtGatt.ScanManager: handling starting scan
,08-17 15:19:04.616  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 15:19:04.617  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:19:04.618  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-17 15:19:04.618  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:19:04.628  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:19:04.628  2858  2906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:19:04.628  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:04.629  2858  2928 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 15:19:04.632  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:19:04.633  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:19:04.639  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:19:04.646  2858  2906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 15:19:04.647  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:04.647  2858  2928 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:19:04.647  2858  2928 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 15:19:04.649  3938  3988 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 15:19:04.655  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:04.656  3938  3988 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:19:04.656  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:04.656  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:19:04.656  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:04.656  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 15:19:04.656  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:19:04.656  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:19:04.656  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:19:04.656  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:19:04.657  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:19:04.657  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:19:04.659  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:19:04.659  2858  3079 D BtGatt.GattService: stopScan() - queue size =1
08-17 15:19:04.660  2858  2871 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 15:19:04.661  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:19:04.661  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 15:19:04.661  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:19:04.661  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:19:04.661  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 15:19:04.662  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:19:04.663  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:19:04.663  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:19:04.663  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:19:04.663  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:19:04.665  2858  2906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 15:19:04.665  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:04.667  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:19:04.667  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:19:04.667  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:19:04.667  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:19:04.667  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:04.667  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:19:04.667  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:04.668  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:04.668  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:04.668  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:04.668  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:04.668  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:04.668  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:04.669  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:04.669  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:19:04.670  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:04.670  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:04.670  3938  3988 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 15:19:04.673  2858  2906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:19:04.673  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:04.676  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:04.681  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:04.681  2858  2906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 15:19:04.681  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:04.682  2858  2928 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:19:04.683  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:04.683  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:19:04.684  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:19:04.684  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:19:04.684  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:19:04.684  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:19:04.684  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:19:04.686  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:04.687  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 15:19:04.687  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:19:04.690  2858  2906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 15:19:04.690  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:04.690  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:19:04.691  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:19:04.692  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 15:19:04.693  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:04.693  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:19:04.697  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 15:19:04.697  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:04.697  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:19:04.697  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:19:04.697  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-17 15:19:04.698  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:19:04.700  2858  2871 D BtGatt.GattService: registerClient() - UUID=2a2c8055-fd57-4638-9a02-b8272dbcc8d4
,08-17 15:19:04.700  2858  2906 D BtGatt.GattService: onClientRegistered() - UUID=2a2c8055-fd57-4638-9a02-b8272dbcc8d4, clientIf=5
,08-17 15:19:04.700  3938  3949 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 15:19:04.701  2858  2869 D BtGatt.GattService: start scan with filters
,08-17 15:19:04.703  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 15:19:04.703  2858  2928 D BtGatt.ScanManager: handling starting scan
08-17 15:19:04.703  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:19:04.703  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:19:04.703  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:19:04.705  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:19:04.705  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:19:04.706  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:19:04.709  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:19:04.710  2858  2906 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 15:19:04.710  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:04.710  2858  2928 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 15:19:04.711  3938  3988 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 15:19:04.715  2858  2906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:19:04.715  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:04.715  2858  2928 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:19:04.715  2858  2928 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 15:19:04.726  2858  2906 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 15:19:04.726  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:04.731  2858  2906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 15:19:04.732  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:04.973  3938  3938 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 15:19:04.974  3938  3938 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 15:19:05.011   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 15:19:05.012  3938  3938 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1216810 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e72a431, 16908290=android.view.AbsSavedState$1@e72a431}, android:focusedViewId=100}]}]
,08-17 15:19:05.012  3938  3938 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-17 15:19:05.014  3938  3938 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 15:19:05.015  3938  3938 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 15:19:05.029   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 15:19:05.032   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-17 15:19:05.033   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 15:19:05.034   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 15:19:05.206  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 15:19:05.206  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:19:05.206  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:19:05.262   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 15:19:05.265   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 15:19:05.271   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-17 15:19:05.276   874   894 I DreamManagerService: Entering dreamland.
,08-17 15:19:05.278   874   894 I PowerManagerService: Dozing...
08-17 15:19:05.280   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 15:19:05.345   374  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 15:19:05.345   374  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 15:19:05.350  2858  2858 D BtGatt.ScanManager: awakened up at time 154047
08-17 15:19:05.351  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:19:05.366   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:19:05.371  1927  4007 D NfcService: Discovery configuration equal, not updating.
08-17 15:19:05.376   874  1307 E native  : do suspend false
,08-17 15:19:05.401   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 15:19:05.403  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-17 15:19:05.403  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:05.404  2858  2906 D BtGatt.GattService: current time is 154101613067
,08-17 15:19:05.404  2858  2906 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -93, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 15:19:05.405  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-17 15:19:05.406  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-17 15:19:05.407  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-17 15:19:05.407  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 15:19:05.408  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 15:19:05.414   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:19:05.417   874  1307 E native  : do suspend true
,08-17 15:19:05.476   374  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 15:19:05.477   374  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 15:19:05.713  1500  2107 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 15:19:05.871   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-17 15:19:06.908  2858  2858 D BtGatt.ScanManager: awakened up at time 155604
,08-17 15:19:06.910  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:19:06.944  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-17 15:19:06.945  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:06.945  2858  2906 D BtGatt.GattService: current time is 155642958684
,08-17 15:19:06.946  2858  2906 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -85, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -94, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 15:19:06.947  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 15:19:06.947  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 15:19:06.948  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-17 15:19:06.949  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-17 15:19:06.950  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 15:19:08.451  2858  2858 D BtGatt.ScanManager: awakened up at time 157148
,08-17 15:19:08.453  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:19:08.465  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 15:19:08.465  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:09.712  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:09.713  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:09.713  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:19:09.713  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:09.714  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-17 15:19:09.714  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:19:09.714  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:19:09.714  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 15:19:09.715  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:19:09.716  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 15:19:09.716  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 15:19:09.718  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:19:09.720  2858  2911 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:19:09.723  2858  3079 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 15:19:09.724  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 15:19:09.724  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 15:19:09.724  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 15:19:09.725  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:19:09.725  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:19:09.729  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:19:09.729  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:19:09.730  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:19:09.731  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:19:09.732  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:19:09.732  2858  2858 D BtGatt.ScanManager: awakened up at time 158429
,08-17 15:19:09.735  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:19:09.736  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:19:09.736  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:19:09.737  2858  2906 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 15:19:09.738  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:19:09.738  2858  2928 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:19:09.746  2858  2906 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:19:09.746  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:09.747  2858  2928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:19:09.772  2858  2906 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-17 15:19:09.772  2858  2906 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:19:09.773  2858  2906 D BtGatt.GattService: current time is 158470609440
08-17 15:19:09.773  2858  2906 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -96, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -90, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 15:19:09.774  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 15:19:09.775  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-17 15:19:09.776  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-17 15:19:09.776  2858  2906 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-17 15:19:10.120  1882  2768 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 15:19:10.237  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:19:10.238  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:10.238  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:19:11.269  3246  4012 V KeepSync: Connecting to GoogleApiClient
08-17 15:19:11.270   874  1984 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 15:19:11.343  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:11.349  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:11.423  1500  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 15:19:11.423  1500  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-17 15:19:11.423  1500  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:19:11.423  1500  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:11.450  1713  4013 V BaseAuthAsyncOperation: access token request failed
,08-17 15:19:11.451  3246  4012 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 15:19:11.519  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-17 15:19:11.519  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 15:19:11.519  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:19:11.520  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:11.546  3246  4012 E KeepSync: IOException
08-17 15:19:11.546  3246  4012 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 15:19:11.546  3246  4012 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:19:11.546  3246  4012 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 15:19:11.546  3246  4012 E KeepSync: 	... 10 more
08-17 15:19:11.546  3246  4012 W KeepSync: Sync result 2
,08-17 15:19:11.558   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130601, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:19:14.737  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:14.738  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:14.738  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:14.738  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.739  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:14.739  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:19:14.740  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.740  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.740  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.741  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:14.741  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.743  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.743  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.746  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.747  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.747  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:14.747  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:14.750  3938  3988 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 15:19:14.752  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:14.752  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:14.752  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:14.753  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.754  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.754  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.754  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.755  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:14.755  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.755  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:14.756  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.756  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.756  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.757  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.759  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.759  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.759  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.759  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:14.761  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:19:14.762  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:14.762  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:14.762  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:14.763  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.763  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:14.763  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.764  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.764  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.764  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.764  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:14.764  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.764  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.765  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.765  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.767  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:19:14.767  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.767  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.767  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:14.769  3938  3988 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-17 15:19:14.769  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:14.769  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:14.770  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:14.770  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.770  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.771  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.771  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.771  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.771  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.771  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:14.771  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.772  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.772  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.772  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.774  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.774  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:19:14.774  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.775  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:14.776  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-17 15:19:14.776  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:14.776  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:14.776  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:14.777  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.777  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:14.777  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.777  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:14.777  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.777  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:14.777  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:14.777  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:14.777  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.778  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.778  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.779  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.779  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-17 15:19:14.779  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.779  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:14.780  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 15:19:14.780  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:19:14.780  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:19:14.780  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 15:19:14.780  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:19:14.780  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:19:14.780  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 15:19:14.781  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:19:14.781  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:19:14.781  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:14.781  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:14.781  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:14.781  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.781  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.782  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.782  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:14.782  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.782  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.782  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:14.782  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.782  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.782  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.782  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.784  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.784  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.784  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:14.784  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.785  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:19:14.785  3938  3988 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-17 15:19:14.785  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:19:14.789  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:19:14.789  3938  3988 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-17 15:19:14.790  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 15:19:14.791  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:19:14.792  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-17 15:19:14.792  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 15:19:14.793  3938  3988 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:19:14.793  3938  3988 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-17 15:19:14.793  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 15:19:14.793  3938  3988 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:19:14.793  3938  3988 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
08-17 15:19:14.793  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:19:14.793  3938  3988 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 15:19:14.793  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 15:19:14.797  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-17 15:19:14.798  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 15:19:14.798  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 15:19:14.799  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-17 15:19:14.799  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-17 15:19:14.800  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-17 15:19:14.800  3938  3988 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:19:14.801  3938  3988 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 15:19:14.802  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:14.802  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:14.802  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:14.803  3938  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
,08-17 15:19:14.805  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.805  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.805  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.815  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-17 15:19:14.818  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.818  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.818  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.818  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:14.818  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.818  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.818  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.818  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.820  3938  4014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:19:14.821  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.821  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.821  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:14.821  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.822  3938  3988 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 15:19:14.823  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:14.823  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:14.823  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:14.824  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.824  3938  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
08-17 15:19:14.824  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.824  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.824  3938  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 426)
,08-17 15:19:14.824  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.824  3938  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 426)
08-17 15:19:14.824  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.824  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.824  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:14.824  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:14.824  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.824  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.825  3938  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
08-17 15:19:14.825  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.828  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:19:14.828  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.828  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.828  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.829  3938  3988 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 15:19:14.829  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:14.829  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:14.829  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:14.830  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.830  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.830  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.830  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:14.830  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.830  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.830  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:14.830  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.830  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.830  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:14.830  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.832  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.832  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:14.832  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.832  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.833  3938  3988 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-17 15:19:14.833  3938  3988 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 15:19:14.833  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:19:14.834  3938  3988 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 15:19:14.834  3938  3988 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:19:14.834  3938  3988 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 15:19:14.834  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:19:14.834  3938  3988 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-17 15:19:14.834  3938  3988 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:19:14.834  3938  3988 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:19:14.834  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:19:14.834  3938  3988 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 15:19:14.835  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:14.835  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:14.835  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:14.835  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.835  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.835  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.835  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:14.835  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.836  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.836  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:14.836  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.836  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.836  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.836  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.837  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:14.837  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:19:14.837  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.837  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.838  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:14.838  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.838  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:14.838  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:14.838  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:14.838  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:14.838  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:14.838  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:14.838  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:14.892   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-17 15:19:14.895  2858  3064 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,08-17 15:19:16.585  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:16.789  1500  4017 I VacuumService: Vacuum at: now=1471439956789 tag=VacuumService
,08-17 15:19:16.864  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:16.884  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:16.886  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:16.907  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 15:19:16.908  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 15:19:16.908  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:19:16.908  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:16.942  1500  4018 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-17 15:19:16.944  1500  4018 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 15:19:16.961  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 15:19:16.962  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 15:19:16.962  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-17 15:19:19.839  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:19.840  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:19.840  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:19.840  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.841  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.841  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:19.841  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:19.842  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:19.842  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:19.843  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:19:19.843  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.844  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.844  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:19.844  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:19.845  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:19.845  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:19.845  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.846  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.846  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.846  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.850  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:19.850  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:19.850  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:19.851  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:19.856  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 15:19:19.857  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:19:19.859  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 15:19:19.861  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-17 15:19:19.861  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-17 15:19:19.862  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-17 15:19:19.863  3938  3938 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 15:19:19.863  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 15:19:19.863  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:19.864  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-17 15:19:19.864  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 15:19:19.864  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-17 15:19:19.865  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.865  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-17 15:19:19.865  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:19.865  3938  3938 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-17 15:19:19.865  3938  4024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:19:19.866  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:19.866  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:19:19.866  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:19:19.866  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 15:19:19.867  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.867  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.868  3938  4024 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 15:19:19.869  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:19:19.869  3938  4024 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 15:19:19.869  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:19.869  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:19.869  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:19:19.869  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:19.870  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:19.870  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:19.870  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:19:19.870  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.870  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.870  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:19.870  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:19.870  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:19:19.870  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:19.870  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:19.870  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.870  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.870  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.870  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.871  3938  4024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 15:19:19.872  3938  3938 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 15:19:19.873  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:19:19.873  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:19:19.873  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:19.873  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:19.876  3938  3988 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-17 15:19:19.877  3938  3988 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 15:19:19.877  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:19:19.879  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:19:19.879  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:19:19.879  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:19.879  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:19.879  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:19.879  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:19:19.879  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.879  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.880  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:19.880  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:19.880  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:19.880  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:19.880  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.880  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.880  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.880  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.882  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:19:19.883  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:19.883  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 15:19:19.883  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
,08-17 15:19:19.888  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:19:19.888  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:19:19.889  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:19:19.889  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:19:19.889  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.889  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:19.889  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
,08-17 15:19:19.889  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:19.889  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:19.889  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:19.889  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.889  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.889  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.889  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.891  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:19.891  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:19.891  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:19.891  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:19.892  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:19:19.892  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:19:19.892  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:19:19.892  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:19:19.892  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.892  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.892  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@854c7a7 not in the list
08-17 15:19:19.892  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:19.893  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:19.893  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:19.893  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:19.893  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.893  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:19.893  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:19.894  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:19:19.894  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:19:19.894  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:19.894  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3181454 not in the list
08-17 15:19:19.896  3938  3988 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 15:19:19.896  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:19:19.896  3938  3988 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 15:19:19.896  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:19:19.896  3938  3988 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-17 15:19:19.896  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:19:19.899  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:19:19.899  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 15:19:19.900  3938  3988 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 15:19:19.900  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:19:19.900  3938  3988 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-17 15:19:19.900  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:19:19.900  3938  3988 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 15:19:19.901  3938  3988 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 15:19:19.901  3938  3988 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 15:19:19.901  3938  3988 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 15:19:19.902  3938  3988 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-17 15:19:19.902  3938  3988 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 15:19:19.902  3938  3988 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 15:19:19.902  3938  3988 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 15:19:19.903  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:19:19.903  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8e897 added. We now have 3 listener(s)
,08-17 15:19:19.904  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:19:19.906  3938  3988 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 15:19:19.906   874  1685 D WifiService: setWifiEnabled: true pid=3938, uid=10000
08-17 15:19:19.906   874  1685 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:19:19.949  2858  3041 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-17 15:19:19.949  2858  3041 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-17 15:19:20.371  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:19:22.020   874  2084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 15:19:22.333  1500  4018 W Uploader:  no longer exists, so no auth token.
,08-17 15:19:23.178  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:23.180  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:23.218  1500  4018 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-17 15:19:23.219  1500  4018 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 15:19:23.219  1500  4018 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:19:23.219  1500  4018 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:23.239  1500  4018 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 15:19:23.239  1500  4018 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 15:19:23.239  1500  4018 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 15:19:23.565  1500  4018 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 15:19:23.565  1500  4018 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 15:19:23.565  1500  4018 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:19:23.566  1500  4018 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:23.588  1500  4018 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 15:19:23.588  1500  4018 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 15:19:23.588  1500  4018 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 15:19:24.164  1500  4018 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 15:19:24.164  1500  4018 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 15:19:24.164  1500  4018 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:19:24.164  1500  4018 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:24.184  1500  4018 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 15:19:24.184  1500  4018 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 15:19:24.184  1500  4018 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 15:19:24.913  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:19:24.914  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a933a84 added. We now have 4 listener(s)
,08-17 15:19:24.914  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:19:24.924  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:24.924  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a933a84 removed from the list
08-17 15:19:24.924  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:24.924  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:24.924  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:19:24.925  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:19:24.925  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29c526d added. We now have 4 listener(s)
08-17 15:19:24.925  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:19:24.927  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:24.928  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29c526d removed from the list
,08-17 15:19:24.928  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:24.928  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:24.929  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:24.930  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:19:24.931  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afa7ea2 added. We now have 4 listener(s)
,08-17 15:19:24.931  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:19:24.935   874  1983 D WifiService: setWifiEnabled: false pid=3938, uid=10000
,08-17 15:19:24.935   874  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:19:24.946  2858  2902 D BluetoothAdapterState: Current state: ON, message: 23
08-17 15:19:24.946  2858  2902 D BluetoothAdapterProperties: Setting state to 13
08-17 15:19:24.946  2858  2902 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 15:19:24.946  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:19:24.947  2858  2902 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 15:19:24.948  2858  2902 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:19:24.956  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 15:19:24.958  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:24.958  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:24.959  2858  2858 D BluetoothMapService: onReceive
,08-17 15:19:24.959  2858  2858 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:19:24.959  2858  2858 D BluetoothMapService: STATE_TURNING_OFF
,08-17 15:19:24.959  2858  2858 D BluetoothMapService: MAP Service closeService in
,08-17 15:19:24.959  2858  2858 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 15:19:24.959  2858  2858 D ObexServerSockets0: shutdown(block = true)
08-17 15:19:24.960  2858  2858 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 15:19:24.960  2858  2858 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 15:19:24.961  2858  3080 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 15:19:24.961  2858  3064 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 15:19:24.962  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:24.963  2858  3081 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-17 15:19:24.963  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:24.963  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:19:24.965  2858  2906 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:19:24.965  2858  2858 I BtOppRfcommListener: stopping Accept Thread
08-17 15:19:24.965  2858  2902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 15:19:24.966  2858  3639 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 15:19:24.967  2858  3639 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:19:24.967  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:24.970   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 15:19:24.970   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 15:19:24.970   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:19:24.970   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:19:24.973  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:24.977  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:24.977  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:24.978  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:24.979  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:24.979   874   887 I ActivityManager: Start proc 4037:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-17 15:19:24.985  2858  2858 D HeadsetService: Received stop request...Stopping profile...
08-17 15:19:24.987   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:24.987   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:24.987  1365  2074 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:24.987  1365  1365 D HeadsetProfile: Bluetooth service disconnected
,08-17 15:19:24.988   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:24.988   874  1307 E native  : do suspend true
08-17 15:19:24.988  1943  1958 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:24.988  2858  2858 D A2dpService: Received stop request...Stopping profile...
08-17 15:19:24.989  2858  3072 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:19:24.990  1365  1365 D BluetoothA2dp: Proxy object disconnected
,08-17 15:19:24.991   874   874 D BluetoothA2dp: Proxy object disconnected
08-17 15:19:24.992  2858  2858 D HidService: Received stop request...Stopping profile...
08-17 15:19:24.992  2858  2858 D HidService: Stopping Bluetooth HidService
08-17 15:19:24.992  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:24.992  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:24.993  1365  1365 D BluetoothInputDevice: Proxy object disconnected
,08-17 15:19:24.993  1365  1365 D HidProfile: Bluetooth service disconnected
,08-17 15:19:24.993  2858  2858 V BluetoothAdapterState: isTurningOff()=true
,08-17 15:19:24.993  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:24.993  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:19:24.993  2858  2858 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:24.993  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:24.993  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:19:24.996  2858  2858 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:19:24.996  2858  2858 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:19:24.996  2858  2906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 15:19:24.997  2858  2858 D HealthService: Received stop request...Stopping profile...
08-17 15:19:24.997  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:24.997  2858  3041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 15:19:24.997  2858  3041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:24.997  2858  3041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:24.998  2858  2906 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-17 15:19:24.999  2858  2858 D PanService: Received stop request...Stopping profile...
08-17 15:19:25.000  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:19:25.000  2858  2858 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:25.000  1365  1365 D PanProfile: Bluetooth service disconnected
08-17 15:19:25.000  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:25.001  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:19:25.001  2858  2858 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:25.002  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:25.002  2858  2906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-17 15:19:25.002  2858  3041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 15:19:25.002  2858  3041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 15:19:25.003  2858  3041 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:19:25.003  2858  3041 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 15:19:25.003  2858  3041 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:19:25.003   874  2085 D DhcpClient: Clearing IP address
08-17 15:19:25.003  2858  3041 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:19:25.004   370   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:19:25.006  2858  2858 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 15:19:25.006  2858  2858 D BluetoothMapService: stop()
08-17 15:19:25.007  2858  2858 D BluetoothMapAppObserver: deinitObservers()
08-17 15:19:25.007  2858  2858 D BluetoothMapAppObserver: removeReceiver()
08-17 15:19:25.007  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:25.007   370   872 D CommandListener: Setting iface cfg
,08-17 15:19:25.014   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 15:19:25.017   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 15:19:25.018   394   394 E Parcel  : Reading a NULL string not supported here.
08-17 15:19:25.019  1500  2525 V NativeCrypto: Read error: ssl=0xaedb5e00: I/O error during system call, Connection timed out
08-17 15:19:25.021   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-17 15:19:25.021   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:19:25.021   874  1307 E native  : do suspend true
08-17 15:19:25.022  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:25.022  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:25.023  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.023  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:25.025  1365  1365 D BluetoothMap: Proxy object disconnected
08-17 15:19:25.025  1365  1365 D MapProfile: Bluetooth service disconnected
08-17 15:19:25.025  1500  2525 V NativeCrypto: SSL shutdown failed: ssl=0xaedb5e00: I/O error during system call, Broken pipe
08-17 15:19:25.025  2858  2858 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:25.025  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:25.025  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:25.025  2858  2858 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:25.025  2858  2858 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:19:25.026  2858  2858 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:19:25.026  2858  2858 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:25.026  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:25.026  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:25.026  2858  2858 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:25.026  2858  2858 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:19:25.026  2858  2906 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 15:19:25.026  2858  2906 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 15:19:25.027  2858  2858 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:19:25.028  2858  2858 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:25.028  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:25.028  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:25.028  2858  2858 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:25.028  2858  2858 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:19:25.028  2858  2858 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 15:19:25.031   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-17 15:19:25.031  2858  2858 D BluetoothMapService: MAP Service closeService in
08-17 15:19:25.033  2858  2858 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:25.033  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:25.033  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:25.033  2858  2858 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:25.033  2858  2902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 15:19:25.033  2858  2902 D BluetoothAdapterProperties: Setting state to 15
08-17 15:19:25.033  2858  2902 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 15:19:25.035  2858  2902 I BluetoothAdapterState: Entering BleOnState
08-17 15:19:25.035  1365  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 15:19:25.037  2858  2858 D BluetoothMapService: cleanup()
,08-17 15:19:25.037  2858  2858 D BluetoothMapService: MAP Service closeService in
08-17 15:19:25.038   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:19:25.039  1365  1377 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:19:25.039   874  2104 D DhcpClient: Receive thread stopped
08-17 15:19:25.040  1365  2074 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:19:25.040   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:25.040   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:25.040  1365  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:19:25.041   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:25.041  1365  1377 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:19:25.041  1943  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:25.042  1365  2074 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 15:19:25.042  2858  2902 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 15:19:25.042  2858  2902 D BluetoothAdapterProperties: Setting state to 16
08-17 15:19:25.042  2858  2902 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 15:19:25.043  2858  2902 D BluetoothAdapterProperties: onBleDisable
08-17 15:19:25.043  2858  2902 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:19:25.043  2858  2903 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 15:19:25.044  2858  2906 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:19:25.044  2858  3041 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 15:19:25.044  2858  3041 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:25.047  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:25.047  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:25.047  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.048  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:25.049  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:25.049  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:25.049  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.050  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:25.051  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:25.051  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:25.054  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:25.056  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:25.057  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:25.062   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:19:25.065  4037  4037 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 15:19:25.075  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:19:25.079   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:19:25.080   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-17 15:19:25.080   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:19:25.080   370   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:19:25.081  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:19:25.083   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:19:25.088  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:25.088   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 15:19:25.089  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:25.090  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:25.092  3574  3574 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4f1cfce and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 15:19:25.099   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32c8d3:true
,08-17 15:19:25.103   874  3316 I ActivityManager: Start proc 4055:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 15:19:25.107   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 15:19:25.111   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:19:25.111  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:25.111  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:19:25.111  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.111  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:25.113  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:25.114  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:25.115  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.115  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:25.117  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:25.117  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:25.117  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:25.117  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:25.129  1882  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:19:25.136   370   872 E Netd    : netlink response contains error (No such file or directory)
08-17 15:19:25.137   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 15:19:25.142  4037  4037 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 15:19:25.144  4037  4037 D BluetoothMap: Create BluetoothMap proxy object
,08-17 15:19:25.150  4055  4055 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 15:19:25.153  4037  4037 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 15:19:25.166  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:19:25.173   874  1978 I ActivityManager: Killing 3378:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 15:19:25.247  2858  2906 I bt_hci  : shut_down
,08-17 15:19:25.247  2858  2929 D bt_hwcfg: hw_epilog_process
,08-17 15:19:25.259  2858  2929 I bt_vendor: low_power_mode_cb
,08-17 15:19:25.282  2858  2929 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 15:19:25.283  2858  2929 I bt_vendor: epilog_cb
,08-17 15:19:25.283  2858  2929 I bt_hci  : epilog_finished_callback
,08-17 15:19:25.289  2858  2906 I bt_hci_h4: hal_close
,08-17 15:19:25.290  2858  2906 I bt_userial_vendor: device fd = 51 close
,08-17 15:19:25.329  4055  4055 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 15:19:25.329  4055  4055 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 15:19:25.329  4055  4055 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:19:25.329  4055  4055 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 15:19:25.329  405,5  4055 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:19:25.329  4055  4055 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:1,9:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.329  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:19:25.330  4055  4055 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:19:25.330  4055  4055 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:19:25.330  4055  4055 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:19:25.330  4055  4055 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:19:25.335  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 15:19:25.343  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:19:25.352  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:19:25.393   874  1685 I ActivityManager: Killing 3574:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 15:19:25.468  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-17 15:19:25.469  2858  2903 D bt_stack_manager: event_shut_down_stack finished.
,08-17 15:19:25.469  2858  2902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 15:19:25.470  2858  2902 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 15:19:25.470  2858  2858 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:19:25.471  2858  2858 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 15:19:25.471  2858  2858 D BtGatt.GattService: stop()
,08-17 15:19:25.471  2858  2858 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 15:19:25.472  1713  1713 D SystemUpdateService: onCreate
,08-17 15:19:25.473  2858  2858 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:25.473  2858  2858 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:25.473  2858  2858 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:25.473  2858  2858 V BluetoothAdapterState: isBleTurningOff()=true
08-17 15:19:25.473  2858  2902 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 15:19:25.473  2858  2902 D BluetoothAdapterProperties: Setting state to 10
08-17 15:19:25.474  2858  2902 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 15:19:25.474  2858  2902 I BluetoothAdapterState: Entering OffState
08-17 15:19:25.475   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-17 15:19:25.477  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 15:19:25.484  2858  2858 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 15:19:25.484  2858  2858 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 15:19:25.484  2858  2858 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:19:25.485  2858  2903 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 15:19:25.489  2858  2903 D bt_stack_manager: event_clean_up_stack finished.
,08-17 15:19:25.493  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 15:19:25.503  2858  2858 I art     : System.exit called, status: 0
,08-17 15:19:25.503  2858  2858 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 15:19:25.514  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:19:25.496  1713  2503 I iu.UploadsManager: num queued entries: 0
,08-17 15:19:25.517  1713  4088 I SystemUpdateService: active receiver: enabled
,08-17 15:19:25.518  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:19:25.529  1713  2503 I iu.UploadsManager: num updated entries: 0
,08-17 15:19:25.536   874  1965 I ActivityManager: Start proc 4091:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 15:19:25.544  1713  4088 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:19:25.546  1713  2503 I iu.SyncManager: NEXT; no task
,08-17 15:19:25.547  1713  4088 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 15:19:25.547  1713  4088 I SystemUpdateService: now status is 0 (complete)
,08-17 15:19:25.547  1713  4088 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:19:25.547  1713  4088 I SystemUpdateService: file has been verified
,08-17 15:19:25.547  1713  4088 I SystemUpdateService: OTA package size = 12249756
,08-17 15:19:25.556  1713  4088 I SystemUpdateService: showing system update notification
,08-17 15:19:25.566   874  3316 I ActivityManager: Process com.android.bluetooth (pid 2858) has died
,08-17 15:19:25.601  1713  1713 D SystemUpdateService: onDestroy
,08-17 15:19:25.620  4091  4091 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 15:19:25.623  4091  4091 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:19:25.641  4091  4091 D SprintDMHelper: simOperator: 
,08-17 15:19:25.642  4091  4091 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:19:25.661   874  1988 I ActivityManager: Start proc 4105:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 15:19:25.681  4055  4083 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 15:19:25.702   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23d19e9:true
,08-17 15:19:25.787   874  1983 I ActivityManager: Start proc 4120:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 15:19:25.792  2817  4119 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 15:19:25.796   874  1603 I ActivityManager: Killing 3452:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 15:19:25.848  4120  4120 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 15:19:25.905  4120  4120 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 15:19:25.905  4120  4120 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 15:19:25.905  4120  4120 I GAv4    :   adb logcat -s GAv4
,08-17 15:19:25.922  4120  4120 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:19:25.929  4120  4120 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:19:25.961  4120  4137 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:19:26.075  4120  4120 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 15:19:26.122  4120  4120 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 15:19:26.131  4120  4120 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4826-4829)
08-17 15:19:26.131  4120  4120 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 15:19:26.141  4120  4120 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d57c87e}
,08-17 15:19:26.142  4120  4120 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 15:19:26.143  4120  4120 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 15:19:26.152  4120  4120 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 15:19:26.154  4120  4120 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 15:19:26.172  4120  4120 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 15:19:26.188  4120  4120 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 15:19:26.188  4120  4120 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 15:19:26.188  4120  4120 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 15:19:26.188  4120  4120 I Adreno  : Build Date                       : 10/20/15
08-17 15:19:26.188  4120  4120 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 15:19:26.188  4120  4120 I Adreno  : Local Branch                     : M14
08-17 15:19:26.188  4120  4120 I Adreno  : Remote Branch                    : 
08-17 15:19:26.188  4120  4120 I Adreno  : Remote Branch                    : 
08-17 15:19:26.188  4120  4120 I Adreno  : Reconstruct Branch               : 
,08-17 15:19:26.235  4120  4166 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 15:19:26.255  4120  4120 I NSApplication: Starting up...
,08-17 15:19:26.304   874  1983 I ActivityManager: Start proc 4171:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 15:19:26.306   874  1983 I ActivityManager: Killing 3228:android.process.acore/u0a5 (adj 15): empty #17
,08-17 15:19:26.390  4171  4171 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 15:19:26.577   874   885 I ActivityManager: Killing 3793:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 15:19:26.664   874  1965 I ActivityManager: Start proc 4185:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-17 15:19:26.744  4185  4185 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 15:19:26.795  4185  4185 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 15:19:26.845   874  1978 I ActivityManager: Killing 3808:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 15:19:29.966   874  1599 D WifiService: setWifiEnabled: true pid=3938, uid=10000
08-17 15:19:29.966   874  1599 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:19:29.979   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 15:19:29.985  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:29.986  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:29.986  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:29.986  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:29.988  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:29.989  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:19:29.989  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:29.989  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:29.993  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:29.993  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:29.994  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:29.994  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:30.028   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 15:19:30.029   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 15:19:30.030   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 15:19:30.031   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 15:19:30.031   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 15:19:30.031   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 15:19:30.031   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 15:19:30.045   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 15:19:30.046   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 15:19:30.048   370   872 D CommandListener: Setting iface cfg
,08-17 15:19:30.055   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 15:19:30.056   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 15:19:30.056   874  1307 E native  : do suspend true
,08-17 15:19:30.078   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 15:19:30.079   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 15:19:30.079   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:19:30.738   874  1978 I ActivityManager: Killing 3602:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 15:19:31.381   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 15:19:31.447   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.00 rxSuccessRate=7.44 delta 1000 -> 994
,08-17 15:19:31.448   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 15:19:31.449   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:19:31.470   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 15:19:31.519   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 15:19:31.521  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 15:19:31.951  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:19:31.993  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 15:19:31.996  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 15:19:32.004   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:19:32.022   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 15:19:32.023   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:19:32.023   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 15:19:32.052   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:19:32.073   370   872 D CommandListener: Setting iface cfg
08-17 15:19:32.074   874  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 15:19:32.081   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 15:19:32.116   874  4220 D DhcpClient: Receive thread started
,08-17 15:19:32.207   874  1307 E native  : do suspend false
,08-17 15:19:32.227   874  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 15:19:32.241   874  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,08-17 15:19:32.243   874  2085 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,08-17 15:19:32.246   874  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 15:19:32.260   874  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 15:19:32.261   874  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 15:19:32.267   370   872 D CommandListener: Setting iface cfg
,08-17 15:19:32.278   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 15:19:32.279   874  2085 D DhcpClient: Scheduling renewal in 86399s
,08-17 15:19:32.284   874  1307 E native  : do suspend true
,08-17 15:19:32.312   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 15:19:32.316   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 15:19:32.318   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 15:19:32.320   874  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 15:19:32.331   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 15:19:32.402   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 15:19:32.403   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 15:19:32.406   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 15:19:32.410   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
,08-17 15:19:32.415   874  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 15:19:32.435   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 15:19:32.441   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 15:19:32.441   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 15:19:32.441   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 15:19:32.441   874  1309 D ConnectivityService:    accepting network in place of null
,08-17 15:19:32.443   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 15:19:32.442   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 15:19:32.449   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 15:19:32.454   874  4219 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181151, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 15:19:32.495   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:19:32.525   874  4218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:80d::200e
,08-17 15:19:32.530   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:19:32.537   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 15:19:32.537   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:19:32.543   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 15:19:32.547   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:19:32.563  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:32.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:32.563  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:32.563  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:19:32.566  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:32.566  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:32.566  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:32.566  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:19:32.569  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:19:32.569  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:19:32.569  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:32.569  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:19:32.578  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:19:32.585  3890  4231 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 15:19:32.599  1713  1713 D SystemUpdateService: onCreate
,08-17 15:19:32.602  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:19:32.611   874  4218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:19:32 GMT], X-Android-Received-Millis=[1471439972611], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471439972580]}
,08-17 15:19:32.613   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 15:19:32.613   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-17 15:19:32.613   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:19:32.618   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:19:32.629  3890  4236 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 15:19:32.636  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 15:19:32.639  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:32.643  1713  2503 I iu.UploadsManager: num queued entries: 0
,08-17 15:19:32.643  1713  2503 I iu.UploadsManager: num updated entries: 0
,08-17 15:19:32.645  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:32.650  1713  4233 I SystemUpdateService: active receiver: enabled
,08-17 15:19:32.653  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:19:32.660  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:19:32.668  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:19:32.668  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 15:19:32.668  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:19:32.669  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:32.675  4091  4091 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:19:32.683  1713  4237 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 15:19:32.685  4091  4091 D SprintDMHelper: simOperator: 
,08-17 15:19:32.685  4091  4091 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:19:32.713  1713  4237 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 15:19:32.717  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:32.727  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:32.729  1713  4237 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 15:19:32.761  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:19:32.761  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 15:19:32.761  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:19:32.761  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:32.780  3890  4236 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,08-17 15:19:32.781  3890  4231 E BooksSync: Soft error
08-17 15:19:32.781  3890  4231 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 15:19:32.781  3890  4231 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 15:19:32.781  3890  4231 E BooksSync: Sync error
08-17 15:19:32.781  3890  4231 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 15:19:32.781  3890  4231 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 15:19:32.781  3890  4231 I BooksSync: Finished books sync
,08-17 15:19:32.787  1713  2503 I iu.SyncManager: NEXT; no task
,08-17 15:19:32.786  1713  4233 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-17 15:19:32.790   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161884, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:19:32.808  1713  4233 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 15:19:32.808  1713  4233 I SystemUpdateService: now status is 0 (complete)
08-17 15:19:32.808  1713  4233 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:19:32.808  1713  4233 I SystemUpdateService: file has been verified
08-17 15:19:32.808  1713  4233 I SystemUpdateService: OTA package size = 12249756
,08-17 15:19:32.815  1713  4233 I SystemUpdateService: showing system update notification
,08-17 15:19:32.829  1500  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 15:19:32.829  1500  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 15:19:32.829  1500  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:19:32.829  1500  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:32.838  1713  1713 D SystemUpdateService: onDestroy
,08-17 15:19:32.854  1713  4237 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-17 15:19:32.859  2817  4240 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 15:19:33.536   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 15:19:34.973   874   884 D WifiService: setWifiEnabled: false pid=3938, uid=10000
,08-17 15:19:34.973   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:19:35.009  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 15:19:35.016   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 15:19:35.016   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 15:19:35.016   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 15:19:35.017   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:19:35.038   874  1307 E native  : do suspend true
,08-17 15:19:35.059   874  2085 D DhcpClient: Clearing IP address
,08-17 15:19:35.060   370   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:19:35.071  1500  4244 V NativeCrypto: Read error: ssl=0x9b736000: I/O error during system call, Connection timed out
,08-17 15:19:35.077  1500  4244 V NativeCrypto: SSL shutdown failed: ssl=0x9b736000: I/O error during system call, Broken pipe
,08-17 15:19:35.082   370   872 D CommandListener: Setting iface cfg
,08-17 15:19:35.087   874  4220 D DhcpClient: Receive thread stopped,
,08-17 15:19:35.097   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 15:19:35.097   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 15:19:35.100   394   394 E Parcel  : Reading a NULL string not supported here.
,08-17 15:19:35.103   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-17 15:19:35.104   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:19:35.104   874  1307 E native  : do suspend true
08-17 15:19:35.107   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-17 15:19:35.140   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:19:35.171   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:19:35.172   370   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:19:35.175   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true,
,08-17 15:19:35.176   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:19:35.177   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 15:19:35.186   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:19:35.200  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:35.200  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:35.200  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.200  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:35.204  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:35.204  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:35.204  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.204  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:35.205  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:35.205  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:35.205  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.205  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:35.206   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:19:35.209  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:35.209  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:35.209  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.209  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:35.210  1882  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:19:35.210  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:35.210  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:35.210  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.210  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:35.211   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:19:35.211  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:35.211  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:19:35.212  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:35.212  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:19:35.218  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:19:35.226  1713  1713 D SystemUpdateService: onCreate
,08-17 15:19:35.230  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:19:35.240  1713  4254 I SystemUpdateService: active receiver: enabled
,08-17 15:19:35.241  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 15:19:35.247  1713  2503 I iu.UploadsManager: num queued entries: 0
,08-17 15:19:35.247  1713  2503 I iu.UploadsManager: num updated entries: 0
,08-17 15:19:35.248  1713  2503 I iu.SyncManager: NEXT; no task
08-17 15:19:35.249  1713  4254 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:19:35.250  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:19:35.251  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:19:35.253  4091  4091 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:19:35.254  1713  4254 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 15:19:35.255  1713  4254 I SystemUpdateService: now status is 0 (complete)
08-17 15:19:35.255  1713  4254 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 15:19:35.255  1713  4254 I SystemUpdateService: file has been verified
08-17 15:19:35.255  1713  4254 I SystemUpdateService: OTA package size = 12249756
,08-17 15:19:35.258  4091  4091 D SprintDMHelper: simOperator: 
,08-17 15:19:35.258  4091  4091 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:19:35.275  2817  4259 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 15:19:35.283   370   872 E Netd    : netlink response contains error (No such file or directory)
,08-17 15:19:35.285   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 15:19:35.293  1713  4254 I SystemUpdateService: showing system update notification
,08-17 15:19:35.312  1713  1713 D SystemUpdateService: onDestroy
,08-17 15:19:40.031   874   891 I ActivityManager: Start proc 4263:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 15:19:40.189  4263  4263 D AdapterServiceConfig: Adding HeadsetService
08-17 15:19:40.190  4263  4263 D AdapterServiceConfig: Adding A2dpService
08-17 15:19:40.190  4263  4263 D AdapterServiceConfig: Adding HidService
,08-17 15:19:40.190  4263  4263 D AdapterServiceConfig: Adding HealthService
,08-17 15:19:40.191  4263  4263 D AdapterServiceConfig: Adding PanService
08-17 15:19:40.191  4263  4263 D AdapterServiceConfig: Adding GattService
08-17 15:19:40.191  4263  4263 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 15:19:40.203   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9c6b99f:true
,08-17 15:19:40.203  4263  4263 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 15:19:40.207  4263  4263 I bt_bluedroid: init
,08-17 15:19:40.207  4263  4275 I BluetoothAdapterState: Entering OffState
,08-17 15:19:40.209  4263  4276 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 15:19:40.210  4263  4276 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:19:40.210  4263  4276 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 15:19:40.210  4263  4276 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 15:19:40.210  4263  4263 I bt_bluedroid: get_profile_interface socket
,08-17 15:19:40.212  4263  4279 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:19:40.213  4263  4263 I bt_bluedroid: get_profile_interface sdp
08-17 15:19:40.215  4263  4279 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:19:40.217  4263  4274 I bt_bluedroid: config_hci_snoop_log
,08-17 15:19:40.218   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 15:19:40.221  4263  4275 D BluetoothAdapterState: Current state: OFF, message: 0
08-17 15:19:40.221  4263  4275 D BluetoothAdapterProperties: Setting state to 14
08-17 15:19:40.221  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 15:19:40.223  4263  4275 D BluetoothBondStateMachine: make
,08-17 15:19:40.225  4263  4280 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 15:19:40.227  4263  4275 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:19:40.229  4263  4263 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 15:19:40.233  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:40.233  4263  4263 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:19:40.234  4263  4263 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:19:40.234  4263  4263 D BtGatt.GattService: start()
08-17 15:19:40.234  4263  4263 I bt_bluedroid: get_profile_interface gatt
,08-17 15:19:40.235  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:40.236  4263  4263 D BtGatt.AdvertiseManager: advertise manager created
,08-17 15:19:40.241  4263  4263 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:19:40.241  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:40.242  4263  4263 V BluetoothAdapterState: isBleTurningOn()=true
08-17 15:19:40.242  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:40.243  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 15:19:40.243  4263  4275 I bt_bluedroid: enable
,08-17 15:19:40.243  4263  4276 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 15:19:40.244  4263  4276 I bt_hci  : start_up
,08-17 15:19:40.250  4263  4276 I bt_vendor: alloc value 0xb3a81189
,08-17 15:19:40.250  4263  4276 I bt_vendor: init
08-17 15:19:40.250  4263  4276 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 15:19:40.250  4263  4276 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 15:19:40.356  4263  4276 D bt_hci  : start_up starting async portion
,08-17 15:19:40.357  4263  4283 I bt_hci  : event_finish_startup
,08-17 15:19:40.358  4263  4283 I bt_hci_h4: hal_open
08-17 15:19:40.358  4263  4283 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 15:19:40.370  4263  4283 I bt_userial_vendor: device fd = 51 open
,08-17 15:19:40.399  4263  4283 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 15:19:40.431  4263  4283 D bt_hwcfg: Chipset BCM4354A2
,08-17 15:19:40.432  4263  4283 D bt_hwcfg: Target name = [BCM4354A2]
08-17 15:19:40.433  4263  4283 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 15:19:40.447   874  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-17 15:19:41.095  4263  4283 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 15:19:41.097  4263  4283 D bt_hwcfg: Settlement delay -- 100 ms
08-17 15:19:41.097  4263  4283 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 15:19:41.214  4263  4283 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-17 15:19:41.215  4263  4283 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 15:19:41.244  4263  4283 I bt_hwcfg: vendor lib fwcfg completed
,08-17 15:19:41.245  4263  4283 I bt_vendor: firmware callback
,08-17 15:19:41.245  4263  4283 I bt_hci  : firmware_config_callback
,08-17 15:19:41.256  4263  4285 I bt_btu  : btu_task pending for preload complete event
,08-17 15:19:41.257  4263  4285 I bt_btu_task: Bluetooth chip preload is complete
,08-17 15:19:41.257  4263  4285 I bt_btu  : btu_task received preload complete event
,08-17 15:19:41.267  4263  4285 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 15:19:41.267  4263  4285 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 15:19:41.268  4263  4285 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 15:19:41.268  4263  4285 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:19:41.268  4263  4285 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 15:19:41.268  4263  4285 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:19:41.269  4263  4285 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 15:19:41.269  4263  4285 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:19:41.269  4263  4285 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:19:41.270  4263  4285 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:19:41.270  4263  4285 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:19:41.270  4263  4285 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:19:41.271  4263  4285 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:19:41.271  4263  4285 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:19:41.271  4263  4285 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:19:41.404  4263  4285 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fed9d
,08-17 15:19:41.404  4263  4285 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fed9d 
,08-17 15:19:41.434  4263  4279 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 15:19:41.436  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 15:19:41.437  4263  4279 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:19:41.438  4263  4279 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:19:41.440  4263  4279 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:19:41.440  4263  4279 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:19:41.440  4263  4279 D bt_hci  : do_postload posting postload work item
,08-17 15:19:41.440  4263  4283 I bt_hci  : event_postload
,08-17 15:19:41.440  4263  4283 I bt_vendor: sco_config_cb
,08-17 15:19:41.441  4263  4283 I bt_hci  : sco_config_callback postload finished.
,08-17 15:19:41.443  4263  4279 D bt_bte_conf: Device ID record 1 : primary
,08-17 15:19:41.443  4263  4279 D bt_bte_conf:   vendorId            = 000f
,08-17 15:19:41.444  4263  4279 D bt_bte_conf:   vendorIdSource      = 0001
,08-17 15:19:41.444  4263  4279 D bt_bte_conf:   product             = 1200
,08-17 15:19:41.444  4263  4279 D bt_bte_conf:   version             = 1436
,08-17 15:19:41.444  4263  4279 D bt_bte_conf:   clientExecutableURL = 
,08-17 15:19:41.445  4263  4279 D bt_bte_conf:   serviceDescription  = 
,08-17 15:19:41.445  4263  4279 D bt_bte_conf:   documentationURL    = 
,08-17 15:19:41.445  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:41.445  4263  4279 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 15:19:41.446  4263  4276 D bt_stack_manager: event_start_up_stack finished
08-17 15:19:41.447  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 15:19:41.448  4263  4275 D BluetoothAdapterProperties: Setting state to 15
08-17 15:19:41.448  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 15:19:41.448  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:41.449  4263  4275 I BluetoothAdapterState: Entering BleOnState
08-17 15:19:41.450  4263  4283 I bt_vendor: low_power_mode_cb
08-17 15:19:41.452  4263  4275 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 15:19:41.453  4263  4275 D BluetoothAdapterProperties: Setting state to 11
08-17 15:19:41.453  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 15:19:41.454  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:41.465  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:41.470  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:41.473  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
08-17 15:19:41.473  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:41.474  4263  4263 D HeadsetService: Received start request. Starting profile...
,08-17 15:19:41.477  4263  4263 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:19:41.477  4263  4263 D HeadsetStateMachine: make
,08-17 15:19:41.483  4263  4275 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:19:41.488  4263  4263 D HeadsetStateMachine: max_hf_connections = 1
,08-17 15:19:41.488  4263  4263 I bt_bluedroid: get_profile_interface handsfree
08-17 15:19:41.489  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 15:19:41.489  4263  4279 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-17 15:19:41.494  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:19:41.494  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
08-17 15:19:41.495  4263  4263 D A2dpService: Received start request. Starting profile...
,08-17 15:19:41.495  4263  4263 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 15:19:41.496  4263  4263 I bt_bluedroid: get_profile_interface avrcp
,08-17 15:19:41.503  4263  4263 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 15:19:41.503  4263  4263 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:19:41.503  4263  4263 D A2dpStateMachine: make
,08-17 15:19:41.505  4263  4263 I bt_bluedroid: get_profile_interface a2dp
,08-17 15:19:41.507  4263  4294 D A2dpStateMachine: Enter Disconnected: -2
,08-17 15:19:41.508  4263  4263 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 15:19:41.506  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 15:19:41.509  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:41.511  4263  4263 D HidService: Received start request. Starting profile...
,08-17 15:19:41.511  4037  4037 D BluetoothInputDevice: Proxy object connected
08-17 15:19:41.511  4263  4263 I bt_bluedroid: get_profile_interface hidhost
,08-17 15:19:41.511  4263  4279 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e03e5
,08-17 15:19:41.512  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 15:19:41.512  4263  4263 D HidService: setHidService(): set to: null
08-17 15:19:41.512  4037  4037 D HidProfile: Bluetooth service connected
08-17 15:19:41.512  4263  4263 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:19:41.513  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:41.514  4263  4263 D HealthService: Received start request. Starting profile...
,08-17 15:19:41.516  4263  4263 I bt_bluedroid: get_profile_interface health
,08-17 15:19:41.516  4263  4263 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:19:41.517  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:41.519  4263  4263 D PanService: Received start request. Starting profile...
08-17 15:19:41.519  4037  4037 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:19:41.519  4263  4263 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:19:41.519  4263  4263 I bt_bluedroid: get_profile_interface pan
08-17 15:19:41.520  4263  4279 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 15:19:41.520  4037  4037 D PanProfile: Bluetooth service connected
,08-17 15:19:41.522  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:41.524  4263  4263 D BluetoothMapService: Received start request. Starting profile...
08-17 15:19:41.524  4037  4037 D BluetoothMap: Proxy object connected
08-17 15:19:41.524  4263  4263 D BluetoothMapService: start()
08-17 15:19:41.524  4037  4037 D MapProfile: Bluetooth service connected
08-17 15:19:41.524  4037  4037 D BluetoothMap: getConnectedDevices()
08-17 15:19:41.525  4037  4037 D BluetoothMap: Bluetooth is Not enabled
,08-17 15:19:41.526  4263  4263 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 15:19:41.527  4263  4263 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-17 15:19:41.527  4263  4263 D BluetoothMapAppObserver: createReceiver()
,08-17 15:19:41.528  4263  4263 D BluetoothMapAppObserver: initObservers()
,08-17 15:19:41.528  4263  4263 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 15:19:41.536  4263  4263 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:19:41.536  4263  4263 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:41.536  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:41.536  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:41.539  4263  4292 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 15:19:41.542  4263  4263 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:19:41.542  4263  4263 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:19:41.542  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:19:41.542  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:41.542  4263  4263 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:41.542  4263  4263 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:41.543  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:41.544  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:41.544  4263  4263 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:41.544  4263  4263 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:41.544  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:41.544  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:41.544  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 15:19:41.544  4263  4275 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:19:41.545  4263  4275 D BluetoothAdapterProperties: State =  11
,08-17 15:19:41.546  4263  4279 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:19:41.546  4263  4279 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:19:41.546  4263  4275 D BluetoothAdapterProperties: Setting state to 12
08-17 15:19:41.546  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 15:19:41.548  4037  4048 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 15:19:41.548  4263  4275 I BluetoothAdapterState: Entering OnState
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:41.550  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:41.551  1365  1378 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:19:41.553  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:41.553   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:19:41.554  1365  2074 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:41.556  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:19:41.555  4263  4263 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:19:41.557  1365  1365 D BluetoothMap: Proxy object connected
,08-17 15:19:41.558  1365  1365 D MapProfile: Bluetooth service connected
08-17 15:19:41.558  1365  1365 D BluetoothMap: getConnectedDevices()
08-17 15:19:41.558  1365  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:19:41.559  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:41.559  4263  4263 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-17 15:19:41.561  1365  1365 D BluetoothInputDevice: Proxy object connected
08-17 15:19:41.561  1365  1365 D HidProfile: Bluetooth service connected
08-17 15:19:41.561   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:41.562   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:41.562  1365  2074 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:41.563  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:41.564  4263  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:19:41.564  4037  4047 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 15:19:41.564  4037  4048 D BluetoothMap: onBluetoothStateChange: up=true
08-17 15:19:41.565   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:41.565  4037  4047 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:19:41.565  1365  1377 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:19:41.565  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:41.567  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:19:41.567  1365  1365 D PanProfile: Bluetooth service connected
,08-17 15:19:41.567  4263  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:19:41.567  1943  2125 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:41.568  4263  4263 D ObexServerSockets: Succeed to create listening sockets 
08-17 15:19:41.568  4263  4263 D ObexServerSockets0: startAccept()
08-17 15:19:41.568  1365  2074 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:41.568  4263  4263 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:19:41.571   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 15:19:41.573  4263  4263 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 15:19:41.573  4263  4263 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 15:19:41.574   874   874 D BluetoothA2dp: Proxy object connected
,08-17 15:19:41.574  4263  4263 D BluetoothMapService: onReceive
08-17 15:19:41.574  4263  4263 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:19:41.574  1365  1365 D BluetoothA2dp: Proxy object connected
08-17 15:19:41.574  4263  4263 D BluetoothMapService: STATE_ON
08-17 15:19:41.576  4263  4300 D ObexServerSockets0: Accepting socket connection...
08-17 15:19:41.576  4263  4301 D ObexServerSockets0: Accepting socket connection...
,08-17 15:19:41.580  4037  4037 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-17 15:19:41.581  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:41.582  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:41.584  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:41.586  4037  4037 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 15:19:41.595  4263  4263 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 15:19:41.595  4263  4263 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:19:41.599  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:19:41.602  4037  4037 D BluetoothA2dp: Proxy object connected
,08-17 15:19:41.606  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:19:41.610  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:19:41.616  1365  1365 D BluetoothPbap: Proxy object connected
,08-17 15:19:41.617  1365  1365 D PbapServerProfile: Bluetooth service connected
08-17 15:19:41.617  4037  4037 D BluetoothPbap: Proxy object connected
,08-17 15:19:41.617  4037  4037 D PbapServerProfile: Bluetooth service connected
,08-17 15:19:41.626  4263  4305 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:19:41.639  4263  4309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:19:41.640  4263  4309 I BtOppRfcommListener: Accept thread started.
,08-17 15:19:41.663   874   874 D BluetoothHeadset: Proxy object connected
08-17 15:19:41.663   874   874 D BluetoothHeadset: Proxy object connected
08-17 15:19:41.663  1365  1377 D BluetoothHeadset: Proxy object connected
08-17 15:19:41.664   874   874 D BluetoothHeadset: Proxy object connected
08-17 15:19:41.664  1365  1365 D HeadsetProfile: Bluetooth service connected
,08-17 15:19:41.664  1943  1958 D BluetoothHeadset: Proxy object connected
08-17 15:19:41.665   874   891 D BluetoothHeadset: Proxy object connected
,08-17 15:19:41.668  1943  1953 D BluetoothHeadset: Proxy object connected
,08-17 15:19:41.668  1365  2074 D BluetoothHeadset: Proxy object connected
08-17 15:19:41.668  1365  1365 D HeadsetProfile: Bluetooth service connected
,08-17 15:19:41.696  4037  4048 D BluetoothHeadset: Proxy object connected
,08-17 15:19:41.697  4037  4037 D HeadsetProfile: Bluetooth service connected
,08-17 15:19:44.991  4263  4275 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 15:19:44.991  4263  4275 D BluetoothAdapterProperties: Setting state to 13
,08-17 15:19:44.991  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 15:19:44.994  4263  4275 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 15:19:45.006  4263  4275 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:19:45.006  4263  4263 D BluetoothMapService: onReceive
,08-17 15:19:45.007  4263  4263 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:19:45.007  4263  4263 D BluetoothMapService: STATE_TURNING_OFF
,08-17 15:19:45.008  4263  4263 D BluetoothMapService: MAP Service closeService in
08-17 15:19:45.008  4263  4263 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 15:19:45.010  4263  4263 D ObexServerSockets0: shutdown(block = true)
08-17 15:19:45.011  4263  4300 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-17 15:19:45.011  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:45.012  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:19:45.015  4263  4279 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:19:45.015  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:45.015  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-17 15:19:45.016  4263  4263 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 15:19:45.018  4263  4287 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 15:19:45.018  4263  4301 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-17 15:19:45.018  4263  4263 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 15:19:45.020  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 15:19:45.022  4263  4263 I BtOppRfcommListener: stopping Accept Thread
,08-17 15:19:45.022  4263  4309 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:19:45.023  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:45.023  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:45.023  4263  4309 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 15:19:45.024  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:45.024  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:45.026  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:45.027  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:19:45.027  3938  3938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:19:45.027  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:45.029  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 15:19:45.031  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:45.032  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:45.034  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 15:19:45.035  4263  4263 D HeadsetService: Received stop request...Stopping profile...,
,08-17 15:19:45.063  4037  4047 D BluetoothHeadset: Proxy object disconnected
,08-17 15:19:45.064   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:45.064   874   874 D BluetoothHeadset: Proxy object disconnected
,08-17 15:19:45.064  1365  1378 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:45.064  1365  1365 D HeadsetProfile: Bluetooth service disconnected
,08-17 15:19:45.064   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 15:19:45.064  1943  2125 D BluetoothHeadset: Proxy object disconnected
,08-17 15:19:45.065  4263  4263 D A2dpService: Received stop request...Stopping profile...
08-17 15:19:45.066  4263  4294 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:19:45.066   874   874 D BluetoothA2dp: Proxy object disconnected
,08-17 15:19:45.067  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:19:45.067  1365  1365 D BluetoothA2dp: Proxy object disconnected
08-17 15:19:45.068  4037  4037 D HeadsetProfile: Bluetooth service disconnected
08-17 15:19:45.068  4263  4263 V BluetoothAdapterState: isTurningOff()=true
,08-17 15:19:45.068  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:45.068  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.068  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:45.069  4263  4263 D HidService: Received stop request...Stopping profile...
08-17 15:19:45.069  4263  4263 D HidService: Stopping Bluetooth HidService
,08-17 15:19:45.073  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:19:45.073  1365  1365 D BluetoothInputDevice: Proxy object disconnected
08-17 15:19:45.073  1365  1365 D HidProfile: Bluetooth service disconnected
,08-17 15:19:45.075  4037  4037 D BluetoothA2dp: Proxy object disconnected
,08-17 15:19:45.075  4037  4037 D BluetoothInputDevice: Proxy object disconnected
08-17 15:19:45.075  4037  4037 D HidProfile: Bluetooth service disconnected
,08-17 15:19:45.076  4263  4263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:19:45.077  4263  4263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 15:19:45.077  4263  4285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 15:19:45.077  4263  4285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:45.077  4263  4285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:45.077  4263  4263 D HealthService: Received stop request...Stopping profile...
08-17 15:19:45.077  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-17 15:19:45.078  4263  4279 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-17 15:19:45.079  4263  4263 D PanService: Received stop request...Stopping profile...
,08-17 15:19:45.080  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:19:45.080  1365  1365 D PanProfile: Bluetooth service disconnected
08-17 15:19:45.081  4263  4263 D BluetoothMapService: Received stop request...Stopping profile...
08-17 15:19:45.081  4263  4263 D BluetoothMapService: stop()
08-17 15:19:45.082  4263  4263 D BluetoothMapAppObserver: deinitObservers()
08-17 15:19:45.082  4263  4263 D BluetoothMapAppObserver: removeReceiver()
,08-17 15:19:45.084  1365  1365 D BluetoothMap: Proxy object disconnected
08-17 15:19:45.084  1365  1365 D MapProfile: Bluetooth service disconnected
,08-17 15:19:45.085  4037  4037 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 15:19:45.085  4037  4037 D PanProfile: Bluetooth service disconnected
08-17 15:19:45.085  4263  4263 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:45.085  4263  4263 V BluetoothAdapterState: isTurningOn()=false
,08-17 15:19:45.085  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.085  4037  4037 D BluetoothMap: Proxy object disconnected
08-17 15:19:45.086  4037  4037 D MapProfile: Bluetooth service disconnected
,08-17 15:19:45.086  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:45.087  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 15:19:45.087  4263  4285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:45.087  4263  4285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:45.087  4263  4285 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:19:45.087  4263  4285 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:19:45.087  4263  4285 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:19:45.087  4263  4285 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:19:45.089  4037  4037 D BluetoothPbap: Proxy object disconnected
,08-17 15:19:45.089  4037  4037 D PbapServerProfile: Bluetooth service disconnected
08-17 15:19:45.090  1365  1365 D BluetoothPbap: Proxy object disconnected
08-17 15:19:45.090  1365  1365 D PbapServerProfile: Bluetooth service disconnected
08-17 15:19:45.090  4263  4263 V BluetoothAdapterState: isTurningOff()=true
,08-17 15:19:45.090  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:45.091  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.091  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:45.091  4263  4263 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:19:45.091  4263  4279 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 15:19:45.091  4263  4263 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 15:19:45.092  4263  4263 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:45.092  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:45.092  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.092  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:45.093  4263  4263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:19:45.093  4263  4279 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-17 15:19:45.094  4263  4263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:19:45.094  4263  4263 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:45.094  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:45.094  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.094  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:45.099  4263  4263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:19:45.099  4263  4263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 15:19:45.100  4263  4263 D BluetoothMapService: MAP Service closeService in
,08-17 15:19:45.100  4263  4263 V BluetoothAdapterState: isTurningOff()=true
08-17 15:19:45.100  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:45.100  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.100  4263  4263 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:45.101  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 15:19:45.101  4263  4275 D BluetoothAdapterProperties: Setting state to 15
08-17 15:19:45.101  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 15:19:45.101  4263  4275 I BluetoothAdapterState: Entering BleOnState
08-17 15:19:45.102  4037  4048 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 15:19:45.103  4263  4263 D BluetoothMapService: cleanup()
08-17 15:19:45.103  4263  4263 D BluetoothMapService: MAP Service closeService in
,08-17 15:19:45.106  1365  2074 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 15:19:45.106   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:19:45.106  1365  1378 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:19:45.107  1365  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:19:45.107   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:45.107   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:45.107  1365  2074 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:19:45.108  4037  4047 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:19:45.108  4037  4048 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:19:45.109   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:45.109  4037  4047 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:19:45.109  1365  1378 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:19:45.110  1943  1958 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:45.110  4037  4048 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:45.110  1365  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:19:45.110  4037  4047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:19:45.111  4263  4275 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-17 15:19:45.111  4263  4275 D BluetoothAdapterProperties: Setting state to 16
,08-17 15:19:45.111  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 15:19:45.112  4263  4275 D BluetoothAdapterProperties: onBleDisable
08-17 15:19:45.112  4263  4275 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:19:45.112  4263  4276 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-17 15:19:45.113  4263  4285 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 15:19:45.113  4263  4285 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:19:45.114  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:45.115  4263  4279 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:19:45.116  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:45.118  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:45.119  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 15:19:45.119  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:45.120  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:45.122  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:45.123  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:19:45.128  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:19:45.248  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:45.257  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:45.259  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:19:45.279  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 15:19:45.279  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 15:19:45.279  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:19:45.280  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:19:45.297  3683  3683 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 15:19:45.297  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 15:19:45.298  3683  3683 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-17 15:19:45.317  4263  4279 I bt_hci  : shut_down
,08-17 15:19:45.317  4263  4283 D bt_hwcfg: hw_epilog_process
,08-17 15:19:45.327  4263  4283 I bt_vendor: low_power_mode_cb
,08-17 15:19:45.350  4263  4283 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-17 15:19:45.350  4263  4283 I bt_vendor: epilog_cb
,08-17 15:19:45.350  4263  4283 I bt_hci  : epilog_finished_callback
,08-17 15:19:45.357  4263  4279 I bt_hci_h4: hal_close
,08-17 15:19:45.359  4263  4279 I bt_userial_vendor: device fd = 51 close
,08-17 15:19:45.484  4263  4276 D bt_stack_manager: event_shut_down_stack finished.
,08-17 15:19:45.510  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 15:19:45.515  4263  4263 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:19:45.515  4263  4275 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-17 15:19:45.515  4263  4263 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 15:19:45.515  4263  4263 D BtGatt.GattService: stop()
08-17 15:19:45.515  4263  4263 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 15:19:45.520  4263  4263 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:19:45.520  4263  4263 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:45.520  4263  4263 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:45.520  4263  4263 V BluetoothAdapterState: isBleTurningOff()=true
08-17 15:19:45.522  4263  4275 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-17 15:19:45.522  4263  4275 D BluetoothAdapterProperties: Setting state to 10
,08-17 15:19:45.523  4263  4275 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 15:19:45.524  4263  4275 I BluetoothAdapterState: Entering OffState
08-17 15:19:45.524   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 15:19:45.547  4263  4263 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 15:19:45.547  4263  4263 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 15:19:45.547  4263  4263 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:19:45.548  4263  4276 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 15:19:45.550  4263  4276 D bt_stack_manager: event_clean_up_stack finished.
,08-17 15:19:45.552  4263  4263 I art     : System.exit called, status: 0
08-17 15:19:45.552  4263  4263 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 15:19:45.614   874   885 I ActivityManager: Process com.android.bluetooth (pid 4263) has died
,08-17 15:19:49.988  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:19:49.988  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:49.993  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:19:49.993  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afa7ea2 removed from the list
,08-17 15:19:49.994  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:49.994  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:19:49.994  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:49.997  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:19:49.998  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4b7af0 added. We now have 4 listener(s)
08-17 15:19:49.998  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:19:50.000  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:19:50.000  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4b7af0 removed from the list
,08-17 15:19:50.000  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:19:50.001  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:19:50.001  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:19:50.003  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:19:50.003  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@438a869 added. We now have 4 listener(s)
,08-17 15:19:50.004  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:19:55.017  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:55.066   874   891 I ActivityManager: Start proc 4320:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 15:19:55.200  4320  4320 D AdapterServiceConfig: Adding HeadsetService
08-17 15:19:55.200  4320  4320 D AdapterServiceConfig: Adding A2dpService
,08-17 15:19:55.200  4320  4320 D AdapterServiceConfig: Adding HidService
08-17 15:19:55.200  4320  4320 D AdapterServiceConfig: Adding HealthService
08-17 15:19:55.201  4320  4320 D AdapterServiceConfig: Adding PanService
,08-17 15:19:55.201  4320  4320 D AdapterServiceConfig: Adding GattService
08-17 15:19:55.201  4320  4320 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 15:19:55.217   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fcb662:true
08-17 15:19:55.217  4320  4320 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 15:19:55.221  4320  4320 I bt_bluedroid: init
,08-17 15:19:55.222  4320  4332 I BluetoothAdapterState: Entering OffState
,08-17 15:19:55.230  4320  4333 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:19:55.230  4320  4333 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:19:55.231  4320  4333 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 15:19:55.231  4320  4333 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 15:19:55.236  4320  4320 I bt_bluedroid: get_profile_interface socket
,08-17 15:19:55.238  4320  4336 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:19:55.240  4320  4336 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:19:55.243  4320  4320 I bt_bluedroid: get_profile_interface sdp
,08-17 15:19:55.249  4320  4331 I bt_bluedroid: config_hci_snoop_log
,08-17 15:19:55.251   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 15:19:55.263  4320  4332 D BluetoothAdapterState: Current state: OFF, message: 0
08-17 15:19:55.263  4320  4332 D BluetoothAdapterProperties: Setting state to 14
,08-17 15:19:55.264  4320  4332 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 15:19:55.270  4320  4332 D BluetoothBondStateMachine: make
,08-17 15:19:55.273  4320  4337 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 15:19:55.280  4320  4332 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:19:55.284  4320  4320 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 15:19:55.291  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:55.293  4320  4320 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:19:55.295  4320  4320 D BtGatt.GattService: Received start request. Starting profile...
,08-17 15:19:55.296  4320  4320 D BtGatt.GattService: start()
,08-17 15:19:55.296  4320  4320 I bt_bluedroid: get_profile_interface gatt
,08-17 15:19:55.300  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4,
,08-17 15:19:55.301  4320  4320 D BtGatt.AdvertiseManager: advertise manager created
,08-17 15:19:55.315  4320  4320 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:55.315  4320  4320 V BluetoothAdapterState: isTurningOn()=false
08-17 15:19:55.315  4320  4320 V BluetoothAdapterState: isBleTurningOn()=true
08-17 15:19:55.316  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:55.316  4320  4332 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 15:19:55.317  4320  4332 I bt_bluedroid: enable
08-17 15:19:55.318  4320  4333 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 15:19:55.319  4320  4333 I bt_hci  : start_up
,08-17 15:19:55.340  4320  4333 I bt_vendor: alloc value 0xb3a81189
,08-17 15:19:55.340  4320  4333 I bt_vendor: init
,08-17 15:19:55.340  4320  4333 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 15:19:55.340  4320  4333 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 15:19:55.448  4320  4333 D bt_hci  : start_up starting async portion
,08-17 15:19:55.449  4320  4340 I bt_hci  : event_finish_startup
,08-17 15:19:55.450  4320  4340 I bt_hci_h4: hal_open
,08-17 15:19:55.450  4320  4340 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 15:19:55.463  4320  4340 I bt_userial_vendor: device fd = 51 open
,08-17 15:19:55.491  4320  4340 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 15:19:55.522  4320  4340 D bt_hwcfg: Chipset BCM4354A2
08-17 15:19:55.523  4320  4340 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 15:19:55.524  4320  4340 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 15:19:56.383  4320  4340 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-17 15:19:56.385  4320  4340 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 15:19:56.385  4320  4340 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 15:19:56.503  4320  4340 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 15:19:56.504  4320  4340 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 15:19:56.532  4320  4340 I bt_hwcfg: vendor lib fwcfg completed
,08-17 15:19:56.533  4320  4340 I bt_vendor: firmware callback
08-17 15:19:56.533  4320  4340 I bt_hci  : firmware_config_callback
,08-17 15:19:56.546  4320  4342 I bt_btu  : btu_task pending for preload complete event
,08-17 15:19:56.547  4320  4342 I bt_btu_task: Bluetooth chip preload is complete
08-17 15:19:56.547  4320  4342 I bt_btu  : btu_task received preload complete event
,08-17 15:19:56.556  4320  4342 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 15:19:56.557  4320  4342 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 15:19:56.557  4320  4342 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 15:19:56.557  4320  4342 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 15:19:56.558  4320  4342 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 15:19:56.558  4320  4342 I         : BTE_InitTraceLevels -- TRC_A2D
,08-17 15:19:56.558  4320  4342 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:19:56.558  4320  4342 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:19:56.558  4320  4342 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:19:56.559  4320  4342 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:19:56.559  4320  4342 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:19:56.559  4320  4342 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:19:56.560  4320  4342 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:19:56.560  4320  4342 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:19:56.560  4320  4342 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:19:56.713  4320  4342 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fed9d
,08-17 15:19:56.713  4320  4342 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fed9d 
,08-17 15:19:56.744  4320  4336 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 15:19:56.746  4320  4336 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 15:19:56.747  4320  4336 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:19:56.750  4320  4336 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:19:56.753  4320  4336 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:19:56.753  4320  4336 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 15:19:56.754  4320  4336 D bt_hci  : do_postload posting postload work item
,08-17 15:19:56.754  4320  4340 I bt_hci  : event_postload
,08-17 15:19:56.754  4320  4340 I bt_vendor: sco_config_cb
08-17 15:19:56.755  4320  4340 I bt_hci  : sco_config_callback postload finished.
08-17 15:19:56.757  4320  4336 D bt_bte_conf: Device ID record 1 : primary
08-17 15:19:56.757  4320  4336 D bt_bte_conf:   vendorId            = 000f
08-17 15:19:56.757  4320  4336 D bt_bte_conf:   vendorIdSource      = 0001
08-17 15:19:56.757  4320  4336 D bt_bte_conf:   product             = 1200
,08-17 15:19:56.757  4320  4336 D bt_bte_conf:   version             = 1436
08-17 15:19:56.758  4320  4336 D bt_bte_conf:   clientExecutableURL = 
08-17 15:19:56.758  4320  4336 D bt_bte_conf:   serviceDescription  = 
08-17 15:19:56.758  4320  4336 D bt_bte_conf:   documentationURL    = 
08-17 15:19:56.759  4320  4336 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 15:19:56.759  4320  4333 D bt_stack_manager: event_start_up_stack finished
08-17 15:19:56.761  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:56.762  4320  4332 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 15:19:56.763  4320  4332 D BluetoothAdapterProperties: Setting state to 15
,08-17 15:19:56.763  4320  4332 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 15:19:56.768  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:56.770  4320  4332 I BluetoothAdapterState: Entering BleOnState
08-17 15:19:56.775  4320  4332 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 15:19:56.775  4320  4332 D BluetoothAdapterProperties: Setting state to 11
08-17 15:19:56.775  4320  4332 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 15:19:56.775  4320  4340 I bt_vendor: low_power_mode_cb
,08-17 15:19:56.781  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:56.783  4320  4320 D HeadsetService: Received start request. Starting profile...
,08-17 15:19:56.787  4320  4320 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:19:56.789  4320  4320 D HeadsetStateMachine: make
,08-17 15:19:56.789  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:56.792  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:19:56.802  4320  4332 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:19:56.808  4320  4320 D HeadsetStateMachine: max_hf_connections = 1
,08-17 15:19:56.809  4320  4320 I bt_bluedroid: get_profile_interface handsfree
08-17 15:19:56.812  4320  4336 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 15:19:56.812  4320  4336 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-17 15:19:56.814  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:56.816  4320  4320 D A2dpService: Received start request. Starting profile...
,08-17 15:19:56.817  4320  4320 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 15:19:56.818  4320  4320 I bt_bluedroid: get_profile_interface avrcp
,08-17 15:19:56.829  4320  4320 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 15:19:56.829  4320  4320 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:19:56.829  4320  4320 D A2dpStateMachine: make
,08-17 15:19:56.831  4320  4320 I bt_bluedroid: get_profile_interface a2dp
,08-17 15:19:56.836  4320  4336 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 15:19:56.836  4320  4351 D A2dpStateMachine: Enter Disconnected: -2
,08-17 15:19:56.838  4320  4320 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 15:19:56.839  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:56.840  4320  4320 D HidService: Received start request. Starting profile...
,08-17 15:19:56.841  4320  4320 I bt_bluedroid: get_profile_interface hidhost
08-17 15:19:56.841  4320  4320 D HidService: setHidService(): set to: null
,08-17 15:19:56.841  4320  4336 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e03e5
,08-17 15:19:56.841  4320  4336 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 15:19:56.842  4320  4320 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 15:19:56.844  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:56.845  4320  4320 D HealthService: Received start request. Starting profile...
,08-17 15:19:56.848  4320  4320 I bt_bluedroid: get_profile_interface health
,08-17 15:19:56.849  4320  4320 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:19:56.851  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:56.852  4320  4320 D PanService: Received start request. Starting profile...
,08-17 15:19:56.852  4320  4320 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 15:19:56.852  4320  4320 I bt_bluedroid: get_profile_interface pan
,08-17 15:19:56.853  4320  4336 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 15:19:56.858  4320  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:19:56.859  4320  4320 D BluetoothMapService: Received start request. Starting profile...
,08-17 15:19:56.859  4320  4320 D BluetoothMapService: start()
,08-17 15:19:56.863  4320  4320 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 15:19:56.864  4320  4320 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 15:19:56.864  4320  4320 D BluetoothMapAppObserver: createReceiver()
,08-17 15:19:56.865  4320  4320 D BluetoothMapAppObserver: initObservers()
08-17 15:19:56.865  4320  4320 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 15:19:56.874  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:19:56.874  4320  4348 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 15:19:56.875  4320  4320 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:19:56.875  4320  4320 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:19:56.875  4320  4320 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:19:56.875  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:19:56.876  4320  4320 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:56.877  4320  4320 V BluetoothAdapterState: isTurningOn()=true
08-17 15:19:56.878  4320  4320 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:56.878  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:56.878  4320  4320 V BluetoothAdapterState: isTurningOff()=false
08-17 15:19:56.878  4320  4320 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:19:56.878  4320  4320 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:19:56.878  4320  4320 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:19:56.878  4320  4332 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 15:19:56.878  4320  4332 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:19:56.878  4320  4332 D BluetoothAdapterProperties: State =  11
08-17 15:19:56.879  4320  4332 D BluetoothAdapterProperties: Setting state to 12
08-17 15:19:56.879  4320  4332 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 15:19:56.880  4037  4047 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:19:56.880  4320  4336 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:19:56.880  4320  4336 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:19:56.880  4320  4332 I BluetoothAdapterState: Entering OnState
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:56.884  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:56.884  1365  1377 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:19:56.885  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:56.886   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:19:56.887  1365  2074 D BluetoothMap: onBluetoothStateChange: up=true
08-17 15:19:56.887   874   874 D BluetoothA2dp: Proxy object connected
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:19:56.889  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:19:56.889  1365  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:19:56.890  1365  1365 D BluetoothMap: Proxy object connected
08-17 15:19:56.890  1365  1365 D MapProfile: Bluetooth service connected
08-17 15:19:56.890  1365  1365 D BluetoothMap: getConnectedDevices()
08-17 15:19:56.891   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:56.891   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:19:56.891  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:19:56.891  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:19:56.891  4320  4320 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:19:56.892  4320  4320 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 15:19:56.893  1365  1365 D BluetoothA2dp: Proxy object connected
08-17 15:19:56.893  4037  4048 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 15:19:56.895  4320  4320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:19:56.897  4320  4320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:19:56.898  4320  4320 D ObexServerSockets: Succeed to create listening sockets 
08-17 15:19:56.898  4320  4320 D ObexServerSockets0: startAccept()
08-17 15:19:56.898  4320  4320 D ObexServerSockets0: prepareForNewConnect()
08-17 15:19:56.898  4037  4047 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:19:56.899  4320  4320 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 15:19:56.899  4320  4320 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 15:19:56.900  4320  4357 D ObexServerSockets0: Accepting socket connection...
08-17 15:19:56.901  1365  1365 D BluetoothInputDevice: Proxy object connected
08-17 15:19:56.901  1365  1365 D HidProfile: Bluetooth service connected
08-17 15:19:56.901  4320  4358 D ObexServerSockets0: Accepting socket connection...
,08-17 15:19:56.903   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:19:56.903  4037  4048 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:19:56.905  1365  2074 D BluetoothPan: onBluetoothStateChange on: true
,08-17 15:19:56.906  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:19:56.906  1365  1365 D PanProfile: Bluetooth service connected
08-17 15:19:56.907  1943  1958 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:19:56.907  4037  4048 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:19:56.908  1365  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:19:56.908  4037  4047 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:19:56.908  4037  4037 D BluetoothInputDevice: Proxy object connected
,08-17 15:19:56.909  4037  4037 D HidProfile: Bluetooth service connected
,08-17 15:19:56.913   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 15:19:56.915  4320  4320 D BluetoothMapService: onReceive
08-17 15:19:56.915  4320  4320 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:19:56.915  4320  4320 D BluetoothMapService: STATE_ON
08-17 15:19:56.916  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:56.916  4037  4037 D BluetoothMap: Proxy object connected
,08-17 15:19:56.917  4037  4037 D MapProfile: Bluetooth service connected
08-17 15:19:56.917  4037  4037 D BluetoothMap: getConnectedDevices()
,08-17 15:19:56.917  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:19:56.918  4037  4037 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 15:19:56.918  4037  4037 D PanProfile: Bluetooth service connected
08-17 15:19:56.918  4037  4037 D BluetoothA2dp: Proxy object connected
,08-17 15:19:56.923  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:19:56.928  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:19:56.930  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:19:56.934  4037  4037 D BluetoothPbap: Proxy object connected
,08-17 15:19:56.934  4037  4037 D PbapServerProfile: Bluetooth service connected
,08-17 15:19:56.937  4320  4361 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:19:56.941  1365  1365 D BluetoothPbap: Proxy object connected
08-17 15:19:56.941  1365  1365 D PbapServerProfile: Bluetooth service connected
,08-17 15:19:56.941  4320  4320 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:19:56.941  4320  4320 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:19:56.957  4320  4367 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:19:56.959  4320  4367 I BtOppRfcommListener: Accept thread started.
,08-17 15:19:56.993  4037  4359 D BluetoothHeadset: Proxy object connected
,08-17 15:19:56.994   874   874 D BluetoothHeadset: Proxy object connected
08-17 15:19:56.994   874   874 D BluetoothHeadset: Proxy object connected
08-17 15:19:56.995  1365  1377 D BluetoothHeadset: Proxy object connected
08-17 15:19:56.995   874   874 D BluetoothHeadset: Proxy object connected
08-17 15:19:56.995  1365  1365 D HeadsetProfile: Bluetooth service connected
08-17 15:19:56.995  1943  1953 D BluetoothHeadset: Proxy object connected
08-17 15:19:56.996  4037  4037 D HeadsetProfile: Bluetooth service connected
,08-17 15:19:57.003   874   891 D BluetoothHeadset: Proxy object connected
,08-17 15:19:57.007  1943  2125 D BluetoothHeadset: Proxy object connected
,08-17 15:19:57.008  4037  4048 D BluetoothHeadset: Proxy object connected
,08-17 15:19:57.009  1365  2074 D BluetoothHeadset: Proxy object connected
08-17 15:19:57.010  1365  1365 D HeadsetProfile: Bluetooth service connected
,08-17 15:19:57.010  4037  4037 D HeadsetProfile: Bluetooth service connected
,08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:20:00.037  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:20:00.044  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:20:00.046  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:00.047  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@438a869 removed from the list
,08-17 15:20:00.047  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:20:00.047  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:00.048  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:00.050  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:20:00.051  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a5e2ee added. We now have 4 listener(s)
08-17 15:20:00.051  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:20:00.055   874  1685 D WifiService: setWifiEnabled: false pid=3938, uid=10000
08-17 15:20:00.055   874  1685 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:20:04.341  1869  1918 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-17 15:20:04.342  1869  1918 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-17 15:20:04.397  1500  1500 I ConfigService: onCreate
,08-17 15:20:05.067  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:20:05.069   874  1685 D WifiService: setWifiEnabled: true pid=3938, uid=10000
,08-17 15:20:05.069   874  1685 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:20:05.081   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:20:05.097  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:20:05.106  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:20:05.116  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:20:05.117   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 15:20:05.119   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 15:20:05.120  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:20:05.122   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 15:20:05.124   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 15:20:05.124   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 15:20:05.124   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 15:20:05.124   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 15:20:05.142   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 15:20:05.144   370   872 D CommandListener: Setting iface cfg
,08-17 15:20:05.144   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 15:20:05.144   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-17 15:20:05.144   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 15:20:05.147   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 15:20:05.199   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 15:20:05.203   874  1307 E native  : do suspend true
,08-17 15:20:05.249   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:20:06.523   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 15:20:06.654   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.81 rxSuccessRate=9.19 delta 1000 -> 994
,08-17 15:20:06.657   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 15:20:06.657   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:20:06.677   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 15:20:06.732   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 15:20:06.737  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 15:20:07.169  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:20:07.203  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:20:07.203  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 15:20:07.209   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:20:07.220   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 15:20:07.221   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 15:20:07.221   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:20:07.244   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:20:07.261   370   872 D CommandListener: Setting iface cfg
,08-17 15:20:07.262   874  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 15:20:07.273   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 15:20:07.303   874  4379 D DhcpClient: Receive thread started
,08-17 15:20:07.392   874  1307 E native  : do suspend false
,08-17 15:20:07.414   874  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 15:20:07.427   874  4379 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-17 15:20:07.428   874  2085 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-17 15:20:07.431   874  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 15:20:07.444   874  4379 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 15:20:07.445   874  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 15:20:07.450   370   872 D CommandListener: Setting iface cfg
,08-17 15:20:07.463   874  2085 D DhcpClient: Scheduling renewal in 86399s
,08-17 15:20:07.462   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 15:20:07.469   874  1307 E native  : do suspend true
,08-17 15:20:07.491   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 15:20:07.494   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 15:20:07.495   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 15:20:07.498   874  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 15:20:07.509   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 15:20:07.551   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 15:20:07.551   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 15:20:07.553   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 15:20:07.554   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-17 15:20:07.555   874  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 15:20:07.568   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 15:20:07.575   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-17 15:20:07.575   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-17 15:20:07.575   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 15:20:07.576   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:20:07.576   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-17 15:20:07.576   874  1309 D ConnectivityService:    accepting network in place of null
08-17 15:20:07.578   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 15:20:07.585   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216282, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 15:20:07.620   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:20:07.651   874  4377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
,08-17 15:20:07.678   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:20:07.685   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 15:20:07.687   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:20:07.694   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 15:20:07.695   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:07.716  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:20:07.721  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:20:07.724  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:20:07.728   874  4377 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:20:07 GMT], X-Android-Received-Millis=[1471440007727], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471440007698]}
,08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:07.731  3938  3938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:20:07.731  1713  1713 D SystemUpdateService: onCreate
08-17 15:20:07.732   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 15:20:07.733  3938  3938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:07.733   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 15:20:07.734   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 15:20:07.736  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:20:07.738   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:20:07.761  1713  4389 I SystemUpdateService: active receiver: enabled
,08-17 15:20:07.764  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 15:20:07.766  1713  2503 I iu.UploadsManager: num queued entries: 0
,08-17 15:20:07.771  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:20:07.775  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:20:07.777  4091  4091 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:20:07.781  1713  4389 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:20:07.782  4091  4091 D SprintDMHelper: simOperator: 
,08-17 15:20:07.782  4091  4091 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:20:07.783  1713  2503 I iu.UploadsManager: num updated entries: 0
08-17 15:20:07.785  1713  2503 I iu.SyncManager: NEXT; no task
,08-17 15:20:07.788  1713  4389 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 15:20:07.788  1713  4389 I SystemUpdateService: now status is 0 (complete)
08-17 15:20:07.788  1713  4389 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:20:07.788  1713  4389 I SystemUpdateService: file has been verified
,08-17 15:20:07.788  1713  4389 I SystemUpdateService: OTA package size = 12249756
,08-17 15:20:07.795  1713  4391 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 15:20:07.796  1713  4391 W BaseAppContext: Using Auth Proxy for data requests.
08-17 15:20:07.797  3890  4394 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 15:20:07.798  1713  4391 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 15:20:07.814  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:20:07.816  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:20:07.835  1713  4389 I SystemUpdateService: showing system update notification
,08-17 15:20:07.882  1713  1713 D SystemUpdateService: onDestroy
,08-17 15:20:07.896  3890  4400 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 15:20:07.902  1500  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-17 15:20:07.903  1500  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 15:20:07.903  1500  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:20:07.903  1500  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:20:07.919  1500  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:20:07.919  1500  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 15:20:07.920  1500  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:20:07.920  1500  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:20:07.924  2817  4395 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 15:20:07.960  1713  4391 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-17 15:20:07.979  1500  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:20:07.979  1500  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 15:20:07.979  1500  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:20:07.979  1500  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:20:07.997  3890  4400 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 15:20:07.998  3890  4394 E BooksSync: Soft error
08-17 15:20:07.998  3890  4394 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 15:20:07.998  3890  4394 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 15:20:07.998  3890  4394 E BooksSync: Sync error
08-17 15:20:07.998  3890  4394 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 15:20:07.998  3890  4394 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 15:20:07.999  3890  4394 I BooksSync: Finished books sync
,08-17 15:20:08.012   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 213685, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:20:08.684   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 15:20:09.489  1500  1500 I ConfigService: onDestroy
,08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:10.093  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:20:10.100  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:20:10.101  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:10.102  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a5e2ee removed from the list,
,08-17 15:20:10.102  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:20:10.102  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:20:10.103  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:10.114  3938  4402 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-17 15:20:10.115  3938  4402 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 15:20:13.121  3938  4403 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-17 15:20:13.122  3938  4402 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-17 15:20:13.123  3938  4403 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-17 15:20:13.123  3938  4402 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 15:20:13.124  3938  4403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 15:20:13.125  3938  4402 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 15:20:13.126  3938  4403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 15:20:13.127  3938  4402 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 15:20:13.130  3938  4405 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: IncomingSocketThread/Sender)
,08-17 15:20:13.130  3938  4403 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-17 15:20:13.132  3938  4402 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-17 15:20:13.136  3938  4406 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: OutgoingSocketThread/Sender)
,08-17 15:20:13.140  3938  4407 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: IncomingSocketThread/Receiver)
,08-17 15:20:13.142  3938  4408 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: OutgoingSocketThread/Receiver)
,08-17 15:20:13.142  3938  4407 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: IncomingSocketThread/Receiver)
08-17 15:20:13.143  3938  4407 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-17 15:20:13.143  3938  4407 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-17 15:20:13.144  3938  4408 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: OutgoingSocketThread/Receiver)
08-17 15:20:13.144  3938  4408 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-17 15:20:13.144  3938  4408 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-17 15:20:15.582   874  1309 D ConnectivityService: handlePromptUnvalidated 102
,08-17 15:20:16.121  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 15:20:16.123  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 15:20:16.131  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1216810 Bundle[{}]
,08-17 15:20:16.131  3938  3988 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 15:20:16.132  3938  3988 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 15:20:16.132  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivityStarted,
08-17 15:20:16.133  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 15:20:16.133  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 15:20:16.134  3938  3988 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 15:20:16.138  3938  3988 I System.out: Running OutgoingSocketThread
,08-17 15:20:16.141  3938  4409 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-17 15:20:16.141  3938  4409 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 15:20:19.151  3938  4410 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-17 15:20:19.151  3938  4410 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-17 15:20:19.152  3938  4410 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 15:20:19.153  3938  4409 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-17 15:20:19.153  3938  4409 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 15:20:19.154  3938  4409 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 15:20:19.154  3938  4410 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 15:20:19.156  3938  4412 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: IncomingSocketThread/Sender)
,08-17 15:20:19.157  3938  4409 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 15:20:19.157  3938  4410 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-17 15:20:19.162  3938  4409 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-17 15:20:19.168  3938  4414 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 470, name: IncomingSocketThread/Receiver)
,08-17 15:20:19.169  3938  4413 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 471, name: OutgoingSocketThread/Sender)
,08-17 15:20:19.170  3938  4414 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 470, thread name: IncomingSocketThread/Receiver)
08-17 15:20:19.170  3938  4414 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-17 15:20:19.170  3938  4414 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 470, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-17 15:20:19.171  3938  4415 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: OutgoingSocketThread/Receiver)
08-17 15:20:19.173  3938  4415 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 472, thread name: OutgoingSocketThread/Receiver)
08-17 15:20:19.174  3938  4415 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done,
08-17 15:20:19.174  3938  4415 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 472, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-17 15:20:22.153  3938  3988 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 481)
,08-17 15:20:22.155  3938  3988 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 15:20:22.156  3938  3988 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 482)
,08-17 15:20:22.163  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:20:22.163  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da538f added. We now have 3 listener(s)
08-17 15:20:22.165  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:20:22.165  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:20:22.165  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:20:22.165  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:20:22.165  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05561c added. We now have 4 listener(s)
08-17 15:20:22.165  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:20:22.166  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:20:22.170  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:22.181  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:20:22.187  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:20:22.187  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:20:22.188  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:20:22.188  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:20:22.188  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:20:22.188  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:20:22.188  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:22.189  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:20:22.189  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:20:22.189  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da538f removed from the list
08-17 15:20:22.189  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:22.189  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05561c removed from the list
,08-17 15:20:22.193  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:20:22.194  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:20:22.194  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:22.194  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:20:22.195  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:22.196  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:20:22.197  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:20:22.197  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:22.197  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05561c not in the list
,08-17 15:20:22.197  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:22.197  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:22.199  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:22.200  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:20:22.200  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:22.200  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05561c not in the list
08-17 15:20:22.200  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:22.201  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:20:22.201  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:22.201  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:22.201  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da538f not in the list
08-17 15:20:22.203  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:20:22.203  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b913ffa added. We now have 3 listener(s)
,08-17 15:20:22.209  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:20:22.210  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:20:22.210  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:20:22.210  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:20:22.211  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b299ab added. We now have 4 listener(s)
08-17 15:20:22.211  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:20:22.212  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:20:22.218  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:22.226  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:20:22.231  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:22.231  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:20:22.231  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:20:22.231  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:20:22.231  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 15:20:22.232  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:20:22.232  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:20:22.235  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:20:22.237  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 15:20:22.237  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:20:22.240  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:20:22.245  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:20:22.247  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 15:20:22.247  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:20:22.256  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:20:22.256  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:20:22.256  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 15:20:22.258  3938  3988 D BluetoothAdapter: STATE_ON
,08-17 15:20:22.266  4320  4331 D BtGatt.GattService: registerClient() - UUID=4bb0b455-088b-4377-ae92-749ccee379e3
,08-17 15:20:22.268  4320  4336 D BtGatt.GattService: onClientRegistered() - UUID=4bb0b455-088b-4377-ae92-749ccee379e3, clientIf=5
,08-17 15:20:22.270  3938  3949 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 15:20:22.274  4320  4330 D BtGatt.GattService: start scan with filters
,08-17 15:20:22.285  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 15:20:22.285  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:20:22.286  4320  4339 D BtGatt.ScanManager: handling starting scan
,08-17 15:20:22.286  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-17 15:20:22.286  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:20:22.291  4320  4339 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8be95a4
,08-17 15:20:22.296  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:20:22.297  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:20:22.297  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:20:22.303  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:20:22.306  4320  4336 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:20:22.306  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:22.308  4320  4339 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 15:20:22.311  3938  3988 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:20:22.312  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:20:22.312  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:20:22.312  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:22.313  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 15:20:22.313  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 15:20:22.313  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:20:22.313  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 15:20:22.314  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:20:22.315  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 15:20:22.315  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:20:22.318  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:20:22.319  4320  4330 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:20:22.321  4320  4349 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 15:20:22.322  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 15:20:22.322  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:20:22.323  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 15:20:22.323  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 15:20:22.323  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:20:22.326  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:20:22.327  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 15:20:22.327  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:20:22.327  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:20:22.328  4320  4336 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:20:22.328  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:22.329  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:20:22.330  4320  4339 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:20:22.331  4320  4339 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 15:20:22.331  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:20:22.332  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:20:22.332  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:20:22.361  4320  4336 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 15:20:22.361  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:22.371  4320  4336 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 15:20:22.372  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:22.388  4320  4336 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 15:20:22.388  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-17 15:20:22.389  4320  4339 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:20:22.400  4320  4336 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:20:22.401  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:22.401  4320  4339 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:20:22.416  4320  4336 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 15:20:22.417  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:22.833  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:20:22.834  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:20:22.834  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:20:25.332  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:20:25.333  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:20:25.333  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:20:25.334  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:25.334  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:25.334  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:20:25.335  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:20:25.335  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b913ffa removed from the list
08-17 15:20:25.335  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:25.336  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b299ab removed from the list
08-17 15:20:25.336  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:20:25.336  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:25.338  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:25.338  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:25.341  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:20:25.342  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:25.342  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:25.343  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b299ab not in the list
08-17 15:20:25.343  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:25.343  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:25.347  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:20:25.347  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:20:25.347  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:25.347  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b299ab not in the list
08-17 15:20:25.348  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:25.348  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:25.348  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:25.349  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b913ffa not in the list
08-17 15:20:25.351  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:20:25.351  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fc4cb4 added. We now have 3 listener(s)
,08-17 15:20:25.357  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:20:25.358  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:20:25.358  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:20:25.359  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:20:25.359  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03b0dd added. We now have 4 listener(s)
08-17 15:20:25.360  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:20:25.361  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:20:25.366  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:25.375  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:20:25.379  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:20:25.379  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:20:25.380  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 15:20:25.381  3938  3988 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-17 15:20:25.382  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-17 15:20:25.382  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-17 15:20:25.383  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-17 15:20:25.383  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 15:20:25.383  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:20:25.384  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:20:25.386  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 15:20:25.388  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-17 15:20:25.388  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 15:20:25.389  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 15:20:25.389  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-17 15:20:25.389  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:20:25.389  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:20:25.390  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:20:25.391  3938  3938 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 15:20:25.391  3938  4416 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:20:25.396  3938  4416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-17 15:20:25.400  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 15:20:25.401  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:20:25.409  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:20:25.411  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 15:20:25.411  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:20:25.415  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-17 15:20:25.416  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:20:25.417  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-17 15:20:25.419  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-17 15:20:25.419  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-17 15:20:25.420  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-17 15:20:25.421  3938  3988 D BluetoothAdapter: STATE_ON
,08-17 15:20:25.426  4320  4330 D BtGatt.GattService: registerClient() - UUID=dc024b6b-c944-4d64-99aa-b0df9af81190
,08-17 15:20:25.427  4320  4336 D BtGatt.GattService: onClientRegistered() - UUID=dc024b6b-c944-4d64-99aa-b0df9af81190, clientIf=5
,08-17 15:20:25.428  3938  3949 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-17 15:20:25.431  4320  4338 D BtGatt.AdvertiseManager: message : 0
,08-17 15:20:25.437  4320  4338 D BtGatt.AdvertiseManager: starting multi advertising
,08-17 15:20:25.452  4320  4336 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-17 15:20:25.464  4320  4336 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-17 15:20:25.466  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-17 15:20:25.467  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:20:25.471  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:20:25.473  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 15:20:25.474  3938  3938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-17 15:20:25.474  3938  3938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-17 15:20:25.474  3938  3938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-17 15:20:25.475  3938  3938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-17 15:20:25.475  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-17 15:20:25.477  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 15:20:25.483  3938  3938 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-17 15:20:25.483  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-17 15:20:25.985  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-17 15:20:25.985  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 15:20:25.985  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:20:28.478  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:20:28.479  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-17 15:20:28.480  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:20:28.480  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 15:20:28.480  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-17 15:20:28.480  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-17 15:20:28.484  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 15:20:28.485  3938  4416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 15:20:28.485  3938  3988 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 15:20:28.485  3938  4416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 15:20:28.485  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:20:28.485  3938  3938 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 15:20:28.486  3938  4416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 15:20:28.486  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 15:20:28.486  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:20:28.486  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 15:20:28.487  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:20:28.489  3938  3988 D BluetoothAdapter: STATE_ON
08-17 15:20:28.489  3938  3988 D BluetoothLeScanner: could not find callback wrapper
08-17 15:20:28.490  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 15:20:28.490  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-17 15:20:28.492  4320  4338 D BtGatt.AdvertiseManager: message : 1
08-17 15:20:28.493  4320  4338 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-17 15:20:28.503  4320  4336 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-17 15:20:28.503  4320  4336 D BtGatt.GattService: Client app is not null!
,08-17 15:20:28.504  4320  4349 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 15:20:28.505  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:20:28.506  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-17 15:20:28.506  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-17 15:20:28.506  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-17 15:20:28.507  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-17 15:20:28.509  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:20:28.509  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 15:20:28.509  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:20:28.510  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:20:28.513  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:20:28.514  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 15:20:28.514  3938  3938 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 15:20:28.514  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:20:28.515  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:20:28.515  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:20:28.516  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:28.516  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:28.516  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:20:28.516  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:20:28.517  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fc4cb4 removed from the list
08-17 15:20:28.517  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:28.517  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03b0dd removed from the list
08-17 15:20:28.517  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:20:28.518  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:28.519  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:20:28.519  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:28.521  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:20:28.521  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:28.521  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:28.522  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03b0dd not in the list
08-17 15:20:28.522  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:28.522  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:28.523  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:28.524  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:20:28.524  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:28.524  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03b0dd not in the list
,08-17 15:20:28.524  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:28.524  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:28.524  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:28.524  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fc4cb4 not in the list
08-17 15:20:28.525  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:20:28.525  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b46e39e added. We now have 3 listener(s)
,08-17 15:20:28.527  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:20:28.527  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:20:28.527  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:20:28.527  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:20:28.527  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd3e7f added. We now have 4 listener(s)
08-17 15:20:28.528  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:20:28.528  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:20:28.531  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:28.535  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:20:28.538  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:20:28.538  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:20:28.538  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-17 15:20:28.538  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:20:28.538  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-17 15:20:28.538  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:20:28.539  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:20:28.541  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:20:28.543  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:20:28.544  3938  3988 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:20:28.544  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:20:28.548  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:20:28.549  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:20:28.549  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:20:28.552  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:20:28.552  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:20:28.552  3938  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:20:28.553  3938  3988 D BluetoothAdapter: STATE_ON
,08-17 15:20:28.556  4320  4356 D BtGatt.GattService: registerClient() - UUID=5d4ef524-9159-4877-89c5-4a2a700c4fdf
,08-17 15:20:28.556  4320  4336 D BtGatt.GattService: onClientRegistered() - UUID=5d4ef524-9159-4877-89c5-4a2a700c4fdf, clientIf=5
08-17 15:20:28.557  3938  3949 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 15:20:28.557  4320  4331 D BtGatt.GattService: start scan with filters
,08-17 15:20:28.560  4320  4339 D BtGatt.ScanManager: handling starting scan
,08-17 15:20:28.560  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:20:28.560  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:20:28.560  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:20:28.560  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:20:28.564  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:20:28.564  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:20:28.565  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:20:28.567  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:20:28.571  4320  4336 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:20:28.571  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:28.572  4320  4339 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-17 15:20:28.579  4320  4336 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:20:28.579  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:28.579  4320  4339 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 15:20:28.579  4320  4339 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 15:20:28.591  4320  4336 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 15:20:28.591  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:28.598  4320  4336 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 15:20:28.598  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:20:29.016  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:20:29.065  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-17 15:20:29.065  3938  3938 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:20:29.065  3938  3938 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:20:30.105  4320  4320 D BtGatt.ScanManager: awakened up at time 238802
,08-17 15:20:30.109  4320  4339 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:20:30.147  4320  4336 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-17 15:20:30.147  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:30.148  4320  4336 D BtGatt.GattService: current time is 238845792589
,08-17 15:20:30.149  4320  4336 D BtGatt.GattService: Batch record : [35, -17, -63, 81, 81, 96, 1, -128, -56, 29, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-17 15:20:30.153  4320  4336 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-17 15:20:30.155  4320  4336 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-17 15:20:30.156  4320  4336 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-17 15:20:30.159  4320  4336 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 15:20:30.160  4320  4336 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-17 15:20:30.161  4320  4336 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-17 15:20:30.164  3938  3938 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-17 15:20:30.165  3938  3938 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-17 15:20:31.579  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:20:31.579  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:20:31.580  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:20:31.580  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:31.580  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 15:20:31.581  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:20:31.581  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:20:31.581  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:20:31.581  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 15:20:31.583  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:20:31.583  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:20:31.585  3938  3988 D BluetoothAdapter: STATE_ON
,08-17 15:20:31.587  4320  4331 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:20:31.590  4320  4349 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 15:20:31.594  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:20:31.594  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:20:31.594  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:20:31.595  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:20:31.595  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:20:31.600  4320  4320 D BtGatt.ScanManager: awakened up at time 240297
,08-17 15:20:31.599  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:20:31.602  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:20:31.603  3938  3988 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:20:31.604  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:20:31.606  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:20:31.606  3938  3988 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-17 15:20:31.610  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:31.610  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:20:31.610  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:20:31.610  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:20:31.610  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:20:31.610  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b46e39e removed from the list
,08-17 15:20:31.610  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:20:31.611  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd3e7f removed from the list
,08-17 15:20:31.611  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:20:31.611  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:31.611  3938  3938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:20:31.611  3938  3938 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:20:31.612  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:20:31.612  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:31.613  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:20:31.613  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:31.613  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:31.614  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd3e7f not in the list
08-17 15:20:31.614  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:20:31.614  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:31.614  4320  4336 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 15:20:31.614  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:31.614  4320  4339 D BtGatt.ScanManager: stopping BLe Batch
08-17 15:20:31.615  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:31.615  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:20:31.615  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:31.615  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd3e7f not in the list
08-17 15:20:31.616  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:31.616  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:31.616  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:20:31.616  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b46e39e not in the list
,08-17 15:20:31.617  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:20:31.617  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920f11 added. We now have 3 listener(s)
08-17 15:20:31.618  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:20:31.619  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:20:31.619  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:20:31.619  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:20:31.619  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2edc876 added. We now have 4 listener(s)
08-17 15:20:31.619  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:20:31.620  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:20:31.625  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:20:31.625  4320  4336 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:20:31.625  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:31.625  4320  4339 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:20:31.631  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:20:31.633  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:20:31.634  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:20:31.634  3938  3988 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:20:31.634  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:20:31.634  3938  3988 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:20:31.634  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:31.634  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:31.634  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:20:31.634  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:20:31.635  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920f11 removed from the list
08-17 15:20:31.635  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:31.636  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2edc876 removed from the list
08-17 15:20:31.636  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:20:31.636  3938  3988 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:20:31.636  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:31.637  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:31.637  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:31.639  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:20:31.639  4320  4336 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-17 15:20:31.639  4320  4336 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:20:31.639  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:20:31.639  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:31.639  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:31.639  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2edc876 not in the list
,08-17 15:20:31.639  4320  4336 D BtGatt.GattService: current time is 240337408273
08-17 15:20:31.640  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:31.640  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:31.640  4320  4336 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -97, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 15:20:31.640  4320  4336 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 15:20:31.640  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:20:31.640  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:20:31.641  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:20:31.641  3938  3988 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2edc876 not in the list
08-17 15:20:31.641  3938  3988 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:20:31.641  3938  3988 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:20:31.641  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:20:31.641  3938  3988 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c920f11 not in the list
08-17 15:20:31.642  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-17 15:20:31.642  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 15:20:31.642  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 15:20:31.642  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:20:31.643  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 15:20:31.643  3938  3988 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:20:32.112  3938  3938 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:20:33.657  3938  4418 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: My test thread name)
,08-17 15:20:35.655  3938  3988 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 491
,08-17 15:20:35.655  3938  3988 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 491, name: My test thread name)
,08-17 15:20:35.661  3938  4419 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: My test thread name)
,08-17 15:20:35.662  3938  4419 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 492, thread name: My test thread name)
08-17 15:20:35.662  3938  4419 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 492, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-17 15:20:35.666  3938  3988 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 15:20:35.674  3938  4420 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 496, name: My test thread name)
,08-17 15:20:35.675  3938  4420 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 496, thread name: My test thread name): Test exception.
,08-17 15:20:35.676  3938  4420 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 496, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-17 15:20:35.683  3938  3988 I jxcore-log: Total number of executed tests:  82
08-17 15:20:35.683  3938  3988 I jxcore-log: 
,08-17 15:20:35.683  3938  3988 I jxcore-log: Number of passed tests:  82
08-17 15:20:35.683  3938  3988 I jxcore-log: 
,08-17 15:20:35.684  3938  3988 I jxcore-log: Number of failed tests:  0
08-17 15:20:35.684  3938  3988 I jxcore-log: 
,08-17 15:20:35.685  3938  3988 I jxcore-log: Number of ignored tests:  0
08-17 15:20:35.685  3938  3988 I jxcore-log: 
,08-17 15:20:35.687  3938  3988 I jxcore-log: Total duration:  101267
08-17 15:20:35.687  3938  3988 I jxcore-log: 
,08-17 15:20:35.694  3938  3988 I jxcore-log: Unit Test app is loaded
08-17 15:20:35.694  3938  3988 I jxcore-log: 
,08-17 15:20:35.703  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.703  3938  3988 I jxcore-log: 
,08-17 15:20:35.707  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.707  3938  3988 I jxcore-log: 
,08-17 15:20:35.708  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.708  3938  3988 I jxcore-log: 
,08-17 15:20:35.710  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.710  3938  3988 I jxcore-log: 
,08-17 15:20:35.711  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-17 15:20:35.711  3938  3988 I jxcore-log: 
,08-17 15:20:35.713  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:20:35.713  3938  3988 I jxcore-log: 
,08-17 15:20:35.715  3938  3938 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-17 15:20:35.715  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.715  3938  3988 I jxcore-log: 
08-17 15:20:35.717  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.717  3938  3988 I jxcore-log: 
,08-17 15:20:35.719  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-17 15:20:35.719  3938  3988 I jxcore-log: 
08-17 15:20:35.719  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:20:35.719  3938  3988 I jxcore-log: 
,08-17 15:20:35.720  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:20:35.720  3938  3988 I jxcore-log: 
08-17 15:20:35.721  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.721  3938  3988 I jxcore-log: 
,08-17 15:20:35.722  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.722  3938  3988 I jxcore-log: 
,08-17 15:20:35.723  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.723  3938  3988 I jxcore-log: 
08-17 15:20:35.723  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.723  3938  3988 I jxcore-log: 
,08-17 15:20:35.724  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.724  3938  3988 I jxcore-log: 
,08-17 15:20:35.725  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.725  3938  3988 I jxcore-log: 
08-17 15:20:35.726  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.726  3938  3988 I jxcore-log: 
,08-17 15:20:35.727  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.727  3938  3988 I jxcore-log: 
08-17 15:20:35.728  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.728  3938  3988 I jxcore-log: 
,08-17 15:20:35.729  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.729  3938  3988 I jxcore-log: 
,08-17 15:20:35.729  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.729  3938  3988 I jxcore-log: 
08-17 15:20:35.730  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.730  3938  3988 I jxcore-log: 
,08-17 15:20:35.731  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.731  3938  3988 I jxcore-log: 
08-17 15:20:35.732  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.732  3938  3988 I jxcore-log: 
,08-17 15:20:35.732  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.732  3938  3988 I jxcore-log: 
08-17 15:20:35.733  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.733  3938  3988 I jxcore-log: 
,08-17 15:20:35.734  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.734  3938  3988 I jxcore-log: 
08-17 15:20:35.735  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.735  3938  3988 I jxcore-log: 
,08-17 15:20:35.736  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.736  3938  3988 I jxcore-log: 
,08-17 15:20:35.737  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.737  3938  3988 I jxcore-log: 
08-17 15:20:35.737  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.737  3938  3988 I jxcore-log: 
,08-17 15:20:35.738  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.738  3938  3988 I jxcore-log: 
08-17 15:20:35.738  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.738  3938  3988 I jxcore-log: 
08-17 15:20:35.739  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.739  3938  3988 I jxcore-log: 
,08-17 15:20:35.739  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.739  3938  3988 I jxcore-log: 
08-17 15:20:35.740  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.740  3938  3988 I jxcore-log: 
08-17 15:20:35.740  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.740  3938  3988 I jxcore-log: 
,08-17 15:20:35.741  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.741  3938  3988 I jxcore-log: 
08-17 15:20:35.741  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.741  3938  3988 I jxcore-log: 
08-17 15:20:35.742  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:20:35.742  3938  3988 I jxcore-log: 
,08-17 15:20:35.742  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.742  3938  3988 I jxcore-log: 
08-17 15:20:35.743  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:20:35.743  3938  3988 I jxcore-log: 
08-17 15:20:35.743  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.743  3938  3988 I jxcore-log: 
,08-17 15:20:35.744  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.744  3938  3988 I jxcore-log: 
08-17 15:20:35.744  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.744  3938  3988 I jxcore-log: 
08-17 15:20:35.745  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.745  3938  3988 I jxcore-log: 
,08-17 15:20:35.745  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.745  3938  3988 I jxcore-log: 
08-17 15:20:35.746  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:20:35.746  3938  3988 I jxcore-log: 
08-17 15:20:35.746  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.746  3938  3988 I jxcore-log: 
,08-17 15:20:35.747  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-17 15:20:35.747  3938  3988 I jxcore-log: 
08-17 15:20:35.747  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.747  3938  3988 I jxcore-log: 
08-17 15:20:35.748  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:20:35.748  3938  3988 I jxcore-log: 
,08-17 15:20:35.748  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-17 15:20:35.748  3938  3988 I jxcore-log: 
08-17 15:20:35.749  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-17 15:20:35.749  3938  3988 I jxcore-log: 
,08-17 15:20:35.749  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:20:35.749  3938  3988 I jxcore-log: 
08-17 15:20:35.750  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:20:35.750  3938  3988 I jxcore-log: 
,08-17 15:20:35.752  3938  3988 I jxcore-log: My device name is: motorola-Nexus 6
08-17 15:20:35.752  3938  3988 I jxcore-log: 
,08-17 15:20:35.785  3938  4418 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 491, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-17 15:20:36.226   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244923, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 15:20:38.011  3938  3988 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-17 15:20:38.011  3938  3988 I jxcore-log: 
,08-17 15:20:38.025  3938  3988 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-17 15:20:38.027  3938  3988 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-17 15:20:38.027  3938  3988 I jxcore-log: 
,08-17 15:20:39.828  3890  4422 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 15:20:39.854  3890  4423 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 15:20:39.884  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:20:39.887  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:20:39.929  1500  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:20:39.929  1500  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 15:20:39.929  1500  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:20:39.929  1500  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:20:39.976  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:20:39.981  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:20:40.019  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:20:40.019  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 15:20:40.019  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:20:40.019  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:20:40.048  3890  4423 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 15:20:40.049  3890  4422 E BooksSync: Soft error
08-17 15:20:40.049  3890  4422 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 15:20:40.049  3890  4422 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 15:20:40.049  3890  4422 E BooksSync: Sync error
08-17 15:20:40.049  3890  4422 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 15:20:40.049  3890  4422 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 15:20:40.050  3890  4422 I BooksSync: Finished books sync
,08-17 15:20:40.062   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 248487, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:20:43.087   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=251784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 15:21:10.475  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:21:10.479  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:21:10.526  1500  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:21:10.526  1500  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 15:21:10.526  1500  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:21:10.526  1500  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:21:10.552  3174  4426 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 15:21:10.552  3174  4426 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at blb.a(PG:3937)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at czp.a(PG:18188)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:21:10.552  3174  4426 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	... 12 more
08-17 15:21:10.552  3174  4426 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at fal.a(PG:38)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:21:10.552  3174  4426 E HttpOperation: 	... 14 more
,08-17 15:21:10.639  1500  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:21:10.639  1500  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 15:21:10.639  1500  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:21:10.639  1500  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:21:10.665  3174  4426 E HttpOperation: [getmobileexperiments] Unexpected exception,
08-17 15:21:10.665  3174  4426 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at hec.a(PG:42)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at hee.a(PG:102)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at czr.a(PG:65)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at kka.a(PG:108)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at czp.a(PG:19176)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:21:10.665  3174  4426 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	... 15 more
08-17 15:21:10.665  3174  4426 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at fal.a(PG:38)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:21:10.665  3174  4426 E HttpOperation: 	... 17 more
,08-17 15:21:10.665  3174  4426 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 15:21:10.665  3174  4426 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at hec.a(PG:42)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at hee.a(PG:102)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at czr.a(PG:65)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at kka.a(PG:108)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	... 15 more
08-17 15:21:10.665  3174  4426 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at fal.a(PG:38)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 15:21:10.665  3174  4426 E ExperimentLoader: 	... 17 more
,08-17 15:21:10.778   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 250724, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:21:11.246   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=279943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 15:21:20.367   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 15:21:40.907  3246  4434 V KeepSync: Connecting to GoogleApiClient
08-17 15:21:40.907   874  1599 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 15:21:40.976  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:21:40.979  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:21:41.027  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-17 15:21:41.028  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-17 15:21:41.028  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:21:41.028  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:21:41.053  1713  4435 V BaseAuthAsyncOperation: access token request failed
,08-17 15:21:41.054  3246  4434 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 15:21:41.132  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 15:21:41.132  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 15:21:41.133  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:21:41.133  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:21:41.163  3246  4434 E KeepSync: IOException
08-17 15:21:41.163  3246  4434 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 15:21:41.163  3246  4434 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:21:41.163  3246  4434 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 15:21:41.163  3246  4434 E KeepSync: 	... 10 more
,08-17 15:21:41.163  3246  4434 W KeepSync: Sync result 2
,08-17 15:21:41.176   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 285012, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:21:48.473   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=317170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 15:21:55.767   874  4378 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 15:22:11.373  3890  4447 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 15:22:11.471  3890  4449 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 15:22:11.482  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:11.484  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:11.516  1500  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:22:11.516  1500  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 15:22:11.516  1500  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:22:11.516  1500  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:11.543  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:11.545  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:11.567  1500  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 15:22:11.567  1500  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 15:22:11.567  1500  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:22:11.567  1500  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:11.596  3890  4449 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 15:22:11.598  3890  4447 E BooksSync: Soft error
08-17 15:22:11.598  3890  4447 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 15:22:11.598  3890  4447 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 15:22:11.598  3890  4447 E BooksSync: Sync error
08-17 15:22:11.598  3890  4447 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 15:22:11.598  3890  4447 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 15:22:11.599  3890  4447 I BooksSync: Finished books sync
,08-17 15:22:11.616   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 312314, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:22:11.627  1500  2297 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:22:11.627  1500  2297 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 15:22:11.627  1500  2297 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:22:11.627  1500  2297 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:11.647  3174  4448 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 15:22:11.647  3174  4448 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at blb.a(PG:3937)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at czp.a(PG:18188)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:22:11.647  3174  4448 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	... 12 more
08-17 15:22:11.647  3174  4448 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at fal.a(PG:38)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:22:11.647  3174  4448 E HttpOperation: 	... 14 more
,08-17 15:22:11.699  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:22:11.699  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 15:22:11.699  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:22:11.699  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:11.713  3174  4448 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 15:22:11.713  3174  4448 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at hec.a(PG:42)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at hee.a(PG:102)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at czr.a(PG:65)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at kka.a(PG:108)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at czp.a(PG:19176)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:22:11.713  3174  4448 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	... 15 more
08-17 15:22:11.713  3174  4448 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at fal.a(PG:38)
08-17 15:22:11.713  3174  4448 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:22:11.713  3174  4448 E HttpOperation: ,	... 17 more
,08-17 15:22:11.714  3174  4448 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 15:22:11.714  3174  4448 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at hec.a(PG:42)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at hee.a(PG:102)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at czr.a(PG:65)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at kka.a(PG:108)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	... 15 more
08-17 15:22:11.714  3174  4448 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at fal.a(PG:38)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 15:22:11.714  3174  4448 E ExperimentLoader: 	... 17 more
,08-17 15:22:11.817   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 310665, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:22:16.081  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:16.159  1500  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-17 15:22:16.160  1500  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-17 15:22:16.160  1500  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:22:16.160  1500  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:16.214  1500  2012 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 15:22:16.214  1500  2012 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 15:22:16.214  1500  2012 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 15:22:16.214  1500  2012 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-17 15:22:16.214  1500  2012 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-17 15:22:16.214  1500  2012 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-17 15:22:16.214  1500  2012 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-17 15:22:16.232  3683  3719 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 15:22:16.232  3683  3719 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-17 15:22:16.232  3683  3719 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-17 15:22:16.232  3683  3719 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-17 15:22:16.232  3683  3719 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-17 15:22:16.232  3683  3719 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-17 15:22:16.232  3683  3719 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-17 15:22:41.998  3246  4455 V KeepSync: Connecting to GoogleApiClient
,08-17 15:22:42.000   874  1988 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 15:22:42.067  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:42.069  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:22:42.114  1500  2296 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-17 15:22:42.114  1500  2296 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-17 15:22:42.114  1500  2296 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:22:42.114  1500  2296 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:42.140  1713  4456 V BaseAuthAsyncOperation: access token request failed
,08-17 15:22:42.141  3246  4455 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 15:22:42.213  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 15:22:42.213  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 15:22:42.213  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:22:42.213  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:22:42.237  3246  4455 E KeepSync: IOException
08-17 15:22:42.237  3246  4455 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 15:22:42.237  3246  4455 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:22:42.237  3246  4455 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 15:22:42.237  3246  4455 E KeepSync: 	... 10 more
08-17 15:22:42.237  3246  4455 W KeepSync: Sync result 2
,08-17 15:22:42.251   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 342469, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:23:14.489  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:23:14.491  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:23:14.538  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:23:14.538  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 15:23:14.538  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:23:14.539  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:23:14.562  3174  4459 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 15:23:14.562  3174  4459 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at blb.a(PG:3937)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at czp.a(PG:18188)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:23:14.562  3174  4459 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	... 12 more
08-17 15:23:14.562  3174  4459 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at fal.a(PG:38)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:23:14.562  3174  4459 E HttpOperation: 	... 14 more
,08-17 15:23:14.657  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:23:14.657  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 15:23:14.657  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:23:14.657  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:23:14.703  3174  4459 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 15:23:14.703  3174  4459 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at hec.a(PG:42)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at hee.a(PG:102)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at czr.a(PG:65)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at kka.a(PG:108)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at czp.a(PG:19176)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:23:14.703  3174  4459 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	... 15 more
08-17 15:23:14.703  3174  4459 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at fal.a(PG:38)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:23:14.703  3174  4459 E HttpOperation: 	... 17 more
,08-17 15:23:14.703  3174  4459 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 15:23:14.703  3174  4459 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at hec.a(PG:42)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at hee.a(PG:102)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at czr.a(PG:65)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at kka.a(PG:108)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
,08-17 15:23:14.703  3174  4459 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	... 15 more
08-17 15:23:14.703  3174  4459 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at fal.a(PG:38)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 15:23:14.703  3174  4459 E ExperimentLoader: 	... 17 more
,08-17 15:23:14.863   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 402895, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:23:47.620  3246  4462 V KeepSync: Connecting to GoogleApiClient
08-17 15:23:47.620   874  3316 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 15:23:47.703  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:23:47.706  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:23:47.751  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-17 15:23:47.751  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 15:23:47.751  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:23:47.752  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:23:47.762  1713  4463 V BaseAuthAsyncOperation: access token request failed
08-17 15:23:47.763  3246  4462 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 15:23:47.793  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-17 15:23:47.793  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 15:23:47.793  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:23:47.793  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:23:47.803  3246  4462 E KeepSync: IOException
08-17 15:23:47.803  3246  4462 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 15:23:47.803  3246  4462 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 15:23:47.803  3246  4462 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 15:23:47.803  3246  4462 E KeepSync: 	... 10 more
08-17 15:23:47.804  3246  4462 W KeepSync: Sync result 2
,08-17 15:23:47.808   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 436139, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:24:10.497  3938  3988 I jxcore-log: TAP version 13
08-17 15:24:10.497  3938  3988 I jxcore-log: 
,08-17 15:24:10.502  3938  3988 I jxcore-log: # setup
08-17 15:24:10.502  3938  3988 I jxcore-log: 
,08-17 15:24:10.761  3938  3988 I jxcore-log: # 1. onPeerLost calls jxcore
08-17 15:24:10.761  3938  3988 I jxcore-log: 
,08-17 15:24:10.916  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:24:10.916  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a64ae4 added. We now have 3 listener(s)
,08-17 15:24:10.918  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:24:10.918  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:24:10.918  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:24:10.918  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:24:10.919  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f78b4d added. We now have 4 listener(s)
08-17 15:24:10.919  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:24:10.920  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:24:10.922  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:24:10.930  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:24:10.933  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:24:10.933  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:24:10.936  3938  3988 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
08-17 15:24:10.936  3938  3988 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-17 15:24:10.938  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:24:10.944  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:24:12.940  3938  3988 I jxcore-log: onPeerLost
08-17 15:24:12.940  3938  3988 I jxcore-log: 
,08-17 15:24:12.944  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:24:12.944  3938  3988 I jxcore-log: 
,08-17 15:24:12.964  3938  3988 I jxcore-log: # teardown
08-17 15:24:12.964  3938  3988 I jxcore-log: 
,08-17 15:24:12.976  3938  3988 I jxcore-log: ok 1 check if callback was fired by onPeerLost
08-17 15:24:12.976  3938  3988 I jxcore-log: 
,08-17 15:24:12.977  3938  3988 I jxcore-log: ok 2 check if peerAvailable is false
08-17 15:24:12.977  3938  3988 I jxcore-log: 
,08-17 15:24:13.140  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 15:24:13.140  3938  3988 I jxcore-log: 
,08-17 15:24:13.145  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 15:24:13.145  3938  3988 I jxcore-log: 
,08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:24:13.160  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:24:13.165  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:24:13.168  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 15:24:13.168  3938  3988 I jxcore-log: 
,08-17 15:24:13.172  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 15:24:13.172  3938  3988 I jxcore-log: 
,08-17 15:24:13.178  3938  3988 I jxcore-log: # setup
08-17 15:24:13.178  3938  3988 I jxcore-log: 
,08-17 15:24:13.182  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:24:13.182  3938  3988 I jxcore-log: 
,08-17 15:24:13.338  3938  3988 I jxcore-log: # 2. onPeerDiscovered calls jxcore
08-17 15:24:13.338  3938  3988 I jxcore-log: 
,08-17 15:24:13.473  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:24:13.473  3938  3988 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8b13 added. We now have 4 listener(s)
,08-17 15:24:13.478  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:24:13.478  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:24:13.478  3938  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:24:13.478  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:24:13.478  3938  3988 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ef3150 added. We now have 5 listener(s)
08-17 15:24:13.478  3938  3988 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:24:13.479  3938  3988 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:24:13.486  3938  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:24:13.496  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:24:13.499  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:24:13.500  3938  3988 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:24:13.501  3938  3988 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-17 15:24:13.503  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:24:13.506  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:24:15.503  3938  3988 I jxcore-log: onPeerDiscovered
08-17 15:24:15.503  3938  3988 I jxcore-log: 
,08-17 15:24:15.507  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:24:15.507  3938  3988 I jxcore-log: 
,08-17 15:24:15.522  3938  3988 I jxcore-log: # teardown
08-17 15:24:15.522  3938  3988 I jxcore-log: 
,08-17 15:24:15.529  3938  3988 I jxcore-log: ok 3 check if callback was fired by onPeerDiscovered
08-17 15:24:15.529  3938  3988 I jxcore-log: 
,08-17 15:24:15.530  3938  3988 I jxcore-log: ok 4 check if peerAvailable is true
08-17 15:24:15.530  3938  3988 I jxcore-log: 
,08-17 15:24:15.687  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 15:24:15.687  3938  3988 I jxcore-log: 
,08-17 15:24:15.692  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 15:24:15.692  3938  3988 I jxcore-log: 
,08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:24:15.705  3938  3988 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:24:15.708  3938  3988 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:24:15.710  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 15:24:15.710  3938  3988 I jxcore-log: 
,08-17 15:24:15.711  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 15:24:15.711  3938  3988 I jxcore-log: 
,08-17 15:24:15.714  3938  3988 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:24:15.714  3938  3988 I jxcore-log: 
,08-17 15:24:16.281  3938  3988 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 15:24:16.281  3938  3988 I jxcore-log: 
,08-17 15:24:16.965  4465  4465 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 15:24:16.970  4465  4465 D AndroidRuntime: CheckJNI is OFF
,08-17 15:24:17.013  4465  4465 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 15:24:17.062  4465  4465 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 15:24:17.084  4465  4465 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 15:24:17.093   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 15:24:17.094   874   887 I ActivityManager: Killing 3938:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 15:24:17.210   874   897 W PackageSettings: Skipping PackageSetting{b2e39e1 com.example.hello/10273} due to missing metadata
,08-17 15:24:17.254   874  1983 D GraphicsStats: Buffer count: 2
,08-17 15:24:17.255   874  1599 I WindowState: WIN DEATH: Window{14a33da u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-17 15:24:17.256   874  1308 D WifiService: Client connection lost with reason: 4
08-17 15:24:17.258   874   897 I art     : Starting a blocking GC Explicit
,08-17 15:24:17.317   874   887 E libprocessgroup: failed to kill 1 processes for processgroup 3938
,08-17 15:24:17.318   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-17 15:24:17.318   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-17 15:24:17.320   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-17 15:24:17.320   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 15:24:17.320   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.320   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.320   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:24:17.320   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-17 15:24:17.320   874   887 I ActivityManager:   Force finishing activity ActivityRecord{69a4db3 u0 com.test.thalitest/.MainActivity t2}
,08-17 15:24:17.344   874   897 I art     : Explicit concurrent mark sweep GC freed 19705(1376KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.527ms total 84.912ms
,08-17 15:24:17.346   874  1988 W ActivityManager: Spurious death for ProcessRecord{fdcc4da 0:com.test.thalitest/u0a0}, curProc for 3938: null
,08-17 15:24:17.372   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 15:24:17.374  4465  4465 I art     : System.exit called, status: 0
,08-17 15:24:17.374  4465  4465 I AndroidRuntime: VM exiting with result code 0.
,08-17 15:24:17.387   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 15:24:17.425   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 15:24:17.430  4320  4320 D BluetoothMapAppObserver: onReceive
,08-17 15:24:17.430  4320  4320 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-17 15:24:17.435   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 15:24:17.435  1882  2260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 15:24:17.436  1869  1869 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 15:24:17.437  3781  3781 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 15:24:17.465  1869  4477 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 15:24:17.471   874  1385 I ActivityManager: Start proc 4479:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 15:24:17.479  1869  4477 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-17 15:24:17.479  1869  4477 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-17 15:24:17.479  1869  4477 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-17 15:24:17.479  1869  4477 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-17 15:24:17.479  1869  4477 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-17 15:24:17.480  1869  4477 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-17 15:24:17.481  1869  4477 I Decoder : createOrResetDecoder
,08-17 15:24:17.487  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 15:24:17.492   874  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-17 15:24:17.508  1500  1500 I ConfigService: onCreate
,08-17 15:24:17.512  4479  4479 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 15:24:17.523  1500  4491 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 15:24:17.523  1500  4491 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 15:24:17.523  1500  4491 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-17 15:24:17.527  1500  4491 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-17 15:24:17.528   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 15:24:17.532   874  1984 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3938 uid 10000
,08-17 15:24:17.533  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-17 15:24:17.545  1954  2051 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 15:24:17.545   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-17 15:24:17.545   874   886 E PackageManager: Failed to write settings, restoring backup
08-17 15:24:17.545   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 15:24:17.545   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 15:24:17.545   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 15:24:17.545   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 15:24:17.545   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 15:24:17.545   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.545   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.545   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:24:17.549   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-17 15:24:17.549   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 15:24:17.549   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:24:17.549   874   887 E DropBoxManagerService: 	... 13 more
,08-17 15:24:17.554  1869  4477 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 15:24:17.560   874  1988 I ActivityManager: Start proc 4493:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-17 15:24:17.560  1954  2051 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 15:24:17.560  1954  2051 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1954
08-17 15:24:17.560  1954  2051 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.560  1954  2051 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:24:17.562   874  1385 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 15:24:17.563   874  4498 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:24:17.563   874  4498 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:24:17.563   874  4498 E DropBoxManagerService: 	... 5 more
,08-17 15:24:17.569  1954  2051 I Process : Sending signal. PID: 1954 SIG: 9
,08-17 15:24:17.615  4479  4479 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 15:24:17.621  1869  4477 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-17 15:24:17.623   874  1385 D GraphicsStats: Buffer count: 1
08-17 15:24:17.623   874  1984 I WindowState: WIN DEATH: Window{27a446c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 15:24:17.632  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-17 15:24:17.633  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 15:24:17.634   874  1978 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1954) has died
,08-17 15:24:17.635   874  1978 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-17 15:24:17.637   874  1978 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 15:24:17.647  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-17 15:24:17.647  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-17 15:24:17.647  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-17 15:24:17.647  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-17 15:24:17.648  1869  4477 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-17 15:24:17.648  1869  4477 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-17 15:24:17.648  1869  4477 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-17 15:24:17.649  1869  4477 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 15:24:17.649  1869  4477 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-17 15:24:17.649  1869  4477 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 15:24:17.653   874   887 I ActivityManager: Start proc 4510:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 15:24:17.667  4479  4506 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.667  4479  4506 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.667  4479  4506 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:24:17.671  4479  4523 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 15:24:17.676   874  1984 I ActivityManager: Start proc 4524:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-17 15:24:17.708  4524  4524 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 15:24:17.708  4510  4510 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:24:17.708  4510  4510 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:24:17.708  4510  4510 D AndroidRuntime: Shutting down VM
,08-17 15:24:17.716  4510  4510 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:24:17.716  4510  4510 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4510
08-17 15:24:17.716  4510  4510 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:24:17.716  4510  4510 E AndroidRuntime: 	... 10 more
,08-17 15:24:17.717   874  1685 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 15:24:17.718  4510  4510 I Process : Sending signal. PID: 4510 SIG: 9
08-17 15:24:17.718   874  4537 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:24:17.718   874  4537 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:24:17.718   874  4537 E DropBoxManagerService: 	... 5 more
,08-17 15:24:17.731  1713  4536 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-17 15:24:17.732  1713  4536 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-17 15:24:17.736  1713  4536 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-17 15:24:17.737  1713  4536 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-17 15:24:17.746   874  1988 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4510) has died
,08-17 15:24:17.747   874  1988 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 15:24:17.761   874   887 I ActivityManager: Start proc 4540:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 15:24:17.765   874   885 I ActivityManager: Killing 3831:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-17 15:24:17.774  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-17 15:24:17.775  1500  1500 D AndroidRuntime: Shutting down VM
08-17 15:24:17.775  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:24:17.775  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
08-17 15:24:17.775  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 15:24:17.775  1500  1500 E AndroidRuntime: 	... 8 more
,08-17 15:24:17.803  4479  4506 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-17 15:24:17.809  4479  4523 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.809  4479  4523 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:24:17.810  4479  4523 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 15:24:17.810  4479  4523 E AndroidRuntime: Process: android.process.acore, PID: 4479
08-17 15:24:17.810  4479  4523 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:24:17.810  4479  4523 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:24:17.812  4479  4506 I Process : Sending signal. PID: 4479 SIG: 9
,08-17 15:24:17.823   874  4554 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:24:17.823   874  4554 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:24:17.823   874  4554 E DropBoxManagerService: 	... 5 more
,08-17 15:24:17.825   874  4553 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:24:17.825   874  4553 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:24:17.825   874  4553 E DropBoxManagerService: 	... 5 more
,08-17 15:24:17.832  1500  1500 I Process : Sending signal. PID: 1500 SIG: 9
08-17 15:24:17.850   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
