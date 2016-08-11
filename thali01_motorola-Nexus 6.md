#### Test 807613740d32244_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 11:06:11.114  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:11.124  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 11:06:11.129  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 11:06:11.165  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-11 11:06:11.165  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 11:06:11.165  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:11.165  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 11:06:11.192  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-11 11:06:11.192  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:06:11.192  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-11 11:06:11.752  3621  3621 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 11:06:11.757  3621  3621 D AndroidRuntime: CheckJNI is OFF
08-11 11:06:11.812  3621  3621 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 11:06:11.870  3621  3621 I Radio-JNI: register_android_hardware_Radio DONE
08-11 11:06:11.899  3621  3621 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 11:06:11.907   872  1724 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 11:06:11.944  1826  1856 W SearchService: Abort, client detached.
08-11 11:06:11.952  3621  3621 D AndroidRuntime: Shutting down VM
08-11 11:06:11.957  1826  2159 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@66b395
08-11 11:06:11.957  1826  1826 I HotwordDetector: Closing mic
08-11 11:06:11.959  1826  2168 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 11:06:11.967   872  1862 I ActivityManager: Start proc 3631:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 11:06:12.012   376  2170 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 11:06:12.015   376  2170 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 11:06:12.022   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 11:06:12.024  1826  2166 I MicroRecognitionRnrImpl: Detection finished
08-11 11:06:12.024  1826  2164 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 11:06:12.042  3631  3631 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 11:06:12.068  3631  3631 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 11:06:12.078  3631  3631 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3086-3092)
08-11 11:06:12.078  3631  3631 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 11:06:12.090  3631  3631 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6323669}
08-11 11:06:12.090  3631  3631 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 11:06:12.091  3631  3631 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 11:06:12.099  3631  3631 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 11:06:12.100  3631  3631 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 11:06:12.112  3631  3631 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 11:06:12.123  3631  3631 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 11:06:12.123  3631  3631 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 11:06:12.123  3631  3631 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 11:06:12.123  3631  3631 I Adreno  : Build Date                       : 10/20/15
08-11 11:06:12.123  3631  3631 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 11:06:12.123  3631  3631 I Adreno  : Local Branch                     : M14
08-11 11:06:12.123  3631  3631 I Adreno  : Remote Branch                    : 
08-11 11:06:12.123  3631  3631 I Adreno  : Remote Branch                    : 
08-11 11:06:12.123  3631  3631 I Adreno  : Reconstruct Branch               : 
,08-11 11:06:12.171   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4dc369:true
,08-11 11:06:12.221  3631  3631 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 11:06:12.233  3631  3631 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 11:06:12.270  3631  3669 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 11:06:12.277  3631  3656 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 11:06:12.304  3631  3669 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 11:06:12.359   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +410ms
,08-11 11:06:12.363  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-11 11:06:12.382   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-11 11:06:12.454  3631  3631 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3631
,08-11 11:06:12.599  3631  3631 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 11:06:12.785   872  1714 I ActivityManager: Killing 3074:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 11:06:12.806  3631  3671 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1678837456
,08-11 11:06:12.812  3631  3671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 11:06:12.812  3631  3671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 11:06:12.812  3631  3671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 11:06:12.812  3631  3671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 11:06:12.812  3631  3671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 11:06:12.812  3631  3671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fdf374 added. We now have 1 listener(s)
,08-11 11:06:12.816  3631  3671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 11:06:12.816  3631  3671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 11:06:12.817  3631  3671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 11:06:12.817  3631  3671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 11:06:12.820  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 11:06:12.821  3631  3671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe78e3 added. We now have 1 listener(s)
,08-11 11:06:12.821  3631  3671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:06:12.824   872  1308 D WifiService: New client listening to asynchronous messages
,08-11 11:06:12.826  3631  3671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 11:06:12.826  3631  3671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 11:06:12.826  3631  3671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 11:06:12.826  3631  3671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-11 11:06:12.826  3631  3671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 11:06:12.843   872  1714 I ActivityManager: Killing 2938:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-11 11:06:12.882  3631  3671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:12.882  3631  3671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 11:06:12.886  3631  3671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:12.886  3631  3671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 11:06:12.886  3631  3671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 11:06:12.887  3631  3671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:06:12.887  3631  3671 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 11:06:12.986  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:12.990  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:12.994  3631  3631 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 11:06:13.874  3631  3679 W jxcore-log: Initializing JXcore engine
08-11 11:06:13.874  3631  3679 W jxcore-log: JXcore engine is ready
,08-11 11:06:13.930  3679  3679 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 11:06:13.930  3679  3679 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12175]" dev="sockfs" ino=12175 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 11:06:13.930  3679  3679 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 11:06:13.930  3679  3679 W Thread-325: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25910]" dev="sockfs" ino=25910 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 11:06:13.946  3631  3679 W jxcore-log: Starting JXcore engine
,08-11 11:06:13.979  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:06:13.979  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 11:06:13.979  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:06:13.979  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:13.996  2477  3682 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:06:13.996  2477  3682 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:06:13.996  2477  3682 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	... 12 more
08-11 11:06:13.996  2477  3682 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at fal.a(PG:38)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:06:13.996  2477  3682 E HttpOperation: 	... 14 more
,08-11 11:06:14.024  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:06:14.024  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 11:06:14.024  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:06:14.024  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:14.036  2477  3682 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 11:06:14.036  2477  3682 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at hec.a(PG:42)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at hee.a(PG:102)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at czr.a(PG:65)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at kka.a(PG:108)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:06:14.036  2477  3682 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	... 15 more
08-11 11:06:14.036  2477  3682 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at fal.a(PG:38)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:06:14.036  2477  3682 E HttpOperation: 	... 17 more
,08-11 11:06:14.036  2477  3682 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:06:14.036  2477  3682 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	... 15 more
08-11 11:06:14.036  2477  3682 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:06:14.036  2477  3682 E ExperimentLoader: 	... 17 more
,08-11 11:06:14.059  3631  3679 W jxcore-log: Platform android
08-11 11:06:14.059  3631  3679 W jxcore-log: 
,08-11 11:06:14.060  3631  3679 W jxcore-log: Process ARCH arm
08-11 11:06:14.060  3631  3679 W jxcore-log: 
,08-11 11:06:14.133   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 124799, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:06:14.319  3631  3679 I jxcore-log: JXcore Cordova bridge is ready!
08-11 11:06:14.319  3631  3679 I jxcore-log: 
,08-11 11:06:14.320  3631  3679 W jxcore-log: JXcore engine is started
,08-11 11:06:14.324  3631  3671 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 11:06:14.327  3631  3631 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 11:06:29.963  3631  3679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 11:06:29.963  3631  3679 I jxcore-log: 
,08-11 11:06:29.965  3631  3679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 11:06:29.965  3631  3679 I jxcore-log: 
,08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:29.975  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:29.981  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:06:29.983  3631  3679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 11:06:29.983  3631  3679 I jxcore-log: 
,08-11 11:06:29.984  3631  3679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 11:06:29.984  3631  3679 I jxcore-log: 
,08-11 11:06:30.359  3631  3679 I jxcore-log: Running unit tests
08-11 11:06:30.359  3631  3679 I jxcore-log: 
,08-11 11:06:30.360  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 11:06:30.360  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54bed22 added. We now have 2 listener(s)
,08-11 11:06:30.361  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 11:06:30.361  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 11:06:30.361  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 11:06:30.362  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:06:30.362  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de083b3 added. We now have 2 listener(s)
08-11 11:06:30.362  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:06:30.363  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 11:06:30.368  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:30.378  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:30.383  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:06:30.383  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 11:06:30.384  3631  3679 D ExecuteNativeTests: Running unit tests
,08-11 11:06:30.396  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:30.404  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:30.488  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 11:06:30.489  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 added. We now have 3 listener(s)
08-11 11:06:30.490  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 11:06:30.490  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 11:06:30.490  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 11:06:30.490  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:06:30.490  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e added. We now have 3 listener(s)
08-11 11:06:30.490  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 11:06:30.491  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 11:06:30.496  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:30.512  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:30.513  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:30.513  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-11 11:06:30.516  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 11:06:30.517  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 11:06:30.517  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 11:06:30.517  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 11:06:30.519  3631  3679 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-11 11:06:30.519  3631  3679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 11:06:30.519  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-11 11:06:30.519  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 11:06:30.519  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-11 11:06:30.519  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 11:06:30.520  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:30.520  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:30.520  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:30.520  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:30.521  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:30.521  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 11:06:30.521  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 11:06:30.521  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 removed from the list
08-11 11:06:30.521  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:30.521  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e removed from the list
08-11 11:06:30.522  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:30.523  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:06:30.523  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.523  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:30.524  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.525  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:30.525  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:06:30.525  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:30.525  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:30.527  3631  3679 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-11 11:06:30.527  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:30.527  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:30.527  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:30.528  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:30.528  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:30.528  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.528  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:30.528  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:30.528  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:30.528  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:30.528  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:30.528  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.528  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:30.528  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.529  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:30.529  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:30.529  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:30.529  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 11:06:30.534  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 11:06:30.535  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 11:06:30.535  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:30.535  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:30.535  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:30.536  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:30.536  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:30.536  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.536  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:30.536  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:30.536  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:30.536  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:30.536  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:30.536  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.536  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:30.536  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:30.539  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:30.539  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:30.539  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:30.541  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:30.543  3631  3679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 11:06:30.544  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:30.556  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 11:06:30.559  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:30.560  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:06:30.560  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 11:06:30.560  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 11:06:30.562  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 11:06:30.562  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:06:30.562  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 11:06:30.563  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:30.566  3631  3679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 11:06:30.566  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 11:06:30.567  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:30.572  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 11:06:30.575  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 11:06:30.575  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 11:06:30.579  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-11 11:06:30.581  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-11 11:06:30.582  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 11:06:30.582  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 11:06:30.583  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 11:06:30.584  3631  3679 D BluetoothAdapter: STATE_ON
08-11 11:06:30.589  2548  2742 D BtGatt.GattService: registerClient() - UUID=6d60e683-15b6-42a5-b706-60ec074d178d
08-11 11:06:30.589  2548  2601 D BtGatt.GattService: onClientRegistered() - UUID=6d60e683-15b6-42a5-b706-60ec074d178d, clientIf=5
08-11 11:06:30.590  3631  3643 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 11:06:30.591  2548  2565 D BtGatt.GattService: start scan with filters
08-11 11:06:30.595  2548  2605 D BtGatt.ScanManager: handling starting scan
08-11 11:06:30.596  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 11:06:30.596  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 11:06:30.596  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 11:06:30.596  2548  2605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
08-11 11:06:30.596  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-11 11:06:30.603  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 11:06:30.604  2548  2601 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 11:06:30.604  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:30.604  2548  2605 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-11 11:06:30.604  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 11:06:30.605  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 11:06:30.610  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-11 11:06:30.613  2548  2601 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 11:06:30.613  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:30.614  2548  2605 D BtGatt.ScanManager: Starting BLE batch scan
08-11 11:06:30.614  2548  2605 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 11:06:30.621  2548  2601 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 11:06:30.621  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:30.623  3631  3679 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 11:06:30.627  2548  2601 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 11:06:30.627  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:31.106  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-11 11:06:31.107  3631  3631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 11:06:31.107  3631  3631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 11:06:32.134  2548  2548 D BtGatt.ScanManager: awakened up at time 143148
,08-11 11:06:32.137  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:32.187  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 11:06:32.187  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:32.188  2548  2601 D BtGatt.GattService: current time is 143202435994
,08-11 11:06:32.189  2548  2601 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -88, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -106, -15, -31, -128, 20, -7, 1, 0, -103, 5, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 91, 82, -43, 2, 2, -29, 21, 62, 73, 24, 92, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -92, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,08-11 11:06:32.194  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 11:06:32.197  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 11:06:32.198  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 11:06:32.199  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 11:06:32.200  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 91, 82, -43, 2, 2, -29, 21, 62, 73, 24, 92, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-11 11:06:32.202  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 11:06:33.702  2548  2548 D BtGatt.ScanManager: awakened up at time 144716
,08-11 11:06:33.704  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:33.742  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 11:06:33.742  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:33.784   872  1393 I ActivityManager: Start proc 3695:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-11 11:06:33.818  3695  3695 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-11 11:06:33.872  3695  3707 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 11:06:33.875  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:33.882  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:33.884  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:33.919  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:06:33.919  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 11:06:33.919  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:33.919  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:33.932  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:06:33.932  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:06:33.933  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-11 11:06:33.952  3695  3707 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 11:06:33.998  3695  3707 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 11:06:34.000  3720  3720 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-975769591.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-975769591.dex
,08-11 11:06:34.021  3695  3695 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-11 11:06:34.038  3720  3720 I dex2oat : dex2oat took 38.803ms (threads: 4) arena alloc=209KB java alloc=37KB native alloc=1642KB free=1685KB
,08-11 11:06:34.172  3695  3695 W InstanceID/Rpc: Found 10011
,08-11 11:06:34.234   872  1705 I ActivityManager: Start proc 3773:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-11 11:06:34.240   872   883 I ActivityManager: Killing 2840:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-11 11:06:34.303  2548  2548 D BtGatt.ScanManager: awakened up at time 145317
,08-11 11:06:34.303  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:34.319  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-11 11:06:34.320  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:34.320  2548  2601 D BtGatt.GattService: current time is 145334531727
,08-11 11:06:34.321  2548  2601 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -69, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 11:06:34.321  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 11:06:34.322  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-11 11:06:34.323  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 11:06:34.343  3773  3773 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-11 11:06:34.384  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:34.390  3773  3773 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-11 11:06:34.474  1492  3803 I VacuumService: Vacuum at: now=1470906394474 tag=VacuumService
,08-11 11:06:34.488  3773  3802 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:06:34.522  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 11:06:34.523  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 11:06:34.523  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:06:34.523  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 11:06:34.540  3773  3802 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 11:06:34.551   872  1862 I ActivityManager: Killing 2381:com.google.android.talk/u0a61 (adj 15): empty #17
,08-11 11:06:34.823  2548  2548 D BtGatt.ScanManager: awakened up at time 145837
,08-11 11:06:34.823  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:34.852  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 11:06:34.852  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:34.852  1492  3804 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
08-11 11:06:34.853  2548  2601 D BtGatt.GattService: current time is 145867126728
08-11 11:06:34.853  2548  2601 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-11 11:06:34.854  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 11:06:34.858  1492  3804 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-11 11:06:34.901  1492  3804 W Uploader:  no longer exists, so no auth token.
,08-11 11:06:35.631  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:35.631  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 11:06:35.631  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 11:06:35.632  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:35.632  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 11:06:35.632  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-11 11:06:35.633  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 11:06:35.633  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 11:06:35.633  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 11:06:35.636  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 11:06:35.636  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 11:06:35.638  3631  3679 D BluetoothAdapter: STATE_ON
,08-11 11:06:35.640  2548  2565 D BtGatt.GattService: stopScan() - queue size =1
,08-11 11:06:35.642  2548  2753 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 11:06:35.643  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 11:06:35.643  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 11:06:35.643  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-11 11:06:35.644  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-11 11:06:35.644  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 11:06:35.650  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 11:06:35.652  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-11 11:06:35.652  2548  2548 D BtGatt.ScanManager: awakened up at time 146666
,08-11 11:06:35.652  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 11:06:35.654  2548  2601 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 11:06:35.654  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:35.655  2548  2605 D BtGatt.ScanManager: stopping BLe Batch
08-11 11:06:35.656  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 11:06:35.657  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 11:06:35.659  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:06:35.660  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:06:35.660  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:35.660  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 11:06:35.660  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:35.661  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 11:06:35.661  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:35.661  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:35.662  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:35.662  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:35.663  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:35.668  2548  2601 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 11:06:35.668  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:35.668  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:35.673  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 11:06:35.673  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:35.949  1492  3804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 11:06:35.950  1492  3804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 11:06:35.950  1492  3804 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:35.950  1492  3804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:35.972  1492  3804 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 11:06:35.972  1492  3804 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 11:06:35.972  1492  3804 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 11:06:36.161  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 11:06:36.610  1492  3804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 11:06:36.611  1492  3804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-11 11:06:36.611  1492  3804 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:36.612  1492  3804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:36.661  1492  3804 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 11:06:36.661  1492  3804 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 11:06:36.661  1492  3804 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 11:06:36.850  1492  3804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-11 11:06:36.850  1492  3804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-11 11:06:36.851  1492  3804 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:06:36.851  1492  3804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:36.903  1492  3804 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 11:06:36.903  1492  3804 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 11:06:36.903  1492  3804 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 11:06:39.139   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-11 11:06:39.147  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-11 11:06:39.167   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 11:06:39.167   872   892 I Adreno  : Build Date                       : 10/20/15
08-11 11:06:39.167   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 11:06:39.167   872   892 I Adreno  : Local Branch                     : M14
08-11 11:06:39.167   872   892 I Adreno  : Remote Branch                    : 
08-11 11:06:39.167   872   892 I Adreno  : Remote Branch                    : 
08-11 11:06:39.167   872   892 I Adreno  : Reconstruct Branch               : 
,08-11 11:06:39.211   281   348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (281 us)
,08-11 11:06:39.276   872  2134 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 11:06:39.854  3631  3631 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-11 11:06:39.854  3631  3631 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-11 11:06:39.890   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-11 11:06:39.893  3631  3631 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c302387 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4a9f5b8, 16908290=android.view.AbsSavedState$1@4a9f5b8}, android:focusedViewId=100}]}]
,08-11 11:06:39.894  3631  3631 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-11 11:06:39.894  3631  3631 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-11 11:06:39.894  3631  3631 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-11 11:06:39.902   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-11 11:06:39.908   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-11 11:06:39.909   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-11 11:06:39.909   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-11 11:06:39.944   872   881 I art     : Background partial concurrent mark sweep GC freed 36817(2MB) AllocSpace objects, 8(196KB) LOS objects, 33% free, 29MB/43MB, paused 968us total 102.240ms
,08-11 11:06:40.140   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 11:06:40.144   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-11 11:06:40.145   872  1334 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-11 11:06:40.149   872   892 I DreamManagerService: Entering dreamland.
,08-11 11:06:40.150   872   892 I PowerManagerService: Dozing...
,08-11 11:06:40.152   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-11 11:06:40.205   376  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-11 11:06:40.205   376  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-11 11:06:40.222   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:06:40.228  1692  3818 D NfcService: Discovery configuration equal, not updating.
,08-11 11:06:40.233   872  1307 E native  : do suspend false
,08-11 11:06:40.245   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-11 11:06:40.265   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:06:40.268   872  1307 E native  : do suspend true
,08-11 11:06:40.343   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-11 11:06:40.343   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-11 11:06:40.664  3631  3679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 11:06:40.673  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:40.686  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:40.693  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:06:40.693  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:06:40.694  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 11:06:40.695  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 11:06:40.696  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 11:06:40.696  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:40.696  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 11:06:40.700  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:40.707  3631  3679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 11:06:40.707  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 11:06:40.708  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:40.720  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 11:06:40.723  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 11:06:40.723  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 11:06:40.734  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 11:06:40.734  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 11:06:40.735  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 11:06:40.737  3631  3679 D BluetoothAdapter: STATE_ON
,08-11 11:06:40.744  2548  2562 D BtGatt.GattService: registerClient() - UUID=ce6b77f9-deb7-4d03-9eb4-259b98a3f7ad
,08-11 11:06:40.746  2548  2601 D BtGatt.GattService: onClientRegistered() - UUID=ce6b77f9-deb7-4d03-9eb4-259b98a3f7ad, clientIf=5
,08-11 11:06:40.747  3631  3643 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 11:06:40.748  2548  2565 D BtGatt.GattService: start scan with filters
,08-11 11:06:40.758  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 11:06:40.759  2548  2605 D BtGatt.ScanManager: handling starting scan
08-11 11:06:40.759  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-11 11:06:40.759  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-11 11:06:40.760  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 11:06:40.770  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 11:06:40.771  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 11:06:40.772  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 11:06:40.776  2548  2601 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 11:06:40.777  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:40.778  2548  2605 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 11:06:40.782  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 11:06:40.790  2548  2601 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 11:06:40.790  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:40.790  2548  2605 D BtGatt.ScanManager: Starting BLE batch scan
08-11 11:06:40.790  2548  2605 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-11 11:06:40.791  3631  3679 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 11:06:40.795  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:40.795  3631  3679 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-11 11:06:40.796  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 11:06:40.796  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 11:06:40.796  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:40.796  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 11:06:40.797  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-11 11:06:40.797  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 11:06:40.797  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 11:06:40.797  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 11:06:40.798  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 11:06:40.798  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-11 11:06:40.800  3631  3679 D BluetoothAdapter: STATE_ON
,08-11 11:06:40.801  2548  2565 D BtGatt.GattService: stopScan() - queue size =1
08-11 11:06:40.803  2548  2742 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 11:06:40.804  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 11:06:40.804  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 11:06:40.805  2548  2601 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 11:06:40.805  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:40.805  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 11:06:40.806  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 11:06:40.806  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 11:06:40.808  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 11:06:40.809  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 11:06:40.809  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 11:06:40.809  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 11:06:40.810  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 11:06:40.812  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-11 11:06:40.813  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 11:06:40.813  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 11:06:40.813  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:40.813  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:40.814  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 11:06:40.814  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:40.814  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:40.814  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list,
08-11 11:06:40.814  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:06:40.815  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:40.816  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:40.816  2548  2601 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 11:06:40.816  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:40.816  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:40.819  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:40.819  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:06:40.819  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:40.820  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:40.822  3631  3679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 11:06:40.825  2548  2601 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 11:06:40.825  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:40.826  2548  2605 D BtGatt.ScanManager: stopping BLe Batch
,08-11 11:06:40.826  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:40.834  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:40.836  2548  2601 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 11:06:40.836  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:40.836  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:40.837  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:06:40.838  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:06:40.838  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 11:06:40.838  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 11:06:40.838  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 11:06:40.838  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:40.838  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 11:06:40.843  3631  3679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 11:06:40.843  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 11:06:40.844  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:40.848  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 11:06:40.849  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:40.850  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 11:06:40.850  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 11:06:40.851  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 11:06:40.851  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:40.854  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 11:06:40.855  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 11:06:40.855  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 11:06:40.856  3631  3679 D BluetoothAdapter: STATE_ON
,08-11 11:06:40.859  2548  2753 D BtGatt.GattService: registerClient() - UUID=9c04dcbe-23ce-4ebc-b0be-f0a95e087d68
,08-11 11:06:40.859  2548  2601 D BtGatt.GattService: onClientRegistered() - UUID=9c04dcbe-23ce-4ebc-b0be-f0a95e087d68, clientIf=5
08-11 11:06:40.860  3631  3643 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 11:06:40.860  2548  2565 D BtGatt.GattService: start scan with filters
,08-11 11:06:40.864  2548  2605 D BtGatt.ScanManager: handling starting scan
,08-11 11:06:40.864  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 11:06:40.864  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 11:06:40.865  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 11:06:40.865  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 11:06:40.869  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 11:06:40.870  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 11:06:40.870  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 11:06:40.872  2548  2601 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 11:06:40.872  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:40.873  2548  2605 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 11:06:40.873  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-11 11:06:40.878  3631  3679 I io.jxcore.node.ConnectionHelper: start: OK
08-11 11:06:40.879  2548  2601 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 11:06:40.879  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:40.879  2548  2605 D BtGatt.ScanManager: Starting BLE batch scan
,08-11 11:06:40.879  2548  2605 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 11:06:40.892  2548  2601 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 11:06:40.892  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:40.899  2548  2601 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 11:06:40.899  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:41.371  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 11:06:41.371  3631  3631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 11:06:41.372  3631  3631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 11:06:42.406  2548  2548 D BtGatt.ScanManager: awakened up at time 153420
,08-11 11:06:42.408  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:42.475  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-11 11:06:42.476  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:42.476  2548  2601 D BtGatt.GattService: current time is 153490526986
08-11 11:06:42.477  2548  2601 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -91, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -106, -15, -31, -128, 20, -7, 1, 0, -102, 3, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 101, 82, -43, 2, 2, -25, 21, 62, -79, 18, 34, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-11 11:06:42.478  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 11:06:42.479  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 11:06:42.480  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 11:06:42.481  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 11:06:42.482  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 11:06:42.483  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 11:06:42.484  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 101, 82, -43, 2, 2, -25, 21, 62, -79, 18, 34, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-11 11:06:43.978  2548  2548 D BtGatt.ScanManager: awakened up at time 154992
,08-11 11:06:43.981  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:43.993  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 11:06:43.993  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:44.232  3433  3822 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:06:44.278  3433  3824 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:06:44.286  3001  3823 V KeepSync: Connecting to GoogleApiClient
08-11 11:06:44.287   872  1393 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:06:44.302  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:44.309  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:06:44.367  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 11:06:44.367  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:06:44.367  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:44.368  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:44.372  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 11:06:44.372  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 11:06:44.373  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:44.373  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:44.395  1834  3825 V BaseAuthAsyncOperation: access token request failed
,08-11 11:06:44.397  3001  3823 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:06:44.437  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:06:44.437  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:06:44.437  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:44.438  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:44.481  3433  3824 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:06:44.484  3433  3822 E BooksSync: Soft error
08-11 11:06:44.484  3433  3822 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:06:44.484  3433  3822 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:06:44.484  3433  3822 E BooksSync: Sync error
08-11 11:06:44.484  3433  3822 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:06:44.484  3433  3822 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:06:44.484  3433  3822 I BooksSync: Finished books sync
,08-11 11:06:44.493  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 11:06:44.493  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 11:06:44.494  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:06:44.494  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:06:44.498   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125613, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:06:44.506  2548  2548 D BtGatt.ScanManager: awakened up at time 155520
,08-11 11:06:44.507  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:44.530  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-11 11:06:44.530  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:44.531  2548  2601 D BtGatt.GattService: current time is 155545460504
08-11 11:06:44.531  2548  2601 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -78, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 11:06:44.532  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 11:06:44.533  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 11:06:44.535  3001  3823 E KeepSync: IOException
08-11 11:06:44.535  3001  3823 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:06:44.535  3001  3823 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:06:44.535  3001  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:06:44.535  3001  3823 E KeepSync: 	... 10 more
08-11 11:06:44.536  3001  3823 W KeepSync: Sync result 2
,08-11 11:06:44.542   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126123, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:06:45.376  1769  2332 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 11:06:45.878  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:45.879  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:45.879  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 11:06:45.880  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:45.880  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 11:06:45.880  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 11:06:45.881  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 11:06:45.881  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 11:06:45.881  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 11:06:45.882  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 11:06:45.883  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 11:06:45.885  3631  3679 D BluetoothAdapter: STATE_ON
,08-11 11:06:45.887  2548  2742 D BtGatt.GattService: stopScan() - queue size =1
,08-11 11:06:45.890  2548  2565 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 11:06:45.892  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 11:06:45.893  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 11:06:45.893  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 11:06:45.895  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 11:06:45.895  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 11:06:45.900  2548  2548 D BtGatt.ScanManager: awakened up at time 156914
,08-11 11:06:45.901  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 11:06:45.901  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 11:06:45.901  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 11:06:45.901  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 11:06:45.908  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 11:06:45.910  2548  2601 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 11:06:45.911  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:45.911  2548  2605 D BtGatt.ScanManager: stopping BLe Batch
,08-11 11:06:45.912  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:06:45.913  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:06:45.913  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 11:06:45.921  2548  2601 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 11:06:45.922  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:06:45.922  2548  2605 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:06:45.971  2548  2601 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-11 11:06:45.971  2548  2601 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:06:45.972  2548  2601 D BtGatt.GattService: current time is 156986048304
,08-11 11:06:45.972  2548  2601 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -95, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -90, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -93, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 11:06:45.973  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 11:06:45.974  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 11:06:45.975  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 11:06:45.976  2548  2601 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 11:06:46.414  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 11:06:46.415  3631  3631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:46.415  3631  3631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 11:06:50.914  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:50.914  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.914  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:50.915  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:50.916  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.916  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 11:06:50.917  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.917  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:50.918  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.918  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.918  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.920  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.921  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.924  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:50.924  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.924  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:50.925  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.927  3631  3679 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-11 11:06:50.929  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:50.930  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.930  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:50.930  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.930  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.931  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.931  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.931  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.932  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.932  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.932  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.933  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.933  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.933  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.936  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:50.936  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:06:50.936  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.937  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.939  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-11 11:06:50.940  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:50.940  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 11:06:50.940  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:50.941  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.941  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:50.942  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.942  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:50.942  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.942  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.943  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.943  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.943  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.943  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.944  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.946  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:50.946  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.947  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:50.947  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.949  3631  3679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-11 11:06:50.949  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:50.950  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.950  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:50.951  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:50.951  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.951  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.952  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.952  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:50.952  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.953  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.953  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:50.953  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.953  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:50.953  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.954  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:50.954  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.954  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.954  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.955  3631  3679 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-11 11:06:50.955  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:50.955  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.955  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:50.955  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.955  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.955  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.955  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:50.956  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.956  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:50.956  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.956  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:50.956  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.956  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.956  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:50.957  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:50.957  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:06:50.957  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.957  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.958  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 11:06:50.960  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 11:06:50.960  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 11:06:50.960  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-11 11:06:50.960  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 11:06:50.960  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 11:06:50.960  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 11:06:50.960  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 11:06:50.960  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 11:06:50.960  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:50.961  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.961  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:50.961  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.961  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.961  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.961  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.961  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.961  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.961  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.962  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.962  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.962  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.962  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.963  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:50.963  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.963  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:50.963  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.964  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 11:06:50.964  3631  3679 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 11:06:50.964  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 11:06:50.968  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 11:06:50.968  3631  3679 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-11 11:06:50.968  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 11:06:50.968  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 11:06:50.968  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 11:06:50.969  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 11:06:50.970  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 11:06:50.971  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 11:06:50.971  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-11 11:06:50.971  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 11:06:50.971  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-11 11:06:50.971  3631  3679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 11:06:50.971  3631  3679 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-11 11:06:50.972  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 11:06:50.972  3631  3679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 11:06:50.972  3631  3679 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-11 11:06:50.972  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 11:06:50.972  3631  3679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 11:06:50.972  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-11 11:06:50.974  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-11 11:06:50.975  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-11 11:06:50.976  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-11 11:06:50.976  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-11 11:06:50.976  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-11 11:06:50.977  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-11 11:06:50.977  3631  3679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 11:06:50.977  3631  3679 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-11 11:06:50.978  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:50.978  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.978  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:50.978  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.978  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.978  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.979  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-11 11:06:50.980  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.980  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.980  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.980  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.980  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.980  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.980  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.980  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.982  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:50.982  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.982  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.982  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.983  3631  3679 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-11 11:06:50.984  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:50.984  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.984  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:50.984  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.984  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.984  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.984  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.985  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.985  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.985  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.985  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.985  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.985  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.985  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.987  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:50.987  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.987  3631  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
08-11 11:06:50.987  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.988  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.988  3631  3828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
08-11 11:06:50.989  3631  3679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-11 11:06:50.989  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:50.989  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.989  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:50.989  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.990  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.990  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.990  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.990  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.990  3631  3827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 11:06:50.990  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.990  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.990  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.990  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.990  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.990  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.991  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:50.991  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.991  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.991  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.992  3631  3679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-11 11:06:50.992  3631  3679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-11 11:06:50.993  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 11:06:50.993  3631  3679 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-11 11:06:50.993  3631  3679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 11:06:50.993  3631  3679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-11 11:06:50.993  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 11:06:50.993  3631  3679 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-11 11:06:50.993  3631  3679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 11:06:50.993  3631  3679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 11:06:50.993  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 11:06:50.994  3631  3679 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-11 11:06:50.994  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:50.994  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:50.994  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:50.995  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.995  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.995  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.995  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.995  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.995  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.995  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.995  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.995  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.995  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.996  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.996  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:50.997  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:50.997  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.997  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.997  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:50.997  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.997  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:50.998  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:50.998  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:50.998  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:50.998  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:50.998  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:50.998  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:52.398   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 12 -> obsolete
,08-11 11:06:55.999  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:55.999  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.000  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:56.000  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.000  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.001  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:56.001  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:56.001  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:56.002  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:56.003  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:56.003  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.003  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.004  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:56.004  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.004  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.004  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:06:56.005  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.005  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.005  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.005  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.010  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:56.010  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:06:56.010  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.011  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:56.016  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-11 11:06:56.017  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:56.018  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 11:06:56.019  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 11:06:56.019  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-11 11:06:56.020  3631  3631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 11:06:56.020  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 11:06:56.020  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-11 11:06:56.020  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:56.021  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 11:06:56.021  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 11:06:56.021  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 11:06:56.021  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.021  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 11:06:56.021  3631  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 11:06:56.021  3631  3631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-11 11:06:56.021  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:56.021  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.021  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 11:06:56.022  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 11:06:56.021  3631  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-11 11:06:56.022  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 11:06:56.022  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.022  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.026  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 11:06:56.027  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:06:56.027  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 11:06:56.027  3631  3631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
,08-11 11:06:56.027  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 11:06:56.027  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:56.027  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:06:56.028  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 11:06:56.028  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:56.028  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:56.028  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.028  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-11 11:06:56.028  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:56.028  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:56.028  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.028  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:06:56.029  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.029  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.029  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.029  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.030  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:56.030  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:56.030  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.030  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:56.032  3631  3679 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-11 11:06:56.032  3631  3679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 11:06:56.032  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 11:06:56.033  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 11:06:56.033  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 11:06:56.033  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:56.033  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:56.033  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:56.033  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:56.034  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.034  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.034  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
08-11 11:06:56.034  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.034  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.034  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:56.034  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.034  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.034  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.034  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.036  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:56.036  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:56.036  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.036  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.041  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:56.041  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:06:56.041  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:06:56.042  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:06:56.042  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.042  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.042  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:56.042  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.042  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.042  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:56.042  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.042  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.042  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.043  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:06:56.044  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:06:56.044  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:06:56.044  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:56.044  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
08-11 11:06:56.045  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:06:56.045  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 11:06:56.045  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:06:56.046  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:06:56.046  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.046  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.046  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91be59 not in the list
,08-11 11:06:56.046  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.046  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:56.046  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:06:56.046  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.046  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.046  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.046  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.048  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:06:56.048  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:06:56.048  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:56.048  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35a1e not in the list
,08-11 11:06:56.049  3631  3679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-11 11:06:56.049  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-11 11:06:56.049  3631  3679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-11 11:06:56.050  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-11 11:06:56.050  3631  3679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-11 11:06:56.050  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
08-11 11:06:56.053  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 11:06:56.053  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-11 11:06:56.054  3631  3679 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-11 11:06:56.054  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-11 11:06:56.054  3631  3679 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-11 11:06:56.054  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 11:06:56.054  3631  3679 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-11 11:06:56.054  3631  3679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-11 11:06:56.055  3631  3679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-11 11:06:56.055  3631  3679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-11 11:06:56.056  3631  3679 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-11 11:06:56.056  3631  3679 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-11 11:06:56.056  3631  3679 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-11 11:06:56.056  3631  3679 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-11 11:06:56.062  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:06:56.062  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f11efc9 added. We now have 3 listener(s)
08-11 11:06:56.062  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:06:56.065  3631  3679 D BluetoothAdapter: enable(): BT is already enabled..!
08-11 11:06:56.066   872  1863 D WifiService: setWifiEnabled: true pid=3631, uid=10000
08-11 11:06:56.066   872  1863 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 11:06:56.067  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:06:56.068  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2886ce added. We now have 4 listener(s)
,08-11 11:06:56.068  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 11:06:56.076  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:06:56.077  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2886ce removed from the list
08-11 11:06:56.077  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:56.077  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:06:56.078  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.081  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 11:06:56.081  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba859ef added. We now have 4 listener(s)
08-11 11:06:56.081  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:06:56.083  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:06:56.084  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba859ef removed from the list
,08-11 11:06:56.085  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:06:56.085  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:06:56.085  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:06:56.087  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 11:06:56.087  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fef4cfc added. We now have 4 listener(s)
08-11 11:06:56.088  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:06:56.092   872  3055 D WifiService: setWifiEnabled: false pid=3631, uid=10000
,08-11 11:06:56.092   872  3055 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 11:06:56.098  2548  2596 D BluetoothAdapterState: Current state: ON, message: 23
,08-11 11:06:56.098  2548  2596 D BluetoothAdapterProperties: Setting state to 13
08-11 11:06:56.098  2548  2596 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-11 11:06:56.099  2548  2596 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 11:06:56.100  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:06:56.100  2548  2596 I BluetoothAdapterState: Entering PendingCommandState
08-11 11:06:56.101  2548  2548 D BluetoothMapService: onReceive
08-11 11:06:56.102  2548  2548 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 11:06:56.102  2548  2548 D BluetoothMapService: STATE_TURNING_OFF
,08-11 11:06:56.102  2548  2548 D BluetoothMapService: MAP Service closeService in
08-11 11:06:56.102  2548  2548 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 11:06:56.102  2548  2548 D ObexServerSockets0: shutdown(block = true)
08-11 11:06:56.102  2548  2548 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 11:06:56.103  2548  2548 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 11:06:56.103  2548  2756 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-11 11:06:56.103  2548  2757 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-11 11:06:56.104  2548  2739 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 11:06:56.104  2548  2548 I BtOppRfcommListener: stopping Accept Thread
08-11 11:06:56.104  2548  3269 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 11:06:56.105  2548  3269 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 11:06:56.105  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 11:06:56.107   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-11 11:06:56.107   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 11:06:56.107   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 11:06:56.107   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 11:06:56.114   872  1307 E native  : do suspend true
,08-11 11:06:56.116  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:56.116  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 11:06:56.116  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.117  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:56.117  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:06:56.118  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.120  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.121   872  2135 D DhcpClient: Clearing IP address
,08-11 11:06:56.121   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-11 11:06:56.123   372   870 D CommandListener: Setting iface cfg
,08-11 11:06:56.123  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:56.123  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:56.123  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.123  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:56.126  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:56.126  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:56.126  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.126  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:06:56.128  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:06:56.131  1492  2286 V NativeCrypto: Read error: ssl=0x9b40ee00: I/O error during system call, Connection timed out
,08-11 11:06:56.136   872   885 I ActivityManager: Start proc 3836:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-11 11:06:56.136  2548  2601 D BluetoothAdapterProperties: Scan Mode:20
,08-11 11:06:56.136  2548  2596 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 11:06:56.137  2548  2548 D HeadsetService: Received stop request...Stopping profile...
08-11 11:06:56.138   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-11 11:06:56.138   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-11 11:06:56.139   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-11 11:06:56.139  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:06:56.139  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:56.139   872  2139 D DhcpClient: Receive thread stopped
,08-11 11:06:56.140  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.140  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:06:56.140  1492  2286 V NativeCrypto: SSL shutdown failed: ssl=0x9b40ee00: I/O error during system call, Broken pipe
08-11 11:06:56.141  2548  2718 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-11 11:06:56.141  2548  2739 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
08-11 11:06:56.141  3631  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
08-11 11:06:56.142  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.142  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:06:56.143  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.143  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:06:56.144   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,08-11 11:06:56.144   872  1307 E native  : do suspend true
,08-11 11:06:56.144  1365  1377 D BluetoothHeadset: Proxy object disconnected
,08-11 11:06:56.144   872   872 D BluetoothHeadset: Proxy object disconnected
08-11 11:06:56.144   872   872 D BluetoothHeadset: Proxy object disconnected
,08-11 11:06:56.144  1707  1726 D BluetoothHeadset: Proxy object disconnected
08-11 11:06:56.145   872   872 D BluetoothHeadset: Proxy object disconnected
,08-11 11:06:56.145   400   400 E Parcel  : Reading a NULL string not supported here.
,08-11 11:06:56.146  2548  2548 D A2dpService: Received stop request...Stopping profile...
08-11 11:06:56.146  2548  2745 D A2dpStateMachine: Exit Disconnected: -1
,08-11 11:06:56.146  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.147  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 11:06:56.147  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.147  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:06:56.147   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-11 11:06:56.149  1365  1365 D HeadsetProfile: Bluetooth service disconnected
08-11 11:06:56.150   872   872 D BluetoothA2dp: Proxy object disconnected
,08-11 11:06:56.150  2548  2548 D HidService: Received stop request...Stopping profile...
08-11 11:06:56.150  1365  1365 D BluetoothA2dp: Proxy object disconnected
08-11 11:06:56.150  2548  2548 D HidService: Stopping Bluetooth HidService
,08-11 11:06:56.151  1365  1365 D BluetoothInputDevice: Proxy object disconnected
08-11 11:06:56.151  1365  1365 D HidProfile: Bluetooth service disconnected
08-11 11:06:56.151  2548  2548 V BluetoothAdapterState: isTurningOff()=true
08-11 11:06:56.151  2548  2548 V BluetoothAdapterState: isTurningOn()=false
08-11 11:06:56.151  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:06:56.151  2548  2548 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:06:56.153  2548  2548 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 11:06:56.153  2548  2548 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 11:06:56.153  2548  2718 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:06:56.153  2548  2718 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:06:56.153  2548  2718 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:06:56.153  2548  2601 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-11 11:06:56.154  2548  2601 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-11 11:06:56.155  2548  2548 D HealthService: Received stop request...Stopping profile...
08-11 11:06:56.157  2548  2548 D PanService: Received stop request...Stopping profile...
08-11 11:06:56.158  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 11:06:56.158  1365  1365 D PanProfile: Bluetooth service disconnected
08-11 11:06:56.159  2548  2548 D BluetoothMapService: Received stop request...Stopping profile...
08-11 11:06:56.160  2548  2548 D BluetoothMapService: stop()
08-11 11:06:56.160  2548  2548 D BluetoothMapAppObserver: deinitObservers()
08-11 11:06:56.161  2548  2548 D BluetoothMapAppObserver: removeReceiver()
08-11 11:06:56.162  1365  1365 D BluetoothMap: Proxy object disconnected
08-11 11:06:56.162  1365  1365 D MapProfile: Bluetooth service disconnected
08-11 11:06:56.162  2548  2548 V BluetoothAdapterState: isTurningOff()=true
08-11 11:06:56.162  2548  2548 V BluetoothAdapterState: isTurningOn()=false
08-11 11:06:56.162  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:06:56.162  2548  2548 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:06:56.163  2548  2548 V BluetoothAdapterState: isTurningOff()=true
08-11 11:06:56.163  2548  2548 V BluetoothAdapterState: isTurningOn()=false
08-11 11:06:56.164  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:06:56.164  2548  2548 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:06:56.164  2548  2601 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-11 11:06:56.164  2548  2718 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:06:56.164  2548  2718 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:06:56.164  2548  2548 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 11:06:56.164  2548  2718 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 11:06:56.164  2548  2601 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 11:06:56.164  2548  2718 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 11:06:56.164  2548  2718 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 11:06:56.164  2548  2548 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 11:06:56.164  2548  2718 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 11:06:56.165  2548  2548 V BluetoothAdapterState: isTurningOff()=true
08-11 11:06:56.165  2548  2548 V BluetoothAdapterState: isTurningOn()=false
08-11 11:06:56.165  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:06:56.165  2548  2548 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:06:56.165  2548  2548 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health, Interface...
08-11 11:06:56.166  2548  2601 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 11:06:56.166  2548  2548 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 11:06:56.166  2548  2548 V BluetoothAdapterState: isTurningOff()=true
08-11 11:06:56.166  2548  2548 V BluetoothAdapterState: isTurningOn()=false
08-11 11:06:56.166  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:06:56.166  2548  2548 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:06:56.167  2548  2548 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 11:06:56.167  2548  2548 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 11:06:56.168  2548  2548 D BluetoothMapService: MAP Service closeService in
08-11 11:06:56.168  2548  2548 V BluetoothAdapterState: isTurningOff()=true
08-11 11:06:56.168  2548  2548 V BluetoothAdapterState: isTurningOn()=false
08-11 11:06:56.168  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:06:56.168  2548  2548 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:06:56.168  2548  2596 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-11 11:06:56.168  2548  2596 D BluetoothAdapterProperties: Setting state to 15
08-11 11:06:56.168  2548  2596 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 11:06:56.169  2548  2596 I BluetoothAdapterState: Entering BleOnState
08-11 11:06:56.169  2548  2548 D BluetoothMapService: cleanup()
08-11 11:06:56.169   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:06:56.169  2548  2548 D BluetoothMapService: MAP Service closeService in
08-11 11:06:56.170  1365  3630 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 11:06:56.170  1365  1854 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 11:06:56.171  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 11:06:56.171  1365  1386 D BluetoothPan: onBluetoothStateChange on: false
08-11 11:06:56.172  1365  3630 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:06:56.172   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 11:06:56.172  1707  1733 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:06:56.172   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:06:56.172   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:06:56.173  1365  1854 D BluetoothMap: onBluetoothStateChange: up=false
08-11 11:06:56.174  2548  2596 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-11 11:06:56.174  2548  2596 D BluetoothAdapterProperties: Setting state to 16
08-11 11:06:56.175  2548  2596 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-11 11:06:56.176  2548  2596 D BluetoothAdapterProperties: onBleDisable
08-11 11:06:56.176  2548  2596 I BluetoothAdapterState: Entering PendingCommandState
08-11 11:06:56.176  2548  2597 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-11 11:06:56.177  2548  2718 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 11:06:56.177  2548  2718 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:06:56.179  2548  2601 D BluetoothAdapterProperties: Scan Mode:20
08-11 11:06:56.181  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.181  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:06:56.183  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.183  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:06:56.185  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.185  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:06:56.186  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.187  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.188  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.189   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:06:56.195  3836  3836 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-11 11:06:56.210   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:06:56.211   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-11 11:06:56.211   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-11 11:06:56.211   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:06:56.214   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-11 11:06:56.214   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 11:06:56.215  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.217  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.218  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:06:56.220  3257  3257 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@43a876b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-11 11:06:56.225  3836  3836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 11:06:56.227   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:06:56.230   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d877943:true
08-11 11:06:56.231  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.231  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:06:56.231  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.231  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:06:56.231   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-11 11:06:56.233  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.233  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:06:56.233  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 11:06:56.233  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.233  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:06:56.235  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:06:56.235  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:06:56.235  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:06:56.235  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:06:56.237  1769  2054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 11:06:56.248   872   883 I ActivityManager: Start proc 3855:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-11 11:06:56.256  3836  3836 D LocalBluetoothProfileManager: Adding local MAP profile
,08-11 11:06:56.258  3836  3836 D BluetoothMap: Create BluetoothMap proxy object
,08-11 11:06:56.269  3836  3836 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-11 11:06:56.276  3855  3855 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-11 11:06:56.285  3836  3836 D DockEventReceiver: finishStartingService: stopping service
,08-11 11:06:56.286   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-11 11:06:56.288   872  1863 I ActivityManager: Killing 3257:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-11 11:06:56.382  2548  2601 I bt_hci  : shut_down
,08-11 11:06:56.383  2548  2617 D bt_hwcfg: hw_epilog_process
,08-11 11:06:56.384  2548  2617 I bt_vendor: low_power_mode_cb
,08-11 11:06:56.410  2548  2617 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 11:06:56.410  2548  2617 I bt_vendor: epilog_cb
08-11 11:06:56.410  2548  2617 I bt_hci  : epilog_finished_callback
,08-11 11:06:56.414  2548  2601 I bt_hci_h4: hal_close
,08-11 11:06:56.414  2548  2601 I bt_userial_vendor: device fd = 51 close
,08-11 11:06:56.523  2548  2597 D bt_stack_manager: event_shut_down_stack finished.
08-11 11:06:56.524  2548  2596 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 11:06:56.528  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 11:06:56.529  2548  2548 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 11:06:56.529  2548  2596 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-11 11:06:56.529  2548  2548 D BtGatt.GattService: Received stop request...Stopping profile...
,08-11 11:06:56.529  2548  2548 D BtGatt.GattService: stop()
08-11 11:06:56.529  2548  2548 D BtGatt.AdvertiseManager: advertise clients cleared
08-11 11:06:56.532  2548  2548 V BluetoothAdapterState: isTurningOff()=false
08-11 11:06:56.533  2548  2548 V BluetoothAdapterState: isTurningOn()=false
,08-11 11:06:56.533  2548  2548 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 11:06:56.533  2548  2548 V BluetoothAdapterState: isBleTurningOff()=true
,08-11 11:06:56.534  2548  2596 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-11 11:06:56.534  2548  2596 D BluetoothAdapterProperties: Setting state to 10
,08-11 11:06:56.535  2548  2596 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-11 11:06:56.537  2548  2596 I BluetoothAdapterState: Entering OffState
,08-11 11:06:56.537   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-11 11:06:56.551  3855  3855 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.551  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.553  3855  3855 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.553  3855  3855 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.553  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.554  3855  3855 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.554  3855  3855 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.k.d(PG:583)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.554  3855  3855 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.554  3855  3855 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.554  3855  3855 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:06:56.554  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 11:06:56.572   872  1393 I ActivityManager: Start proc 3886:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-11 11:06:56.574   872  1393 I ActivityManager: Killing 3323:com.android.providers.calendar/u0a3 (adj 15): empty #17
08-11 11:06:56.580  2548  2548 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-11 11:06:56.580  2548  2548 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-11 11:06:56.580  2548  2597 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 11:06:56.582  2548  2597 D bt_stack_manager: event_clean_up_stack finished.
,08-11 11:06:56.582  2548  2548 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-11 11:06:56.596  2548  2548 I art     : System.exit called, status: 0
,08-11 11:06:56.596  2548  2548 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 11:06:56.646   872  1714 I ActivityManager: Process com.android.bluetooth (pid 2548) has died
,08-11 11:06:56.661  3886  3886 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-11 11:06:56.880  3886  3905 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-11 11:06:56.880  3886  3905 I Babel_SMS: MmsConfig.loadMmsSettings
,08-11 11:06:56.881  3886  3905 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-11 11:06:56.882  3886  3905 I Babel_SMS: MmsConfig.loadFromDatabase
,08-11 11:06:56.920  3886  3905 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-11 11:06:56.920  3886  3905 I Babel_SMS: MmsConfig.loadFromResources
,08-11 11:06:56.921  3886  3905 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-11 11:06:56.922  3886  3905 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-11 11:06:56.952  3886  3886 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 11:06:56.955  3886  3886 I Babel_Crash: startup - clean
,08-11 11:06:56.973  3886  3886 I Babel_telephony: TeleModule.launchCompleted
,08-11 11:06:56.979   872  1705 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-11 11:06:56.987  3886  3886 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-11 11:06:56.998  3886  3886 W Babel   : BAM#gBA: invalid account id: -1
,08-11 11:06:56.998  3886  3886 W Babel   : BAM#gBA: invalid account id: -1
,08-11 11:06:56.998  3886  3886 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-11 11:06:57.000  3886  3910 I Babel   : deleted: false for 0
,08-11 11:06:57.012   872  1863 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-11 11:06:57.023  3836  3836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 11:06:57.055   872  1714 I ActivityManager: Start proc 3913:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-11 11:06:57.069  3836  3836 D DockEventReceiver: finishStartingService: stopping service
,08-11 11:06:57.088  3886  3886 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 11:06:57.160  3886  3886 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-11 11:06:57.166  3886  3886 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 11:06:57.167  3886  3886 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 11:06:57.187  3886  3886 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 11:06:57.191  3913  3913 D AdapterServiceConfig: Adding HeadsetService
,08-11 11:06:57.191  3913  3913 D AdapterServiceConfig: Adding A2dpService
,08-11 11:06:57.191  3913  3913 D AdapterServiceConfig: Adding HidService
,08-11 11:06:57.192  3913  3913 D AdapterServiceConfig: Adding HealthService
,08-11 11:06:57.192  3913  3913 D AdapterServiceConfig: Adding PanService
,08-11 11:06:57.192  3913  3913 D AdapterServiceConfig: Adding GattService
,08-11 11:06:57.192  3913  3913 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 11:06:57.199  3886  3886 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 11:06:57.204   872   882 I ActivityManager: Killing 2951:android.process.acore/u0a5 (adj 15): empty #17
,08-11 11:06:57.315  3855  3880 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-11 11:06:57.330   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5f2d523:true
,08-11 11:06:57.354   872  1727 I ActivityManager: Killing 3516:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-11 11:06:57.354  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 11:06:57.408  3886  3886 I vclib   : onServiceConnected
,08-11 11:06:57.466  1834  1834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 11:06:57.471  1834  1834 D SystemUpdateService: onCreate
,08-11 11:06:57.474  1834  1834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 11:06:57.479  1834  3928 I SystemUpdateService: active receiver: enabled
,08-11 11:06:57.482  1834  3928 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 11:06:57.482  1834  1834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-11 11:06:57.484  1834  3928 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-11 11:06:57.484  1834  3928 I SystemUpdateService: now status is 0 (complete)
,08-11 11:06:57.484  1834  3928 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 11:06:57.484  1834  3928 I SystemUpdateService: file has been verified
,08-11 11:06:57.484  1834  3928 I SystemUpdateService: OTA package size = 12249756
,08-11 11:06:57.486  1834  2355 I iu.UploadsManager: num queued entries: 0
,08-11 11:06:57.487  1834  2355 I iu.UploadsManager: num updated entries: 0
08-11 11:06:57.488  1834  2355 I iu.SyncManager: NEXT; no task
,08-11 11:06:57.489  1834  3928 I SystemUpdateService: showing system update notification
,08-11 11:06:57.503  1834  1834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 11:06:57.504  1834  1834 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 11:06:57.517   872  1705 I ActivityManager: Start proc 3930:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-11 11:06:57.519  1834  1834 D SystemUpdateService: onDestroy
,08-11 11:06:57.552  3930  3930 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-11 11:06:57.554  3930  3930 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:06:57.558  3930  3930 D SprintDMHelper: simOperator: 
,08-11 11:06:57.558  3930  3930 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 11:06:57.571   872  1705 I ActivityManager: Start proc 3942:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-11 11:06:57.685   872  1724 I ActivityManager: Start proc 3957:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-11 11:06:57.704  3886  3956 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-11 11:06:57.721   872  1393 I ActivityManager: Killing 3533:com.android.musicfx/u0a18 (adj 15): empty #17
,08-11 11:06:57.744  3957  3957 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-11 11:06:57.806  3957  3957 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-11 11:06:57.806  3957  3957 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 11:06:57.806  3957  3957 I GAv4    :   adb logcat -s GAv4
,08-11 11:06:57.821  3957  3957 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 11:06:57.827  3957  3957 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 11:06:57.862  3957  3974 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 11:06:57.963  3957  3957 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-11 11:06:58.003  3957  3957 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 11:06:58.015  3957  3957 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9022-9029)
,08-11 11:06:58.015  3957  3957 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 11:06:58.024  3957  3957 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9797b0d}
,08-11 11:06:58.025  3957  3957 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 11:06:58.025  3957  3957 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 11:06:58.034  3957  3957 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 11:06:58.035  3957  3957 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 11:06:58.056  3957  3957 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 11:06:58.071  3957  3957 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 11:06:58.071  3957  3957 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 11:06:58.072  3957  3957 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 11:06:58.072  3957  3957 I Adreno  : Build Date                       : 10/20/15
08-11 11:06:58.072  3957  3957 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 11:06:58.072  3957  3957 I Adreno  : Local Branch                     : M14
08-11 11:06:58.072  3957  3957 I Adreno  : Remote Branch                    : 
08-11 11:06:58.072  3957  3957 I Adreno  : Remote Branch                    : 
08-11 11:06:58.072  3957  3957 I Adreno  : Reconstruct Branch               : 
,08-11 11:06:58.138  3957  3957 I NSApplication: Starting up...
,08-11 11:06:58.143  3957  4003 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-11 11:06:58.179   872   883 I ActivityManager: Start proc 4008:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-11 11:06:58.181   872   883 I ActivityManager: Killing 3308:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-11 11:06:58.254  4008  4008 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-11 11:06:58.413   872  1393 I ActivityManager: Killing 3481:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-11 11:07:01.118   872   883 D WifiService: setWifiEnabled: true pid=3631, uid=10000
,08-11 11:07:01.118   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 11:07:01.122   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-11 11:07:01.127  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:01.127  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:01.127  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-11 11:07:01.128  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-11 11:07:01.129  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:01.129  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:01.130  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:01.130  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-11 11:07:01.132  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:01.132  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:01.132  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-11 11:07:01.132  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:01.138   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-11 11:07:01.139   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000,
,08-11 11:07:01.139   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-11 11:07:01.140   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 11:07:01.140   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-11 11:07:01.140   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-11 11:07:01.141   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 11:07:01.155   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-11 11:07:01.155   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 11:07:01.156   372   870 D CommandListener: Setting iface cfg
,08-11 11:07:01.157   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-11 11:07:01.158   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 11:07:01.164   872  1307 E native  : do suspend true
,08-11 11:07:01.164   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 11:07:01.168   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 11:07:01.175   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:07:01.838  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:07:01.847  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:07:01.851  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:07:01.898  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:07:01.899  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-11 11:07:01.900  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:07:01.900  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:07:01.939  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:07:01.939  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 11:07:01.940  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-11 11:07:02.570   872  1727 I ActivityManager: Killing 3554:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-11 11:07:02.571   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 11:07:02.626   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.06 rxSuccessRate=8.38 delta 1000 -> 994
,08-11 11:07:02.661   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-11 11:07:02.661   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 11:07:02.677   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 11:07:02.712   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 11:07:02.717  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 11:07:03.129  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 11:07:03.169  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 11:07:03.170  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 11:07:03.176   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:07:03.193   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 11:07:03.194   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-11 11:07:03.194   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 11:07:03.214   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 11:07:03.225   372   870 D CommandListener: Setting iface cfg
,08-11 11:07:03.228   872  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-11 11:07:03.236   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 11:07:03.264   872  4032 D DhcpClient: Receive thread started
,08-11 11:07:03.350   872  1307 E native  : do suspend false
,08-11 11:07:03.362   872  2135 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 11:07:03.374   872  4032 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172649, domain null
,08-11 11:07:03.374   872  2135 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172649 seconds
,08-11 11:07:03.377   872  2135 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 11:07:03.389   872  4032 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 11:07:03.390   872  2135 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 11:07:03.394   372   870 D CommandListener: Setting iface cfg
,08-11 11:07:03.402   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 11:07:03.405   872  2135 D DhcpClient: Scheduling renewal in 86399s
,08-11 11:07:03.406   872  1307 E native  : do suspend true
,08-11 11:07:03.429   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-11 11:07:03.431   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-11 11:07:03.433   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-11 11:07:03.436   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-11 11:07:03.448   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 11:07:03.517   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 11:07:03.518   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-11 11:07:03.521   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-11 11:07:03.524   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-11 11:07:03.527   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-11 11:07:03.547   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-11 11:07:03.558   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-11 11:07:03.558   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-11 11:07:03.559   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-11 11:07:03.559   872  1309 D ConnectivityService:    accepting network in place of null
,08-11 11:07:03.559   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-11 11:07:03.560   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,08-11 11:07:03.561   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 11:07:03.571   872  4031 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 11:07:03.613   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:07:03.650   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:07:03.652   872  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
,08-11 11:07:03.657   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-11 11:07:03.657   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:07:03.662   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-11 11:07:03.659   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-11 11:07:03.672  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:03.672  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 11:07:03.672  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:03.672  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:03.674  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:03.674  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:07:03.675  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:03.675  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:03.676  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:03.676  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:07:03.677  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:03.677  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:07:03.688  1834  1834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 11:07:03.695  1834  1834 D SystemUpdateService: onCreate
,08-11 11:07:03.700  1834  1834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 11:07:03.718  1834  4041 I SystemUpdateService: active receiver: enabled
,08-11 11:07:03.721  1834  1834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 11:07:03.726  1834  2355 I iu.UploadsManager: num queued entries: 0
,08-11 11:07:03.728  1834  1834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 11:07:03.730  1834  4041 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 11:07:03.736  1834  1834 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 11:07:03.739  3930  3930 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:07:03.741   872  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 09:07:03 GMT], X-Android-Received-Millis=[1470906423739], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470906423709]}
08-11 11:07:03.742   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 11:07:03.743   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-11 11:07:03.743   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-11 11:07:03.745   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-11 11:07:03.749  1834  4043 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-11 11:07:03.749  1834  4043 W BaseAppContext: Using Auth Proxy for data requests.
08-11 11:07:03.751  3930  3930 D SprintDMHelper: simOperator: 
08-11 11:07:03.751  3930  3930 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 11:07:03.759  1834  4043 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:07:03.729  1834  2355 I iu.UploadsManager: num updated entries: 0
,08-11 11:07:03.762  1834  2355 I iu.SyncManager: NEXT; no task
,08-11 11:07:03.763  1834  4041 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-11 11:07:03.763  1834  4041 I SystemUpdateService: now status is 0 (complete)
08-11 11:07:03.763  1834  4041 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 11:07:03.763  1834  4041 I SystemUpdateService: file has been verified
,08-11 11:07:03.763  1834  4041 I SystemUpdateService: OTA package size = 12249756
,08-11 11:07:03.789  1834  4041 I SystemUpdateService: showing system update notification
,08-11 11:07:03.817  1834  1834 D SystemUpdateService: onDestroy
,08-11 11:07:03.860  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-11 11:07:03.860  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-11 11:07:03.860  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:07:03.860  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:07:03.878  1834  4043 E MDM     : [215] SitrepService.a: Error sending sitrep.
,08-11 11:07:03.888  3886  4047 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 11:07:04.658   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-11 11:07:06.122   872  1508 D WifiService: setWifiEnabled: false pid=3631, uid=10000
,08-11 11:07:06.123   872  1508 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 11:07:06.170  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-11 11:07:06.180   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-11 11:07:06.180   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 11:07:06.180   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 11:07:06.181   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 11:07:06.203   872  1307 E native  : do suspend true
,08-11 11:07:06.220   872  2135 D DhcpClient: Clearing IP address
,08-11 11:07:06.220   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-11 11:07:06.226   372   870 D CommandListener: Setting iface cfg
,08-11 11:07:06.231   872  4032 D DhcpClient: Receive thread stopped
,08-11 11:07:06.239  1492  4051 V NativeCrypto: Read error: ssl=0x9aebd000: I/O error during system call, Connection timed out
,08-11 11:07:06.245  1492  4051 V NativeCrypto: SSL shutdown failed: ssl=0x9aebd000: I/O error during system call, Broken pipe
,08-11 11:07:06.245   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-11 11:07:06.246   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-11 11:07:06.250   400   400 E Parcel  : Reading a NULL string not supported here.
08-11 11:07:06.252   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-11 11:07:06.256   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 11:07:06.256   872  1307 E native  : do suspend true
,08-11 11:07:06.266   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-11 11:07:06.306   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:07:06.336   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:07:06.337   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-11 11:07:06.337   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-11 11:07:06.337   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-11 11:07:06.339   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-11 11:07:06.352  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:06.352  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:06.353  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.353  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:07:06.354  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:06.354  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:06.354  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.354  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:06.355  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:06.355  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:06.355  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:06.356  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:06.362  1834  1834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 11:07:06.366  1834  1834 D SystemUpdateService: onCreate
,08-11 11:07:06.370  1834  1834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 11:07:06.381  1834  1834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-11 11:07:06.385  1834  2355 I iu.UploadsManager: num queued entries: 0
,08-11 11:07:06.388  1834  1834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-11 11:07:06.389  1834  1834 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 11:07:06.391  3930  3930 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:07:06.396  3930  3930 D SprintDMHelper: simOperator: 
,08-11 11:07:06.396  3930  3930 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 11:07:06.406   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-11 11:07:06.407   872  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-11 11:07:06.408   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 11:07:06.411  1834  2355 I iu.UploadsManager: num updated entries: 0
,08-11 11:07:06.414  1834  4063 I SystemUpdateService: active receiver: enabled
,08-11 11:07:06.421  3886  4067 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-11 11:07:06.425   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-11 11:07:06.427  1769  2054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 11:07:06.427  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:06.427  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:06.427  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.428  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:06.429  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:06.429  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:06.429  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.429   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-11 11:07:06.429  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:06.430  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:06.430  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:06.430  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:06.430  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:06.440  1834  2355 I iu.SyncManager: NEXT; no task
,08-11 11:07:06.443  1834  4063 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 11:07:06.444  1834  4063 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-11 11:07:06.444  1834  4063 I SystemUpdateService: now status is 0 (complete)
08-11 11:07:06.444  1834  4063 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 11:07:06.444  1834  4063 I SystemUpdateService: file has been verified
08-11 11:07:06.445  1834  4063 I SystemUpdateService: OTA package size = 12249756
,08-11 11:07:06.451  1834  4063 I SystemUpdateService: showing system update notification
,08-11 11:07:06.460  1834  1834 D SystemUpdateService: onDestroy
,08-11 11:07:11.178  3913  3913 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 11:07:11.178   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a3fa19c:true
,08-11 11:07:11.183  3913  3913 I bt_bluedroid: init
,08-11 11:07:11.184  3913  4073 I BluetoothAdapterState: Entering OffState
,08-11 11:07:11.192  3913  4074 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-11 11:07:11.192  3913  4074 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-11 11:07:11.193  3913  4074 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-11 11:07:11.194  3913  4074 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-11 11:07:11.199  3913  3913 I bt_bluedroid: get_profile_interface socket
,08-11 11:07:11.203  3913  3913 I bt_bluedroid: get_profile_interface sdp
08-11 11:07:11.206  3913  4077 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-11 11:07:11.211  3913  3924 I bt_bluedroid: config_hci_snoop_log
08-11 11:07:11.211  3913  4077 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 11:07:11.216   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-11 11:07:11.227  3913  4073 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 11:07:11.228  3913  4073 D BluetoothAdapterProperties: Setting state to 14
08-11 11:07:11.228  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14,
,08-11 11:07:11.232  3913  4073 D BluetoothBondStateMachine: make
,08-11 11:07:11.238  3913  4079 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 11:07:11.247  3913  4073 I BluetoothAdapterState: Entering PendingCommandState
,08-11 11:07:11.248  3913  3913 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 11:07:11.255  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:11.257  3913  3913 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 11:07:11.257  3913  3913 D BtGatt.GattService: Received start request. Starting profile...
08-11 11:07:11.257  3913  3913 D BtGatt.GattService: start()
08-11 11:07:11.257  3913  3913 I bt_bluedroid: get_profile_interface gatt
,08-11 11:07:11.258  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
08-11 11:07:11.258  3913  3913 D BtGatt.AdvertiseManager: advertise manager created
,08-11 11:07:11.268  3913  3913 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:11.268  3913  3913 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:11.268  3913  3913 V BluetoothAdapterState: isBleTurningOn()=true
,08-11 11:07:11.268  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 11:07:11.269  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-11 11:07:11.272  3913  4073 I bt_bluedroid: enable
,08-11 11:07:11.273  3913  4074 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-11 11:07:11.274  3913  4074 I bt_hci  : start_up
,08-11 11:07:11.296  3913  4074 I bt_vendor: alloc value 0xb3939189
,08-11 11:07:11.296  3913  4074 I bt_vendor: init
08-11 11:07:11.296  3913  4074 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 11:07:11.297  3913  4074 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 11:07:11.406  3913  4074 D bt_hci  : start_up starting async portion
,08-11 11:07:11.407  3913  4082 I bt_hci  : event_finish_startup
,08-11 11:07:11.407  3913  4082 I bt_hci_h4: hal_open
08-11 11:07:11.407  3913  4082 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 11:07:11.419  3913  4082 I bt_userial_vendor: device fd = 51 open
,08-11 11:07:11.446  3913  4082 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 11:07:11.479  3913  4082 D bt_hwcfg: Chipset BCM4354A2
,08-11 11:07:11.479  3913  4082 D bt_hwcfg: Target name = [BCM4354A2]
08-11 11:07:11.480  3913  4082 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 11:07:11.564   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-11 11:07:12.156  3913  4082 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 11:07:12.157  3913  4082 D bt_hwcfg: Settlement delay -- 100 ms
08-11 11:07:12.157  3913  4082 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 11:07:12.274  3913  4082 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 11:07:12.275  3913  4082 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 11:07:12.305  3913  4082 I bt_hwcfg: vendor lib fwcfg completed
,08-11 11:07:12.305  3913  4082 I bt_vendor: firmware callback
,08-11 11:07:12.305  3913  4082 I bt_hci  : firmware_config_callback
,08-11 11:07:12.316  3913  4084 I bt_btu  : btu_task pending for preload complete event
,08-11 11:07:12.317  3913  4084 I bt_btu_task: Bluetooth chip preload is complete
,08-11 11:07:12.317  3913  4084 I bt_btu  : btu_task received preload complete event
,08-11 11:07:12.327  3913  4084 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 11:07:12.327  3913  4084 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-11 11:07:12.327  3913  4084 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 11:07:12.328  3913  4084 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 11:07:12.328  3913  4084 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-11 11:07:12.328  3913  4084 I         : BTE_InitTraceLevels -- TRC_A2D
,08-11 11:07:12.329  3913  4084 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-11 11:07:12.329  3913  4084 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 11:07:12.329  3913  4084 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 11:07:12.329  3913  4084 I         : BTE_InitTraceLevels -- TRC_PAN
,08-11 11:07:12.330  3913  4084 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 11:07:12.330  3913  4084 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 11:07:12.330  3913  4084 I         : BTE_InitTraceLevels -- TRC_SMP
,08-11 11:07:12.330  3913  4084 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 11:07:12.331  3913  4084 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 11:07:12.467  3913  4084 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-11 11:07:12.467  3913  4084 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-11 11:07:12.478  3913  4077 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 11:07:12.480  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 11:07:12.481  3913  4077 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 11:07:12.484  3913  4077 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 11:07:12.488  3913  4077 D BluetoothAdapterProperties: Scan Mode:20
,08-11 11:07:12.488  3913  4077 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 11:07:12.490  3913  4077 D bt_hci  : do_postload posting postload work item
,08-11 11:07:12.490  3913  4082 I bt_hci  : event_postload
08-11 11:07:12.490  3913  4082 I bt_vendor: sco_config_cb
08-11 11:07:12.490  3913  4082 I bt_hci  : sco_config_callback postload finished.
08-11 11:07:12.493  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:12.493  3913  4077 D bt_bte_conf: Device ID record 1 : primary
,08-11 11:07:12.494  3913  4077 D bt_bte_conf:   vendorId            = 000f
08-11 11:07:12.494  3913  4077 D bt_bte_conf:   vendorIdSource      = 0001
08-11 11:07:12.494  3913  4077 D bt_bte_conf:   product             = 1200
,08-11 11:07:12.494  3913  4077 D bt_bte_conf:   version             = 1436
08-11 11:07:12.494  3913  4077 D bt_bte_conf:   clientExecutableURL = 
08-11 11:07:12.494  3913  4077 D bt_bte_conf:   serviceDescription  = 
,08-11 11:07:12.495  3913  4077 D bt_bte_conf:   documentationURL    = 
08-11 11:07:12.495  3913  4077 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 11:07:12.495  3913  4074 D bt_stack_manager: event_start_up_stack finished
08-11 11:07:12.497  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 11:07:12.497  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.498  3913  4073 D BluetoothAdapterProperties: Setting state to 15
08-11 11:07:12.498  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-11 11:07:12.502  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.503  3913  4082 I bt_vendor: low_power_mode_cb
,08-11 11:07:12.504  3913  4073 I BluetoothAdapterState: Entering BleOnState
08-11 11:07:12.506  3913  4073 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-11 11:07:12.506  3913  4073 D BluetoothAdapterProperties: Setting state to 11
08-11 11:07:12.506  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 11:07:12.514  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:12.515  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.515  3913  3913 D HeadsetService: Received start request. Starting profile...
08-11 11:07:12.517  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:12.519  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.519  3913  3913 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 11:07:12.522  3913  3913 D HeadsetStateMachine: make
,08-11 11:07:12.528  3913  4073 I BluetoothAdapterState: Entering PendingCommandState
,08-11 11:07:12.531  3913  3913 D HeadsetStateMachine: max_hf_connections = 1
,08-11 11:07:12.531  3913  3913 I bt_bluedroid: get_profile_interface handsfree
08-11 11:07:12.532  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-11 11:07:12.532  3913  4077 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-11 11:07:12.538  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:12.538  3913  3913 D A2dpService: Received start request. Starting profile...
08-11 11:07:12.539  3913  3913 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 11:07:12.539  3913  3913 I bt_bluedroid: get_profile_interface avrcp
,08-11 11:07:12.546  3913  3913 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 11:07:12.546  3913  3913 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 11:07:12.546  3913  3913 D A2dpStateMachine: make
,08-11 11:07:12.548  3913  3913 I bt_bluedroid: get_profile_interface a2dp
,08-11 11:07:12.548  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 11:07:12.553  3913  3913 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 11:07:12.554  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:12.554  3913  4092 D A2dpStateMachine: Enter Disconnected: -2
,08-11 11:07:12.555  3913  3913 D HidService: Received start request. Starting profile...
08-11 11:07:12.555  3913  3913 I bt_bluedroid: get_profile_interface hidhost
08-11 11:07:12.555  3913  3913 D HidService: setHidService(): set to: null
,08-11 11:07:12.555  3913  4077 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
,08-11 11:07:12.555  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-11 11:07:12.556  3836  3836 D BluetoothInputDevice: Proxy object connected
,08-11 11:07:12.556  3913  3913 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-11 11:07:12.557  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:12.557  3836  3836 D HidProfile: Bluetooth service connected
08-11 11:07:12.557  3913  3913 D HealthService: Received start request. Starting profile...
,08-11 11:07:12.559  3913  3913 I bt_bluedroid: get_profile_interface health
,08-11 11:07:12.560  3913  3913 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 11:07:12.561  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 11:07:12.561  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:12.563  3913  3913 D PanService: Received start request. Starting profile...
,08-11 11:07:12.563  3913  3913 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-11 11:07:12.563  3913  3913 I bt_bluedroid: get_profile_interface pan
,08-11 11:07:12.563  3836  3836 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 11:07:12.564  3913  4077 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 11:07:12.565  3836  3836 D PanProfile: Bluetooth service connected
,08-11 11:07:12.570  3913  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
08-11 11:07:12.572  3913  3913 D BluetoothMapService: Received start request. Starting profile...
,08-11 11:07:12.572  3913  3913 D BluetoothMapService: start()
,08-11 11:07:12.572  3836  3836 D BluetoothMap: Proxy object connected
,08-11 11:07:12.573  3836  3836 D MapProfile: Bluetooth service connected
08-11 11:07:12.573  3836  3836 D BluetoothMap: getConnectedDevices(),
08-11 11:07:12.574  3836  3836 D BluetoothMap: Bluetooth is Not enabled
08-11 11:07:12.576  3913  3913 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
,08-11 11:07:12.577  3913  3913 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-11 11:07:12.577  3913  3913 D BluetoothMapAppObserver: createReceiver()
08-11 11:07:12.579  3913  3913 D BluetoothMapAppObserver: initObservers()
,08-11 11:07:12.579  3913  3913 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 11:07:12.590  3913  3913 V BluetoothAdapterState: isTurningOff()=false
,08-11 11:07:12.590  3913  3913 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:12.590  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 11:07:12.590  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isTurningOff()=false
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isTurningOn()=true
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 11:07:12.595  3913  4090 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isTurningOff()=false
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isTurningOn()=true
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:12.595  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:12.597  3913  3913 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:12.597  3913  3913 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:12.597  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:12.598  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:12.598  3913  3913 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:12.598  3913  3913 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:12.598  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:12.598  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:12.598  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 11:07:12.598  3913  4073 D BluetoothAdapterProperties: ScanMode =  20
08-11 11:07:12.598  3913  4073 D BluetoothAdapterProperties: State =  11
08-11 11:07:12.599  3913  4073 D BluetoothAdapterProperties: Setting state to 12
08-11 11:07:12.599  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 11:07:12.599  3913  4073 I BluetoothAdapterState: Entering OnState
08-11 11:07:12.600  3836  3847 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 11:07:12.601  3913  4077 D BluetoothAdapterProperties: Scan Mode:21
08-11 11:07:12.601  3913  4077 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 11:07:12.602   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:12.602  1365  1386 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 11:07:12.603  1365  3630 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:12.603  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:12.604  1365  1365 D BluetoothInputDevice: Proxy object connected
08-11 11:07:12.604  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 11:07:12.604  1365  1365 D HidProfile: Bluetooth service connected
08-11 11:07:12.605  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:07:12.606  3836  3850 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 11:07:12.607  1365  1365 D BluetoothA2dp: Proxy object connected
08-11 11:07:12.607  1365  3630 D BluetoothPan: onBluetoothStateChange on: true
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:  ,   - BSSID name: null
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:12.608  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:12.608  3913  3913 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 11:07:12.609  3913  3913 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-11 11:07:12.609  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 11:07:12.609  1365  1365 D PanProfile: Bluetooth service connected
08-11 11:07:12.609  1365  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:12.609   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 11:07:12.609   872   872 D BluetoothA2dp: Proxy object connected
08-11 11:07:12.610  1707  1725 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:12.610  3913  3913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 11:07:12.610  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:07:12.610  3836  3849 D BluetoothPan: onBluetoothStateChange on: true
08-11 11:07:12.611   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:12.611  3836  3847 D BluetoothMap: onBluetoothStateChange: up=true
08-11 11:07:12.611   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:12.611  3913  3913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 11:07:12.611  1365  1386 D BluetoothMap: onBluetoothStateChange: up=true
08-11 11:07:12.612  3913  3913 D ObexServerSockets: Succeed to create listening sockets 
08-11 11:07:12.612  3913  3913 D ObexServerSockets0: startAccept()
08-11 11:07:12.612  3913  3913 D ObexServerSockets0: prepareForNewConnect()
08-11 11:07:12.613  1365  1365 D BluetoothMap: Proxy object connected
08-11 11:07:12.613  1365  1365 D MapProfile: Bluetooth service connected
08-11 11:07:12.613  1365  1365 D BluetoothMap: getConnectedDevices()
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:12.613  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:12.614  3913  4098 D ObexServerSockets0: Accepting socket connection...
08-11 11:07:12.616   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 11:07:12.616  3913  3913 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-11 11:07:12.616  3913  3913 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-11 11:07:12.616  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:07:12.616  3913  3913 D BluetoothMapService: onReceive
08-11 11:07:12.616  3913  3913 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 11:07:12.616  3913  3913 D BluetoothMapService: STATE_ON
08-11 11:07:12.617  3836  3836 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 11:07:12.617  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.617  3913  4100 D ObexServerSockets0: Accepting socket connection...
,08-11 11:07:12.618  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.619  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:12.621  3836  3836 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-11 11:07:12.631  3836  3836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 11:07:12.634  3836  3836 D BluetoothA2dp: Proxy object connected
,08-11 11:07:12.636  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 11:07:12.643  3836  3836 D DockEventReceiver: finishStartingService: stopping service
,08-11 11:07:12.643  3913  3913 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 11:07:12.643  3913  3913 D ObexServerSockets0: prepareForNewConnect()
,08-11 11:07:12.644  3836  3836 D BluetoothPbap: Proxy object connected
08-11 11:07:12.644  3836  3836 D PbapServerProfile: Bluetooth service connected
,08-11 11:07:12.650  1365  1365 D BluetoothPbap: Proxy object connected
08-11 11:07:12.650  1365  1365 D PbapServerProfile: Bluetooth service connected
,08-11 11:07:12.654  3913  4104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:12.666  3913  4108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:12.667  3913  4108 I BtOppRfcommListener: Accept thread started.
,08-11 11:07:12.704  1365  1377 D BluetoothHeadset: Proxy object connected
08-11 11:07:12.704   872   872 D BluetoothHeadset: Proxy object connected
08-11 11:07:12.704  1365  1365 D HeadsetProfile: Bluetooth service connected
08-11 11:07:12.704   872   872 D BluetoothHeadset: Proxy object connected
08-11 11:07:12.704  1707  1726 D BluetoothHeadset: Proxy object connected
,08-11 11:07:12.704   872   872 D BluetoothHeadset: Proxy object connected
,08-11 11:07:12.709  1365  3630 D BluetoothHeadset: Proxy object connected
08-11 11:07:12.709  1365  1365 D HeadsetProfile: Bluetooth service connected
,08-11 11:07:12.710  1707  1733 D BluetoothHeadset: Proxy object connected
08-11 11:07:12.711   872   889 D BluetoothHeadset: Proxy object connected
,08-11 11:07:12.711   872   889 D BluetoothHeadset: Proxy object connected
,08-11 11:07:12.723  3836  3847 D BluetoothHeadset: Proxy object connected
08-11 11:07:12.724  3836  3836 D HeadsetProfile: Bluetooth service connected
,08-11 11:07:16.142  3913  4073 D BluetoothAdapterState: Current state: ON, message: 23
,08-11 11:07:16.143  3913  4073 D BluetoothAdapterProperties: Setting state to 13
08-11 11:07:16.143  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-11 11:07:16.145  3913  4073 D BluetoothAdapterProperties: onBluetoothDisable()
,08-11 11:07:16.149  3913  4073 I BluetoothAdapterState: Entering PendingCommandState
,08-11 11:07:16.154  3913  3913 D BluetoothMapService: onReceive
08-11 11:07:16.155  3913  3913 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 11:07:16.155  3913  3913 D BluetoothMapService: STATE_TURNING_OFF
,08-11 11:07:16.156  3913  3913 D BluetoothMapService: MAP Service closeService in
08-11 11:07:16.156  3913  3913 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 11:07:16.157  3913  3913 D ObexServerSockets0: shutdown(block = true)
08-11 11:07:16.158  3913  4098 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-11 11:07:16.160  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:16.160  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:16.161  3913  3913 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 11:07:16.162  3913  4100 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 11:07:16.166  3913  4086 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 11:07:16.167  3913  3913 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 11:07:16.172  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:16.172  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:07:16.174  3913  3913 I BtOppRfcommListener: stopping Accept Thread
,08-11 11:07:16.174  3913  4108 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-11 11:07:16.174  3913  4108 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 11:07:16.175  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:16.175  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:16.176  3913  4077 D BluetoothAdapterProperties: Scan Mode:20
08-11 11:07:16.176  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 11:07:16.177  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:16.177  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 11:07:16.181  3913  3913 D HeadsetService: Received stop request...Stopping profile...
,08-11 11:07:16.182  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:16.182  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 11:07:16.183  1365  3630 D BluetoothHeadset: Proxy object disconnected
08-11 11:07:16.183  3631  3631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 11:07:16.183  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:16.183   872   872 D BluetoothHeadset: Proxy object disconnected
08-11 11:07:16.183  3913  3913 D A2dpService: Received stop request...Stopping profile...
08-11 11:07:16.183   872   872 D BluetoothHeadset: Proxy object disconnected
08-11 11:07:16.184  3913  4092 D A2dpStateMachine: Exit Disconnected: -1
08-11 11:07:16.185  3836  3847 D BluetoothHeadset: Proxy object disconnected
08-11 11:07:16.185  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:16.186  1707  1726 D BluetoothHeadset: Proxy object disconnected
08-11 11:07:16.186   872   872 D BluetoothHeadset: Proxy object disconnected
,08-11 11:07:16.186   872   872 D BluetoothA2dp: Proxy object disconnected
08-11 11:07:16.186  3836  3836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 11:07:16.186  3913  3913 D HidService: Received stop request...Stopping profile...
08-11 11:07:16.187  3913  3913 D HidService: Stopping Bluetooth HidService
08-11 11:07:16.187  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:16.188  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:16.190  3913  3913 V BluetoothAdapterState: isTurningOff()=true
08-11 11:07:16.190  3836  3836 D HeadsetProfile: Bluetooth service disconnected
08-11 11:07:16.190  3913  3913 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:16.190  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:16.190  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:16.190  3836  3836 D BluetoothA2dp: Proxy object disconnected
08-11 11:07:16.191  3913  3913 D HealthService: Received stop request...Stopping profile...
,08-11 11:07:16.194  3913  3913 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-11 11:07:16.194  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-11 11:07:16.194  3913  3913 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 11:07:16.194  3913  4084 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:07:16.195  3913  4084 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:07:16.195  3913  4084 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:07:16.195  3913  4077 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-11 11:07:16.194  3836  3836 D DockEventReceiver: finishStartingService: stopping service
08-11 11:07:16.195  3913  3913 D PanService: Received stop request...Stopping profile...
08-11 11:07:16.197  3913  3913 D BluetoothMapService: Received stop request...Stopping profile...
08-11 11:07:16.197  3913  3913 D BluetoothMapService: stop()
08-11 11:07:16.198  3836  3836 D BluetoothInputDevice: Proxy object disconnected
08-11 11:07:16.198  3836  3836 D HidProfile: Bluetooth service disconnected
08-11 11:07:16.199  3913  3913 D BluetoothMapAppObserver: deinitObservers()
08-11 11:07:16.199  3913  3913 D BluetoothMapAppObserver: removeReceiver()
,08-11 11:07:16.201  1365  1365 D HeadsetProfile: Bluetooth service disconnected
08-11 11:07:16.201  1365  1365 D BluetoothA2dp: Proxy object disconnected
08-11 11:07:16.201  1365  1365 D BluetoothInputDevice: Proxy object disconnected
08-11 11:07:16.201  1365  1365 D HidProfile: Bluetooth service disconnected
08-11 11:07:16.202  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-11 11:07:16.202  1365  1365 D PanProfile: Bluetooth service disconnected
08-11 11:07:16.202  1365  1365 D BluetoothMap: Proxy object disconnected
,08-11 11:07:16.202  1365  1365 D MapProfile: Bluetooth service disconnected
08-11 11:07:16.203  3913  3913 V BluetoothAdapterState: isTurningOff()=true
08-11 11:07:16.203  3913  3913 V BluetoothAdapterState: isTurningOn()=false
,08-11 11:07:16.203  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:16.203  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:16.203  3836  3836 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 11:07:16.204  3836  3836 D PanProfile: Bluetooth service disconnected
08-11 11:07:16.204  3836  3836 D BluetoothMap: Proxy object disconnected
08-11 11:07:16.204  3836  3836 D MapProfile: Bluetooth service disconnected
08-11 11:07:16.204  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-11 11:07:16.204  3913  4084 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:07:16.204  3913  4084 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:07:16.204  3913  4084 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 11:07:16.204  3913  4084 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 11:07:16.205  3913  4084 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 11:07:16.205  3913  4084 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-11 11:07:16.205  3913  3913 V BluetoothAdapterState: isTurningOff()=true
08-11 11:07:16.205  3913  3913 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:16.205  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:16.205  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:16.205  3913  3913 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 11:07:16.206  3913  3913 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 11:07:16.206  3913  4077 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 11:07:16.207  3913  3913 V BluetoothAdapterState: isTurningOff()=true
08-11 11:07:16.207  3913  3913 V BluetoothAdapterState: isTurningOn()=false
,08-11 11:07:16.207  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:16.207  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:16.208  3913  3913 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 11:07:16.208  3913  3913 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 11:07:16.208  3913  3913 V BluetoothAdapterState: isTurningOff()=true
08-11 11:07:16.208  3913  3913 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:16.208  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:16.208  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:16.209  3913  3913 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 11:07:16.209  3913  4077 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 11:07:16.209  3913  3913 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 11:07:16.210  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 11:07:16.211  3913  3913 D BluetoothMapService: MAP Service closeService in
,08-11 11:07:16.211  3913  3913 V BluetoothAdapterState: isTurningOff()=true
08-11 11:07:16.211  3913  3913 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:16.211  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 11:07:16.211  3913  3913 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:16.212  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-11 11:07:16.212  3913  4073 D BluetoothAdapterProperties: Setting state to 15
08-11 11:07:16.212  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 11:07:16.213  3913  4073 I BluetoothAdapterState: Entering BleOnState
08-11 11:07:16.213  3836  3847 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 11:07:16.213  3913  3913 D BluetoothMapService: cleanup()
08-11 11:07:16.214  3913  3913 D BluetoothMapService: MAP Service closeService in
08-11 11:07:16.214   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 11:07:16.214  1365  1854 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 11:07:16.215  1365  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 11:07:16.215  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 11:07:16.216  3836  3849 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 11:07:16.217  1365  3630 D BluetoothPan: onBluetoothStateChange on: false
08-11 11:07:16.217  1365  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:07:16.218   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 11:07:16.218  1707  1733 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:07:16.218  3836  3850 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:07:16.218  3836  3847 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 11:07:16.221  3836  3849 D BluetoothPan: onBluetoothStateChange on: false
08-11 11:07:16.222   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 11:07:16.222  3836  3850 D BluetoothMap: onBluetoothStateChange: up=false
,08-11 11:07:16.223   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 11:07:16.223  1365  1386 D BluetoothMap: onBluetoothStateChange: up=false
08-11 11:07:16.224  3913  4073 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-11 11:07:16.224  3913  4073 D BluetoothAdapterProperties: Setting state to 16
,08-11 11:07:16.224  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-11 11:07:16.224  3913  4073 D BluetoothAdapterProperties: onBleDisable
08-11 11:07:16.225  3913  4073 I BluetoothAdapterState: Entering PendingCommandState,
08-11 11:07:16.225  3913  4074 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-11 11:07:16.226  3913  4077 D BluetoothAdapterProperties: Scan Mode:20
,08-11 11:07:16.226  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:16.227  3913  4084 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 11:07:16.227  3913  4084 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 11:07:16.228  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-11 11:07:16.229  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:16.229  3836  3836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 11:07:16.230  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:16.231  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:16.233  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:16.233  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 11:07:16.244  3836  3836 D DockEventReceiver: finishStartingService: stopping service
,08-11 11:07:16.432  3913  4077 I bt_hci  : shut_down
,08-11 11:07:16.447  3913  4082 D bt_hwcfg: hw_epilog_process
,08-11 11:07:16.448  3913  4082 I bt_vendor: low_power_mode_cb
,08-11 11:07:16.473  3913  4082 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 11:07:16.473  3913  4082 I bt_vendor: epilog_cb
,08-11 11:07:16.474  3913  4082 I bt_hci  : epilog_finished_callback
,08-11 11:07:16.481  3913  4077 I bt_hci_h4: hal_close
,08-11 11:07:16.482  3913  4077 I bt_userial_vendor: device fd = 51 close
,08-11 11:07:16.599  3913  4074 D bt_stack_manager: event_shut_down_stack finished.
,08-11 11:07:16.601  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 11:07:16.608  3913  3913 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 11:07:16.608  3913  4073 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-11 11:07:16.609  3913  3913 D BtGatt.GattService: Received stop request...Stopping profile...
08-11 11:07:16.609  3913  3913 D BtGatt.GattService: stop()
08-11 11:07:16.610  3913  3913 D BtGatt.AdvertiseManager: advertise clients cleared
,08-11 11:07:16.616  3913  3913 V BluetoothAdapterState: isTurningOff()=false
,08-11 11:07:16.616  3913  3913 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:16.616  3913  3913 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:16.617  3913  3913 V BluetoothAdapterState: isBleTurningOff()=true
,08-11 11:07:16.618  3913  4073 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-11 11:07:16.618  3913  4073 D BluetoothAdapterProperties: Setting state to 10
08-11 11:07:16.619  3913  4073 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-11 11:07:16.620  3913  4073 I BluetoothAdapterState: Entering OffState
08-11 11:07:16.622   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-11 11:07:16.654  3913  3913 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-11 11:07:16.654  3913  3913 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-11 11:07:16.655  3913  4074 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 11:07:16.662  3913  4074 D bt_stack_manager: event_clean_up_stack finished.
,08-11 11:07:16.662  3913  3913 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-11 11:07:16.667  3913  3913 I art     : System.exit called, status: 0
,08-11 11:07:16.668  3913  3913 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 11:07:16.739   872   882 I ActivityManager: Process com.android.bluetooth (pid 3913) has died
,08-11 11:07:21.140  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:07:21.140  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:26.146  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:07:26.146  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fef4cfc removed from the list
08-11 11:07:26.147  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:07:26.147  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:26.147  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:26.150  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 11:07:26.151  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca41da added. We now have 4 listener(s)
,08-11 11:07:26.151  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:07:26.153  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:07:26.154  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca41da removed from the list
,08-11 11:07:26.155  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:07:26.156  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:07:26.157  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:26.160  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-11 11:07:26.161  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ecaa60b added. We now have 4 listener(s)
,08-11 11:07:26.161  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:07:26.163  3631  3679 I System.out: IsBluetoothEnabled
,08-11 11:07:26.172  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:26.214   872   889 I ActivityManager: Start proc 4119:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 11:07:26.344  4119  4119 D AdapterServiceConfig: Adding HeadsetService
,08-11 11:07:26.345  4119  4119 D AdapterServiceConfig: Adding A2dpService
08-11 11:07:26.345  4119  4119 D AdapterServiceConfig: Adding HidService
08-11 11:07:26.345  4119  4119 D AdapterServiceConfig: Adding HealthService
,08-11 11:07:26.345  4119  4119 D AdapterServiceConfig: Adding PanService
08-11 11:07:26.346  4119  4119 D AdapterServiceConfig: Adding GattService
08-11 11:07:26.346  4119  4119 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 11:07:26.359  4119  4119 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 11:07:26.359   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26eb3a9:true
,08-11 11:07:26.365  4119  4119 I bt_bluedroid: init
,08-11 11:07:26.366  4119  4131 I BluetoothAdapterState: Entering OffState
,08-11 11:07:26.369  4119  4132 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-11 11:07:26.369  4119  4132 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 11:07:26.369  4119  4132 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 11:07:26.369  4119  4132 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-11 11:07:26.370  4119  4119 I bt_bluedroid: get_profile_interface socket
08-11 11:07:26.372  4119  4119 I bt_bluedroid: get_profile_interface sdp
,08-11 11:07:26.377  4119  4135 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 11:07:26.377  4119  4130 I bt_bluedroid: config_hci_snoop_log
,08-11 11:07:26.380  4119  4135 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 11:07:26.384   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-11 11:07:26.396  4119  4131 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 11:07:26.397  4119  4131 D BluetoothAdapterProperties: Setting state to 14
08-11 11:07:26.397  4119  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-11 11:07:26.401  4119  4131 D BluetoothBondStateMachine: make
,08-11 11:07:26.407  4119  4136 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 11:07:26.417  4119  4131 I BluetoothAdapterState: Entering PendingCommandState
,08-11 11:07:26.421  4119  4119 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 11:07:26.429  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:26.430  4119  4119 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 11:07:26.430  4119  4119 D BtGatt.GattService: Received start request. Starting profile...
08-11 11:07:26.430  4119  4119 D BtGatt.GattService: start()
08-11 11:07:26.430  4119  4119 I bt_bluedroid: get_profile_interface gatt
08-11 11:07:26.431  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
08-11 11:07:26.432  4119  4119 D BtGatt.AdvertiseManager: advertise manager created
,08-11 11:07:26.442  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:26.442  4119  4119 V BluetoothAdapterState: isTurningOn()=false
08-11 11:07:26.442  4119  4119 V BluetoothAdapterState: isBleTurningOn()=true
08-11 11:07:26.442  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 11:07:26.443  4119  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 11:07:26.443  4119  4131 I bt_bluedroid: enable
08-11 11:07:26.444  4119  4132 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-11 11:07:26.445  4119  4132 I bt_hci  : start_up
,08-11 11:07:26.455  4119  4132 I bt_vendor: alloc value 0xb39aa189
08-11 11:07:26.455  4119  4132 I bt_vendor: init
08-11 11:07:26.455  4119  4132 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 11:07:26.455  4119  4132 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 11:07:26.566  4119  4132 D bt_hci  : start_up starting async portion
08-11 11:07:26.566  4119  4139 I bt_hci  : event_finish_startup
08-11 11:07:26.567  4119  4139 I bt_hci_h4: hal_open
,08-11 11:07:26.567  4119  4139 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 11:07:26.580  4119  4139 I bt_userial_vendor: device fd = 51 open
,08-11 11:07:26.608  4119  4139 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 11:07:26.639  4119  4139 D bt_hwcfg: Chipset BCM4354A2
08-11 11:07:26.639  4119  4139 D bt_hwcfg: Target name = [BCM4354A2]
,08-11 11:07:26.640  4119  4139 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 11:07:27.536  4119  4139 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 11:07:27.537  4119  4139 D bt_hwcfg: Settlement delay -- 100 ms
08-11 11:07:27.537  4119  4139 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 11:07:27.655  4119  4139 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 11:07:27.656  4119  4139 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 11:07:27.686  4119  4139 I bt_hwcfg: vendor lib fwcfg completed
08-11 11:07:27.686  4119  4139 I bt_vendor: firmware callback
,08-11 11:07:27.686  4119  4139 I bt_hci  : firmware_config_callback
,08-11 11:07:27.700  4119  4141 I bt_btu  : btu_task pending for preload complete event
,08-11 11:07:27.701  4119  4141 I bt_btu_task: Bluetooth chip preload is complete
08-11 11:07:27.701  4119  4141 I bt_btu  : btu_task received preload complete event
,08-11 11:07:27.711  4119  4141 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 11:07:27.711  4119  4141 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 11:07:27.711  4119  4141 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 11:07:27.712  4119  4141 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 11:07:27.712  4119  4141 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 11:07:27.712  4119  4141 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 11:07:27.713  4119  4141 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-11 11:07:27.713  4119  4141 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 11:07:27.713  4119  4141 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 11:07:27.713  4119  4141 I         : BTE_InitTraceLevels -- TRC_PAN
,08-11 11:07:27.714  4119  4141 I         : BTE_InitTraceLevels -- TRC_SDP
,08-11 11:07:27.714  4119  4141 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 11:07:27.714  4119  4141 I         : BTE_InitTraceLevels -- TRC_SMP
,08-11 11:07:27.714  4119  4141 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 11:07:27.714  4119  4141 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 11:07:27.859  4119  4141 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3927d9d
,08-11 11:07:27.860  4119  4141 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3927d9d 
,08-11 11:07:27.872  4119  4135 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 11:07:27.873  4119  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 11:07:27.874  4119  4135 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-11 11:07:27.877  4119  4135 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 11:07:27.880  4119  4135 D BluetoothAdapterProperties: Scan Mode:20
,08-11 11:07:27.881  4119  4135 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-11 11:07:27.881  4119  4135 D bt_hci  : do_postload posting postload work item
,08-11 11:07:27.881  4119  4139 I bt_hci  : event_postload
,08-11 11:07:27.882  4119  4139 I bt_vendor: sco_config_cb
,08-11 11:07:27.882  4119  4139 I bt_hci  : sco_config_callback postload finished.
08-11 11:07:27.885  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:27.888  4119  4135 D bt_bte_conf: Device ID record 1 : primary
08-11 11:07:27.888  4119  4135 D bt_bte_conf:   vendorId            = 000f
,08-11 11:07:27.888  4119  4135 D bt_bte_conf:   vendorIdSource      = 0001
08-11 11:07:27.889  4119  4135 D bt_bte_conf:   product             = 1200
,08-11 11:07:27.889  4119  4135 D bt_bte_conf:   version             = 1436
08-11 11:07:27.889  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-11 11:07:27.889  4119  4135 D bt_bte_conf:   clientExecutableURL = 
08-11 11:07:27.889  4119  4135 D bt_bte_conf:   serviceDescription  = ,
08-11 11:07:27.890  4119  4135 D bt_bte_conf:   documentationURL    = 
,08-11 11:07:27.890  4119  4135 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 11:07:27.890  4119  4132 D bt_stack_manager: event_start_up_stack finished
08-11 11:07:27.890  4119  4139 I bt_vendor: low_power_mode_cb,
08-11 11:07:27.891  4119  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 11:07:27.892  4119  4131 D BluetoothAdapterProperties: Setting state to 15,
08-11 11:07:27.892  4119  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 11:07:27.893  4119  4131 I BluetoothAdapterState: Entering BleOnState
,08-11 11:07:27.901  4119  4131 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-11 11:07:27.901  4119  4131 D BluetoothAdapterProperties: Setting state to 11
08-11 11:07:27.901  4119  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 11:07:27.912  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:27.913  4119  4119 D HeadsetService: Received start request. Starting profile...
08-11 11:07:27.920  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:27.921  4119  4119 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 11:07:27.922  4119  4119 D HeadsetStateMachine: make
08-11 11:07:27.922  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:27.932  4119  4131 I BluetoothAdapterState: Entering PendingCommandState
,08-11 11:07:27.939  4119  4119 D HeadsetStateMachine: max_hf_connections = 1
,08-11 11:07:27.940  4119  4119 I bt_bluedroid: get_profile_interface handsfree
08-11 11:07:27.940  4119  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-11 11:07:27.940  4119  4135 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-11 11:07:27.947  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:27.948  4119  4119 D A2dpService: Received start request. Starting profile...
08-11 11:07:27.948  4119  4119 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 11:07:27.949  4119  4119 I bt_bluedroid: get_profile_interface avrcp
,08-11 11:07:27.960  4119  4119 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 11:07:27.961  4119  4119 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 11:07:27.961  4119  4119 D A2dpStateMachine: make
,08-11 11:07:27.963  4119  4119 I bt_bluedroid: get_profile_interface a2dp
,08-11 11:07:27.965  4119  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 11:07:27.968  4119  4150 D A2dpStateMachine: Enter Disconnected: -2
,08-11 11:07:27.970  4119  4119 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 11:07:27.972  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:27.979  4119  4119 D HidService: Received start request. Starting profile...
08-11 11:07:27.979  4119  4119 I bt_bluedroid: get_profile_interface hidhost
08-11 11:07:27.980  4119  4135 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39093e5
08-11 11:07:27.980  4119  4119 D HidService: setHidService(): set to: null
08-11 11:07:27.980  4119  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 11:07:27.980  4119  4119 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 11:07:27.982  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
08-11 11:07:27.983  4119  4119 D HealthService: Received start request. Starting profile...
,08-11 11:07:27.984  4119  4119 I bt_bluedroid: get_profile_interface health
,08-11 11:07:27.984  4119  4119 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-11 11:07:27.985  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:27.985  4119  4119 D PanService: Received start request. Starting profile...
08-11 11:07:27.985  4119  4119 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 11:07:27.986  4119  4119 I bt_bluedroid: get_profile_interface pan
08-11 11:07:27.986  4119  4135 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 11:07:27.989  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 11:07:27.989  4119  4119 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
08-11 11:07:27.990  4119  4119 D BluetoothMapService: Received start request. Starting profile...
08-11 11:07:27.990  4119  4119 D BluetoothMapService: start()
08-11 11:07:27.991  4119  4119 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-11 11:07:27.992  4119  4119 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-11 11:07:27.992  4119  4119 D BluetoothMapAppObserver: createReceiver()
08-11 11:07:27.993  4119  4119 D BluetoothMapAppObserver: initObservers()
08-11 11:07:27.993  4119  4119 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 11:07:27.998  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-11 11:07:27.998  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:27.998  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:27.998  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isTurningOff()=false
,08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isTurningOn()=true
,08-11 11:07:28.000  4119  4148 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:28.000  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isTurningOff()=false
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isTurningOn()=true
08-11 11:07:28.001  4119  4119 V BluetoothAdapterState: isBleTurningOn()=false
08-11 11:07:28.002  4119  4119 V BluetoothAdapterState: isBleTurningOff()=false
08-11 11:07:28.002  4119  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 11:07:28.002  4119  4131 D BluetoothAdapterProperties: ScanMode =  20
08-11 11:07:28.002  4119  4131 D BluetoothAdapterProperties: State =  11
08-11 11:07:28.002  4119  4131 D BluetoothAdapterProperties: Setting state to 12
08-11 11:07:28.002  4119  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 11:07:28.003  4119  4135 D BluetoothAdapterProperties: Scan Mode:21
08-11 11:07:28.003  4119  4135 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 11:07:28.003  4119  4131 I BluetoothAdapterState: Entering OnState
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:28.005  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:28.007  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:28.009  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:28.010  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:28.012  3836  3849 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 11:07:28.015   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 11:07:28.015  1365  1386 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 11:07:28.017  1365  3630 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 11:07:28.017  4119  4119 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-11 11:07:28.018  4119  4119 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-11 11:07:28.018  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 11:07:28.019  4119  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:28.020  3836  3850 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 11:07:28.021  1365  1854 D BluetoothPan: onBluetoothStateChange on: true
,08-11 11:07:28.022  4119  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:28.023  4119  4119 D ObexServerSockets: Succeed to create listening sockets 
,08-11 11:07:28.023  1365  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:28.023  4119  4119 D ObexServerSockets0: startAccept()
,08-11 11:07:28.023  4119  4119 D ObexServerSockets0: prepareForNewConnect()
08-11 11:07:28.023   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 11:07:28.024  1707  1725 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 11:07:28.024  3836  3847 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 11:07:28.025  4119  4119 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-11 11:07:28.025  3836  3849 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-11 11:07:28.025  4119  4119 D BluetoothSdpJni: SDP Create record success - handle: 0
08-11 11:07:28.025  4119  4155 D ObexServerSockets0: Accepting socket connection...
08-11 11:07:28.026  4119  4156 D ObexServerSockets0: Accepting socket connection...
,08-11 11:07:28.026  1365  1365 D BluetoothInputDevice: Proxy object connected
,08-11 11:07:28.026  1365  1365 D HidProfile: Bluetooth service connected
08-11 11:07:28.026  3836  3849 D BluetoothPan: onBluetoothStateChange on: true
08-11 11:07:28.026   872   872 D BluetoothA2dp: Proxy object connected
,08-11 11:07:28.028   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 11:07:28.028  1365  1365 D BluetoothA2dp: Proxy object connected
08-11 11:07:28.028  3836  3847 D BluetoothMap: onBluetoothStateChange: up=true
,08-11 11:07:28.029  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 11:07:28.029  1365  1365 D PanProfile: Bluetooth service connected
,08-11 11:07:28.029   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 11:07:28.030  1365  3630 D BluetoothMap: onBluetoothStateChange: up=true
08-11 11:07:28.030  3836  3836 D BluetoothInputDevice: Proxy object connected
08-11 11:07:28.030  3836  3836 D HidProfile: Bluetooth service connected
,08-11 11:07:28.031  3836  3836 D BluetoothA2dp: Proxy object connected
08-11 11:07:28.031  1365  1365 D BluetoothMap: Proxy object connected
,08-11 11:07:28.031  1365  1365 D MapProfile: Bluetooth service connected
08-11 11:07:28.031  1365  1365 D BluetoothMap: getConnectedDevices()
08-11 11:07:28.032   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 11:07:28.033  4119  4119 D BluetoothMapService: onReceive
,08-11 11:07:28.033  4119  4119 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 11:07:28.034  4119  4119 D BluetoothMapService: STATE_ON
08-11 11:07:28.034  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:28.035  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:28.036  3836  3836 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 11:07:28.036  3836  3836 D PanProfile: Bluetooth service connected
08-11 11:07:28.036  3836  3836 D BluetoothMap: Proxy object connected
,08-11 11:07:28.036  3836  3836 D MapProfile: Bluetooth service connected
08-11 11:07:28.036  3836  3836 D BluetoothMap: getConnectedDevices()
,08-11 11:07:28.041  3836  3836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 11:07:28.046  3836  3836 D DockEventReceiver: finishStartingService: stopping service
,08-11 11:07:28.047  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 11:07:28.054  3836  3836 D BluetoothPbap: Proxy object connected
,08-11 11:07:28.054  3836  3836 D PbapServerProfile: Bluetooth service connected
,08-11 11:07:28.058  1365  1365 D BluetoothPbap: Proxy object connected
,08-11 11:07:28.058  1365  1365 D PbapServerProfile: Bluetooth service connected
,08-11 11:07:28.061  4119  4119 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-11 11:07:28.061  4119  4119 D ObexServerSockets0: prepareForNewConnect()
08-11 11:07:28.063  4119  4161 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:28.077  4119  4165 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:28.079  4119  4165 I BtOppRfcommListener: Accept thread started.
,08-11 11:07:28.116  1365  3630 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.116  1365  1365 D HeadsetProfile: Bluetooth service connected
08-11 11:07:28.116   872   872 D BluetoothHeadset: Proxy object connected
08-11 11:07:28.116   872   872 D BluetoothHeadset: Proxy object connected
08-11 11:07:28.117  3836  3847 D BluetoothHeadset: Proxy object connected
08-11 11:07:28.117  3836  3836 D HeadsetProfile: Bluetooth service connected
,08-11 11:07:28.117  1707  1726 D BluetoothHeadset: Proxy object connected
08-11 11:07:28.117   872   872 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.124  1365  1854 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.124  1365  1365 D HeadsetProfile: Bluetooth service connected
,08-11 11:07:28.125  1707  1733 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.127  3836  3850 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.127  3836  3836 D HeadsetProfile: Bluetooth service connected
,08-11 11:07:28.128   872   889 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.130   872   889 D BluetoothHeadset: Proxy object connected
,08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:28.182  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:28.185  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:28.186  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:07:28.186  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ecaa60b removed from the list
,08-11 11:07:28.187  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:07:28.187  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:07:28.187  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:28.189  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 11:07:28.190  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2623ce8 added. We now have 4 listener(s)
08-11 11:07:28.190  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 11:07:28.194   872  1724 D WifiService: setWifiEnabled: false pid=3631, uid=10000
,08-11 11:07:28.194   872  1724 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 11:07:28.198  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:28.199   872  3055 D WifiService: setWifiEnabled: true pid=3631, uid=10000
08-11 11:07:28.199   872  3055 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 11:07:28.207   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:28.220  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:28.224  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:28.229  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:28.231  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:28.239   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-11 11:07:28.240   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 11:07:28.240   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-11 11:07:28.241   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-11 11:07:28.241   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-11 11:07:28.241   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-11 11:07:28.241   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 11:07:28.251   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-11 11:07:28.251   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-11 11:07:28.252   372   870 D CommandListener: Setting iface cfg
,08-11 11:07:28.252   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-11 11:07:28.252   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 11:07:28.309   872  1307 E native  : do suspend true
,08-11 11:07:28.313   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 11:07:28.324   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 11:07:28.345   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:07:29.747   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 11:07:29.875   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.88 rxSuccessRate=9.88 delta 1000 -> 994
,08-11 11:07:29.876   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-11 11:07:29.876   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 11:07:29.896   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 11:07:29.947   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 11:07:29.952  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 11:07:30.218  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 11:07:30.226  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 11:07:30.226  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:30.227  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2623ce8 removed from the list
,08-11 11:07:30.228  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:07:30.229  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:07:30.230  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:30.245  3631  4171 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-11 11:07:30.246  3631  4171 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 11:07:30.387  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 11:07:30.431  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 11:07:30.433  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 11:07:30.436   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 11:07:30.442   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 11:07:30.443   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 11:07:30.443   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-11 11:07:30.459   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 11:07:30.470   372   870 D CommandListener: Setting iface cfg
08-11 11:07:30.471   872  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-11 11:07:30.477   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 11:07:30.507   872  4174 D DhcpClient: Receive thread started
,08-11 11:07:30.594   872  1307 E native  : do suspend false
,08-11 11:07:30.613   872  2135 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 11:07:30.626   872  4174 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172773, domain null
,08-11 11:07:30.627   872  2135 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172773 seconds
,08-11 11:07:30.630   872  2135 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 11:07:30.647   872  4174 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 11:07:30.648   872  2135 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 11:07:30.653   372   870 D CommandListener: Setting iface cfg
,08-11 11:07:30.663   872  2135 D DhcpClient: Scheduling renewal in 86399s
,08-11 11:07:30.664   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 11:07:30.667   872  1307 E native  : do suspend true
,08-11 11:07:30.680   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE],
08-11 11:07:30.681   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled,
08-11 11:07:30.682   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-11 11:07:30.684   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 11:07:30.684   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-11 11:07:30.753   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 11:07:30.754   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-11 11:07:30.757   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-11 11:07:30.760   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-11 11:07:30.762   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-11 11:07:30.776   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-11 11:07:30.782   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-11 11:07:30.783   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-11 11:07:30.783   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-11 11:07:30.783   872  1309 D ConnectivityService:    accepting network in place of null
,08-11 11:07:30.784   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-11 11:07:30.785   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 11:07:30.786   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 11:07:30.794   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=201807, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 11:07:30.845   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:07:30.857   872  4172 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:804::200e
,08-11 11:07:30.882   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 11:07:30.892   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-11 11:07:30.892   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:07:30.897   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-11 11:07:30.897   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:30.915  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:07:30.918  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:30.923  3631  3631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:07:30.926  3631  3631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:07:30.930  1834  1834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 11:07:30.937   872  4172 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 09:07:30 GMT], X-Android-Received-Millis=[1470906450936], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470906450908]}
,08-11 11:07:30.938   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 11:07:30.939   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-11 11:07:30.939   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-11 11:07:30.940   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-11 11:07:30.951  1834  1834 D SystemUpdateService: onCreate
,08-11 11:07:30.957  1834  1834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 11:07:30.966  1834  4184 I SystemUpdateService: active receiver: enabled
,08-11 11:07:30.975  1834  4184 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 11:07:30.983  1834  4184 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 11:07:30.983  1834  4184 I SystemUpdateService: now status is 0 (complete)
08-11 11:07:30.983  1834  4184 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 11:07:30.983  1834  4184 I SystemUpdateService: file has been verified
,08-11 11:07:30.984  1834  4184 I SystemUpdateService: OTA package size = 12249756
,08-11 11:07:30.993  1834  4184 I SystemUpdateService: showing system update notification
,08-11 11:07:31.025  1834  1834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 11:07:31.027  1834  2355 I iu.UploadsManager: num queued entries: 0
08-11 11:07:31.027  1834  2355 I iu.UploadsManager: num updated entries: 0
,08-11 11:07:31.028  1834  2355 I iu.SyncManager: NEXT; no task
,08-11 11:07:31.042  1834  1834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 11:07:31.048  1834  1834 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 11:07:31.053  3930  3930 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 11:07:31.055  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:07:31.058  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:07:31.062  3930  3930 D SprintDMHelper: simOperator: 
,08-11 11:07:31.062  3930  3930 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 11:07:31.116  1834  4187 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-11 11:07:31.116  1834  4187 W BaseAppContext: Using Auth Proxy for data requests.
,08-11 11:07:31.119  1834  4187 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:07:31.122  3773  4186 V GoogleAuthProtoRequest: [323] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:07:31.191  1834  1834 D SystemUpdateService: onDestroy
,08-11 11:07:31.210  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 11:07:31.210  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 11:07:31.210  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:07:31.211  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:07:31.219  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-11 11:07:31.219  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-11 11:07:31.219  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:07:31.220  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:07:31.244  3773  4186 W ExperimentUpdateService: [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 11:07:31.245  3773  4186 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 11:07:31.255  3886  4191 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 11:07:31.262  1834  4187 E MDM     : [220] SitrepService.a: Error sending sitrep.
,08-11 11:07:31.633  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:07:31.675  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:07:31.675  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-11 11:07:31.675  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:07:31.676  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:07:31.710  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:07:31.711  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 11:07:31.711  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-11 11:07:31.891   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-11 11:07:33.254  3631  4198 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-11 11:07:33.255  3631  4198 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 11:07:33.255  3631  4171 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-11 11:07:33.256  3631  4171 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 11:07:33.257  3631  4171 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 11:07:33.258  3631  4171 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 11:07:33.259  3631  4198 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 11:07:33.261  3631  4200 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: OutgoingSocketThread/Sender)
08-11 11:07:33.261  3631  4171 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 11:07:33.264  3631  4198 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 11:07:33.266  3631  4201 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: OutgoingSocketThread/Receiver)
,08-11 11:07:33.266  3631  4202 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: IncomingSocketThread/Sender)
08-11 11:07:33.267  3631  4198 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 11:07:33.267  3631  4201 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 421, thread name: OutgoingSocketThread/Receiver)
08-11 11:07:33.268  3631  4203 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Receiver)
,08-11 11:07:33.268  3631  4201 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 11:07:33.268  3631  4201 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 421, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 11:07:33.268  3631  4203 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: IncomingSocketThread/Receiver)
08-11 11:07:33.268  3631  4203 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-11 11:07:33.268  3631  4203 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 11:07:36.252  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-11 11:07:36.254  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-11 11:07:36.261  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c302387 Bundle[{}]
,08-11 11:07:36.263  3631  3679 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 11:07:36.264  3631  3679 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-11 11:07:36.265  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-11 11:07:36.267  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-11 11:07:36.268  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-11 11:07:36.270  3631  3679 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-11 11:07:36.278  3631  3679 I System.out: Running OutgoingSocketThread
,08-11 11:07:36.281  3631  4204 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-11 11:07:36.282  3631  4204 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 11:07:38.791   872  1309 D ConnectivityService: handlePromptUnvalidated 102
,08-11 11:07:39.189  1655  1782 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-11 11:07:39.189  1655  1782 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 11:07:39.229  1492  1492 I ConfigService: onCreate
,08-11 11:07:39.290  3631  4206 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-11 11:07:39.290  3631  4206 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-11 11:07:39.290  3631  4206 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 11:07:39.290  3631  4204 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-11 11:07:39.291  3631  4204 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 11:07:39.291  3631  4204 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 11:07:39.291  3631  4206 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 11:07:39.293  3631  4204 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 11:07:39.294  3631  4206 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 11:07:39.299  3631  4208 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Sender)
08-11 11:07:39.301  3631  4204 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 11:07:39.305  3631  4209 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Sender)
,08-11 11:07:39.309  3631  4210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Receiver)
,08-11 11:07:39.311  3631  4210 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: IncomingSocketThread/Receiver)
08-11 11:07:39.312  3631  4210 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 11:07:39.310  3631  4211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
,08-11 11:07:39.312  3631  4210 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 11:07:39.313  3631  4211 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
08-11 11:07:39.313  3631  4211 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 11:07:39.314  3631  4211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 11:07:42.293  3631  3679 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 444)
,08-11 11:07:42.295  3631  3679 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-11 11:07:42.296  3631  3679 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,08-11 11:07:42.302  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 11:07:42.302  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d2cf01 added. We now have 3 listener(s)
,08-11 11:07:42.304  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 11:07:42.304  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 11:07:42.304  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 11:07:42.304  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:07:42.305  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa1a6 added. We now have 4 listener(s)
08-11 11:07:42.305  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 11:07:42.305  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 11:07:42.313  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:42.326  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:07:42.331  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:42.331  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:07:42.331  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:07:42.331  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:07:42.331  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 11:07:42.332  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:07:42.332  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.332  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 11:07:42.332  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 11:07:42.332  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d2cf01 removed from the list
08-11 11:07:42.332  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:42.332  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa1a6 removed from the list
,08-11 11:07:42.339  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:42.347  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:42.348  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:07:42.348  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:42.348  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.348  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:42.350  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 11:07:42.351  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:07:42.351  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:42.351  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa1a6 not in the list
08-11 11:07:42.351  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:07:42.351  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:42.353  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:07:42.353  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:07:42.354  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:42.354  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19aa1a6 not in the list
,08-11 11:07:42.354  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:07:42.354  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.355  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:42.355  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d2cf01 not in the list
08-11 11:07:42.357  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 11:07:42.357  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8923f94 added. We now have 3 listener(s)
,08-11 11:07:42.363  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 11:07:42.363  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 11:07:42.364  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 11:07:42.364  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:07:42.365  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c5a3d added. We now have 4 listener(s)
,08-11 11:07:42.365  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 11:07:42.366  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 11:07:42.375  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:42.386  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 11:07:42.391  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 11:07:42.392  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 11:07:42.394  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 11:07:42.394  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 11:07:42.394  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 11:07:42.395  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:07:42.395  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 11:07:42.397  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:42.400  3631  3679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 11:07:42.400  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 11:07:42.403  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:42.406  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 11:07:42.407  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 11:07:42.407  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 11:07:42.414  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 11:07:42.414  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 11:07:42.415  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 11:07:42.416  3631  3679 D BluetoothAdapter: STATE_ON
,08-11 11:07:42.424  4119  4130 D BtGatt.GattService: registerClient() - UUID=6751acb6-9c5d-4a18-9c96-7457ef13ab2f
,08-11 11:07:42.425  4119  4135 D BtGatt.GattService: onClientRegistered() - UUID=6751acb6-9c5d-4a18-9c96-7457ef13ab2f, clientIf=5
,08-11 11:07:42.427  3631  3642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 11:07:42.428  4119  4157 D BtGatt.GattService: start scan with filters
,08-11 11:07:42.435  4119  4138 D BtGatt.ScanManager: handling starting scan
08-11 11:07:42.436  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 11:07:42.436  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 11:07:42.436  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 11:07:42.437  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 11:07:42.437  4119  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6afb7ab
,08-11 11:07:42.441  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 11:07:42.441  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 11:07:42.442  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 11:07:42.444  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 11:07:42.453  4119  4135 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 11:07:42.453  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:07:42.453  4119  4138 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 11:07:42.452  3631  3679 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-11 11:07:42.454  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 11:07:42.454  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 11:07:42.454  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.455  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 11:07:42.455  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 11:07:42.455  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 11:07:42.455  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 11:07:42.455  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 11:07:42.455  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 11:07:42.455  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 11:07:42.456  3631  3679 D BluetoothAdapter: STATE_ON
08-11 11:07:42.457  4119  4147 D BtGatt.GattService: stopScan() - queue size =1
,08-11 11:07:42.458  4119  4129 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 11:07:42.458  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 11:07:42.458  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 11:07:42.459  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 11:07:42.459  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-11 11:07:42.459  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 11:07:42.460  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 11:07:42.460  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 11:07:42.460  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 11:07:42.460  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 11:07:42.461  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 11:07:42.462  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:07:42.463  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 11:07:42.463  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 11:07:42.466  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 11:07:42.466  3631  3679 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-11 11:07:42.466  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 11:07:42.466  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 11:07:42.467  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 11:07:42.467  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:07:42.467  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 11:07:42.467  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 11:07:42.467  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8923f94 removed from the list
08-11 11:07:42.467  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:42.467  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c5a3d removed from the list
08-11 11:07:42.468  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
08-11 11:07:42.468  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:42.469  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.469  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:42.470  4119  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 11:07:42.470  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:07:42.470  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:07:42.470  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 11:07:42.471  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:42.471  4119  4138 D BtGatt.ScanManager: Starting BLE batch scan
08-11 11:07:42.471  4119  4138 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-11 11:07:42.471  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c5a3d not in the list
,08-11 11:07:42.472  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.472  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:42.473  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:07:42.473  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:07:42.474  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:42.474  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c5a3d not in the list
,08-11 11:07:42.474  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:07:42.474  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:42.474  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:42.474  3631  3679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8923f94 not in the list
08-11 11:07:42.475  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 11:07:42.475  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2a3f7e added. We now have 3 listener(s)
,08-11 11:07:42.477  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 11:07:42.477  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 11:07:42.477  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 11:07:42.477  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 11:07:42.477  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c99cdf added. We now have 4 listener(s)
,08-11 11:07:42.477  3631  3679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 11:07:42.478  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 11:07:42.483  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 11:07:42.488  3631  3679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 11:07:42.490  3631  3679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 11:07:42.490  3631  3679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 11:07:42.491  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 11:07:42.493  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 11:07:42.495  3631  3679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-11 11:07:42.495  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-11 11:07:42.496  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 11:07:42.497  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 11:07:42.497  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 11:07:42.497  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:07:42.498  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 11:07:42.498  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 11:07:42.498  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 11:07:42.498  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-11 11:07:42.498  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 11:07:42.498  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 11:07:42.498  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 11:07:42.500  3631  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 11:07:42.500  4119  4135 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 11:07:42.500  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:07:42.502  3631  3631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 11:07:42.503  3631  3631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-11 11:07:42.504  3631  4212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-11 11:07:42.504  3631  3679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 11:07:42.504  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 11:07:42.507  4119  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 11:07:42.507  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:07:42.509  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 11:07:42.510  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 11:07:42.510  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 11:07:42.512  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-11 11:07:42.512  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 11:07:42.513  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-11 11:07:42.514  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 11:07:42.514  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-11 11:07:42.514  3631  3679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-11 11:07:42.515  3631  3679 D BluetoothAdapter: STATE_ON
08-11 11:07:42.516  4119  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 11:07:42.516  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:07:42.516  4119  4138 D BtGatt.ScanManager: stopping BLe Batch
08-11 11:07:42.517  4119  4130 D BtGatt.GattService: registerClient() - UUID=aff7efcb-c0c9-4014-bee8-68495786b624,
,08-11 11:07:42.518  4119  4135 D BtGatt.GattService: onClientRegistered() - UUID=aff7efcb-c0c9-4014-bee8-68495786b624, clientIf=5
08-11 11:07:42.518  3631  3642 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-11 11:07:42.520  4119  4137 D BtGatt.AdvertiseManager: message : 0
,08-11 11:07:42.522  4119  4137 D BtGatt.AdvertiseManager: starting multi advertising
08-11 11:07:42.522  4119  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 11:07:42.522  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:07:42.523  4119  4138 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 11:07:42.530  4119  4135 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 11:07:42.530  4119  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 11:07:42.539  4119  4135 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 11:07:42.546  4119  4135 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 11:07:42.547  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-11 11:07:42.547  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 11:07:42.549  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-11 11:07:42.551  3631  3631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 11:07:42.551  3631  3631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-11 11:07:42.551  3631  3631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-11 11:07:42.552  3631  3631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-11 11:07:42.552  3631  3631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-11 11:07:42.552  3631  3631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-11 11:07:42.554  3631  3631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 11:07:42.555  3631  3631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 11:07:42.964  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 11:07:43.056  3631  3631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-11 11:07:43.056  3631  3631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 11:07:43.057  3631  3631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 11:07:44.302  1492  1492 I ConfigService: onDestroy
,08-11 11:07:47.553  3631  3679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 11:07:47.553  3631  3679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-11 11:07:47.553  3631  3679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 11:07:47.554  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 11:07:47.554  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 11:07:47.554  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 11:07:47.555  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 11:07:47.555  3631  4212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-11 11:07:47.555  3631  3679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 11:07:47.556  3631  4212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 11:07:47.556  3631  4212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-11 11:07:47.557  3631  3631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 11:07:47.557  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 11:07:47.557  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 11:07:47.557  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 11:07:47.558  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 11:07:47.558  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 11:07:47.561  3631  3679 D BluetoothAdapter: STATE_ON
08-11 11:07:47.561  3631  3679 D BluetoothLeScanner: could not find callback wrapper
,08-11 11:07:47.561  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 11:07:47.562  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-11 11:07:47.564  4119  4137 D BtGatt.AdvertiseManager: message : 1
,08-11 11:07:47.566  4119  4137 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 11:07:47.576  4119  4135 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-11 11:07:47.577  4119  4135 D BtGatt.GattService: Client app is not null!
08-11 11:07:47.579  4119  4147 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 11:07:47.581  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 11:07:47.581  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-11 11:07:47.581  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 11:07:47.582  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-11 11:07:47.582  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 11:07:47.585  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 11:07:47.586  3631  3679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 11:07:47.586  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 11:07:47.587  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 11:07:47.590  3631  3631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 11:07:47.590  3631  3679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 11:07:47.593  3631  3631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 11:07:47.593  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:47.594  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 11:07:47.594  3631  3631 D AndroidRuntime: Shutting down VM
08-11 11:07:47.594  3631  3679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 11:07:47.594  3631  3679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2a3f7e removed from the list
08-11 11:07:47.594  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
--------- beginning of crash
08-11 11:07:47.594  3631  3631 E AndroidRuntime: FATAL EXCEPTION: main
08-11 11:07:47.594  3631  3631 E AndroidRuntime: Process: com.test.thalitest, PID: 3631
08-11 11:07:47.594  3631  3631 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:07:47.594  3631  3631 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 11:07:47.595  3631  3679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c99cdf removed from the list
08-11 11:07:47.595  3631  3679 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 11:07:47.595  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:47.597  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 11:07:47.597  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 11:07:47.599   872  1714 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-11 11:07:47.600  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:07:47.600  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 11:07:47.600  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 11:07:47.600  3631  3679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c99cdf not in the list
08-11 11:07:47.601  3631  3679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 11:07:47.601  3631  3679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 11:07:47.610  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 11:07:47.610  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 11:07:47.610  3631  3679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 11:07:47.611  3631  3631 I Process : Sending signal. PID: 3631 SIG: 9
,08-11 11:07:47.704   872   883 I WindowState: WIN DEATH: Window{14c554c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 11:07:47.704   872  1727 D GraphicsStats: Buffer count: 2
,08-11 11:07:47.705   872  1308 D WifiService: Client connection lost with reason: 4
,08-11 11:07:47.740   872  1705 I ActivityManager: Process com.test.thalitest (pid 3631) has died
,08-11 11:07:47.793   872  1508 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3631 uid 10000
,08-11 11:07:47.795  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-11 11:07:58.895   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229909, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:08:14.867  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:08:14.872  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:08:14.926  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:08:14.926  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:08:14.927  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:08:14.927  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:08:14.955  2477  4218 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:08:14.955  2477  4218 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:08:14.955  2477  4218 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	... 12 more
08-11 11:08:14.955  2477  4218 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at fal.a(PG:38)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:08:14.955  2477  4218 E HttpOperation: 	... 14 more
,08-11 11:08:15.065  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:08:15.065  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:08:15.065  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:08:15.065  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:08:15.083  2477  4218 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 11:08:15.083  2477  4218 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at hec.a(PG:42)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at hee.a(PG:102)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at czr.a(PG:65)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at kka.a(PG:108)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
,08-11 11:08:15.083  2477  4218 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:08:15.083  2477  4218 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	... 15 more
08-11 11:08:15.083  2477  4218 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at fal.a(PG:38)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:08:15.083  2477  4218 E HttpOperation: 	... 17 more
08-11 11:08:15.083  2477  4218 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:08:15.083  2477  4218 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	,at java.lang.Thread.run(Thread.java:818)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	... 15 more
08-11 11:08:15.083  2477  4218 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:08:15.083  2477  4218 E ExperimentLoader: 	... 17 more
,08-11 11:08:15.240   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 245315, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:08:37.785   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268799, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:08:45.660  3433  4222 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:08:45.695  3433  4223 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:08:45.713  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:08:45.715  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:08:45.744  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:08:45.744  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:08:45.744  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:08:45.744  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:08:45.778  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:08:45.780  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:08:45.807  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:08:45.807  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:08:45.807  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:08:45.807  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:08:45.832  3433  4223 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:08:45.834  3433  4222 E BooksSync: Soft error
08-11 11:08:45.834  3433  4222 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:08:45.834  3433  4222 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:08:45.835  3433  4222 E BooksSync: Sync error
08-11 11:08:45.835  3433  4222 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:08:45.835  3433  4222 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 11:08:45.835  3433  4222 I BooksSync: Finished books sync
,08-11 11:08:45.844   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 276601, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:08:47.836  1655  1782 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-11 11:08:47.836  1655  1782 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 11:08:47.884  1492  1492 I ConfigService: onCreate
,08-11 11:08:52.956  1492  1492 I ConfigService: onDestroy
,08-11 11:09:01.241  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:01.243  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:01.262  3773  4229 V GoogleAuthProtoRequest: [324] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:09:01.294  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 11:09:01.295  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 11:09:01.295  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:01.295  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:01.313  3773  4229 W ExperimentUpdateService: [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 11:09:01.314  3773  4229 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 11:09:04.824   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=295837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:09:16.153  3001  4232 V KeepSync: Connecting to GoogleApiClient
08-11 11:09:16.154   872  1508 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:09:16.169  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:16.180  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:16.254  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:09:16.254  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:09:16.254  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:09:16.254  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:16.308  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 11:09:16.308  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 11:09:16.308  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:16.308  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 11:09:16.314  2477  4233 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:09:16.314  2477  4233 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:09:16.314  2477  4233 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	... 12 more
08-11 11:09:16.314  2477  4233 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at fal.a(PG:38)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:09:16.314  2477  4233 E HttpOperation: 	... 14 more
,08-11 11:09:16.356  1834  4234 V BaseAuthAsyncOperation: access token request failed
,08-11 11:09:16.357  3001  4232 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:09:16.382  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:09:16.382  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:09:16.382  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:16.382  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:16.405  2477  4233 E HttpOperation: [getmobileexperiments] Unexpected exception,
08-11 11:09:16.405  2477  4233 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at hec.a(PG:42)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at hee.a(PG:102)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at czr.a(PG:65)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at kka.a(PG:108)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:09:16.405  2477  4233 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	... 15 more
08-11 11:09:16.405  2477  4233 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at fal.a(PG:38)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:09:16.405  2477  4233 E HttpOperation: 	... 17 more
08-11 11:09:16.406  2477  4233 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:09:16.406  2477  4233 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:09:16.4,06  2477  4233 E ExperimentLoader: 	... 15 more
08-11 11:09:16.406  2477  4233 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:09:16.406  2477  4233 E ExperimentLoader: 	... 17 more
,08-11 11:09:16.461  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 11:09:16.461  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 11:09:16.461  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:16.461  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:16.477  3001  4232 E KeepSync: IOException
08-11 11:09:16.477  3001  4232 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:09:16.477  3001  4232 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:09:16.477  3001  4232 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:09:16.477  3001  4232 E KeepSync: 	... 10 more
08-11 11:09:16.477  3001  4232 W KeepSync: Sync result 2
,08-11 11:09:16.500   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 277609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:09:16.606   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 277193, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:09:31.283  1492  1986 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 11:09:36.557   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:09:46.708  3433  4238 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:09:46.736  3433  4239 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:09:46.750  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:46.754  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:46.794  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 11:09:46.794  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 11:09:46.794  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:46.794  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:46.833  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:46.836  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:46.876  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 11:09:46.876  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 11:09:46.877  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:46.877  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:46.901  3433  4239 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:09:46.902  3433  4238 E BooksSync: Soft error
08-11 11:09:46.902  3433  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:09:46.902  3433  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:09:46.904  3433  4238 E BooksSync: Sync error
08-11 11:09:46.904  3433  4238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:09:46.904  3433  4238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 11:09:46.904  3433  4238 I BooksSync: Finished books sync
,08-11 11:09:46.917   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309697, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:09:50.912  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:50.932  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:50.939  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:09:51.032  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 11:09:51.032  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 11:09:51.033  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:09:51.033  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:09:51.087  1492  2851 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 11:09:51.087  1492  2851 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 11:09:51.087  1492  2851 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 11:09:51.087  1492  2851 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 11:09:51.087  1492  2851 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 11:09:51.087  1492  2851 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 11:09:51.087  1492  2851 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 11:09:51.101  3371  3404 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 11:09:51.101  3371  3404 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 11:09:51.101  3371  3404 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 11:09:51.101  3371  3404 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 11:09:51.101  3371  3404 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 11:09:51.101  3371  3404 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 11:09:51.101  3371  3404 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 11:10:17.207  3001  4244 V KeepSync: Connecting to GoogleApiClient
08-11 11:10:17.207   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:10:17.255  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:10:17.259  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:10:17.300  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 11:10:17.300  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 11:10:17.301  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:10:17.301  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:10:17.332  1834  4245 V BaseAuthAsyncOperation: access token request failed
,08-11 11:10:17.335  3001  4244 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:10:17.407  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 11:10:17.407  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 11:10:17.407  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:10:17.408  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:10:17.434  3001  4244 E KeepSync: IOException
08-11 11:10:17.434  3001  4244 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:10:17.434  3001  4244 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:10:17.434  3001  4244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:10:17.434  3001  4244 E KeepSync: 	... 10 more
08-11 11:10:17.435  3001  4244 W KeepSync: Sync result 2
,08-11 11:10:17.450   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 340430, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:10:18.478   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=369492, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:10:42.320   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=393333, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:10:47.738  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:10:47.740  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:10:47.774  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:10:47.774  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:10:47.774  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:10:47.774  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:10:47.791  2477  4249 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:10:47.791  2477  4249 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:10:47.791  2477  4249 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	... 12 more
08-11 11:10:47.791  2477  4249 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at fal.a(PG:38)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:10:47.791  2477  4249 E HttpOperation: 	... 14 more
,08-11 11:10:47.846  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:10:47.846  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 11:10:47.846  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:10:47.847  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:10:47.861  2477  4249 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 11:10:47.861  2477  4249 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at hec.a(PG:42)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at hee.a(PG:102)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at czr.a(PG:65)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at kka.a(PG:108)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:10:47.861  2477  4249 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	... 15 more
08-11 11:10:47.861  2477  4249 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at fal.a(PG:38)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:10:47.861  2477  4249 E HttpOperation: 	... 17 more
,08-11 11:10:47.861  2477  4249 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:10:47.861  2477  4249 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	... 15 more
08-11 11:10:47.861  2477  4249 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:10:47.861  2477  4249 E ExperimentLoader: 	... 17 more
,08-11 11:10:47.995   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 369499, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:11:01.451  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:01.454  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:01.473  3773  4251 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:11:01.530  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-11 11:11:01.531  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 11:11:01.531  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:11:01.531  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:11:01.582  3773  4251 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 11:11:01.584  3773  4251 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 11:11:09.410   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:11:18.146  3433  4253 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:11:18.188  3433  4254 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:11:18.199  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:18.205  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:18.244  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:11:18.244  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:11:18.244  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:11:18.244  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:11:18.287  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:18.293  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:18.336  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:11:18.337  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:11:18.337  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:11:18.337  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:11:18.387  3433  4254 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:11:18.389  3433  4253 E BooksSync: Soft error
08-11 11:11:18.389  3433  4253 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:11:18.389  3433  4253 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:11:18.390  3433  4253 E BooksSync: Sync error
08-11 11:11:18.390  3433  4253 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:11:18.390  3433  4253 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:11:18.390  3433  4253 I BooksSync: Finished books sync
,08-11 11:11:18.403   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 403607, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:11:36.107   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=447120, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:11:48.538  3001  4257 V KeepSync: Connecting to GoogleApiClient
,08-11 11:11:48.538   872  1727 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:11:48.590  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:48.595  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:11:48.626  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 11:11:48.626  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 11:11:48.626  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:11:48.626  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:11:48.647  1834  4258 V BaseAuthAsyncOperation: access token request failed
,08-11 11:11:48.648  3001  4257 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:11:48.706  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 11:11:48.707  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 11:11:48.707  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:11:48.707  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:11:48.737  3001  4257 E KeepSync: IOException
08-11 11:11:48.737  3001  4257 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:11:48.737  3001  4257 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:11:48.737  3001  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:11:48.737  3001  4257 E KeepSync: 	... 10 more
08-11 11:11:48.737  3001  4257 W KeepSync: Sync result 2
,08-11 11:11:48.752   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 434296, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:12:03.172   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=474185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:12:35.945   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=506959, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:12:52.042  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:12:52.047  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:12:52.080  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:12:52.080  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:12:52.080  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:12:52.080  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:12:52.112  2477  4263 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:12:52.112  2477  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:12:52.112  2477  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	... 12 more
08-11 11:12:52.112  2477  4263 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at fal.a(PG:38)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:12:52.112  2477  4263 E HttpOperation: 	... 14 more
,08-11 11:12:52.196  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:12:52.196  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 11:12:52.196  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:12:52.196  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:12:52.220  2477  4263 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 11:12:52.220  2477  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at hec.a(PG:42)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at hee.a(PG:102)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at czr.a(PG:65)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at kka.a(PG:108)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:12:52.220  2477  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	... 15 more
08-11 11:12:52.220  2477  4263 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at fal.a(PG:38)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:12:52.220  2477  4263 E HttpOperation: 	... 17 more
,08-11 11:12:52.221  2477  4263 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:12:52.221  2477  4263 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	... 15 more
08-11 11:12:52.221  2477  4263 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:12:52.221  2477  4263 E ExperimentLoader: 	... 17 more
,08-11 11:12:52.363   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 522765, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:13:03.010   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=534024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:13:29.814  3433  4267 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:13:29.844  3433  4268 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:13:29.861  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:13:29.864  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:13:29.913  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:13:29.913  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 11:13:29.913  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:13:29.914  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:13:29.956  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:13:29.960  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:13:30.009  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:13:30.009  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:13:30.009  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:13:30.009  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:13:30.042  3433  4268 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:13:30.044  3433  4267 E BooksSync: Soft error
08-11 11:13:30.044  3433  4267 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:13:30.044  3433  4267 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:13:30.044  3433  4267 E BooksSync: Sync error
08-11 11:13:30.044  3433  4267 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:13:30.044  3433  4267 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:13:30.044  3433  4267 I BooksSync: Finished books sync
,08-11 11:13:30.059   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 560769, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:13:34.478   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=565492, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:13:48.774  1492  1986 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 11:14:00.576  3001  4270 V KeepSync: Connecting to GoogleApiClient
08-11 11:14:00.576   872  3055 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:14:00.637  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:00.641  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:00.679  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 11:14:00.679  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 11:14:00.679  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:14:00.679  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:00.702  1834  4271 V BaseAuthAsyncOperation: access token request failed
,08-11 11:14:00.704  3001  4270 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:14:00.766  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 11:14:00.766  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 11:14:00.766  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:14:00.767  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:00.790  3001  4270 E KeepSync: IOException
08-11 11:14:00.790  3001  4270 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:14:00.790  3001  4270 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:14:00.790  3001  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:14:00.790  3001  4270 E KeepSync: 	... 10 more
08-11 11:14:00.790  3001  4270 W KeepSync: Sync result 2
,08-11 11:14:00.803   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 591434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:14:01.572   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=592585, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:14:31.230  3371  3371 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-11 11:14:31.449  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:31.489  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:31.493  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:31.609  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 11:14:31.610  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-11 11:14:31.610  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:14:31.611  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:31.678  3371  3371 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-11 11:14:31.710  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:31.781  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 11:14:31.781  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 11:14:31.781  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:14:31.781  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:31.874  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:31.910  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-11 11:14:31.910  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 11:14:31.910  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:14:31.910  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:31.958  3371  3371 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-11 11:14:32.409  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:32.449  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 11:14:32.449  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-11 11:14:32.450  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:14:32.450  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:32.481  3371  3371 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
08-11 11:14:32.482  3371  3371 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-11 11:14:32.482  3371  3371 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-11 11:14:32.487  3371  3426 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-11 11:14:32.490  3371  3371 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,08-11 11:14:47.209  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:47.225  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:47.230  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:14:47.297  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:14:47.297  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 11:14:47.297  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:14:47.298  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:14:47.346  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:14:47.346  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:14:47.347  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-11 11:14:56.464   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 11:15:07.538  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:07.541  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:07.572  3773  4282 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:15:07.617  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 11:15:07.617  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 11:15:07.617  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:15:07.617  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:15:07.646  3773  4282 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 11:15:07.647  3773  4282 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 11:15:07.723  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:07.763  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:15:07.764  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 11:15:07.764  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:15:07.764  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:15:07.817  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:15:07.817  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:15:07.817  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-11 11:15:23.600   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=674613, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:15:28.115  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:28.129  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:28.134  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:28.186  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:15:28.186  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-11 11:15:28.187  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:15:28.187  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:15:28.241  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-11 11:15:28.242  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:15:28.243  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-11 11:15:48.568  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:48.583  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:48.589  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:15:48.645  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:15:48.646  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-11 11:15:48.646  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:15:48.646  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:15:48.699  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-11 11:15:48.700  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:15:48.701  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-11 11:16:09.061  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:16:09.079  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:16:09.085  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:16:09.174  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:16:09.175  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 11:16:09.176  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:16:09.176  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:16:09.249  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:16:09.250  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 11:16:09.255  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-11 11:16:29.634  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:16:29.650  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:16:29.656  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:16:29.709  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 11:16:29.710  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 11:16:29.710  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:16:29.711  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:16:29.768  3371  3371 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 11:16:29.768  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 11:16:29.769  3371  3371 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-11 11:17:00.235  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:17:00.238  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:17:00.288  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:17:00.288  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:17:00.289  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:17:00.289  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:17:00.315  2477  4291 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:17:00.315  2477  4291 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:17:00.315  2477  4291 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	... 12 more
08-11 11:17:00.315  2477  4291 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at fal.a(PG:38)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:17:00.315  2477  4291 E HttpOperation: 	... 14 more
,08-11 11:17:00.390  1492  1901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:17:00.390  1492  1901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:17:00.390  1492  1901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:17:00.390  1492  1901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:17:00.438  2477  4291 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 11:17:00.438  2477  4291 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at hec.a(PG:42)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at hee.a(PG:102)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at czr.a(PG:65)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at kka.a(PG:108)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:17:00.438  2477  4291 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	... 15 more
08-11 11:17:00.438  2477  4291 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at fal.a(PG:38)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:17:00.438  2477  4291 E HttpOperation: 	... 17 more
08-11 11:17:00.439  2477  4291 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:17:00.439  2477  4291 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	... 15 more
08-11 11:17:00.439  2477  4291 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:17:00.439  2477  4291 E ExperimentLoader: 	... 17 more
,08-11 11:17:00.539   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 770889, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:17:07.824  1492  1986 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 11:17:52.862  3433  4296 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:17:52.884  3433  4297 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:17:52.899  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:17:52.901  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:17:52.939  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:17:52.939  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 11:17:52.939  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:17:52.939  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:17:52.978  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:17:52.981  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:17:53.027  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:17:53.027  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 11:17:53.027  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:17:53.027  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:17:53.044  3433  4297 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:17:53.044  3433  4296 E BooksSync: Soft error
08-11 11:17:53.044  3433  4296 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:17:53.044  3433  4296 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 11:17:53.045  3433  4296 E BooksSync: Sync error
08-11 11:17:53.045  3433  4296 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:17:53.045  3433  4296 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 11:17:53.045  3433  4296 I BooksSync: Finished books sync
,08-11 11:17:53.056   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 823777, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:18:24.294  3001  4299 V KeepSync: Connecting to GoogleApiClient
,08-11 11:18:24.294   872  3055 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:18:24.404  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:18:24.406  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:18:24.455  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 11:18:24.455  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 11:18:24.455  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:18:24.455  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:18:24.487  1834  4300 V BaseAuthAsyncOperation: access token request failed
,08-11 11:18:24.488  3001  4299 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:18:24.543  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 11:18:24.543  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 11:18:24.543  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:18:24.543  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:18:24.567  3001  4299 E KeepSync: IOException
08-11 11:18:24.567  3001  4299 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:18:24.567  3001  4299 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:18:24.567  3001  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:18:24.567  3001  4299 E KeepSync: 	... 10 more
,08-11 11:18:24.567  3001  4299 W KeepSync: Sync result 2
,08-11 11:18:24.573   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 855145, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:22:36.785   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1107798, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 11:22:50.637   872  4173 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 11:23:07.846  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:23:07.847  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:23:07.864  3773  4315 V GoogleAuthProtoRequest: [327] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 11:23:07.908  1492  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-11 11:23:07.908  1492  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-11 11:23:07.908  1492  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:23:07.908  1492  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:23:07.936  3773  4315 W ExperimentUpdateService: [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 11:23:07.937  3773  4315 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 11:24:27.627   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,08-11 11:25:15.987  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:25:15.989  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:25:16.024  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:25:16.024  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:25:16.024  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:25:16.024  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:25:16.044  2477  4322 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 11:25:16.044  2477  4322 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at blb.a(PG:3937)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at czp.a(PG:18188)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:25:16.044  2477  4322 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	... 12 more
08-11 11:25:16.044  2477  4322 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at fal.a(PG:38)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:25:16.044  2477  4322 E HttpOperation: 	... 14 more
,08-11 11:25:16.126  1492  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 11:25:16.126  1492  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 11:25:16.126  1492  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:25:16.126  1492  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:25:16.152  2477  4322 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 11:25:16.152  2477  4322 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jdm.a(PG:82)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jcs.o(PG:406)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jcn.a(PG:1379)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jcs.i(PG:143)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at hec.a(PG:42)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at hee.a(PG:102)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at czr.a(PG:65)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at kka.a(PG:108)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at czp.a(PG:19176)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at czp.a(PG:9081)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at czq.run(PG:1686)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:25:16.152  2477  4322 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jdj.a(PG:4091)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jdj.a(PG:1125)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jdm.a(PG:77)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	... 15 more
08-11 11:25:16.152  2477  4322 E HttpOperation: Caused by: faj: BadAuthentication
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at fal.a(PG:38)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	at jdj.a(PG:4089)
08-11 11:25:16.152  2477  4322 E HttpOperation: 	... 17 more
,08-11 11:25:16.153  2477  4322 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 11:25:16.153  2477  4322 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at hec.a(PG:42)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at hee.a(PG:102)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at czr.a(PG:65)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at kka.a(PG:108)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	... 15 more
08-11 11:25:16.153  2477  4322 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at fal.a(PG:38)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 11:25:16.153  2477  4322 E ExperimentLoader: 	... 17 more
,08-11 11:25:16.312   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1266577, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:26:38.532  3433  4326 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 11:26:38.596  3433  4327 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 11:26:38.616  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:26:38.621  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:26:38.679  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:26:38.679  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:26:38.679  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:26:38.679  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:26:38.751  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:26:38.758  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:26:38.825  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 11:26:38.826  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 11:26:38.826  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 11:26:38.826  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:26:38.862  3433  4327 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 11:26:38.863  3433  4326 E BooksSync: Soft error
08-11 11:26:38.863  3433  4326 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:26:38.863  3433  4326 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 11:26:38.863  3433  4326 E BooksSync: Sync error
08-11 11:26:38.863  3433  4326 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 11:26:38.863  3433  4326 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 11:26:38.863  3433  4326 I BooksSync: Finished books sync
,08-11 11:26:38.874   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1349478, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 11:27:11.433  3001  4331 V KeepSync: Connecting to GoogleApiClient
,08-11 11:27:11.433   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 11:27:11.509  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:27:11.515  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 11:27:11.579  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 11:27:11.580  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 11:27:11.580  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:27:11.580  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:27:11.612  1834  4332 V BaseAuthAsyncOperation: access token request failed
,08-11 11:27:11.613  3001  4331 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 11:27:11.698  1492  2851 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 11:27:11.699  1492  2851 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 11:27:11.699  1492  2851 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 11:27:11.699  1492  2851 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 11:27:11.718  3001  4331 E KeepSync: IOException
08-11 11:27:11.718  3001  4331 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 11:27:11.718  3001  4331 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 11:27:11.718  3001  4331 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 11:27:11.718  3001  4331 E KeepSync: 	... 10 more
,08-11 11:27:11.718  3001  4331 W KeepSync: Sync result 2
,08-11 11:27:11.726   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1382243, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),08-11 11:29:43.037  4338  4338 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 11:29:43.043  4338  4338 D AndroidRuntime: CheckJNI is OFF
08-11 11:29:43.078  4338  4338 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 11:29:43.119  4338  4338 I Radio-JNI: register_android_hardware_Radio DONE
08-11 11:29:43.141  4338  4338 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-11 11:29:43.151   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-11 11:29:43.296   872   895 W PackageSettings: Skipping PackageSetting{c38386c com.example.hello/10273} due to missing metadata
08-11 11:29:43.347   872   895 I art     : Starting a blocking GC Explicit
08-11 11:29:43.395   872   895 I art     : Explicit concurrent mark sweep GC freed 16454(1063KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 643us total 48.055ms
08-11 11:29:43.417   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-11 11:29:43.422  4338  4338 I art     : System.exit called, status: 0
08-11 11:29:43.422  4338  4338 I AndroidRuntime: VM exiting with result code 0.
08-11 11:29:43.455   872   895 I ActivityManager: Start proc 4348:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-11 11:29:43.455   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-11 11:29:43.486   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 11:29:43.489  4119  4119 D BluetoothMapAppObserver: onReceive
08-11 11:29:43.489  4119  4119 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 11:29:43.490  1769  2019 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 11:29:43.493  3502  3502 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-11 11:29:43.493  1655  1655 I Keyboard.Facilitator: resetDictionaries() : en_US
08-11 11:29:43.518  1655  4362 I Keyboard.Facilitator.DecoderInitializer: run()
08-11 11:29:43.520  1655  4362 I Decoder : createOrResetDecoder
08-11 11:29:43.535   872  1724 I ActivityManager: Start proc 4364:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-11 11:29:43.546  1492  1492 I ConfigService: onCreate
08-11 11:29:43.547  1707  1707 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 11:29:43.555  1492  4375 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 11:29:43.556  1492  4375 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-11 11:29:43.558  1492  4375 W SQLiteOpenHelper: Opened config.db in read-only mode
08-11 11:29:43.563   872  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-11 11:29:43.579  1655  4362 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-11 11:29:43.597  4364  4364 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-11 11:29:43.597   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 11:29:43.607  1655  4362 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-11 11:29:43.608  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-11 11:29:43.609  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-11 11:29:43.611  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 11:29:43.611  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-11 11:29:43.611  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-11 11:29:43.611  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-11 11:29:43.612  1655  4362 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 11:29:43.612  1655  4362 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 11:29:43.612  1655  4362 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 11:29:43.612  1655  4362 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 11:29:43.612  1655  4362 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 11:29:43.612  1655  4362 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-11 11:29:43.626  1728  1820 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-11 11:29:43.626   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 11:29:43.627   872   884 E PackageManager: Failed to write settings, restoring backup
08-11 11:29:43.627   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 11:29:43.627   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 11:29:43.627   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 11:29:43.627   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 11:29:43.627   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 11:29:43.627   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.627   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.627   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.630   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-11 11:29:43.630   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 11:29:43.630   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 11:29:43.630   872   885 E DropBoxManagerService: 	... 13 more
08-11 11:29:43.638   872   882 I ActivityManager: Start proc 4382:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-11 11:29:43.639  1728  1820 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 11:29:43.639  1728  1820 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1728
08-11 11:29:43.639  1728  1820 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.639  1728  1820 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.640   872  1393 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 11:29:43.641   872  4388 E DropBoxManagerService: Can't write: system_app_crash
08-11 11:29:43.641   872  4388 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 11:29:43.641   872  4388 E DropBoxManagerService: 	... 5 more
08-11 11:29:43.644  1728  1820 I Process : Sending signal. PID: 1728 SIG: 9
08-11 11:29:43.648  4364  4364 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-11 11:29:43.668   872   883 I ActivityManager: Start proc 4396:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-11 11:29:43.677  4364  4401 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 11:29:43.715  4396  4396 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-11 11:29:43.731   872  1297 W InputDispatcher: channel '4d21330 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-11 11:29:43.731   872  1297 E InputDispatcher: channel '4d21330 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-11 11:29:43.732   872  1727 D GraphicsStats: Buffer count: 1
08-11 11:29:43.732   872  3055 I WindowState: WIN DEATH: Window{4d21330 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-11 11:29:43.732   872  3055 W InputDispatcher: Attempted to unregister already unregistered input channel '4d21330 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-11 11:29:43.748   872  1714 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1728) has died
08-11 11:29:43.748   872  1714 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-11 11:29:43.749   872  1714 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.761  4364  4380 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.761  4364  4380 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.764  1492  1492 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-11 11:29:43.765  1492  1492 D AndroidRuntime: Shutting down VM
08-11 11:29:43.765  1492  1492 E AndroidRuntime: FATAL EXCEPTION: main
08-11 11:29:43.765  1492  1492 E AndroidRuntime: Process: com.google.process.gapps, PID: 1492
08-11 11:29:43.765  1492  1492 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 11:29:43.765  1492  1492 E AndroidRuntime: 	... 8 more
08-11 11:29:43.771   872   885 I ActivityManager: Start proc 4414:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 11:29:43.778   872  4420 E DropBoxManagerService: Can't write: system_app_crash
08-11 11:29:43.778   872  4420 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 11:29:43.778   872  4420 E DropBoxManagerService: 	... 5 more
08-11 11:29:43.780  1492  1492 I Process : Sending signal. PID: 1492 SIG: 9
08-11 11:29:43.793   872  1724 I ActivityManager: Killing 1826:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-11 11:29:43.830   872  1308 D WifiService: Client connection lost with reason: 4
08-11 11:29:43.833  4364  4380 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-11 11:29:43.838   872   890 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
08-11 11:29:43.839   872   890 W DisplayManagerService: Failed to notify process 1492 that displays changed, assuming it died.
08-11 11:29:43.839   872   890 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.839   872   890 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 11:29:43.852   872  1308 D WifiService: Client connection lost with reason: 4
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.854  4364  4401 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-11 11:29:43.854  4364  4401 E AndroidRuntime: Process: android.process.acore, PID: 4364
08-11 11:29:43.854  4364  4401 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.854  4364  4401 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 11:29:43.855  4364  4380 I Process : Sending signal. PID: 4364 SIG: 9
08-11 11:29:43.859  1834  4426 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@98cf02c
08-11 11:29:43.859   872  1714 I ActivityManager: Process com.google.process.gapps (pid 1492) early provider death
08-11 11:29:43.860   872  1714 I ActivityManager: Process com.google.process.gapps (pid 1492) has died
08-11 11:29:43.860   872  1714 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-11 11:29:43.860   872  1714 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-11 11:29:43.860   872  1714 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-11 11:29:43.866   872  4428 E DropBoxManagerService: Can't write: system_app_crash
08-11 11:29:43.866   872  4428 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 11:29:43.866   872  4428 E DropBoxManagerService: 	... 5 more
08-11 11:29:43.874   872  1393 I ActivityManager: Start proc 4429:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-11 11:29:43.876   872  1705 W ActivityManager: Spurious death for ProcessRecord{9534e7 0:com.google.process.gapps/u0a11}, curProc for 1492: null
08-11 11:29:43.883  1834  1834 W RocketImpressions: ClearcutLogger connection suspended: 1
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:29:43.888  4414  4414 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 11:29:43.888  4414  4414 D AndroidRuntime: Shutting down VM
08-11 11:29:43.896  4414  4414 E AndroidRuntime: FATAL EXCEPTION: main
08-11 11:29:43.896  4414  4414 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4414
08-11 11:29:43.896  4414  4414 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 11:29:43.896  4414  4414 E AndroidRuntime: 	... 10 more
08-11 11:29:43.897   872  1705 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 11:29:43.898  4414  4414 I Process : Sending signal. PID: 4414 SIG: 9
08-11 11:29:43.899   872  4442 E DropBoxManagerService: Can't write: system_app_crash
08-11 11:29:43.899   872  4442 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 11:29:43.899   872  4442 E DropBoxManagerService: 	... 5 more
08-11 11:29:43.911   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
