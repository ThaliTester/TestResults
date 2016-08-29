#### Test 814185773fe89cf_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 08:37:29.112   871  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 08:37:29.828  3916  3916 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 08:37:29.832  3916  3916 D AndroidRuntime: CheckJNI is OFF
08-29 08:37:29.868  3916  3916 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 08:37:29.911  3916  3916 I Radio-JNI: register_android_hardware_Radio DONE
08-29 08:37:29.930  3916  3916 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 08:37:29.936   871  1394 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 08:37:29.969  2039  2054 W SearchService: Abort, client detached.
08-29 08:37:29.976  3916  3916 D AndroidRuntime: Shutting down VM
08-29 08:37:29.985  2039  2348 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2d26e4b
08-29 08:37:29.986  2039  2356 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 08:37:29.987  2039  2039 I HotwordDetector: Closing mic
08-29 08:37:30.005   871  1994 I ActivityManager: Start proc 3925:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 08:37:30.051   373  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 08:37:30.053   373  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 08:37:30.056   373  1284 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 08:37:30.059  2039  2352 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 08:37:30.060  2039  2355 I MicroRecognitionRnrImpl: Detection finished
08-29 08:37:30.071  3925  3925 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 08:37:30.094  3925  3925 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 08:37:30.101  3925  3925 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4722-4725)
08-29 08:37:30.101  3925  3925 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:37:30.116  3925  3925 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ebd06a}
08-29 08:37:30.116  3925  3925 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 08:37:30.116  3925  3925 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 08:37:30.122  3925  3925 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 08:37:30.124  3925  3925 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 08:37:30.145  3925  3925 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 08:37:30.154  3925  3925 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 08:37:30.154  3925  3925 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 08:37:30.154  3925  3925 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 08:37:30.154  3925  3925 I Adreno  : Build Date                       : 10/20/15
08-29 08:37:30.154  3925  3925 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 08:37:30.154  3925  3925 I Adreno  : Local Branch                     : M14
08-29 08:37:30.154  3925  3925 I Adreno  : Remote Branch                    : 
08-29 08:37:30.154  3925  3925 I Adreno  : Remote Branch                    : 
08-29 08:37:30.154  3925  3925 I Adreno  : Reconstruct Branch               : 
,08-29 08:37:30.206   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5613c47:true
,08-29 08:37:30.255  3925  3925 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 08:37:30.267  3925  3925 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 08:37:30.327  3925  3963 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 08:37:30.336  3925  3950 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 08:37:30.368  3925  3963 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 08:37:30.435   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +454ms
,08-29 08:37:30.439  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-29 08:37:30.521  3925  3925 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3925
,08-29 08:37:30.623  3925  3925 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 08:37:30.798   871   881 I ActivityManager: Killing 2640:com.google.android.calendar/u0a37 (adj 15): empty #17
08-29 08:37:30.799   278   278 E lowmemorykiller: Error writing /proc/2640/oom_score_adj; errno=22
,08-29 08:37:30.828  3925  3967 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1702098640
,08-29 08:37:30.836   871   881 I ActivityManager: Killing 3225:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-29 08:37:30.842  3925  3967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 08:37:30.842  3925  3967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 08:37:30.842  3925  3967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 08:37:30.842  3925  3967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 08:37:30.842  3925  3967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 08:37:30.843  3925  3967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@484f0c9 added. We now have 1 listener(s)
,08-29 08:37:30.847  3925  3967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 08:37:30.850  3925  3967 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:37:30.851  3925  3967 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:37:30.851  3925  3967 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 08:37:30.856  3925  3967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfb01fc added. We now have 1 listener(s)
08-29 08:37:30.856  3925  3967 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:37:30.861   871  1314 D WifiService: New client listening to asynchronous messages
,08-29 08:37:30.862  3925  3967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:37:30.862  3925  3967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 08:37:30.862  3925  3967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 08:37:30.863  3925  3967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 08:37:30.863  3925  3967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 08:37:30.881  3925  3967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:37:30.881  3925  3967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 08:37:30.888  3925  3967 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:30.888  3925  3967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:30.888  3925  3967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 08:37:30.888  3925  3967 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:30.890  3925  3967 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 08:37:30.890  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:30.893  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:31.141  3925  3925 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 08:37:31.585  3925  3935 I art     : Background sticky concurrent mark sweep GC freed 72161(7MB) AllocSpace objects, 18(1604KB) LOS objects, 28% free, 23MB/32MB, paused 807us total 224.978ms
,08-29 08:37:32.503  3925  3976 W jxcore-log: Initializing JXcore engine
,08-29 08:37:32.503  3925  3976 W jxcore-log: JXcore engine is ready
,08-29 08:37:32.554  3976  3976 W Thread-358: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8946 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 08:37:32.554  3976  3976 W Thread-358: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11636]" dev="sockfs" ino=11636 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 08:37:32.554  3976  3976 W Thread-358: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 08:37:32.554  3976  3976 W Thread-358: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25291]" dev="sockfs" ino=25291 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 08:37:32.569  3925  3976 W jxcore-log: Starting JXcore engine
,08-29 08:37:32.673  3925  3976 W jxcore-log: Platform android
08-29 08:37:32.673  3925  3976 W jxcore-log: 
,08-29 08:37:32.673  3925  3976 W jxcore-log: Process ARCH arm
08-29 08:37:32.673  3925  3976 W jxcore-log: 
,08-29 08:37:32.857  3925  3976 I jxcore-log: JXcore Cordova bridge is ready!
08-29 08:37:32.857  3925  3976 I jxcore-log: 
,08-29 08:37:32.857  3925  3976 W jxcore-log: JXcore engine is started
,08-29 08:37:32.868  3925  3967 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 08:37:32.874  3925  3925 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 08:37:34.200  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 08:37:34.205  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 08:37:34.238  1507  2282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 08:37:34.238  1507  2282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 08:37:34.238  1507  2282 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 08:37:34.238  1507  2282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:34.259  3722  3979 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 08:37:34.259  3722  3979 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jdm.a(PG:82)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jcs.o(PG:406)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jcn.a(PG:1379)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jcs.i(PG:143)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at blb.a(PG:3937)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at czp.a(PG:18188)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at czp.a(PG:9081)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at czq.run(PG:1686)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 08:37:34.259  3722  3979 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jdj.a(PG:4091)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jdj.a(PG:1125)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jdm.a(PG:77)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	... 12 more
08-29 08:37:34.259  3722  3979 E HttpOperation: Caused by: faj: BadAuthentication
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at fal.a(PG:38)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	at jdj.a(PG:4089)
08-29 08:37:34.259  3722  3979 E HttpOperation: 	... 14 more
,08-29 08:37:34.318  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 08:37:34.319  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 08:37:34.319  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 08:37:34.319  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:34.337  3722  3979 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 08:37:34.337  3722  3979 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jdm.a(PG:82)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jcs.o(PG:406)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jcn.a(PG:1379)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jcs.i(PG:143)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at hec.a(PG:42)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at hee.a(PG:102)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at czr.a(PG:65)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at kka.a(PG:108)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at czp.a(PG:19176)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at czp.a(PG:9081)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at czq.run(PG:1686)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 08:37:34.337  3722  3979 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jdj.a(PG:4091)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jdj.a(PG:1125)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jdm.a(PG:77)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	... 15 more
08-29 08:37:34.337  3722  3979 E HttpOperation: Caused by: faj: BadAuthentication
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at fal.a(PG:38)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	at jdj.a(PG:4089)
08-29 08:37:34.337  3722  3979 E HttpOperation: 	... 17 more
,08-29 08:37:34.337  3722  3979 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 08:37:34.337  3722  3979 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at hec.a(PG:42)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at hee.a(PG:102)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at czr.a(PG:65)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at kka.a(PG:108)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	... 15 more
08-29 08:37:34.337  3722  3979 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at fal.a(PG:38)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 08:37:34.337  3722  3979 E ExperimentLoader: 	... 17 more
,08-29 08:37:34.431   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 128540, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 08:37:34.461  3343  3981 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 08:37:34.475  3343  3982 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 08:37:34.506  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 08:37:34.506  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 08:37:34.506  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 08:37:34.506  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:34.567  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 08:37:34.567  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 08:37:34.567  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 08:37:34.568  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:34.604  3343  3982 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 08:37:34.605  3343  3981 E BooksSync: Soft error
08-29 08:37:34.605  3343  3981 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 08:37:34.605  3343  3981 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 08:37:34.605  3343  3981 E BooksSync: Sync error
08-29 08:37:34.605  3343  3981 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 08:37:34.605  3343  3981 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 08:37:34.605  3343  3981 I BooksSync: Finished books sync
,08-29 08:37:34.613   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128640, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 08:37:35.879   871  2073 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:37:42.885  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 08:37:42.885  3925  3976 I jxcore-log: 
,08-29 08:37:42.887  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 08:37:42.887  3925  3976 I jxcore-log: 
,08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:42.898  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:42.903  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:37:42.905  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 08:37:42.905  3925  3976 I jxcore-log: 
,08-29 08:37:42.907  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 08:37:42.907  3925  3976 I jxcore-log: 
,08-29 08:37:43.403  3925  3976 D executeNativeTests: Running unit tests
,08-29 08:37:43.462  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:37:43.462  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e added. We now have 2 listener(s)
,08-29 08:37:43.463  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:37:43.463  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:37:43.463  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:37:43.463  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:37:43.463  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff added. We now have 2 listener(s)
08-29 08:37:43.463  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:37:43.464  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:37:43.466  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:43.473  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:43.477  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:37:43.477  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:37:43.483  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:43.486  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 08:37:43.488  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:43.489  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 08:37:43.490  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 08:37:43.499  3925  3976 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 08:37:43.501  3925  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 08:37:43.502  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:37:43.503  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:43.503  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 08:37:43.504  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:43.505  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.506  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:43.506  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.507  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.507  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:43.507  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:37:43.508  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e removed from the list
08-29 08:37:43.508  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.508  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff removed from the list
08-29 08:37:43.508  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.509  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.514  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.514  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.518  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.519  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.519  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.520  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.524  3925  3976 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 08:37:43.526  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.526  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.526  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.527  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:43.527  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.527  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.527  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.527  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.527  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.528  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.528  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.528  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.528  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.529  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.531  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.531  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:37:43.531  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.531  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:37:43.540  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:37:43.541  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 08:37:43.542  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 08:37:43.542  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:37:43.542  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:37:43.542  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:37:43.542  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:37:43.542  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.542  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.542  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.542  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.542  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.542  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.542  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.542  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.542  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.543  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.543  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.543  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.543  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.543  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.544  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.545  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.545  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.545  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.545  3925  3976 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 08:37:43.547  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:43.556  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:43.559  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.559  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:43.559  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:37:43.559  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:37:43.559  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:37:43.559  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:43.559  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:37:43.561  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.564  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.570  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:37:43.570  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:37:43.587  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 08:37:43.593  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:37:43.595  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 08:37:43.602  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 08:37:43.610  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 08:37:43.611  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:37:43.611  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:37:43.616  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 08:37:43.618  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:37:43.626  2873  3080 D BtGatt.GattService: registerClient() - UUID=2c756b2a-ea9b-4798-88f3-0edcbbeac8ee
,08-29 08:37:43.628  2873  2919 D BtGatt.GattService: onClientRegistered() - UUID=2c756b2a-ea9b-4798-88f3-0edcbbeac8ee, clientIf=5
,08-29 08:37:43.630  3925  3937 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:37:43.633  2873  2886 D BtGatt.GattService: start scan with filters
,08-29 08:37:43.642  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:37:43.642  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:37:43.643  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:37:43.643  2873  2933 D BtGatt.ScanManager: handling starting scan
08-29 08:37:43.643  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:37:43.646  2873  2933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:43.652  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:37:43.653  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:37:43.655  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 08:37:43.660  2873  2919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:37:43.660  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.661  2873  2933 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:37:43.663  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:37:43.671  3925  3976 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 08:37:43.671  2873  2919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 08:37:43.671  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:37:43.672  2873  2933 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:37:43.672  2873  2933 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 08:37:43.676  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.676  3925  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 08:37:43.676  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.676  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 08:37:43.676  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.676  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:37:43.676  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:37:43.676  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 08:37:43.677  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 08:37:43.677  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:37:43.677  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:37:43.678  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 08:37:43.678  3925  3976 D BluetoothAdapter: STATE_ON
08-29 08:37:43.679  2873  3078 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:37:43.680  2873  2884 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:37:43.680  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:43.681  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:37:43.681  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:37:43.681  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 08:37:43.681  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:37:43.682  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:43.683  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:37:43.683  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:37:43.683  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:37:43.684  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:37:43.686  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:37:43.686  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:43.687  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:43.687  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:43.687  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.687  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:37:43.687  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.687  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.687  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.687  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:43.687  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.688  3925  3976 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 08:37:43.691  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:43.697  2873  2919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:37:43.697  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:43.698  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:43.703  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:37:43.703  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:43.704  2873  2919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:37:43.704  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.705  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:37:43.706  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:37:43.706  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:37:43.706  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:43.706  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:37:43.708  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:43.712  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.713  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:37:43.713  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:37:43.714  2873  2919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 08:37:43.714  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.715  2873  2933 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:37:43.717  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:37:43.719  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:37:43.719  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:37:43.722  2873  2919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:37:43.722  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:37:43.722  2873  2933 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:37:43.725  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 08:37:43.725  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:37:43.725  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:37:43.726  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:37:43.728  2873  3080 D BtGatt.GattService: registerClient() - UUID=1010e49e-7aa0-4f7c-be3f-6ebbbccad6a4
08-29 08:37:43.729  2873  2919 D BtGatt.GattService: onClientRegistered() - UUID=1010e49e-7aa0-4f7c-be3f-6ebbbccad6a4, clientIf=5
,08-29 08:37:43.729  3925  3937 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:37:43.729  2873  3091 D BtGatt.GattService: start scan with filters
,08-29 08:37:43.732  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:37:43.732  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 08:37:43.732  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:37:43.732  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:37:43.734  2873  2919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-29 08:37:43.734  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.735  2873  2919 D BtGatt.GattService: current time is 138359371864
08-29 08:37:43.735  2873  2919 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 08:37:43.735  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:37:43.735  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:37:43.735  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:37:43.736  2873  2919 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 08:37:43.737  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 08:37:43.737  2873  2933 D BtGatt.ScanManager: handling starting scan
,08-29 08:37:43.740  3925  3976 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 08:37:43.743  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.743  3925  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:37:43.743  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.743  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 08:37:43.743  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.743  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:37:43.743  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:37:43.743  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:37:43.743  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:37:43.743  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:37:43.744  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:37:43.744  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 08:37:43.744  3925  3976 D BluetoothAdapter: STATE_ON
08-29 08:37:43.745  2873  2886 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:37:43.745  2873  2919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:37:43.745  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:37:43.746  2873  3080 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:37:43.746  2873  2933 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:37:43.746  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:43.746  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:37:43.746  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:37:43.746  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 08:37:43.747  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:37:43.748  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:37:43.748  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:37:43.748  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:37:43.748  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:37:43.749  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:37:43.750  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:43.751  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:43.751  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:43.751  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:43.751  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.751  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:43.751  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.751  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.751  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.751  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.751  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.752  2873  2919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 08:37:43.752  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.752  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.752  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.752  2873  2933 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:37:43.752  2873  2933 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:37:43.753  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.753  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.753  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.753  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.754  3925  3976 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 08:37:43.755  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:43.761  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:37:43.763  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:37:43.763  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:43.764  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:37:43.764  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:37:43.764  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:37:43.764  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:37:43.764  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:37:43.764  2873  2919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 08:37:43.764  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.766  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.769  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.770  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 08:37:43.770  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:37:43.771  2873  2919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:37:43.771  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:37:43.778  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:37:43.779  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 08:37:43.779  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:37:43.779  2873  2919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 08:37:43.780  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.780  2873  2933 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:37:43.783  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 08:37:43.783  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 08:37:43.783  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:37:43.784  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:37:43.787  2873  3080 D BtGatt.GattService: registerClient() - UUID=2d4661ef-85fe-41c4-af56-00c057b2493b
,08-29 08:37:43.787  2873  2919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:37:43.787  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.787  2873  2919 D BtGatt.GattService: onClientRegistered() - UUID=2d4661ef-85fe-41c4-af56-00c057b2493b, clientIf=5
08-29 08:37:43.787  2873  2933 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 08:37:43.788  3925  3966 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:37:43.788  2873  3091 D BtGatt.GattService: start scan with filters
,08-29 08:37:43.792  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:37:43.792  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:37:43.792  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:37:43.792  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:37:43.794  2873  2919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:37:43.794  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.795  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:37:43.795  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:37:43.795  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:37:43.796  2873  2933 D BtGatt.ScanManager: handling starting scan
,08-29 08:37:43.797  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:37:43.801  3925  3976 I io.jxcore.node.ConnectionHelper: start: OK
08-29 08:37:43.801  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:43.801  3925  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:37:43.801  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.801  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 08:37:43.801  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.801  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 08:37:43.801  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 08:37:43.801  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:37:43.801  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:37:43.801  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:37:43.802  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:37:43.802  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:37:43.802  2873  2919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 08:37:43.803  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.803  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:37:43.803  2873  2933 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:37:43.803  2873  3091 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:37:43.804  2873  2884 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:37:43.804  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:37:43.805  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 08:37:43.805  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:37:43.805  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:37:43.805  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:37:43.806  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:43.806  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 08:37:43.806  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:37:43.806  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:37:43.806  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:37:43.807  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:37:43.808  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:43.808  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:37:43.808  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.808  3925  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 08:37:43.808  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.808  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.809  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:43.809  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.809  2873  2919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 08:37:43.809  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:37:43.809  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.809  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.809  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.809  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.809  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.809  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.809  2873  2933 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:37:43.809  2873  2933 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:37:43.810  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.810  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.813  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.813  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.813  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.813  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.815  3925  3976 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 08:37:43.817  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:43.818  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.818  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.818  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:37:43.819  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.819  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.821  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.821  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.821  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.822  2873  2919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:37:43.822  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.822  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.822  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.824  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.824  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.825  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.827  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.827  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.827  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.827  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.828  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 08:37:43.828  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.828  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:37:43.828  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.829  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.829  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.829  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.829  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.829  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.830  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.830  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.830  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.830  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.835  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.835  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.836  2873  2919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:37:43.836  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.836  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.836  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:37:43.837  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.837  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.838  3925  3976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 08:37:43.838  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.838  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:37:43.838  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.839  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.840  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.840  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.840  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.840  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.840  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.840  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.840  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.840  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.840  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.841  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.842  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:37:43.842  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.842  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.842  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.843  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 08:37:43.843  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.843  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.843  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.843  2873  2919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 08:37:43.843  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.844  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.844  2873  2933 D BtGatt.ScanManager: stopping BLe Batch
08-29 08:37:43.844  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.844  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.844  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.844  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.844  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.844  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.844  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.844  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.845  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.845  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.846  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.846  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.847  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.847  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.848  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:37:43.848  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:37:43.848  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:37:43.849  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:43.849  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 08:37:43.849  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 08:37:43.849  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:43.849  2873  2919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:37:43.849  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:37:43.849  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.849  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:37:43.850  2873  2933 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 08:37:43.850  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.850  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.850  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.850  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
,08-29 08:37:43.850  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.850  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.850  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.850  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.850  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.851  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.851  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.852  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.852  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.852  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.852  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.853  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:43.853  3925  3976 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:37:43.853  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 08:37:43.856  2873  2919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:37:43.856  2873  2919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:37:43.857  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:43.857  3925  3976 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-29 08:37:43.857  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 08:37:43.858  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 08:37:43.859  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 08:37:43.860  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 08:37:43.860  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 08:37:43.860  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 08:37:43.860  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 08:37:43.860  3925  3976 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:37:43.860  3925  3976 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 08:37:43.860  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 08:37:43.860  3925  3976 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:37:43.860  3925  3976 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 08:37:43.861  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 08:37:43.861  3925  3976 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 08:37:43.861  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 08:37:43.864  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 08:37:43.865  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 08:37:43.865  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 08:37:43.865  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 08:37:43.865  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 08:37:43.865  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 08:37:43.866  3925  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 08:37:43.866  3925  3976 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 08:37:43.866  3925  3992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 422)
08-29 08:37:43.867  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:43.867  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:37:43.867  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.867  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.867  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.867  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.867  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 08:37:43.868  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.868  3925  3992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:43.868  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.868  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.869  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.869  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.869  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.869  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.869  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.870  3925  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 422
08-29 08:37:43.870  3925  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 422)
08-29 08:37:43.870  3925  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 422)
08-29 08:37:43.871  3925  3992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 422)
08-29 08:37:43.872  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.875  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.875  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.876  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.878  3925  3976 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-29 08:37:43.880  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.880  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.880  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.880  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.880  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.880  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.881  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.881  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.881  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.881  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.881  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.882  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.882  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.882  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.884  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.884  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.884  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.884  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.884  3925  3976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 08:37:43.885  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.885  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.885  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.885  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.885  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.885  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.885  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.885  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.885  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.885  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.885  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.885  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.885  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.886  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.887  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.887  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.887  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.887  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.887  3925  3976 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 08:37:43.887  3925  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 08:37:43.887  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:37:43.887  3925  3976 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 08:37:43.887  3925  3976 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-29 08:37:43.888  3925  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 08:37:43.888  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:37:43.888  3925  3976 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 08:37:43.888  3925  3976 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 08:37:43.888  3925  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 08:37:43.888  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 08:37:43.888  3925  3976 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 08:37:43.888  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.888  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.888  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.888  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.888  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.888  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.888  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.889  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.889  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.889  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.889  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.889  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.889  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.889  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.891  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.891  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.891  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.891  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.891  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.891  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.891  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.892  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.892  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.892  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.892  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.892  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.892  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.892  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.892  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.892  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.892  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.892  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.892  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
,08-29 08:37:43.892  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.892  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.893  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.893  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.893  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.893  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.893  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.893  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.893  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.893  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.893  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.893  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.893  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.893  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.894  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.894  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.894  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.895  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.896  3925  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 08:37:43.896  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:37:43.897  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 08:37:43.898  3925  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 08:37:43.898  3925  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 08:37:43.898  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-29 08:37:43.898  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:37:43.898  3925  3925 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 08:37:43.898  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.898  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 08:37:43.899  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 08:37:43.899  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 08:37:43.899  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.899  3925  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 08:37:43.899  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
,08-29 08:37:43.899  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.899  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:37:43.899  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:37:43.899  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:37:43.899  3925  3925 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 08:37:43.899  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.899  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.900  3925  3995 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 08:37:43.901  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:37:43.901  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.901  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.901  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.901  3925  3995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 08:37:43.901  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 08:37:43.901  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.901  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:37:43.901  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.901  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:37:43.901  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.901  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:37:43.902  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.902  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.902  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.902  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.902  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.902  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.902  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.902  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.902  3925  3925 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 08:37:43.903  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.903  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.903  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.903  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.904  3925  3976 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 08:37:43.904  3925  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 08:37:43.904  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 08:37:43.904  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 08:37:43.905  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:37:43.905  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.905  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.905  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.905  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.905  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.905  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.905  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.905  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.905  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.905  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.905  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.905  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.905  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.906  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.906  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.907  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:37:43.907  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.911  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.911  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.911  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.911  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.912  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.912  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.912  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.912  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.912  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.912  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:37:43.912  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.912  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.913  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.913  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.914  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.914  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.914  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.914  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.916  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:37:43.916  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:37:43.916  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:37:43.916  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:37:43.916  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.916  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.917  3925  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a73b1e not in the list
08-29 08:37:43.917  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.917  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
08-29 08:37:43.917  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:43.917  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.917  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:37:43.917  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:37:43.917  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:43.919  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:37:43.919  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:37:43.919  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:37:43.919  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6b7fff not in the list
,08-29 08:37:43.921  3925  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 08:37:43.921  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:37:43.921  3925  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 08:37:43.921  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 08:37:43.921  3925  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 08:37:43.921  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 08:37:43.924  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 08:37:43.924  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 08:37:43.925  3925  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 08:37:43.925  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:37:43.926  3925  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 08:37:43.926  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 08:37:43.926  3925  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 08:37:43.926  3925  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-29 08:37:43.927  3925  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 08:37:43.927  3925  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 08:37:43.928  3925  3976 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 08:37:43.928  3925  3976 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-29 08:37:43.928  3925  3976 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 08:37:43.928  3925  3976 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 08:37:43.930  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:43.930  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59ff4c9 added. We now have 2 listener(s)
08-29 08:37:43.930  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:37:43.932  3925  3976 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 08:37:43.932   871   881 D WifiService: setWifiEnabled: true pid=3925, uid=10000
08-29 08:37:43.932   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:37:43.933  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:43.933  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e26a7ce added. We now have 3 listener(s)
08-29 08:37:43.933  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:37:43.939  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:43.939  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ea66ef added. We now have 4 listener(s)
08-29 08:37:43.939  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:37:43.941  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:37:43.941  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f04d5fc added. We now have 5 listener(s)
,08-29 08:37:43.941  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:37:43.943   871  1994 D WifiService: setWifiEnabled: false pid=3925, uid=10000
08-29 08:37:43.943   871  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:37:43.947  2873  2911 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 08:37:43.947  2873  2911 D BluetoothAdapterProperties: Setting state to 13
08-29 08:37:43.947  2873  2911 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 08:37:43.948  2873  2911 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 08:37:43.948  2873  2911 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:37:43.948  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:37:43.951  2873  2919 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:37:43.951  2873  2911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 08:37:43.953  2873  2873 D BluetoothMapService: onReceive
08-29 08:37:43.953  2873  2873 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 08:37:43.953  2873  2873 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:37:43.953  2873  2873 D BluetoothMapService: MAP Service closeService in
08-29 08:37:43.954  2873  2873 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 08:37:43.954  2873  2873 D ObexServerSockets0: shutdown(block = true)
08-29 08:37:43.954  2873  2873 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:37:43.954  2873  2873 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:37:43.954  2873  3093 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 08:37:43.955  2873  3075 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 08:37:43.955  2873  3094 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 08:37:43.955  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:43.955  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:43.956  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:43.956  2873  2873 I BtOppRfcommListener: stopping Accept Thread
,08-29 08:37:43.956  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:37:43.956  2873  3633 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:43.956  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 08:37:43.957  2873  3633 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 08:37:43.958  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 08:37:43.959   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 08:37:43.959   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 08:37:43.959   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 08:37:43.959   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:37:43.962  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.966  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:43.968  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:43.968  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:43.969  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:43.969  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:43.969   871  2076 D DhcpClient: Clearing IP address
08-29 08:37:43.969   369   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:37:43.971  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:43.972   369   870 D CommandListener: Setting iface cfg
,08-29 08:37:43.973  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.973   871   884 I ActivityManager: Start proc 3998:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 08:37:43.976  1507  2542 V NativeCrypto: Read error: ssl=0x9b3b5000: I/O error during system call, Connection timed out
08-29 08:37:43.977  2873  2873 D HeadsetService: Received stop request...Stopping profile...
08-29 08:37:43.977  1507  2542 V NativeCrypto: SSL shutdown failed: ssl=0x9b3b5000: I/O error during system call, Broken pipe
08-29 08:37:43.978  1371  1382 D BluetoothHeadset: Proxy object disconnected
,08-29 08:37:43.978   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:43.979  1956  2142 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:43.979   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:43.979   871   871 D BluetoothHeadset: Proxy object disconnected
,08-29 08:37:43.981   871  1969 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 08:37:43.981   871  2066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-29 08:37:43.981  2873  2873 D A2dpService: Received stop request...Stopping profile...
,08-29 08:37:43.981  2873  3084 D A2dpStateMachine: Exit Disconnected: -1
,08-29 08:37:43.982  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:43.984   871  2066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 08:37:43.985   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 08:37:43.985   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 08:37:43.986  2873  2873 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:43.986   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 08:37:43.986  2873  2873 V BluetoothAdapterState: isTurningOn()=false
,08-29 08:37:43.986  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:43.986  2873  2873 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:43.986   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:37:43.987  2873  2873 D HidService: Received stop request...Stopping profile...
08-29 08:37:43.987  2873  2873 D HidService: Stopping Bluetooth HidService
,08-29 08:37:43.987   871   871 D BluetoothA2dp: Proxy object disconnected
,08-29 08:37:43.990   369   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:37:43.991   394   394 E Parcel  : Reading a NULL string not supported here.
08-29 08:37:43.992   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 08:37:43.992   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:37:43.992   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 08:37:43.995  1371  1371 D HeadsetProfile: Bluetooth service disconnected
,08-29 08:37:43.995  2873  2873 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
,08-29 08:37:43.995  2873  2873 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 08:37:43.995  1371  1371 D BluetoothA2dp: Proxy object disconnected
08-29 08:37:43.996  2873  3054 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:43.996  2873  3054 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:37:43.996  2873  3054 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:43.996  2873  2919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 08:37:43.997  2873  2919 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 08:37:43.997  1371  1371 D BluetoothInputDevice: Proxy object disconnected
08-29 08:37:43.997  1371  1371 D HidProfile: Bluetooth service disconnected
08-29 08:37:43.998  2873  2873 D HealthService: Received stop request...Stopping profile...
08-29 08:37:44.000   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-29 08:37:44.003  2873  2873 D PanService: Received stop request...Stopping profile...
08-29 08:37:44.005  2873  2873 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:37:44.005  2873  2873 D BluetoothMapService: stop()
08-29 08:37:44.005  2873  2873 D BluetoothMapAppObserver: deinitObservers()
08-29 08:37:44.005  2873  2873 D BluetoothMapAppObserver: removeReceiver()
08-29 08:37:44.006  2873  2873 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:44.006  2873  2873 V BluetoothAdapterState: isTurningOn()=false
,08-29 08:37:44.006  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:44.006  2873  2873 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:44.007  2873  2919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 08:37:44.007  2873  3054 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:44.007  2873  3054 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:44.007  2873  2873 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:44.007  2873  2873 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:44.007  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:44.007  2873  2873 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:44.008  2873  3054 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:44.008  2873  3054 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 08:37:44.008  2873  3054 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:44.008  2873  3054 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 08:37:44.011   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 08:37:44.012  2873  2873 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 08:37:44.012  2873  2919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:37:44.012  2873  2873 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:37:44.013   871  2081 D DhcpClient: Receive thread stopped
08-29 08:37:44.014  2873  2873 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:44.014  2873  2873 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:44.014  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:44.014  2873  2873 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:44.014  2873  2873 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:37:44.014  2873  2919 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 08:37:44.014  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:44.015  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:44.015  2873  2873 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:37:44.015  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:44.015  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:44.016  2873  2873 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:44.016  2873  2873 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:44.016  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:44.016  2873  2873 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:44.016  2873  2873 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 08:37:44.017  2873  2873 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 08:37:44.018   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 08:37:44.020  2873  2873 D BluetoothMapService: MAP Service closeService in
08-29 08:37:44.020  2873  2873 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:44.020  2873  2873 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:44.020  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:44.020  2873  2873 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:44.020  2873  2911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 08:37:44.020  2873  2873 D BluetoothMapService: cleanup()
,08-29 08:37:44.021  2873  2873 D BluetoothMapService: MAP Service closeService in
08-29 08:37:44.021  2873  2911 D BluetoothAdapterProperties: Setting state to 15
08-29 08:37:44.021  2873  2911 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 08:37:44.021  1889  2301 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:44.021  2873  2911 I BluetoothAdapterState: Entering BleOnState
08-29 08:37:44.021  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:37:44.021  1371  1371 D PanProfile: Bluetooth service disconnected
08-29 08:37:44.021  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:44.021  1371  1371 D BluetoothMap: Proxy object disconnected
,08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:44.021  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:44.021  1371  1371 D MapProfile: Bluetooth service disconnected
08-29 08:37:44.023   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:44.023  1371  1382 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:37:44.024  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:44.024  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:44.024  1371  1383 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:44.024   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:37:44.024  1371  2084 D BluetoothPan: onBluetoothStateChange on: false
08-29 08:37:44.025  1371  1382 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:37:44.025  1956  1973 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:44.025   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:44.025  1371  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:37:44.026  1371  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:37:44.027   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:44.027  2873  2911 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 08:37:44.027  2873  2911 D BluetoothAdapterProperties: Setting state to 16
,08-29 08:37:44.027  2873  2911 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 08:37:44.027  2873  2911 D BluetoothAdapterProperties: onBleDisable
08-29 08:37:44.028  2873  2911 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:37:44.028  2873  2916 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 08:37:44.029  2873  2919 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:37:44.031  2873  3054 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 08:37:44.031  2873  3054 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:44.034  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.035  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.036  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.037  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:44.049   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:37:44.060  3998  3998 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 08:37:44.065   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:37:44.066   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-29 08:37:44.066   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:44.069   871   888 D Tethering: MasterInitialState.processMessage what=3
08-29 08:37:44.073  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:44.073  3565  3565 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@26df3ce and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 08:37:44.074  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:44.080  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:37:44.085   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4a701f5:true
,08-29 08:37:44.085  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:44.098   871  1429 I ActivityManager: Start proc 4018:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 08:37:44.107  3998  3998 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 08:37:44.109  3998  3998 D BluetoothMap: Create BluetoothMap proxy object
,08-29 08:37:44.111   369   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 08:37:44.112   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 08:37:44.120  3998  3998 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 08:37:44.128  4018  4018 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 08:37:44.131  3998  3998 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:44.138   871  1699 I ActivityManager: Killing 2753:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 08:37:44.232  2873  2919 I bt_hci  : shut_down
,08-29 08:37:44.238  2873  2942 I bt_vendor: low_power_mode_cb
,08-29 08:37:44.240  2873  2942 D bt_hwcfg: hw_epilog_process
,08-29 08:37:44.265  2873  2942 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 08:37:44.265  2873  2942 I bt_vendor: epilog_cb
,08-29 08:37:44.265  2873  2942 I bt_hci  : epilog_finished_callback
,08-29 08:37:44.270  2873  2919 I bt_hci_h4: hal_close
,08-29 08:37:44.271  2873  2919 I bt_userial_vendor: device fd = 51 close
,08-29 08:37:44.344  4018  4018 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 08:37:44.344  4018  4018 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.344  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 08:37:44.345  4018  4018 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 08:37:44.345  4018  4018 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:37:44.345  4018  4018 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:37:44.345  4018  4018 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:37:44.345  4018  4018 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.345,  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:37:44.345  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:37:44.351  4018  4018 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
,08-29 08:37:44.351  4018  4018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 08:37:44.393   871  2007 I ActivityManager: Start proc 4049:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 08:37:44.394   871  2007 I ActivityManager: Killing 3565:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 08:37:44.402  3925  3925 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:37:44.502  4018  4036 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 08:37:44.567  2873  2916 D bt_stack_manager: event_shut_down_stack finished.
,08-29 08:37:44.567  2873  2911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 08:37:44.571  2873  2873 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:37:44.571  2873  2911 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 08:37:44.571  2873  2873 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 08:37:44.571  2873  2873 D BtGatt.GattService: stop()
,08-29 08:37:44.571  2873  2873 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 08:37:44.573  2873  2873 V BluetoothAdapterState: isTurningOff()=false,
08-29 08:37:44.574  2873  2873 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:44.574  2873  2873 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:37:44.574  2873  2873 V BluetoothAdapterState: isBleTurningOff()=true
08-29 08:37:44.574  2873  2911 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 08:37:44.574  2873  2911 D BluetoothAdapterProperties: Setting state to 10
,08-29 08:37:44.575  2873  2911 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 08:37:44.576   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 08:37:44.576  2873  2911 I BluetoothAdapterState: Entering OffState
,08-29 08:37:44.578  4049  4049 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 08:37:44.582  2873  2873 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 08:37:44.582  2873  2873 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 08:37:44.582  2873  2873 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 08:37:44.583  2873  2916 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 08:37:44.585  2873  2916 D bt_stack_manager: event_clean_up_stack finished.
,08-29 08:37:44.590  2873  2873 I art     : System.exit called, status: 0
,08-29 08:37:44.590  2873  2873 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 08:37:44.590   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48634bf:true
,08-29 08:37:44.638   871   882 I ActivityManager: Process com.android.bluetooth (pid 2873) has died
,08-29 08:37:44.657  4049  4049 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 08:37:44.677  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:37:44.701   871  1429 I ActivityManager: Start proc 4079:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 08:37:44.704  3998  3998 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:44.805  4079  4079 D AdapterServiceConfig: Adding HeadsetService
08-29 08:37:44.806  4079  4079 D AdapterServiceConfig: Adding A2dpService
08-29 08:37:44.806  4079  4079 D AdapterServiceConfig: Adding HidService
08-29 08:37:44.806  4079  4079 D AdapterServiceConfig: Adding HealthService
08-29 08:37:44.806  4079  4079 D AdapterServiceConfig: Adding PanService
08-29 08:37:44.806  4079  4079 D AdapterServiceConfig: Adding GattService
08-29 08:37:44.806  4079  4079 D AdapterServiceConfig: Adding BluetoothMapService
08-29 08:37:44.809   871  1394 I ActivityManager: Killing 3459:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 08:37:44.868  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:44.895  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 08:37:44.899  1716  1716 D SystemUpdateService: onCreate
,08-29 08:37:44.901  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 08:37:44.906  1716  4091 I SystemUpdateService: active receiver: enabled
,08-29 08:37:44.908  1716  4091 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 08:37:44.916  1716  4091 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 08:37:44.916  1716  4091 I SystemUpdateService: now status is 0 (complete)
08-29 08:37:44.916  1716  4091 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 08:37:44.916  1716  4091 I SystemUpdateService: file has been verified
,08-29 08:37:44.916  1716  4091 I SystemUpdateService: OTA package size = 12249756
,08-29 08:37:44.919  1716  4091 I SystemUpdateService: showing system update notification
,08-29 08:37:44.945  1716  1716 D SystemUpdateService: onDestroy
,08-29 08:37:44.950  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 08:37:44.953  1716  2519 I iu.UploadsManager: num queued entries: 0
,08-29 08:37:44.953  1716  2519 I iu.UploadsManager: num updated entries: 0
,08-29 08:37:44.955  1716  2519 I iu.SyncManager: NEXT; no task
,08-29 08:37:44.957  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 08:37:44.961  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 08:37:44.976   871  4062 I ActivityManager: Start proc 4093:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 08:37:45.026  4093  4093 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 08:37:45.029  4093  4093 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:45.034  4093  4093 D SprintDMHelper: simOperator: 
08-29 08:37:45.034  4093  4093 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:37:45.061   871  1394 I ActivityManager: Start proc 4105:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 08:37:45.063   871  1394 I ActivityManager: Killing 3241:android.process.acore/u0a5 (adj 15): empty #17
,08-29 08:37:45.214   871  1910 I ActivityManager: Start proc 4120:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 08:37:45.217  2833  4119 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 08:37:45.222   871   881 I ActivityManager: Killing 3809:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 08:37:45.276   871   880 I art     : Background partial concurrent mark sweep GC freed 32708(1833KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.121ms total 100.587ms
,08-29 08:37:45.300  4120  4120 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 08:37:45.355  4120  4120 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 08:37:45.355  4120  4120 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 08:37:45.355  4120  4120 I GAv4    :   adb logcat -s GAv4
,08-29 08:37:45.371  4120  4120 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 08:37:45.378  4120  4120 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 08:37:45.417  4120  4137 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 08:37:45.522  4120  4120 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 08:37:45.567  4120  4120 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 08:37:45.579  4120  4120 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 197-204)
,08-29 08:37:45.580  4120  4120 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 08:37:45.590  4120  4120 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {424ec7e}
,08-29 08:37:45.590  4120  4120 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 08:37:45.590  4120  4120 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 08:37:45.598  4120  4120 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 08:37:45.600  4120  4120 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 08:37:45.618  4120  4120 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 08:37:45.631  4120  4120 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 08:37:45.631  4120  4120 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 08:37:45.631  4120  4120 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 08:37:45.631  4120  4120 I Adreno  : Build Date                       : 10/20/15
08-29 08:37:45.631  4120  4120 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 08:37:45.631  4120  4120 I Adreno  : Local Branch                     : M14
08-29 08:37:45.631  4120  4120 I Adreno  : Remote Branch                    : 
08-29 08:37:45.631  4120  4120 I Adreno  : Remote Branch                    : 
08-29 08:37:45.631  4120  4120 I Adreno  : Reconstruct Branch               : 
,08-29 08:37:45.697  4120  4120 I NSApplication: Starting up...
,08-29 08:37:45.709  4120  4166 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 08:37:45.745   871   881 I ActivityManager: Start proc 4171:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 08:37:45.746   871   881 I ActivityManager: Killing 3825:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 08:37:45.817  4171  4171 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 08:37:46.027   871   882 I ActivityManager: Killing 3590:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 08:37:46.959   871  2005 D WifiService: setWifiEnabled: true pid=3925, uid=10000
,08-29 08:37:46.959   871  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:37:46.977   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-29 08:37:46.985  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:46.986  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:46.986  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:46.986  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:46.990  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:46.990  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:37:46.990  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:46.991  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:37:47.009   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-29 08:37:47.010   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 08:37:47.011   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 08:37:47.012   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 08:37:47.012   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 08:37:47.012   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 08:37:47.012   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 08:37:47.027   369   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 08:37:47.028   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.75 rxSuccessRate=15.88 delta 1000 -> 994
08-29 08:37:47.029   369   870 D CommandListener: Setting iface cfg
,08-29 08:37:47.030   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-29 08:37:47.030   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 08:37:47.037   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 08:37:47.037   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:37:47.038   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 08:37:47.040   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 08:37:47.047   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 08:37:47.118   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 08:37:47.123  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 08:37:47.561  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 08:37:47.606  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 08:37:47.609  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 08:37:47.619   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 08:37:47.632   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:37:47.633   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 08:37:47.633   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 08:37:47.662   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:37:47.687   369   870 D CommandListener: Setting iface cfg
,08-29 08:37:47.688   871  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 08:37:47.715   871  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 08:37:47.721   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 08:37:47.728   871  4196 D DhcpClient: Receive thread started
,08-29 08:37:47.813   871  1313 E native  : do suspend false
,08-29 08:37:47.833   871  2076 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 08:37:47.847   871  4196 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172681, domain null
,08-29 08:37:47.848   871  2076 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172681 seconds
,08-29 08:37:47.854   871  2076 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 08:37:47.868   871  4196 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 08:37:47.869   871  2076 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 08:37:47.874   369   870 D CommandListener: Setting iface cfg
,08-29 08:37:47.887   871  2076 D DhcpClient: Scheduling renewal in 86399s
,08-29 08:37:47.887   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 08:37:47.906   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 08:37:47.907   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 08:37:47.907   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 08:37:47.908   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 08:37:47.909   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 08:37:47.917   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 08:37:47.967   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 08:37:47.968   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 08:37:47.969   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 08:37:47.971   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 08:37:47.973   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 08:37:47.986   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:47.990   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-29 08:37:47.990   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 08:37:47.990   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:47.990   871  1315 D ConnectivityService:    accepting network in place of null
,08-29 08:37:47.991   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 08:37:47.991   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:37:47.993   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 08:37:48.012   871  4195 D NetlinkSocketObserver: NeighborEvent{elapsedMs=142636, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:37:48.073   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:37:48.089   871  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:807::200e
,08-29 08:37:48.152   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:37:48.161   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 08:37:48.162   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:48.169   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:48.182   871   888 D Tethering: MasterInitialState.processMessage what=3
08-29 08:37:48.184   871  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 06:37:48 GMT], X-Android-Received-Millis=[1472452668181], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472452668141]}
08-29 08:37:48.190   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 08:37:48.191   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 08:37:48.191   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 08:37:48.192  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:48.192  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:48.192  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:48.192  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:48.192   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 08:37:48.194  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:37:48.194  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:37:48.195  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:48.195  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular,: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:37:48.200  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 08:37:48.203  1716  1716 D SystemUpdateService: onCreate
,08-29 08:37:48.211  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 08:37:48.214  1716  4207 I SystemUpdateService: active receiver: enabled
,08-29 08:37:48.216  1716  4207 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 08:37:48.220  1716  4207 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 08:37:48.220  1716  4207 I SystemUpdateService: now status is 0 (complete)
,08-29 08:37:48.221  1716  4207 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 08:37:48.221  1716  4207 I SystemUpdateService: file has been verified
08-29 08:37:48.223  1716  4207 I SystemUpdateService: OTA package size = 12249756
,08-29 08:37:48.230  1716  4207 I SystemUpdateService: showing system update notification
,08-29 08:37:48.233  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 08:37:48.235  1716  2519 I iu.UploadsManager: num queued entries: 0
08-29 08:37:48.236  1716  2519 I iu.UploadsManager: num updated entries: 0
,08-29 08:37:48.237  1716  4213 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 08:37:48.237  1716  4213 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 08:37:48.238  1716  4213 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 08:37:48.240  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 08:37:48.241  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 08:37:48.243  1716  2519 I iu.SyncManager: NEXT; no task
,08-29 08:37:48.243  4093  4093 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:48.246  4093  4093 D SprintDMHelper: simOperator: 
,08-29 08:37:48.246  4093  4093 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 08:37:48.246  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 08:37:48.248  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 08:37:48.253  1716  1716 D SystemUpdateService: onDestroy
,08-29 08:37:48.278  3270  4209 V KeepSync: Connecting to GoogleApiClient
,08-29 08:37:48.279   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 08:37:48.289  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 08:37:48.290  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 08:37:48.290  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 08:37:48.290  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:48.313  1716  4213 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-29 08:37:48.330  1507  2131 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 08:37:48.330  1507  2131 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 08:37:48.330  1507  2131 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 08:37:48.330  1507  2131 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:48.340  1716  4220 V BaseAuthAsyncOperation: access token request failed
,08-29 08:37:48.341  3270  4209 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 08:37:48.379  2833  4215 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 08:37:48.388  1507  2282 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 08:37:48.388  1507  2282 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 08:37:48.388  1507  2282 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 08:37:48.388  1507  2282 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:37:48.403  3270  4209 E KeepSync: IOException
08-29 08:37:48.403  3270  4209 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 08:37:48.403  3270  4209 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 08:37:48.403  3270  4209 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 08:37:48.403  3270  4209 E KeepSync: 	... 10 more
,08-29 08:37:48.403  3270  4209 W KeepSync: Sync result 2
,08-29 08:37:48.512   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130687, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 08:37:49.114   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-29 08:37:49.159   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 08:37:49.648   871  1968 I ActivityManager: Killing 3848:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 08:37:49.972   871  2005 D WifiService: setWifiEnabled: false pid=3925, uid=10000
08-29 08:37:49.973   871  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:37:50.012  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 08:37:50.023   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 08:37:50.024   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 08:37:50.024   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:37:50.025   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:37:50.046   871  2076 D DhcpClient: Clearing IP address
08-29 08:37:50.047   369   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 08:37:50.055  1507  4222 V NativeCrypto: Read error: ssl=0x9b3b5000: I/O error during system call, Connection timed out
,08-29 08:37:50.061  1507  4222 V NativeCrypto: SSL shutdown failed: ssl=0x9b3b5000: I/O error during system call, Broken pipe
08-29 08:37:50.068   369   870 D CommandListener: Setting iface cfg
08-29 08:37:50.070   871  1969 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-29 08:37:50.071   871  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-29 08:37:50.073   871  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:807::200e
08-29 08:37:50.084   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 08:37:50.084   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 08:37:50.086   871  4196 D DhcpClient: Receive thread stopped
08-29 08:37:50.090   394   394 E Parcel  : Reading a NULL string not supported here.
08-29 08:37:50.100   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 08:37:50.101   871  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:807::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-29 08:37:50.102   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 08:37:50.103   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 08:37:50.149   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:37:50.191   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:37:50.192   369   870 D CommandListener: Clearing all IP addresses on wlan0
08-29 08:37:50.192   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 08:37:50.193   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:50.199   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-29 08:37:50.200  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:50.200  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:37:50.200  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:50.200  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:50.202  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:50.202  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:37:50.202  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:50.202  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:50.206   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 08:37:50.211  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:50.211  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:50.212  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:50.212  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:50.216  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:50.216  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:50.216  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:50.216  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 08:37:50.216  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:37:50.217   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 08:37:50.220  1889  2301 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 08:37:50.223  1716  1716 D SystemUpdateService: onCreate
,08-29 08:37:50.231  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 08:37:50.244  1716  4232 I SystemUpdateService: active receiver: enabled
,08-29 08:37:50.246  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 08:37:50.252  1716  4232 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 08:37:50.254  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 08:37:50.255  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,08-29 08:37:50.259  4093  4093 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:37:50.264  4093  4093 D SprintDMHelper: simOperator: 
,08-29 08:37:50.264  4093  4093 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:37:50.277  1716  2519 I iu.UploadsManager: num queued entries: 0
,08-29 08:37:50.277  1716  2519 I iu.UploadsManager: num updated entries: 0
,08-29 08:37:50.283   369   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 08:37:50.284   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 08:37:50.284   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 08:37:50.286  1716  4232 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 08:37:50.286  1716  4232 I SystemUpdateService: now status is 0 (complete)
08-29 08:37:50.286  1716  4232 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 08:37:50.292  2833  4236 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 08:37:50.287  1716  4232 I SystemUpdateService: file has been verified
08-29 08:37:50.297  1716  4232 I SystemUpdateService: OTA package size = 12249756
,08-29 08:37:50.308  1716  2519 I iu.SyncManager: NEXT; no task
,08-29 08:37:50.311  1716  4232 I SystemUpdateService: showing system update notification
,08-29 08:37:50.360  1716  1716 D SystemUpdateService: onDestroy
,08-29 08:37:53.030  4079  4079 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 08:37:53.030   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a39ee0:true
,08-29 08:37:53.040  4079  4079 I bt_bluedroid: init
,08-29 08:37:53.040  4079  4241 I BluetoothAdapterState: Entering OffState
,08-29 08:37:53.045  4079  4242 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 08:37:53.045  4079  4242 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 08:37:53.045  4079  4242 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 08:37:53.046  4079  4242 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 08:37:53.046  4079  4079 I bt_bluedroid: get_profile_interface socket
08-29 08:37:53.048  4079  4079 I bt_bluedroid: get_profile_interface sdp
08-29 08:37:53.051  4079  4245 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 08:37:53.055  4079  4090 I bt_bluedroid: config_hci_snoop_log
,08-29 08:37:53.055  4079  4245 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 08:37:53.058   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 08:37:53.072  4079  4241 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 08:37:53.072  4079  4241 D BluetoothAdapterProperties: Setting state to 14
08-29 08:37:53.073  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 08:37:53.078  4079  4241 D BluetoothBondStateMachine: make
,08-29 08:37:53.083  4079  4246 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 08:37:53.090  4079  4241 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:37:53.093  4079  4079 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 08:37:53.099  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:53.100  4079  4079 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:37:53.101  4079  4079 D BtGatt.GattService: Received start request. Starting profile...
,08-29 08:37:53.102  4079  4079 D BtGatt.GattService: start()
,08-29 08:37:53.102  4079  4079 I bt_bluedroid: get_profile_interface gatt
,08-29 08:37:53.105  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
08-29 08:37:53.106  4079  4079 D BtGatt.AdvertiseManager: advertise manager created
,08-29 08:37:53.117  4079  4079 V BluetoothAdapterState: isTurningOff()=false
08-29 08:37:53.117  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:53.117  4079  4079 V BluetoothAdapterState: isBleTurningOn()=true
08-29 08:37:53.117  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:53.118  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 08:37:53.118  4079  4241 I bt_bluedroid: enable
,08-29 08:37:53.119  4079  4242 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 08:37:53.119  4079  4242 I bt_hci  : start_up
,08-29 08:37:53.128  4079  4242 I bt_vendor: alloc value 0xb39a9189
,08-29 08:37:53.128  4079  4242 I bt_vendor: init
,08-29 08:37:53.128  4079  4242 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 08:37:53.128  4079  4242 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 08:37:53.238  4079  4242 D bt_hci  : start_up starting async portion
,08-29 08:37:53.238  4079  4249 I bt_hci  : event_finish_startup
08-29 08:37:53.239  4079  4249 I bt_hci_h4: hal_open
,08-29 08:37:53.239  4079  4249 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 08:37:53.249  4079  4249 I bt_userial_vendor: device fd = 51 open
,08-29 08:37:53.279  4079  4249 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:37:53.311  4079  4249 D bt_hwcfg: Chipset BCM4354A2
,08-29 08:37:53.312  4079  4249 D bt_hwcfg: Target name = [BCM4354A2]
08-29 08:37:53.312  4079  4249 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 08:37:53.983  4079  4249 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 08:37:53.985  4079  4249 D bt_hwcfg: Settlement delay -- 100 ms
08-29 08:37:53.985  4079  4249 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 08:37:54.102  4079  4249 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:37:54.103  4079  4249 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 08:37:54.133  4079  4249 I bt_hwcfg: vendor lib fwcfg completed
,08-29 08:37:54.133  4079  4249 I bt_vendor: firmware callback
,08-29 08:37:54.133  4079  4249 I bt_hci  : firmware_config_callback
,08-29 08:37:54.144  4079  4251 I bt_btu  : btu_task pending for preload complete event
,08-29 08:37:54.145  4079  4251 I bt_btu_task: Bluetooth chip preload is complete
,08-29 08:37:54.145  4079  4251 I bt_btu  : btu_task received preload complete event
,08-29 08:37:54.155  4079  4251 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:37:54.156  4079  4251 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 08:37:54.156  4079  4251 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 08:37:54.156  4079  4251 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 08:37:54.157  4079  4251 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 08:37:54.157  4079  4251 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 08:37:54.157  4079  4251 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 08:37:54.157  4079  4251 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:37:54.158  4079  4251 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 08:37:54.158  4079  4251 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 08:37:54.158  4079  4251 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 08:37:54.158  4079  4251 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:37:54.159  4079  4251 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 08:37:54.159  4079  4251 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:37:54.159  4079  4251 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 08:37:54.290  4079  4251 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
08-29 08:37:54.291  4079  4251 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,08-29 08:37:54.303  4079  4245 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 08:37:54.304  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 08:37:54.305  4079  4245 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 08:37:54.309  4079  4245 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 08:37:54.312  4079  4245 D BluetoothAdapterProperties: Scan Mode:20
,08-29 08:37:54.313  4079  4245 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:37:54.314  4079  4245 D bt_hci  : do_postload posting postload work item
08-29 08:37:54.314  4079  4249 I bt_hci  : event_postload
08-29 08:37:54.314  4079  4249 I bt_vendor: sco_config_cb
08-29 08:37:54.314  4079  4249 I bt_hci  : sco_config_callback postload finished.
,08-29 08:37:54.318  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:54.318  4079  4245 D bt_bte_conf: Device ID record 1 : primary
08-29 08:37:54.318  4079  4245 D bt_bte_conf:   vendorId            = 000f
08-29 08:37:54.319  4079  4245 D bt_bte_conf:   vendorIdSource      = 0001
08-29 08:37:54.319  4079  4245 D bt_bte_conf:   product             = 1200
08-29 08:37:54.319  4079  4245 D bt_bte_conf:   version             = 1436
08-29 08:37:54.319  4079  4245 D bt_bte_conf:   clientExecutableURL = 
08-29 08:37:54.320  4079  4245 D bt_bte_conf:   serviceDescription  = 
08-29 08:37:54.320  4079  4245 D bt_bte_conf:   documentationURL    = 
08-29 08:37:54.320  4079  4249 I bt_vendor: low_power_mode_cb
08-29 08:37:54.320  4079  4245 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 08:37:54.320  4079  4242 D bt_stack_manager: event_start_up_stack finished
08-29 08:37:54.321  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:54.322  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 08:37:54.323  4079  4241 D BluetoothAdapterProperties: Setting state to 15
08-29 08:37:54.323  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 08:37:54.326  4079  4241 I BluetoothAdapterState: Entering BleOnState
,08-29 08:37:54.328  4079  4241 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 08:37:54.329  4079  4241 D BluetoothAdapterProperties: Setting state to 11
,08-29 08:37:54.329  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 08:37:54.334  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
08-29 08:37:54.339  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:54.341  4079  4079 D HeadsetService: Received start request. Starting profile...
08-29 08:37:54.343  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:54.344  4079  4079 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 08:37:54.345  4079  4079 D HeadsetStateMachine: make
08-29 08:37:54.347  4079  4241 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:37:54.357  4079  4079 D HeadsetStateMachine: max_hf_connections = 1
,08-29 08:37:54.357  4079  4079 I bt_bluedroid: get_profile_interface handsfree
08-29 08:37:54.357  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 08:37:54.358  4079  4245 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 08:37:54.363  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:54.363  4079  4079 D A2dpService: Received start request. Starting profile...
08-29 08:37:54.364  4079  4079 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:37:54.364  4079  4079 I bt_bluedroid: get_profile_interface avrcp
,08-29 08:37:54.372  4079  4079 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 08:37:54.373  4079  4079 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:37:54.373  4079  4079 D A2dpStateMachine: make
,08-29 08:37:54.374  4079  4079 I bt_bluedroid: get_profile_interface a2dp
,08-29 08:37:54.375  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 08:37:54.377  4079  4261 D A2dpStateMachine: Enter Disconnected: -2
,08-29 08:37:54.378  4079  4079 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 08:37:54.379  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:54.381  4079  4079 D HidService: Received start request. Starting profile...
,08-29 08:37:54.381  4079  4079 I bt_bluedroid: get_profile_interface hidhost
08-29 08:37:54.381  4079  4245 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
08-29 08:37:54.381  3998  3998 D BluetoothInputDevice: Proxy object connected
,08-29 08:37:54.381  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 08:37:54.382  4079  4079 D HidService: setHidService(): set to: null
08-29 08:37:54.382  4079  4079 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:37:54.383  3998  3998 D HidProfile: Bluetooth service connected
,08-29 08:37:54.383  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:54.384  4079  4079 D HealthService: Received start request. Starting profile...
,08-29 08:37:54.385  4079  4079 I bt_bluedroid: get_profile_interface health
,08-29 08:37:54.386  4079  4079 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 08:37:54.387  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:54.389  3998  3998 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 08:37:54.389  4079  4079 D PanService: Received start request. Starting profile...
08-29 08:37:54.389  4079  4079 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:37:54.389  4079  4079 I bt_bluedroid: get_profile_interface pan
08-29 08:37:54.390  3998  3998 D PanProfile: Bluetooth service connected
,08-29 08:37:54.390  4079  4245 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 08:37:54.392  4079  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:37:54.393  4079  4079 D BluetoothMapService: Received start request. Starting profile...
,08-29 08:37:54.393  4079  4079 D BluetoothMapService: start()
08-29 08:37:54.393  3998  3998 D BluetoothMap: Proxy object connected
08-29 08:37:54.394  3998  3998 D MapProfile: Bluetooth service connected
08-29 08:37:54.394  3998  3998 D BluetoothMap: getConnectedDevices()
,08-29 08:37:54.395  3998  3998 D BluetoothMap: Bluetooth is Not enabled
08-29 08:37:54.395  4079  4079 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 08:37:54.396  4079  4079 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 08:37:54.396  4079  4079 D BluetoothMapAppObserver: createReceiver()
,08-29 08:37:54.397  4079  4079 D BluetoothMapAppObserver: initObservers()
08-29 08:37:54.397  4079  4079 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 08:37:54.405  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:54.406  4079  4079 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:37:54.406  4079  4079 V BluetoothAdapterState: isTurningOn()=true
08-29 08:37:54.406  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:54.406  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isTurningOn()=true
08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:54.408  4079  4259 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isTurningOn()=true
08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:54.408  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isTurningOff()=false
08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isTurningOn()=true
,08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isTurningOff()=false
08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isTurningOn()=true
,08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:37:54.409  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:54.410  4079  4079 V BluetoothAdapterState: isTurningOff()=false
08-29 08:37:54.410  4079  4079 V BluetoothAdapterState: isTurningOn()=true,
,08-29 08:37:54.410  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:37:54.410  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:54.410  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 08:37:54.411  4079  4241 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:37:54.411  4079  4241 D BluetoothAdapterProperties: State =  11
,08-29 08:37:54.412  4079  4245 D BluetoothAdapterProperties: Scan Mode:21
08-29 08:37:54.412  4079  4241 D BluetoothAdapterProperties: Setting state to 12
08-29 08:37:54.412  4079  4245 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:37:54.412  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 08:37:54.413  4079  4241 I BluetoothAdapterState: Entering OnState
08-29 08:37:54.413  3998  4010 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:37:54.414   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:37:54.414  1371  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:54.416  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:54.417  1371  2084 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:37:54.418  1371  1371 D BluetoothA2dp: Proxy object connected
,08-29 08:37:54.418   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:37:54.419  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:54.421   871   871 D BluetoothA2dp: Proxy object connected
,08-29 08:37:54.421  3998  4009 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:54.423  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:54.424  3998  4010 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 08:37:54.424  1371  1382 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:37:54.425  4079  4079 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:37:54.425  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:54.426  4079  4079 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 08:37:54.426  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 08:37:54.426  1371  2084 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:37:54.426  1371  1371 D PanProfile: Bluetooth service connected
08-29 08:37:54.427  4079  4079 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:54.429  1371  1371 D BluetoothMap: Proxy object connected
08-29 08:37:54.429  1371  1371 D MapProfile: Bluetooth service connected
,08-29 08:37:54.429  1371  1371 D BluetoothMap: getConnectedDevices()
08-29 08:37:54.429  1956  1970 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:37:54.430   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:37:54.430  4079  4079 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:37:54.430  1371  1383 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:37:54.431  4079  4079 D ObexServerSockets: Succeed to create listening sockets 
08-29 08:37:54.431  4079  4079 D ObexServerSockets0: startAccept()
,08-29 08:37:54.432  4079  4079 D ObexServerSockets0: prepareForNewConnect()
,08-29 08:37:54.433  3998  4009 D BluetoothPan: onBluetoothStateChange on: true
,08-29 08:37:54.433  1371  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:37:54.434  4079  4079 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 08:37:54.434  4079  4079 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 08:37:54.435   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:37:54.435  1371  1371 D BluetoothInputDevice: Proxy object connected
08-29 08:37:54.435  4079  4268 D ObexServerSockets0: Accepting socket connection...
08-29 08:37:54.436  1371  1371 D HidProfile: Bluetooth service connected
,08-29 08:37:54.437  4079  4267 D ObexServerSockets0: Accepting socket connection...
,08-29 08:37:54.438  4079  4079 D BluetoothMapService: onReceive
08-29 08:37:54.438  4079  4079 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:54.438  4079  4079 D BluetoothMapService: STATE_ON
08-29 08:37:54.438   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 08:37:54.440  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:54.441  3998  3998 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 08:37:54.441  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:54.448  3998  3998 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 08:37:54.455  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:37:54.458  3998  3998 D BluetoothA2dp: Proxy object connected
,08-29 08:37:54.459  4079  4079 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 08:37:54.459  4079  4079 D ObexServerSockets0: prepareForNewConnect()
08-29 08:37:54.462  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:54.465  3998  3998 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:54.472  1371  1371 D BluetoothPbap: Proxy object connected
,08-29 08:37:54.472  1371  1371 D PbapServerProfile: Bluetooth service connected
,08-29 08:37:54.472  3998  3998 D BluetoothPbap: Proxy object connected
08-29 08:37:54.473  3998  3998 D PbapServerProfile: Bluetooth service connected
,08-29 08:37:54.484  4079  4272 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:37:54.502  4079  4276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:37:54.504  4079  4276 I BtOppRfcommListener: Accept thread started.
,08-29 08:37:54.519  1371  1382 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.520  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-29 08:37:54.520   871   871 D BluetoothHeadset: Proxy object connected
08-29 08:37:54.520  1956  2142 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.521   871   871 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.521   871   871 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.530  1956  1973 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.531   871   888 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.535   871   888 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.550  3998  4010 D BluetoothHeadset: Proxy object connected
,08-29 08:37:54.551  3998  3998 D HeadsetProfile: Bluetooth service connected
,08-29 08:37:55.991  4079  4241 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 08:37:55.991  4079  4241 D BluetoothAdapterProperties: Setting state to 13
,08-29 08:37:55.991  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 08:37:55.992   871  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-29 08:37:55.993  4079  4241 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 08:37:55.996  4079  4241 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:37:56.000  4079  4245 D BluetoothAdapterProperties: Scan Mode:20
,08-29 08:37:56.001  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 08:37:56.005  4079  4079 D BluetoothMapService: onReceive
,08-29 08:37:56.005  4079  4079 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:37:56.006  4079  4079 D BluetoothMapService: STATE_TURNING_OFF
08-29 08:37:56.007  4079  4079 D BluetoothMapService: MAP Service closeService in
,08-29 08:37:56.007  4079  4079 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 08:37:56.007  4079  4079 D ObexServerSockets0: shutdown(block = true)
08-29 08:37:56.008  4079  4267 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 08:37:56.011  4079  4079 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 08:37:56.013  4079  4268 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 08:37:56.014  4079  4254 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 08:37:56.015  4079  4079 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 08:37:56.016  4079  4079 I BtOppRfcommListener: stopping Accept Thread
08-29 08:37:56.017  4079  4276 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 08:37:56.018  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:56.018  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:37:56.021  4079  4276 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 08:37:56.021  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:56.022  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:56.023  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 08:37:56.024  4079  4079 D HeadsetService: Received stop request...Stopping profile...
,08-29 08:37:56.026  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:37:56.026  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:37:56.027  3925  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 08:37:56.027  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:37:56.028  1371  1383 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:56.029   871   871 D BluetoothHeadset: Proxy object disconnected,
08-29 08:37:56.029  1956  2285 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:56.029   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:56.029  4079  4079 D A2dpService: Received stop request...Stopping profile...
08-29 08:37:56.030   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:56.030  3998  4009 D BluetoothHeadset: Proxy object disconnected
08-29 08:37:56.030  4079  4261 D A2dpStateMachine: Exit Disconnected: -1
08-29 08:37:56.032   871   871 D BluetoothA2dp: Proxy object disconnected
08-29 08:37:56.033  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:56.033  4079  4079 D HidService: Received stop request...Stopping profile...
08-29 08:37:56.033  4079  4079 D HidService: Stopping Bluetooth HidService
08-29 08:37:56.036  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:37:56.036  1371  1371 D HeadsetProfile: Bluetooth service disconnected
08-29 08:37:56.036  1371  1371 D BluetoothA2dp: Proxy object disconnected
08-29 08:37:56.036  1371  1371 D BluetoothInputDevice: Proxy object disconnected
08-29 08:37:56.036  1371  1371 D HidProfile: Bluetooth service disconnected
08-29 08:37:56.038  4079  4079 D HealthService: Received stop request...Stopping profile...
08-29 08:37:56.039  4079  4079 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:56.039  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:56.039  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:37:56.039  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:56.041  4079  4079 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 08:37:56.041  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 08:37:56.041  4079  4251 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:37:56.041  4079  4079 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 08:37:56.041  4079  4251 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:37:56.041  4079  4251 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:56.041  4079  4245 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-29 08:37:56.043  4079  4079 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:56.043  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:56.043  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:56.043  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:56.044  4079  4079 D PanService: Received stop request...Stopping profile...
,08-29 08:37:56.045  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 08:37:56.045  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:37:56.046  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 08:37:56.046  4079  4251 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:56.046  4079  4251 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 08:37:56.046  4079  4251 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 08:37:56.046  4079  4251 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:56.046  4079  4251 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 08:37:56.046  4079  4251 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 08:37:56.046  4079  4079 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:56.049  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:56.049  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:56.049  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:56.049  4079  4079 D BluetoothMapService: Received stop request...Stopping profile...
08-29 08:37:56.049  4079  4079 D BluetoothMapService: stop()
08-29 08:37:56.050  4079  4079 D BluetoothMapAppObserver: deinitObservers()
,08-29 08:37:56.050  4079  4079 D BluetoothMapAppObserver: removeReceiver()
08-29 08:37:56.050  1371  1371 D PanProfile: Bluetooth service disconnected
08-29 08:37:56.052  1371  1371 D BluetoothMap: Proxy object disconnected
,08-29 08:37:56.052  1371  1371 D MapProfile: Bluetooth service disconnected
08-29 08:37:56.052  4079  4079 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 08:37:56.052  4079  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 08:37:56.053  4079  4079 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 08:37:56.053  4079  4079 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:56.053  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:56.053  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:56.053  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:56.054  4079  4079 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 08:37:56.054  4079  4245 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 08:37:56.054  4079  4079 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 08:37:56.056  1371  1371 D BluetoothPbap: Proxy object disconnected
08-29 08:37:56.056  1371  1371 D PbapServerProfile: Bluetooth service disconnected
08-29 08:37:56.057  4079  4079 V BluetoothAdapterState: isTurningOff()=true
08-29 08:37:56.057  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:56.057  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 08:37:56.057  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:37:56.057  4079  4079 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 08:37:56.057  4079  4079 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 08:37:56.060  4079  4079 D BluetoothMapService: MAP Service closeService in
08-29 08:37:56.061  4079  4079 V BluetoothAdapterState: isTurningOff()=true
,08-29 08:37:56.061  4079  4079 V BluetoothAdapterState: isTurningOn()=false
08-29 08:37:56.061  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:56.061  4079  4079 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:37:56.063  3998  3998 D DockEventReceiver: finishStartingService: stopping service
08-29 08:37:56.063  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 08:37:56.063  4079  4241 D BluetoothAdapterProperties: Setting state to 15
08-29 08:37:56.063  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 08:37:56.064  4079  4241 I BluetoothAdapterState: Entering BleOnState
,08-29 08:37:56.064  4079  4079 D BluetoothMapService: cleanup()
08-29 08:37:56.064  4079  4079 D BluetoothMapService: MAP Service closeService in
08-29 08:37:56.064  3998  4010 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 08:37:56.064   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:56.064  3998  3998 D HeadsetProfile: Bluetooth service disconnected
08-29 08:37:56.065  1371  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 08:37:56.065  3998  3998 D BluetoothA2dp: Proxy object disconnected
08-29 08:37:56.065  3998  3998 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 08:37:56.065  1371  2084 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 08:37:56.065  3998  3998 D PanProfile: Bluetooth service disconnected
08-29 08:37:56.065   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 08:37:56.066  3998  4009 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 08:37:56.066  3998  4010 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:37:56.067  3998  3998 D BluetoothMap: Proxy object disconnected
08-29 08:37:56.067  3998  3998 D MapProfile: Bluetooth service disconnected
08-29 08:37:56.067  1371  1382 D BluetoothPan: onBluetoothStateChange on: false
,08-29 08:37:56.068  1371  1383 D BluetoothMap: onBluetoothStateChange: up=false
08-29 08:37:56.069  1956  1970 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:56.069   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:56.069  3998  4010 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 08:37:56.071  1371  2084 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 08:37:56.071  3998  4009 D BluetoothPan: onBluetoothStateChange on: false
,08-29 08:37:56.072  1371  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 08:37:56.072  3998  4281 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 08:37:56.073   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 08:37:56.073  4079  4241 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-29 08:37:56.073  4079  4241 D BluetoothAdapterProperties: Setting state to 16
08-29 08:37:56.073  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 08:37:56.074  4079  4241 D BluetoothAdapterProperties: onBleDisable
,08-29 08:37:56.074  4079  4241 I BluetoothAdapterState: Entering PendingCommandState
08-29 08:37:56.074  4079  4242 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 08:37:56.075  4079  4251 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 08:37:56.075  4079  4251 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 08:37:56.079  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:56.080  4079  4245 D BluetoothAdapterProperties: Scan Mode:20
08-29 08:37:56.080  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:56.081  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:37:56.081  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:56.082  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:37:56.086  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:37:56.091  3998  3998 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:37:56.278  4079  4245 I bt_hci  : shut_down
,08-29 08:37:56.290  4079  4249 D bt_hwcfg: hw_epilog_process
,08-29 08:37:56.290  4079  4249 I bt_vendor: low_power_mode_cb
,08-29 08:37:56.313  4079  4249 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 08:37:56.313  4079  4249 I bt_vendor: epilog_cb
,08-29 08:37:56.314  4079  4249 I bt_hci  : epilog_finished_callback
,08-29 08:37:56.323  4079  4245 I bt_hci_h4: hal_close
,08-29 08:37:56.325  4079  4245 I bt_userial_vendor: device fd = 51 close
,08-29 08:37:56.454  4079  4242 D bt_stack_manager: event_shut_down_stack finished.
,08-29 08:37:56.455  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 08:37:56.461  4079  4079 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:37:56.461  4079  4241 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 08:37:56.463  4079  4079 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 08:37:56.463  4079  4079 D BtGatt.GattService: stop()
08-29 08:37:56.464  4079  4079 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 08:37:56.469  4079  4079 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:37:56.470  4079  4079 V BluetoothAdapterState: isTurningOn()=false
,08-29 08:37:56.470  4079  4079 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:37:56.470  4079  4079 V BluetoothAdapterState: isBleTurningOff()=true
08-29 08:37:56.471  4079  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 08:37:56.472  4079  4241 D BluetoothAdapterProperties: Setting state to 10
,08-29 08:37:56.472  4079  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 08:37:56.474  4079  4241 I BluetoothAdapterState: Entering OffState
08-29 08:37:56.475   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 08:37:56.495  4079  4079 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 08:37:56.495  4079  4079 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 08:37:56.496  4079  4242 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 08:37:56.499  4079  4242 D bt_stack_manager: event_clean_up_stack finished.
,08-29 08:37:56.499  4079  4079 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 08:37:56.502  4079  4079 I art     : System.exit called, status: 0
08-29 08:37:56.502  4079  4079 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 08:37:56.560   871   881 I ActivityManager: Process com.android.bluetooth (pid 4079) has died
,08-29 08:37:58.557   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 08:37:58.567  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-29 08:37:58.586   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 08:37:58.586   871   891 I Adreno  : Build Date                       : 10/20/15
08-29 08:37:58.586   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 08:37:58.586   871   891 I Adreno  : Local Branch                     : M14
08-29 08:37:58.586   871   891 I Adreno  : Remote Branch                    : 
08-29 08:37:58.586   871   891 I Adreno  : Remote Branch                    : 
08-29 08:37:58.586   871   891 I Adreno  : Reconstruct Branch               : 
,08-29 08:37:58.639   280   894 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (332 us)
,08-29 08:37:58.990  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:37:58.990  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:37:59.302  3925  3925 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 08:37:59.302  3925  3925 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 08:37:59.337   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 08:37:59.340  3925  3925 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2bec10 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@70972da, 16908290=android.view.AbsSavedState$1@70972da}, android:focusedViewId=100}]}]
,08-29 08:37:59.340  3925  3925 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 08:37:59.341  3925  3925 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 08:37:59.341  3925  3925 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 08:37:59.342   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-29 08:37:59.346   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-29 08:37:59.347   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-29 08:37:59.347   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 08:37:59.392   871   880 I art     : Background partial concurrent mark sweep GC freed 6310(438KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/43MB, paused 824us total 107.568ms
,08-29 08:37:59.578   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 08:37:59.589   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 08:37:59.596   871  1339 D SurfaceControl: Excessive delay in setPowerMode(): 249ms
,08-29 08:37:59.601   871   891 I DreamManagerService: Entering dreamland.
,08-29 08:37:59.602   871   891 I PowerManagerService: Dozing...
,08-29 08:37:59.603   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 08:37:59.652   373  1285 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 08:37:59.652   373  1285 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 08:37:59.657   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 08:37:59.661   871  1313 E native  : do suspend false
,08-29 08:37:59.666  1940  4288 D NfcService: Discovery configuration equal, not updating.
,08-29 08:37:59.680   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 08:37:59.684   871  1313 E native  : do suspend true
,08-29 08:37:59.795   373   373 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 08:37:59.795   373   373 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 08:38:01.997  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:01.997  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ea0830b added. We now have 6 listener(s)
08-29 08:38:01.998  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:02.001  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:02.002  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c755e8 added. We now have 7 listener(s)
08-29 08:38:02.002  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:02.004  3925  3976 I System.out: IsBluetoothEnabled
,08-29 08:38:02.015  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:02.065   871   888 I ActivityManager: Start proc 4297:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 08:38:02.225  4297  4297 D AdapterServiceConfig: Adding HeadsetService
,08-29 08:38:02.226  4297  4297 D AdapterServiceConfig: Adding A2dpService
08-29 08:38:02.227  4297  4297 D AdapterServiceConfig: Adding HidService
,08-29 08:38:02.228  4297  4297 D AdapterServiceConfig: Adding HealthService
,08-29 08:38:02.228  4297  4297 D AdapterServiceConfig: Adding PanService
08-29 08:38:02.229  4297  4297 D AdapterServiceConfig: Adding GattService
08-29 08:38:02.230  4297  4297 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 08:38:02.252   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a6ceb8:true
08-29 08:38:02.252  4297  4297 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 08:38:02.256  4297  4297 I bt_bluedroid: init
,08-29 08:38:02.256  4297  4309 I BluetoothAdapterState: Entering OffState
,08-29 08:38:02.259  4297  4310 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 08:38:02.259  4297  4310 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 08:38:02.259  4297  4310 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 08:38:02.259  4297  4310 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 08:38:02.261  4297  4297 I bt_bluedroid: get_profile_interface socket
,08-29 08:38:02.263  4297  4297 I bt_bluedroid: get_profile_interface sdp
,08-29 08:38:02.267  4297  4308 I bt_bluedroid: config_hci_snoop_log
,08-29 08:38:02.268  4297  4313 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 08:38:02.268   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 08:38:02.273  4297  4313 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 08:38:02.280  4297  4309 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 08:38:02.280  4297  4309 D BluetoothAdapterProperties: Setting state to 14
,08-29 08:38:02.281  4297  4309 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 08:38:02.285  4297  4309 D BluetoothBondStateMachine: make
,08-29 08:38:02.290  4297  4314 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 08:38:02.300  4297  4297 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 08:38:02.299  4297  4309 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:38:02.303  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:02.304  4297  4297 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 08:38:02.304  4297  4297 D BtGatt.GattService: Received start request. Starting profile...
,08-29 08:38:02.304  4297  4297 D BtGatt.GattService: start()
08-29 08:38:02.305  4297  4297 I bt_bluedroid: get_profile_interface gatt
,08-29 08:38:02.306  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:02.306  4297  4297 D BtGatt.AdvertiseManager: advertise manager created
,08-29 08:38:02.314  4297  4297 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:38:02.314  4297  4297 V BluetoothAdapterState: isTurningOn()=false
,08-29 08:38:02.314  4297  4297 V BluetoothAdapterState: isBleTurningOn()=true
08-29 08:38:02.314  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:38:02.314  4297  4309 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 08:38:02.315  4297  4309 I bt_bluedroid: enable
08-29 08:38:02.316  4297  4310 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 08:38:02.316  4297  4310 I bt_hci  : start_up
,08-29 08:38:02.324  4297  4310 I bt_vendor: alloc value 0xb3a05189
,08-29 08:38:02.324  4297  4310 I bt_vendor: init
08-29 08:38:02.324  4297  4310 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 08:38:02.324  4297  4310 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 08:38:02.430  4297  4310 D bt_hci  : start_up starting async portion
08-29 08:38:02.431  4297  4317 I bt_hci  : event_finish_startup
08-29 08:38:02.431  4297  4317 I bt_hci_h4: hal_open
08-29 08:38:02.431  4297  4317 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 08:38:02.436  4297  4317 I bt_userial_vendor: device fd = 51 open
,08-29 08:38:02.472  4297  4317 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 08:38:02.504  4297  4317 D bt_hwcfg: Chipset BCM4354A2
08-29 08:38:02.504  4297  4317 D bt_hwcfg: Target name = [BCM4354A2]
08-29 08:38:02.504  4297  4317 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 08:38:03.138  4297  4317 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 08:38:03.140  4297  4317 D bt_hwcfg: Settlement delay -- 100 ms
08-29 08:38:03.140  4297  4317 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 08:38:03.257  4297  4317 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 08:38:03.258  4297  4317 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 08:38:03.287  4297  4317 I bt_hwcfg: vendor lib fwcfg completed
,08-29 08:38:03.287  4297  4317 I bt_vendor: firmware callback
,08-29 08:38:03.288  4297  4317 I bt_hci  : firmware_config_callback
,08-29 08:38:03.299  4297  4319 I bt_btu  : btu_task pending for preload complete event
,08-29 08:38:03.299  4297  4319 I bt_btu_task: Bluetooth chip preload is complete
08-29 08:38:03.299  4297  4319 I bt_btu  : btu_task received preload complete event
,08-29 08:38:03.311  4297  4319 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 08:38:03.312  4297  4319 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 08:38:03.312  4297  4319 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 08:38:03.312  4297  4319 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 08:38:03.313  4297  4319 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 08:38:03.313  4297  4319 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 08:38:03.314  4297  4319 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 08:38:03.315  4297  4319 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 08:38:03.316  4297  4319 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 08:38:03.316  4297  4319 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 08:38:03.316  4297  4319 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 08:38:03.316  4297  4319 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 08:38:03.317  4297  4319 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 08:38:03.317  4297  4319 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 08:38:03.317  4297  4319 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 08:38:03.460  4297  4319 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3982d9d
,08-29 08:38:03.461  4297  4319 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3982d9d 
,08-29 08:38:03.472  4297  4313 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 08:38:03.474  4297  4313 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 08:38:03.475  4297  4313 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 08:38:03.478  4297  4313 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 08:38:03.481  4297  4313 D BluetoothAdapterProperties: Scan Mode:20
,08-29 08:38:03.481  4297  4313 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:38:03.481  4297  4313 D bt_hci  : do_postload posting postload work item
08-29 08:38:03.482  4297  4317 I bt_hci  : event_postload
,08-29 08:38:03.482  4297  4317 I bt_vendor: sco_config_cb
,08-29 08:38:03.483  4297  4317 I bt_hci  : sco_config_callback postload finished.
08-29 08:38:03.485  4297  4313 D bt_bte_conf: Device ID record 1 : primary
08-29 08:38:03.485  4297  4313 D bt_bte_conf:   vendorId            = 000f
08-29 08:38:03.486  4297  4313 D bt_bte_conf:   vendorIdSource      = 0001
08-29 08:38:03.486  4297  4313 D bt_bte_conf:   product             = 1200
08-29 08:38:03.486  4297  4313 D bt_bte_conf:   version             = 1436
08-29 08:38:03.486  4297  4313 D bt_bte_conf:   clientExecutableURL = 
,08-29 08:38:03.486  4297  4313 D bt_bte_conf:   serviceDescription  = 
08-29 08:38:03.487  4297  4313 D bt_bte_conf:   documentationURL    = 
08-29 08:38:03.487  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.487  4297  4313 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 08:38:03.488  4297  4310 D bt_stack_manager: event_start_up_stack finished
,08-29 08:38:03.489  4297  4309 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 08:38:03.489  4297  4309 D BluetoothAdapterProperties: Setting state to 15
08-29 08:38:03.490  4297  4309 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 08:38:03.494  4297  4317 I bt_vendor: low_power_mode_cb
08-29 08:38:03.495  4297  4309 I BluetoothAdapterState: Entering BleOnState
,08-29 08:38:03.495  4297  4309 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 08:38:03.495  4297  4309 D BluetoothAdapterProperties: Setting state to 11
08-29 08:38:03.496  4297  4309 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 08:38:03.502  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:03.507  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:03.509  4297  4297 D HeadsetService: Received start request. Starting profile...
,08-29 08:38:03.513  4297  4297 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 08:38:03.513  4297  4297 D HeadsetStateMachine: make
,08-29 08:38:03.520  4297  4309 I BluetoothAdapterState: Entering PendingCommandState
,08-29 08:38:03.525  4297  4297 D HeadsetStateMachine: max_hf_connections = 1,
,08-29 08:38:03.525  4297  4297 I bt_bluedroid: get_profile_interface handsfree
,08-29 08:38:03.525  4297  4313 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 08:38:03.526  4297  4313 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 08:38:03.530  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:03.530  4297  4297 D A2dpService: Received start request. Starting profile...
,08-29 08:38:03.531  4297  4297 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 08:38:03.531  4297  4297 I bt_bluedroid: get_profile_interface avrcp
,08-29 08:38:03.537  4297  4297 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 08:38:03.537  4297  4297 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 08:38:03.537  4297  4297 D A2dpStateMachine: make
,08-29 08:38:03.538  4297  4297 I bt_bluedroid: get_profile_interface a2dp
08-29 08:38:03.538  4297  4313 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 08:38:03.540  4297  4328 D A2dpStateMachine: Enter Disconnected: -2
,08-29 08:38:03.541  4297  4297 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 08:38:03.541  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:03.542  4297  4297 D HidService: Received start request. Starting profile...
,08-29 08:38:03.542  4297  4297 I bt_bluedroid: get_profile_interface hidhost
08-29 08:38:03.542  4297  4297 D HidService: setHidService(): set to: null
08-29 08:38:03.542  4297  4313 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39643e5
08-29 08:38:03.542  4297  4313 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 08:38:03.543  4297  4297 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 08:38:03.544  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
08-29 08:38:03.544  4297  4297 D HealthService: Received start request. Starting profile...
,08-29 08:38:03.545  4297  4297 I bt_bluedroid: get_profile_interface health
,08-29 08:38:03.546  4297  4297 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 08:38:03.546  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:03.547  4297  4297 D PanService: Received start request. Starting profile...
08-29 08:38:03.547  4297  4297 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 08:38:03.547  4297  4297 I bt_bluedroid: get_profile_interface pan
,08-29 08:38:03.548  4297  4313 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 08:38:03.550  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:38:03.552  4297  4297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:03.553  4297  4297 D BluetoothMapService: Received start request. Starting profile...
08-29 08:38:03.553  4297  4297 D BluetoothMapService: start()
,08-29 08:38:03.555  4297  4297 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 08:38:03.555  4297  4297 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 08:38:03.556  4297  4297 D BluetoothMapAppObserver: createReceiver()
,08-29 08:38:03.556  4297  4297 D BluetoothMapAppObserver: initObservers()
08-29 08:38:03.556  4297  4297 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 08:38:03.563  4297  4297 V BluetoothAdapterState: isTurningOff()=false
08-29 08:38:03.563  4297  4297 V BluetoothAdapterState: isTurningOn()=true
08-29 08:38:03.563  4297  4297 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:38:03.564  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:38:03.565  4297  4297 V BluetoothAdapterState: isTurningOff()=false
,08-29 08:38:03.565  4297  4297 V BluetoothAdapterState: isTurningOn()=true
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isBleTurningOn()=false,
,08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isTurningOff()=false
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isTurningOn()=true
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:38:03.566  4297  4326 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isTurningOff()=false
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isTurningOn()=true
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:38:03.566  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isTurningOff()=false
08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isTurningOn()=true
08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isTurningOff()=false
08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isTurningOn()=true
,08-29 08:38:03.567  4297  4297 V BluetoothAdapterState: isBleTurningOn()=false
08-29 08:38:03.568  4297  4297 V BluetoothAdapterState: isBleTurningOff()=false
08-29 08:38:03.569  4297  4309 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 08:38:03.569  4297  4309 D BluetoothAdapterProperties: ScanMode =  20
08-29 08:38:03.569  4297  4309 D BluetoothAdapterProperties: State =  11
08-29 08:38:03.569  4297  4309 D BluetoothAdapterProperties: Setting state to 12
08-29 08:38:03.569  4297  4309 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 08:38:03.570  4297  4309 I BluetoothAdapterState: Entering OnState
08-29 08:38:03.570  4297  4313 D BluetoothAdapterProperties: Scan Mode:21
,08-29 08:38:03.570  3998  4281 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 08:38:03.570  4297  4313 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:03.575  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 08:38:03.575   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:03.576  1371  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:38:03.577  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:38:03.580  1371  2084 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:38:03.580  1371  1371 D BluetoothA2dp: Proxy object connected
08-29 08:38:03.580  3998  3998 D BluetoothInputDevice: Proxy object connected
08-29 08:38:03.580   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 08:38:03.580  3998  3998 D HidProfile: Bluetooth service connected
08-29 08:38:03.581   871   871 D BluetoothA2dp: Proxy object connected
,08-29 08:38:03.581  3998  4009 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 08:38:03.583  4297  4297 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 08:38:03.584  4297  4297 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 08:38:03.585  4297  4297 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:38:03.586  3998  4010 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 08:38:03.588  4297  4297 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 08:38:03.588  1371  1383 D BluetoothPan: onBluetoothStateChange on: true
08-29 08:38:03.589  4297  4297 D ObexServerSockets: Succeed to create listening sockets 
,08-29 08:38:03.589  4297  4297 D ObexServerSockets0: startAccept()
08-29 08:38:03.589  4297  4297 D ObexServerSockets0: prepareForNewConnect()
,08-29 08:38:03.592  4297  4297 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 08:38:03.592  4297  4297 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 08:38:03.592  1371  2084 D BluetoothMap: onBluetoothStateChange: up=true
08-29 08:38:03.594  4297  4334 D ObexServerSockets0: Accepting socket connection...
08-29 08:38:03.594  4297  4335 D ObexServerSockets0: Accepting socket connection...
,08-29 08:38:03.597  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 08:38:03.597  1371  1371 D PanProfile: Bluetooth service connected
,08-29 08:38:03.597  1371  1371 D BluetoothMap: Proxy object connected
08-29 08:38:03.598  1956  2285 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:03.598  1371  1371 D MapProfile: Bluetooth service connected
08-29 08:38:03.598  1371  1371 D BluetoothMap: getConnectedDevices()
08-29 08:38:03.598  3998  3998 D BluetoothMap: Proxy object connected
,08-29 08:38:03.598   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:03.599  3998  4009 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 08:38:03.598  3998  3998 D MapProfile: Bluetooth service connected
,08-29 08:38:03.601  3998  3998 D BluetoothMap: getConnectedDevices()
,08-29 08:38:03.601  1371  1383 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 08:38:03.603  3998  4281 D BluetoothPan: onBluetoothStateChange on: true
,08-29 08:38:03.604  3998  3998 D BluetoothA2dp: Proxy object connected
,08-29 08:38:03.605  1371  2084 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 08:38:03.606  3998  3998 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 08:38:03.606  3998  3998 D PanProfile: Bluetooth service connected
,08-29 08:38:03.607  1371  1371 D BluetoothInputDevice: Proxy object connected
08-29 08:38:03.607  3998  4010 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 08:38:03.607  1371  1371 D HidProfile: Bluetooth service connected
,08-29 08:38:03.607   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 08:38:03.609   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 08:38:03.612  4297  4297 D BluetoothMapService: onReceive
,08-29 08:38:03.612  4297  4297 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 08:38:03.612  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:03.613  4297  4297 D BluetoothMapService: STATE_ON
,08-29 08:38:03.618  3998  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 08:38:03.624  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 08:38:03.635  3998  3998 D DockEventReceiver: finishStartingService: stopping service
,08-29 08:38:03.635  3998  3998 D BluetoothPbap: Proxy object connected
08-29 08:38:03.635  3998  3998 D PbapServerProfile: Bluetooth service connected
,08-29 08:38:03.638  1371  1371 D BluetoothPbap: Proxy object connected
,08-29 08:38:03.638  1371  1371 D PbapServerProfile: Bluetooth service connected
,08-29 08:38:03.642  4297  4297 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 08:38:03.642  4297  4297 D ObexServerSockets0: prepareForNewConnect()
,08-29 08:38:03.648  4297  4340 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:38:03.665  4297  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 08:38:03.666  4297  4344 I BtOppRfcommListener: Accept thread started.
,08-29 08:38:03.678  1371  1383 D BluetoothHeadset: Proxy object connected
,08-29 08:38:03.678   871   871 D BluetoothHeadset: Proxy object connected
,08-29 08:38:03.679  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-29 08:38:03.679  1956  1970 D BluetoothHeadset: Proxy object connected
08-29 08:38:03.679   871   871 D BluetoothHeadset: Proxy object connected
08-29 08:38:03.679   871   871 D BluetoothHeadset: Proxy object connected
,08-29 08:38:03.680  3998  4281 D BluetoothHeadset: Proxy object connected
08-29 08:38:03.680  3998  3998 D HeadsetProfile: Bluetooth service connected
08-29 08:38:03.680  1371  2084 D BluetoothHeadset: Proxy object connected
,08-29 08:38:03.681  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-29 08:38:03.698  1956  2142 D BluetoothHeadset: Proxy object connected,
,08-29 08:38:03.699   871   888 D BluetoothHeadset: Proxy object connected
,08-29 08:38:03.707  3998  4009 D BluetoothHeadset: Proxy object connected
,08-29 08:38:03.708  3998  3998 D HeadsetProfile: Bluetooth service connected
,08-29 08:38:03.708   871   888 D BluetoothHeadset: Proxy object connected
,08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:04.037  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:38:04.043  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 08:38:04.048  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:04.048  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57c7401 added. We now have 8 listener(s)
,08-29 08:38:04.049  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:04.057   871   881 D WifiService: setWifiEnabled: false pid=3925, uid=10000
08-29 08:38:04.057   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:38:04.069  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:04.070   871  2007 D WifiService: setWifiEnabled: true pid=3925, uid=10000
,08-29 08:38:04.070   871  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 08:38:04.082   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:04.098  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:38:04.104  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:38:04.105   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-29 08:38:04.106   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 08:38:04.107   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 08:38:04.108   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 08:38:04.108   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 08:38:04.108   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 08:38:04.108   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 08:38:04.123   369   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 08:38:04.124   369   870 D CommandListener: Setting iface cfg
,08-29 08:38:04.125   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-29 08:38:04.125   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 08:38:04.125   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.29 delta 1000 -> 1000
,08-29 08:38:04.127   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 08:38:04.128   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 08:38:04.130   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 08:38:04.141   871  1313 E native  : do suspend true
,08-29 08:38:04.154   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 08:38:04.154   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:38:04.164   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 08:38:04.228   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 08:38:04.230  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 08:38:04.372  1889  2739 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 08:38:04.679  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 08:38:04.719  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 08:38:04.719  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 08:38:04.724   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 08:38:04.731   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 08:38:04.732   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
08-29 08:38:04.732   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:38:04.747   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 08:38:04.761   369   870 D CommandListener: Setting iface cfg
,08-29 08:38:04.762   871  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 08:38:04.770   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 08:38:04.803   871  4353 D DhcpClient: Receive thread started
,08-29 08:38:04.888   871  1313 E native  : do suspend false
,08-29 08:38:04.907   871  2076 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 08:38:04.921   871  4353 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 08:38:04.922   871  2076 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 08:38:04.925   871  2076 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 08:38:04.942   871  4353 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 08:38:04.944   871  2076 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 08:38:04.948   369   870 D CommandListener: Setting iface cfg
,08-29 08:38:04.958   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 08:38:04.962   871  1313 E native  : do suspend true
,08-29 08:38:04.962   871  2076 D DhcpClient: Scheduling renewal in 86399s
,08-29 08:38:04.989   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 08:38:04.992   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 08:38:04.994   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 08:38:04.998   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 08:38:04.999   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 08:38:05.058   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 08:38:05.059   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 08:38:05.060   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 08:38:05.062   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 08:38:05.063   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 08:38:05.075   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 08:38:05.084  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 08:38:05.086  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 08:38:05.086   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 08:38:05.087   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 08:38:05.087   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 08:38:05.087   871  1315 D ConnectivityService:    accepting network in place of null
,08-29 08:38:05.089   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 08:38:05.089   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 08:38:05.089   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 08:38:05.091  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 08:38:05.091  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 08:38:05.094  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2bec10 Bundle[{}]
,08-29 08:38:05.095  3925  3976 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 08:38:05.095  3925  3976 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 08:38:05.096  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 08:38:05.096  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 08:38:05.097  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 08:38:05.097  3925  3976 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 08:38:05.102  3925  3976 I System.out: Running OutgoingSocketThread
,08-29 08:38:05.103   871  4352 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159727, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 08:38:05.103  3925  4358 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 452)
,08-29 08:38:05.104  3925  4358 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39652
,08-29 08:38:05.104  3925  4358 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 08:38:05.120   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:38:05.162   369   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 08:38:05.169   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 08:38:05.169   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 08:38:05.172   871  4351 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:807::200e
,08-29 08:38:05.174   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 08:38:05.180   871   888 D Tethering: MasterInitialState.processMessage what=3
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:05.185  3925  3925 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:38:05.188  3925  3925 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:38:05.200  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 08:38:05.206  1716  1716 D SystemUpdateService: onCreate
,08-29 08:38:05.210  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 08:38:05.229  1716  4363 I SystemUpdateService: active receiver: enabled
,08-29 08:38:05.231  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 08:38:05.241  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 08:38:05.242  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 08:38:05.244  1716  2519 I iu.UploadsManager: num queued entries: 0
,08-29 08:38:05.244   871  4351 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 06:38:05 GMT], X-Android-Received-Millis=[1472452685244], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472452685217]}
08-29 08:38:05.244  1716  2519 I iu.UploadsManager: num updated entries: 0
,08-29 08:38:05.245  4093  4093 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 08:38:05.247   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 08:38:05.247   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-29 08:38:05.247   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 08:38:05.251   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 08:38:05.254  1716  4366 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 08:38:05.254  1716  4366 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 08:38:05.257  4093  4093 D SprintDMHelper: simOperator: 
,08-29 08:38:05.257  4093  4093 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 08:38:05.260  1716  4366 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 08:38:05.263  1716  4363 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 08:38:05.273  1716  2519 I iu.SyncManager: NEXT; no task
,08-29 08:38:05.274  1716  4363 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 08:38:05.274  1716  4363 I SystemUpdateService: now status is 0 (complete)
,08-29 08:38:05.274  1716  4363 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 08:38:05.274  1716  4363 I SystemUpdateService: file has been verified
,08-29 08:38:05.274  1716  4363 I SystemUpdateService: OTA package size = 12249756
08-29 08:38:05.277  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 08:38:05.278  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 08:38:05.287  1716  4363 I SystemUpdateService: showing system update notification
,08-29 08:38:05.327  1507  2289 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 08:38:05.327  1507  2289 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 08:38:05.327  1716  1716 D SystemUpdateService: onDestroy
08-29 08:38:05.327  1507  2289 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 08:38:05.328  1507  2289 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 08:38:05.349  1716  4366 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-29 08:38:05.380  2833  4369 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 08:38:06.105  3925  3976 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 453)
08-29 08:38:06.106  3925  3976 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 453)
,08-29 08:38:06.115  3925  3976 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 458)
,08-29 08:38:06.117  3925  3976 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 08:38:06.118  3925  3976 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 459)
,08-29 08:38:06.124  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:06.124  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1be2a6 added. We now have 2 listener(s)
,08-29 08:38:06.126  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:38:06.127  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:06.127  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:38:06.127  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:06.127  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5244e7 added. We now have 9 listener(s)
08-29 08:38:06.127  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:06.128  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:38:06.130  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:06.138  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:38:06.141  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:38:06.141  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:38:06.143  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:06.143  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b4f3d added. We now have 3 listener(s)
08-29 08:38:06.145  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.149  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.149  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:38:06.150  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:06.150  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:06.150  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:06.151  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c938332 added. We now have 10 listener(s)
,08-29 08:38:06.151  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:06.151  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:06.152  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:38:06.152  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 08:38:06.152  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:38:06.152  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.153  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:06.153  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:06.153  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1be2a6 removed from the list
08-29 08:38:06.153  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.154  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5244e7 removed from the list
,08-29 08:38:06.154  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:06.154  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.155  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.155  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.157  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:06.157  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:38:06.157  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.157  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5244e7 not in the list
08-29 08:38:06.157  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.157  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.158  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.158  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:38:06.158  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.158  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c938332 removed from the list
,08-29 08:38:06.158  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:38:06.158  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.158  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.158  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:06.159  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b4f3d removed from the list
08-29 08:38:06.159  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:38:06.159  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7744883 added. We now have 2 listener(s)
08-29 08:38:06.161  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 08:38:06.161  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:38:06.161  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:06.162  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:06.162  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecfa00 added. We now have 9 listener(s)
,08-29 08:38:06.162  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:06.162  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 08:38:06.165  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.167   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:06.170  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:38:06.172  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:06.172  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:38:06.174  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.175  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:38:06.175  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@972a07e added. We now have 3 listener(s)
,08-29 08:38:06.178  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:38:06.178  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:06.178  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:38:06.178  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:06.178  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:06.178  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228e9df added. We now have 10 listener(s)
08-29 08:38:06.178  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:06.178  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:38:06.178  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:38:06.179  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:38:06.179  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.179  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 08:38:06.182  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 08:38:06.182  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:38:06.186  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:38:06.187  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 08:38:06.187  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:38:06.191  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 08:38:06.191  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:38:06.191  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 08:38:06.192  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:38:06.195  4297  4325 D BtGatt.GattService: registerClient() - UUID=4530ba0a-8e2b-4842-bee1-46c2840bb717
,08-29 08:38:06.196  4297  4313 D BtGatt.GattService: onClientRegistered() - UUID=4530ba0a-8e2b-4842-bee1-46c2840bb717, clientIf=5
,08-29 08:38:06.197  3925  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:38:06.199  4297  4333 D BtGatt.GattService: start scan with filters
,08-29 08:38:06.203  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:38:06.203  4297  4316 D BtGatt.ScanManager: handling starting scan
08-29 08:38:06.203  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 08:38:06.203  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:38:06.204  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:38:06.206  4297  4316 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d68d9a4
,08-29 08:38:06.210  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:38:06.210  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:38:06.211  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 08:38:06.213  4297  4313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 08:38:06.214  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.214  4297  4316 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 08:38:06.215  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:38:06.221  3925  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 08:38:06.221  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:38:06.221  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 08:38:06.221  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.222  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:38:06.222  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 08:38:06.223  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 08:38:06.223  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 08:38:06.223  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 08:38:06.223  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:38:06.224  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 08:38:06.225  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:38:06.226  4297  4313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 08:38:06.226  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.227  4297  4325 D BtGatt.GattService: stopScan() - queue size =1,
08-29 08:38:06.227  4297  4316 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 08:38:06.227  4297  4316 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 08:38:06.228  4297  4333 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 08:38:06.229  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:38:06.229  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 08:38:06.229  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 08:38:06.230  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 08:38:06.230  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:38:06.232  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:38:06.232  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:38:06.233  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:38:06.234  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:38:06.235  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:06.236  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:38:06.236  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:38:06.237  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 08:38:06.239  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:38:06.239  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:06.239  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:38:06.240  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:06.240  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.240  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:38:06.241  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:06.241  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7744883 removed from the list
,08-29 08:38:06.241  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.241  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecfa00 removed from the list
,08-29 08:38:06.241  4297  4313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 08:38:06.242  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.242  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:38:06.242  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:38:06.243  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.243  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:38:06.244  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:38:06.245  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.245  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.245  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecfa00 not in the list
,08-29 08:38:06.245  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.245  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:38:06.246  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.247  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-29 08:38:06.247  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.247  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228e9df removed from the list
08-29 08:38:06.247  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:38:06.247  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.247  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.247  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
,08-29 08:38:06.248  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@972a07e removed from the list
,08-29 08:38:06.248  4297  4313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 08:38:06.248  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 08:38:06.249  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:38:06.249  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45c44fb added. We now have 2 listener(s)
08-29 08:38:06.252  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:38:06.252  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:06.253  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:38:06.253  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:06.253  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d700918 added. We now have 9 listener(s)
,08-29 08:38:06.253  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:06.254  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:38:06.257  4297  4313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 08:38:06.257  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.257  4297  4316 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:38:06.258  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:06.263  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 08:38:06.264  4297  4313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-29 08:38:06.264  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:38:06.265  4297  4316 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:38:06.267  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:38:06.267  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:38:06.268  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:38:06.268  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d784156 added. We now have 3 listener(s)
,08-29 08:38:06.270  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.271  4297  4313 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:38:06.271  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-29 08:38:06.272  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 08:38:06.273  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:38:06.273  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:06.273  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:38:06.273  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 08:38:06.273  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea035d7 added. We now have 10 listener(s)
08-29 08:38:06.274  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:06.274  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:06.275  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 08:38:06.275  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 08:38:06.275  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 08:38:06.275  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 08:38:06.276  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 08:38:06.279  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 08:38:06.279  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:38:06.285  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:38:06.286  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 08:38:06.286  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:38:06.290  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 08:38:06.290  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:38:06.290  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 08:38:06.291  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:38:06.294  4297  4308 D BtGatt.GattService: registerClient() - UUID=144ebd50-214c-473d-afeb-f1aac1b718e4
,08-29 08:38:06.294  4297  4313 D BtGatt.GattService: onClientRegistered() - UUID=144ebd50-214c-473d-afeb-f1aac1b718e4, clientIf=5
,08-29 08:38:06.294  3925  3966 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 08:38:06.295  4297  4307 D BtGatt.GattService: start scan with filters
,08-29 08:38:06.298  4297  4316 D BtGatt.ScanManager: handling starting scan
,08-29 08:38:06.298  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 08:38:06.298  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 08:38:06.298  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 08:38:06.298  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:38:06.303  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:38:06.303  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 08:38:06.303  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:38:06.304  4297  4313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-29 08:38:06.304  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.305  4297  4316 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:38:06.306  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:38:06.310  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:38:06.310  3925  3976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 08:38:06.311  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:38:06.311  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:38:06.311  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:38:06.311  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:38:06.311  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.311  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:38:06.312  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:06.312  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45c44fb removed from the list
08-29 08:38:06.312  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.312  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d700918 removed from the list
,08-29 08:38:06.312  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:38:06.312  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:38:06.313  4297  4313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 08:38:06.313  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.313  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.313  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 08:38:06.313  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.313  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:38:06.313  4297  4316 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 08:38:06.313  4297  4316 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:38:06.316  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 08:38:06.316  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.316  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.316  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d700918 not in the list
08-29 08:38:06.316  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:38:06.316  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:38:06.316  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:38:06.317  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:38:06.317  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 08:38:06.318  3925  3976 D BluetoothAdapter: STATE_ON
08-29 08:38:06.318  4297  4307 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:38:06.319  4297  4325 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:38:06.320  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 08:38:06.320  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:38:06.320  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:38:06.320  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:38:06.320  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 08:38:06.322  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:38:06.322  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:38:06.322  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:38:06.322  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:38:06.323  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.325  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:38:06.325  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:38:06.325  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:38:06.325  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.325  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:06.326  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.326  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea035d7 removed from the list
08-29 08:38:06.326  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:06.326  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.326  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: releas,e: 1 listener(s) left
08-29 08:38:06.326  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:06.326  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d784156 removed from the list
08-29 08:38:06.328  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:38:06.328  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec85873 added. We now have 2 listener(s),
08-29 08:38:06.329  4297  4313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 08:38:06.329  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.331  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 08:38:06.331  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:06.331  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:06.331  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:06.331  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232e330 added. We now have 9 listener(s)
08-29 08:38:06.332  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:06.333  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-29 08:38:06.337  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.339  4297  4313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 08:38:06.339  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:06.344  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:38:06.347  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:38:06.347  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-29 08:38:06.347  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 08:38:06.347  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc6252e added. We now have 3 listener(s),
08-29 08:38:06.349  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:38:06.349  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 08:38:06.349  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:38:06.350  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:06.350  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24608cf added. We now have 10 listener(s),
,08-29 08:38:06.350  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:06.350  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:38:06.350  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 08:38:06.350  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 08:38:06.350  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.350  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.350  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 08:38:06.352  4297  4313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-29 08:38:06.352  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.352  4297  4316 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:38:06.353  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.355  3925  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 08:38:06.355  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 08:38:06.359  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 08:38:06.360  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 08:38:06.361  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 08:38:06.362  4297  4313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 08:38:06.362  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 08:38:06.362  4297  4316 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 08:38:06.364  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 08:38:06.364  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 08:38:06.364  3925  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 08:38:06.365  3925  3976 D BluetoothAdapter: STATE_ON
,08-29 08:38:06.368  4297  4308 D BtGatt.GattService: registerClient() - UUID=9b21304e-0c59-4d31-8d5a-674cbbd8cfef
08-29 08:38:06.369  4297  4313 D BtGatt.GattService: onClientRegistered() - UUID=9b21304e-0c59-4d31-8d5a-674cbbd8cfef, clientIf=5
08-29 08:38:06.369  3925  3936 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 08:38:06.370  4297  4336 D BtGatt.GattService: start scan with filters
08-29 08:38:06.371  4297  4313 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:38:06.371  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:38:06.373  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 08:38:06.373  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 08:38:06.373  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 08:38:06.373  4297  4316 D BtGatt.ScanManager: handling starting scan
08-29 08:38:06.373  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 08:38:06.377  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 08:38:06.378  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 08:38:06.378  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 08:38:06.380  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 08:38:06.382  4297  4313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 08:38:06.382  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.382  4297  4316 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 08:38:06.387  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 08:38:06.388  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:38:06.388  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:38:06.388  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:06.388  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.388  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 08:38:06.388  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:06.388  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec85873 removed from the list
,08-29 08:38:06.388  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.389  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232e330 removed from the list
,08-29 08:38:06.389  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 08:38:06.389  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:38:06.389  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.390  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 08:38:06.390  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.390  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 08:38:06.390  4297  4313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 08:38:06.390  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:38:06.391  4297  4316 D BtGatt.ScanManager: Starting BLE batch scan
08-29 08:38:06.391  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:06.391  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.391  4297  4316 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 08:38:06.391  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.391  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232e330 not in the list
,08-29 08:38:06.391  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 08:38:06.391  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 08:38:06.391  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 08:38:06.391  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 08:38:06.392  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 08:38:06.393  3925  3976 D BluetoothAdapter: STATE_ON
08-29 08:38:06.394  4297  4308 D BtGatt.GattService: stopScan() - queue size =1
08-29 08:38:06.395  4297  4336 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 08:38:06.395  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 08:38:06.395  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 08:38:06.396  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 08:38:06.396  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 08:38:06.396  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 08:38:06.397  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:38:06.397  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 08:38:06.397  3925  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 08:38:06.398  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 08:38:06.399  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:38:06.405  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 08:38:06.405  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:06.405  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.405  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:38:06.405  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24608cf removed from the list
08-29 08:38:06.406  3925  3925 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 08:38:06.406  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 08:38:06.406  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.406  3925  3925 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 08:38:06.406  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.406  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:06.406  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc6252e removed from the list
08-29 08:38:06.407  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:06.407  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24462eb added. We now have 2 listener(s)
08-29 08:38:06.409  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 08:38:06.409  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:38:06.409  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 08:38:06.409  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:06.409  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a03e848 added. We now have 9 listener(s)
08-29 08:38:06.409  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 08:38:06.410  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 08:38:06.413  4297  4313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 08:38:06.413  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:38:06.414  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 08:38:06.421  3925  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 08:38:06.422  4297  4313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 08:38:06.422  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.423  3925  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 08:38:06.424  3925  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 08:38:06.424  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 08:38:06.424  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1ac06 added. We now have 3 listener(s)
,08-29 08:38:06.426  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 08:38:06.426  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 08:38:06.427  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 08:38:06.427  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 08:38:06.427  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58442c7 added. We now have 10 listener(s)
08-29 08:38:06.427  3925  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 08:38:06.428  3925  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 08:38:06.428  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 08:38:06.428  3925  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 08:38:06.428  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 08:38:06.428  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:06.428  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.429  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 08:38:06.429  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 08:38:06.429  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24462eb removed from the list
08-29 08:38:06.429  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.430  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a03e848 removed from the list
,08-29 08:38:06.431  3925  3925 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 08:38:06.431  3925  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-29 08:38:06.431  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 08:38:06.432  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 08:38:06.432  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.433  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:06.433  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.433  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 08:38:06.433  3925  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a03e848 not in the list
,08-29 08:38:06.433  4297  4313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 08:38:06.433  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.433  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:38:06.433  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.434  4297  4316 D BtGatt.ScanManager: stopping BLe Batch
,08-29 08:38:06.434  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 08:38:06.434  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 08:38:06.435  3925  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 08:38:06.435  3925  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58442c7 removed from the list
,08-29 08:38:06.435  3925  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 08:38:06.435  3925  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 08:38:06.435  3925  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 08:38:06.435  3925  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 08:38:06.435  3925  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c1ac06 removed from the list
,08-29 08:38:06.436  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 08:38:06.436  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 08:38:06.437  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 08:38:06.437  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 08:38:06.437  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 08:38:06.437  3925  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 08:38:06.443  4297  4313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 08:38:06.443  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 08:38:06.443  4297  4316 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 08:38:06.445  3925  4375 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,08-29 08:38:06.447  3925  4375 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 466, thread name: My test thread name)
,08-29 08:38:06.447  3925  4375 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 08:38:06.449  3925  4376 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: My test thread name)
08-29 08:38:06.449  3925  4376 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 468, thread name: My test thread name)
08-29 08:38:06.449  3925  4376 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 08:38:06.449  4297  4313 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 08:38:06.449  4297  4313 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 08:38:06.451  3925  3976 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 08:38:06.451  3925  3976 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 08:38:06.452  3925  3976 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-29 08:38:06.452  3925  3976 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 08:38:06.452  3925  3976 D com.test.thalitest.ThaliTestRunner: Total duration: 22991 ms,
,08-29 08:38:06.453  3925  3976 I jxcore-log: Total number of executed tests:  80
08-29 08:38:06.453  3925  3976 I jxcore-log: 
08-29 08:38:06.453  3925  3976 I jxcore-log: Number of passed tests:  80
08-29 08:38:06.453  3925  3976 I jxcore-log: 
,08-29 08:38:06.454  3925  3976 I jxcore-log: Number of failed tests:  0
08-29 08:38:06.454  3925  3976 I jxcore-log: 
,08-29 08:38:06.454  3925  3976 I jxcore-log: Number of ignored tests:  0
08-29 08:38:06.454  3925  3976 I jxcore-log: ,
08-29 08:38:06.454  3925  3976 I jxcore-log: Total duration:  22991
08-29 08:38:06.454  3925  3976 I jxcore-log: 
,08-29 08:38:06.454  3925  3976 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 08:38:06.454  3925  3976 I jxcore-log: 
,08-29 08:38:06.457  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.457  3925  3976 I jxcore-log: 
08-29 08:38:06.460  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.460  3925  3976 I jxcore-log: 
08-29 08:38:06.461  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.461  3925  3976 I jxcore-log: 
08-29 08:38:06.462  3925  3925 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 08:38:06.462  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.462  3925  3976 I jxcore-log: 
08-29 08:38:06.463  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.463  3925  3976 I jxcore-log: 
08-29 08:38:06.464  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.464  3925  3976 I jxcore-log: 
08-29 08:38:06.466  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.466  3925  3976 I jxcore-log: 
08-29 08:38:06.468  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.468  3925  3976 I jxcore-log: 
,08-29 08:38:06.469  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.469  3925  3976 I jxcore-log: 
08-29 08:38:06.470  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:38:06.470  3925  3976 I jxcore-log: 
08-29 08:38:06.471  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:06.471  3925  3976 I jxcore-log: 
,08-29 08:38:06.472  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:06.472  3925  3976 I jxcore-log: 
,08-29 08:38:06.473  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.473  3925  3976 I jxcore-log: 
08-29 08:38:06.474  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.474  3925  3976 I jxcore-log: 
,08-29 08:38:06.474  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:06.474  3925  3976 I jxcore-log: 
,08-29 08:38:06.475  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 08:38:06.475  3925  3976 I jxcore-log: 
08-29 08:38:06.476  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.476  3925  3976 I jxcore-log: 
,08-29 08:38:06.477  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.477  3925  3976 I jxcore-log: 
,08-29 08:38:06.477  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.477  3925  3976 I jxcore-log: 
,08-29 08:38:06.482  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.482  3925  3976 I jxcore-log: 
,08-29 08:38:06.483  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.483  3925  3976 I jxcore-log: 
,08-29 08:38:06.483  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.483  3925  3976 I jxcore-log: 
,08-29 08:38:06.484  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.484  3925  3976 I jxcore-log: 
,08-29 08:38:06.486  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 08:38:06.486  3925  3976 I jxcore-log: 
,08-29 08:38:06.487  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:38:06.487  3925  3976 I jxcore-log: 
,08-29 08:38:06.487  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 08:38:06.487  3925  3976 I jxcore-log: 
,08-29 08:38:06.488  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.488  3925  3976 I jxcore-log: 
,08-29 08:38:06.489  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.489  3925  3976 I jxcore-log: 
08-29 08:38:06.489  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.489  3925  3976 I jxcore-log: 
08-29 08:38:06.490  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.490  3925  3976 I jxcore-log: 
08-29 08:38:06.490  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.490  3925  3976 I jxcore-log: 
08-29 08:38:06.491  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 08:38:06.491  3925  3976 I jxcore-log: 
,08-29 08:38:06.737  3925  3925 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:38:06.742  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:38:06.742  3925  3976 I jxcore-log: 
,08-29 08:38:06.825  3925  3925 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:38:06.829  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:38:06.829  3925  3976 I jxcore-log: 
,08-29 08:38:06.907  3925  3925 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 08:38:06.911  3925  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 08:38:06.911  3925  3976 I jxcore-log: 
,08-29 08:38:07.096  4377  4377 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 08:38:07.101  4377  4377 D AndroidRuntime: CheckJNI is OFF
,08-29 08:38:07.143  4377  4377 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 08:38:07.190  4377  4377 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 08:38:07.213  4377  4377 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 08:38:07.223   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 08:38:07.224   871   884 I ActivityManager: Killing 3925:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 08:38:07.371   871   895 W PackageSettings: Skipping PackageSetting{3c0ede1 com.example.hello/10273} due to missing metadata
,08-29 08:38:07.374   871  1968 I WindowState: WIN DEATH: Window{685fbc2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 08:38:07.375   871  1976 D GraphicsStats: Buffer count: 2
08-29 08:38:07.376   871  1314 D WifiService: Client connection lost with reason: 4
,08-29 08:38:07.424   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 08:38:07.424   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 08:38:07.425   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-29 08:38:07.425   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 08:38:07.425   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.425   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.425   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 08:38:07.425   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 08:38:07.426   871   884 I ActivityManager:   Force finishing activity ActivityRecord{d51467b u0 com.test.thalitest/.MainActivity t2}
,08-29 08:38:07.430   871  1910 W ActivityManager: Spurious death for ProcessRecord{f26c1dd 0:com.test.thalitest/u0a0}, curProc for 3925: null
,08-29 08:38:07.435   871   895 I art     : Starting a blocking GC Explicit
,08-29 08:38:07.477   871   895 I art     : Explicit concurrent mark sweep GC freed 13849(965KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 714us total 41.727ms
,08-29 08:38:07.532   871   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 08:38:07.536  4377  4377 I art     : System.exit called, status: 0
08-29 08:38:07.536  4377  4377 I AndroidRuntime: VM exiting with result code 0.
,08-29 08:38:07.541   871   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 08:38:07.563   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 08:38:07.567  4297  4297 D BluetoothMapAppObserver: onReceive
08-29 08:38:07.567  4297  4297 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 08:38:07.568  1876  1876 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 08:38:07.569  1889  2272 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 08:38:07.572  3795  3795 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 08:38:07.573   871  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 08:38:07.579  1876  4388 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 08:38:07.585  1876  4388 I Decoder : createOrResetDecoder
,08-29 08:38:07.611   871   881 I ActivityManager: Start proc 4391:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 08:38:07.611  1956  1956 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 08:38:07.639  1507  1507 I ConfigService: onCreate
,08-29 08:38:07.652  4391  4391 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 08:38:07.661   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 08:38:07.666  1876  4388 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 08:38:07.678   871  1394 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3925 uid 10000
,08-29 08:38:07.680  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-29 08:38:07.721  4391  4391 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 08:38:07.723  1971  2080 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 08:38:07.726   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 08:38:07.727   871   883 E PackageManager: Failed to write settings, restoring backup
08-29 08:38:07.727   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 08:38:07.727   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 08:38:07.727   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 08:38:07.727   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 08:38:07.727   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 08:38:07.727   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.727   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.727   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 08:38:07.727  1876  4388 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 08:38:07.730  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 08:38:07.730  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 08:38:07.731   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-29 08:38:07.731   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 08:38:07.731   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:38:07.731   871   884 E DropBoxManagerService: 	... 13 more
,08-29 08:38:07.732  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 08:38:07.732  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 08:38:07.733  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 08:38:07.733  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 08:38:07.734  1876  4388 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 08:38:07.734  1876  4388 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-29 08:38:07.734  1876  4388 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 08:38:07.734  1876  4388 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 08:38:07.734  1876  4388 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 08:38:07.734  1876  4388 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 08:38:07.740  4391  4405 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.740  4391  4405 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.740  4391  4405 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:38:07.743   871   881 I ActivityManager: Start proc 4408:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 08:38:07.744  1971  2080 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 08:38:07.744  1971  2080 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1971
08-29 08:38:07.744  1971  2080 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	,at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.744  1971  2080 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:38:07.746   871  2005 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 08:38:07.746   871  4416 E DropBoxManagerService: Can't write: system_app_crash
08-29 08:38:07.746   871  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:38:07.746   871  4416 E DropBoxManagerService: 	... 5 more
,08-29 08:38:07.789  1971  2080 I Process : Sending signal. PID: 1971 SIG: 9
,08-29 08:38:07.817   871  1994 I ActivityManager: Start proc 4424:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 08:38:07.820  4391  4423 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 08:38:07.849  4424  4424 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 08:38:07.884  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 08:38:07.885  1507  1507 D AndroidRuntime: Shutting down VM
08-29 08:38:07.886  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
08-29 08:38:07.886  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
08-29 08:38:07.886  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 08:38:07.886  1507  1507 E AndroidRuntime: 	... 8 more
,08-29 08:38:07.890  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
,08-29 08:38:07.894   871  4440 E DropBoxManagerService: Can't write: system_app_crash
08-29 08:38:07.894   871  4440 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:38:07.894   871  4440 E DropBoxManagerService: 	... 5 more
,08-29 08:38:07.915   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-29 08:38:07.923  4391  4405 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-29 08:38:07.929  4391  4423 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.929  4391  4423 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:38:07.929  4391  4423 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 08:38:07.929  4391  4423 E AndroidRuntime: Process: android.process.acore, PID: 4391
08-29 08:38:07.929  4391  4423 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 08:38:07.929  4391  4423 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 08:38:07.935  1716  4438 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@426888a
08-29 08:38:07.935   871  1314 D WifiService: Client connection lost with reason: 4
,08-29 08:38:07.939   871  1910 I WindowState: WIN DEATH: Window{ef22ccc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-29 08:38:07.940   871  2007 D GraphicsStats: Buffer count: 1
,08-29 08:38:07.941   871  2005 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
,08-29 08:38:07.944   871  2005 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-29 08:38:07.945   871  2005 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 10999ms
,08-29 08:38:07.945   871  2005 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,08-29 08:38:07.945   871  2005 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30998ms
,08-29 08:38:07.964  1716  1716 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 08:38:07.967  4391  4405 I Process : Sending signal. PID: 4391 SIG: 9
,08-29 08:38:07.970   871  4062 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1971) has died
,08-29 08:38:07.971   871  4062 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40973ms
,08-29 08:38:07.972   871  4062 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 08:38:07.986   871   884 I ActivityManager: Start proc 4442:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 08:38:08.021   871  1429 I ActivityManager: Start proc 4455:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-29 08:38:08.030   871  2005 I ActivityManager: Process android.process.acore (pid 4391) has died
,08-29 08:38:08.030   871  2005 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30914ms
,08-29 08:38:08.039   871  4465 E DropBoxManagerService: Can't write: system_app_crash
08-29 08:38:08.039   871  4465 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 08:38:08.039   871  4465 E DropBoxManagerService: 	... 5 more
,08-29 08:38:08.058  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-29 08:38:08.058  1716  1716 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-29 08:38:08.062  4455  4455 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm

```
