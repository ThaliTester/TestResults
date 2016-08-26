#### Test 82865362163efc7_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-26 20:27:56.091   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-26 20:27:56.168  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 20:27:56.176  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 20:27:56.178  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 20:27:56.194  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 20:27:56.194  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 20:27:56.194  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:27:56.194  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 20:27:56.207  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 20:27:56.208  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 20:27:56.208  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 20:27:56.724  3790  3790 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 20:27:56.729  3790  3790 D AndroidRuntime: CheckJNI is OFF
08-26 20:27:56.774  3790  3790 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 20:27:56.825  3790  3790 I Radio-JNI: register_android_hardware_Radio DONE
08-26 20:27:56.848  3790  3790 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 20:27:56.853   870  1435 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 20:27:56.891  3790  3790 D AndroidRuntime: Shutting down VM
08-26 20:27:56.894  2010  2026 W SearchService: Abort, client detached.
08-26 20:27:56.902  2010  2320 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3a24166
08-26 20:27:56.902  2010  2336 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 20:27:56.902  2010  2010 I HotwordDetector: Closing mic
08-26 20:27:56.919   870  1976 I ActivityManager: Start proc 3799:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 20:27:56.948   375  2338 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 20:27:56.950   375  2338 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 20:27:56.961   375  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 20:27:56.963  2010  2327 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 20:27:56.964  2010  2333 I MicroRecognitionRnrImpl: Detection finished
08-26 20:27:56.998  3799  3799 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 20:27:57.025  3799  3799 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 20:27:57.033  3799  3799 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 377-380)
08-26 20:27:57.033  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 20:27:57.049  3799  3799 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e7d1c78}
08-26 20:27:57.049  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 20:27:57.050  3799  3799 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 20:27:57.055  3799  3799 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 20:27:57.056  3799  3799 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 20:27:57.070  3799  3799 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 20:27:57.079  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 20:27:57.079  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 20:27:57.079  3799  3799 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 20:27:57.079  3799  3799 I Adreno  : Build Date                       : 10/20/15
08-26 20:27:57.079  3799  3799 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 20:27:57.079  3799  3799 I Adreno  : Local Branch                     : M14
08-26 20:27:57.079  3799  3799 I Adreno  : Remote Branch                    : 
08-26 20:27:57.079  3799  3799 I Adreno  : Remote Branch                    : 
08-26 20:27:57.079  3799  3799 I Adreno  : Reconstruct Branch               : 
,08-26 20:27:57.140   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b01f6e2:true
,08-26 20:27:57.187  3799  3799 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 20:27:57.206  3799  3799 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 20:27:57.294  3799  3839 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 20:27:57.302  3799  3826 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 20:27:57.348  3799  3839 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 20:27:57.423   870   888 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +526ms
,08-26 20:27:57.431  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-26 20:27:57.505  3799  3799 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3799
,08-26 20:27:57.601  3799  3799 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 20:27:57.718   870  1435 I ActivityManager: Killing 2976:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 20:27:57.756   870  1435 I ActivityManager: Killing 3201:com.google.android.gm/u0a78 (adj 15): empty #18
,08-26 20:27:57.857  3799  3842 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1696401104
,08-26 20:27:57.874  3799  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 20:27:57.874  3799  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 20:27:57.874  3799  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 20:27:57.874  3799  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 20:27:57.874  3799  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 20:27:57.875  3799  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f807c added. We now have 1 listener(s)
,08-26 20:27:57.889  3799  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 20:27:57.891  3799  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 20:27:57.892  3799  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 20:27:57.893  3799  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 20:27:57.897  3799  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec10f8b added. We now have 1 listener(s)
08-26 20:27:57.898  3799  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:27:57.900   870  1315 D WifiService: New client listening to asynchronous messages
,08-26 20:27:57.902  3799  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:27:57.902  3799  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 20:27:57.902  3799  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 20:27:57.902  3799  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 20:27:57.902  3799  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 20:27:57.905  3799  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:27:57.906  3799  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 20:27:57.912  3799  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:27:57.912  3799  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 20:27:57.913  3799  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-26 20:27:57.913  3799  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 20:27:57.913  3799  3842 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 20:27:58.014  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:27:58.020  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:27:58.021  3799  3799 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 20:27:59.115   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:27:59.273  3799  3851 W jxcore-log: Initializing JXcore engine
,08-26 20:27:59.273  3799  3851 W jxcore-log: JXcore engine is ready
,08-26 20:27:59.310  3851  3851 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 20:27:59.310  3851  3851 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10460]" dev="sockfs" ino=10460 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 20:27:59.310  3851  3851 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 20:27:59.310  3851  3851 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26817]" dev="sockfs" ino=26817 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 20:27:59.325  3799  3851 W jxcore-log: Starting JXcore engine
,08-26 20:27:59.403  3799  3851 W jxcore-log: Platform android
08-26 20:27:59.403  3799  3851 W jxcore-log: 
08-26 20:27:59.403  3799  3851 W jxcore-log: Process ARCH arm
08-26 20:27:59.403  3799  3851 W jxcore-log: 
,08-26 20:27:59.500   870  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 20:27:59.603  3799  3851 I jxcore-log: JXcore Cordova bridge is ready!
08-26 20:27:59.603  3799  3851 I jxcore-log: 
,08-26 20:27:59.603  3799  3851 W jxcore-log: JXcore engine is started
,08-26 20:27:59.616  3799  3842 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 20:27:59.623  3799  3799 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 20:28:02.147   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:02.690  3038  3857 V KeepSync: Connecting to GoogleApiClient
08-26 20:28:02.690   870  3078 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 20:28:02.742  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:02.743  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:02.770  1519  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 20:28:02.770  1519  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 20:28:02.770  1519  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:02.770  1519  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 20:28:02.793  3554  3859 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 20:28:02.793  3554  3859 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at blb.a(PG:3937)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at czp.a(PG:18188)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:28:02.793  3554  3859 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	... 12 more
08-26 20:28:02.793  3554  3859 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at fal.a(PG:38)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:28:02.793  3554  3859 E HttpOperation: 	... 14 more
,08-26 20:28:02.872  1519  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:28:02.872  1519  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:28:02.872  1519  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:02.872  1519  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:02.885  3554  3859 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 20:28:02.885  3554  3859 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jcn.a(PG:1379),
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at hec.a(PG:42)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at hee.a(PG:102)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at czr.a(PG:65)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at kka.a(PG:108)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at czp.a(PG:19176)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:28:02.885  3554  3859 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	... 15 more
08-26 20:28:02.885  3554  3859 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at fal.a(PG:38)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:28:02.885  3554  3859 E HttpOperation: 	... 17 more
08-26 20:28:02.885  3554  3859 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 20:28:02.885  3554  3859 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at hec.a(PG:42)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at hee.a(PG:102)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at czr.a(PG:65)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at kka.a(PG:108)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	,at jdj.a(PG:4091)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	... 15 more
08-26 20:28:02.885  3554  3859 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at fal.a(PG:38)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 20:28:02.885  3554  3859 E ExperimentLoader: 	... 17 more
,08-26 20:28:02.963  1729  3860 I art     : Waiting for a blocking GC DisableMovingGc
,08-26 20:28:02.974  1729  3860 I art     : WaitForGcToComplete blocked for 11.224ms for cause DisableMovingGc
08-26 20:28:02.974  1729  3860 I art     : Starting a blocking GC DisableMovingGc
08-26 20:28:02.975   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 124978, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:28:03.009  1519  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-26 20:28:03.009  1519  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 20:28:03.009  1519  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:03.009  1519  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:03.025  1729  3860 V BaseAuthAsyncOperation: access token request failed
08-26 20:28:03.025  3038  3857 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 20:28:03.078  1519  2194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 20:28:03.078  1519  2194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-26 20:28:03.080  1519  2194 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 20:28:03.081  1519  2194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:03.103  3038  3857 E KeepSync: IOException
08-26 20:28:03.103  3038  3857 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 20:28:03.103  3038  3857 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:28:03.103  3038  3857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 20:28:03.103  3038  3857 E KeepSync: 	... 10 more
,08-26 20:28:03.103  3038  3857 W KeepSync: Sync result 2
,08-26 20:28:03.116   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 124766, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:28:05.184   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:11.235   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:13.421  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 20:28:13.421  3799  3851 I jxcore-log: 
,08-26 20:28:13.424  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 20:28:13.424  3799  3851 I jxcore-log: 
,08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:13.438  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:13.445  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:13.452  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 20:28:13.452  3799  3851 I jxcore-log: 
,08-26 20:28:13.460  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 20:28:13.460  3799  3851 I jxcore-log: 
,08-26 20:28:13.899  3799  3851 I jxcore-log: Running unit tests
08-26 20:28:13.899  3799  3851 I jxcore-log: 
,08-26 20:28:13.900  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 20:28:13.900  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b6d1bc added. We now have 2 listener(s)
08-26 20:28:13.901  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 20:28:13.901  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 20:28:13.902  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 20:28:13.902  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 20:28:13.902  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f26c545 added. We now have 2 listener(s)
08-26 20:28:13.902  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:28:13.902  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:28:13.910  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:13.914  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:13.916  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:13.916  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:28:13.917  3799  3851 D executeNativeTests: Running unit tests
,08-26 20:28:13.925  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:13.932  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:13.977  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 20:28:13.978  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb added. We now have 3 listener(s)
,08-26 20:28:13.979  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 20:28:13.979  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 20:28:13.979  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 20:28:13.979  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:28:13.979  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 added. We now have 3 listener(s)
,08-26 20:28:13.979  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:28:13.979  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:28:13.982  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:13.994  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:13.995  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:13.996  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:28:13.998  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 20:28:14.000  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 20:28:14.000  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 20:28:14.001  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 20:28:14.004  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:14.008  3799  3851 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 20:28:14.009  3799  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 20:28:14.009  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 20:28:14.009  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:14.009  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:14.010  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:14.010  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:14.011  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:14.014  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:14.014  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:14.015  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:14.016  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.017  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:14.017  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 20:28:14.017  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb removed from the list
08-26 20:28:14.017  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:14.017  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 removed from the list
08-26 20:28:14.018  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 20:28:14.018  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.018  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.018  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.019  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:14.019  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:28:14.020  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:14.020  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:14.021  3799  3851 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 20:28:14.022  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:14.022  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:14.022  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:14.022  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 20:28:14.022  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.022  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.022  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:14.022  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:14.022  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
,08-26 20:28:14.023  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:14.023  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.023  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.023  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.023  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:14.024  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:14.024  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:14.024  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:14.024  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
,08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 20:28:14.029  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 20:28:14.030  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 20:28:14.031  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 20:28:14.031  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:14.031  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:14.031  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 20:28:14.031  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:14.032  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.032  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.032  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:14.032  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:14.032  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:14.032  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 20:28:14.032  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.032  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.032  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:14.032  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:14.034  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:14.034  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:28:14.034  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:14.034  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:14.034  3799  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 20:28:14.036  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:14.042  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:14.043  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:14.044  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 20:28:14.044  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 20:28:14.044  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 20:28:14.044  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 20:28:14.044  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:28:14.044  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 20:28:14.046  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:14.048  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 20:28:14.048  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 20:28:14.049  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:14.053  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 20:28:14.055  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 20:28:14.055  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 20:28:14.059  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 20:28:14.062  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 20:28:14.063  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 20:28:14.063  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 20:28:14.063  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 20:28:14.064  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:28:14.069  2685  2847 D BtGatt.GattService: registerClient() - UUID=de6e5388-a54f-4aca-9862-1f49011827fd
,08-26 20:28:14.070  2685  2706 D BtGatt.GattService: onClientRegistered() - UUID=de6e5388-a54f-4aca-9862-1f49011827fd, clientIf=5
,08-26 20:28:14.070  3799  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 20:28:14.071  2685  2696 D BtGatt.GattService: start scan with filters
,08-26 20:28:14.074  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 20:28:14.076  2685  2710 D BtGatt.ScanManager: handling starting scan
,08-26 20:28:14.077  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 20:28:14.077  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 20:28:14.077  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 20:28:14.080  2685  2710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:28:14.081  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 20:28:14.082  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 20:28:14.082  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 20:28:14.083  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-26 20:28:14.086  3799  3851 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 20:28:14.087  2685  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 20:28:14.087  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:14.088  2685  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 20:28:14.093  2685  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 20:28:14.093  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:14.093  2685  2710 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 20:28:14.093  2685  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 20:28:14.101  2685  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 20:28:14.101  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:14.105  2685  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 20:28:14.105  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:14.265   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:14.584  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-26 20:28:14.585  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 20:28:14.585  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 20:28:15.612  2685  2685 D BtGatt.ScanManager: awakened up at time 138959
,08-26 20:28:15.615  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:15.662  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-26 20:28:15.663  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:15.663  2685  2706 D BtGatt.GattService: current time is 139010550116
,08-26 20:28:15.664  2685  2706 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -90, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 30, 55, 11, -53, -15, -31, 1, -128, -106, 18, 0, 27, 2, 1, 6, 17, 6, -70, 86, -119, -90, -6, -65, -94, -67, 1, 70, 125, 110, 29, 100, -85, -83, 5, 22, 10, 24, 7, 6, 0, 71, -122, -77, 84, 69, -12, 1, -128, -70, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 20:28:15.667  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-26 20:28:15.669  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 17, 6, -70, 86, -119, -90, -6, -65, -94, -67, 1, 70, 125, 110, 29, 100, -85, -83, 5, 22, 10, 24, 7, 6]
,08-26 20:28:15.670  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-26 20:28:15.670  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-26 20:28:15.671  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-26 20:28:15.671  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 20:28:17.167  2685  2685 D BtGatt.ScanManager: awakened up at time 140514
,08-26 20:28:17.169  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:17.246  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-26 20:28:17.247  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:17.247  2685  2706 D BtGatt.GattService: current time is 140594361255
08-26 20:28:17.247  2685  2706 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-26 20:28:17.247  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-26 20:28:17.248  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
08-26 20:28:17.248  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-26 20:28:17.277   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:17.285   870  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,08-26 20:28:17.417  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:17.427  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:17.429  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:17.467  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 20:28:17.468  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 20:28:17.468  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 20:28:17.468  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:17.504  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 20:28:17.505  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 20:28:17.506  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 20:28:18.749  2685  2685 D BtGatt.ScanManager: awakened up at time 142096
,08-26 20:28:18.754  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:18.782  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-26 20:28:18.782  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:18.782  2685  2706 D BtGatt.GattService: current time is 142129418232
08-26 20:28:18.782  2685  2706 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -68, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -88, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,08-26 20:28:18.782  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-26 20:28:18.783  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-26 20:28:18.783  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-26 20:28:18.785  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-26 20:28:19.095  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:19.096  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:28:19.096  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 20:28:19.097  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:19.097  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-26 20:28:19.097  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 20:28:19.098  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 20:28:19.098  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 20:28:19.098  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 20:28:19.100  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 20:28:19.101  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 20:28:19.103  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:28:19.105  2685  2698 D BtGatt.GattService: stopScan() - queue size =1
,08-26 20:28:19.108  2685  2847 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 20:28:19.109  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 20:28:19.110  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 20:28:19.110  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 20:28:19.110  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 20:28:19.111  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 20:28:19.114  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:28:19.115  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 20:28:19.115  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 20:28:19.116  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 20:28:19.118  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:19.122  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:19.122  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:28:19.122  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:19.122  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 20:28:19.122  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:19.122  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:28:19.123  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
,08-26 20:28:19.123  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:28:19.123  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
,08-26 20:28:19.123  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:19.124  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:19.128  2685  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 20:28:19.128  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:19.129  2685  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-26 20:28:19.138  2685  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 20:28:19.138  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:19.138  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:19.153  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 20:28:19.154  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:19.624  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 20:28:20.294   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:20.303   870  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-26 20:28:23.327   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:24.126  3799  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 20:28:24.134  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:24.151  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:24.162  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:24.163  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:28:24.165  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 20:28:24.167  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 20:28:24.167  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 20:28:24.167  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:28:24.168  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 20:28:24.172  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:24.181  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:24.185  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 20:28:24.185  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 20:28:24.200  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 20:28:24.203  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 20:28:24.204  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 20:28:24.217  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 20:28:24.217  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 20:28:24.218  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 20:28:24.220  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:28:24.229  2685  2847 D BtGatt.GattService: registerClient() - UUID=5f27130b-3a71-4d2c-86e3-e069757069cb
,08-26 20:28:24.231  2685  2706 D BtGatt.GattService: onClientRegistered() - UUID=5f27130b-3a71-4d2c-86e3-e069757069cb, clientIf=5
,08-26 20:28:24.232  3799  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 20:28:24.233  2685  2696 D BtGatt.GattService: start scan with filters
,08-26 20:28:24.246  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 20:28:24.246  2685  2710 D BtGatt.ScanManager: handling starting scan
,08-26 20:28:24.247  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 20:28:24.248  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 20:28:24.248  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 20:28:24.262  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 20:28:24.263  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 20:28:24.266  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 20:28:24.272  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 20:28:24.282  3799  3851 I io.jxcore.node.ConnectionHelper: start: OK
08-26 20:28:24.275  2685  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 20:28:24.285  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:24.285  2685  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 20:28:24.295  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:28:24.295  3799  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 20:28:24.295  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:28:24.295  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 20:28:24.295  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:28:24.295  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-26 20:28:24.295  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 20:28:24.295  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 20:28:24.295  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-26 20:28:24.295  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 20:28:24.296  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 20:28:24.296  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 20:28:24.298  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:28:24.299  2685  2847 D BtGatt.GattService: stopScan() - queue size =1
08-26 20:28:24.300  2685  2698 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 20:28:24.300  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 20:28:24.301  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 20:28:24.301  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 20:28:24.301  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 20:28:24.301  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 20:28:24.304  2685  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 20:28:24.304  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-26 20:28:24.305  2685  2710 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 20:28:24.305  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:28:24.305  2685  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 20:28:24.305  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 20:28:24.306  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 20:28:24.306  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 20:28:24.308  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:24.311  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 20:28:24.311  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 20:28:24.312  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:28:24.312  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:24.312  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:28:24.313  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:24.313  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
,08-26 20:28:24.314  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:24.314  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
,08-26 20:28:24.314  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:24.314  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:24.315  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:28:24.316  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:24.319  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:28:24.319  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:28:24.319  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:28:24.319  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:24.323  3799  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 20:28:24.330  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:24.334  2685  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 20:28:24.334  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:24.342  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:24.346  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:24.346  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 20:28:24.348  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 20:28:24.348  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 20:28:24.348  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 20:28:24.348  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:28:24.348  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 20:28:24.349  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:24.352  2685  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 20:28:24.353  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:24.354  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:24.357  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 20:28:24.357  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 20:28:24.364  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 20:28:24.365  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 20:28:24.365  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 20:28:24.367  2685  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 20:28:24.367  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.368  2685  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-26 20:28:24.374  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 20:28:24.374  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 20:28:24.374  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 20:28:24.376  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:28:24.377  2685  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 20:28:24.377  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.378  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:24.381  2685  2847 D BtGatt.GattService: registerClient() - UUID=b754a5e1-85a4-41e6-adac-72b530237232
,08-26 20:28:24.382  2685  2706 D BtGatt.GattService: onClientRegistered() - UUID=b754a5e1-85a4-41e6-adac-72b530237232, clientIf=5
,08-26 20:28:24.384  3799  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 20:28:24.385  2685  2698 D BtGatt.GattService: start scan with filters
,08-26 20:28:24.389  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 20:28:24.389  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.392  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 20:28:24.392  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 20:28:24.393  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 20:28:24.393  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 20:28:24.394  2685  2710 D BtGatt.ScanManager: handling starting scan
,08-26 20:28:24.400  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 20:28:24.401  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 20:28:24.401  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 20:28:24.405  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 20:28:24.406  2685  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 20:28:24.406  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.407  2685  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 20:28:24.412  3799  3851 I io.jxcore.node.ConnectionHelper: start: OK,
,08-26 20:28:24.419  2685  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 20:28:24.419  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.419  2685  2710 D BtGatt.ScanManager: Starting BLE batch scan
08-26 20:28:24.420  2685  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 20:28:24.437  2685  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 20:28:24.437  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.448  2685  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 20:28:24.448  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:24.902  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-26 20:28:24.903  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 20:28:24.903  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 20:28:25.954  2685  2685 D BtGatt.ScanManager: awakened up at time 149301
,08-26 20:28:25.960  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:26.013  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-26 20:28:26.013  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:26.014  2685  2706 D BtGatt.GattService: current time is 149361144734
,08-26 20:28:26.015  2685  2706 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-26 20:28:26.016  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-26 20:28:26.017  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-26 20:28:26.018  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-26 20:28:26.019  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-26 20:28:26.020  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-26 20:28:26.021  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 20:28:26.363   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 20:28:26.575   870   890 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 20:28:26.585  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-26 20:28:26.597   870   890 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 20:28:26.597   870   890 I Adreno  : Build Date                       : 10/20/15
08-26 20:28:26.597   870   890 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 20:28:26.597   870   890 I Adreno  : Local Branch                     : M14
08-26 20:28:26.597   870   890 I Adreno  : Remote Branch                    : 
08-26 20:28:26.597   870   890 I Adreno  : Remote Branch                    : 
08-26 20:28:26.597   870   890 I Adreno  : Reconstruct Branch               : 
,08-26 20:28:26.633   281   369 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (734 us)
,08-26 20:28:27.311  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 20:28:27.311  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 20:28:27.373   870   890 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 20:28:27.373  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@762c38e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7844a25, 16908290=android.view.AbsSavedState$1@7844a25}, android:focusedViewId=100}]}]
,08-26 20:28:27.379  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 20:28:27.381   870   890 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-26 20:28:27.381  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 20:28:27.381  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 20:28:27.386   870   888 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 20:28:27.386   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-26 20:28:27.386   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 20:28:27.515  2685  2685 D BtGatt.ScanManager: awakened up at time 150862
,08-26 20:28:27.517  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:27.552  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-26 20:28:27.553  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:27.553  2685  2706 D BtGatt.GattService: current time is 150900418947
,08-26 20:28:27.554  2685  2706 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -87, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -87, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-26 20:28:27.554  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-26 20:28:27.555  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-26 20:28:27.556  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-26 20:28:27.557  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-26 20:28:27.557  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-26 20:28:27.622   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 20:28:27.625   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 20:28:27.627   870  1339 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,08-26 20:28:27.636   870   890 I DreamManagerService: Entering dreamland.
,08-26 20:28:27.637   870   890 I PowerManagerService: Dozing...
,08-26 20:28:27.639   870   885 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 20:28:27.696   375  1283 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 20:28:27.696   375  1283 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 20:28:27.706   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:28:27.715  1931  3871 D NfcService: Discovery configuration equal, not updating.
,08-26 20:28:27.720   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-26 20:28:27.721   870  1313 E native  : do suspend false
,08-26 20:28:27.743   870  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 20:28:27.752   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:28:27.758   870  1313 E native  : do suspend true
,08-26 20:28:27.833   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 20:28:27.834   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 20:28:28.057  2685  2685 D BtGatt.ScanManager: awakened up at time 151404
,08-26 20:28:28.058  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:28.099  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-26 20:28:28.099  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:28:28.100  2685  2706 D BtGatt.GattService: current time is 151447153845
,08-26 20:28:28.100  2685  2706 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -73, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-26 20:28:28.101  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-26 20:28:28.102  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-26 20:28:28.103  2685  2706 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-26 20:28:28.212   870  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-26 20:28:29.413  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:28:29.414  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:28:29.414  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 20:28:29.414  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:29.415  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-26 20:28:29.415  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 20:28:29.415  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 20:28:29.415  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 20:28:29.416  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 20:28:29.416  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 20:28:29.417  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 20:28:29.419  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:28:29.421  2685  2847 D BtGatt.GattService: stopScan() - queue size =1
08-26 20:28:29.424  2685  2698 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 20:28:29.425  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 20:28:29.425  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 20:28:29.425  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 20:28:29.426  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 20:28:29.426  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 20:28:29.432  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:28:29.434  2685  2685 D BtGatt.ScanManager: awakened up at time 152781
08-26 20:28:29.434  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 20:28:29.435  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 20:28:29.436  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 20:28:29.438  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:29.441  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 20:28:29.441  2685  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 20:28:29.441  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:29.441  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:28:29.441  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:28:29.441  2685  2710 D BtGatt.ScanManager: stopping BLe Batch
,08-26 20:28:29.455  2685  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 20:28:29.455  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:29.455  2685  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:28:29.467  2685  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 20:28:29.468  2685  2706 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:28:29.943  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 20:28:29.943  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:29.943  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 20:28:32.389  1900  2645 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 20:28:34.442  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:28:34.442  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:28:34.443  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.443  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.444  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.444  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:28:34.444  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.445  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.445  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.445  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.445  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.447  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.448  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:34.451  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:28:34.451  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.452  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:28:34.452  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.454  3799  3851 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 20:28:34.456  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:28:34.457  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:28:34.457  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.458  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.458  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:28:34.458  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.459  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
,08-26 20:28:34.459  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.459  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.460  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 20:28:34.460  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.460  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.460  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:28:34.461  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.465  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:28:34.466  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.467  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.467  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.468  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 20:28:34.468  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.469  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.469  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 20:28:34.469  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.469  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.469  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.469  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.469  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.469  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.469  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.469  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.469  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.470  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.470  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.472  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.472  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:28:34.472  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.472  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.473  3799  3851 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-26 20:28:34.473  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:28:34.473  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:28:34.473  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 20:28:34.473  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.473  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.473  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.473  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.473  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.474  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.474  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.474  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.474  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.474  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.474  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.476  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.476  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.476  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.476  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.477  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 20:28:34.477  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.477  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.477  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.477  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.477  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.477  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.477  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.477  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.477  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.478  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.478  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.478  3799  3851 D org.thaliproje,ct.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.478  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.478  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.479  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.479  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.479  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.479  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.480  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 20:28:34.482  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 20:28:34.482  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 20:28:34.482  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 20:28:34.483  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:34.483  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:34.483  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 20:28:34.483  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 20:28:34.483  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 20:28:34.483  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.484  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.484  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.484  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.484  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.484  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.484  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.484  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.484  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.485  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.485  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.485  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.485  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.485  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.487  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.487  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.487  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.487  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.488  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 20:28:34.489  3799  3851 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 20:28:34.489  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 20:28:34.497  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 20:28:34.498  3799  3851 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 20:28:34.498  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 20:28:34.498  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 20:28:34.499  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 20:28:34.499  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 20:28:34.499  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 20:28:34.500  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 20:28:34.500  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 20:28:34.500  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 20:28:34.501  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 20:28:34.501  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 20:28:34.501  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 20:28:34.501  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 20:28:34.502  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 20:28:34.502  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 20:28:34.502  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 20:28:34.503  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 20:28:34.503  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 20:28:34.503  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 20:28:34.504  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 20:28:34.504  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 20:28:34.504  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 20:28:34.504  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 20:28:34.505  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 20:28:34.505  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 20:28:34.505  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 20:28:34.505  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 20:28:34.506  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 20:28:34.506  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 20:28:34.506  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 20:28:34.507  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 20:28:34.507  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 20:28:34.508  3799  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 20:28:34.508  3799  3851 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 20:28:34.508  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 20:28:34.509  3799  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 20:28:34.509  3799  3851 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 20:28:34.509  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 20:28:34.509  3799  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 20:28:34.510  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 20:28:34.514  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 20:28:34.516  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 20:28:34.517  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 20:28:34.518  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 20:28:34.519  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 20:28:34.519  3799  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-26 20:28:34.519  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-26 20:28:34.520  3799  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 20:28:34.520  3799  3851 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 20:28:34.521  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.521  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.521  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.521  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.521  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.521  3799  3876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 20:28:34.521  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.521  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 20:28:34.523  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.523  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.523  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.523  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.523  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.523  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.523  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.524  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.526  3799  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-26 20:28:34.526  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.526  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.526  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.526  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.526  3799  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-26 20:28:34.527  2685  2838 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 20:28:34.527  3799  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-26 20:28:34.529  3799  3851 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 20:28:34.529  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.530  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.530  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.530  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.530  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.530  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.530  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.530  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.530  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.530  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.530  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.530  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.530  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.531  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.531  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.532  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.532  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.532  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.532  3799  3851 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 20:28:34.533  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.533  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.533  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.533  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.533  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.533  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.533  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.533  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.533  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.533  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.533  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.534  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.534  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.534  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.533  3799  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-26 20:28:34.535  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.535  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.535  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.535  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.541  3799  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 20:28:34.541  3799  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 20:28:34.541  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 20:28:34.541  3799  3851 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 20:28:34.541  3799  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 20:28:34.541  3799  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 20:28:34.541  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 20:28:34.541  3799  3851 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 20:28:34.541  3799  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 20:28:34.541  3799  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 20:28:34.542  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 20:28:34.542  3799  3851 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 20:28:34.542  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:34.542  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:34.542  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:34.542  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.542  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.542  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.542  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.542  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.542  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.543  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.543  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.543  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.543  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.543  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.544  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:34.544  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:34.544  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.544  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.545  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:34.545  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.545  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:34.545  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:34.545  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:34.545  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:34.545  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:34.545  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:34.545  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:35.144  3754  3878 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 20:28:35.170  3754  3879 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 20:28:35.200  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:35.205  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:35.255  1519  2194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 20:28:35.255  1519  2194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:28:35.256  1519  2194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:35.256  1519  2194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:35.314  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:35.320  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:35.395  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 20:28:35.395  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:28:35.396  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:35.397  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:35.435  3754  3879 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-26 20:28:35.436  3754  3878 E BooksSync: Soft error
08-26 20:28:35.436  3754  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:28:35.436  3754  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:28:35.436  3754  3878 E BooksSync: Sync error
08-26 20:28:35.436  3754  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:28:35.436  3754  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:28:35.436  3754  3878 I BooksSync: Finished books sync
,08-26 20:28:35.444   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158379, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:28:37.628  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:37.637  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:37.638  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:37.658  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,08-26 20:28:37.658  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
08-26 20:28:37.658  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:37.658  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:37.669  1729  3880 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
,08-26 20:28:37.809  1519  3881 I VacuumService: Vacuum at: now=1472236117809 tag=VacuumService
,08-26 20:28:37.952  1519  3882 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-26 20:28:37.955  1519  3882 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 20:28:38.050  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:38.089  1519  2194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 20:28:38.090  1519  2194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 20:28:38.090  1519  2194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:38.090  1519  2194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:38.117  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 20:28:38.118  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 20:28:38.118  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-26 20:28:39.516   870  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-26 20:28:39.546  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.547  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.547  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 20:28:39.547  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.548  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:39.548  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.548  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:28:39.549  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:39.549  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 20:28:39.549  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:39.551  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.551  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:39.552  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.552  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.553  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
,08-26 20:28:39.553  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:39.554  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.554  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.555  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:28:39.556  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.561  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:28:39.561  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:39.561  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:28:39.561  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.567  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-26 20:28:39.567  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:39.568  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 20:28:39.569  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-26 20:28:39.569  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 20:28:39.570  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-26 20:28:39.570  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-26 20:28:39.570  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 20:28:39.570  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 20:28:39.570  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-26 20:28:39.570  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 20:28:39.570  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 20:28:39.571  3799  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 20:28:39.571  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.571  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 20:28:39.571  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 20:28:39.571  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.571  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.571  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 20:28:39.571  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 20:28:39.571  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 20:28:39.572  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.572  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.573  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:28:39.573  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:28:39.574  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:28:39.574  3799  3889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 20:28:39.574  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:28:39.574  3799  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 20:28:39.574  3799  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 20:28:39.574  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.574  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 20:28:39.574  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:39.575  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:39.575  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:39.575  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:39.575  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.575  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.B,luetoothManager: release: 2 listener(s) left
08-26 20:28:39.575  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.575  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.575  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.575  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:39.576  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.576  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.576  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.576  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.577  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:39.577  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:39.577  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.577  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.579  3799  3851 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 20:28:39.579  3799  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 20:28:39.579  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 20:28:39.579  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:39.580  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 20:28:39.580  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:39.580  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:39.580  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:39.580  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:39.580  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.580  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.580  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.580  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.581  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.581  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08,-26 20:28:39.581  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.581  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.581  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.581  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.582  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:39.582  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:39.582  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.582  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.589  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:39.589  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:39.590  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:39.590  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:39.590  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.590  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.591  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.591  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.591  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.591  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:39.592  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.592  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.592  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.593  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.595  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:39.595  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:39.595  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.595  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.597  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:28:39.597  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:28:39.597  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:28:39.597  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:28:39.597  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.597  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.598  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173bb not in the list
08-26 20:28:39.598  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.598  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.598  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:39.598  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.598  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.598  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:39.598  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:39.600  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:28:39.600  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:28:39.600  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:28:39.600  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f370d8 not in the list
08-26 20:28:39.601  3799  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 20:28:39.601  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 20:28:39.601  3799  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 20:28:39.601  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 20:28:39.601  3799  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 20:28:39.602  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 20:28:39.605  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 20:28:39.605  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 20:28:39.605  3799  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 20:28:39.606  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 20:28:39.606  3799  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 20:28:39.606  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 20:28:39.606  3799  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 20:28:39.606  3799  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 20:28:39.607  3799  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 20:28:39.607  3799  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 20:28:39.607  3799  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 20:28:39.607  3799  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 20:28:39.608  3799  3851 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 20:28:39.608  3799  3851 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 20:28:39.609  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:28:39.609  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@322c1ab added. We now have 3 listener(s)
08-26 20:28:39.609  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:28:39.611  3799  3851 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 20:28:39.612   870  2038 D WifiService: setWifiEnabled: true pid=3799, uid=10000
08-26 20:28:39.612   870  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 20:28:39.652  2685  2813 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-26 20:28:39.653  2685  2813 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-26 20:28:40.075  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 20:28:40.381  1519  3882 W Uploader:  no longer exists, so no auth token.
,08-26 20:28:41.329  1519  3882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-26 20:28:41.329  1519  3882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 20:28:41.329  1519  3882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:41.329  1519  3882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:41.347  1519  3882 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 20:28:41.347  1519  3882 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 20:28:41.347  1519  3882 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 20:28:41.820  1519  3882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-26 20:28:41.820  1519  3882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 20:28:41.820  1519  3882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:41.820  1519  3882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:41.834  1519  3882 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 20:28:41.834  1519  3882 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 20:28:41.834  1519  3882 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 20:28:41.978  1519  3882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-26 20:28:41.978  1519  3882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 20:28:41.978  1519  3882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:41.978  1519  3882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:41.992  1519  3882 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 20:28:41.992  1519  3882 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 20:28:41.992  1519  3882 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 20:28:43.050   870  2082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 20:28:44.620  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 20:28:44.620  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@210c008 added. We now have 4 listener(s)
08-26 20:28:44.620  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:28:44.636  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:28:44.637  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@210c008 removed from the list
08-26 20:28:44.637  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:44.637  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:44.637  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:28:44.640  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 20:28:44.640  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d463a1 added. We now have 4 listener(s)
08-26 20:28:44.640  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:28:44.646  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:28:44.646  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d463a1 removed from the list
08-26 20:28:44.647  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:28:44.647  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:28:44.647  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:28:44.650  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:28:44.650  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54fa9c6 added. We now have 4 listener(s)
,08-26 20:28:44.651  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:28:44.658   870  1976 D WifiService: setWifiEnabled: false pid=3799, uid=10000
,08-26 20:28:44.658   870  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 20:28:44.673  2685  2702 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 20:28:44.675  2685  2702 D BluetoothAdapterProperties: Setting state to 13
,08-26 20:28:44.675  2685  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 20:28:44.676  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:28:44.677  2685  2702 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 20:28:44.680  2685  2702 I BluetoothAdapterState: Entering PendingCommandState
,08-26 20:28:44.683  2685  2706 D BluetoothAdapterProperties: Scan Mode:20
,08-26 20:28:44.683  2685  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 20:28:44.690  2685  2685 D HeadsetService: Received stop request...Stopping profile...
08-26 20:28:44.694  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:44.695  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:44.696  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:44.697  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:44.697  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:28:44.699  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 20:28:44.703  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.704  1944  2213 D BluetoothHeadset: Proxy object disconnected
08-26 20:28:44.704   870   870 D BluetoothHeadset: Proxy object disconnected,
08-26 20:28:44.704   870   870 D BluetoothHeadset: Proxy object disconnected
08-26 20:28:44.704   870   870 D BluetoothHeadset: Proxy object disconnected
08-26 20:28:44.704   870  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 20:28:44.705   870  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 20:28:44.705   870  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 20:28:44.705   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 20:28:44.705  1351  1367 D BluetoothHeadset: Proxy object disconnected
08-26 20:28:44.705  2685  2685 D A2dpService: Received stop request...Stopping profile...
,08-26 20:28:44.706  1351  1351 D HeadsetProfile: Bluetooth service disconnected
,08-26 20:28:44.706  2685  2853 D A2dpStateMachine: Exit Disconnected: -1
,08-26 20:28:44.708  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.709   870   870 D BluetoothA2dp: Proxy object disconnected
08-26 20:28:44.710  1351  1351 D BluetoothA2dp: Proxy object disconnected
,08-26 20:28:44.711  2685  2685 V BluetoothAdapterState: isTurningOff()=true
,08-26 20:28:44.711  2685  2685 V BluetoothAdapterState: isTurningOn()=false
,08-26 20:28:44.711  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 20:28:44.711  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:28:44.711  2685  2685 D HidService: Received stop request...Stopping profile...,
08-26 20:28:44.711  2685  2685 D HidService: Stopping Bluetooth HidService
08-26 20:28:44.712  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-26 20:28:44.712  1351  1351 D HidProfile: Bluetooth service disconnected
,08-26 20:28:44.713  2685  2685 D HealthService: Received stop request...Stopping profile...
,08-26 20:28:44.713  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:44.714  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:44.716  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:44.716  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:44.717   870  1313 E native  : do suspend true
,08-26 20:28:44.719  2685  2685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 20:28:44.719  2685  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 20:28:44.719  2685  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:28:44.719  2685  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:28:44.720  2685  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 20:28:44.720  2685  2706 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 20:28:44.721  2685  2685 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 20:28:44.722  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:44.722  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:44.723  2685  2685 D PanService: Received stop request...Stopping profile...
,08-26 20:28:44.723  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:44.723  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:44.724  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 20:28:44.724  1351  1351 D PanProfile: Bluetooth service disconnected
08-26 20:28:44.725  2685  2685 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 20:28:44.725  2685  2685 D BluetoothMapService: stop()
08-26 20:28:44.726  2685  2685 D BluetoothMapAppObserver: deinitObservers()
08-26 20:28:44.726  2685  2685 D BluetoothMapAppObserver: removeReceiver()
08-26 20:28:44.729  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:44.731   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-26 20:28:44.731   870  2085 D DhcpClient: Clearing IP address
08-26 20:28:44.731  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.734  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.734   371   869 D CommandListener: Setting iface cfg
,08-26 20:28:44.735  1519  2539 V NativeCrypto: Read error: ssl=0xaec7f000: I/O error during system call, Connection timed out
,08-26 20:28:44.737  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:44.739  1519  2539 V NativeCrypto: SSL shutdown failed: ssl=0xaec7f000: I/O error during system call, Broken pipe
,08-26 20:28:44.741   870  1976 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-26 20:28:44.741   870  2079 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 20:28:44.743   870  2079 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 20:28:44.744   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-26 20:28:44.744   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-26 20:28:44.745   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 20:28:44.750   870   883 I ActivityManager: Start proc 3901:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 20:28:44.751  2685  2685 V BluetoothAdapterState: isTurningOff()=true
,08-26 20:28:44.751  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:44.751  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 20:28:44.751  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:28:44.752  2685  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 20:28:44.752  2685  2685 V BluetoothAdapterState: isTurningOff()=true
,08-26 20:28:44.752  2685  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:28:44.753  2685  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:28:44.753  2685  2813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 20:28:44.753  2685  2813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 20:28:44.753  2685  2813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 20:28:44.753  2685  2813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 20:28:44.752  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:44.754  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:28:44.754  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 20:28:44.754  2685  2685 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 20:28:44.755  2685  2706 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 20:28:44.755   870  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 20:28:44.755  2685  2685 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 20:28:44.755   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 20:28:44.755   394   394 E Parcel  : Reading a NULL string not supported here.
08-26 20:28:44.755  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-26 20:28:44.755  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:44.756   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 20:28:44.756  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:28:44.756  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:28:44.756  2685  2685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 20:28:44.757  2685  2706 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 20:28:44.757  2685  2685 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 20:28:44.757  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-26 20:28:44.758  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:44.758  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:28:44.758  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 20:28:44.758  2685  2685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 20:28:44.758  2685  2685 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 20:28:44.756   870  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 20:28:44.759   870  1313 E native  : do suspend true
08-26 20:28:44.759  1351  1351 D BluetoothMap: Proxy object disconnected
08-26 20:28:44.759  1351  1351 D MapProfile: Bluetooth service disconnected
08-26 20:28:44.759  2685  2685 D BluetoothMapService: MAP Service closeService in
08-26 20:28:44.759  2685  2685 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 20:28:44.759  2685  2685 D ObexServerSockets0: shutdown(block = true)
08-26 20:28:44.760  2685  2685 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 20:28:44.760  2685  2873 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 20:28:44.760  2685  2838 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 20:28:44.760  2685  2685 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 20:28:44.761  2685  2874 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 20:28:44.762  2685  2685 V BluetoothAdapterState: isTurningOff()=true
08-26 20:28:44.762  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:44.762  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:28:44.762  2685  2685 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:28:44.762  2685  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 20:28:44.762   870  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 20:28:44.762  2685  2702 D BluetoothAdapterProperties: Setting state to 15
08-26 20:28:44.762  2685  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 20:28:44.762  2685  2685 D BluetoothMapService: cleanup()
08-26 20:28:44.762  2685  2685 D BluetoothMapService: MAP Service closeService in
08-26 20:28:44.763  2685  2702 I BluetoothAdapterState: Entering BleOnState
08-26 20:28:44.763  2685  2685 I BtOppRfcommListener: stopping Accept Thread
08-26 20:28:44.763  1351  2035 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 20:28:44.763  2685  3432 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 20:28:44.763  2685  3432 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 20:28:44.764  1944  2209 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:28:44.764   870   887 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 20:28:44.764   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:28:44.764  1351  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-26 20:28:44.765   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:28:44.765  1351  1367 D BluetoothPan: onBluetoothStateChange on: false
,08-26 20:28:44.766  1351  2035 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:28:44.766   870  2101 D DhcpClient: Receive thread stopped
08-26 20:28:44.766  1351  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 20:28:44.767  1351  2035 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 20:28:44.768   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:28:44.768  2685  2702 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 20:28:44.768  2685  2702 D BluetoothAdapterProperties: Setting state to 16
08-26 20:28:44.768  2685  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 20:28:44.769  2685  2702 D BluetoothAdapterProperties: onBleDisable
,08-26 20:28:44.769  2685  2702 I BluetoothAdapterState: Entering PendingCommandState
08-26 20:28:44.770  2685  2703 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 20:28:44.770  2685  2706 D BluetoothAdapterProperties: Scan Mode:20
08-26 20:28:44.771  2685  2813 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 20:28:44.771  2685  2813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:28:44.773  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:44.773  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:44.774  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:44.774  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:44.775   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-26 20:28:44.775  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:44.775  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:44.776  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.776  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:44.780  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:44.780  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:28:44.780  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.780  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:44.781  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.782  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.784  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:44.800   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:28:44.801  3901  3901 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 20:28:44.810  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 20:28:44.815  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 20:28:44.817   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b92b64:true
,08-26 20:28:44.826   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:28:44.827   870  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-26 20:28:44.827   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:28:44.831   870  1391 I ActivityManager: Start proc 3917:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 20:28:44.834   870  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 20:28:44.836   870   887 D Tethering: MasterInitialState.processMessage what=3
,08-26 20:28:44.839  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:44.840  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:28:44.841  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:28:44.842  3384  3384 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@26f807c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 20:28:44.850   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 20:28:44.852  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:44.854  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:44.854  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 20:28:44.855  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:44.856  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:44.856  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:28:44.857  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.857  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:44.858  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:44.858  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:44.858  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:44.859  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:28:44.851  1900  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 20:28:44.860   870  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 20:28:44.878  3917  3917 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 20:28:44.880  3901  3901 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 20:28:44.882  3901  3901 D BluetoothMap: Create BluetoothMap proxy object
,08-26 20:28:44.897  3901  3901 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 20:28:44.909   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-26 20:28:44.910   870  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 20:28:44.912  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-26 20:28:44.920   870  1435 I ActivityManager: Killing 3384:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 20:28:44.972  2685  2706 I bt_hci  : shut_down
,08-26 20:28:45.039  2685  2711 D bt_hwcfg: hw_epilog_process
,08-26 20:28:45.040  2685  2711 I bt_vendor: low_power_mode_cb
,08-26 20:28:45.065  2685  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 20:28:45.065  2685  2711 I bt_vendor: epilog_cb
,08-26 20:28:45.065  2685  2711 I bt_hci  : epilog_finished_callback
,08-26 20:28:45.072  2685  2706 I bt_hci_h4: hal_close
,08-26 20:28:45.073  2685  2706 I bt_userial_vendor: device fd = 51 close
,08-26 20:28:45.161  3917  3917 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 20:28:45.161  3917  3917 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 20:28:45.161  3917  3917 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 20:28:45.161  3917  3917 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:28:45.161  3917  3917 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.161  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:28:45.162  3917  3917 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
,08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:28:45.162  3917  3917 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:28:45.162  3917  3917 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:28:45.162  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:28:45.171  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 20:28:45.189  3901  3901 D DockEventReceiver: finishStartingService: stopping service
08-26 20:28:45.188  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 20:28:45.190  2685  2703 D bt_stack_manager: event_shut_down_stack finished.
08-26 20:28:45.190  2685  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-26 20:28:45.191   870  1976 I ActivityManager: Killing 3569:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-26 20:28:45.236  2685  2685 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 20:28:45.237  2685  2702 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 20:28:45.237  2685  2685 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 20:28:45.238  2685  2685 D BtGatt.GattService: stop()
,08-26 20:28:45.238  2685  2685 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 20:28:45.246  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-26 20:28:45.246  2685  2685 V BluetoothAdapterState: isTurningOff()=false
08-26 20:28:45.246  2685  2685 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:45.246  2685  2685 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:28:45.246  2685  2685 V BluetoothAdapterState: isBleTurningOff()=true
08-26 20:28:45.247  2685  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 20:28:45.247  2685  2702 D BluetoothAdapterProperties: Setting state to 10
08-26 20:28:45.248  2685  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 20:28:45.251   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-26 20:28:45.259  2685  2702 I BluetoothAdapterState: Entering OffState
,08-26 20:28:45.263  1729  1729 D SystemUpdateService: onCreate
,08-26 20:28:45.273  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 20:28:45.275  2685  2685 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 20:28:45.275  2685  2685 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 20:28:45.275  2685  2685 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 20:28:45.275  2685  2703 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 20:28:45.278  2685  2703 D bt_stack_manager: event_clean_up_stack finished.
,08-26 20:28:45.282  2685  2685 I art     : System.exit called, status: 0
,08-26 20:28:45.282  2685  2685 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 20:28:45.310  1729  3954 I SystemUpdateService: active receiver: enabled
,08-26 20:28:45.317  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 20:28:45.324  1729  2516 I iu.UploadsManager: num queued entries: 0
08-26 20:28:45.325  1729  2516 I iu.UploadsManager: num updated entries: 0
08-26 20:28:45.325  1729  2516 I iu.SyncManager: NEXT; no task
,08-26 20:28:45.328  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 20:28:45.332  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 20:28:45.340  1729  3954 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 20:28:45.344  1729  3954 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 20:28:45.345  1729  3954 I SystemUpdateService: now status is 0 (complete)
08-26 20:28:45.345  1729  3954 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 20:28:45.345  1729  3954 I SystemUpdateService: file has been verified
08-26 20:28:45.345  1729  3954 I SystemUpdateService: OTA package size = 12249756
,08-26 20:28:45.351  1729  3954 I SystemUpdateService: showing system update notification
,08-26 20:28:45.368  3917  3941 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 20:28:45.378   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39bd5fb:true
,08-26 20:28:45.396   870  1976 I ActivityManager: Start proc 3959:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 20:28:45.399   870  3078 I ActivityManager: Process com.android.bluetooth (pid 2685) has died
,08-26 20:28:45.459  1729  1729 D SystemUpdateService: onDestroy
,08-26 20:28:45.468  3959  3959 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 20:28:45.471  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:28:45.477  3959  3959 D SprintDMHelper: simOperator: 
08-26 20:28:45.477  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 20:28:45.494   870  2041 I ActivityManager: Start proc 3971:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 20:28:45.581  2251  3985 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 20:28:45.616   870  1976 I ActivityManager: Start proc 3986:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 20:28:45.620   870  1976 I ActivityManager: Killing 3453:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 20:28:45.688  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 20:28:45.758  3986  3986 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 20:28:45.758  3986  3986 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 20:28:45.758  3986  3986 I GAv4    :   adb logcat -s GAv4
,08-26 20:28:45.774  3986  3986 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 20:28:45.781  3986  3986 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 20:28:45.804  3986  4003 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 20:28:45.933  3986  3986 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 20:28:45.970  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 20:28:45.979  3986  3986 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9323-9326)
,08-26 20:28:45.980  3986  3986 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 20:28:45.995  3986  3986 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ed200ac}
,08-26 20:28:45.995  3986  3986 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 20:28:45.995  3986  3986 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 20:28:46.005  3986  3986 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 20:28:46.007  3986  3986 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 20:28:46.026  3986  3986 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 20:28:46.042  3986  3986 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 20:28:46.042  3986  3986 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 20:28:46.042  3986  3986 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 20:28:46.042  3986  3986 I Adreno  : Build Date                       : 10/20/15
08-26 20:28:46.042  3986  3986 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 20:28:46.042  3986  3986 I Adreno  : Local Branch                     : M14
08-26 20:28:46.042  3986  3986 I Adreno  : Remote Branch                    : 
08-26 20:28:46.042  3986  3986 I Adreno  : Remote Branch                    : 
08-26 20:28:46.042  3986  3986 I Adreno  : Reconstruct Branch               : 
,08-26 20:28:46.106  3986  3986 I NSApplication: Starting up...
,08-26 20:28:46.090  3986  4032 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 20:28:46.135   870  1976 I ActivityManager: Start proc 4037:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 20:28:46.137   870  1976 I ActivityManager: Killing 3497:android.process.acore/u0a5 (adj 15): empty #17
,08-26 20:28:46.204  4037  4037 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 20:28:46.387   870  1435 I ActivityManager: Killing 3658:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 20:28:46.483   870  2038 I ActivityManager: Start proc 4051:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 20:28:46.559  4051  4051 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 20:28:46.607  4051  4051 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 20:28:46.619   870  1949 I ActivityManager: Killing 3671:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 20:28:49.699   870  1967 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,08-26 20:28:49.700   870  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 20:28:49.725   870  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-26 20:28:49.731  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:49.731  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:49.731  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:49.732  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:28:49.735  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:49.735  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:49.736  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:49.736  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:49.739  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:49.739  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:28:49.740  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:49.740  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:28:49.763   870  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-26 20:28:49.764   870  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 20:28:49.765   870  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 20:28:49.766   870  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 20:28:49.767   870  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 20:28:49.767   870  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 20:28:49.767   870  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 20:28:49.779   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 20:28:49.779   870  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-26 20:28:49.780   371   869 D CommandListener: Setting iface cfg
,08-26 20:28:49.789   870  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
08-26 20:28:49.789   870  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 20:28:49.791   870  1313 E native  : do suspend true
,08-26 20:28:49.801   870  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 20:28:49.802   870  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 20:28:49.813   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:28:50.531   870  1949 I ActivityManager: Killing 2163:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 20:28:50.790  3986  3986 I art     : Waiting for a blocking GC DisableMovingGc
,08-26 20:28:50.796  3986  3986 I art     : WaitForGcToComplete blocked for 5.521ms for cause DisableMovingGc
08-26 20:28:50.796  3986  3986 I art     : Starting a blocking GC DisableMovingGc
,08-26 20:28:51.204   870  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 20:28:51.304   870  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.62 rxSuccessRate=7.31 delta 1000 -> 994
,08-26 20:28:51.305   870  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 20:28:51.305   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 20:28:51.319   870  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 20:28:51.355   870  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 20:28:51.357  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 20:28:51.837  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 20:28:51.877  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 20:28:51.877  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 20:28:51.882   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:28:51.892   870  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 20:28:51.893   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 20:28:51.893   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 20:28:51.913   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 20:28:51.925   371   869 D CommandListener: Setting iface cfg
,08-26 20:28:51.926   870  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 20:28:51.934   870  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 20:28:51.954   870  4084 D DhcpClient: Receive thread started
,08-26 20:28:52.040   870  1313 E native  : do suspend false
,08-26 20:28:52.063   870  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 20:28:52.082   870  4084 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,08-26 20:28:52.083   870  2085 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,08-26 20:28:52.089   870  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 20:28:52.109   870  4084 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 20:28:52.111   870  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 20:28:52.118   371   869 D CommandListener: Setting iface cfg
,08-26 20:28:52.127   870  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 20:28:52.130   870  2085 D DhcpClient: Scheduling renewal in 86399s
,08-26 20:28:52.130   870  1313 E native  : do suspend true
,08-26 20:28:52.145   870  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 20:28:52.148   870  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 20:28:52.149   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 20:28:52.153   870  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 20:28:52.163   870  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 20:28:52.200   870  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 20:28:52.200   870  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 20:28:52.202   870  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 20:28:52.203   870  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 20:28:52.204   870  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 20:28:52.214   870  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 20:28:52.221   870  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 20:28:52.222   870  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-26 20:28:52.222   870  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 20:28:52.222   870  1316 D ConnectivityService:    accepting network in place of null
08-26 20:28:52.222   870  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 20:28:52.224   870  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 20:28:52.224   870  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 20:28:52.234   870  4083 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175580, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 20:28:52.252   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:28:52.283   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:28:52.290   870  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 20:28:52.291   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:28:52.295   870  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 20:28:52.303   870   887 D Tethering: MasterInitialState.processMessage what=3
08-26 20:28:52.306   870  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:814::200e
,08-26 20:28:52.314  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:52.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:52.314  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:52.315  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:52.320  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:52.321  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 20:28:52.321  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:52.321  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:52.324  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:28:52.324  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:28:52.324  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:52.324  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:28:52.329  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 20:28:52.335  1729  1729 D SystemUpdateService: onCreate
,08-26 20:28:52.340  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 20:28:52.362  1729  4094 I SystemUpdateService: active receiver: enabled
,08-26 20:28:52.367  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 20:28:52.371  1729  2516 I iu.UploadsManager: num queued entries: 0
,08-26 20:28:52.371  1729  2516 I iu.UploadsManager: num updated entries: 0
,08-26 20:28:52.380  1729  4094 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 20:28:52.381   870  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 18:28:52 GMT], X-Android-Received-Millis=[1472236132379], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472236132352]}
,08-26 20:28:52.381  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 20:28:52.383   870  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 20:28:52.383   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 20:28:52.383   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101],
,08-26 20:28:52.384   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 20:28:52.385  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 20:28:52.387  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:28:52.395  1729  4098 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null],
08-26 20:28:52.395  1729  4098 W BaseAppContext: Using Auth Proxy for data requests.
08-26 20:28:52.395  3959  3959 D SprintDMHelper: simOperator: 
08-26 20:28:52.395  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 20:28:52.402  1729  4098 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 20:28:52.413  1729  4094 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 20:28:52.413  1729  4094 I SystemUpdateService: now status is 0 (complete)
08-26 20:28:52.413  1729  4094 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 20:28:52.413  1729  4094 I SystemUpdateService: file has been verified
08-26 20:28:52.413  1729  4094 I SystemUpdateService: OTA package size = 12249756
,08-26 20:28:52.419  1729  2516 I iu.SyncManager: NEXT; no task
,08-26 20:28:52.423  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:52.424  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:52.429  1729  4094 I SystemUpdateService: showing system update notification
,08-26 20:28:52.487  1729  1729 D SystemUpdateService: onDestroy
,08-26 20:28:52.504  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-26 20:28:52.505  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 20:28:52.506  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:52.507  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:52.519  2251  4102 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 20:28:52.525  1729  4098 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-26 20:28:53.291   870  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 20:28:54.713   870  1701 D WifiService: setWifiEnabled: false pid=3799, uid=10000
,08-26 20:28:54.713   870  1701 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 20:28:54.752  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 20:28:54.761   870  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 20:28:54.761   870  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 20:28:54.762   870  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 20:28:54.762   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 20:28:54.785   870  1313 E native  : do suspend true
,08-26 20:28:54.801   870  2085 D DhcpClient: Clearing IP address
,08-26 20:28:54.802   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-26 20:28:54.809  1519  4106 V NativeCrypto: Read error: ssl=0x9af39400: I/O error during system call, Connection timed out
,08-26 20:28:54.811   371   869 D CommandListener: Setting iface cfg
,08-26 20:28:54.816   870  4084 D DhcpClient: Receive thread stopped
,08-26 20:28:54.821   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 20:28:54.821   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-26 20:28:54.827   394   394 E Parcel  : Reading a NULL string not supported here.
08-26 20:28:54.828   870  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
08-26 20:28:54.825  1519  4106 V NativeCrypto: SSL shutdown failed: ssl=0x9af39400: I/O error during system call, Broken pipe
08-26 20:28:54.829   870  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 20:28:54.829   870  1313 E native  : do suspend true
,08-26 20:28:54.837   870  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 20:28:54.871   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:28:54.911   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:28:54.913   870  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 20:28:54.913   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:28:54.913   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-26 20:28:54.917   870   887 D Tethering: MasterInitialState.processMessage what=3
08-26 20:28:54.923  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:54.923  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:54.923  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:54.923  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:54.935  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:54.935  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:54.935  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:54.935  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:54.939  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:54.939  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:54.940  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:54.941  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:28:54.950  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 20:28:54.956  1729  1729 D SystemUpdateService: onCreate
,08-26 20:28:54.959  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 20:28:54.973  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-26 20:28:54.975  1729  2516 I iu.UploadsManager: num queued entries: 0
08-26 20:28:54.975  1729  2516 I iu.UploadsManager: num updated entries: 0
08-26 20:28:54.975  1729  2516 I iu.SyncManager: NEXT; no task
,08-26 20:28:54.981  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 20:28:54.983  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 20:28:54.985  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:28:54.989  3959  3959 D SprintDMHelper: simOperator: 
08-26 20:28:54.989  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 20:28:55.008   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-26 20:28:55.010   870  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 20:28:55.011   870  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 20:28:55.022  1729  4116 I SystemUpdateService: active receiver: enabled
,08-26 20:28:55.025  2251  4120 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 20:28:55.031   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:28:55.033  1729  4116 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 20:28:55.035  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:55.035  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:28:55.035  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:55.035  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:55.036  1729  4116 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 20:28:55.036  1729  4116 I SystemUpdateService: now status is 0 (complete)
08-26 20:28:55.036  1729  4116 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 20:28:55.036  1729  4116 I SystemUpdateService: file has been verified
08-26 20:28:55.037  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:55.037  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:55.037  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:28:55.037  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:55.038  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:28:55.038  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:28:55.038  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:28:55.039  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:28:55.039  1900  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 20:28:55.039  1729  4116 I SystemUpdateService: OTA package size = 12249756
08-26 20:28:55.050   870  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 20:28:55.052  1729  4116 I SystemUpdateService: showing system update notification
,08-26 20:28:55.062  1729  1729 D SystemUpdateService: onDestroy
,08-26 20:28:59.745   870   887 I ActivityManager: Start proc 4125:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 20:28:59.822  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:59.831  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:59.833  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:28:59.855  4125  4125 D AdapterServiceConfig: Adding HeadsetService
,08-26 20:28:59.855  4125  4125 D AdapterServiceConfig: Adding A2dpService
08-26 20:28:59.855  4125  4125 D AdapterServiceConfig: Adding HidService
08-26 20:28:59.856  4125  4125 D AdapterServiceConfig: Adding HealthService
08-26 20:28:59.856  4125  4125 D AdapterServiceConfig: Adding PanService
,08-26 20:28:59.856  4125  4125 D AdapterServiceConfig: Adding GattService
,08-26 20:28:59.856  4125  4125 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 20:28:59.878  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 20:28:59.879  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 20:28:59.879  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:28:59.879  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:28:59.880   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6c2555a:true
,08-26 20:28:59.881  4125  4125 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 20:28:59.884  4125  4125 I bt_bluedroid: init
,08-26 20:28:59.885  4125  4137 I BluetoothAdapterState: Entering OffState
,08-26 20:28:59.887  4125  4138 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 20:28:59.887  4125  4138 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 20:28:59.887  4125  4138 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 20:28:59.888  4125  4138 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 20:28:59.889  4125  4125 I bt_bluedroid: get_profile_interface socket
,08-26 20:28:59.890  4125  4125 I bt_bluedroid: get_profile_interface sdp
,08-26 20:28:59.892  4125  4141 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 20:28:59.894  4125  4136 I bt_bluedroid: config_hci_snoop_log
,08-26 20:28:59.893  4125  4141 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 20:28:59.895   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 20:28:59.899  4125  4137 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 20:28:59.899  4125  4137 D BluetoothAdapterProperties: Setting state to 14
,08-26 20:28:59.900  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 20:28:59.901  4125  4137 D BluetoothBondStateMachine: make
,08-26 20:28:59.903  4125  4142 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 20:28:59.907  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 20:28:59.907  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 20:28:59.907  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-26 20:28:59.907  4125  4137 I BluetoothAdapterState: Entering PendingCommandState
,08-26 20:28:59.908  4125  4125 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-26 20:28:59.911  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:28:59.911  4125  4125 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 20:28:59.911  4125  4125 D BtGatt.GattService: Received start request. Starting profile...
08-26 20:28:59.912  4125  4125 D BtGatt.GattService: start()
,08-26 20:28:59.912  4125  4125 I bt_bluedroid: get_profile_interface gatt
08-26 20:28:59.912  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:28:59.912  4125  4125 D BtGatt.AdvertiseManager: advertise manager created
,08-26 20:28:59.918  4125  4125 V BluetoothAdapterState: isTurningOff()=false
,08-26 20:28:59.918  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:28:59.918  4125  4125 V BluetoothAdapterState: isBleTurningOn()=true
08-26 20:28:59.918  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:28:59.919  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 20:28:59.919  4125  4137 I bt_bluedroid: enable
,08-26 20:28:59.919  4125  4138 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 20:28:59.920  4125  4138 I bt_hci  : start_up
,08-26 20:28:59.930  4125  4138 I bt_vendor: alloc value 0xb39db189
,08-26 20:28:59.930  4125  4138 I bt_vendor: init
,08-26 20:28:59.930  4125  4138 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 20:28:59.931  4125  4138 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 20:29:00.037  4125  4138 D bt_hci  : start_up starting async portion
,08-26 20:29:00.038  4125  4145 I bt_hci  : event_finish_startup
,08-26 20:29:00.038  4125  4145 I bt_hci_h4: hal_open
08-26 20:29:00.038  4125  4145 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 20:29:00.046  4125  4145 I bt_userial_vendor: device fd = 51 open
,08-26 20:29:00.080  4125  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 20:29:00.112  4125  4145 D bt_hwcfg: Chipset BCM4354A2
08-26 20:29:00.112  4125  4145 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 20:29:00.113  4125  4145 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 20:29:00.226   870  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-26 20:29:00.771  4125  4145 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 20:29:00.773  4125  4145 D bt_hwcfg: Settlement delay -- 100 ms
08-26 20:29:00.773  4125  4145 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 20:29:00.890  4125  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 20:29:00.891  4125  4145 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 20:29:00.920  4125  4145 I bt_hwcfg: vendor lib fwcfg completed
,08-26 20:29:00.920  4125  4145 I bt_vendor: firmware callback
08-26 20:29:00.920  4125  4145 I bt_hci  : firmware_config_callback
,08-26 20:29:00.932  4125  4147 I bt_btu  : btu_task pending for preload complete event
,08-26 20:29:00.932  4125  4147 I bt_btu_task: Bluetooth chip preload is complete
08-26 20:29:00.932  4125  4147 I bt_btu  : btu_task received preload complete event
,08-26 20:29:00.942  4125  4147 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 20:29:00.942  4125  4147 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 20:29:00.943  4125  4147 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 20:29:00.943  4125  4147 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 20:29:00.943  4125  4147 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 20:29:00.944  4125  4147 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 20:29:00.944  4125  4147 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 20:29:00.944  4125  4147 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 20:29:00.944  4125  4147 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 20:29:00.945  4125  4147 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 20:29:00.945  4125  4147 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 20:29:00.945  4125  4147 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 20:29:00.946  4125  4147 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 20:29:00.946  4125  4147 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 20:29:00.946  4125  4147 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 20:29:01.084  4125  4147 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3958d9d
,08-26 20:29:01.084  4125  4147 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3958d9d 
,08-26 20:29:01.106  4125  4141 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 20:29:01.107  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 20:29:01.108  4125  4141 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-26 20:29:01.111  4125  4141 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 20:29:01.114  4125  4141 D BluetoothAdapterProperties: Scan Mode:20
,08-26 20:29:01.115  4125  4141 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 20:29:01.115  4125  4141 D bt_hci  : do_postload posting postload work item
,08-26 20:29:01.117  4125  4145 I bt_hci  : event_postload
,08-26 20:29:01.118  4125  4145 I bt_vendor: sco_config_cb
,08-26 20:29:01.118  4125  4145 I bt_hci  : sco_config_callback postload finished.
,08-26 20:29:01.120  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:01.121  4125  4141 D bt_bte_conf: Device ID record 1 : primary
,08-26 20:29:01.121  4125  4141 D bt_bte_conf:   vendorId            = 000f
,08-26 20:29:01.121  4125  4141 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 20:29:01.122  4125  4141 D bt_bte_conf:   product             = 1200
,08-26 20:29:01.122  4125  4141 D bt_bte_conf:   version             = 1436
,08-26 20:29:01.122  4125  4141 D bt_bte_conf:   clientExecutableURL = 
,08-26 20:29:01.122  4125  4141 D bt_bte_conf:   serviceDescription  = 
08-26 20:29:01.122  4125  4141 D bt_bte_conf:   documentationURL    = 
08-26 20:29:01.123  4125  4141 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 20:29:01.123  4125  4138 D bt_stack_manager: event_start_up_stack finished
,08-26 20:29:01.124  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 20:29:01.124  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:01.125  4125  4137 D BluetoothAdapterProperties: Setting state to 15
,08-26 20:29:01.125  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 20:29:01.129  4125  4145 I bt_vendor: low_power_mode_cb
,08-26 20:29:01.131  4125  4137 I BluetoothAdapterState: Entering BleOnState
08-26 20:29:01.131  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 20:29:01.133  4125  4137 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 20:29:01.133  4125  4137 D BluetoothAdapterProperties: Setting state to 11
,08-26 20:29:01.133  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 20:29:01.142  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:01.146  4125  4125 D HeadsetService: Received start request. Starting profile...
,08-26 20:29:01.150  4125  4137 I BluetoothAdapterState: Entering PendingCommandState
08-26 20:29:01.154  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:01.155  4125  4125 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 20:29:01.155  4125  4125 D HeadsetStateMachine: make
,08-26 20:29:01.158  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:01.159  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 20:29:01.164  4125  4125 D HeadsetStateMachine: max_hf_connections = 1
,08-26 20:29:01.164  4125  4125 I bt_bluedroid: get_profile_interface handsfree
,08-26 20:29:01.165  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 20:29:01.165  4125  4141 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 20:29:01.170  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:01.170  4125  4125 D A2dpService: Received start request. Starting profile...
,08-26 20:29:01.172  4125  4125 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 20:29:01.172  4125  4125 I bt_bluedroid: get_profile_interface avrcp,
,08-26 20:29:01.180  4125  4125 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 20:29:01.180  4125  4125 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 20:29:01.181  4125  4125 D A2dpStateMachine: make
,08-26 20:29:01.182  4125  4125 I bt_bluedroid: get_profile_interface a2dp,
08-26 20:29:01.183  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 20:29:01.187  4125  4156 D A2dpStateMachine: Enter Disconnected: -2
,08-26 20:29:01.188  4125  4125 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 20:29:01.189  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:01.190  4125  4125 D HidService: Received start request. Starting profile...
,08-26 20:29:01.190  3901  3901 D BluetoothInputDevice: Proxy object connected
08-26 20:29:01.190  4125  4125 I bt_bluedroid: get_profile_interface hidhost
08-26 20:29:01.190  4125  4125 D HidService: setHidService(): set to: null
08-26 20:29:01.190  4125  4141 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393a3e5
08-26 20:29:01.190  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 20:29:01.191  3901  3901 D HidProfile: Bluetooth service connected
,08-26 20:29:01.191  4125  4125 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 20:29:01.192  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
08-26 20:29:01.192  4125  4125 D HealthService: Received start request. Starting profile...
,08-26 20:29:01.194  4125  4125 I bt_bluedroid: get_profile_interface health
,08-26 20:29:01.195  4125  4125 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 20:29:01.196  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:01.197  3901  3901 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 20:29:01.197  4125  4125 D PanService: Received start request. Starting profile...
08-26 20:29:01.197  4125  4125 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 20:29:01.197  4125  4125 I bt_bluedroid: get_profile_interface pan
,08-26 20:29:01.198  4125  4141 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 20:29:01.198  3901  3901 D PanProfile: Bluetooth service connected
08-26 20:29:01.199  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:01.201  3901  3901 D BluetoothMap: Proxy object connected
,08-26 20:29:01.201  4125  4125 D BluetoothMapService: Received start request. Starting profile...
08-26 20:29:01.201  4125  4125 D BluetoothMapService: start()
08-26 20:29:01.201  3901  3901 D MapProfile: Bluetooth service connected
,08-26 20:29:01.201  3901  3901 D BluetoothMap: getConnectedDevices()
08-26 20:29:01.202  3901  3901 D BluetoothMap: Bluetooth is Not enabled
,08-26 20:29:01.203  4125  4125 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 20:29:01.204  4125  4125 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 20:29:01.204  4125  4125 D BluetoothMapAppObserver: createReceiver()
08-26 20:29:01.205  4125  4125 D BluetoothMapAppObserver: initObservers()
,08-26 20:29:01.205  4125  4125 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 20:29:01.213  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 20:29:01.214  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:01.214  4125  4125 V BluetoothAdapterState: isTurningOn()=true
,08-26 20:29:01.214  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:01.214  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 20:29:01.216  4125  4154 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 20:29:01.216  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isTurningOn()=true
,08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 20:29:01.217  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:01.218  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 20:29:01.218  4125  4137 D BluetoothAdapterProperties: ScanMode =  20
08-26 20:29:01.218  4125  4137 D BluetoothAdapterProperties: State =  11
08-26 20:29:01.219  4125  4141 D BluetoothAdapterProperties: Scan Mode:21
08-26 20:29:01.219  4125  4141 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 20:29:01.222  4125  4137 D BluetoothAdapterProperties: Setting state to 12
08-26 20:29:01.222  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 20:29:01.222  4125  4137 I BluetoothAdapterState: Entering OnState
08-26 20:29:01.222  1351  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:01.224  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:01.224  1351  1351 D BluetoothInputDevice: Proxy object connected
08-26 20:29:01.224  1351  1351 D HidProfile: Bluetooth service connected
08-26 20:29:01.225  1944  2213 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:01.226   870   887 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 20:29:01.226   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:01.227  1351  1367 D BluetoothMap: onBluetoothStateChange: up=true
08-26 20:29:01.227  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:01.228  1351  1351 D BluetoothMap: Proxy object connected
08-26 20:29:01.228  1351  1351 D MapProfile: Bluetooth service connected
08-26 20:29:01.228  1351  1351 D BluetoothMap: getConnectedDevices()
08-26 20:29:01.229   870   870 D BluetoothA2dp: Proxy object connected
08-26 20:29:01.230  3901  3911 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 20:29:01.230   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:01.230  1351  1374 D BluetoothPan: onBluetoothStateChange on: true
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:01.230  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:01.231  4125  4125 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 20:29:01.232  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:01.233  1351  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:01.232  4125  4125 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 20:29:01.233  1351  2035 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 20:29:01.234  4125  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:01.235  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:01.235  3901  3913 D BluetoothPan: onBluetoothStateChange on: true
08-26 20:29:01.235  3901  3911 D BluetoothMap: onBluetoothStateChange: up=true
08-26 20:29:01.236  1351  1367 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 20:29:01.236  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:01.237  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 20:29:01.237  1351  1351 D PanProfile: Bluetooth service connected
08-26 20:29:01.237  1351  1351 D BluetoothA2dp: Proxy object connected
08-26 20:29:01.237  4125  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 20:29:01.237   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:01.237  3901  3913 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 20:29:01.238  4125  4125 D ObexServerSockets: Succeed to create listening sockets 
08-26 20:29:01.238  4125  4125 D ObexServerSockets0: startAccept()
08-26 20:29:01.238  4125  4125 D ObexServerSockets0: prepareForNewConnect()
08-26 20:29:01.240  4125  4125 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 20:29:01.240  4125  4125 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 20:29:01.241  4125  4163 D ObexServerSockets0: Accepting socket connection...
08-26 20:29:01.241  4125  4164 D ObexServerSockets0: Accepting socket connection...
08-26 20:29:01.242  4125  4125 D BluetoothMapService: onReceive
08-26 20:29:01.242  4125  4125 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 20:29:01.242  4125  4125 D BluetoothMapService: STATE_ON
08-26 20:29:01.242   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 20:29:01.244  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:01.244  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:01.245  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:01.246  3901  3901 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 20:29:01.250  3901  3901 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 20:29:01.255  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 20:29:01.256  3901  3901 D BluetoothA2dp: Proxy object connected
,08-26 20:29:01.259  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 20:29:01.264  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-26 20:29:01.268  1351  1351 D BluetoothPbap: Proxy object connected
,08-26 20:29:01.268  3901  3901 D BluetoothPbap: Proxy object connected
08-26 20:29:01.268  1351  1351 D PbapServerProfile: Bluetooth service connected
08-26 20:29:01.268  3901  3901 D PbapServerProfile: Bluetooth service connected
,08-26 20:29:01.272  4125  4125 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 20:29:01.272  4125  4125 D ObexServerSockets0: prepareForNewConnect()
,08-26 20:29:01.275  4125  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 20:29:01.289  4125  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 20:29:01.291  4125  4172 I BtOppRfcommListener: Accept thread started.
,08-26 20:29:01.326  1944  2209 D BluetoothHeadset: Proxy object connected
,08-26 20:29:01.326   870   870 D BluetoothHeadset: Proxy object connected
08-26 20:29:01.326   870   870 D BluetoothHeadset: Proxy object connected
08-26 20:29:01.326   870   870 D BluetoothHeadset: Proxy object connected
08-26 20:29:01.327  1351  1374 D BluetoothHeadset: Proxy object connected
08-26 20:29:01.327  1351  1351 D HeadsetProfile: Bluetooth service connected
08-26 20:29:01.327   870   887 D BluetoothHeadset: Proxy object connected
,08-26 20:29:01.330   870   887 D BluetoothHeadset: Proxy object connected
,08-26 20:29:01.334  1351  2035 D BluetoothHeadset: Proxy object connected
08-26 20:29:01.334  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-26 20:29:01.337   870   887 D BluetoothHeadset: Proxy object connected
,08-26 20:29:01.353  3901  3911 D BluetoothHeadset: Proxy object connected
,08-26 20:29:01.356  3901  3901 D HeadsetProfile: Bluetooth service connected
,08-26 20:29:04.736  4125  4137 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 20:29:04.737  4125  4137 D BluetoothAdapterProperties: Setting state to 13
08-26 20:29:04.737  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 20:29:04.739  4125  4137 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 20:29:04.744  4125  4137 I BluetoothAdapterState: Entering PendingCommandState
,08-26 20:29:04.751  4125  4125 D BluetoothMapService: onReceive
,08-26 20:29:04.752  4125  4125 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 20:29:04.752  4125  4125 D BluetoothMapService: STATE_TURNING_OFF
,08-26 20:29:04.753  4125  4125 D BluetoothMapService: MAP Service closeService in
08-26 20:29:04.753  4125  4125 D BluetoothMapMasInstance0: MAP Service shutdown
,08-26 20:29:04.754  4125  4125 D ObexServerSockets0: shutdown(block = true)
,08-26 20:29:04.754  4125  4163 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 20:29:04.757  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:04.758  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:04.760  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:29:04.760  4125  4125 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 20:29:04.760  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:04.762  4125  4164 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 20:29:04.762  4125  4141 D BluetoothAdapterProperties: Scan Mode:20
08-26 20:29:04.763  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 20:29:04.764  4125  4149 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 20:29:04.764  4125  4125 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 20:29:04.765  4125  4125 I BtOppRfcommListener: stopping Accept Thread
08-26 20:29:04.766  4125  4172 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 20:29:04.767  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:04.767  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:04.768  4125  4172 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 20:29:04.769  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:29:04.769  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:04.771  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:04.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:29:04.772  4125  4125 D HeadsetService: Received stop request...Stopping profile...
08-26 20:29:04.772  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 20:29:04.772  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:04.774  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:04.774  4125  4125 D A2dpService: Received stop request...Stopping profile...
08-26 20:29:04.775  4125  4156 D A2dpStateMachine: Exit Disconnected: -1
08-26 20:29:04.775  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:04.776  1944  1961 D BluetoothHeadset: Proxy object disconnected
08-26 20:29:04.776   870   870 D BluetoothHeadset: Proxy object disconnected
,08-26 20:29:04.777   870   870 D BluetoothHeadset: Proxy object disconnected
08-26 20:29:04.777  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:04.777  3901  3911 D BluetoothHeadset: Proxy object disconnected
08-26 20:29:04.777   870   870 D BluetoothHeadset: Proxy object disconnected
08-26 20:29:04.777  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-26 20:29:04.777  1351  1374 D BluetoothHeadset: Proxy object disconnected
08-26 20:29:04.778  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-26 20:29:04.778  4125  4125 D HidService: Received stop request...Stopping profile...
08-26 20:29:04.778   870   870 D BluetoothA2dp: Proxy object disconnected
08-26 20:29:04.778  4125  4125 D HidService: Stopping Bluetooth HidService
08-26 20:29:04.778  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-26 20:29:04.778  1351  1351 D HidProfile: Bluetooth service disconnected
,08-26 20:29:04.779  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 20:29:04.780  4125  4125 D HealthService: Received stop request...Stopping profile...
,08-26 20:29:04.784  4125  4125 D PanService: Received stop request...Stopping profile...
,08-26 20:29:04.784  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 20:29:04.785  1351  1351 D PanProfile: Bluetooth service disconnected
08-26 20:29:04.785  4125  4125 V BluetoothAdapterState: isTurningOff()=true
08-26 20:29:04.785  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:04.785  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:04.785  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 20:29:04.786  3901  3901 D BluetoothA2dp: Proxy object disconnected
08-26 20:29:04.786  3901  3901 D HeadsetProfile: Bluetooth service disconnected
08-26 20:29:04.786  4125  4125 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 20:29:04.786  4125  4125 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 20:29:04.787  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 20:29:04.787  4125  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 20:29:04.787  4125  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:29:04.787  4125  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:29:04.787  4125  4125 D BluetoothMapService: Received stop request...Stopping profile...
08-26 20:29:04.787  4125  4125 D BluetoothMapService: stop()
08-26 20:29:04.787  3901  3901 D BluetoothInputDevice: Proxy object disconnected
08-26 20:29:04.787  3901  3901 D HidProfile: Bluetooth service disconnected
08-26 20:29:04.788  4125  4141 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 20:29:04.788  4125  4125 D BluetoothMapAppObserver: deinitObservers()
08-26 20:29:04.788  4125  4125 D BluetoothMapAppObserver: removeReceiver()
08-26 20:29:04.789  4125  4125 V BluetoothAdapterState: isTurningOff()=true
08-26 20:29:04.789  1351  1351 D BluetoothMap: Proxy object disconnected
08-26 20:29:04.789  1351  1351 D MapProfile: Bluetooth service disconnected
08-26 20:29:04.789  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:04.790  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 20:29:04.790  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:04.791  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 20:29:04.791  4125  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:29:04.791  4125  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 20:29:04.791  4125  4147 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 20:29:04.791  4125  4147 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 20:29:04.791  4125  4147 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 20:29:04.791  4125  4125 V BluetoothAdapterState: isTurningOff()=true
,08-26 20:29:04.791  4125  4147 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 20:29:04.791  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:04.791  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 20:29:04.792  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:04.793  4125  4125 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 20:29:04.793  4125  4125 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 20:29:04.793  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 20:29:04.793  4125  4125 V BluetoothAdapterState: isTurningOff()=true
08-26 20:29:04.793  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:04.794  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-26 20:29:04.793  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:04.794  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:04.794  4125  4125 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 20:29:04.794  4125  4141 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 20:29:04.795  4125  4125 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 20:29:04.795  4125  4125 V BluetoothAdapterState: isTurningOff()=true
08-26 20:29:04.795  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:04.795  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:04.795  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:04.795  4125  4125 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 20:29:04.796  4125  4125 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 20:29:04.799  4125  4125 D BluetoothMapService: MAP Service closeService in
,08-26 20:29:04.800  4125  4125 V BluetoothAdapterState: isTurningOff()=true
08-26 20:29:04.800  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:04.801  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:04.801  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:04.801  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 20:29:04.801  4125  4125 D BluetoothMapService: cleanup()
08-26 20:29:04.801  4125  4137 D BluetoothAdapterProperties: Setting state to 15
08-26 20:29:04.801  4125  4125 D BluetoothMapService: MAP Service closeService in
08-26 20:29:04.801  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 20:29:04.802  4125  4137 I BluetoothAdapterState: Entering BleOnState
08-26 20:29:04.803  1351  2035 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 20:29:04.804  1944  2213 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:29:04.805   870   887 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 20:29:04.805   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:29:04.805  1351  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-26 20:29:04.806  1351  1351 D BluetoothPbap: Proxy object disconnected
08-26 20:29:04.806  3901  3913 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 20:29:04.806  1351  1351 D PbapServerProfile: Bluetooth service disconnected
08-26 20:29:04.806   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 20:29:04.807  1351  1367 D BluetoothPan: onBluetoothStateChange on: false
08-26 20:29:04.807  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 20:29:04.807  1351  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:29:04.807  1351  2035 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 20:29:04.809  3901  3911 D BluetoothPan: onBluetoothStateChange on: false
08-26 20:29:04.811  3901  3913 D BluetoothMap: onBluetoothStateChange: up=false
08-26 20:29:04.812  3901  3901 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 20:29:04.812  3901  3901 D PanProfile: Bluetooth service disconnected
,08-26 20:29:04.813  1351  1367 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 20:29:04.813  3901  3901 D BluetoothPbap: Proxy object disconnected
08-26 20:29:04.813  3901  3901 D PbapServerProfile: Bluetooth service disconnected
08-26 20:29:04.814   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:29:04.814  3901  3913 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 20:29:04.815  3901  3911 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 20:29:04.816  3901  4177 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 20:29:04.816  4125  4137 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 20:29:04.816  4125  4137 D BluetoothAdapterProperties: Setting state to 16
08-26 20:29:04.816  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 20:29:04.817  4125  4137 D BluetoothAdapterProperties: onBleDisable
,08-26 20:29:04.817  4125  4137 I BluetoothAdapterState: Entering PendingCommandState
08-26 20:29:04.818  4125  4138 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 20:29:04.818  4125  4147 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 20:29:04.818  4125  4147 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 20:29:04.819  4125  4141 D BluetoothAdapterProperties: Scan Mode:20
,08-26 20:29:04.821  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:04.822  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:04.824  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:04.825  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 20:29:04.826  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:04.827  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:04.828  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:04.829  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 20:29:04.835  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-26 20:29:05.020  4125  4141 I bt_hci  : shut_down
,08-26 20:29:05.034  4125  4145 D bt_hwcfg: hw_epilog_process
,08-26 20:29:05.034  4125  4145 I bt_vendor: low_power_mode_cb,
,08-26 20:29:05.050  4125  4145 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 20:29:05.050  4125  4145 I bt_vendor: epilog_cb
08-26 20:29:05.050  4125  4145 I bt_hci  : epilog_finished_callback
,08-26 20:29:05.054  4125  4141 I bt_hci_h4: hal_close
08-26 20:29:05.054  4125  4141 I bt_userial_vendor: device fd = 51 close
,08-26 20:29:05.173  4125  4138 D bt_stack_manager: event_shut_down_stack finished.
,08-26 20:29:05.175  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 20:29:05.181  4125  4137 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 20:29:05.181  4125  4125 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 20:29:05.182  4125  4125 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 20:29:05.183  4125  4125 D BtGatt.GattService: stop()
08-26 20:29:05.183  4125  4125 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 20:29:05.188  4125  4125 V BluetoothAdapterState: isTurningOff()=false
,08-26 20:29:05.188  4125  4125 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:05.189  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:05.189  4125  4125 V BluetoothAdapterState: isBleTurningOff()=true
08-26 20:29:05.190  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 20:29:05.191  4125  4137 D BluetoothAdapterProperties: Setting state to 10
08-26 20:29:05.191  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 20:29:05.193  4125  4137 I BluetoothAdapterState: Entering OffState
08-26 20:29:05.194   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 20:29:05.220  4125  4125 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 20:29:05.220  4125  4125 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 20:29:05.221  4125  4138 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 20:29:05.227  4125  4138 D bt_stack_manager: event_clean_up_stack finished.
,08-26 20:29:05.228  4125  4125 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 20:29:05.232  4125  4125 I art     : System.exit called, status: 0
,08-26 20:29:05.233  4125  4125 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 20:29:05.294   870  2041 I ActivityManager: Process com.android.bluetooth (pid 4125) has died
,08-26 20:29:09.733  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:09.734  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:09.739  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:29:09.739  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54fa9c6 removed from the list
,08-26 20:29:09.740  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 20:29:09.740  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:09.740  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:09.747  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 20:29:09.747  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f5d4b4 added. We now have 4 listener(s)
08-26 20:29:09.747  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:29:09.749  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:29:09.750  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f5d4b4 removed from the list
,08-26 20:29:09.750  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:09.750  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:09.750  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:09.753  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:09.753  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb298dd added. We now have 4 listener(s)
08-26 20:29:09.754  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:29:14.766  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:14.818   870   887 I ActivityManager: Start proc 4184:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 20:29:14.990  4184  4184 D AdapterServiceConfig: Adding HeadsetService
,08-26 20:29:14.991  4184  4184 D AdapterServiceConfig: Adding A2dpService
08-26 20:29:14.991  4184  4184 D AdapterServiceConfig: Adding HidService
08-26 20:29:14.991  4184  4184 D AdapterServiceConfig: Adding HealthService
08-26 20:29:14.991  4184  4184 D AdapterServiceConfig: Adding PanService
,08-26 20:29:14.992  4184  4184 D AdapterServiceConfig: Adding GattService
08-26 20:29:14.992  4184  4184 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 20:29:15.008   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f9ec1a:true
,08-26 20:29:15.010  4184  4184 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 20:29:15.019  4184  4184 I bt_bluedroid: init
,08-26 20:29:15.020  4184  4196 I BluetoothAdapterState: Entering OffState
,08-26 20:29:15.024  4184  4197 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 20:29:15.024  4184  4197 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 20:29:15.024  4184  4197 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 20:29:15.024  4184  4197 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 20:29:15.025  4184  4184 I bt_bluedroid: get_profile_interface socket
,08-26 20:29:15.028  4184  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 20:29:15.031  4184  4200 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 20:29:15.031  4184  4184 I bt_bluedroid: get_profile_interface sdp
,08-26 20:29:15.039  4184  4195 I bt_bluedroid: config_hci_snoop_log
,08-26 20:29:15.042   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 20:29:15.055  4184  4196 D BluetoothAdapterState: Current state: OFF, message: 0
08-26 20:29:15.056  4184  4196 D BluetoothAdapterProperties: Setting state to 14
,08-26 20:29:15.056  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 20:29:15.061  4184  4196 D BluetoothBondStateMachine: make
,08-26 20:29:15.067  4184  4201 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 20:29:15.075  4184  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-26 20:29:15.078  4184  4184 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 20:29:15.087  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:15.089  4184  4184 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 20:29:15.090  4184  4184 D BtGatt.GattService: Received start request. Starting profile...
08-26 20:29:15.091  4184  4184 D BtGatt.GattService: start()
08-26 20:29:15.091  4184  4184 I bt_bluedroid: get_profile_interface gatt
,08-26 20:29:15.094  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
08-26 20:29:15.094  4184  4184 D BtGatt.AdvertiseManager: advertise manager created
,08-26 20:29:15.107  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-26 20:29:15.107  4184  4184 V BluetoothAdapterState: isTurningOn()=false
08-26 20:29:15.107  4184  4184 V BluetoothAdapterState: isBleTurningOn()=true
08-26 20:29:15.107  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:15.108  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 20:29:15.108  4184  4196 I bt_bluedroid: enable
08-26 20:29:15.109  4184  4197 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 20:29:15.111  4184  4197 I bt_hci  : start_up
,08-26 20:29:15.131  4184  4197 I bt_vendor: alloc value 0xb39db189
08-26 20:29:15.131  4184  4197 I bt_vendor: init
08-26 20:29:15.131  4184  4197 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 20:29:15.132  4184  4197 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 20:29:15.239  4184  4197 D bt_hci  : start_up starting async portion
,08-26 20:29:15.240  4184  4204 I bt_hci  : event_finish_startup
,08-26 20:29:15.240  4184  4204 I bt_hci_h4: hal_open
08-26 20:29:15.241  4184  4204 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 20:29:15.250  4184  4204 I bt_userial_vendor: device fd = 51 open
,08-26 20:29:15.280  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 20:29:15.312  4184  4204 D bt_hwcfg: Chipset BCM4354A2
,08-26 20:29:15.312  4184  4204 D bt_hwcfg: Target name = [BCM4354A2]
08-26 20:29:15.313  4184  4204 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 20:29:15.969  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 20:29:15.971  4184  4204 D bt_hwcfg: Settlement delay -- 100 ms
08-26 20:29:15.971  4184  4204 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 20:29:16.087  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 20:29:16.089  4184  4204 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 20:29:16.118  4184  4204 I bt_hwcfg: vendor lib fwcfg completed
08-26 20:29:16.119  4184  4204 I bt_vendor: firmware callback
08-26 20:29:16.119  4184  4204 I bt_hci  : firmware_config_callback
,08-26 20:29:16.130  4184  4206 I bt_btu  : btu_task pending for preload complete event
08-26 20:29:16.131  4184  4206 I bt_btu_task: Bluetooth chip preload is complete
,08-26 20:29:16.131  4184  4206 I bt_btu  : btu_task received preload complete event
,08-26 20:29:16.141  4184  4206 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 20:29:16.141  4184  4206 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 20:29:16.142  4184  4206 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 20:29:16.142  4184  4206 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 20:29:16.142  4184  4206 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 20:29:16.142  4184  4206 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 20:29:16.142  4184  4206 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 20:29:16.143  4184  4206 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 20:29:16.143  4184  4206 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 20:29:16.143  4184  4206 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 20:29:16.143  4184  4206 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 20:29:16.143  4184  4206 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 20:29:16.144  4184  4206 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 20:29:16.144  4184  4206 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 20:29:16.144  4184  4206 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 20:29:16.280  4184  4206 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3958d9d
,08-26 20:29:16.281  4184  4206 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3958d9d 
,08-26 20:29:16.304  4184  4200 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 20:29:16.306  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 20:29:16.306  4184  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 20:29:16.308  4184  4200 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 20:29:16.311  4184  4200 D BluetoothAdapterProperties: Scan Mode:20
,08-26 20:29:16.311  4184  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 20:29:16.312  4184  4200 D bt_hci  : do_postload posting postload work item
08-26 20:29:16.312  4184  4204 I bt_hci  : event_postload
08-26 20:29:16.312  4184  4204 I bt_vendor: sco_config_cb
08-26 20:29:16.312  4184  4204 I bt_hci  : sco_config_callback postload finished.
08-26 20:29:16.314  4184  4200 D bt_bte_conf: Device ID record 1 : primary
,08-26 20:29:16.314  4184  4200 D bt_bte_conf:   vendorId            = 000f
,08-26 20:29:16.314  4184  4200 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 20:29:16.314  4184  4200 D bt_bte_conf:   product             = 1200
08-26 20:29:16.315  4184  4200 D bt_bte_conf:   version             = 1436
08-26 20:29:16.315  4184  4200 D bt_bte_conf:   clientExecutableURL = 
08-26 20:29:16.315  4184  4200 D bt_bte_conf:   serviceDescription  = 
08-26 20:29:16.315  4184  4200 D bt_bte_conf:   documentationURL    = 
,08-26 20:29:16.315  4184  4200 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 20:29:16.316  4184  4197 D bt_stack_manager: event_start_up_stack finished
08-26 20:29:16.316  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:16.318  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 20:29:16.319  4184  4196 D BluetoothAdapterProperties: Setting state to 15
08-26 20:29:16.319  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 20:29:16.319  4184  4204 I bt_vendor: low_power_mode_cb,
08-26 20:29:16.319  4184  4196 I BluetoothAdapterState: Entering BleOnState
08-26 20:29:16.322  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:16.326  4184  4196 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 20:29:16.327  4184  4196 D BluetoothAdapterProperties: Setting state to 11
08-26 20:29:16.327  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 20:29:16.340  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:16.341  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:16.346  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:16.346  4184  4184 D HeadsetService: Received start request. Starting profile...
,08-26 20:29:16.353  4184  4184 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 20:29:16.355  4184  4184 D HeadsetStateMachine: make
08-26 20:29:16.359  4184  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-26 20:29:16.365  4184  4184 D HeadsetStateMachine: max_hf_connections = 1
,08-26 20:29:16.366  4184  4184 I bt_bluedroid: get_profile_interface handsfree
08-26 20:29:16.366  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 20:29:16.366  4184  4200 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 20:29:16.379  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 20:29:16.380  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
08-26 20:29:16.381  4184  4184 D A2dpService: Received start request. Starting profile...
08-26 20:29:16.382  4184  4184 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 20:29:16.382  4184  4184 I bt_bluedroid: get_profile_interface avrcp
,08-26 20:29:16.389  4184  4184 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 20:29:16.389  4184  4184 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 20:29:16.389  4184  4184 D A2dpStateMachine: make
,08-26 20:29:16.390  4184  4184 I bt_bluedroid: get_profile_interface a2dp
08-26 20:29:16.391  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 20:29:16.393  4184  4215 D A2dpStateMachine: Enter Disconnected: -2
,08-26 20:29:16.393  4184  4184 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 20:29:16.394  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
08-26 20:29:16.395  4184  4184 D HidService: Received start request. Starting profile...
,08-26 20:29:16.395  4184  4184 I bt_bluedroid: get_profile_interface hidhost
08-26 20:29:16.395  4184  4184 D HidService: setHidService(): set to: null
08-26 20:29:16.395  4184  4200 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393a3e5
08-26 20:29:16.395  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 20:29:16.395  4184  4184 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 20:29:16.396  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:16.397  4184  4184 D HealthService: Received start request. Starting profile...
08-26 20:29:16.398  4184  4184 I bt_bluedroid: get_profile_interface health
08-26 20:29:16.399  4184  4184 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 20:29:16.400  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:16.400  4184  4184 D PanService: Received start request. Starting profile...
08-26 20:29:16.400  4184  4184 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 20:29:16.400  4184  4184 I bt_bluedroid: get_profile_interface pan
,08-26 20:29:16.401  4184  4200 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 20:29:16.408  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:16.409  4184  4184 D BluetoothMapService: Received start request. Starting profile...
08-26 20:29:16.409  4184  4184 D BluetoothMapService: start()
,08-26 20:29:16.413  4184  4184 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 20:29:16.415  4184  4184 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 20:29:16.415  4184  4184 D BluetoothMapAppObserver: createReceiver()
,08-26 20:29:16.417  4184  4184 D BluetoothMapAppObserver: initObservers()
,08-26 20:29:16.417  4184  4184 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 20:29:16.425  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-26 20:29:16.425  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:16.426  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:16.426  4184  4213 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 20:29:16.426  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 20:29:16.428  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isTurningOn()=true
,08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:16.429  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:16.430  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:16.430  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:16.430  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:16.430  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:16.430  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isTurningOn()=true
,08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-26 20:29:16.431  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-26 20:29:16.431  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 20:29:16.431  4184  4196 D BluetoothAdapterProperties: ScanMode =  20
08-26 20:29:16.431  4184  4196 D BluetoothAdapterProperties: State =  11
,08-26 20:29:16.432  4184  4200 D BluetoothAdapterProperties: Scan Mode:21
08-26 20:29:16.433  4184  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 20:29:16.433  4184  4196 D BluetoothAdapterProperties: Setting state to 12
08-26 20:29:16.433  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 20:29:16.433  4184  4196 I BluetoothAdapterState: Entering OnState
08-26 20:29:16.434  1351  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 20:29:16.436  1944  2213 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 20:29:16.437   870   887 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 20:29:16.437  1351  1351 D BluetoothInputDevice: Proxy object connected
,08-26 20:29:16.437  1351  1351 D HidProfile: Bluetooth service connected
08-26 20:29:16.437   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:16.437  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:16.437  1351  1367 D BluetoothMap: onBluetoothStateChange: up=true
08-26 20:29:16.438   870   870 D BluetoothA2dp: Proxy object connected
08-26 20:29:16.439  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:16.440  3901  4177 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 20:29:16.441  1351  1351 D BluetoothMap: Proxy object connected
08-26 20:29:16.441  1351  1351 D MapProfile: Bluetooth service connected
08-26 20:29:16.441  1351  1351 D BluetoothMap: getConnectedDevices()
08-26 20:29:16.442   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 20:29:16.443  1351  2035 D BluetoothPan: onBluetoothStateChange on: true
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:16.443  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:16.444  1351  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:16.444  4184  4184 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 20:29:16.444  1351  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 20:29:16.444  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 20:29:16.445  4184  4184 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 20:29:16.445  1351  1351 D BluetoothA2dp: Proxy object connected
08-26 20:29:16.445  3901  3913 D BluetoothPan: onBluetoothStateChange on: true
08-26 20:29:16.446  4184  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 20:29:16.447  3901  3911 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 20:29:16.448  4184  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 20:29:16.448  1351  1367 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 20:29:16.449  4184  4184 D ObexServerSockets: Succeed to create listening sockets 
08-26 20:29:16.449  4184  4184 D ObexServerSockets0: startAccept()
08-26 20:29:16.449  4184  4184 D ObexServerSockets0: prepareForNewConnect()
08-26 20:29:16.450  3901  3901 D BluetoothInputDevice: Proxy object connected
08-26 20:29:16.450  3901  3901 D HidProfile: Bluetooth service connected
08-26 20:29:16.450   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:16.451  3901  3913 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 20:29:16.451  4184  4184 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 20:29:16.451  4184  4184 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 20:29:16.452  4184  4222 D ObexServerSockets0: Accepting socket connection...
08-26 20:29:16.452  4184  4221 D ObexServerSockets0: Accepting socket connection...
,08-26 20:29:16.452  3901  3911 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 20:29:16.453  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 20:29:16.453  1351  1351 D PanProfile: Bluetooth service connected
08-26 20:29:16.453  3901  3913 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 20:29:16.455   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 20:29:16.456  4184  4184 D BluetoothMapService: onReceive
08-26 20:29:16.456  4184  4184 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 20:29:16.456  4184  4184 D BluetoothMapService: STATE_ON
08-26 20:29:16.457  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:16.458  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:16.459  3901  3901 D BluetoothMap: Proxy object connected
,08-26 20:29:16.460  3901  3901 D MapProfile: Bluetooth service connected
08-26 20:29:16.460  3901  3901 D BluetoothMap: getConnectedDevices()
08-26 20:29:16.461  3901  3901 D BluetoothA2dp: Proxy object connected
,08-26 20:29:16.462  3901  3901 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 20:29:16.462  3901  3901 D PanProfile: Bluetooth service connected
,08-26 20:29:16.466  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 20:29:16.471  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 20:29:16.472  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-26 20:29:16.479  3901  3901 D BluetoothPbap: Proxy object connected
,08-26 20:29:16.479  3901  3901 D PbapServerProfile: Bluetooth service connected
,08-26 20:29:16.481  1351  1351 D BluetoothPbap: Proxy object connected
08-26 20:29:16.481  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-26 20:29:16.484  4184  4184 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 20:29:16.484  4184  4184 D ObexServerSockets0: prepareForNewConnect()
,08-26 20:29:16.486  4184  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 20:29:16.502  4184  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 20:29:16.503  4184  4231 I BtOppRfcommListener: Accept thread started.
,08-26 20:29:16.539  1944  2209 D BluetoothHeadset: Proxy object connected
,08-26 20:29:16.539   870   870 D BluetoothHeadset: Proxy object connected
08-26 20:29:16.539   870   870 D BluetoothHeadset: Proxy object connected
08-26 20:29:16.539  3901  4177 D BluetoothHeadset: Proxy object connected
,08-26 20:29:16.539  3901  3901 D HeadsetProfile: Bluetooth service connected
08-26 20:29:16.539   870   870 D BluetoothHeadset: Proxy object connected
08-26 20:29:16.540  1351  1374 D BluetoothHeadset: Proxy object connected
08-26 20:29:16.540  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-26 20:29:16.542   870   887 D BluetoothHeadset: Proxy object connected
,08-26 20:29:16.545  1351  1367 D BluetoothHeadset: Proxy object connected
,08-26 20:29:16.545  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-26 20:29:16.550   870   887 D BluetoothHeadset: Proxy object connected
,08-26 20:29:16.553  3901  3911 D BluetoothHeadset: Proxy object connected
08-26 20:29:16.553  3901  3901 D HeadsetProfile: Bluetooth service connected
,08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:19.789  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:29:19.796  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:29:19.797  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:29:19.797  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb298dd removed from the list
08-26 20:29:19.798  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:19.798  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:19.798  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:19.801  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:19.801  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48c9c52 added. We now have 4 listener(s)
08-26 20:29:19.802  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:29:19.806   870  3078 D WifiService: setWifiEnabled: false pid=3799, uid=10000
,08-26 20:29:19.806   870  3078 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 20:29:24.820  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:24.821   870  1967 D WifiService: setWifiEnabled: true pid=3799, uid=10000
08-26 20:29:24.821   870  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 20:29:24.838   870  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:24.857  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 20:29:24.862  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:29:24.868   870  1313 D WifiConfigStore: loaded 0 passpoint configs
08-26 20:29:24.870   870  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 20:29:24.870  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 20:29:24.870   870  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 20:29:24.872   870  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 20:29:24.872   870  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 20:29:24.872   870  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 20:29:24.872   870  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-26 20:29:24.873  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 20:29:24.886   870  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 20:29:24.886   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 20:29:24.889   371   869 D CommandListener: Setting iface cfg
,08-26 20:29:24.938   870  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 20:29:24.939   870  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 20:29:24.943   870  1313 E native  : do suspend true
,08-26 20:29:24.956   870  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 20:29:24.964   870  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 20:29:24.966   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:29:26.341   870  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 20:29:26.493   870  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=8.75 delta 1000 -> 994
,08-26 20:29:26.495   870  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 20:29:26.495   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 20:29:26.519   870  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 20:29:26.589   870  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 20:29:26.592  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 20:29:26.627  1869  1927 I Keyboard.Facilitator.LanguageModelFlusher: run(),
08-26 20:29:26.627  1869  1927 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-26 20:29:26.664  1519  1519 I ConfigService: onCreate
,08-26 20:29:27.021  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 20:29:27.069  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 20:29:27.071  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 20:29:27.080   870  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 20:29:27.098   870  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 20:29:27.100   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 20:29:27.101   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 20:29:27.130   870  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 20:29:27.161   371   869 D CommandListener: Setting iface cfg
,08-26 20:29:27.164   870  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 20:29:27.183   870  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 20:29:27.192   870  4240 D DhcpClient: Receive thread started
,08-26 20:29:27.289   870  1313 E native  : do suspend false
,08-26 20:29:27.316   870  2085 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 20:29:27.335   870  4240 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-26 20:29:27.337   870  2085 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-26 20:29:27.340   870  2085 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 20:29:27.363   870  4240 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 20:29:27.364   870  2085 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 20:29:27.369   371   869 D CommandListener: Setting iface cfg
,08-26 20:29:27.380   870  2085 D DhcpClient: Scheduling renewal in 86399s
,08-26 20:29:27.382   870  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-26 20:29:27.386   870  1313 E native  : do suspend true
,08-26 20:29:27.413   870  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 20:29:27.415   870  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 20:29:27.416   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 20:29:27.417   870  1316 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 20:29:27.423   870  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 20:29:27.456   870  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 20:29:27.456   870  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 20:29:27.457   870  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 20:29:27.459   870  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 20:29:27.460   870  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 20:29:27.468   870  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 20:29:27.473   870  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 20:29:27.473   870  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-26 20:29:27.474   870  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 20:29:27.474   870  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 20:29:27.474   870  1316 D ConnectivityService:    accepting network in place of null
08-26 20:29:27.474   870  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 20:29:27.475   870  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 20:29:27.488   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210835, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 20:29:27.518   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:29:27.570   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 20:29:27.570   870  4238 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:805::200e
,08-26 20:29:27.580   870  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 20:29:27.580   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:29:27.587   870  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 20:29:27.589   870   887 D Tethering: MasterInitialState.processMessage what=3
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:27.600  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:27.603  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:27.608  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:27.611  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:29:27.617  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 20:29:27.624  1729  1729 D SystemUpdateService: onCreate
,08-26 20:29:27.632  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 20:29:27.642  1729  4249 I SystemUpdateService: active receiver: enabled
,08-26 20:29:27.648   870  4238 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 18:29:27 GMT], X-Android-Received-Millis=[1472236167647], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472236167614]}
08-26 20:29:27.649   870  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 20:29:27.649   870  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 20:29:27.649   870  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 20:29:27.650   870  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 20:29:27.652  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 20:29:27.654  1729  2516 I iu.UploadsManager: num queued entries: 0
08-26 20:29:27.655  1729  2516 I iu.UploadsManager: num updated entries: 0
,08-26 20:29:27.655  1729  2516 I iu.SyncManager: NEXT; no task
,08-26 20:29:27.662  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 20:29:27.663  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 20:29:27.664  1729  4249 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 20:29:27.666  1729  4249 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 20:29:27.666  1729  4249 I SystemUpdateService: now status is 0 (complete)
08-26 20:29:27.666  1729  4249 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 20:29:27.666  1729  4249 I SystemUpdateService: file has been verified
08-26 20:29:27.666  1729  4249 I SystemUpdateService: OTA package size = 12249756
,08-26 20:29:27.667  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 20:29:27.674  3959  3959 D SprintDMHelper: simOperator: 
,08-26 20:29:27.674  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 20:29:27.688  1729  4251 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 20:29:27.688  1729  4251 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 20:29:27.696  1729  4251 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 20:29:27.710  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:29:27.711  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:29:27.713  1729  4249 I SystemUpdateService: showing system update notification
,08-26 20:29:27.776  1729  1729 D SystemUpdateService: onDestroy
,08-26 20:29:27.808  1519  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-26 20:29:27.808  1519  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 20:29:27.808  1519  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:29:27.808  1519  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:29:27.842  2251  4255 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 20:29:27.851  1729  4251 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-26 20:29:28.577   870  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:29.849  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:29.857  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:29:29.858  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:29:29.858  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48c9c52 removed from the list
08-26 20:29:29.859  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:29.859  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:29.859  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:29.871  3799  4261 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-26 20:29:29.872  3799  4261 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 20:29:31.749  1519  1519 I ConfigService: onDestroy
,08-26 20:29:32.879  3799  4261 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-26 20:29:32.880  3799  4263 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-26 20:29:32.881  3799  4261 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-26 20:29:32.881  3799  4263 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-26 20:29:32.882  3799  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-26 20:29:32.882  3799  4261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-26 20:29:32.884  3799  4263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-26 20:29:32.884  3799  4261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-26 20:29:32.888  3799  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: IncomingSocketThread/Sender)
08-26 20:29:32.889  3799  4263 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-26 20:29:32.890  3799  4261 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-26 20:29:32.897  3799  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
,08-26 20:29:32.902  3799  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
08-26 20:29:32.903  3799  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
08-26 20:29:32.903  3799  4267 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
08-26 20:29:32.903  3799  4267 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-26 20:29:32.904  3799  4267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-26 20:29:32.904  3799  4268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
08-26 20:29:32.904  3799  4268 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-26 20:29:32.905  3799  4268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-26 20:29:35.480   870  1316 D ConnectivityService: handlePromptUnvalidated 102
,08-26 20:29:35.878  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 20:29:35.880  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 20:29:35.888  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@762c38e Bundle[{}]
,08-26 20:29:35.889  3799  3851 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 20:29:35.889  3799  3851 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 20:29:35.890  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 20:29:35.890  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 20:29:35.891  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 20:29:35.891  3799  3851 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 20:29:35.895  3799  3851 I System.out: Running OutgoingSocketThread
,08-26 20:29:35.899  3799  4269 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-26 20:29:35.899  3799  4269 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 20:29:38.907  3799  4270 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-26 20:29:38.908  3799  4270 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-26 20:29:38.908  3799  4270 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-26 20:29:38.909  3799  4269 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-26 20:29:38.910  3799  4269 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-26 20:29:38.910  3799  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-26 20:29:38.911  3799  4270 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-26 20:29:38.911  3799  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-26 20:29:38.915  3799  4270 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-26 20:29:38.916  3799  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
08-26 20:29:38.918  3799  4269 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-26 20:29:38.925  3799  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Sender)
,08-26 20:29:38.926  3799  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Receiver)
,08-26 20:29:38.928  3799  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
,08-26 20:29:38.928  3799  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: IncomingSocketThread/Receiver)
,08-26 20:29:38.929  3799  4274 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-26 20:29:38.929  3799  4275 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
08-26 20:29:38.929  3799  4275 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-26 20:29:38.929  3799  4275 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-26 20:29:38.929  3799  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-26 20:29:41.910  3799  3851 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-26 20:29:41.912  3799  3851 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 20:29:41.912  3799  3851 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,08-26 20:29:41.919  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 20:29:41.919  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebbb23 added. We now have 3 listener(s)
,08-26 20:29:41.921  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 20:29:41.921  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 20:29:41.922  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 20:29:41.922  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:41.922  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7758820 added. We now have 4 listener(s)
08-26 20:29:41.922  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:29:41.923  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:29:41.926  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:41.936  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:41.942  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:41.942  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:29:41.943  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:29:41.943  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:29:41.943  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:29:41.943  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:41.944  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:41.944  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 20:29:41.944  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 20:29:41.944  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebbb23 removed from the list
08-26 20:29:41.944  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:41.944  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7758820 removed from the list
08-26 20:29:41.948  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:41.954  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:41.954  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:41.955  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:41.955  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:41.955  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:41.958  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:29:41.958  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:41.958  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:41.959  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7758820 not in the list
08-26 20:29:41.959  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:41.959  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:41.961  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:41.961  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:29:41.961  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:41.962  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7758820 not in the list
08-26 20:29:41.962  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:41.962  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:41.962  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:41.962  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebbb23 not in the list
08-26 20:29:41.963  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 20:29:41.964  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b342b9e added. We now have 3 listener(s)
08-26 20:29:41.967  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 20:29:41.967  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 20:29:41.967  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 20:29:41.968  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:41.968  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b4e67f added. We now have 4 listener(s)
,08-26 20:29:41.968  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:29:41.969  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:29:41.974  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:41.987  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:41.992  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:29:41.992  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 20:29:41.993  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 20:29:41.993  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 20:29:41.994  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 20:29:41.994  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:29:41.994  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 20:29:41.999  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:42.002  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 20:29:42.002  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 20:29:42.006  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:42.011  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 20:29:42.014  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 20:29:42.014  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 20:29:42.024  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 20:29:42.025  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 20:29:42.025  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 20:29:42.026  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:29:42.033  4184  4211 D BtGatt.GattService: registerClient() - UUID=ec0358fa-50a7-4a95-af7c-f0424a7bcca2
,08-26 20:29:42.036  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=ec0358fa-50a7-4a95-af7c-f0424a7bcca2, clientIf=5
,08-26 20:29:42.038  3799  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 20:29:42.041  4184  4195 D BtGatt.GattService: start scan with filters
,08-26 20:29:42.053  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 20:29:42.053  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 20:29:42.053  4184  4203 D BtGatt.ScanManager: handling starting scan
08-26 20:29:42.053  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 20:29:42.054  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 20:29:42.058  4184  4203 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9c9542
,08-26 20:29:42.059  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 20:29:42.059  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 20:29:42.059  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 20:29:42.062  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 20:29:42.068  3799  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 20:29:42.068  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 20:29:42.069  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 20:29:42.069  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:42.069  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-26 20:29:42.069  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 20:29:42.069  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 20:29:42.069  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 20:29:42.070  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 20:29:42.070  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 20:29:42.070  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 20:29:42.072  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:29:42.074  4184  4195 D BtGatt.GattService: stopScan() - queue size =1
08-26 20:29:42.076  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 20:29:42.076  4184  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 20:29:42.076  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:42.077  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 20:29:42.077  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 20:29:42.077  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 20:29:42.077  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 20:29:42.078  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 20:29:42.078  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 20:29:42.080  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:29:42.080  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 20:29:42.080  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 20:29:42.080  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 20:29:42.081  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 20:29:42.084  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:29:42.084  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:29:42.084  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:29:42.098  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 20:29:42.098  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:42.100  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
08-26 20:29:42.100  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 20:29:42.131  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 20:29:42.131  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:42.155  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 20:29:42.155  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:42.184  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 20:29:42.184  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:42.185  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
,08-26 20:29:42.209  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 20:29:42.210  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:42.210  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:29:42.232  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 20:29:42.233  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:42.586  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 20:29:42.586  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:29:42.587  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 20:29:43.337   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=226683, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:29:45.085  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:29:45.085  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 20:29:45.086  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:29:45.086  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 20:29:45.087  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:45.087  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 20:29:45.087  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 20:29:45.088  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b342b9e removed from the list
08-26 20:29:45.088  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:45.088  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b4e67f removed from the list
08-26 20:29:45.088  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 20:29:45.089  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:45.090  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:45.091  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:45.094  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:29:45.094  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:45.095  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:29:45.095  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b4e67f not in the list
08-26 20:29:45.095  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:45.096  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:45.099  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:45.099  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:29:45.100  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:45.100  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b4e67f not in the list
08-26 20:29:45.100  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:45.101  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:45.101  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:45.101  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b342b9e not in the list
08-26 20:29:45.104  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 20:29:45.104  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8783b38 added. We now have 3 listener(s)
,08-26 20:29:45.110  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 20:29:45.110  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 20:29:45.111  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 20:29:45.111  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:45.111  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c7711 added. We now have 4 listener(s)
08-26 20:29:45.112  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:29:45.112  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:29:45.117  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:45.124  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:45.128  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:29:45.128  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:29:45.128  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-26 20:29:45.129  3799  3851 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-26 20:29:45.129  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-26 20:29:45.130  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-26 20:29:45.130  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-26 20:29:45.130  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-26 20:29:45.130  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:29:45.131  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 20:29:45.131  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 20:29:45.132  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 20:29:45.132  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 20:29:45.132  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-26 20:29:45.132  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:29:45.132  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 20:29:45.134  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:45.139  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 20:29:45.139  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 20:29:45.139  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:45.140  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 20:29:45.142  3799  4276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 20:29:45.151  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 20:29:45.152  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 20:29:45.152  3799  4276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-26 20:29:45.152  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 20:29:45.156  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-26 20:29:45.157  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 20:29:45.158  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-26 20:29:45.160  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-26 20:29:45.161  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-26 20:29:45.161  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-26 20:29:45.163  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:29:45.168  4184  4220 D BtGatt.GattService: registerClient() - UUID=f5b54c0c-31b4-458d-8406-6edaf7aec679
,08-26 20:29:45.169  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=f5b54c0c-31b4-458d-8406-6edaf7aec679, clientIf=5
,08-26 20:29:45.169  3799  3811 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-26 20:29:45.173  4184  4202 D BtGatt.AdvertiseManager: message : 0
,08-26 20:29:45.178  4184  4202 D BtGatt.AdvertiseManager: starting multi advertising
,08-26 20:29:45.203  4184  4200 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-26 20:29:45.224  4184  4200 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-26 20:29:45.226  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-26 20:29:45.227  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 20:29:45.232  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 20:29:45.235  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-26 20:29:45.236  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-26 20:29:45.236  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-26 20:29:45.236  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-26 20:29:45.236  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-26 20:29:45.237  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-26 20:29:45.241  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 20:29:45.247  3799  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-26 20:29:45.247  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-26 20:29:45.749  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-26 20:29:45.749  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 20:29:45.750  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 20:29:48.243  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:29:48.243  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-26 20:29:48.244  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 20:29:48.244  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 20:29:48.244  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 20:29:48.245  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-26 20:29:48.247  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-26 20:29:48.248  3799  4276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-26 20:29:48.248  3799  4276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 20:29:48.247  3799  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-26 20:29:48.248  3799  4276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 20:29:48.248  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 20:29:48.248  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 20:29:48.249  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 20:29:48.249  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 20:29:48.250  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 20:29:48.250  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 20:29:48.252  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:29:48.253  3799  3851 D BluetoothLeScanner: could not find callback wrapper
,08-26 20:29:48.254  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 20:29:48.254  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-26 20:29:48.258  4184  4202 D BtGatt.AdvertiseManager: message : 1
08-26 20:29:48.259  4184  4202 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-26 20:29:48.269  4184  4200 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-26 20:29:48.269  4184  4200 D BtGatt.GattService: Client app is not null!
,08-26 20:29:48.271  4184  4220 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 20:29:48.272  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 20:29:48.272  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-26 20:29:48.273  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-26 20:29:48.273  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-26 20:29:48.273  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-26 20:29:48.275  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:29:48.275  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 20:29:48.276  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 20:29:48.277  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:29:48.280  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:29:48.281  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 20:29:48.281  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 20:29:48.281  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:29:48.281  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:29:48.281  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:29:48.282  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:48.282  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:48.282  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 20:29:48.282  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 20:29:48.282  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8783b38 removed from the list
08-26 20:29:48.282  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:48.282  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c7711 removed from the list
08-26 20:29:48.282  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 20:29:48.282  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:48.283  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:48.284  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:48.286  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:29:48.286  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:29:48.287  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:48.287  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c7711 not in the list
08-26 20:29:48.287  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:48.287  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:48.290  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:29:48.290  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:29:48.290  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:48.290  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c7711 not in the list
,08-26 20:29:48.291  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:48.291  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:48.291  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:48.291  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8783b38 not in the list
,08-26 20:29:48.293  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 20:29:48.294  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@750be02 added. We now have 3 listener(s)
,08-26 20:29:48.300  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 20:29:48.300  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 20:29:48.301  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 20:29:48.301  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:48.301  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed1b313 added. We now have 4 listener(s)
,08-26 20:29:48.301  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 20:29:48.302  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:29:48.307  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:48.314  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:48.317  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 20:29:48.318  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:29:48.318  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 20:29:48.318  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 20:29:48.318  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 20:29:48.319  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:29:48.319  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 20:29:48.322  3799  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 20:29:48.322  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 20:29:48.323  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:48.328  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:48.328  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 20:29:48.330  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 20:29:48.330  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 20:29:48.336  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 20:29:48.337  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 20:29:48.337  3799  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 20:29:48.338  3799  3851 D BluetoothAdapter: STATE_ON
,08-26 20:29:48.343  4184  4211 D BtGatt.GattService: registerClient() - UUID=7e0f8216-a142-45f5-89dc-d250450f3ecb
,08-26 20:29:48.343  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=7e0f8216-a142-45f5-89dc-d250450f3ecb, clientIf=5
08-26 20:29:48.344  3799  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 20:29:48.345  4184  4220 D BtGatt.GattService: start scan with filters
,08-26 20:29:48.351  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 20:29:48.351  4184  4203 D BtGatt.ScanManager: handling starting scan
08-26 20:29:48.352  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 20:29:48.352  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 20:29:48.355  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 20:29:48.365  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 20:29:48.365  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 20:29:48.365  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 20:29:48.366  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 20:29:48.367  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:48.367  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 20:29:48.371  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 20:29:48.384  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 20:29:48.385  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:48.385  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
08-26 20:29:48.385  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 20:29:48.407  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 20:29:48.407  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:48.421  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 20:29:48.421  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:48.783  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 20:29:48.867  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-26 20:29:48.867  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 20:29:48.868  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 20:29:49.925  4184  4184 D BtGatt.ScanManager: awakened up at time 233272
,08-26 20:29:49.928  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 20:29:49.981  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-26 20:29:49.981  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:49.981  4184  4200 D BtGatt.GattService: current time is 233328998848
08-26 20:29:49.982  4184  4200 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -88, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -84, 62, -74, 107, 66, 64, 1, -128, -59, 21, 0, 0, 0, -84, 62, -74, 107, 66, 64, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 20:29:49.984  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-26 20:29:49.985  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-26 20:29:49.985  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-26 20:29:49.985  4184  4200 D BtGatt.GattService: ScanRecord : []
08-26 20:29:49.986  4184  4200 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-26 20:29:49.986  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-26 20:29:49.990  3799  3799 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-26 20:29:49.991  3799  3799 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-26 20:29:51.387  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 20:29:51.387  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 20:29:51.388  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 20:29:51.388  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:51.388  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-26 20:29:51.389  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 20:29:51.389  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 20:29:51.389  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 20:29:51.390  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 20:29:51.390  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 20:29:51.390  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 20:29:51.393  3799  3851 D BluetoothAdapter: STATE_ON
08-26 20:29:51.397  4184  4194 D BtGatt.GattService: stopScan() - queue size =1
,08-26 20:29:51.399  4184  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 20:29:51.400  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 20:29:51.400  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 20:29:51.400  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 20:29:51.401  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 20:29:51.401  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 20:29:51.407  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 20:29:51.407  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 20:29:51.407  3799  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 20:29:51.408  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 20:29:51.408  4184  4184 D BtGatt.ScanManager: awakened up at time 234755
,08-26 20:29:51.410  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 20:29:51.411  3799  3851 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-26 20:29:51.413  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 20:29:51.413  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:51.413  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 20:29:51.414  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 20:29:51.414  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:51.414  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 20:29:51.414  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 20:29:51.415  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@750be02 removed from the list
08-26 20:29:51.415  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:51.415  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed1b313 removed from the list
,08-26 20:29:51.415  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:51.416  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:51.417  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:51.417  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:51.418  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 20:29:51.419  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 20:29:51.420  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
08-26 20:29:51.421  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:29:51.421  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:51.422  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 20:29:51.422  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed1b313 not in the list
08-26 20:29:51.422  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:51.422  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:51.425  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 20:29:51.425  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:29:51.425  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:51.426  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed1b313 not in the list
08-26 20:29:51.426  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 20:29:51.426  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:51.426  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:51.427  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@750be02 not in the list
,08-26 20:29:51.427  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 20:29:51.427  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:51.428  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 20:29:51.429  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 20:29:51.430  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d45bf05 added. We now have 3 listener(s)
,08-26 20:29:51.436  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 20:29:51.436  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 20:29:51.436  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 20:29:51.437  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 20:29:51.437  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c40b5a added. We now have 4 listener(s)
08-26 20:29:51.437  3799  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 20:29:51.437  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 20:29:51.440  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 20:29:51.440  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-26 20:29:51.440  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 20:29:51.441  4184  4200 D BtGatt.GattService: current time is 234788062715
08-26 20:29:51.441  4184  4200 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -84, 62, -74, 107, 66, 64, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
,08-26 20:29:51.441  4184  4200 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-26 20:29:51.441  4184  4200 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 20:29:51.444  3799  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 20:29:51.446  3799  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 20:29:51.446  3799  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 20:29:51.447  3799  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 20:29:51.447  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:29:51.447  3799  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 20:29:51.447  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:51.447  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:51.447  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 20:29:51.447  3799  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 20:29:51.447  3799  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d45bf05 removed from the list
08-26 20:29:51.448  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:51.448  3799  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c40b5a removed from the list
,08-26 20:29:51.449  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 20:29:51.451  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 20:29:51.451  3799  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-26 20:29:51.451  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:51.452  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:51.452  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 20:29:51.453  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 20:29:51.453  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:51.453  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:51.453  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c40b5a not in the list
08-26 20:29:51.453  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 20:29:51.453  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:51.454  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 20:29:51.454  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 20:29:51.454  3799  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 20:29:51.454  3799  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c40b5a not in the list
,08-26 20:29:51.454  3799  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 20:29:51.455  3799  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 20:29:51.455  3799  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 20:29:51.455  3799  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d45bf05 not in the list
08-26 20:29:51.456  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 20:29:51.456  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 20:29:51.456  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 20:29:51.456  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 20:29:51.456  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 20:29:51.456  3799  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 20:29:51.915  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 20:29:53.471  3799  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,08-26 20:29:55.469  3799  3851 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 459
,08-26 20:29:55.469  3799  3851 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 459, name: My test thread name)
,08-26 20:29:55.475  3799  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,08-26 20:29:55.476  3799  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
,08-26 20:29:55.476  3799  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-26 20:29:55.481  3799  3851 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-26 20:29:55.489  3799  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,08-26 20:29:55.490  3799  4280 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 464, thread name: My test thread name): Test exception.
08-26 20:29:55.490  3799  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-26 20:29:55.498  3799  3851 I jxcore-log: Total number of executed tests:  82
08-26 20:29:55.498  3799  3851 I jxcore-log: 
,08-26 20:29:55.500  3799  3851 I jxcore-log: Number of passed tests:  82
08-26 20:29:55.500  3799  3851 I jxcore-log: 
,08-26 20:29:55.500  3799  3851 I jxcore-log: Number of failed tests:  0
08-26 20:29:55.500  3799  3851 I jxcore-log: 
,08-26 20:29:55.501  3799  3851 I jxcore-log: Number of ignored tests:  0
08-26 20:29:55.501  3799  3851 I jxcore-log: 
,08-26 20:29:55.501  3799  3851 I jxcore-log: Total duration:  101516
08-26 20:29:55.501  3799  3851 I jxcore-log: 
,08-26 20:29:55.511  3799  3851 I jxcore-log: Unit Test app is loaded
08-26 20:29:55.511  3799  3851 I jxcore-log: 
,08-26 20:29:55.534  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.534  3799  3851 I jxcore-log: 
,08-26 20:29:55.541  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.541  3799  3851 I jxcore-log: 
,08-26 20:29:55.542  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.542  3799  3851 I jxcore-log: 
,08-26 20:29:55.542  3799  3799 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 20:29:55.543  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.543  3799  3851 I jxcore-log: 
08-26 20:29:55.545  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-26 20:29:55.545  3799  3851 I jxcore-log: 
08-26 20:29:55.546  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 20:29:55.546  3799  3851 I jxcore-log: 
,08-26 20:29:55.549  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.549  3799  3851 I jxcore-log: 
,08-26 20:29:55.551  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.551  3799  3851 I jxcore-log: 
,08-26 20:29:55.551  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-26 20:29:55.551  3799  3851 I jxcore-log: 
,08-26 20:29:55.553  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 20:29:55.553  3799  3851 I jxcore-log: 
08-26 20:29:55.553  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 20:29:55.553  3799  3851 I jxcore-log: 
,08-26 20:29:55.554  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.554  3799  3851 I jxcore-log: 
08-26 20:29:55.555  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.555  3799  3851 I jxcore-log: 
,08-26 20:29:55.556  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.556  3799  3851 I jxcore-log: 
08-26 20:29:55.557  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.557  3799  3851 I jxcore-log: 
,08-26 20:29:55.558  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.558  3799  3851 I jxcore-log: 
08-26 20:29:55.559  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.559  3799  3851 I jxcore-log: 
,08-26 20:29:55.559  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.559  3799  3851 I jxcore-log: 
,08-26 20:29:55.561  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.561  3799  3851 I jxcore-log: 
08-26 20:29:55.562  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.562  3799  3851 I jxcore-log: 
,08-26 20:29:55.563  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.563  3799  3851 I jxcore-log: 
,08-26 20:29:55.564  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.564  3799  3851 I jxcore-log: 
08-26 20:29:55.564  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.564  3799  3851 I jxcore-log: 
,08-26 20:29:55.565  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.565  3799  3851 I jxcore-log: 
08-26 20:29:55.566  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.566  3799  3851 I jxcore-log: 
,08-26 20:29:55.567  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.567  3799  3851 I jxcore-log: 
08-26 20:29:55.568  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.568  3799  3851 I jxcore-log: 
,08-26 20:29:55.568  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.568  3799  3851 I jxcore-log: 
08-26 20:29:55.569  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.569  3799  3851 I jxcore-log: 
,08-26 20:29:55.570  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.570  3799  3851 I jxcore-log: 
08-26 20:29:55.571  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.571  3799  3851 I jxcore-log: 
,08-26 20:29:55.572  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.572  3799  3851 I jxcore-log: 
08-26 20:29:55.572  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.572  3799  3851 I jxcore-log: 
,08-26 20:29:55.573  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.573  3799  3851 I jxcore-log: 
08-26 20:29:55.574  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.574  3799  3851 I jxcore-log: 
,08-26 20:29:55.575  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.575  3799  3851 I jxcore-log: 
08-26 20:29:55.575  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.575  3799  3851 I jxcore-log: 
,08-26 20:29:55.577  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.577  3799  3851 I jxcore-log: 
,08-26 20:29:55.578  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.578  3799  3851 I jxcore-log: 
08-26 20:29:55.578  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.578  3799  3851 I jxcore-log: 
,08-26 20:29:55.579  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 20:29:55.579  3799  3851 I jxcore-log: 
08-26 20:29:55.579  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.579  3799  3851 I jxcore-log: 
,08-26 20:29:55.580  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 20:29:55.580  3799  3851 I jxcore-log: 
08-26 20:29:55.580  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.580  3799  3851 I jxcore-log: 
,08-26 20:29:55.581  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.581  3799  3851 I jxcore-log: 
08-26 20:29:55.581  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.581  3799  3851 I jxcore-log: 
,08-26 20:29:55.582  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.582  3799  3851 I jxcore-log: 
08-26 20:29:55.582  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.582  3799  3851 I jxcore-log: 
,08-26 20:29:55.583  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 20:29:55.583  3799  3851 I jxcore-log: 
08-26 20:29:55.583  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.583  3799  3851 I jxcore-log: 
08-26 20:29:55.584  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-26 20:29:55.584  3799  3851 I jxcore-log: 
08-26 20:29:55.584  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.584  3799  3851 I jxcore-log: 
08-26 20:29:55.585  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 20:29:55.585  3799  3851 I jxcore-log: 
08-26 20:29:55.585  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-26 20:29:55.585  3799  3851 I jxcore-log: 
08-26 20:29:55.586  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-26 20:29:55.586  3799  3851 I jxcore-log: 
08-26 20:29:55.587  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 20:29:55.587  3799  3851 I jxcore-log: 
,08-26 20:29:55.587  3799  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 20:29:55.587  3799  3851 I jxcore-log: 
,08-26 20:29:55.590  3799  3851 I jxcore-log: My device name is: motorola-Nexus 6
08-26 20:29:55.590  3799  3851 I jxcore-log: 
,08-26 20:29:55.612  3799  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-26 20:29:56.000  3799  3851 W jxcore-log: !!! js_ReportOverRecursed called !!!
,08-26 20:29:56.067  4281  3851 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,08-26 20:29:56.068  4281  3851 W google-breakpad: O A arm 04 armv7l 3.10.40-geb6cc9d #1 SMP PREEMPT Wed Apr 20 00:05:01 UTC 2016
,08-26 20:29:56.068  4281  3851 W google-breakpad: S 0 92C0BB28 92C0B000 00008000
,08-26 20:29:56.140  4281  3851 W google-breakpad: S 92C0B000 14B0C092C0CECEB69CE13D9484E13D9474B0C0928850F4910100000010C0F29100F4E99FE4E78D94C0FDCC978E89EA98E0F4E99FE4E78D9410C0F291E0FDCC9740B0F29178B0C092ACB0C09250478C59000000000000000058DB8E945CB1C092E0F4E99F24B1C09268B1C092E4E78D940CB1C09230A544949CE13D940000000068B1C0920000000000000000E4E78D94E0F4E99F58DB8E9401000000C0CECEB69CE13D9484E13D94FCB0C0920000000060E7079188FFFFFF0000000082FFFFFFE4E78D946081F2910000000040A6F29158AFC0924000000045C21E8ECEC21E8ECEC21E8EF2C21E8ECEC21E8E01000000000000000C00000004C31E8E24C31E8E0100000001000000010000000000040080BA8D941400000005000000FFFFFFFFC8B4C092000000000000000000000000000004000000000050AEC092010000008850F4915CB1C09200000000000000002CAEC092F44D44940000000058B1C092000000000000000000000000E0F4E99F080000000000000040A6F2919CAEC092
,08-26 20:29:56.140  4281  3851 W google-breakpad: S 92C0B180 000000005CB1C09250AEC0923003A4908850F4915CB1C0920000000024B1C0924CAEC092584F44944CAEC092E0F4E99FE0F4E99F5CB1C0929CAEC09294AEC0927CAEC092E85B50948850F491D8E78D94C8B5C092E6FFFFFFECF4E99F9CAEC0920000000000000000C0CECEB6E0F4E99F0CAFC092508F509440A6F2918CAEC0929CAEC0929CAEC09230B2C0929CAEC092E4AEC09284D93494002201924C1C79940000C09200BE1E8E000000000400000045C21E8ECEC21E8ECEC21E8EF2C21E8ECEC21E8E01000000000000000C00000004C31E8E24C31E8E0100000001000000010000000000040080BA8D941400000005000000FFFFFFFFC8B4C092000000000000000000000000000004000000000050AEC092010000008850F4915CB1C09200000000000000002CAEC092F44D44940000000058B1C092000000000000000000000000E0F4E99F080000000000000040A6F2919CAEC092000000005CB1C09250AEC0923003A4908850F4915CB1C0920000000024B1C0924CAEC092584F4494
,08-26 20:29:56.141  4281  3851 W google-breakpad: S 92C0B300 4CAEC092E0F4E99FE0F4E99F5CB1C0929CAEC09294AEC0927CAEC092E85B50948850F491D8E78D94C8B5C092E6FFFFFFECF4E99F9CAEC0920000000000000000C0CECEB6E0F4E99F0CAFC092508F509440A6F2918CAEC0929CAEC0929CAEC09230B2C0929CAEC092E4AEC09284D93494002201924C1C79940000C09200BE1E8E00000000030200000100000001000000603FF7910082FA919D13EA9FADDBBA0054B6C09250478C59603FF79190D4A29088FFFFFF81FFFFFFF0D4A29003020000603FF7910100000054B6C09208E6DF9088FFFFFFDCB3C092F0D4A29003020000C8B4C0920100000000000000B4DBDF900CB4C092FCB3C0920825989400000000000000007CDBDF90C004000002000000C0D0F29188FFFFFFA00FF39188FFFFFFF0D4A29088FFFFFF90D4A29088FFFFFFF02A9894C8F10192F0D4A290C0D4A2900000000087FFFFFFA00FF39190D4A290C0D4A29060E70791E0BBD58D85020000C036F491020000000000000082FFFFFFA00FF39188FFFFFF90D4A29088FFFFFF
,08-26 20:29:56.141  4281  3851 W google-breakpad: S 92C0B480 B8B4C09290D4A29030D4A29060D4A290FCDED58D850200000037F4910000000030D4A29088FFFFFF1089A1908A000000070000002089A190E0F4E99F40B0F29110EEA0900037F4912008A89903020000603FF7910100000040B0F29188FFFFFF10EEA09085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000004003EA9FE0F4E99FC0CECEB690B6C0920100000081FFFFFFE8B5C0924CB5C092485C30940080109D0000000054B6C09260C43094603FF7910000000000000000B8B5C0926CB5C0923807A89958DB8E94E0F4E99F00FDCC97D4C6C09200000000000000000000000001000000BCBDC092E0F4E99F0001000000000000B0DDD58D00000000603FF79148BAC092020000000100000000000000000000000E00000084FFFFFF000000000000000020BAC092F6FFFFFFECF4E99F01000000E0F4E99FE8B5C0920000000008000000000000000000000000000000000000000000000000000000
08-26 20:29:56.141  4281  3851 W google-breakpad: S 92C0B600 0000000000000000000000000100000090B6C092E0F4E99F783B98940082FA9100000000909F6B9054B6C09250478C5900000000E0F4E99F90B6C09258B6C092603FF7910082FA9150478C59000000007CB6C0920C644E94000000000000000000000000C0CECEB601000000E0F4E99F50BAC09288B6C09204BAC09224664E9452444790FB45479050BAC09201000000E80C8E94010000000082FA9188B6C09200000000004647900200000002000000010000000000000080BA8D945C0000000600000000000000C0C5C092000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-26 20:29:56.141  4281  3851 W google-breakpad: S 92C0B780 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C479000000000000000000100000002000000C0E607910083FA9165D6269D000000000000000050478C5900000000C0CECEB600000000E0F4E99FC8BA409420B8C0929CBBC092A8664E94000000000000000040BCC09200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-26 20:29:56.142  4281  3851 W google-breakpad: S 92C0B900 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C59C0CECEB640BAC092E0F4E99FF0BAC09250BAC092909F6B90ACBAC092E46A4E9400000000000000000000000040B0F29150BAC0920100000030C7C092F6FFFFFFECF4E99F00000000E0F4E99F40BAC0920300000008000000603FF79188FFFFFF40B0F29188FFFFFF10EEA09085FFFFFFC8EF2B9D889F6B900050F89670BBC0920C53CFB6C0EF2B9D9485CEB6C8EF2B9D889F6B905BB2CCB6
08-26 20:29:56.142  4281  3851 W google-breakpad: S 92C0BA80 0400000094BAC09201000000E0F4E99FACBAC09294013F94BCBDC092D4C6C092E0F4E99F00000000DCBAC0925C553E94889F6B90F8BAC09240B0F29169090000D0291BAB1070919604BBC09210441F940000000070BBC0922C00000020BBC092F8BAC0920700000058DB8E9474177994E0F4E99F0000000085FFFFFF00C0109D5CBBC09220491F940000000020BBC092E0F4E99F000000006C17799470BBC092741779945CBBC09207000000000000000000000090B8E0E640EEA09085FFFFFFE01D0192E0F4E99FE0BBC0928CBBC09264BBC09285FFFFFF84BBC092202E3E9400000000E01D01922200000050BCC0928CBBC092E0BBC0927417799440EEA090ACBBC09258D75F947C42BB91000000000000000082FFFFFFE0BBC09250BCC092D0BBC092E0F4E99F14BCC0921C6B5894E4D8789450DC789458DB8E94220000007C42BB910443B99000000000E4BBC09240EEA09085FFFFFFE0F4E99F0000000040EEA09085FFFFFF98BCC09268BDC09218C18F9460BCC0920000000001000000
08-26 20:29:56.142  4281  3851 W google-breakpad: S 92C0BC00 50BCC09240BCC09222000000E0F4E99FA4BDC09228945B94789F6B90B808848F0000000000100000B808848F78BCC09298BCC09298BCC092B808848FE401D8B40000000082FFFFFF00000000000100000000000082FFFFFFE0F4E99F0000000000049C91E0F4E99F01000000C8BDC092D8BDC09201FFFFFF789F6B90070000000700000001FFFFFFB0ECA09000FFFFFFE0F4E99FFFFFFFFFE801D8B4060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000809F6B9022000000B8ECA09007000000000000000100000018000092505C019081FFFFFF04BDC092E0AA489407000000B0ECA090E0F4E99F000000001000009210BDC09244BDC092E8EC48940000000000000000000000000CB2D58D78BDC092010000000000000000D4A290E01B0192B0ECA09000000000FFFFFFFF505C019081FFFFFFE0BDC092B0B2D58D38BEC09254BDC092A0BDC092000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFFB0ECA09085FFFFFF1000009285FFFFFF
,08-26 20:29:56.142  4281  3851 W google-breakpad: S 92C0BD80 000000006049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C019081FFFFFFE0BDC09238CFA89900000000B4BDC0928CD9A899000000000000000088FCD78D42020000010000006049F69188FFFFFF00EAF29188FFFFFFB0ECA09085FFFFFF3CBEC092C05C019088FCD78D01050000B0ECA09085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF000000002801E28C40020000000000005000000030BDF291F0D9019285FFFFFF6CBEC09284BEC0920000000060BEC0928CD9A899820100008086F691010000000000000082FFFFFFB0ECA09085FFFFFF0CBFC092C05687902CACD68D010A0000B0ECA09085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF2910000000083FFFFFF
08-26 20:29:56.142  4281  3851 W google-breakpad: S 92C0BF00 A88BE08C020000000000000038BFC0928CD9A89902020000C04CF69102000000A0C6F59188FFFFFFB0ECA09085FFFFFF40E7079188FFFFFFACBFC0928097708E84CCE08C81060000F0D9019285FFFFFFB0ECA09085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000090BFC0920000000083FFFFFF6800000080B2A28FB8ECA090010000003000000080B2A28F00000000D0BFC0928CD9A89982010000E0E52B91010000000000000082FFFFFFB0ECA09085FFFFFF54C0C0927090708EBCC4E08C81070000B0ECA09085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF70C0C09268C0C09260C0C092D4C0C0927800000080B2A28F0000000016D6379758DB8E94E0F4E99F0000000078C0C0928CD9A8998201000020E62B91010000000000000082FFFFFFB0ECA09085FFFFFFE4C0C09298A65E8E
08-26 20:29:56.143  4281  3851 W google-breakpad: S 92C0C080 9CBAE08C01060000B0ECA09085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F0C0C09208C1C092040000006000000080B2A28FE0865F8D81FFFFFF74C1C092F88FA8990000000008C1C0928CD9A8998201000040E62B91010000000000000082FFFFFFB0ECA09085FFFFFF74C1C09298A05E8EA8B1E08C01060000B0ECA09085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A0D3A290000000007069448D60000000D0D3A29004000000A88BE08C84C1C09278042B940400000098C1C0928CD9A8998201000060E62B91010000000000000082FFFFFFA0D3A29088FFFFFF14C2C09290855F8DB4A8E08C01070000A0D3A29088FFFFFF0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFFB0ECA09085FFFFFF0000000008C2C09204C2C09288FFFFFF7000000070D3A290
,08-26 20:29:56.143  4281  3851 W google-breakpad: S 92C0C200 A071A69084E13D9400000000000000000400000038C2C0928CD9A89982010000E0E62B9101000000C0915A9188FFFFFFD0AFA79088FFFFFF94C2C092607B5F8D20A2E08C01050000D0AFA79088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFFA071A69001000000C4C2C092DCC2C09250000000E0D5028E0200000070909B91B4C2C092C8032B9400000000C8C2C092DCBD32928202000000263F91030000000000000082FFFFFFD0AFA79088FFFFFF0000000081FFFFFFA071A69088FFFFFF64C3C092D0F7828FE832D38D01090000A071A69088FFFFFF0000000081FFFFFFD0AFA79088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF9051A38F88FFFFFF0000000082FFFFFF0900000081FFFFFFA071A69088FFFFFFF071A6900000000094C3C092C0D6F2919000000020C0F291A88BE08C0200000070725F8D81FFFFFF0000000088C3C0928CD9A89982010000B002F39101000000A071A69088FFFFFF
,08-26 20:29:56.143  4281  3851 W google-breakpad: S 92C0C380 00263F9188FFFFFF0CC4C09228775F8D989BE08C8107000000263F9188FFFFFFA071A69088FFFFFFB002F39188FFFFFFF071A69088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF0000000082FFFFFFF071A69088FFFFFF0000000082FFFFFF30C4C09238CFA89900000000F4C3C09278000000E0D5028E00000000E491E08C42030000030000000000000038C4C0928CD9A8990202000020263F9102000000505B619188FFFFFFE00C2E9188FFFFFFA071A69088FFFFFFA4C4C092787CE29FB096E08C01060000A071A69088FFFFFFE00C2E9188FFFFFF505B619188FFFFFF20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFF68C4C092A035F491E0EDA0904011019260000000E0D5028E85FFFFFF2C44E28C85FFFFFFA4C4C092000000000037F491384FE28C800B000060263F91020000000037F49188FFFFFFE00C2E9188FFFFFFA0DBA39088FFFFFFF0EDA09085FFFFFF5071A69088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF00D1A290
08-26 20:29:56.143  4281  3851 W google-breakpad: S 92C0C500 A0DBA390A035F4911089A1908A000000B0D2A290F0EDA0905071A690A0DBA390A035F491E0EDA090801800927089A19009000000E0E60791D0B0F291D0B0F291A0DBA39088FFFFFF0900000040110192090000000037F491E00C2E91A0AFA790E0E6079188FFFFFF000000007CDBDF9020DDDF90000400008036F491010000000037F49188FFFFFFE00C2E9188FFFFFF0000000082FFFFFFF02A9894E00C2E9170AFA79040AFA7900000000087FFFFFFA00FF39110AFA79040AFA790C0E60791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFF10AFA79088FFFFFF20C6C09210AFA790B0AEA790E0AEA790FCDED58D800200000037F49100000000B0AEA79088FFFFFFB0B4A2908A00000007000000C0B4A290E0F4E99F40B0F2910089A1900037F4912008A89903020000603FF7910100000040B0F29188FFFFFF0089A19085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.144  4281  3851 W google-breakpad: S 92C0C680 000000000000000000000000000000000000000000000000E0F4E99FC0CECEB6F8C7C0920100000081FFFFFF50C7C092BCC7C09214C43094603FF791000000000000000020C7C092D4C6C0923807A89958DB8E94E0F4E99F00FDCC973CD8C0920000000000000000000000000100000024CFC092E0F4E99F0001000000000000B0DDD58D00000000603FF791B0CBC092020000000100000000000000000000000100000081FFFFFF000000000000000088CBC092F6FFFFFFECF4E99F01000000E0F4E99F50C7C092000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000F8C7C092E0F4E99F783B98940082FA9100000000709F6B90BCC7C09250478C5900000000E0F4E99FF8C7C092C0C7C092603FF7910082FA9100000000709F6B90E4C7C0922C654E94000000000000000000000000C0CECEB601000000E0F4E99FB8CBC092F0C7C0926CCBC09224664E9452444790FB454790B8CBC09201000000E80C8E9401000000
08-26 20:29:56.144  4281  3851 W google-breakpad: S 92C0C800 0082FA91F0C7C09200000000004647900200000002000000010000000000000080BA8D945C000000060000000000000028D7C09200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C47900000000000000000010000000200000020E607910083FA9165D6269D000000000000000050478C5900000000C0CECEB600000000E0F4E99FC8BA409488C9C09204CDC092A8664E94
,08-26 20:29:56.144  4281  3851 W google-breakpad: S 92C0C980 0000000000000000A8CDC092000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.144  4281  3851 W google-breakpad: S 92C0CB00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C59C0CECEB6A8CBC092E0F4E99F58CCC092B8CBC092709F6B9014CCC092E46A4E9400000000000000000000000040B0F291B8CBC0920100000098D8C092F6FFFFFFECF4E99F00000000E0F4E99FA8CBC0920300000008000000603FF79188FFFFFF40B0F29188FFFFFF0089A19085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C5904000000E0F4E99F68CCC09258CCC09260CCC09254CCC09282FFFFFF689F6B9044CCC09238553E94689F6B9060CCC09240B0F29188FFFFFFC8CCC092D8CCC092B8CDC0920100000070CCC09200000000A4CCC09220EB5F9460CCC092000000001800000040B0F291603FF79188FFFFFF0000000082FFFFFF01000000689F6B900000000082FFFFFFE0F4E99F00000000
08-26 20:29:56.144  4281  3851 W google-breakpad: S 92C0CC80 6C177994D8CCC092C8CCC0920050FB969852FB96E0F4E99FB8CDC0926C17799414CDC092B8FA5694D8CCC0922CCDC092070000004F0000001C2149902C42BB91000000002042BB9140B0F29188FFFFFFE0F4E99F000000000089A19085FFFFFFE0F4E99F0000000028CDC09218707A944D42BB9148CDC092B8CDC09238CDC092E0F4E99F2CCDC092220000000050FB967CCDC092EC6A5894E4D8789450DC789458DB8E94220000002C42BB91D442B990000000004CCDC0922200000000000000D0CEC0920000000064CDC0921435169400CEC092D0CEC09218C18F94C8CDC0920000000001000000B8CDC092A8CDC09222000000E0F4E99F0CCFC09228945B94589F6B9000000000E0F4E99F98CDC09202000000E0CDC092900C2E9100CEC09200AAA79088FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0F4E99F0100000030CFC09240CFC09201000000589F6B90070000000700000001000000A087A19000000000E0F4E99F00000000
08-26 20:29:56.145  4281  3851 W google-breakpad: S 92C0CE00 00000000060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000609F6B9022000000A887A19007000000000000000100000018000092505C019081FFFFFF6CCEC092E0AA489407000000A087A190E0F4E99F000000001000009278CEC092ACCEC092E8EC48940000000000000000000000000CB2D58DE0CEC092010000000000000080AEA790E01B0192A087A19000000000FFFFFFFF505C019081FFFFFF48CFC092B0B2D58DA0CFC092BCCEC09208CFC092000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFFA087A19085FFFFFF1000009285FFFFFF000000006049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C019081FFFFFF48CFC09238CFA899000000001CCFC0928CD9A899000000000000000088FCD78D42020000010000006049F69188FFFFFF00EAF29188FFFFFFA087A19085FFFFFFA4CFC092C05C019088FCD78D01050000A087A19085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF000000002801E28C
08-26 20:29:56.145  4281  3851 W google-breakpad: S 92C0CF80 40020000000000005000000030BDF291F0D9019285FFFFFFD4CFC092ECCFC09200000000C8CFC0928CD9A899820100008086F691010000000000000082FFFFFFA087A19085FFFFFF74D0C092C05687902CACD68D010A0000A087A19085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF2910000000083FFFFFFA88BE08C0200000000000000A0D0C0928CD9A89902020000C04CF69102000000A0C6F59188FFFFFFA087A19085FFFFFFA0E6079188FFFFFF14D1C0928097708E84CCE08C81060000F0D9019285FFFFFFA087A19085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000,082FFFFFFC1030000F8D0C0920000000083FFFFFF6800000080B2A28F
08-26 20:29:56.145  4281  3851 W google-breakpad: S 92C0D100 A887A190010000003000000080B2A28F0000000038D1C0928CD9A89982010000E0E52B91010000000000000082FFFFFFA087A19085FFFFFFBCD1C0927090708EBCC4E08C81070000A087A19085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFD8D1C092D0D1C092C8D1C0923CD2C0927800000080B2A28F0000000016D6379758DB8E94E0F4E99F00000000E0D1C0928CD9A8998201000020E62B91010000000000000082FFFFFFA087A19085FFFFFF4CD2C09298A65E8E9CBAE08C01060000A087A19085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000058D2C09270D2C092040000006000000080B2A28FE0865F8D81FFFFFFDCD2C092F88FA8990000000070D2C0928CD9A8998201000040E62B91010000000000000082FFFFFFA087A19085FFFFFFDCD2C09298A05E8EA8B1E08C01060000
08-26 20:29:56.145  4281  3851 W google-breakpad: S 92C0D280 A087A19085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000020AEA790000000007069448D6000000050AEA79004000000A88BE08CECD2C09278042B940400000000D3C0928CD9A8998201000060E62B91010000000000000082FFFFFF20AEA79088FFFFFF7CD3C09290855F8DB4A8E08C0107000020AEA79088FFFFFF0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFFA087A19085FFFFFF0000000070D3C0926CD3C09288FFFFFF70000000F0ADA79000DBA39084E13D94000000000000000004000000A0D3C0928CD9A89982010000E0E62B9101000000C0915A9188FFFFFF60AAA79088FFFFFFFCD3C092607B5F8D20A2E08C0105000060AAA79088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFF00DBA390010000002CD4C09244D4C09250000000E0D5028E0200000070909B911CD4C092C8032B940000000030D4C092
08-26 20:29:56.146  4281  3851 W google-breakpad: S 92C0D400 DCBD32928202000000263F91030000000000000082FFFFFF60AAA79088FFFFFF0000000081FFFFFF00DBA39088FFFFFFCCD4C092D0F7828FE832D38D0109000000DBA39088FFFFFF0000000081FFFFFF60AAA79088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF2051A38F88FFFFFF0000000082FFFFFF0900000081FFFFFF00DBA39088FFFFFF50DBA39000000000FCD4C092C0D6F2919000000020C0F291A88BE08C0200000070725F8D81FFFFFF00000000F0D4C0928CD9A89982010000B002F3910100000000DBA39088FFFFFF00263F9188FFFFFF74D5C09228775F8D989BE08C8107000000263F9188FFFFFF00DBA39088FFFFFFB002F39188FFFFFF50DBA39088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF0000000082FFFFFF50DBA39088FFFFFF0000000082FFFFFF98D5C09238CFA899000000005CD5C09278000000E0D5028E00000000E491E08C420300000300000000000000A0D5C0928CD9A89902020000
08-26 20:29:56.146  4281  3851 W google-breakpad: S 92C0D580 20263F9102000000505B619188FFFFFF900C2E9188FFFFFF00DBA39088FFFFFF0CD6C092787CE29FB096E08C0106000000DBA39088FFFFFF900C2E9188FFFFFF505B619188FFFFFF20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFD0D5C092A035F491D088A1904011019260000000E0D5028E85FFFFFF2C44E28C85FFFFFF0CD6C092000000000037F491384FE28C800B000060263F91020000000037F49188FFFFFF900C2E9188FFFFFF10D5A39088FFFFFFE088A19085FFFFFFB0DAA39088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF80ABA79010D5A390A035F491B0B4A2908A00000030ADA790E088A190B0DAA39010D5A390A035F491D088A1908018009210B5A2900900000040E60791D0B0F291D0B0F29110D5A39088FFFFFF0900000040110192090000000037F491900C2E9130AAA79040E6079188FFFFFF000000007CDBDF9020DDDF90000400008036F491010000000037F49188FFFFFF900C2E9188FFFFFF0000000082FFFFFF
08-26 20:29:56.146  4281  3851 W google-breakpad: S 92C0D700 F02A9894900C2E9100AAA790D0A9A7900000000087FFFFFFA00FF391A0A9A790D0A9A79020E60791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFFA0A9A79088FFFFFF88D7C092A0A9A79040A9A79070A9A790FCDED58D800200000037F4910000000040A9A79088FFFFFF0091A9908A000000070000001091A990E0F4E99F40B0F291A0B4A2900037F4912008A89903020000603FF7910100000040B0F29188FFFFFFA0B4A29085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0F4E99FC0CECEB660D9C0920100000081FFFFFFB8D8C09224D9C09214C43094603FF791000000000000000088D8C0923CD8C0923807A89958DB8E94E0F4E99F00FDCC97A4E9,C092000000000000000000000000010000008CE0C092E0F4E99F0001000000000000B0DDD58D00000000603FF79118DDC0920200000001000000
08-26 20:29:56.146  4281  3851 W google-breakpad: S 92C0D880 00000000000000000100000081FFFFFF0000000000000000F0DCC092F6FFFFFFECF4E99F01000000E0F4E99FB8D8C09200000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000060D9C092E0F4E99F783B98940082FA9100000000D09E6B9024D9C09250478C5900000000E0F4E99F60D9C09228D9C092603FF7910082FA9100000000D09E6B904CD9C0922C654E94000000000000000000000000C0CECEB601000000E0F4E99F20DDC09258D9C092D4DCC09224664E9452444790FB45479020DDC09201000000E80C8E94010000000082FA9158D9C09200000000004647900200000002000000010000000000000080BA8D945C000000060000000000000090E8C09200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.146  4281  3851 W google-breakpad: S 92C0DA00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C47900000000000000000010000000200000080E507910083FA9165D6269D000000000000000050478C5900000000C0CECEB600000000E0F4E99FC8BA4094F0DAC0926CDEC092A8664E94000000000000000010DFC0920000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.147  4281  3851 W google-breakpad: S 92C0DB80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C59C0CECEB610DDC092E0F4E99FC0DDC09220DDC092D09E6B907CDDC092E46A4E9400000000000000000000000040B0F29120DDC0920100000000EAC092F6FFFFFFECF4E99F00000000
08-26 20:29:56.147  4281  3851 W google-breakpad: S 92C0DD00 E0F4E99F10DDC0920300000008000000603FF79188FFFFFF40B0F29188FFFFFFA0B4A29085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C5900000000E0F4E99FD0DDC092C0DDC092C8DDC092BCDDC09282FFFFFFC89E6B90ACDDC09238553E94C89E6B90C8DDC09240B0F29188FFFFFF30DEC09240DEC09220DFC09201000000D8DDC092000000000CDEC09220EB5F94C8DDC092000000001800000040B0F291603FF79188FFFFFF0000000082FFFFFF01000000C89E6B900000000082FFFFFFE0F4E99F000000006C17799440DEC09230DEC0920050FB969852FB96E0F4E99F20DFC0926C1779947CDEC092B8FA569440DEC09294DEC092070000004F0000001C214990DC41BB9100000000D041BB9140B0F29188FFFFFFE0F4E99F00000000A0B4A29085FFFFFFE0F4E99F0000000090DEC09218707A94FD41BB91B0DEC09220DFC092A0DEC092E0F4E99F94DEC092220000000050FB96E4DEC092EC6A5894
,08-26 20:29:56.147  4281  3851 W google-breakpad: S 92C0DE80 E4D8789450DC789458DB8E9422000000DC41BB91A442B99000000000B4DEC092220000000000000038E0C09200000000CCDEC0921435169468DFC09238E0C09218C18F9430DFC092000000000100000020DFC09210DFC09222000000E0F4E99F74E0C09228945B94B89E6B9000000000E0F4E99F00DFC0920200000048DFC092400C2E9168DFC09290A4A79088FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0F4E99F0100000098E0C092A8E0C09201000000B89E6B9007000000070000000100000040B3A29000000000E0F4E99F0000000000000000060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000C09E6B902200000048B3A29007000000000000000100000018000092505C019081FFFFFFD4DFC092E0AA48940700000040B3A290E0F4E99F0000000010000092E0DFC09214E0C092E8EC48940000000000000000000000000CB2D58D48E0C092010000000000000010A9A790E01B019240B3A290
08-26 20:29:56.147  4281  3851 W google-breakpad: S 92C0E000 00000000FFFFFFFF505C019081FFFFFFB0E0C092B0B2D58D08E1C09224E0C09270E0C092000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFF40B3A29085FFFFFF1000009285FFFFFF000000006049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C019081FFFFFFB0E0C09238CFA8990000000084E0C0928CD9A899000000000000000088FCD78D42020000010000006049F69188FFFFFF00EAF29188FFFFFF40B3A29085FFFFFF0CE1C092C05C019088FCD78D0105000040B3A29085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF000000002801E28C40020000000000005000000030BDF291F0D9019285FFFFFF3CE1C09254E1C0920000000030E1C0928CD9A899820100008086F691010000000000000082FFFFFF40B3A29085FFFFFFDCE1C092C05687902CACD68D010A000040B3A29085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 20:29:56.148  4281  3851 W google-breakpad: S 92C0E180 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF2910000000083FFFFFFA88BE08C020000000000000008E2C0928CD9A89902020000C04CF69102000000A0C6F59188FFFFFF40B3A29085FFFFFF00E6079188FFFFFF7CE2C0928097708E84CCE08C81060000F0D9019285FFFFFF40B3A29085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000060E2C0920000000083FFFFFF6800000080B2A28F48B3A290010000003000000080B2A28F00000000A0E2C0928CD9A89982010000E0E52B91010000000000000082FFFFFF40B3A29085FFFFFF24E3C0927090708EBCC4E08C8107000040B3A29085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF40E3C09238E3C092
,08-26 20:29:56.148  4281  3851 W google-breakpad: S 92C0E300 30E3C092A4E3C0927800000080B2A28F0000000016D6379758DB8E94E0F4E99F0000000048E3C0928CD9A8998201000020E62B91010000000000000082FFFFFF40B3A29085FFFFFFB4E3C09298A65E8E9CBAE08C0106000040B3A29085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000C0E3C092D8E3C092040000006000000080B2A28FE0865F8D81FFFFFF44E4C092F88FA89900000000D8E3C0928CD9A8998201000040E62B91010000000000000082FFFFFF40B3A29085FFFFFF44E4C09298A05E8EA8B1E08C0106000040B3A29085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000B0A8A790000000007069448D60000000E0A8A79004000000A88BE08C54E4C09278042B940400000068E4C0928CD9A8998201000060E62B91010000000000000082FFFFFFB0A8A79088FFFFFFE4E4C09290855F8DB4A8E08C01070000B0A8A79088FFFFFF
08-26 20:29:56.148  4281  3851 W google-breakpad: S 92C0E480 0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFF40B3A29085FFFFFF00000000D8E4C092D4E4C09288FFFFFF7000000080A8A79070D4A39084E13D9400000000000000000400000008E5C0928CD9A89982010000E0E62B9101000000C0915A9188FFFFFFF0A4A79088FFFFFF64E5C092607B5F8D20A2E08C01050000F0A4A79088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFF70D4A3900100000094E5C092ACE5C09250000000E0D5028E0200000070909B9184E5C092C8032B940000000098E5C092DCBD32928202000000263F91030000000000000082FFFFFFF0A4A79088FFFFFF0000000081FFFFFF70D4A39088FFFFFF34E6C092D0F7828FE832D38D0109000070D4A39088FFFFFF0000000081FFFFFFF0A4A79088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFB050A38F88FFFFFF0000000082FFFFFF0900000081FFFFFF
08-26 20:29:56.148  4281  3851 W google-breakpad: S 92C0E600 70D4A39088FFFFFFC0D4A3900000000064E6C092C0D6F2919000000020C0F291A88BE08C0200000070725F8D81FFFFFF0000000058E6C0928CD9A89982010000B002F3910100000070D4A39088FFFFFF00263F9188FFFFFFDCE6C09228775F8D989BE08C8107000000263F9188FFFFFF70D4A39088FFFFFFB002F39188FFFFFFC0D4A39088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF0000000082FFFFFFC0D4A39088FFFFFF0000000082FFFFFF00E7C09238CFA89900000000C4E6C09278000000E0D5028E00000000E491E08C42030000030000000000000008E7C0928CD9A8990202000020263F9102000000505B619188FFFFFF400C2E9188FFFFFF70D4A39088FFFFFF74E7C092787CE29FB096E08C0106000070D4A39088FFFFFF400C2E9188FFFFFF505B619188FFFFFF20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFF38E7C092A035F49170B4A2904011019260000000E0D5028E85FFFFFF2C44E28C85FFFFFF74E7C092000000000037F491384FE28C800B0000,
08-26 20:29:56.148  4281  3851 W google-breakpad: S 92C0E780 60263F91020000000037F49188FFFFFF400C2E9188FFFFFF707EAF9088FFFFFF80B4A29085FFFFFF20D4A39088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF10A6A790707EAF90A035F4910091A9908A000000C0A7A79080B4A29020D4A390707EAF90A035F49170B4A290801800926091A99009000000A0E50791D0B0F291D0B0F291707EAF9088FFFFFF0900000040110192090000000037F491400C2E91C0A4A790A0E5079188FFFFFF000000007CDBDF9020DDDF90000400008036F491010000000037F49188FFFFFF400C2E9188FFFFFF0000000082FFFFFFF02A9894400C2E9190A4A79060A4A7900000000087FFFFFFA00FF39130A4A79060A4A79080E50791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFF30A4A79088FFFFFFF0E8C09230A4A790D0A3A79000A4A790FCDED58D800200000037F49100000000D0A3A79088FFFFFFF03DA6908A00000007000000003EA690E0F4E99F40B0F291F090A9900037F491
08-26 20:29:56.149  4281  3851 W google-breakpad: S 92C0E900 2008A89903020000603FF7910100000040B0F29188FFFFFFF090A99085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0F4E99FC0CECEB6C8EAC0920100000081FFFFFF20EAC0928CEAC09214C43094603FF7910000000000000000F0E9C092A4E9C0923807A89958DB8E94E0F4E99F00FDCC970CFBC09200000000000000000000000001000000F4F1C092E0F4E99F0001C09200000000B0DDD58D00000000603FF79180EEC092020000000100000014EAC092000000000100000081FFFFFF00ECC0920000000558EEC092F6FFFFFFECF4E99F01000000E0F4E99F20EAC092000000000800000044EAC09214A454940000800020000000C8ECC092F87BFA91000010000000000094EAC09201000000C8EAC092E0F4E99F783B98940082FA9100000000A89E6B908CEAC09250478C5900000000E0F4E99FC8EAC09290EAC092603FF7910082FA91
,08-26 20:29:56.149  4281  3851 W google-breakpad: S 92C0EA80 00000000A89E6B90B4EAC0922C654E9400000000B408569402000000C0CECEB601000000E0F4E99F88EEC092C0EAC0923CEEC09224664E94CCEAC0920C09569488EEC09201000000E80C8E94010000000082FA91C0EAC09200000000009B54940200000038000000C4203D8F2C9A549411EBC09238000000C0EEC09211ECC0923C000000000000E0C0CECEB6C8ECC09260EBC092F87BFA91F00B2E910000000094203D8FF0B75494D8203D8F3CEBC092010000004CEBC0924CEBC092FFFFFF00010000005CEBC09208000000DC203D8FB0203D8F0CD8E08C18D8E08C20805494F0D7E08CF0FFFFFFFFFFFFFF00000000C8ECC09244DFC270C8EF2B9D00203D8F0050F896E0EEC092C8EF2B9D289E6B900050F896C8ECC0920C53CFB6C0EF2B9D9485CEB6C8EF2B9D289E6B905BB2CCB60400000074ECC092888FA38EF8EBC092ECEBC092480834940CD8E08C1CD8E08C782DF58D782DF58DFCEBC092E0EEC09201000000782DF58DE0F4E99FC8ECC09201000000782DF58DE0F4E99FF00B2E91
,08-26 20:29:56.149  4281  3851 W google-breakpad: S 92C0EC00 F00B2E91000000001CECC0922CC32094F8F3C092C8ECC0922CECC092246B2F9400000000C0CECEB6B4F7C0925C3D34940020F58DBCC079940D0000007CF40C9003000000000000000000000000AB34940020F58D64C379946862E28CC8ECC092010000000020F58D80ECC092F87BFA91F00B2E9128CB8C9441B0F291584EE28C10000000280000001C0000002C00000000000000782DF58D0D0000007CF40C9003000000000000000D000000CC7A54940200000001000000C8ECC092000000000000000000000000D8ECC0920000000000000000000000000000000000000000F0ECC092000000000000000000000000000000000000000008EDC092000000000000000000000000000000000000000020EDC09200000000000000000000000030EDC09200000000010000000000000040EDC092000000000000000000000000080000000000000058EDC09200000000080000000000000068EDC09200000000080000000000000078EDC09200000000080000000000000088EDC09200000000
08-26 20:29:56.149  4281  3851 W google-breakpad: S 92C0ED80 000000000000000098EDC092000000000000000005000000A8EDC0920000000000000000020000000200000000000000289E6B900100000001000000000000000000000000000000D8EDC0920000000000000000000000002000000000000000F0EDC09200000000200000000000000001EEC0920000000008EEC09205000000010000000500000018EEC0920200000001000000D000000028EEC09250478C59C0CECEB678EEC092E0F4E99F28EFC09288EEC092A89E6B90E4EEC092E46A4E9450EEC092000000000100000040B0F29188EEC0920100000068FBC092F6FFFFFFECF4E99F00000000E0F4E99F78EEC0920300000008000000603FF79188FFFFFF40B0F29188FFFFFFF090A99085FFFFFF200000000000000001EEC09200000000702A8C94B0203D8F01243D8F00003D8F702A8C94B0203D8F01243D8F50478C5904000000E0F4E99F38EFC09228EFC09230EFC09224EFC09282FFFFFFA09E6B9014EFC09238553E94A09E6B9030EFC09240B0F29188FFFFFF98EFC092A8EFC092
,08-26 20:29:56.150  4281  3851 W google-breakpad: S 92C0EF00 88F0C0920100000040EFC0920000000074EFC09220EB5F9430EFC092080000001800000040B0F291603FF79188FFFFFF0000000082FFFFFF01000000A09E6B900000000082FFFFFFE0F4E99F000000006C177994A8EFC09298EFC0920050FB969852FB96E0F4E99F88F0C0926C177994E4EFC092B8FA5694A8EFC092FCEFC092070000004F0000001C2149908C41BB91000000008041BB9140B0F29188FFFFFFE0F4E99F00000000F090A99085FFFFFFE0F4E99F00000000F8EFC09218707A94AD41BB9118F0C09288F0C09208F0C092E0F4E99FFCEFC092220000000050FB964CF0C092EC6A5894E4D8789450DC789458DB8E94220000008C41BB917442B990000000001CF0C0922200000000000000A0F1C0920000000034F0C09214351694D0F0C092A0F1C09218C18F9498F0C092000000000100000088F0C09278F0C09222000000E0F4E99FDCF1C09228945B94289E6B9000000000E0F4E99F68F0C09202000000B0F0C092F00B2E91D0F0C092109FA89088FFFFFF0000000082FFFFFF
08-26 20:29:56.150  4281  3851 W google-breakpad: S 92C0F080 00000000000100002200000000000000000000000000000000000000E0F4E99F0100000000F2C09210F2C09201000000289E6B90070000000700000001000000807FA79000000000E0F4E99F0000000000000000060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000789E6B9022000000887FA79007000000000000000100000018000092505C019081FFFFFF3CF1C092E0AA489407000000807FA790E0F4E99F000000001000009248F1C0927CF1C092E8EC4894F452CFB6BBC4CBB6B00ADC8F0CB2D58DB0F1C09201000000F40E5C8FA0A3A790E01B0192807FA79000000000FFFFFFFF505C019081FFFFFF18F2C092B0B2D58D70F2C0928CF1C092D8F1C092000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFF807FA79085FFFFFF1000009285FFFFFFE401D8B46049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C019081FFFFFF18F2C09238CFA89900000000ECF1C0928CD9A899000000000000000088FCD78D4202000001000000
08-26 20:29:56.150  4281  3851 W google-breakpad: S 92C0F200 6049F69188FFFFFF00EAF29188FFFFFF807FA79085FFFFFF74F2C092C05C019088FCD78D01050000807FA79085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF000000002801E28C40020000000000005000000030BDF291F0D9019285FFFFFFA4F2C092BCF2C0920000000098F2C0928CD9A899820100008086F691010000000000000082FFFFFF807FA79085FFFFFF44F3C092C05687902CACD68D010A0000807FA79085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF2910000000083FFFFFFA88BE08C020000000000000070F3C0928CD9A89902020000C04CF69102000000A0C6F59188FFFFFF807FA79085FFFFFF60E5079188FFFFFFE4F3C0928097708E84CCE08C81060000
08-26 20:29:56.150  4281  3851 W google-breakpad: S 92C0F380 F0D9019285FFFFFF807FA79085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000C8F3C0920000000083FFFFFF6800000080B2A28F887FA790010000003000000080B2A28F0000000008F4C0928CD9A89982010000E0E52B91010000000000000082FFFFFF807FA79085FFFFFF8CF4C0927090708EBCC4E08C81070000807FA79085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFA8F4C092A0F4C09298F4C0920CF5C0927800000080B2A28F0000000016D6379758DB8E94E0F4E99F00000000B0F4C0928CD9A8998201000020E62B91010000000000000082FFFFFF807FA79085FFFFFF1CF5C09298A65E8E9CBAE08C01060000807FA79085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000028F5C09240F5C09204000000,
08-26 20:29:56.151  4281  3851 W google-breakpad: S 92C0F500 6000000080B2A28FE0865F8D81FFFFFFACF5C092F88FA8990000000040F5C0928CD9A8998201000040E62B91010000000000000082FFFFFF807FA79085FFFFFFACF5C09298A05E8EA8B1E08C01060000807FA79085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000040A3A790000000007069448D6000000070A3A79004000000A88BE08CBCF5C09278042B9404000000D0F5C0928CD9A8998201000060E62B91010000000000000082FFFFFF40A3A79088FFFFFF4CF6C09290855F8DB4A8E08C0107000040A3A79088FFFFFF0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFF807FA79085FFFFFF0000000040F6C0923CF6C09288FFFFFF7000000010A3A790D07DAF9084E13D9400000000000000000400000070F6C0928CD9A89982010000E0E62B9101000000C0915A9188FFFFFF709FA89088FFFFFFCCF6C092607B5F8D20A2E08C01050000
08-26 20:29:56.151  4281  3851 W google-breakpad: S 92C0F680 709FA89088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFFD07DAF9001000000FCF6C09214F7C09250000000E0D5028E0200000070909B91ECF6C092C8032B940000000000F7C092DCBD32928202000000263F91030000000000000082FFFFFF709FA89088FFFFFF0000000081FFFFFFD07DAF9088FFFFFF9CF7C092D0F7828FE832D38D01090000D07DAF9088FFFFFF0000000081FFFFFF709FA89088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF4050A38F88FFFFFF0000000082FFFFFF0900000081FFFFFFD07DAF9088FFFFFF207EAF9000000000CCF7C092C0D6F2919000000020C0F291A88BE08C0200000070725F8D81FFFFFF00000000C0F7C0928CD9A89982010000B002F39101000000D07DAF9088FFFFFF00263F9188FFFFFF44F8C09228775F8D989BE08C8107000000263F9188FFFFFFD07DAF9088FFFFFFB002F39188FFFFFF207EAF9088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF
08-26 20:29:56.151  4281  3851 W google-breakpad: S 92C0F800 0000000082FFFFFF207EAF9088FFFFFF0000000082FFFFFF68F8C09238CFA899000000002CF8C09278000000E0D5028E00000000E491E08C42030000030000000000000070F8C0928CD9A8990202000020263F9102000000505B619188FFFFFFF00B2E9188FFFFFFD07DAF9088FFFFFFDCF8C092787CE29FB096E08C01060000D07DAF9088FFFFFFF00B2E9188FFFFFF505B619188FFFFFF20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFA0F8C092A035F491C090A9904011019260000000E0D5028E85FFFFFF2C44E28C85FFFFFFDCF8C092000000000037F491384FE28C800B000060263F91020000000037F49188FFFFFFF00B2E9188FFFFFFE077AF9088FFFFFFD090A99085FFFFFF807DAF9088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFA0A0A790E077AF90A035F491F03DA6908A00000050A2A790D090A990807DAF90E077AF90A035F491C090A99080180092503EA6900900000000E50791D0B0F291D0B0F291E077AF9088FFFFFF
,08-26 20:29:56.151  4281  3851 W google-breakpad: S 92C0F980 0900000040110192090000000037F491F00B2E91409FA89000E5079188FFFFFF000000007CDBDF9020DDDF90000400008036F491010000000037F49188FFFFFFF00B2E9188FFFFFF0000000082FFFFFFF02A9894F00B2E91109FA890E09EA8900000000087FFFFFFA00FF391B09EA890E09EA890E0E40791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFFB09EA89088FFFFFF00000000B09EA890509EA890809EA890FCDED58D800200000037F49100000000509EA89088FFFFFF2004C1924800000064FAC0923002C1924800000040B0F291E03DA6900037F4912008A89903020000603FF7910100000040B0F29188FFFFFFE03DA69085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0F4E99FC0CECEB630FCC0920100000081FFFFFF88FBC092F4FBC09214C43094603FF791000000000000000058FBC092
08-26 20:29:56.151  4281  3851 W google-breakpad: S 92C0FB00 0CFBC0923807A89958DB8E94E0F4E99F00FDCC97740CC192000000000000000000000000010000005C03C192E0F4E99F0001469100000000B0DDD58D00000000603FF791E8FFC092020000000100000070798090000000000100000081FFFFFF0050F896984CDE8FC0FFC092F6FFFFFFECF4E99F01000000E0F4E99F88FBC092000000000800000020B0469100B04691C07980909A010000B06F809000B0469170B0469118040000480113970100000030FCC092E0F4E99F783B98940082FA9100000000189E6B90F4FBC09250478C5900000000E0F4E99F30FCC092F8FBC092603FF7910082FA9100000000189E6B901CFCC0922C654E9400000000F8FF0C9000000000C0CECEB601000000E0F4E99FF0FFC09228FCC092A4FFC09224664E9452444790FB454790F0FFC09201000000E80C8E94010000000082FA9128FCC09200000000004647900200000002000000010000000000000080BA8D945C0000000600000000000000600BC1920000000000000000000000000000000000000000
08-26 20:29:56.152  4281  3851 W google-breakpad: S 92C0FC80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C47900000000000000000010000000200000040E407910083FA9165D6269D000000000000000050478C5900000000C0CECEB600000000E0F4E99FC8BA4094C0FDC0923C01C192A8664E940000000000000000E001C192000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-26 20:29:56.152  4281  3851 W google-breakpad: S 92C0FE00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000005800BC8D6408BC8D00000000008000006408BC8D97C3CBB648FFC09220FFC0926408BC8DE401D8B4E801D8B46408BC8D00000000C3C5CBB6B00ADC8FFFFFFFFFEC1088900100000020049C9101000000040B149D010000006C06008F010000003C12748A01000000E801D8B4FFFFFFFFE801D8B4FFFFFFFFDC140C90FFFFFFFF1008F48DFFFFFFFF8C13B08DFFFFFFFFF40E588DFFFFFFFF
08-26 20:29:56.152  4281  3851 W google-breakpad: S 92C0FF80 F40E588D50478C59C0CECEB6E0FFC092E0F4E99F9000C192F0FFC092189E6B904C00C192E46A4E9400000000000000000000000040B0F291F0FFC09201000000D00CC192F6FFFFFFECF4E99F00000000E0F4E99FE0FFC0920300000008000000603FF79188FFFFFF40B0F29188FFFFFFE03DA69085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000050478C5904000000E0F4E99FA000C1929000C1929800C1928C00C19282FFFFFF109E6B907C00C19238553E94109E6B909800C19240B0F29188FFFFFF0001C1921001C192F001C19201000000A800C19200000000DC00C19220EB5F949800C192000000001800000040B0F291603FF79188FFFFFF0000000082FFFFFF01000000109E6B900000000082FFFFFFE0F4E99F000000006C1779941001C1920001C1920050FB969852FB96E0F4E99FF001C1926C1779944C01C192B8FA56941001C1926401C192070000004F0000001C2149903C41BB91000000003041BB91
08-26 20:29:56.152  4281  3851 W google-breakpad: S 92C10100 40B0F29188FFFFFFE0F4E99F00000000E03DA69085FFFFFFE0F4E99F000000006001C19218707A945D41BB918001C192F001C1927001C192E0F4E99F6401C192220000000050FB96B401C192EC6A5894E4D8789450DC789458DB8E94220000003C41BB914442B990C086BB908401C19222000000000000000803C192000000009C01C192143516943802C1920803C19218C18F940002C1920000000001000000F001C192E001C19222000000E0F4E99F4403C19228945B94D89D6B90000000003880BD8D00000000000000001802C1923402C1923802C1925002C192000000000000000082FFFFFF0000000000010000220000000000000000000000000000000002C192E0F4E99F010000006803C1927803C19201200000D89D6B90070000000700000001000000803CA69000000020E0F4E99FE4FBC092984CDE8F060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000D09D6B9022000000883CA69007000000000000000100000018000092505C019001000000
,08-26 20:29:56.153  4281  3851 W google-breakpad: S 92C10280 A402C192E0AA489407000000803CA690E0F4E99F0000000010000092B002C192E402C192E8EC4894580BD08FFFFFFFFFA80C888F0CB2D58D1803C192010000006408848F209EA890E01B0192803CA69000000000FFFFFFFF505C0190010000008003C192B0B2D58DD803C192F402C1924003C192000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFF803CA69085FFFFFF1000009285FFFFFF8803C1926049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C0190010000008003C19238CFA899000000005403C1928CD9A899000000000000000088FCD78D42020000010000006049F69188FFFFFF00EAF29188FFFFFF803CA69085FFFFFFDC03C192C05C019088FCD78D01050000803CA69085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF000000002801E28C40020000000000005000000030BDF291F0D9019285FFFFFF0C04C1922404C192000000000004C1928CD9A899820100008086F691010000000000000082FFFFFF803CA69085FFFFFF
08-26 20:29:56.153  4281  3851 W google-breakpad: S 92C10400 AC04C192C05687902CACD68D010A0000803CA69085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF2910000000083FFFFFFD09CA8900302000000000000D804C1928CD9A89902020000C04CF69102000000A0C6F59188FFFFFF803CA69085FFFFFFC0E4079188FFFFFF4C05C1928097708E84CCE08C81060000F0D9019285FFFFFF803CA69085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300003005C1920000000083FFFFFF6800000080B2A28F883CA690010000003000000080B2A28F000000007005C1928CD9A89982010000E0E52B91010000000000000082FFFFFF803CA69085FFFFFFF405C1927090708EBCC4E08C81070000
08-26 20:29:56.153  4281  3851 W google-breakpad: S 92C10580 803CA69085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF1006C1920806C1920006C1927406C1927800000080B2A28F0000000016D6379758DB8E94E0F4E99F000000001806C1928CD9A8998201000020E62B91010000000000000082FFFFFF803CA69085FFFFFF8406C19298A65E8E9CBAE08C01060000803CA69085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000009006C192A806C192040000006000000080B2A28FE0865F8D010000001407C192F88FA89900000000A806C1928CD9A8998201000040E62B91010000000000000082FFFFFF803CA69085FFFFFF1407C19298A05E8EA8B1E08C01060000803CA69085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000C09DA890000000007069448D60000000F09DA890
08-26 20:29:56.153  4281  3851 W google-breakpad: S 92C10700 04000000D09CA8902407C19278042B94040000003807C1928CD9A8998201000060E62B91010000000000000082FFFFFFC09DA89088FFFFFFB407C19290855F8DB4A8E08C01070000C09DA89088FFFFFF0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFF803CA69085FFFFFF00000000A807C192A407C19288FFFFFF70000000909DA8904077AF9084E13D94000000000000000004000000D807C1928CD9A89982010000E0E62B9101000000C0915A9188FFFFFF009AA89088FFFFFF3408C192607B5F8D20A2E08C01050000009AA89088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFF4077AF90010000006408C1927C08C19250000000E0D5028E0302000070909B915408C192C8032B94000000006808C192DCBD32928202000000263F91030000000000000082FFFFFF009AA89088FFFFFF0000000081FFFFFF4077AF9088FFFFFF0409C192D0F7828FE832D38D010900004077AF9088FFFFFF
08-26 20:29:56.153  4281  3851 W google-breakpad: S 92C10880 0000000081FFFFFF009AA89088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF90EF219188FFFFFF0000000082FFFFFF0900000081FFFFFF4077AF9088FFFFFF9077AF90000000003409C192C0D6F2919000000020C0F291D09CA8900302000070725F8D01000000000000002809C1928CD9A89982010000B002F391010000004077AF9088FFFFFF00263F9188FFFFFFAC09C19228775F8D989BE08C8107000000263F9188FFFFFF4077AF9088FFFFFFB002F39188FFFFFF9077AF9088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF0000000082FFFFFF9077AF9088FFFFFF0000000082FFFFFFD009C19238CFA899000000009409C19278000000E0D5028E00000000E491E08C420300000300000000000000D809C1928CD9A8990202000020263F9102000000505B619188FFFFFFA00B2E9188FFFFFF4077AF9088FFFFFF440AC192787CE29FB096E08C010600004077AF9088FFFFFFA00B2E9188FFFFFF505B619188FFFFFF
08-26 20:29:56.154  4281  3851 W google-breakpad: S 92C10A00 20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFCCF1A8998C0AC192900AC1920000000060000000E0D5028E780AC19200000000D09CA8900302000000000000700AC1928CD9A8990202000060263F91020000000037F49188FFFFFFA00B2E9188FFFFFF5071AF9088FFFFFF0C0BC19258C62997FC34D78D010900005071AF9088FFFFFFA00B2E9188FFFFFF0037F49188FFFFFF60263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFC03DA69085FFFFFFF076AF9088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF60E4079188FFFFFFD09CA89088FFFFFF603FF7910100000090000000D099A890140BC192040BC1920825989400000000040000005C0DC19220DDDF90000400008036F491010000000037F49188FFFFFFA00B2E9188FFFFFF0000000082FFFFFFF02A9894A00B2E91A099A8907099A8900000000087FFFFFFA00FF3914099A8907099A89040E40791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFF
08-26 20:29:56.154  4281  3851 W google-breakpad: S 92C10B80 4099A89088FFFFFFC00BC1924099A890E098A8901099A890FCDED58D800200000037F49100000000E098A89088FFFFFF006AA6908A00000007000000106AA690E0F4E99F40B0F29190CBA4900037F4912008A89903020000603FF7910100000040B0F29188FFFFFF90CBA49085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0F4E99FC0CECEB6980DC1920100000081FFFFFFF00CC1925C0DC19214C43094603FF7910000000000000000C00CC192740CC1923807A89958DB8E94E0F4E99F00FDCC97DC1DC19200000000000000000000000001000000C414C192E0F4E99F0001000000000000B0DDD58D00000000603FF7915011C192020000000100000000000000000000000100000081FFFFFF00000000000000002811C192F6FFFFFFECF4E99F01000000E0F4E99FF00CC192000000000800000000000000000000000000000000000000
08-26 20:29:56.154  4281  3851 W google-breakpad: S 92C10D00 000000000000000000000000000000000000000001000000980DC192E0F4E99F783B98940082FA9100000000689D6B905C0DC19250478C5900000000E0F4E99F980DC192600DC192603FF7910082FA9100000000689D6B90840DC1922C654E94000000000000000000000000C0CECEB601000000E0F4E99F5811C192900DC1920C11C19224664E9452444790FB4547905811C19201000000E80C8E94010000000082FA91900DC19200000000004647900200000002000000010000000000000080BA8D945C0000000600000000000000C81CC19200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.154  4281  3851 W google-breakpad: S 92C10E80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C479000000000000000000100000002000000A0E307910083FA9165D6269D000000000000000050478C5900000000C0CECEB600000000E0F4E99FC8BA4094280FC192A412C192A8664E9400000000000000004813C1920000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.155  4281  3851 W google-breakpad: S 92C11000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C59C0CECEB64811C192E0F4E99FF811C1925811C192689D6B90B411C192E46A4E9400000000000000000000000040B0F2915811C19201000000381EC192F6FFFFFFECF4E99F00000000E0F4E99F4811C1920300000008000000603FF79188FFFFFF40B0F29188FFFFFF90CBA49085FFFFFF0000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.155  4281  3851 W google-breakpad: S 92C11180 00000000000000000000000050478C5904000000E0F4E99F0812C192F811C1920012C192F411C19282FFFFFF609D6B90E411C19238553E94609D6B900012C19240B0F29188FFFFFF6812C1927812C1925813C192010000001012C192000000004412C19220EB5F940012C192000000001800000040B0F291603FF79188FFFFFF0000000082FFFFFF01000000609D6B900000000082FFFFFFE0F4E99F000000006C1779947812C1926812C1920050FB969852FB96E0F4E99F5813C1926C177994B412C192B8FA56947812C192CC12C192070000004F0000001C214990EC40BB9100000000E040BB9140B0F29188FFFFFFE0F4E99F0000000090CBA49085FFFFFFE0F4E99F00000000C812C19218707A940D41BB91E812C1925813C192D812C192E0F4E99FCC12C192220000000050FB961C13C192EC6A5894E4D8789450DC789458DB8E9422000000EC40BB911442B990E801D8B4EC12C19222000000000000007014C192000000000413C19214351694A013C1927014C19218C18F946813C192
08-26 20:29:56.155  4281  3851 W google-breakpad: S 92C11300 00000000010000005813C1924813C19222000000E0F4E99FAC14C19228945B94409D6B9000000000E0F4E99F3813C192020000008013C192500B2E91A013C1923094A89088FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0F4E99F01000000D014C192E014C19201000000409D6B9007000000070000000100000030CAA49000000000E0F4E99F0000000000000000060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000489D6B902200000038CAA49007000000000000000100000018000092505C0190010000000C14C192E0AA48940700000030CAA490E0F4E99F00000000100000921814C1924C14C192E8EC4894F452CFB6BBC4CBB6B00ADC8F0CB2D58D8014C19201000000F40E5C8FB098A890E01B019230CAA49000000000FFFFFFFF505C019001000000E814C192B0B2D58D4015C1925C14C192A814C192000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFF30CAA49085FFFFFF
08-26 20:29:56.155  4281  3851 W google-breakpad: S 92C11480 1000009285FFFFFFE401D8B46049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C019001000000E814C19238CFA89900000000BC14C1928CD9A899000000000000000088FCD78D42020000010000006049F69188FFFFFF00EAF29188FFFFFF30CAA49085FFFFFF4415C192C05C019088FCD78D0105000030CAA49085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF000000002801E28C40020000000000005000000030BDF291F0D9019285FFFFFF7415C1928C15C192000000006815C1928CD9A899820100008086F691010000000000000082FFFFFF30CAA49085FFFFFF1416C192C05687902CACD68D010A000030CAA49085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF291
08-26 20:29:56.155  4281  3851 W google-breakpad: S 92C11600 0000000083FFFFFF6097A89003020000000000004016C1928CD9A89902020000C04CF69102000000A0C6F59188FFFFFF30CAA49085FFFFFF20E4079188FFFFFFB416C1928097708E84CCE08C81060000F0D9019285FFFFFF30CAA49085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300009816C1920000000083FFFFFF6800000080B2A28F38CAA490010000003000000080B2A28F00000000D816C1928CD9A89982010000E0E52B91010000000000000082FFFFFF30CAA49085FFFFFF5C17C1927090708EBCC4E08C8107000030CAA49085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF7817C1927017C1926817C192DC17C1927800000080B2A28F0000000016D6379758DB8E94E0F4E99F000000008017C1928CD9A8998201000020E62B91010000000000000082FFFFFF30CAA49085FFFFFF
08-26 20:29:56.156  4281  3851 W google-breakpad: S 92C11780 EC17C19298A65E8E9CBAE08C0106000030CAA49085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F817C1921018C192040000006000000080B2A28FE0865F8D010000007C18C192F88FA899000000001018C1928CD9A8998201000040E62B91010000000000000082FFFFFF30CAA49085FFFFFF7C18C19298A05E8EA8B1E08C0106000030CAA49085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000005098A890000000007069448D600000008098A890040000006097A8908C18C19278042B9404000000A018C1928CD9A8998201000060E62B91010000000000000082FFFFFF5098A89088FFFFFF1C19C19290855F8DB4A8E08C010700005098A89088FFFFFF0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFF30CAA49085FFFFFF000000001019C1920C19C19288FFFFFF
08-26 20:29:56.156  4281  3851 W google-breakpad: S 92C11900 700000002098A890B070AF9084E13D940000000000000000040000004019C1928CD9A89982010000E0E62B9101000000C0915A9188FFFFFF9094A89088FFFFFF9C19C192607B5F8D20A2E08C010500009094A89088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFFB070AF9001000000CC19C192E419C19250000000E0D5028E0302000070909B91BC19C192C8032B9400000000D019C192DCBD32928202000000263F91030000000000000082FFFFFF9094A89088FFFFFF0000000081FFFFFFB070AF9088FFFFFF6C1AC192D0F7828FE832D38D01090000B070AF9088FFFFFF0000000081FFFFFF9094A89088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF20EF219188FFFFFF0000000082FFFFFF0900000081FFFFFFB070AF9088FFFFFF0071AF90000000009C1AC192C0D6F2919000000020C0F2916097A8900302000070725F8D0100000000000000901AC1928CD9A89982010000B002F39101000000
08-26 20:29:56.156  4281  3851 W google-breakpad: S 92C11A80 B070AF9088FFFFFF00263F9188FFFFFF141BC19228775F8D989BE08C8107000000263F9188FFFFFFB070AF9088FFFFFFB002F39188FFFFFF0071AF9088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF0000000082FFFFFF0071AF9088FFFFFF0000000082FFFFFF381BC19238CFA89900000000FC1AC19278000000E0D5028E00000000E491E08C420300000300000000000000401BC1928CD9A8990202000020263F9102000000505B619188FFFFFF500B2E9188FFFFFFB070AF9088FFFFFFAC1BC192787CE29FB096E08C01060000B070AF9088FFFFFF500B2E9188FFFFFF505B619188FFFFFF20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFCCF1A899F41BC192F81BC1920000000060000000E0D5028EE01BC192000000006097A8900302000000000000D81BC1928CD9A8990202000060263F91020000000037F49188FFFFFF500B2E9188FFFFFFB01AA59088FFFFFF741CC19258C62997FC34D78D01090000B01AA59088FFFFFF500B2E9188FFFFFF0037F49188FFFFFF
08-26 20:29:56.156  4281  3851 W google-breakpad: S 92C11C00 60263F9188FFFFFF0000000082FFFFFF0000000082FFFFFF70CBA49085FFFFFF6070AF9088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFC0E3079188FFFFFF6097A89088FFFFFF603FF79101000000900000006094A8907C1CC1926C1CC192082598940000000004000000C41EC19220DDDF90000400008036F491010000000037F49188FFFFFF500B2E9188FFFFFF0000000082FFFFFFF02A9894500B2E913094A8900094A8900000000087FFFFFFA00FF391D093A8900094A890A0E30791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFFD093A89088FFFFFF281DC192D093A8907093A890A093A890FCDED58D800200000037F491000000007093A89088FFFFFF1049A6908A000000070000002049A690E0F4E99F40B0F291F069A6900037F4912008A89903020000603FF7910100000040B0F29188FFFFFFF069A69085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.157  4281  3851 W google-breakpad: S 92C11D80 0000000000000000000000000000000000000000000000000000000000000000E0F4E99FC0CECEB6001FC1920100000081FFFFFF581EC192C41EC19214C43094603FF7910000000000000000281EC192DC1DC1923807A89958DB8E94E0F4E99F00FDCC97442FC192000000000000000000000000010000002C26C192E0F4E99F0001000000000000B0DDD58D00000000603FF791B822C192020000000100000000000000000000000100000081FFFFFF00000000000000009022C192F6FFFFFFECF4E99F01000000E0F4E99F581EC192000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000001FC192E0F4E99F783B98940082FA9100000000309D6B90C41EC19250478C5900000000E0F4E99F001FC192C81EC192603FF7910082FA9100000000309D6B90EC1EC1922C654E94000000000000000000000000C0CECEB601000000E0F4E99FC022C192F81EC1927422C19224664E9452444790FB454790C022C19201000000
08-26 20:29:56.157  4281  3851 W google-breakpad: S 92C11F00 E80C8E94010000000082FA91F81EC19200000000004647900200000002000000010000000000000080BA8D945C0000000600000000000000302EC19200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003C47900000000000000000010000000200000000E307910083FA9165D6269D000000000000000050478C5900000000C0CECEB600000000E0F4E99FC8BA40949020C192
08-26 20:29:56.157  4281  3851 W google-breakpad: S 92C12080 0C24C192A8664E940000000000000000B024C19200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.157  4281  3851 W google-breakpad: S 92C12200 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C59C0CECEB6B022C192E0F4E99F6023C192C022C192309D6B901C23C192E46A4E9400000000000000000000000040B0F291C022C19201000000A02FC192F6FFFFFFECF4E99F00000000E0F4E99FB022C1920300000008000000603FF79188FFFFFF40B0F29188FFFFFFF069A69085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050478C5900000000E0F4E99F7023C1926023C1926823C1925C23C19282FFFFFF289D6B904C23C19238553E94289D6B906823C19240B0F29188FFFFFFD023C192E023C192C024C192010000007823C19200000000AC23C19220EB5F946823C192000000001800000040B0F291603FF79188FFFFFF0000000082FFFFFF01000000289D6B900000000082FFFFFF
08-26 20:29:56.157  4281  3851 W google-breakpad: S 92C12380 E0F4E99F000000006C177994E023C192D023C1920050FB969852FB96E0F4E99FC024C1926C1779941C24C192B8FA5694E023C1923424C192070000004F0000001C2149909C40BB91000000009040BB9140B0F29188FFFFFFE0F4E99F00000000F069A69085FFFFFFE0F4E99F000000003024C19218707A94BD40BB915024C192C024C1924024C192E0F4E99F3424C192220000000050FB968424C192EC6A5894E4D8789450DC789458DB8E94220000009C40BB91E441B990000000005424C1922200000000000000D825C192000000006C24C192143516940825C192D825C19218C18F94D024C1920000000001000000C024C192B024C19222000000E0F4E99F1426C19228945B94109D6B9000000000E0F4E99FA024C19202000000E824C192000B2E910825C192B02EA59088FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0F4E99F010000003826C1924826C19201000000109D6B900700000007000000010000009068A69000000000
08-26 20:29:56.158  4281  3851 W google-breakpad: S 92C12500 E0F4E99F0000000000000000060000003CC18F943CC18F940600000018C18F9400000000FFFFFFFF00000000209D6B90220000009868A69007000000000000000100000018000092505C0190010000007425C192E0AA4894070000009068A690E0F4E99F00000000100000928025C192B425C192E8EC4894F452CFB6BBC4CBB6B00ADC8F0CB2D58DE825C1920100000020049C914093A890E01B01929068A69000000000FFFFFFFF505C0190010000005026C192B0B2D58DA826C192C425C1921026C192000000000000000078B2D58D4003000001000000FFFFFFFF81FFFFFF9068A69085FFFFFF1000009285FFFFFFE401D8B46049F69188FFFFFF88FCD78D00000000FFFFFFFFC05C0190010000005026C19238CFA899000000002426C1928CD9A899000000000000000088FCD78D42020000010000006049F69188FFFFFF00EAF29188FFFFFF9068A69085FFFFFFAC26C192C05C019088FCD78D010500009068A69085FFFFFF00EAF29188FFFFFF6049F69188FFFFFF0000000082FFFFFF
08-26 20:29:56.158  4281  3851 W google-breakpad: S 92C12680 000000002801E28C40020000000000005000000030BDF291F0D9019285FFFFFFDC26C192F426C19200000000D026C1928CD9A899820100008086F691010000000000000082FFFFFF9068A69085FFFFFF7C27C192C05687902CACD68D010A00009068A69085FFFFFF0000000082FFFFFF8086F69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007009285FFFFFFF0D9019285FFFFFF82FFFFFF58189894F0FB0192B48AE08CA000000030BDF2910000000083FFFFFFF091A8900302000000000000A827C1928CD9A89902020000C04CF69102000000A0C6F59188FFFFFF9068A69085FFFFFF80E3079188FFFFFF1C28C1928097708E84CCE08C81060000F0D9019285FFFFFF9068A69085FFFFFFA0C6F59188FFFFFFC04CF69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300000028C1920000000083FFFFFF
08-26 20:29:56.158  4281  3851 W google-breakpad: S 92C12800 6800000080B2A28F9868A690010000003000000080B2A28F000000004028C1928CD9A89982010000E0E52B91010000000000000082FFFFFF9068A69085FFFFFFC428C1927090708EBCC4E08C810700009068A69085FFFFFF0000000082FFFFFFE0E52B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE028C192D828C192D028C1924429C1927800000080B2A28F0000000016D6379758DB8E94E0F4E99F00000000E828C1928CD9A8998201000020E62B91010000000000000082FFFFFF9068A69085FFFFFF5429C19298A65E8E9CBAE08C010600009068A69085FFFFFF0000000082FFFFFF20E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000006029C1927829C192040000006000000080B2A28FE0865F8D01000000E429C192F88FA899000000007829C1928CD9A8998201000040E62B91010000000000000082FFFFFF9068A69085FFFFFFE429C19298A05E8E
08-26 20:29:56.158  4281  3851 W google-breakpad: S 92C12980 A8B1E08C010600009068A69085FFFFFF0000000082FFFFFF40E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E092A890000000007069448D600000001093A89004000000F091A890F429C19278042B9404000000082AC1928CD9A8998201000060E62B91010000000000000082FFFFFFE092A89088FFFFFF842AC19290855F8DB4A8E08C01070000E092A89088FFFFFF0000000082FFFFFF60E62B9188FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013019285FFFFFF9068A69085FFFFFF00000000782AC192742AC19288FFFFFF70000000B092A890101AA59084E13D94000000000000000004000000A82AC1928CD9A89982010000E0E62B9101000000C0915A9188FFFFFF102FA59088FFFFFF042BC192607B5F8D20A2E08C01050000102FA59088FFFFFFC0915A9188FFFFFFE0E62B9188FFFFFFC0D3019285FFFFFF101AA59001000000342BC1924C2BC19250000000E0D5028E0302000070909B91242BC192C8032B94
08-26 20:29:56.159  4281  3851 W google-breakpad: S 92C12B00 00000000382BC192DCBD32928202000000263F91030000000000000082FFFFFF102FA59088FFFFFF0000000081FFFFFF101AA59088FFFFFFD42BC192D0F7828FE832D38D01090000101AA59088FFFFFF0000000081FFFFFF102FA59088FFFFFF0000000082FFFFFF00263F9188FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFB0EE219188FFFFFF0000000082FFFFFF0900000081FFFFFF101AA59088FFFFFF601AA59000000000042CC192C0D6F2919000000020C0F291F091A8900302000070725F8D0100000000000000F82BC1928CD9A89982010000B002F39101000000101AA59088FFFFFF00263F9188FFFFFF7C2CC19228775F8D989BE08C8107000000263F9188FFFFFF101AA59088FFFFFFB002F39188FFFFFF601AA59088FFFFFFC0D6F29188FFFFFFC0D0F29188FFFFFF0000000082FFFFFF601AA59088FFFFFF0000000082FFFFFFA02CC19238CFA89900000000642CC19278000000E0D5028E00000000E491E08C420300000300000000000000A82CC192
08-26 20:29:56.159  4281  3851 W google-breakpad: S 92C12C80 8CD9A8990202000020263F9102000000505B619188FFFFFF000B2E9188FFFFFF101AA59088FFFFFF142DC192787CE29FB096E08C01060000101AA59088FFFFFF000B2E9188FFFFFF505B619188FFFFFF20263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFCCF1A8995C2DC192602DC1920000000060000000E0D5028E482DC19200000000F091A8900302000000000000402DC1928CD9A8990202000060263F91020000000037F49188FFFFFF000B2E9188FFFFFF2014A59088FFFFFFDC2DC19258C62997FC34D78D010900002014A59088FFFFFF000B2E9188FFFFFF0037F49188FFFFFF60263F9188FFFFFF0000000082FFFFFF0000000082FFFFFFD069A69085FFFFFFC019A59088FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF20E3079188FFFFFFF091A89088FFFFFF603FF7910100000090000000E02EA590E42DC192D42DC1920825989400000000040000002C30C19220DDDF90000400008036F491010000000037F49188FFFFFF000B2E9188FFFFFF
08-26 20:29:56.159  4281  3851 W google-breakpad: S 92C12E00 0000000082FFFFFFF02A9894000B2E91B02EA590802EA5900000000087FFFFFFA00FF391502EA590802EA59000E30791E0BBD58D80020000C036F491020000000000000082FFFFFFA00FF39188FFFFFF502EA59088FFFFFF902EC192502EA590F02DA590202EA590FCDED58D800200000037F49100000000F02DA59088FFFFFFD0B8A3908A00000007000000E0B8A390E0F4E99F40B0F2910049A6900037F4912008A89903020000603FF7910100000040B0F29188FFFFFF0049A69085FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0F4E99FC0CECEB66830C1920100000081FFFFFFC02FC1922C30C19214C43094603FF7910000000000000000902FC192442FC1923807A89958DB8E94E0F4E99F00FDCC97AC40C192000000000000000000000000010000009437C192E0F4E99F0001000000000000B0DDD58D00000000603FF7912034C192
08-26 20:29:56.159  4281  3851 W google-breakpad: S 92C12F80 020000000100000000000000000000000100000081FFFFFF0000000000000000F833C192F6FFFFFFECF4E99F01000000E0F4E99FC02FC1920000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000006830C192E0F4E99F783B98940082FA9100000000D89C6B90
08-26 20:29:56.159  4281  3851 W google-breakpad: C 060000400080109D0000000064BBC092E0BBC09238BBC0928CBBC092E0F4E99F64BBC09240EEA09085FFFFFF0050FB965CBBC09220BBC09228BBC09278293E947C293E9410000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 20:29:56.160  4281  3851 W google-breakpad: M B6F45000 00000000 00005000 E72F8FF84F6E260968CCE78B856F06B70 app_process32
08-26 20:29:56.160  4281  3851 W google-breakpad: M 93E9B000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-26 20:29:56.160  4281  3851 W google-breakpad: M A255D000 007F2000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
08-26 20:29:56.160  4281  3851 W google-breakpad: M A895D000 00000000 00006000 0D31362517BA6979AC917A35D240E1210 libwebviewchromium_loader.so
08-26 20:29:56.160  4281  3851 W google-breakpad: M A8A01000 00000000 00005000 590854A6A5B5D59683870D00EAE455310 libjnigraphics.so
08-26 20:29:56.160  4281  3851 W google-breakpad: M A8A06000 00000000 0000A000 4AE1FB560051D628B937E5D0F75C69F30 libcompiler_rt.so
08-26 20:29:56.160  4281  3851 W google-breakpad: M A8A10000 00000000 00011000 4CBE9A6CCCBDC8B3EF8B751BC123CEE50 libandroid.so
08-26 20:29:56.160  4281  3851 W google-breakpad: M A8A21000 00000000 0000C000 AFC34749768B41E8D431AF946E23577B0 libqservice.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A2D000 00000000 0000B000 356C1D2029892384AFE121956A0BB4EA0 libqdutils.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A38000 00000000 00005000 95E7634C1A490462E66752EC8939C4530 libqdMetaData.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A3D000 00000000 00008000 9997EA703403C3035DE00C7EE7880E430 libmemalloc.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A45000 00000000 00008000 3FE99556F2945012B0CB1BE7C353A6540 gralloc.msm8084.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A4D000 00000000 0000C000 A1BCE730F0644DAE1C5CBC146CD02BD90 eglSubDriverAndroid.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A59000 00000000 00027000 2A6DCFEF23E3A32055F90972FCABFED60 libGLESv1_CM_adreno.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A8A80000 00000000 0073D000 2003920CF0749EC2675D7EE282DE502B0 libllvm-glnext.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A91CE000 00000000 004AD000 3082CAE2C0BC6E87686AEAA07100FEDE0 libGLESv2_adreno.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A967D000 00000000 0003D000 44E63552D97113055F6017F152FAF0340 libgsl.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A96BA000 00000000 00007000 417C9A0548EF994318FDD8293BD2B4A90 libadreno_utils.so
08-26 20:29:56.161  4281  3851 W google-breakpad: M A96C3000 00000000 00013000 B4DF6A0A447291C436FE548566C498C00 libEGL_adreno.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB14E000 00000000 0001B000 B0EFA02804790BBB6DE8B2B9095BE9CB0 libkeymaster1.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB169000 00000000 00017000 6658C7A49E3552941CE5496BFD2B34980 libsoftkeymasterdevice.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB1C1000 00000000 0000B000 D13E1014D51DECF5BF9D21E7C67666130 libkeymaster_messages.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB1CC000 00000000 0000E000 25D7B988B89B18BC0429BB562FA2DE990 libkeystore_binder.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB1DA000 00000000 00006000 B33B16D8A7ED9B8FFB7AA215D6923C4B0 libkeystore-engine.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB1E0000 00000000 00018000 CEF05C42255586B6905B0AF681C33D8C0 libjavacrypto.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB1F9000 00000000 00010000 0C521B6A6E9E39A0E22193BB5D5525130 libstagefright_amrnb_common.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB209000 00000000 0002C000 582DF60B6AA35307BD7198E3A18119AB0 libexif.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB235000 00000000 0000D000 7CD678568D893C8FE9A4676BCD58F2AD0 libjhead.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB243000 00000000 00018000 ADA21AF62918F8A878B3FE4F2F0456580 libmtp.so
08-26 20:29:56.162  4281  3851 W google-breakpad: M AB25B000 00000000 00048000 0262207412DD5679BF20EB25407B7B440 libmedia_jni.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M AF087000 00000000 00005000 B37EB6398BB0DBE353FE8B1F1DEAB2EB0 memtrack.msm8084.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B0700000 00000000 00036000 E15D31AAB91199642EB180D3D4160C520 libjavacore.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B36CA000 00000000 00007000 79903F128710C73A4159E0E685663A550 libwebviewchromium_plat_support.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B4865000 00000000 00459000 D1BC38C6D191DBFC4B3B8BE9676A2FBB0 libart.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B4DC1000 00000000 00005000 68126D6F94C506C8BE6DAA402968ABD50 libsigchain.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B4DE9000 00000000 00A5C000 0B64AEBAA12EA3FC8CB4E80A5310D9A20 libLLVM.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B584E000 00000000 00038000 EB0128750F7A47E1274CC11D426A63840 libbcinfo.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B5886000 00000000 0005B000 8D9A857B04F62EBCFEC94FC226C49F600 libbcc.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B58E1000 00000000 0000E000 BD9845C69DC7ADC5D6D7E1756D34DD830 libcommon_time_client.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B58F0000 00000000 0001A000 9AC4BF2FD171753488B9C5DB621A9A240 libprotobuf-cpp-lite.so
08-26 20:29:56.163  4281  3851 W google-breakpad: M B590A000 00000000 00009000 9B164CEF29D3AA5EAF47FA86862586FF0 libstagefright_avc_common.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B5913000 00000000 00005000 4AA290A61993A8A5677655D665763B3D0 libstagefright_enc_common.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B5918000 00000000 00007000 5146A8AEEE822B0CE87F523ABAE749F50 libpowermanager.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B591F000 00000000 0001F000 EF15E47D9893659F6C584D4542F099490 libvorbisidec.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B593E000 00000000 00007000 9C90BE63E61A2127D39B214E6F43AF350 libstagefright_yuv.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B5946000 00000000 00032000 C3AC584E1FF634156E2797138D35375E0 libstagefright_omx.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B5978000 00000000 0003D000 B85FA71D8415B28DE38A933B1508D9F00 libopus.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B59B5000 00000000 0000A000 5BEFFA75C748ED7D23421EF091D1F1300 libmediautils.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B59BF000 00000000 0001A000 64DF194390054DFAFF82926D89B359340 libdrmframework.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B59D9000 00000000 00021000 A395A730CEF4C5A1BB47058DE0D9186E0 libRScpp.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B59FA000 00000000 00042000 70A461E7FEC54E6D7E1E5C66F936CE350 libRS.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B5A3C000 00000000 00009000 FDC63F080EB6155F934F885DEB37E94E0 libspeexresampler.so
08-26 20:29:56.164  4281  3851 W google-breakpad: M B5A45000 00000000 0000B000 FFD2B97AE5B754AC2E9678225D23B75A0 libnbaio.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5A50000 00000000 00014000 669F5236C39ADF5E46701FF6C9F768980 libpcre.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5A66000 00000000 00007000 21F0774A2FE026AA52F7480655D27ABE0 libwpa_client.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5A6D000 00000000 00071000 C8703400FE46F435C2134FB0F3FDE9390 libGLES_trace.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5ADE000 00000000 00067000 1821F1842FA60DF842F94DF364C495A10 libft2.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5B45000 00000000 00027000 C5A689AFC30DE04B5E7E5ACBF12CA9330 libpng.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5B6C000 00000000 00005000 E0AD90DEBEAFB376EBAA5415267856B40 libsync.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5B71000 00000000 00007000 F5424CDA56569E38CF2903ECFAFF296E0 libstdc++.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5B78000 00000000 00012000 B4E430E8258C544A786360668D84BE8B0 libunwind.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5BD0000 00000000 0000B000 96BB8488669F21FEDA8649403EB8BB0E0 libbase.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5BDB000 00000000 00007000 D32E249CC58B3A22906A78EDFDD545460 libeffects.so
08-26 20:29:56.165  4281  3851 W google-breakpad: M B5BE3000 00000000 00006000 1964BC7CB1EF496E207C18FC55A57E6C0 libstagefright_http_support.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5BE9000 00000000 0001B000 4E010519E1AA1D9D10F586E0C0490F120 libstagefright_foundation.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5C04000 00000000 0015B000 009817DD6F2FD8255E5AAE0FDE05646B0 libstagefright.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5D5F000 00000000 00070000 4054B4690025F8746C0DC28CC9D69D870 libhwui.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5DCF000 00000000 00005000 9CA9EF8816A2E0C106C15197423A91AE0 libradio_metadata.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5DD4000 00000000 00006000 F1863EB76C05E59645A8AA848D1624570 libnativebridge.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5DDA000 00000000 00006000 1D210F6A59079D7FD7F258724A88DEA70 libprocessgroup.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5DE0000 00000000 00011000 FDCAD8835C0C336BEB30CF765069FC3A0 libminikin.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5DF1000 00000000 0000E000 238BED0ADF305646BB994A7A676D0A1E0 libsoundtrigger.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5E00000 00000000 0000E000 00FDCB77534A86A2594207ABA92E7FBF0 libradio.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5E0E000 00000000 00006000 BBCF64A69A9F42E7BC0E0BD423E728790 libnetd_client.so
08-26 20:29:56.166  4281  3851 W google-breakpad: M B5E14000 00000000 00010000 727E80AEB01F5239858F79470BB43E850 libimg_utils.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B5E24000 00000000 00420000 2D9D72FD541F8A7DFBF9302532B5F3870 libpdfium.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B6245000 00000000 00009000 25B29975558839100CC6E366D29212350 libaudioutils.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B624E000 00000000 0001D000 DFED0D6F37875A07335517F4E69925120 libz.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B626C000 00000000 0004E000 66D92DD691765147492F9C21B6AD68960 libharfbuzz_ng.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B62BA000 00000000 00007000 9008C23BFACF1EF1DDF142956BF976490 libusbhost.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B62C1000 00000000 0003A000 2D00674AA1DD3C58C05B175DD18EE6050 libjpeg.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B62FC000 00000000 000AD000 A52E62FD0AC67AE14A01E7E4847F17620 libmedia.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B63A9000 00000000 0017F000 14D5DC468D2218AA5F70C2F6FC6EBBF90 libicui18n.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B6528000 00000000 00123000 0990D8BD31465D945F9282189239AB8F0 libicuuc.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B664F000 00000000 00026000 C4AA0ABF6C41A8583C0E373BD8CA4EE70 libssl.so
08-26 20:29:56.167  4281  3851 W google-breakpad: M B6675000 00000000 0009D000 A14F571CD9F3F8B6362ACC34BB5E42CA0 libcrypto.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B6712000 00000000 00056000 23B95E0161A14BC00A49FE4C0126E1CF0 libsonivox.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B676D000 00000000 00011000 87F28481D7D1980E2971DFAD611952AA0 libselinux.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B677E000 00000000 00008000 4E213F2F80F006F539A0A0DBEC2228870 libhardware_legacy.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B6787000 00000000 00005000 4025C8440BDADD37826842A415EF9BFF0 libhardware.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B678C000 00000000 00006000 0CBDCDD7DFB535EB3876F8035637EAC00 libETC1.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B6792000 00000000 0000F000 A7B07D10AF426644931390FF2ABC2FEC0 libGLESv2.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B67A1000 00000000 0000A000 1B33374FB686F15B59530546D8DB39640 libGLESv1_CM.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B67AB000 00000000 00068000 DAD11DC7527BFB7648299C3DE956986E0 libEGL.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B6816000 00000000 00065000 E94A253EBAA34A7F995352FCEE8DD0D50 libsqlite.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B687C000 00000000 0026E000 71785D4C7316B73D74AB9E39653907830 libskia.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B6AEE000 00000000 0000A000 306A2E96AB94641A8076D9195DA933FF0 libcamera_metadata.so
08-26 20:29:56.168  4281  3851 W google-breakpad: M B6AF8000 00000000 0002D000 7CA8B61C54BAAABF07F3C7847D490E9F0 libcamera_client.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6B25000 00000000 00040000 6C63D1A1ED4626296733EE132307BF6E0 libinputflinger.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6B65000 00000000 0001F000 112B3314840A32B638874B51553126190 libinput.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6B84000 00000000 0005A000 D55348C7DD771E9409BFBF09AB5AAD720 libgui.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6BDE000 00000000 00010000 10F3AFD84F2FA6D8D59A78E2331D8AC50 libui.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6BEE000 00000000 00009000 8AAEFDEA9747BCF61A977E5DDA0D22620 libnetutils.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6BF7000 00000000 00009000 6C034766ACADC7459DB1EE108B8DDDC70 libnativehelper.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6C00000 00000000 00017000 410352CE283FD8305E8A2FD783B3C8160 libexpat.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6C17000 00000000 0002A000 41777DBC877E41A9712DDD4792610E7A0 libandroidfw.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6C41000 00000000 00005000 EC03C38C8A2A3C11A25493EEEE8E58C20 libmemtrack.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6C46000 00000000 0000B000 6AC6874E2835174DF0B2E6A2BB3511ED0 libbacktrace.so
08-26 20:29:56.169  4281  3851 W google-breakpad: M B6C51000 00000000 00022000 771243F4B38A04911D7E2EFFC103E81F0 libm.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6C73000 00000000 00079000 C45DDC3AA3778947F27583335C11C7260 libc.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6CF6000 00000000 0008E000 4F01D021AD7772AE25722B88EF500DF60 libc++.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6D85000 00000000 0002D000 C02C38CB58D679FECB52E59A954B4AAD0 libwilhelm.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6DB2000 00000000 000DC000 ACD6E6927F2247CE8E5F68E6F5579F0E0 libandroid_runtime.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6E93000 00000000 0002E000 1E5AD4B0BC139C0D5814F52EEC059E2E0 libbinder.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6EC1000 00000000 0000A000 F2FDFCED2E85559AC020655D564D0FFC0 liblog.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6ECB000 00000000 0001B000 4E3DF0460B95A69E7A1D4ABE2D8C0A690 libutils.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6EE6000 00000000 00011000 78F0BD9C3BF5DE7183A84BD26875408C0 libcutils.so
08-26 20:29:56.170  4281  3851 W google-breakpad: M B6F23000 00000000 00020000 C98C597B4AE800CFB3F0589DF3EDED980 linker
08-26 20:29:56.170  4281  3851 W google-breakpad: -----END BREAKPAD MICRODUMP-----
08-26 20:29:56.197  3799  3851 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 20:29:56.197  3799  3851 W google-breakpad: Chrome build fingerprint:
08-26 20:29:56.197  3799  3851 W google-breakpad: 0.0.1
08-26 20:29:56.197  3799  3851 W google-breakpad: 19
08-26 20:29:56.197  3799  3851 W google-breakpad: 6ec9b36e-71c4-4d7b-882c-6b145c858100
08-26 20:29:56.197  3799  3851 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 20:29:56.197  3799  3851 E chromium: ### WebView Version 44.0.2403.117 (code 246011700)
--------- beginning of crash
08-26 20:29:56.198  3799  3851 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 3851 (Thread-329)
,08-26 20:29:56.257   372   372 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,08-26 20:29:56.257   372   372 F DEBUG   : Build fingerprint: 'google/shamu/shamu:6.0.1/MOB30M/2862625:user/release-keys'
08-26 20:29:56.257   372   372 F DEBUG   : Revision: '0'
08-26 20:29:56.258   372   372 F DEBUG   : ABI: 'arm'
08-26 20:29:56.258   372   372 F DEBUG   : pid: 3799, tid: 3851, name: Thread-329  >>> com.test.thalitest <<<
08-26 20:29:56.259   372   372 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,08-26 20:29:56.294   372   372 F DEBUG   :     r0 9d108000  r1 00000000  r2 92c0bb64  r3 92c0bbe0
,08-26 20:29:56.295   372   372 F DEBUG   :     r4 92c0bb38  r5 92c0bb8c  r6 9fe9f4e0  r7 92c0bb64
,08-26 20:29:56.295   372   372 F DEBUG   :     r8 90a0ee40  r9 ffffff85  sl 96fb5000  fp 92c0bb5c
08-26 20:29:56.295   372   372 F DEBUG   :     ip 92c0bb20  sp 92c0bb28  lr 943e2978  pc 943e297c  cpsr 200f0010
,08-26 20:29:56.301   372   372 F DEBUG   : 
08-26 20:29:56.301   372   372 F DEBUG   : backtrace:
,08-26 20:29:56.301   372   372 F DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-26 20:29:56.301   372   372 F DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
,08-26 20:29:56.301   372   372 F DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,08-26 20:29:57.065   372   372 F DEBUG   : 
08-26 20:29:57.065   372   372 F DEBUG   : Tombstone written to: /data/tombstones/tombstone_00
08-26 20:29:57.065   372   372 E DEBUG   : AM write failed: Broken pipe
,08-26 20:29:57.066   870   886 I BootReceiver: Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,08-26 20:29:57.072   870  4282 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,08-26 20:29:57.078   870  4282 I ActivityManager: Killing 3696:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 20:29:57.248   870  1967 D GraphicsStats: Buffer count: 2
,08-26 20:29:57.249   870  1315 D WifiService: Client connection lost with reason: 4
,08-26 20:29:57.249   870  1700 I WindowState: WIN DEATH: Window{c59dc92 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 20:29:57.281   388   388 I Zygote  : Process 3799 exited due to signal (11)
,08-26 20:29:57.282   870  1967 I ActivityManager: Process com.test.thalitest (pid 3799) has died
,08-26 20:29:57.328   870   880 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3799 uid 10000
,08-26 20:29:57.329  1869  1869 I Keyboard.Facilitator: onFinishInput()
,08-26 20:30:03.369  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:30:03.371  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:30:03.411  1519  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:30:03.411  1519  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:30:03.411  1519  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:30:03.411  1519  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:30:03.435  3554  4286 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 20:30:03.435  3554  4286 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at blb.a(PG:3937)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at czp.a(PG:18188)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:30:03.435  3554  4286 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	... 12 more
08-26 20:30:03.435  3554  4286 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at fal.a(PG:38)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:30:03.435  3554  4286 E HttpOperation: 	... 14 more
,08-26 20:30:03.484  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:30:03.484  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:30:03.484  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:30:03.484  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:30:03.530  3554  4286 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 20:30:03.530  3554  4286 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at hec.a(PG:42)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at hee.a(PG:102)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at czr.a(PG:65)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at kka.a(PG:108)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at czp.a(PG:19176)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:30:03.530  3554  4286 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	... 15 more
08-26 20:30:03.530  3554  4286 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at fal.a(PG:38)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:30:03.530  3554  4286 E HttpOperation: 	... 17 more
,08-26 20:30:03.531  3554  4286 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 20:30:03.531  3554  4286 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at hec.a(PG:42)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at hee.a(PG:102)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at czr.a(PG:65)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at kka.a(PG:108)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	... 15 more
08-26 20:30:03.531  3554  4286 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at fal.a(PG:38)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 20:30:03.531  3554  4286 E ExperimentLoader: 	... 17 more
,08-26 20:30:03.702   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 246422, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:30:03.767  3038  4288 V KeepSync: Connecting to GoogleApiClient
,08-26 20:30:03.767   870   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 20:30:03.847  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 20:30:03.847  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 20:30:03.847  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:30:03.848  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:30:03.862  1729  4289 V BaseAuthAsyncOperation: access token request failed
,08-26 20:30:03.863  3038  4288 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 20:30:03.917  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 20:30:03.917  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 20:30:03.917  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:30:03.917  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:30:03.937  3038  4288 E KeepSync: IOException
08-26 20:30:03.937  3038  4288 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 20:30:03.937  3038  4288 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:30:03.937  3038  4288 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 20:30:03.937  3038  4288 E KeepSync: 	... 10 more
,08-26 20:30:03.937  3038  4288 W KeepSync: Sync result 2
,08-26 20:30:03.954   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 246563, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:30:24.905   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268252, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:30:34.306  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:30:34.310  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:30:34.357  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 20:30:34.357  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 20:30:34.357  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:30:34.358  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:30:34.380  3554  4292 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 20:30:34.380  3554  4292 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at blb.a(PG:3937)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at czp.a(PG:18188)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:30:34.380  3554  4292 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	... 12 more
08-26 20:30:34.380  3554  4292 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at fal.a(PG:38)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:30:34.380  3554  4292 E HttpOperation: 	... 14 more
,08-26 20:30:34.453  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:30:34.453  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:30:34.453  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:30:34.453  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:30:34.478  3554  4292 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 20:30:34.478  3554  4292 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at hec.a(PG:42)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at hee.a(PG:102)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at czr.a(PG:65)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at kka.a(PG:108)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at czp.a(PG:19176)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:30:34.478  3554  4292 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	... 15 more
08-26 20:30:34.478  3554  4292 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at fal.a(PG:38)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:30:34.478  3554  4292 E HttpOperation: 	... 17 more
,08-26 20:30:34.479  3554  4292 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 20:30:34.479  3554  4292 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at hec.a(PG:42)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at hee.a(PG:102)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at czr.a(PG:65)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at kka.a(PG:108)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	... 15 more
08-26 20:30:34.479  3554  4292 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at fal.a(PG:38)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 20:30:34.479  3554  4292 E ExperimentLoader: 	... 17 more
,08-26 20:30:34.587   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 277068, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:30:40.277   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=283624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:30:57.371  1869  1927 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-26 20:30:57.372  1869  1927 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-26 20:30:57.420  1519  1519 I ConfigService: onCreate
,08-26 20:31:02.508  1519  1519 I ConfigService: onDestroy
,08-26 20:31:04.748  3754  4301 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 20:31:04.785  3754  4302 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 20:31:04.808  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:04.816  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:04.823  3038  4300 V KeepSync: Connecting to GoogleApiClient
08-26 20:31:04.824   870  1700 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 20:31:04.869  1519  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-26 20:31:04.870  1519  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:31:04.870  1519  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:04.870  1519  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:04.934  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:04.936  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:05.009  1519  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-26 20:31:05.009  1519  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 20:31:05.009  1519  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:05.009  1519  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:05.037  1519  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 20:31:05.037  1519  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 20:31:05.038  1519  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:05.038  1519  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:05.065  3754  4302 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-26 20:31:05.066  3754  4301 E BooksSync: Soft error
08-26 20:31:05.066  3754  4301 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:31:05.066  3754  4301 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:31:05.066  1729  4304 V BaseAuthAsyncOperation: access token request failed
,08-26 20:31:05.067  3038  4300 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-26 20:31:05.066  3754  4301 E BooksSync: Sync error
08-26 20:31:05.066  3754  4301 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:31:05.066  3754  4301 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-26 20:31:05.069  3754  4301 I BooksSync: Finished books sync
08-26 20:31:05.074   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 283943, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:31:05.116  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-26 20:31:05.116  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 20:31:05.116  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:05.116  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:05.130  3038  4300 E KeepSync: IOException
08-26 20:31:05.130  3038  4300 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 20:31:05.130  3038  4300 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:31:05.130  3038  4300 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 20:31:05.130  3038  4300 E KeepSync: 	... 10 more
08-26 20:31:05.130  3038  4300 W KeepSync: Sync result 2
,08-26 20:31:05.135   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 279240, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:31:21.333   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324679, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:31:35.444  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:35.445  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:35.472  1519  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:31:35.472  1519  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:31:35.473  1519  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:35.473  1519  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:35.489  3554  4307 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 20:31:35.489  3554  4307 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at blb.a(PG:3937)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at czp.a(PG:18188)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:31:35.489  3554  4307 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	... 12 more
08-26 20:31:35.489  3554  4307 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at fal.a(PG:38)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:31:35.489  3554  4307 E HttpOperation: 	... 14 more
,08-26 20:31:35.586  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:31:35.587  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:31:35.587  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:35.587  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:35.615  3554  4307 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 20:31:35.615  3554  4307 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at hec.a(PG:42)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at hee.a(PG:102)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at czr.a(PG:65)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at kka.a(PG:108)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at czp.a(PG:19176)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:31:35.615  3554  4307 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	... 15 more
08-26 20:31:35.615  3554  4307 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at fal.a(PG:38)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:31:35.615  3554  4307 E HttpOperation: 	... 17 more
,08-26 20:31:35.616  3554  4307 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 20:31:35.616  3554  4307 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at hec.a(PG:42)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at hee.a(PG:102)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at czr.a(PG:65)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at kka.a(PG:108)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	... 15 more
08-26 20:31:35.616  3554  4307 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at fal.a(PG:38)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 20:31:35.616  3554  4307 E ExperimentLoader: 	... 17 more
,08-26 20:31:35.701   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 337970, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:31:36.704   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:31:38.511  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:31:38.544  1519  2194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-26 20:31:38.544  1519  2194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-26 20:31:38.544  1519  2194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:31:38.544  1519  2194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:31:38.574  1519  2194 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 20:31:38.574  1519  2194 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 20:31:38.574  1519  2194 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 20:31:38.574  1519  2194 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-26 20:31:38.574  1519  2194 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-26 20:31:38.574  1519  2194 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-26 20:31:38.574  1519  2194 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-26 20:31:38.579  3516  3546 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 20:31:38.579  3516  3546 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-26 20:31:38.579  3516  3546 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-26 20:31:38.579  3516  3546 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-26 20:31:38.579  3516  3546 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-26 20:31:38.579  3516  3546 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-26 20:31:38.579  3516  3546 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-26 20:31:43.610   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=346957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 20:31:54.304   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=357650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:32:05.859  3754  4314 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 20:32:05.887  3754  4315 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 20:32:05.915  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:32:05.918  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:32:05.970  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-26 20:32:05.970  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 20:32:05.971  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:32:05.971  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:32:06.020  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:32:06.024  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:32:06.072  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-26 20:32:06.073  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 20:32:06.073  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:32:06.073  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:32:06.102  3754  4315 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-26 20:32:06.103  3754  4314 E BooksSync: Soft error
08-26 20:32:06.103  3754  4314 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:32:06.103  3754  4314 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:32:06.104  3754  4314 E BooksSync: Sync error
08-26 20:32:06.104  3754  4314 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:32:06.104  3754  4314 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:32:06.104  3754  4314 I BooksSync: Finished books sync
,08-26 20:32:06.120   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 339372, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:32:36.411  3038  4317 V KeepSync: Connecting to GoogleApiClient
08-26 20:32:36.412   870  1976 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 20:32:36.478  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:32:36.480  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:32:36.526  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-26 20:32:36.526  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 20:32:36.526  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:32:36.526  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:32:36.552  1729  4318 V BaseAuthAsyncOperation: access token request failed
08-26 20:32:36.553  3038  4317 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 20:32:36.632  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 20:32:36.633  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 20:32:36.633  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:32:36.633  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:32:36.674  3038  4317 E KeepSync: IOException
08-26 20:32:36.674  3038  4317 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 20:32:36.674  3038  4317 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:32:36.674  3038  4317 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 20:32:36.674  3038  4317 E KeepSync: 	... 10 more
08-26 20:32:36.674  3038  4317 W KeepSync: Sync result 2
,08-26 20:32:36.690   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 372358, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:32:47.237   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:33:02.572   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=425918, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:33:04.940  1519  2069 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 20:33:08.199  3754  4320 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 20:33:08.238  3754  4321 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 20:33:08.252  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:33:08.254  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:33:08.287  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 20:33:08.287  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:33:08.288  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 20:33:08.288  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:33:08.318  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:33:08.320  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:33:08.350  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 20:33:08.351  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:33:08.351  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:33:08.351  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:33:08.367  3754  4321 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-26 20:33:08.368  3754  4320 E BooksSync: Soft error
08-26 20:33:08.368  3754  4320 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:33:08.368  3754  4320 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:33:08.369  3754  4320 E BooksSync: Sync error
08-26 20:33:08.369  3754  4320 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:33:08.369  3754  4320 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:33:08.369  3754  4320 I BooksSync: Finished books sync
,08-26 20:33:08.382   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 431369, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:33:32.852   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=456199, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:33:38.697  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:33:38.699  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:33:38.726  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 20:33:38.726  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:33:38.726  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:33:38.726  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:33:38.743  3554  4325 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 20:33:38.743  3554  4325 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at blb.a(PG:3937)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at czp.a(PG:18188)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	,at czp.a(PG:9081)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:33:38.743  3554  4325 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	... 12 more
08-26 20:33:38.743  3554  4325 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at fal.a(PG:38)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:33:38.743  3554  4325 E HttpOperation: 	... 14 more
,08-26 20:33:38.797  1519  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 20:33:38.797  1519  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 20:33:38.797  1519  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:33:38.798  1519  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:33:38.835  3554  4325 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 20:33:38.835  3554  4325 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jdm.a(PG:82)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jcs.o(PG:406)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jcn.a(PG:1379)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jcs.i(PG:143)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at hec.a(PG:42)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at hee.a(PG:102)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at czr.a(PG:65)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at kka.a(PG:108)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at czp.a(PG:19176)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at czp.a(PG:9081)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at czq.run(PG:1686)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:33:38.835  3554  4325 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jdj.a(PG:4091)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jdj.a(PG:1125)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jdm.a(PG:77)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	... 15 more
08-26 20:33:38.835  3554  4325 E HttpOperation: Caused by: faj: BadAuthentication
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at fal.a(PG:38)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	at jdj.a(PG:4089)
08-26 20:33:38.835  3554  4325 E HttpOperation: 	... 17 more
,08-26 20:33:38.835  3554  4325 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 20:33:38.835  3554  4325 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at hec.a(PG:42)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at hee.a(PG:102)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at czr.a(PG:65)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at kka.a(PG:108)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	... 15 more
08-26 20:33:38.835  3554  4325 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at fal.a(PG:38)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 20:33:38.835  3554  4325 E ExperimentLoader: 	... 17 more
,08-26 20:33:38.938   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 459120, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:33:48.224   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=471570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:34:32.664   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=516011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:34:44.562  3038  4331 V KeepSync: Connecting to GoogleApiClient
08-26 20:34:44.563   870  1700 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 20:34:44.628  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:34:44.635  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:34:44.676  1519  2194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-26 20:34:44.676  1519  2194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 20:34:44.676  1519  2194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:34:44.676  1519  2194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:34:44.707  1729  4332 V BaseAuthAsyncOperation: access token request failed
08-26 20:34:44.709  3038  4331 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 20:34:44.786  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 20:34:44.786  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 20:34:44.786  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:34:44.787  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:34:44.818  3038  4331 E KeepSync: IOException
08-26 20:34:44.818  3038  4331 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 20:34:44.818  3038  4331 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 20:34:44.818  3038  4331 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 20:34:44.818  3038  4331 E KeepSync: 	... 10 more
,08-26 20:34:44.818  3038  4331 W KeepSync: Sync result 2
,08-26 20:34:44.830   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 527790, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:34:48.011   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=531357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:35:03.053   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=546399, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:35:15.025  3754  4334 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 20:35:15.070  3754  4335 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 20:35:15.097  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:35:15.104  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:35:15.186  1519  2194 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 20:35:15.187  1519  2194 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:35:15.187  1519  2194 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:35:15.187  1519  2194 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:35:15.274  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:35:15.284  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:35:15.324  1519  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 20:35:15.325  1519  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-26 20:35:15.325  1519  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 20:35:15.325  1519  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:35:15.356  3754  4335 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-26 20:35:15.357  3754  4334 E BooksSync: Soft error
08-26 20:35:15.357  3754  4334 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:35:15.357  3754  4334 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:35:15.357  3754  4334 E BooksSync: Sync error
08-26 20:35:15.357  3754  4334 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 20:35:15.357  3754  4334 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-26 20:35:15.358  3754  4334 I BooksSync: Finished books sync
,08-26 20:35:15.372   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 555533, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 20:35:18.411   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=561757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:35:33.454   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=576801, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:35:48.811   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=592157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:36:43.986   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647333, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 20:36:59.319   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=662665, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 20:46:14.666   870   882 I UsageStatsService: User[0] Flushing usage stats to disk
,08-26 20:51:06.913  1729  4383 I EventLogService: Opted in for usage reporting
,08-26 20:51:06.914  1729  4383 I EventLogService: Aggregate from 1472234585621 (log), 1472234585621 (data)
,08-26 20:51:06.949  1729  4383 W EventLogAggregator: Unknown tag: snet_gcore
08-26 20:51:06.950  1729  4383 W EventLogAggregator: Unknown tag: snet_launch_service
,08-26 20:51:07.040  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:51:07.043  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 20:51:07.089  1729  4383 I ServiceDumpSys: dumping service [account]
,08-26 20:51:07.109  4051  4385 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 20:51:07.147  1519  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-26 20:51:07.147  1519  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-26 20:51:07.147  1519  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 20:51:07.147  1519  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-26 20:51:07.161  4051  4385 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-26 20:51:11.877   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 20:51:19.691   870  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1523037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-26 20:51:27.768  4386  4386 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 20:51:27.773  4386  4386 D AndroidRuntime: CheckJNI is OFF
08-26 20:51:27.808  4386  4386 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 20:51:27.850  4386  4386 I Radio-JNI: register_android_hardware_Radio DONE
08-26 20:51:27.870  4386  4386 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 20:51:27.891   870   883 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 20:51:28.055   870   893 W PackageSettings: Skipping PackageSetting{cb33a47 com.example.hello/10273} due to missing metadata
08-26 20:51:28.094   870   893 I art     : Starting a blocking GC Explicit
08-26 20:51:28.172   870   893 I art     : Explicit concurrent mark sweep GC freed 42616(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 798us total 76.689ms
08-26 20:51:28.195   870   893 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-26 20:51:28.202  4386  4386 I art     : System.exit called, status: 0
08-26 20:51:28.202  4386  4386 I AndroidRuntime: VM exiting with result code 0.
08-26 20:51:28.214   870   893 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-26 20:51:28.241  4184  4184 D BluetoothMapAppObserver: onReceive
08-26 20:51:28.241  4184  4184 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-26 20:51:28.244   870  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 20:51:28.245  1900  2264 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 20:51:28.248  1869  1869 I Keyboard.Facilitator: resetDictionaries() : en_US
08-26 20:51:28.248  3644  3644 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-26 20:51:28.295  1944  1944 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-26 20:51:28.296   870  1976 I ActivityManager: Start proc 4402:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-26 20:51:28.305   870  1310 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-26 20:51:28.313  1869  4398 I Keyboard.Facilitator.DecoderInitializer: run()
08-26 20:51:28.315  1869  4398 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-26 20:51:28.316  1869  4398 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-26 20:51:28.316  1869  4398 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-26 20:51:28.316  1869  4398 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-26 20:51:28.316  1869  4398 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-26 20:51:28.316  1869  4398 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-26 20:51:28.317  1869  4398 I Decoder : createOrResetDecoder
08-26 20:51:28.326  1519  1519 I ConfigService: onCreate
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 20:51:28.337  1519  4413 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 20:51:28.338  1519  4413 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-26 20:51:28.341  1519  4413 W SQLiteOpenHelper: Opened config.db in read-only mode
08-26 20:51:28.345  4402  4402 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-26 20:51:28.355   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 20:51:28.361  1869  4398 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-26 20:51:28.367  1957  2039 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-26 20:51:28.368   870   882 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-26 20:51:28.368   870   882 E PackageManager: Failed to write settings, restoring backup
08-26 20:51:28.368   870   882 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 20:51:28.368   870   882 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 20:51:28.368   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 20:51:28.368   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 20:51:28.368   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 20:51:28.368   870   882 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:51:28.368   870   882 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.368   870   882 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 20:51:28.373   870   883 E DropBoxManagerService: Can't write: system_server_wtf
08-26 20:51:28.373   870   883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 20:51:28.373   870   883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 20:51:28.373   870   883 E DropBoxManagerService: 	... 13 more
08-26 20:51:28.380   870  1700 I ActivityManager: Start proc 4416:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-26 20:51:28.380  1957  2039 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 20:51:28.380  1957  2039 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1957
08-26 20:51:28.380  1957  2039 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.380  1957  2039 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 20:51:28.382   870  1976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 20:51:28.383   870  4422 E DropBoxManagerService: Can't write: system_app_crash
08-26 20:51:28.383   870  4422 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 20:51:28.383   870  4422 E DropBoxManagerService: 	... 5 more
08-26 20:51:28.386  1957  2039 I Process : Sending signal. PID: 1957 SIG: 9
08-26 20:51:28.411  1869  4398 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-26 20:51:28.413  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 20:51:28.413  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-26 20:51:28.415  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-26 20:51:28.415  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-26 20:51:28.415  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 20:51:28.415  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 20:51:28.416  1869  4398 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 20:51:28.416  1869  4398 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 20:51:28.416  1869  4398 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 20:51:28.417  1869  4398 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 20:51:28.417  1869  4398 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 20:51:28.417  1869  4398 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-26 20:51:28.435  4402  4402 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-26 20:51:28.450  4402  4436 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-26 20:51:28.460   870  2041 I ActivityManager: Start proc 4437:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-26 20:51:28.465   870  1967 D GraphicsStats: Buffer count: 1
08-26 20:51:28.465   870  1976 I WindowState: WIN DEATH: Window{52a6ec u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.476  4402  4433 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 20:51:28.476   870  1967 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1957) has died
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.476  4402  4433 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 20:51:28.477   870  1967 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-26 20:51:28.478   870  1967 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-26 20:51:28.504   870   883 I ActivityManager: Start proc 4449:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:51:28.551  4449  4449 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:51:28.552  4449  4449 D AndroidRuntime: Shutting down VM
08-26 20:51:28.556  4449  4449 E AndroidRuntime: FATAL EXCEPTION: main
08-26 20:51:28.556  4449  4449 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4449
08-26 20:51:28.556  4449  4449 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 20:51:28.556  4449  4449 E AndroidRuntime: 	... 10 more
08-26 20:51:28.558   870  1976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 20:51:28.560  4449  4449 I Process : Sending signal. PID: 4449 SIG: 9
08-26 20:51:28.569   870  4461 E DropBoxManagerService: Can't write: system_app_crash
08-26 20:51:28.569   870  4461 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 20:51:28.569   870  4461 E DropBoxManagerService: 	... 5 more
08-26 20:51:28.606  4437  4437 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-26 20:51:28.620   870  1700 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4449) has died
08-26 20:51:28.622   870  1700 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-26 20:51:28.654   870   883 I ActivityManager: Start proc 4466:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 20:51:28.673  1729  4463 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-26 20:51:28.675  1729  4463 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-26 20:51:28.681  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-26 20:51:28.684  1519  1519 D AndroidRuntime: Shutting down VM
08-26 20:51:28.684  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
08-26 20:51:28.684  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
08-26 20:51:28.684  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 20:51:28.684  1519  1519 E AndroidRuntime: 	... 8 more
08-26 20:51:28.685  1729  4463 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-26 20:51:28.688   870  4479 E DropBoxManagerService: Can't write: system_app_crash
08-26 20:51:28.688   870  4479 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 20:51:28.688   870  4479 E DropBoxManagerService: 	... 5 more
08-26 20:51:28.691  1729  4463 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-26 20:51:28.692  1519  1519 I Process : Sending signal. PID: 1519 SIG: 9

```
