#### Test 82914073126c10a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 15:29:23.211   873  1850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:29:24.080  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 15:29:24.090  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 15:29:24.093  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 15:29:24.134  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 15:29:24.134  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 15:29:24.134  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:29:24.134  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 15:29:24.163  3490  3490 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 15:29:24.164  3490  3490 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 15:29:24.164  3490  3490 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-07 15:29:24.517  3729  3729 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 15:29:24.521  3729  3729 D AndroidRuntime: CheckJNI is OFF
09-07 15:29:24.557  3729  3729 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 15:29:24.600  3729  3729 I Radio-JNI: register_android_hardware_Radio DONE
09-07 15:29:24.620  3729  3729 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 15:29:24.624   873  1693 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 15:29:24.655  2030  2425 W SearchService: Abort, client detached.
09-07 15:29:24.676  3729  3729 D AndroidRuntime: Shutting down VM
09-07 15:29:24.678  2030  2362 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@119352f
09-07 15:29:24.678  2030  2371 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 15:29:24.678  2030  2030 I HotwordDetector: Closing mic
09-07 15:29:24.698   873   884 I ActivityManager: Start proc 3738:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 15:29:24.741   376  2373 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 15:29:24.743   376  2373 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 15:29:24.750   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 15:29:24.751  2030  2370 I MicroRecognitionRnrImpl: Detection finished
09-07 15:29:24.752  2030  2368 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 15:29:24.786  3738  3738 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 15:29:24.817  3738  3738 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 15:29:24.832  3738  3738 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 491-499)
09-07 15:29:24.832  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 15:29:24.853  3738  3738 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56965e0}
09-07 15:29:24.856  3738  3738 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 15:29:24.857  3738  3738 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 15:29:24.880  3738  3738 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 15:29:24.882  3738  3738 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 15:29:24.910  3738  3738 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 15:29:24.925  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 15:29:24.925  3738  3738 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 15:29:24.926  3738  3738 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 15:29:24.926  3738  3738 I Adreno  : Build Date                       : 10/20/15
09-07 15:29:24.926  3738  3738 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 15:29:24.926  3738  3738 I Adreno  : Local Branch                     : M14
09-07 15:29:24.926  3738  3738 I Adreno  : Remote Branch                    : 
09-07 15:29:24.926  3738  3738 I Adreno  : Remote Branch                    : 
09-07 15:29:24.926  3738  3738 I Adreno  : Reconstruct Branch               : 
,09-07 15:29:25.013   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f66aa5f:true
,09-07 15:29:25.065  3738  3738 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 15:29:25.085  3738  3738 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 15:29:25.170  3738  3777 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 15:29:25.179  3738  3763 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 15:29:25.214  3738  3777 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 15:29:25.277   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +599ms
,09-07 15:29:25.283  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-07 15:29:25.389  3738  3738 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3738
,09-07 15:29:25.515   873  1994 I ActivityManager: Killing 3192:com.google.android.gm/u0a78 (adj 15): empty #17
,09-07 15:29:25.552   873  1994 I ActivityManager: Killing 3079:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-07 15:29:25.639  3738  3738 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 15:29:25.812  3738  3779 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1701054160
,09-07 15:29:25.823  3738  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 15:29:25.823  3738  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 15:29:25.823  3738  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 15:29:25.823  3738  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 15:29:25.823  3738  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 15:29:25.823  3738  3779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f03564 added. We now have 1 listener(s)
,09-07 15:29:25.828  3738  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 15:29:25.835  3738  3779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:29:25.838  3738  3779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:29:25.839  3738  3779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 15:29:25.851  3738  3779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e35793 added. We now have 1 listener(s)
09-07 15:29:25.851  3738  3779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:25.855   873  1304 D WifiService: New client listening to asynchronous messages
09-07 15:29:25.856  3738  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:29:25.857  3738  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 15:29:25.857  3738  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 15:29:25.857  3738  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 15:29:25.857  3738  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 15:29:25.859  3738  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:25.859  3738  3779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 15:29:25.873  3738  3779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
,09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:25.874  3738  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:25.874  3738  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-07 15:29:25.874  3738  3779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:25.876  3738  3779 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 15:29:25.947  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:25.954  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:25.956  3738  3738 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 15:29:26.432   873  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 15:29:26.734  3738  3787 W jxcore-log: Initializing JXcore engine
,09-07 15:29:26.734  3738  3787 W jxcore-log: JXcore engine is ready
,09-07 15:29:26.776  3787  3787 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 15:29:26.776  3787  3787 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10111]" dev="sockfs" ino=10111 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 15:29:26.776  3787  3787 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 15:29:26.776  3787  3787 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24009]" dev="sockfs" ino=24009 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 15:29:26.790  3738  3787 W jxcore-log: Starting JXcore engine
,09-07 15:29:26.890  3738  3787 W jxcore-log: Platform android
09-07 15:29:26.890  3738  3787 W jxcore-log: 
,09-07 15:29:26.890  3738  3787 W jxcore-log: Process ARCH arm
09-07 15:29:26.890  3738  3787 W jxcore-log: 
,09-07 15:29:27.136  3738  3787 I jxcore-log: JXcore Cordova bridge is ready!
09-07 15:29:27.136  3738  3787 I jxcore-log: 
,09-07 15:29:27.136  3738  3787 W jxcore-log: JXcore engine is started
,09-07 15:29:27.145  3738  3779 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 15:29:27.148  3738  3738 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 15:29:32.179   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 15:29:32.931  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:32.939  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:33.010  1510  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:29:33.011  1510  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 15:29:33.011  1510  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:29:33.011  1510  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:33.058  2988  3795 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 15:29:33.058  2988  3795 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at blb.a(PG:3937)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at czp.a(PG:18188)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:29:33.058  2988  3795 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	... 12 more
09-07 15:29:33.058  2988  3795 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at fal.a(PG:38)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:29:33.058  2988  3795 E HttpOperation: 	... 14 more
,09-07 15:29:33.141  1510  2277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:29:33.141  1510  2277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:29:33.141  1510  2277 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:29:33.142  1510  2277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:33.164  2988  3795 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 15:29:33.164  2988  3795 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at hec.a(PG:42)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at hee.a(PG:102)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at czr.a(PG:65)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at kka.a(PG:108)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at czp.a(PG:19176)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:29:33.164  2988  3795 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	... 15 more
09-07 15:29:33.164  2988  3795 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at fal.a(PG:38)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:29:33.164  2988  3795 E HttpOperation: 	... 17 more
,09-07 15:29:33.165  2988  3795 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 15:29:33.165  2988  3795 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at hec.a(PG:42)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at hee.a(PG:102)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at czr.a(PG:65)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at kka.a(PG:108)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	... 15 more
09-07 15:29:33.165  2988  3795 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at fal.a(PG:38)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 15:29:33.165  2988  3795 E ExperimentLoader: 	... 17 more
,09-07 15:29:33.322   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 128375, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:29:35.215   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 15:29:36.998  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 15:29:36.998  3738  3787 I jxcore-log: 
,09-07 15:29:37.000  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 15:29:37.000  3738  3787 I jxcore-log: 
,09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.012  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:37.017  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:37.019  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 15:29:37.019  3738  3787 I jxcore-log: 
,09-07 15:29:37.021  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 15:29:37.021  3738  3787 I jxcore-log: 
,09-07 15:29:37.515  3738  3787 D executeNativeTests: Running unit tests
,09-07 15:29:37.573  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:29:37.573  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 added. We now have 2 listener(s)
09-07 15:29:37.574  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 15:29:37.574  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:29:37.574  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:37.574  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:37.574  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d added. We now have 2 listener(s)
09-07 15:29:37.574  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:37.575  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:29:37.579  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.594  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:37.600  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:37.601  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:37.603  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:37.604  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:37.608  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 15:29:37.608  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:29:37.608  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 15:29:37.621  3738  3787 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 15:29:37.622  3738  3787 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 15:29:37.622  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 15:29:37.623  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:37.623  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:37.624  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.625  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.626  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.626  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.627  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.627  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:37.627  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:37.628  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 removed from the list
09-07 15:29:37.628  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.628  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d removed from the list
09-07 15:29:37.628  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.629  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.630  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.630  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.631  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.631  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.631  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.631  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.633  3738  3787 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 15:29:37.633  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.633  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.633  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.634  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.634  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.634  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.634  3738  3787 E org.thaliproject.p2p.btconnectorlib.Conne,ctionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.634  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.634  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.634  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.634  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.634  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.634  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.634  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.635  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.635  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.635  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.635  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 15:29:37.641  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 15:29:37.642  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 15:29:37.642  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.642  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.642  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.643  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.643  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.643  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.643  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.643  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.643  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.643  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.643  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.643  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.643  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.643  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.644  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.644  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.644  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.644  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.645  3738  3787 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:29:37.646  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.654  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:37.656  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.656  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:37.658  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:37.658  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:37.658  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:29:37.659  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:37.659  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:37.659  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:29:37.660  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:37.667  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 15:29:37.667  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:29:37.677  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 15:29:37.681  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 15:29:37.682  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:29:37.685  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 15:29:37.690  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 15:29:37.691  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 15:29:37.691  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:37.691  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 15:29:37.692  3738  3787 D BluetoothAdapter: STATE_ON
09-07 15:29:37.696  2676  2689 D BtGatt.GattService: registerClient() - UUID=449b37e3-3a58-4f79-858a-78869417324b
09-07 15:29:37.698  2676  2695 D BtGatt.GattService: onClientRegistered() - UUID=449b37e3-3a58-4f79-858a-78869417324b, clientIf=5
09-07 15:29:37.699  3738  3749 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 15:29:37.700  2676  2805 D BtGatt.GattService: start scan with filters
09-07 15:29:37.704  2676  2698 D BtGatt.ScanManager: handling starting scan
09-07 15:29:37.704  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 15:29:37.705  2676  2698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
09-07 15:29:37.705  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:37.705  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:37.706  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 15:29:37.708  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:29:37.708  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 15:29:37.709  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:29:37.709  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 15:29:37.711  3738  3787 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 15:29:37.716  2676  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 15:29:37.716  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.717  2676  2698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 15:29:37.717  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.720  3738  3787 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 15:29:37.720  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:37.720  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 15:29:37.720  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.721  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 15:29:37.721  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:37.721  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:37.721  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:37.721  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:29:37.723  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 15:29:37.724  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:29:37.724  3738  3787 D BluetoothAdapter: STATE_ON
09-07 15:29:37.724  2676  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 15:29:37.725  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.725  2676  2689 D BtGatt.GattService: stopScan() - queue size =1
09-07 15:29:37.725  2676  2805 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 15:29:37.725  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:37.725  2676  2698 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:29:37.726  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 15:29:37.726  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:37.726  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 15:29:37.726  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 15:29:37.726  2676  2698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 15:29:37.731  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:37.732  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 15:29:37.732  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 15:29:37.733  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 15:29:37.733  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:37.735  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:37.735  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.735  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:37.735  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.735  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:37.735  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.735  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.735  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.735  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.735  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:29:37.735  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:37.736  3738  3787 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:29:37.738  2676  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 15:29:37.738  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.739  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:37.746  2676  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 15:29:37.747  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.750  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:37.752  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:37.753  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:37.753  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 15:29:37.753  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 15:29:37.753  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:37.753  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:37.753  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 15:29:37.756  2676  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 15:29:37.756  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.756  2676  2698 D BtGatt.ScanManager: stopping BLe Batch
09-07 15:29:37.756  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 15:29:37.756  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:29:37.758  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:37.762  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:29:37.763  2676  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 15:29:37.763  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.763  2676  2698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 15:29:37.763  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:37.764  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 15:29:37.764  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:29:37.768  2676  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 15:29:37.768  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.770  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:29:37.770  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:37.771  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:29:37.771  3738  3787 D BluetoothAdapter: STATE_ON
,09-07 15:29:37.773  2676  2813 D BtGatt.GattService: registerClient() - UUID=79e1d719-abe4-4b1a-8a50-901cf43baeb6
,09-07 15:29:37.774  2676  2695 D BtGatt.GattService: onClientRegistered() - UUID=79e1d719-abe4-4b1a-8a50-901cf43baeb6, clientIf=5
09-07 15:29:37.774  3738  3749 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 15:29:37.776  2676  2805 D BtGatt.GattService: start scan with filters
,09-07 15:29:37.779  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 15:29:37.779  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:37.780  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:37.780  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-07 15:29:37.780  2676  2698 D BtGatt.ScanManager: handling starting scan
,09-07 15:29:37.781  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:29:37.781  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 15:29:37.782  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:37.782  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:29:37.786  2676  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 15:29:37.786  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.787  2676  2698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 15:29:37.788  3738  3787 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 15:29:37.792  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.792  3738  3787 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 15:29:37.792  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:37.792  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 15:29:37.792  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.792  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:37.792  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:37.792  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:37.792  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:37.792  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:29:37.792  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:37.793  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:29:37.793  3738  3787 D BluetoothAdapter: STATE_ON
09-07 15:29:37.793  2676  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 15:29:37.793  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.793  2676  2805 D BtGatt.GattService: stopScan() - queue size =1
09-07 15:29:37.793  2676  2698 D BtGatt.ScanManager: Starting BLE batch scan
09-07 15:29:37.794  2676  2687 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 15:29:37.794  2676  2698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 15:29:37.794  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:37.794  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:29:37.794  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:37.794  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:37.794  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 15:29:37.795  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:37.795  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 15:29:37.795  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:37.795  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:29:37.795  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:37.797  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.797  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:37.797  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.797  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:37.797  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:37.797  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.797  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.797  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:37.797  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.798  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:37.798  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.799  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.799  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.800  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.800  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.800  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.800  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.801  3738  3787 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:29:37.802  2676  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 15:29:37.802  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.804  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:37.809  2676  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 15:29:37.810  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.811  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:37.813  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.813  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:37.813  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:37.813  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:29:37.813  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 15:29:37.813  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:37.814  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:29:37.818  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 15:29:37.818  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:29:37.819  2676  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 15:29:37.819  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.819  2676  2698 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:29:37.819  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:37.824  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:29:37.824  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:37.825  2676  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 15:29:37.825  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.825  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 15:29:37.825  2676  2698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 15:29:37.825  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:29:37.831  2676  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 15:29:37.831  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.833  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 15:29:37.833  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:37.833  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:29:37.835  3738  3787 D BluetoothAdapter: STATE_ON
,09-07 15:29:37.837  2676  2687 D BtGatt.GattService: registerClient() - UUID=7f54d6b5-dd36-4f1d-8434-5357bf60d5fa
,09-07 15:29:37.838  2676  2695 D BtGatt.GattService: onClientRegistered() - UUID=7f54d6b5-dd36-4f1d-8434-5357bf60d5fa, clientIf=5
,09-07 15:29:37.838  3738  3750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 15:29:37.839  2676  2689 D BtGatt.GattService: start scan with filters
,09-07 15:29:37.845  2676  2698 D BtGatt.ScanManager: handling starting scan
09-07 15:29:37.845  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 15:29:37.845  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:37.845  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:37.845  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 15:29:37.848  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:37.848  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:37.848  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:29:37.850  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:29:37.854  3738  3787 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 15:29:37.855  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:37.855  3738  3787 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 15:29:37.855  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
09-07 15:29:37.855  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 15:29:37.855  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.855  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:37.855  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:37.855  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 15:29:37.855  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:37.855  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:29:37.855  2676  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 15:29:37.856  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.856  2676  2698 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
09-07 15:29:37.856  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:37.859  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,09-07 15:29:37.860  3738  3787 D BluetoothAdapter: STATE_ON
09-07 15:29:37.863  2676  2689 D BtGatt.GattService: stopScan() - queue size =1
,09-07 15:29:37.864  2676  2805 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 15:29:37.865  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:37.865  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:29:37.865  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:37.865  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:37.865  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 15:29:37.867  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:37.867  2676  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 15:29:37.867  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:29:37.867  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.867  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:37.867  2676  2698 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:29:37.868  2676  2698 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 15:29:37.868  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:29:37.869  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:37.871  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:37.871  3738  3787 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 15:29:37.871  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-07 15:29:37.872  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:37.872  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.872  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-07 15:29:37.872  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.872  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-07 15:29:37.872  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:29:37.873  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.873  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.874  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.874  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:37.874  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:37.874  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.874  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.874  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.875  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:37.875  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.875  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.875  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.876  3738  3787 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 15:29:37.876  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.877  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-07 15:29:37.877  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.877  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:37.877  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.877  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.878  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
,09-07 15:29:37.878  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.878  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list,
09-07 15:29:37.878  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:37.878  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.878  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.878  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.878  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.880  2676  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 15:29:37.880  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.880  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:37.880  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.880  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.881  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.881  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 15:29:37.882  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:37.882  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.882  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,09-07 15:29:37.882  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:37.882  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-07 15:29:37.882  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.882  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list,
,09-07 15:29:37.882  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.882  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.882  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:37.882  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.883  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.883  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.883  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.884  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:37.884  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.884  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.884  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.885  3738  3787 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-07 15:29:37.885  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.885  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.885  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-07 15:29:37.885  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.885  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.885  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.885  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
,09-07 15:29:37.885  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.885  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.885  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:37.885  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.885  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.885  2676  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 15:29:37.886  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:29:37.885  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.886  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 15:29:37.887  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:37.887  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 15:29:37.888  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.888  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
,09-07 15:29:37.888  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-07 15:29:37.888  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.889  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:37.889  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 15:29:37.889  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:37.889  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.889  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.889  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
,09-07 15:29:37.889  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.889  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.889  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:37.889  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.889  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.889  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:37.890  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:37.891  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.891  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.891  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.891  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.891  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:29:37.892  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:29:37.892  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:29:37.892  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:37.892  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:29:37.892  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 15:29:37.892  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.892  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.892  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.892  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.892  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.893  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.893  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.893  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.893  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.893  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.893  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.893  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.893  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.893  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.895  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.897  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.897  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:37.897  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.898  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:29:37.898  3738  3787 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 15:29:37.898  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 15:29:37.904  2676  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 15:29:37.904  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.904  2676  2698 D BtGatt.ScanManager: stopping BLe Batch
09-07 15:29:37.906  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 15:29:37.906  3738  3787 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 15:29:37.906  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 15:29:37.907  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 15:29:37.908  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-07 15:29:37.908  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 15:29:37.908  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 15:29:37.908  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 15:29:37.908  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 15:29:37.908  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 15:29:37.908  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 15:29:37.908  3738  3787 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:29:37.909  3738  3787 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 15:29:37.909  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 15:29:37.909  3738  3787 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:29:37.909  3738  3787 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 15:29:37.909  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:29:37.909  3738  3787 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:29:37.909  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 15:29:37.914  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 15:29:37.914  2676  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 15:29:37.914  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.914  2676  2698 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 15:29:37.915  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 15:29:37.915  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 15:29:37.915  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 15:29:37.915  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 15:29:37.915  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 15:29:37.916  3738  3787 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:29:37.916  3738  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 381)
09-07 15:29:37.916  3738  3787 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 15:29:37.917  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:37.917  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.917  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.917  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.917  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.917  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.917  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 15:29:37.918  3738  3801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:29:37.919  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
,09-07 15:29:37.919  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.919  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.919  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.919  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.919  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.919  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.920  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.921  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.921  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.921  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.921  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.922  3738  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 381
09-07 15:29:37.922  3738  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 381)
09-07 15:29:37.922  3738  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 381)
09-07 15:29:37.922  2676  2802 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-07 15:29:37.922  3738  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 381)
09-07 15:29:37.923  3738  3787 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 15:29:37.924  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.924  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.924  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.924  2676  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 15:29:37.924  2676  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:29:37.925  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.925  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.925  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.925  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.925  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.925  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
0,9-07 15:29:37.925  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.925  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.926  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.926  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.926  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.926  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.926  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.926  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.926  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.927  3738  3787 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 15:29:37.927  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.927  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.927  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.927  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.927  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.927  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.928  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.928  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.928  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.928  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.928  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.928  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.928  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.928  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.928  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.928  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.929  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.929  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.929  3738  3787 D io.jxco,re.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 15:29:37.929  3738  3787 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 15:29:37.929  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:29:37.929  3738  3787 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 15:29:37.929  3738  3787 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 15:29:37.929  3738  3787 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 15:29:37.929  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:29:37.929  3738  3787 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 15:29:37.930  3738  3787 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 15:29:37.930  3738  3787 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 15:29:37.930  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:29:37.930  3738  3787 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 15:29:37.930  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.930  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.930  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.930  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.930  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.930  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.930  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.930  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.930  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.930  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.930  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.930  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.930  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.931  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.931  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.931  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.931  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.931  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.932  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.932  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.932  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.932  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.932  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.932  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.932  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.932  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.932  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.932  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.932  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.932  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.932  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.932  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.932  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.932  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.932  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.933  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.933  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.933  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.933  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.933  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.933  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.933  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.933  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.933  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.933  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.933  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.933  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.934  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.934  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.934  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.934  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.935  3738  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 15:29:37.935  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:37.936  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 15:29:37.936  3738  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 15:29:37.936  3738  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 15:29:37.937  3738  3738 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 15:29:37.937  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 15:29:37.937  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:37.937  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.937  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 15:29:37.937  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 15:29:37.937  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 15:29:37.937  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.937  3738  3787 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 15:29:37.938  3738  3803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 15:29:37.938  3738  3738 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 15:29:37.938  3738  3803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 15:29:37.938  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.938  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.938  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:37.938  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:37.938  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:29:37.938  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.938  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.939  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:37.939  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:37.939  3738  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 15:29:37.939  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:37.939  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:37.939  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.940  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.940  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.940  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.940  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.940  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.940  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.940  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.940  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.940  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.940  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.940  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.940  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.940  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.940  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.941  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.941  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.941  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.941  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.942  3738  3787 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 15:29:37.942  3738  3787 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 15:29:37.942  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:29:37.943  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:37.944  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.944  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.944  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.944  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.944  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.944  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.944  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.944  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.945  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.945  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.945  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.945  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.945  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.945  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.946  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.946  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.946  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.946  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.950  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.950  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.950  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.950  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.950  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.950  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.950  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.950  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.950  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.950  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.950  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.951  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.951  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.951  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.952  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.952  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.952  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.952  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.953  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:37.953  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:37.953  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:37.953  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:37.953  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.954  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.954  3738  3787 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264eb34 not in the list
09-07 15:29:37.954  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.954  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.954  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:37.954  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.954  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.954  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:37.954  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:37.955  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:37.955  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:37.955  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:37.955  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da2d5d not in the list
09-07 15:29:37.956  3738  3787 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 15:29:37.956  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:29:37.956  3738  3787 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 15:29:37.956  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:29:37.956  3738  3787 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 15:29:37.956  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:29:37.958  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 15:29:37.958  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 15:29:37.959  3738  3787 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 15:29:37.959  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 15:29:37.959  3738  3787 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 15:29:37.959  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 15:29:37.959  3738  3787 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 15:29:37.959  3738  3787 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 15:29:37.960  3738  3787 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 15:29:37.960  3738  3787 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 15:29:37.960  3738  3787 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 15:29:37.960  3738  3787 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 15:29:37.960  3738  3787 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 15:29:37.961  3738  3787 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 15:29:37.961  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:37.961  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eafa6f7 added. We now have 2 listener(s)
09-07 15:29:37.961  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:37.964  3738  3787 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 15:29:37.964   873  1994 D WifiService: setWifiEnabled: true pid=3738, uid=10000
09-07 15:29:37.964   873  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 15:29:37.965  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:37.965  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb38964 added. We now have 3 listener(s)
09-07 15:29:37.965  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:37.969  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:37.969  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa627cd added. We now have 4 listener(s)
09-07 15:29:37.969  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:37.970  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:37.970  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e6d9882 added. We now have 5 listener(s)
09-07 15:29:37.970  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:37.972   873  1693 D WifiService: setWifiEnabled: false pid=3738, uid=10000
09-07 15:29:37.972   873  1693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:29:37.978  2676  2691 D BluetoothAdapterState: Current state: ON, message: 23
09-07 15:29:37.978  2676  2691 D BluetoothAdapterProperties: Setting state to 13
09-07 15:29:37.978  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 15:29:37.981  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:37.981  2676  2691 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 15:29:37.983  2676  2695 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:29:37.982  2676  2691 I BluetoothAdapterState: Entering PendingCommandState
09-07 15:29:37.983  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 15:29:37.984  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.984  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:37.985  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.985  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.985  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:37.986  2676  2676 D HeadsetService: Received stop request...Stopping profile...
09-07 15:29:37.988   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:37.989  1947  1960 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:37.990  1358  1383 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:37.990  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:37.990  1358  1358 D HeadsetProfile: Bluetooth service disconnected
09-07 15:29:37.990   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:37.991   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:37.993  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:37.993  2676  2676 D A2dpService: Received stop request...Stopping profile...
09-07 15:29:37.993  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 15:29:37.993  2676  2808 D A2dpStateMachine: Exit Disconnected: -1
09-07 15:29:37.994   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 15:29:37.994   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 15:29:37.995   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 15:29:37.995   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:29:37.998  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:37.998  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:37.998  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.998  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:38.000   873   873 D BluetoothA2dp: Proxy object disconnected
09-07 15:29:38.000  1358  1358 D BluetoothA2dp: Proxy object disconnected
09-07 15:29:38.001  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:38.003  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:38.003  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:38.003  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:38.003  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:38.003   873  1854 D DhcpClient: Clearing IP address
09-07 15:29:38.003   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:29:38.003  2676  2676 D HidService: Received stop request...Stopping profile...
09-07 15:29:38.004  2676  2676 D HidService: Stopping Bluetooth HidService
,09-07 15:29:38.005  1358  1358 D BluetoothInputDevice: Proxy object disconnected
09-07 15:29:38.005  1358  1358 D HidProfile: Bluetooth service disconnected
,09-07 15:29:38.007   372   871 D CommandListener: Setting iface cfg
09-07 15:29:38.007  2676  2676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 15:29:38.007  2676  2676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 15:29:38.008  1510  3430 V NativeCrypto: Read error: ssl=0xaed0ce00: I/O error during system call, Connection timed out
09-07 15:29:38.008  2676  2676 D HealthService: Received stop request...Stopping profile...
09-07 15:29:38.008  2676  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 15:29:38.009  2676  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 15:29:38.009  2676  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 15:29:38.009  2676  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 15:29:38.009  2676  2695 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-07 15:29:38.010  1510  3430 V NativeCrypto: SSL shutdown failed: ssl=0xaed0ce00: I/O error during system call, Broken pipe
09-07 15:29:38.011   873  1694 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011,
09-07 15:29:38.011   873  1849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-07 15:29:38.014   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 15:29:38.014   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-07 15:29:38.016   402   402 E Parcel  : Reading a NULL string not supported here.
,09-07 15:29:38.017   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-07 15:29:38.017   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 15:29:38.019   873  1849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-07 15:29:38.021  2676  2676 D PanService: Received stop request...Stopping profile...
,09-07 15:29:38.021   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 15:29:38.024  2676  2676 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 15:29:38.024  2676  2676 D BluetoothMapService: stop()
09-07 15:29:38.024  2676  2676 D BluetoothMapAppObserver: deinitObservers()
,09-07 15:29:38.024  2676  2676 D BluetoothMapAppObserver: removeReceiver()
09-07 15:29:38.025  2676  2676 V BluetoothAdapterState: isTurningOff()=true
,09-07 15:29:38.025  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:38.025  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:38.025  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:38.026  2676  2676 V BluetoothAdapterState: isTurningOff()=true
,09-07 15:29:38.026  2676  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 15:29:38.026  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:38.026  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:38.026  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:38.026  2676  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 15:29:38.027  2676  2676 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 15:29:38.027  2676  2786 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-07 15:29:38.027  2676  2676 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 15:29:38.027  2676  2786 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:38.027  2676  2786 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 15:29:38.027  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:38.027  2676  2786 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 15:29:38.027  2676  2676 V BluetoothAdapterState: isTurningOn()=false
,09-07 15:29:38.027  2676  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 15:29:38.027  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:38.027  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:38.027  2676  2676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 15:29:38.027  2676  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 15:29:38.028  2676  2695 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-07 15:29:38.028  2676  2676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:29:38.028  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:38.028  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:38.028  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false,
09-07 15:29:38.028  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:38.029  2676  2676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 15:29:38.029  2676  2676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 15:29:38.029  2676  2676 D BluetoothMapService: MAP Service closeService in
09-07 15:29:38.029  2676  2676 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 15:29:38.030  2676  2676 D ObexServerSockets0: shutdown(block = true)
,09-07 15:29:38.030  2676  2814 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 15:29:38.031  2676  2676 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 15:29:38.031  2676  2815 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 15:29:38.031  2676  2802 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 15:29:38.031  2676  2676 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 15:29:38.032  2676  2676 V BluetoothAdapterState: isTurningOff()=true
,09-07 15:29:38.032  2676  2676 V BluetoothAdapterState: isTurningOn()=false
,09-07 15:29:38.032  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:38.032  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:38.032  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 15:29:38.032  2676  2676 D BluetoothMapService: cleanup()
09-07 15:29:38.032  2676  2676 D BluetoothMapService: MAP Service closeService in
,09-07 15:29:38.032  2676  2691 D BluetoothAdapterProperties: Setting state to 15
09-07 15:29:38.032  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-07 15:29:38.033  2676  2691 I BluetoothAdapterState: Entering BleOnState
,09-07 15:29:38.035  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:38.035  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:38.036  2676  2676 I BtOppRfcommListener: stopping Accept Thread
09-07 15:29:38.036  2676  3423 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:29:38.036  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:38.036  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:38.036  2676  3423 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 15:29:38.038  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:38.038  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:38.039  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:38.039  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:38.040  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 15:29:38.040  1358  1358 D PanProfile: Bluetooth service disconnected
,09-07 15:29:38.041  1358  1358 D BluetoothMap: Proxy object disconnected
09-07 15:29:38.041  1358  1358 D MapProfile: Bluetooth service disconnected
,09-07 15:29:38.044   873  1864 D DhcpClient: Receive thread stopped,
09-07 15:29:38.047   873   886 I ActivityManager: Start proc 3808:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 15:29:38.047   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:38.048  1358  1383 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:38.048   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 15:29:38.048   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:29:38.048  1358  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:29:38.050  1947  2273 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 15:29:38.050  1358  1372 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 15:29:38.051  1358  1383 D BluetoothMap: onBluetoothStateChange: up=false
09-07 15:29:38.052  1358  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 15:29:38.053   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:38.053  1358  1372 D BluetoothPan: onBluetoothStateChange on: false
09-07 15:29:38.054  2676  2691 D BluetoothAdapterState: Current state: BLE ON, message: 20,
09-07 15:29:38.054  2676  2691 D BluetoothAdapterProperties: Setting state to 16
09-07 15:29:38.054  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-07 15:29:38.055  2676  2691 D BluetoothAdapterProperties: onBleDisable
09-07 15:29:38.055  2676  2691 I BluetoothAdapterState: Entering PendingCommandState
,09-07 15:29:38.055  2676  2692 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 15:29:38.057  2676  2786 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 15:29:38.057  2676  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 15:29:38.060  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:38.061  2676  2695 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:29:38.061  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:38.062  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:38.063  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:38.065   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:38.091   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:38.091   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:29:38.092   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 15:29:38.092   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:38.095   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:29:38.096  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:38.098  3370  3370 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9f03564 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-07 15:29:38.098  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:38.102   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:29:38.104  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:38.104  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:38.104   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 15:29:38.105  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:38.105  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:38.106  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:38.107  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:38.107  2010  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:29:38.107  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:38.107  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:38.114  3808  3808 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 15:29:38.126  3808  3808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:38.133   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a78177a:true
,09-07 15:29:38.139  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:38.151   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-07 15:29:38.152   873  1995 I ActivityManager: Start proc 3827:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 15:29:38.152   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 15:29:38.169  3808  3808 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 15:29:38.184  3808  3808 D BluetoothMap: Create BluetoothMap proxy object
,09-07 15:29:38.191  3827  3827 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 15:29:38.197  3808  3808 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 15:29:38.215  3808  3808 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:38.226   873   883 I ActivityManager: Killing 2968:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 15:29:38.257  2676  2695 I bt_hci  : shut_down
,09-07 15:29:38.273  2676  2699 I bt_vendor: low_power_mode_cb
,09-07 15:29:38.280  2676  2699 D bt_hwcfg: hw_epilog_process
,09-07 15:29:38.294  2676  2699 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 15:29:38.294  2676  2699 I bt_vendor: epilog_cb
09-07 15:29:38.295  2676  2699 I bt_hci  : epilog_finished_callback
,09-07 15:29:38.299  2676  2695 I bt_hci_h4: hal_close
,09-07 15:29:38.300  2676  2695 I bt_userial_vendor: device fd = 51 close
,09-07 15:29:38.354  3827  3827 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.354  3827  3827 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.354  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.355  3827  3827 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.355  3827  3827 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.355  3827  3827 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.355  3827  3827 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.355  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.359  3827  3827 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.359  3827  3827 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:29:38.359  3827  3827 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:29:38.395  3808  3808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:38.407  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:38.411  3808  3808 D DockEventReceiver: finishStartingService: stopping service,
,09-07 15:29:38.417   873  1984 I ActivityManager: Killing 3370:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 15:29:38.440  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:29:38.504  2676  2692 D bt_stack_manager: event_shut_down_stack finished.
,09-07 15:29:38.505  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-07 15:29:38.506  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 15:29:38.507  2676  2676 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 15:29:38.507  2676  2691 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 15:29:38.507  2676  2676 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 15:29:38.507  2676  2676 D BtGatt.GattService: stop()
09-07 15:29:38.507  2676  2676 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 15:29:38.511  2676  2676 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:38.511  1720  1720 D SystemUpdateService: onCreate
09-07 15:29:38.511  2676  2676 V BluetoothAdapterState: isTurningOn()=false
,09-07 15:29:38.511  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:38.512  2676  2676 V BluetoothAdapterState: isBleTurningOff()=true
09-07 15:29:38.512  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 15:29:38.512  2676  2691 D BluetoothAdapterProperties: Setting state to 10
09-07 15:29:38.512  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 15:29:38.513  2676  2691 I BluetoothAdapterState: Entering OffState
09-07 15:29:38.513   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 15:29:38.524  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 15:29:38.527  2676  2676 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 15:29:38.527  2676  2676 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 15:29:38.527  2676  2676 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 15:29:38.528  1720  3859 I SystemUpdateService: active receiver: enabled
09-07 15:29:38.529  2676  2692 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-07 15:29:38.534  1720  3859 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 15:29:38.539  1720  3859 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 15:29:38.539  1720  3859 I SystemUpdateService: now status is 0 (complete)
09-07 15:29:38.539  1720  3859 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 15:29:38.540  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 15:29:38.540  1720  3859 I SystemUpdateService: file has been verified
,09-07 15:29:38.540  1720  3859 I SystemUpdateService: OTA package size = 12249756
,09-07 15:29:38.542  1720  2300 I iu.UploadsManager: num queued entries: 0
,09-07 15:29:38.543  1720  2300 I iu.UploadsManager: num updated entries: 0
09-07 15:29:38.544  2676  2692 D bt_stack_manager: event_clean_up_stack finished.
,09-07 15:29:38.546  1720  2300 I iu.SyncManager: NEXT; no task
,09-07 15:29:38.548  1720  3859 I SystemUpdateService: showing system update notification
,09-07 15:29:38.548  2676  2676 I art     : System.exit called, status: 0
,09-07 15:29:38.548  2676  2676 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 15:29:38.561  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 15:29:38.562  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 15:29:38.579   873  1995 I ActivityManager: Start proc 3863:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 15:29:38.581  1720  1720 D SystemUpdateService: onDestroy
,09-07 15:29:38.599   873  1995 I ActivityManager: Process com.android.bluetooth (pid 2676) has died
,09-07 15:29:38.614  3863  3863 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 15:29:38.618  3827  3845 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 15:29:38.621  3863  3863 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:38.628  3863  3863 D SprintDMHelper: simOperator: 
,09-07 15:29:38.628  3863  3863 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 15:29:38.641   873  1962 I ActivityManager: Start proc 3875:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 15:29:38.653   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@991caa6:true
,09-07 15:29:38.765   873   884 I ActivityManager: Start proc 3890:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 15:29:38.767   873  1995 I ActivityManager: Killing 3032:com.google.android.keep/u0a79 (adj 15): empty #17
,09-07 15:29:38.849  3890  3890 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 15:29:38.902  3890  3890 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 15:29:38.902  3890  3890 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 15:29:38.902  3890  3890 I GAv4    :   adb logcat -s GAv4
,09-07 15:29:38.921  3890  3890 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:38.929  3890  3890 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:38.960  3890  3908 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:39.057  3890  3890 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 15:29:39.092  3890  3890 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 15:29:39.103  3890  3890 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4767-4770)
,09-07 15:29:39.103  3890  3890 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 15:29:39.111  3890  3890 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37dbf94}
,09-07 15:29:39.111  3890  3890 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 15:29:39.111  3890  3890 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 15:29:39.118  3890  3890 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 15:29:39.119  3890  3890 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 15:29:39.146  3890  3890 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 15:29:39.157  3890  3890 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 15:29:39.158  3890  3890 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 15:29:39.158  3890  3890 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 15:29:39.158  3890  3890 I Adreno  : Build Date                       : 10/20/15
09-07 15:29:39.158  3890  3890 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 15:29:39.158  3890  3890 I Adreno  : Local Branch                     : M14
09-07 15:29:39.158  3890  3890 I Adreno  : Remote Branch                    : 
09-07 15:29:39.158  3890  3890 I Adreno  : Remote Branch                    : 
09-07 15:29:39.158  3890  3890 I Adreno  : Reconstruct Branch               : 
,09-07 15:29:39.211  3890  3936 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 15:29:39.213  3890  3890 I NSApplication: Starting up...
,09-07 15:29:39.244   873   884 I ActivityManager: Start proc 3941:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 15:29:39.246   873   884 I ActivityManager: Killing 3441:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 15:29:39.331  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 15:29:39.509   873  1693 I ActivityManager: Killing 1701:android.process.acore/u0a5 (adj 15): empty #17
,09-07 15:29:39.570   873  1694 I ActivityManager: Start proc 3955:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 15:29:39.680  3955  3955 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 15:29:39.747  3955  3955 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 15:29:39.771   873  1994 I ActivityManager: Start proc 3978:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-07 15:29:39.772   873  1994 I ActivityManager: Killing 3597:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 15:29:39.852  3978  3978 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-07 15:29:40.077   873   884 I ActivityManager: Killing 3612:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 15:29:40.988   873  1524 D WifiService: setWifiEnabled: true pid=3738, uid=10000
,09-07 15:29:40.988   873  1524 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:29:41.009   873  1303 D WifiConfigStore: Loading config and enabling all networks ,
09-07 15:29:41.012  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:41.012  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:41.013  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:41.013  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:41.017  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:41.017  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:41.018  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:41.018  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:41.052   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 15:29:41.054   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 15:29:41.057   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 15:29:41.059   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 15:29:41.060   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 15:29:41.061   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 15:29:41.061   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 15:29:41.089   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 15:29:41.090   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.25 rxSuccessRate=14.75 delta 1000 -> 994
,09-07 15:29:41.092   372   871 D CommandListener: Setting iface cfg
,09-07 15:29:41.093   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-07 15:29:41.094   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 15:29:41.108   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 15:29:41.108   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 15:29:41.109   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:29:41.109   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 15:29:41.123   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 15:29:41.224   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 15:29:41.226  1452  1452 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 15:29:41.654  1452  1452 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 15:29:41.726  1452  1452 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 15:29:41.730  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 15:29:41.737   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:29:41.752   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 15:29:41.753   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:29:41.753   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 15:29:41.777   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:41.786   372   871 D CommandListener: Setting iface cfg
09-07 15:29:41.787   873  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 15:29:41.799   873  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-07 15:29:41.800   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 15:29:41.840   873  4010 D DhcpClient: Receive thread started
,09-07 15:29:41.924   873  1303 E native  : do suspend false
,09-07 15:29:41.944   873  1854 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 15:29:41.965   873  4010 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,09-07 15:29:41.967   873  1854 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,09-07 15:29:41.973   873  1854 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 15:29:41.986   873  4010 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 15:29:41.988   873  1854 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 15:29:41.995   372   871 D CommandListener: Setting iface cfg
,09-07 15:29:42.005   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 15:29:42.006   873  1854 D DhcpClient: Scheduling renewal in 86399s
,09-07 15:29:42.017   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 15:29:42.019   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 15:29:42.020   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 15:29:42.021   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 15:29:42.022   873  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 15:29:42.034   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 15:29:42.078   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 15:29:42.078   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 15:29:42.079   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 15:29:42.081   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 15:29:42.082   873  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 15:29:42.093   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 15:29:42.097   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 15:29:42.097   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-07 15:29:42.097   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-07 15:29:42.097   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 15:29:42.097   873  1305 D ConnectivityService:    accepting network in place of null
,09-07 15:29:42.098   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 15:29:42.098   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 15:29:42.152   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:42.194   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:42.198   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 15:29:42.198   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 15:29:42.207   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:29:42.214   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 15:29:42.215  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:42.215  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:42.216  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:42.216  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:42.220  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:42.221  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:42.221  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:42.222  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:42.228  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 15:29:42.232  1720  1720 D SystemUpdateService: onCreate
,09-07 15:29:42.234  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 15:29:42.237  1720  4020 I SystemUpdateService: active receiver: enabled
,09-07 15:29:42.242  1720  4020 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 15:29:42.244  1720  4020 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 15:29:42.244  1720  4020 I SystemUpdateService: now status is 0 (complete)
09-07 15:29:42.244  1720  4020 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 15:29:42.244  1720  4020 I SystemUpdateService: file has been verified
09-07 15:29:42.244  1720  4020 I SystemUpdateService: OTA package size = 12249756
,09-07 15:29:42.249  1720  4020 I SystemUpdateService: showing system update notification
,09-07 15:29:42.254  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 15:29:42.256  1720  2300 I iu.UploadsManager: num queued entries: 0
09-07 15:29:42.256  1720  2300 I iu.UploadsManager: num updated entries: 0
,09-07 15:29:42.258  1720  2300 I iu.SyncManager: NEXT; no task
,09-07 15:29:42.259  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 15:29:42.260  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 15:29:42.261  1720  4024 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 15:29:42.261  1720  4024 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:42.262  3863  3863 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 15:29:42.262  1720  4024 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 15:29:42.267  1720  1720 D SystemUpdateService: onDestroy
09-07 15:29:42.267  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:42.269  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:42.270  3863  3863 D SprintDMHelper: simOperator: 
,09-07 15:29:42.270  3863  3863 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 15:29:42.301  1510  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 15:29:42.301  1510  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 15:29:42.302  1510  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:29:42.302  1510  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:42.313  1720  4024 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-07 15:29:42.397  3978  4030 V KeepSync: Connecting to GoogleApiClient
,09-07 15:29:42.398   873  1995 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 15:29:42.459  1510  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 15:29:42.459  1510  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 15:29:42.459  1510  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:29:42.460  1510  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:42.488  1720  4031 V BaseAuthAsyncOperation: access token request failed
,09-07 15:29:42.492  3978  4030 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 15:29:42.660  1510  2277 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 15:29:42.660  1510  2277 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 15:29:42.660  1510  2277 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:29:42.660  1510  2277 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:42.708  3978  4030 E KeepSync: IOException
09-07 15:29:42.708  3978  4030 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 15:29:42.708  3978  4030 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:29:42.708  3978  4030 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 15:29:42.708  3978  4030 E KeepSync: 	... 10 more
,09-07 15:29:42.708  3978  4030 W KeepSync: Sync result 2
,09-07 15:29:42.722   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129378, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:29:43.193   873  4009 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138860, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:29:43.199   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 15:29:43.999   873  1962 D WifiService: setWifiEnabled: false pid=3738, uid=10000
,09-07 15:29:44.000   873  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:29:44.034  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 15:29:44.039   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 15:29:44.039   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 15:29:44.039   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 15:29:44.039   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:44.053   873  1854 D DhcpClient: Clearing IP address
,09-07 15:29:44.054   372   871 D CommandListener: Setting iface cfg
,09-07 15:29:44.058   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:44.067   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 15:29:44.067   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-07 15:29:44.081   402   402 E Parcel  : Reading a NULL string not supported here.
,09-07 15:29:44.084   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 15:29:44.085   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 15:29:44.086   873  4010 D DhcpClient: Receive thread stopped
,09-07 15:29:44.088   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:44.093   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 15:29:44.096   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:29:44.100   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 15:29:44.101  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:44.101  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:44.101  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:44.101  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:44.102  2010  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:29:44.102  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:44.102  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:44.102  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:44.102  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:44.134   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:44.169   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:44.170   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 15:29:44.170   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:44.173   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:29:44.177  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:44.179  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:44.201  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 15:29:44.206  1720  1720 D SystemUpdateService: onCreate
,09-07 15:29:44.210  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 15:29:44.214  1720  4043 I SystemUpdateService: active receiver: enabled
,09-07 15:29:44.224  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 15:29:44.246  1720  2300 I iu.UploadsManager: num queued entries: 0
09-07 15:29:44.247  1720  2300 I iu.UploadsManager: num updated entries: 0
,09-07 15:29:44.249  1720  4043 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 15:29:44.251  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 15:29:44.252  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 15:29:44.255  1720  4043 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 15:29:44.255  1720  4043 I SystemUpdateService: now status is 0 (complete)
,09-07 15:29:44.255  1720  4043 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 15:29:44.255  1720  4043 I SystemUpdateService: file has been verified
,09-07 15:29:44.255  1720  4043 I SystemUpdateService: OTA package size = 12249756
,09-07 15:29:44.256  3863  3863 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:44.266  3863  3863 D SprintDMHelper: simOperator: 
09-07 15:29:44.266  3863  3863 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 15:29:44.267   372   871 E Netd    : netlink response contains error (No such file or directory)
09-07 15:29:44.269   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 15:29:44.280  1720  2300 I iu.SyncManager: NEXT; no task
,09-07 15:29:44.315  1720  4043 I SystemUpdateService: showing system update notification
,09-07 15:29:44.334  1720  1720 D SystemUpdateService: onDestroy
,09-07 15:29:44.930  3978  3985 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@9a158b4)
,09-07 15:29:45.074  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:45.116  1510  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 15:29:45.117  1510  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 15:29:45.117  1510  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:29:45.118  1510  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:45.146  3490  3490 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 15:29:45.146  3490  3490 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 15:29:45.147  3490  3490 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 15:29:47.061   873   890 I ActivityManager: Start proc 4051:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 15:29:47.112   873  4008 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-07 15:29:47.115   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 15:29:47.198  4051  4051 D AdapterServiceConfig: Adding HeadsetService
,09-07 15:29:47.199  4051  4051 D AdapterServiceConfig: Adding A2dpService
,09-07 15:29:47.199  4051  4051 D AdapterServiceConfig: Adding HidService
,09-07 15:29:47.199  4051  4051 D AdapterServiceConfig: Adding HealthService
,09-07 15:29:47.199  4051  4051 D AdapterServiceConfig: Adding PanService
,09-07 15:29:47.199  4051  4051 D AdapterServiceConfig: Adding GattService
,09-07 15:29:47.199  4051  4051 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 15:29:47.213  4051  4051 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 15:29:47.213   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37c4475:true
,09-07 15:29:47.218  4051  4051 I bt_bluedroid: init
,09-07 15:29:47.219  4051  4063 I BluetoothAdapterState: Entering OffState
,09-07 15:29:47.225  4051  4064 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 15:29:47.225  4051  4064 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 15:29:47.225  4051  4064 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 15:29:47.226  4051  4064 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 15:29:47.228  4051  4051 I bt_bluedroid: get_profile_interface socket
,09-07 15:29:47.229  4051  4051 I bt_bluedroid: get_profile_interface sdp
,09-07 15:29:47.233  4051  4062 I bt_bluedroid: config_hci_snoop_log
,09-07 15:29:47.234  4051  4067 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 15:29:47.236  4051  4067 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 15:29:47.236   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 15:29:47.245  4051  4063 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 15:29:47.246  4051  4063 D BluetoothAdapterProperties: Setting state to 14
,09-07 15:29:47.247  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 15:29:47.250  4051  4063 D BluetoothBondStateMachine: make
,09-07 15:29:47.254  4051  4068 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 15:29:47.260  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
,09-07 15:29:47.261  4051  4051 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 15:29:47.265  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:47.266  4051  4051 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 15:29:47.266  4051  4051 D BtGatt.GattService: Received start request. Starting profile...
,09-07 15:29:47.266  4051  4051 D BtGatt.GattService: start()
,09-07 15:29:47.267  4051  4051 I bt_bluedroid: get_profile_interface gatt,
09-07 15:29:47.268  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a,
09-07 15:29:47.268  4051  4051 D BtGatt.AdvertiseManager: advertise manager created
,09-07 15:29:47.276  4051  4051 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:47.276  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:47.277  4051  4051 V BluetoothAdapterState: isBleTurningOn()=true
09-07 15:29:47.277  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:47.277  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 15:29:47.277  4051  4063 I bt_bluedroid: enable
,09-07 15:29:47.278  4051  4064 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 15:29:47.278  4051  4064 I bt_hci  : start_up
,09-07 15:29:47.292  4051  4064 I bt_vendor: alloc value 0xb3a57189
,09-07 15:29:47.292  4051  4064 I bt_vendor: init
09-07 15:29:47.292  4051  4064 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-07 15:29:47.292  4051  4064 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 15:29:47.295  2383  4026 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-07 15:29:47.295  2383  4026 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 15:29:47.298  2383  4026 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 15:29:47.305   873  1995 I ActivityManager: Killing 2198:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 15:29:47.400  4051  4064 D bt_hci  : start_up starting async portion
,09-07 15:29:47.401  4051  4071 I bt_hci  : event_finish_startup
09-07 15:29:47.401  4051  4071 I bt_hci_h4: hal_open
,09-07 15:29:47.401  4051  4071 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 15:29:47.409  4051  4071 I bt_userial_vendor: device fd = 51 open
,09-07 15:29:47.443  4051  4071 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 15:29:47.475  4051  4071 D bt_hwcfg: Chipset BCM4354A2
09-07 15:29:47.475  4051  4071 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 15:29:47.477  4051  4071 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 15:29:48.101  4051  4071 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 15:29:48.102  4051  4071 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 15:29:48.102  4051  4071 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 15:29:48.219  4051  4071 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 15:29:48.221  4051  4071 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 15:29:48.250  4051  4071 I bt_hwcfg: vendor lib fwcfg completed
,09-07 15:29:48.250  4051  4071 I bt_vendor: firmware callback
09-07 15:29:48.251  4051  4071 I bt_hci  : firmware_config_callback
,09-07 15:29:48.262  4051  4073 I bt_btu  : btu_task pending for preload complete event
,09-07 15:29:48.262  4051  4073 I bt_btu_task: Bluetooth chip preload is complete
,09-07 15:29:48.263  4051  4073 I bt_btu  : btu_task received preload complete event
,09-07 15:29:48.272  4051  4073 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 15:29:48.273  4051  4073 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 15:29:48.273  4051  4073 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 15:29:48.273  4051  4073 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 15:29:48.273  4051  4073 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-07 15:29:48.274  4051  4073 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 15:29:48.274  4051  4073 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 15:29:48.274  4051  4073 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 15:29:48.275  4051  4073 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 15:29:48.275  4051  4073 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 15:29:48.275  4051  4073 I         : BTE_InitTraceLevels -- TRC_SDP
,09-07 15:29:48.275  4051  4073 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 15:29:48.276  4051  4073 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 15:29:48.276  4051  4073 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 15:29:48.276  4051  4073 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 15:29:48.414  4051  4073 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d4d9d
,09-07 15:29:48.414  4051  4073 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d4d9d 
,09-07 15:29:48.423  4051  4067 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 15:29:48.426  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 15:29:48.427  4051  4067 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 15:29:48.430  4051  4067 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 15:29:48.433  4051  4067 D BluetoothAdapterProperties: Scan Mode:20
,09-07 15:29:48.434  4051  4067 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:29:48.434  4051  4067 D bt_hci  : do_postload posting postload work item
09-07 15:29:48.434  4051  4071 I bt_hci  : event_postload
09-07 15:29:48.434  4051  4071 I bt_vendor: sco_config_cb
09-07 15:29:48.434  4051  4071 I bt_hci  : sco_config_callback postload finished.
,09-07 15:29:48.437  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:48.439  4051  4067 D bt_bte_conf: Device ID record 1 : primary
,09-07 15:29:48.439  4051  4067 D bt_bte_conf:   vendorId            = 000f
09-07 15:29:48.439  4051  4067 D bt_bte_conf:   vendorIdSource      = 0001
09-07 15:29:48.440  4051  4067 D bt_bte_conf:   product             = 1200
09-07 15:29:48.440  4051  4067 D bt_bte_conf:   version             = 1436
09-07 15:29:48.440  4051  4067 D bt_bte_conf:   clientExecutableURL = 
,09-07 15:29:48.440  4051  4067 D bt_bte_conf:   serviceDescription  = 
09-07 15:29:48.441  4051  4067 D bt_bte_conf:   documentationURL    = 
09-07 15:29:48.441  4051  4067 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 15:29:48.441  4051  4064 D bt_stack_manager: event_start_up_stack finished
09-07 15:29:48.444  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 15:29:48.444  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:48.444  4051  4063 D BluetoothAdapterProperties: Setting state to 15
09-07 15:29:48.445  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 15:29:48.445  4051  4071 I bt_vendor: low_power_mode_cb
,09-07 15:29:48.448  4051  4063 I BluetoothAdapterState: Entering BleOnState
,09-07 15:29:48.451  4051  4063 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 15:29:48.451  4051  4063 D BluetoothAdapterProperties: Setting state to 11
09-07 15:29:48.451  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 15:29:48.457  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:48.458  4051  4051 D HeadsetService: Received start request. Starting profile...
09-07 15:29:48.461  4051  4051 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 15:29:48.462  4051  4051 D HeadsetStateMachine: make
,09-07 15:29:48.463  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:48.467  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:48.470  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
09-07 15:29:48.474  4051  4051 D HeadsetStateMachine: max_hf_connections = 1
,09-07 15:29:48.474  4051  4051 I bt_bluedroid: get_profile_interface handsfree
09-07 15:29:48.474  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-07 15:29:48.474  4051  4067 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-07 15:29:48.478  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:48.478  4051  4051 D A2dpService: Received start request. Starting profile...
,09-07 15:29:48.479  4051  4051 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 15:29:48.482  4051  4051 I bt_bluedroid: get_profile_interface avrcp
,09-07 15:29:48.486  4051  4051 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 15:29:48.488  4051  4051 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-07 15:29:48.488  4051  4051 D A2dpStateMachine: make
,09-07 15:29:48.489  4051  4051 I bt_bluedroid: get_profile_interface a2dp
,09-07 15:29:48.490  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 15:29:48.492  4051  4051 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 15:29:48.492  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:48.493  4051  4082 D A2dpStateMachine: Enter Disconnected: -2
,09-07 15:29:48.494  4051  4051 D HidService: Received start request. Starting profile...
09-07 15:29:48.494  3808  3808 D BluetoothInputDevice: Proxy object connected
09-07 15:29:48.494  4051  4051 I bt_bluedroid: get_profile_interface hidhost
09-07 15:29:48.494  4051  4067 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b63e5
,09-07 15:29:48.494  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 15:29:48.494  4051  4051 D HidService: setHidService(): set to: null
09-07 15:29:48.495  3808  3808 D HidProfile: Bluetooth service connected
09-07 15:29:48.495  4051  4051 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 15:29:48.496  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
09-07 15:29:48.496  4051  4051 D HealthService: Received start request. Starting profile...
,09-07 15:29:48.497  4051  4051 I bt_bluedroid: get_profile_interface health
,09-07 15:29:48.498  4051  4051 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 15:29:48.499  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
09-07 15:29:48.500  4051  4051 D PanService: Received start request. Starting profile...
,09-07 15:29:48.500  4051  4051 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 15:29:48.500  3808  3808 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:48.500  4051  4051 I bt_bluedroid: get_profile_interface pan
,09-07 15:29:48.500  4051  4067 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 15:29:48.500  3808  3808 D PanProfile: Bluetooth service connected
,09-07 15:29:48.503  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:48.504  4051  4051 D BluetoothMapService: Received start request. Starting profile...
,09-07 15:29:48.504  4051  4051 D BluetoothMapService: start()
09-07 15:29:48.504  3808  3808 D BluetoothMap: Proxy object connected
,09-07 15:29:48.505  3808  3808 D MapProfile: Bluetooth service connected
09-07 15:29:48.505  3808  3808 D BluetoothMap: getConnectedDevices()
,09-07 15:29:48.505  3808  3808 D BluetoothMap: Bluetooth is Not enabled
09-07 15:29:48.506  4051  4051 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 15:29:48.507  4051  4051 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 15:29:48.507  4051  4051 D BluetoothMapAppObserver: createReceiver()
09-07 15:29:48.508  4051  4051 D BluetoothMapAppObserver: initObservers()
09-07 15:29:48.508  4051  4051 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 15:29:48.516  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:48.517  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:48.517  4051  4051 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:48.517  4051  4080 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 15:29:48.517  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:48.517  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:48.519  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:48.519  4051  4051 V BluetoothAdapterState: isTurningOn()=true
,09-07 15:29:48.519  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:48.519  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:48.520  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:48.521  4051  4051 V BluetoothAdapterState: isTurningOn()=true
,09-07 15:29:48.522  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:48.522  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:48.522  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 15:29:48.522  4051  4063 D BluetoothAdapterProperties: ScanMode =  20
09-07 15:29:48.522  4051  4063 D BluetoothAdapterProperties: State =  11
09-07 15:29:48.523  4051  4067 D BluetoothAdapterProperties: Scan Mode:21
09-07 15:29:48.523  4051  4063 D BluetoothAdapterProperties: Setting state to 12
09-07 15:29:48.523  4051  4067 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:29:48.523  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 15:29:48.524  4051  4063 I BluetoothAdapterState: Entering OnState
09-07 15:29:48.524   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:48.525  1358  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 15:29:48.525  3808  3820 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:29:48.526   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:48.526   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 15:29:48.526  1358  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:48.526  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:48.527   873   873 D BluetoothA2dp: Proxy object connected
09-07 15:29:48.529  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:48.531  1358  1358 D BluetoothA2dp: Proxy object connected
,09-07 15:29:48.533  1947  2273 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:48.533  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:48.534  3808  3821 D BluetoothMap: onBluetoothStateChange: up=true
09-07 15:29:48.535  3808  3820 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 15:29:48.535  4051  4051 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 15:29:48.536  4051  4051 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 15:29:48.536  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:48.538  3808  3821 D BluetoothPan: onBluetoothStateChange on: true
,09-07 15:29:48.538  4051  4051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:48.538  1358  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 15:29:48.540  4051  4051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:48.540  1358  1383 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 15:29:48.542  4051  4051 D ObexServerSockets: Succeed to create listening sockets 
09-07 15:29:48.542  4051  4051 D ObexServerSockets0: startAccept()
09-07 15:29:48.542  4051  4051 D ObexServerSockets0: prepareForNewConnect()
09-07 15:29:48.542  1358  1358 D BluetoothMap: Proxy object connected
09-07 15:29:48.542  1358  1358 D MapProfile: Bluetooth service connected
09-07 15:29:48.542  1358  1358 D BluetoothMap: getConnectedDevices()
,09-07 15:29:48.543  1358  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:29:48.545  1358  1358 D BluetoothInputDevice: Proxy object connected
09-07 15:29:48.545  1358  1358 D HidProfile: Bluetooth service connected
,09-07 15:29:48.545   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:48.545  4051  4051 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 15:29:48.545  4051  4051 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 15:29:48.545  1358  1383 D BluetoothPan: onBluetoothStateChange on: true
09-07 15:29:48.545  4051  4088 D ObexServerSockets0: Accepting socket connection...
09-07 15:29:48.546  4051  4089 D ObexServerSockets0: Accepting socket connection...
09-07 15:29:48.547  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 15:29:48.547  1358  1358 D PanProfile: Bluetooth service connected
09-07 15:29:48.549   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 15:29:48.550  4051  4051 D BluetoothMapService: onReceive
09-07 15:29:48.550  4051  4051 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:48.550  4051  4051 D BluetoothMapService: STATE_ON
09-07 15:29:48.550  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:48.552  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:48.554  3808  3808 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-07 15:29:48.558  3808  3808 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 15:29:48.564  3808  3808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:48.567  3808  3808 D BluetoothA2dp: Proxy object connected
,09-07 15:29:48.571  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:48.575  3808  3808 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:48.592  3808  3808 D BluetoothPbap: Proxy object connected
,09-07 15:29:48.592  1358  1358 D BluetoothPbap: Proxy object connected
09-07 15:29:48.593  1358  1358 D PbapServerProfile: Bluetooth service connected
,09-07 15:29:48.593  3808  3808 D PbapServerProfile: Bluetooth service connected
09-07 15:29:48.593  4051  4051 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 15:29:48.593  4051  4051 D ObexServerSockets0: prepareForNewConnect()
,09-07 15:29:48.606  4051  4093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:48.624  4051  4097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:48.626   873   873 D BluetoothHeadset: Proxy object connected
09-07 15:29:48.626   873   890 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.627  1947  2103 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.627  1358  1385 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.627  4051  4097 I BtOppRfcommListener: Accept thread started.
,09-07 15:29:48.628  1358  1358 D HeadsetProfile: Bluetooth service connected
09-07 15:29:48.628   873   873 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.628   873   873 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.634  1947  1961 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.645   873   890 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.662  3808  3820 D BluetoothHeadset: Proxy object connected
,09-07 15:29:48.664  3808  3808 D HeadsetProfile: Bluetooth service connected
,09-07 15:29:50.021  4051  4063 D BluetoothAdapterState: Current state: ON, message: 23
09-07 15:29:50.021  4051  4063 D BluetoothAdapterProperties: Setting state to 13
09-07 15:29:50.021  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 15:29:50.024  4051  4063 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 15:29:50.033  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
,09-07 15:29:50.038  4051  4051 D BluetoothMapService: onReceive
,09-07 15:29:50.038  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:50.039  4051  4051 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:50.039  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:50.039  4051  4051 D BluetoothMapService: STATE_TURNING_OFF
,09-07 15:29:50.040  4051  4051 D BluetoothMapService: MAP Service closeService in
,09-07 15:29:50.040  4051  4051 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 15:29:50.040  4051  4051 D ObexServerSockets0: shutdown(block = true)
,09-07 15:29:50.041  4051  4088 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 15:29:50.042  4051  4051 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 15:29:50.043  4051  4089 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-07 15:29:50.044  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:50.044  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:50.045  4051  4051 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 15:29:50.045  4051  4076 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 15:29:50.046  4051  4051 I BtOppRfcommListener: stopping Accept Thread
09-07 15:29:50.047  4051  4097 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 15:29:50.047  4051  4097 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 15:29:50.051  4051  4067 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:29:50.051  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 15:29:50.051  3808  3808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 15:29:50.052  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:50.052  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:50.053  3738  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:50.053  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:50.055  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:50.057  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:50.057  4051  4051 D HeadsetService: Received stop request...Stopping profile...
,09-07 15:29:50.062   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:50.063  4051  4051 D A2dpService: Received stop request...Stopping profile...
09-07 15:29:50.064  1947  1960 D BluetoothHeadset: Proxy object disconnected
,09-07 15:29:50.065  3808  3821 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:50.065  4051  4082 D A2dpStateMachine: Exit Disconnected: -1
09-07 15:29:50.065  1358  1372 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:50.065  1358  1358 D HeadsetProfile: Bluetooth service disconnected
09-07 15:29:50.066   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 15:29:50.066   873   873 D BluetoothHeadset: Proxy object disconnected
,09-07 15:29:50.067   873   873 D BluetoothA2dp: Proxy object disconnected
,09-07 15:29:50.067  1358  1358 D BluetoothA2dp: Proxy object disconnected
,09-07 15:29:50.070  3808  3808 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:50.071  4051  4051 D HidService: Received stop request...Stopping profile...
09-07 15:29:50.071  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:29:50.071  4051  4051 D HidService: Stopping Bluetooth HidService,
,09-07 15:29:50.072  3808  3808 D HeadsetProfile: Bluetooth service disconnected
,09-07 15:29:50.072  3808  3808 D BluetoothA2dp: Proxy object disconnected
,09-07 15:29:50.074  1358  1358 D BluetoothInputDevice: Proxy object disconnected
09-07 15:29:50.074  4051  4051 V BluetoothAdapterState: isTurningOff()=true
,09-07 15:29:50.074  1358  1358 D HidProfile: Bluetooth service disconnected
,09-07 15:29:50.074  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:50.074  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:50.075  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:50.075  4051  4051 D HealthService: Received stop request...Stopping profile...
,09-07 15:29:50.077  3808  3808 D BluetoothInputDevice: Proxy object disconnected
09-07 15:29:50.077  3808  3808 D HidProfile: Bluetooth service disconnected
09-07 15:29:50.077  4051  4051 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 15:29:50.077  4051  4051 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 15:29:50.077  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 15:29:50.078  4051  4073 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 15:29:50.078  4051  4073 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 15:29:50.078  4051  4073 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 15:29:50.078  4051  4051 D PanService: Received stop request...Stopping profile...
09-07 15:29:50.079  4051  4067 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-07 15:29:50.079  3808  3808 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 15:29:50.079  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 15:29:50.079  1358  1358 D PanProfile: Bluetooth service disconnected
09-07 15:29:50.079  3808  3808 D PanProfile: Bluetooth service disconnected
,09-07 15:29:50.080  4051  4051 D BluetoothMapService: Received stop request...Stopping profile...
09-07 15:29:50.080  4051  4051 D BluetoothMapService: stop()
,09-07 15:29:50.080  4051  4051 D BluetoothMapAppObserver: deinitObservers()
09-07 15:29:50.080  4051  4051 D BluetoothMapAppObserver: removeReceiver()
,09-07 15:29:50.081  1358  1358 D BluetoothMap: Proxy object disconnected
09-07 15:29:50.081  1358  1358 D MapProfile: Bluetooth service disconnected
,09-07 15:29:50.082  4051  4051 V BluetoothAdapterState: isTurningOff()=true
,09-07 15:29:50.082  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:50.082  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:50.082  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:50.084  3808  3808 D BluetoothMap: Proxy object disconnected
09-07 15:29:50.084  3808  3808 D MapProfile: Bluetooth service disconnected
09-07 15:29:50.084  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 15:29:50.084  4051  4073 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 15:29:50.084  4051  4073 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 15:29:50.084  4051  4073 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:29:50.084  4051  4073 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:50.084  4051  4073 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:29:50.084  4051  4073 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:50.086  1358  1358 D BluetoothPbap: Proxy object disconnected
09-07 15:29:50.087  1358  1358 D PbapServerProfile: Bluetooth service disconnected
,09-07 15:29:50.087  4051  4051 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:50.087  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:50.087  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:50.087  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:50.087  3808  3808 D BluetoothPbap: Proxy object disconnected
09-07 15:29:50.087  4051  4051 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 15:29:50.087  3808  3808 D PbapServerProfile: Bluetooth service disconnected
09-07 15:29:50.088  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 15:29:50.088  4051  4051 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 15:29:50.088  4051  4051 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:50.088  4051  4051 V BluetoothAdapterState: isTurningOn()=false
,09-07 15:29:50.088  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:50.088  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:50.089  4051  4051 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 15:29:50.089  4051  4067 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-07 15:29:50.089  4051  4051 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:29:50.089  4051  4051 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:50.089  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:50.089  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:50.090  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:50.092  4051  4051 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-07 15:29:50.092  4051  4051 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 15:29:50.093  4051  4051 D BluetoothMapService: MAP Service closeService in
09-07 15:29:50.094  4051  4051 V BluetoothAdapterState: isTurningOff()=true
09-07 15:29:50.094  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:50.094  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:50.094  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:50.094  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 15:29:50.094  4051  4063 D BluetoothAdapterProperties: Setting state to 15
09-07 15:29:50.094  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 15:29:50.095  4051  4051 D BluetoothMapService: cleanup()
09-07 15:29:50.095  4051  4051 D BluetoothMapService: MAP Service closeService in
,09-07 15:29:50.095   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:50.095  1358  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:50.095  4051  4063 I BluetoothAdapterState: Entering BleOnState
09-07 15:29:50.096  3808  3820 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 15:29:50.096   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 15:29:50.096  3808  3821 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:29:50.096   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:29:50.097  1358  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:29:50.097  1947  2273 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:50.098  3808  3820 D BluetoothMap: onBluetoothStateChange: up=false
09-07 15:29:50.098  3808  3821 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 15:29:50.099  3808  3820 D BluetoothPan: onBluetoothStateChange on: false
09-07 15:29:50.099  1358  1385 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 15:29:50.100  1358  1372 D BluetoothMap: onBluetoothStateChange: up=false
09-07 15:29:50.100   873  1305 D ConnectivityService: handlePromptUnvalidated 101
09-07 15:29:50.100  3808  3821 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:50.100  1358  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 15:29:50.101   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 15:29:50.101  1358  1385 D BluetoothPan: onBluetoothStateChange on: false
09-07 15:29:50.101  4051  4063 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-07 15:29:50.102  4051  4063 D BluetoothAdapterProperties: Setting state to 16
09-07 15:29:50.102  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 15:29:50.103  4051  4063 D BluetoothAdapterProperties: onBleDisable
09-07 15:29:50.103  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
09-07 15:29:50.103  4051  4064 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 15:29:50.103  4051  4073 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 15:29:50.104  4051  4073 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 15:29:50.104  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:50.105  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:50.108  4051  4067 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:29:50.109  3808  3808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 15:29:50.110  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:50.111  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:50.115  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:50.119  3808  3808 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:50.304  4051  4067 I bt_hci  : shut_down
,09-07 15:29:50.314  4051  4071 I bt_vendor: low_power_mode_cb
,09-07 15:29:50.319  4051  4071 D bt_hwcfg: hw_epilog_process
,09-07 15:29:50.330  4051  4071 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 15:29:50.330  4051  4071 I bt_vendor: epilog_cb
09-07 15:29:50.331  4051  4071 I bt_hci  : epilog_finished_callback
,09-07 15:29:50.337  4051  4067 I bt_hci_h4: hal_close
,09-07 15:29:50.338  4051  4067 I bt_userial_vendor: device fd = 51 close
,09-07 15:29:50.458  4051  4064 D bt_stack_manager: event_shut_down_stack finished.
,09-07 15:29:50.459  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-07 15:29:50.465  4051  4051 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 15:29:50.466  4051  4063 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 15:29:50.467  4051  4051 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 15:29:50.468  4051  4051 D BtGatt.GattService: stop()
09-07 15:29:50.469  4051  4051 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 15:29:50.475  4051  4051 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:50.475  4051  4051 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:50.475  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:50.476  4051  4051 V BluetoothAdapterState: isBleTurningOff()=true
09-07 15:29:50.477  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 15:29:50.477  4051  4063 D BluetoothAdapterProperties: Setting state to 10
09-07 15:29:50.478  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 15:29:50.480  4051  4063 I BluetoothAdapterState: Entering OffState
,09-07 15:29:50.483   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 15:29:50.515  4051  4051 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 15:29:50.515  4051  4051 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-07 15:29:50.517  4051  4064 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 15:29:50.518  4051  4051 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 15:29:50.525  4051  4064 D bt_stack_manager: event_clean_up_stack finished.
,09-07 15:29:50.529  4051  4051 I art     : System.exit called, status: 0
,09-07 15:29:50.530  4051  4051 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 15:29:50.585   873  1365 I ActivityManager: Process com.android.bluetooth (pid 4051) has died
,09-07 15:29:53.017  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:53.018  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:54.516   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 15:29:54.528  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-07 15:29:54.537   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 15:29:54.537   873   893 I Adreno  : Build Date                       : 10/20/15
09-07 15:29:54.537   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 15:29:54.537   873   893 I Adreno  : Local Branch                     : M14
09-07 15:29:54.537   873   893 I Adreno  : Remote Branch                    : 
09-07 15:29:54.537   873   893 I Adreno  : Remote Branch                    : 
09-07 15:29:54.537   873   893 I Adreno  : Reconstruct Branch               : 
,09-07 15:29:54.576   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (202 us)
,09-07 15:29:55.195  3738  3738 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 15:29:55.196  3738  3738 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 15:29:55.234  3738  3738 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e2a3c36 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2d1d7d0, 16908290=android.view.AbsSavedState$1@2d1d7d0}, android:focusedViewId=100}]}]
,09-07 15:29:55.235  3738  3738 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 15:29:55.235   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 15:29:55.235  3738  3738 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 15:29:55.235  3738  3738 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 15:29:55.253   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 15:29:55.258   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 15:29:55.260   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-07 15:29:55.260   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 15:29:55.497   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 15:29:55.503   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 15:29:55.506   873  1328 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
,09-07 15:29:55.510   873   893 I DreamManagerService: Entering dreamland.
,09-07 15:29:55.511   873   893 I PowerManagerService: Dozing...
09-07 15:29:55.513   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 15:29:55.561   376  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-07 15:29:55.561   376  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 15:29:55.573   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:29:55.575  1931  4109 D NfcService: Discovery configuration equal, not updating.
,09-07 15:29:55.576   873  1303 E native  : do suspend false
,09-07 15:29:55.609   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:29:55.613   873  1303 E native  : do suspend true
,09-07 15:29:55.703   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-07 15:29:55.704   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 15:29:56.026  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:56.026  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dfa73c9 added. We now have 6 listener(s)
,09-07 15:29:56.027  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:56.030  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:56.031  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@960bace added. We now have 7 listener(s)
,09-07 15:29:56.031  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:56.033  3738  3787 I System.out: IsBluetoothEnabled
,09-07 15:29:56.044  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:56.069   873   890 I ActivityManager: Start proc 4115:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 15:29:56.185  4115  4115 D AdapterServiceConfig: Adding HeadsetService
,09-07 15:29:56.185  4115  4115 D AdapterServiceConfig: Adding A2dpService
,09-07 15:29:56.186  4115  4115 D AdapterServiceConfig: Adding HidService
,09-07 15:29:56.186  4115  4115 D AdapterServiceConfig: Adding HealthService
,09-07 15:29:56.186  4115  4115 D AdapterServiceConfig: Adding PanService
,09-07 15:29:56.186  4115  4115 D AdapterServiceConfig: Adding GattService
,09-07 15:29:56.187  4115  4115 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 15:29:56.202  4115  4115 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 15:29:56.202   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e2aeed:true
,09-07 15:29:56.207  4115  4115 I bt_bluedroid: init
,09-07 15:29:56.208  4115  4127 I BluetoothAdapterState: Entering OffState
,09-07 15:29:56.213  4115  4128 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 15:29:56.214  4115  4128 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 15:29:56.214  4115  4128 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 15:29:56.214  4115  4128 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 15:29:56.216  4115  4115 I bt_bluedroid: get_profile_interface socket
,09-07 15:29:56.219  4115  4115 I bt_bluedroid: get_profile_interface sdp
09-07 15:29:56.219  4115  4131 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 15:29:56.221  4115  4131 D BluetoothAdapterProperties: Name is: Nexus 6
09-07 15:29:56.222  4115  4126 I bt_bluedroid: config_hci_snoop_log
,09-07 15:29:56.224   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 15:29:56.230  4115  4127 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 15:29:56.231  4115  4127 D BluetoothAdapterProperties: Setting state to 14
,09-07 15:29:56.232  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 15:29:56.236  4115  4127 D BluetoothBondStateMachine: make
,09-07 15:29:56.240  4115  4133 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 15:29:56.248  4115  4127 I BluetoothAdapterState: Entering PendingCommandState
,09-07 15:29:56.248  4115  4115 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 15:29:56.252  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:56.253  4115  4115 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 15:29:56.254  4115  4115 D BtGatt.GattService: Received start request. Starting profile...
,09-07 15:29:56.254  4115  4115 D BtGatt.GattService: start()
,09-07 15:29:56.254  4115  4115 I bt_bluedroid: get_profile_interface gatt
,09-07 15:29:56.256  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
09-07 15:29:56.256  4115  4115 D BtGatt.AdvertiseManager: advertise manager created
,09-07 15:29:56.266  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:56.266  4115  4115 V BluetoothAdapterState: isTurningOn()=false
09-07 15:29:56.266  4115  4115 V BluetoothAdapterState: isBleTurningOn()=true
09-07 15:29:56.266  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:56.267  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 15:29:56.267  4115  4127 I bt_bluedroid: enable
,09-07 15:29:56.268  4115  4128 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 15:29:56.269  4115  4128 I bt_hci  : start_up
,09-07 15:29:56.289  4115  4128 I bt_vendor: alloc value 0xb3a57189
,09-07 15:29:56.289  4115  4128 I bt_vendor: init
,09-07 15:29:56.289  4115  4128 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 15:29:56.290  4115  4128 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 15:29:56.399  4115  4128 D bt_hci  : start_up starting async portion
,09-07 15:29:56.400  4115  4136 I bt_hci  : event_finish_startup
09-07 15:29:56.400  4115  4136 I bt_hci_h4: hal_open
09-07 15:29:56.400  4115  4136 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 15:29:56.409  4115  4136 I bt_userial_vendor: device fd = 51 open
,09-07 15:29:56.441  4115  4136 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 15:29:56.472  4115  4136 D bt_hwcfg: Chipset BCM4354A2
,09-07 15:29:56.472  4115  4136 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 15:29:56.474  4115  4136 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 15:29:57.050  1510  2154 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 15:29:57.140  4115  4136 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 15:29:57.142  4115  4136 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 15:29:57.143  4115  4136 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 15:29:57.260  4115  4136 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 15:29:57.261  4115  4136 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 15:29:57.290  4115  4136 I bt_hwcfg: vendor lib fwcfg completed
,09-07 15:29:57.290  4115  4136 I bt_vendor: firmware callback
09-07 15:29:57.290  4115  4136 I bt_hci  : firmware_config_callback
,09-07 15:29:57.303  4115  4138 I bt_btu  : btu_task pending for preload complete event
,09-07 15:29:57.303  4115  4138 I bt_btu_task: Bluetooth chip preload is complete
09-07 15:29:57.304  4115  4138 I bt_btu  : btu_task received preload complete event
,09-07 15:29:57.315  4115  4138 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 15:29:57.315  4115  4138 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 15:29:57.315  4115  4138 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 15:29:57.315  4115  4138 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 15:29:57.316  4115  4138 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 15:29:57.316  4115  4138 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 15:29:57.316  4115  4138 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-07 15:29:57.317  4115  4138 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 15:29:57.318  4115  4138 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 15:29:57.318  4115  4138 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 15:29:57.318  4115  4138 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 15:29:57.318  4115  4138 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 15:29:57.319  4115  4138 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 15:29:57.319  4115  4138 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 15:29:57.319  4115  4138 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 15:29:57.449  4115  4138 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d4d9d
,09-07 15:29:57.450  4115  4138 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d4d9d 
,09-07 15:29:57.475  4115  4131 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 15:29:57.476  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 15:29:57.477  4115  4131 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 15:29:57.480  4115  4131 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 15:29:57.482  4115  4131 D BluetoothAdapterProperties: Scan Mode:20
,09-07 15:29:57.482  4115  4131 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:29:57.483  4115  4131 D bt_hci  : do_postload posting postload work item
09-07 15:29:57.483  4115  4136 I bt_hci  : event_postload
09-07 15:29:57.483  4115  4136 I bt_vendor: sco_config_cb
09-07 15:29:57.483  4115  4136 I bt_hci  : sco_config_callback postload finished.
,09-07 15:29:57.487  4115  4131 D bt_bte_conf: Device ID record 1 : primary
,09-07 15:29:57.488  4115  4131 D bt_bte_conf:   vendorId            = 000f
,09-07 15:29:57.488  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:57.488  4115  4131 D bt_bte_conf:   vendorIdSource      = 0001
09-07 15:29:57.488  4115  4131 D bt_bte_conf:   product             = 1200
09-07 15:29:57.489  4115  4131 D bt_bte_conf:   version             = 1436
09-07 15:29:57.489  4115  4131 D bt_bte_conf:   clientExecutableURL = 
09-07 15:29:57.489  4115  4131 D bt_bte_conf:   serviceDescription  = 
09-07 15:29:57.489  4115  4131 D bt_bte_conf:   documentationURL    = 
09-07 15:29:57.490  4115  4131 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 15:29:57.490  4115  4136 I bt_vendor: low_power_mode_cb
09-07 15:29:57.490  4115  4128 D bt_stack_manager: event_start_up_stack finished
09-07 15:29:57.491  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 15:29:57.491  4115  4127 D BluetoothAdapterProperties: Setting state to 15
09-07 15:29:57.491  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 15:29:57.493  4115  4127 I BluetoothAdapterState: Entering BleOnState
,09-07 15:29:57.499  4115  4127 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 15:29:57.499  4115  4127 D BluetoothAdapterProperties: Setting state to 11
,09-07 15:29:57.499  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 15:29:57.507  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:57.508  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:57.509  4115  4115 D HeadsetService: Received start request. Starting profile...
,09-07 15:29:57.513  4115  4115 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 15:29:57.513  4115  4115 D HeadsetStateMachine: make
,09-07 15:29:57.531  4115  4115 D HeadsetStateMachine: max_hf_connections = 1
,09-07 15:29:57.531  4115  4115 I bt_bluedroid: get_profile_interface handsfree
09-07 15:29:57.531  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 15:29:57.532  4115  4131 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-07 15:29:57.533  4115  4127 I BluetoothAdapterState: Entering PendingCommandState
,09-07 15:29:57.538  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:57.538  4115  4115 D A2dpService: Received start request. Starting profile...
,09-07 15:29:57.540  4115  4115 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 15:29:57.540  4115  4115 I bt_bluedroid: get_profile_interface avrcp
,09-07 15:29:57.547  4115  4115 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 15:29:57.548  4115  4115 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 15:29:57.548  4115  4115 D A2dpStateMachine: make
,09-07 15:29:57.549  4115  4115 I bt_bluedroid: get_profile_interface a2dp
,09-07 15:29:57.550  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 15:29:57.551  4115  4147 D A2dpStateMachine: Enter Disconnected: -2
,09-07 15:29:57.552  4115  4115 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 15:29:57.553  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:57.554  4115  4115 D HidService: Received start request. Starting profile...
09-07 15:29:57.554  4115  4115 I bt_bluedroid: get_profile_interface hidhost
,09-07 15:29:57.554  4115  4131 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b63e5
09-07 15:29:57.555  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 15:29:57.555  4115  4115 D HidService: setHidService(): set to: null
,09-07 15:29:57.558  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:57.558  4115  4115 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 15:29:57.559  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:57.560  4115  4115 D HealthService: Received start request. Starting profile...
,09-07 15:29:57.561  4115  4115 I bt_bluedroid: get_profile_interface health
,09-07 15:29:57.564  4115  4115 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 15:29:57.564  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:57.565  4115  4115 D PanService: Received start request. Starting profile...
09-07 15:29:57.565  4115  4115 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 15:29:57.565  4115  4115 I bt_bluedroid: get_profile_interface pan
09-07 15:29:57.566  4115  4131 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 15:29:57.568  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:29:57.569  4115  4115 D BluetoothMapService: Received start request. Starting profile...
09-07 15:29:57.569  4115  4115 D BluetoothMapService: start()
,09-07 15:29:57.571  4115  4115 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 15:29:57.572  4115  4115 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 15:29:57.572  4115  4115 D BluetoothMapAppObserver: createReceiver()
,09-07 15:29:57.573  4115  4115 D BluetoothMapAppObserver: initObservers()
09-07 15:29:57.573  4115  4115 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 15:29:57.579  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:57.579  4115  4115 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:57.579  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:57.579  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:57.581  4115  4145 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:57.581  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:57.583  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,09-07 15:29:57.583  4115  4115 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:57.583  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 15:29:57.583  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isTurningOff()=false
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isTurningOn()=true
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
09-07 15:29:57.584  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 15:29:57.584  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 15:29:57.584  4115  4127 D BluetoothAdapterProperties: ScanMode =  20
09-07 15:29:57.585  4115  4127 D BluetoothAdapterProperties: State =  11
09-07 15:29:57.585  4115  4127 D BluetoothAdapterProperties: Setting state to 12
,09-07 15:29:57.585  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 15:29:57.586  4115  4127 I BluetoothAdapterState: Entering OnState
09-07 15:29:57.586   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:57.586  1358  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:57.587  3808  3820 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:29:57.588  4115  4131 D BluetoothAdapterProperties: Scan Mode:21
09-07 15:29:57.588  4115  4131 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:57.591  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:57.591   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:57.592  3808  3821 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:57.593  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:57.594   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:57.595   873   873 D BluetoothA2dp: Proxy object connected
,09-07 15:29:57.595  3808  3808 D BluetoothInputDevice: Proxy object connected
09-07 15:29:57.595  3808  3808 D HidProfile: Bluetooth service connected
09-07 15:29:57.595  1358  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:57.597  1358  1358 D BluetoothA2dp: Proxy object connected
,09-07 15:29:57.598  1947  1960 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:57.599  3808  3821 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 15:29:57.599  4115  4115 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 15:29:57.599  3808  3808 D BluetoothA2dp: Proxy object connected
09-07 15:29:57.599  4115  4115 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 15:29:57.601  3808  3820 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 15:29:57.601  4115  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:29:57.602  3808  4152 D BluetoothPan: onBluetoothStateChange on: true
09-07 15:29:57.603  4115  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:57.604  1358  1383 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 15:29:57.604  4115  4115 D ObexServerSockets: Succeed to create listening sockets 
,09-07 15:29:57.604  4115  4115 D ObexServerSockets0: startAccept()
09-07 15:29:57.604  4115  4115 D ObexServerSockets0: prepareForNewConnect()
,09-07 15:29:57.605  1358  1372 D BluetoothMap: onBluetoothStateChange: up=true
09-07 15:29:57.606  4115  4115 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 15:29:57.606  4115  4115 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 15:29:57.607  3808  3821 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 15:29:57.607  1358  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:29:57.608  1358  1358 D BluetoothMap: Proxy object connected
09-07 15:29:57.608  1358  1358 D MapProfile: Bluetooth service connected
09-07 15:29:57.608  1358  1358 D BluetoothMap: getConnectedDevices()
09-07 15:29:57.608  4115  4153 D ObexServerSockets0: Accepting socket connection...
09-07 15:29:57.609  4115  4154 D ObexServerSockets0: Accepting socket connection...
09-07 15:29:57.609   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 15:29:57.609  1358  1383 D BluetoothPan: onBluetoothStateChange on: true
,09-07 15:29:57.609  3808  3808 D BluetoothMap: Proxy object connected
,09-07 15:29:57.609  3808  3808 D MapProfile: Bluetooth service connected
09-07 15:29:57.609  3808  3808 D BluetoothMap: getConnectedDevices()
09-07 15:29:57.610  1358  1358 D BluetoothInputDevice: Proxy object connected
09-07 15:29:57.610  1358  1358 D HidProfile: Bluetooth service connected
09-07 15:29:57.611  3808  3808 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:57.611  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:57.611  1358  1358 D PanProfile: Bluetooth service connected
09-07 15:29:57.612  3808  3808 D PanProfile: Bluetooth service connected
,09-07 15:29:57.612   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 15:29:57.614  4115  4115 D BluetoothMapService: onReceive
09-07 15:29:57.614  4115  4115 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:57.614  4115  4115 D BluetoothMapService: STATE_ON
09-07 15:29:57.615  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:57.621  3808  3808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:57.627  1510  1510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:57.630  3808  3808 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:57.636  3808  3808 D BluetoothPbap: Proxy object connected
,09-07 15:29:57.636  3808  3808 D PbapServerProfile: Bluetooth service connected
09-07 15:29:57.637  1358  1358 D BluetoothPbap: Proxy object connected
09-07 15:29:57.637  1358  1358 D PbapServerProfile: Bluetooth service connected
,09-07 15:29:57.643  4115  4115 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 15:29:57.643  4115  4115 D ObexServerSockets0: prepareForNewConnect()
,09-07 15:29:57.645  4115  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:57.661  4115  4162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:57.662  4115  4162 I BtOppRfcommListener: Accept thread started.
,09-07 15:29:57.688   873   873 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.688  1947  2273 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.689  3808  3821 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.690  1358  1385 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.691  1358  1358 D HeadsetProfile: Bluetooth service connected
09-07 15:29:57.691   873   873 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.691   873   873 D BluetoothHeadset: Proxy object connected
09-07 15:29:57.692   873   890 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.694  3808  3808 D HeadsetProfile: Bluetooth service connected
,09-07 15:29:57.698  1947  2103 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.707  3808  3820 D BluetoothHeadset: Proxy object connected
,09-07 15:29:57.707  3808  3808 D HeadsetProfile: Bluetooth service connected
,09-07 15:29:57.709   873   890 D BluetoothHeadset: Proxy object connected
,09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:58.067  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:58.074  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:58.078  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:58.079  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e7def added. We now have 8 listener(s)
09-07 15:29:58.079  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:58.085   873  1962 D WifiService: setWifiEnabled: false pid=3738, uid=10000
,09-07 15:29:58.085   873  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:29:58.097  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:58.099   873  1984 D WifiService: setWifiEnabled: true pid=3738, uid=10000
,09-07 15:29:58.100   873  1984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:29:58.114   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:58.132  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:58.139  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:58.149   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 15:29:58.151   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 15:29:58.151   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 15:29:58.152   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 15:29:58.152   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 15:29:58.153   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 15:29:58.153   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 15:29:58.176   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,09-07 15:29:58.177   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 15:29:58.177   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-07 15:29:58.180   372   871 D CommandListener: Setting iface cfg
,09-07 15:29:58.186   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-07 15:29:58.187   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 15:29:58.187   873  1303 E native  : do suspend true
,09-07 15:29:58.199   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 15:29:58.206   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 15:29:58.206   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 15:29:58.207   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:58.257   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 15:29:58.329   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 15:29:58.330  1452  1452 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 15:29:58.755  1452  1452 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 15:29:58.812  1452  1452 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 15:29:58.813  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-07 15:29:58.820   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:29:58.836   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 15:29:58.837   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 15:29:58.837   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:58.866   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:58.883   372   871 D CommandListener: Setting iface cfg
,09-07 15:29:58.884   873  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 15:29:58.897   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 15:29:58.934   873  4170 D DhcpClient: Receive thread started
,09-07 15:29:59.019   873  1303 E native  : do suspend false
,09-07 15:29:59.038   873  1854 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 15:29:59.055   873  4170 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-07 15:29:59.056   873  1854 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-07 15:29:59.059   873  1854 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 15:29:59.077   873  4170 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 15:29:59.078   873  1854 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 15:29:59.083   372   871 D CommandListener: Setting iface cfg
,09-07 15:29:59.094   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 15:29:59.098   873  1854 D DhcpClient: Scheduling renewal in 86399s
,09-07 15:29:59.099   873  1303 E native  : do suspend true
,09-07 15:29:59.113   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 15:29:59.116   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 15:29:59.118   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:59.119  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:59.120   873  1305 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 15:29:59.129  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:59.141   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 15:29:59.141  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 15:29:59.142  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 15:29:59.144  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e2a3c36 Bundle[{}]
,09-07 15:29:59.145  3738  3787 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 15:29:59.145  3738  3787 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 15:29:59.145  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 15:29:59.146  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 15:29:59.147  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 15:29:59.147  3738  3787 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 15:29:59.151  3738  3787 I System.out: Running OutgoingSocketThread
,09-07 15:29:59.153  3738  4173 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 411)
,09-07 15:29:59.154  3738  4173 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46231
,09-07 15:29:59.154  3738  4173 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 15:29:59.163   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 15:29:59.163   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-07 15:29:59.164   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 15:29:59.165   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 15:29:59.166   873  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 15:29:59.174   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 15:29:59.179   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-07 15:29:59.179   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 15:29:59.179   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 15:29:59.179   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 15:29:59.179   873  1305 D ConnectivityService:    accepting network in place of null
,09-07 15:29:59.180   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 15:29:59.180   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 15:29:59.207   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:59.235   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:29:59.240   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-07 15:29:59.240   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:59.252   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 15:29:59.253   873   890 D Tethering: MasterInitialState.processMessage what=3
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:59.270  3738  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:59.273  3738  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:59.282  1720  1720 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 15:29:59.292  1720  1720 D SystemUpdateService: onCreate
,09-07 15:29:59.295  1720  1720 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 15:29:59.314  1720  4180 I SystemUpdateService: active receiver: enabled
,09-07 15:29:59.317  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 15:29:59.326  1720  2300 I iu.UploadsManager: num queued entries: 0
,09-07 15:29:59.327  1720  2300 I iu.UploadsManager: num updated entries: 0
,09-07 15:29:59.327  1720  2300 I iu.SyncManager: NEXT; no task
,09-07 15:29:59.329  1720  4180 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 15:29:59.330  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 15:29:59.331  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 15:29:59.333  3863  3863 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:59.338  1720  4183 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 15:29:59.338  1720  4183 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 15:29:59.341  3863  3863 D SprintDMHelper: simOperator: 
,09-07 15:29:59.341  3863  3863 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 15:29:59.350  1720  4183 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 15:29:59.368  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:59.370  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:29:59.373  1720  4180 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 15:29:59.373  1720  4180 I SystemUpdateService: now status is 0 (complete)
09-07 15:29:59.373  1720  4180 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 15:29:59.373  1720  4180 I SystemUpdateService: file has been verified
09-07 15:29:59.373  1720  4180 I SystemUpdateService: OTA package size = 12249756
,09-07 15:29:59.395  1720  4180 I SystemUpdateService: showing system update notification
,09-07 15:29:59.417  1720  1720 D SystemUpdateService: onDestroy
,09-07 15:29:59.422  1510  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 15:29:59.422  1510  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 15:29:59.422  1510  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:29:59.422  1510  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:29:59.452  1720  4183 E MDM     : [183] SitrepService.a: Error sending sitrep.
,09-07 15:30:00.155  3738  3787 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 412)
09-07 15:30:00.155  3738  3787 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 412)
,09-07 15:30:00.164  3738  3787 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 417)
,09-07 15:30:00.167  3738  3787 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 15:30:00.167  3738  3787 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 418)
,09-07 15:30:00.172  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:00.172  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f44a0fc added. We now have 2 listener(s)
,09-07 15:30:00.174  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:30:00.174  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.174  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:30:00.174  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:00.174  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82d8385 added. We now have 9 listener(s)
09-07 15:30:00.174  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:30:00.175  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:30:00.179  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:00.187  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:30:00.190  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:30:00.190  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:30:00.190  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:00.190  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cf0a0b added. We now have 3 listener(s)
09-07 15:30:00.192  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 15:30:00.192  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.192  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:00.193  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:00.193  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8d0e8 added. We now have 10 listener(s)
09-07 15:30:00.193  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:00.193  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:00.193  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:00.193  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:00.193  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:00.193  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.193  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:00.193  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.194  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f44a0fc removed from the list
09-07 15:30:00.194  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.194  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82d8385 removed from the list
09-07 15:30:00.196  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:00.199  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:00.199  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:00.199  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.200  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.200  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.201  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:00.201  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.201  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.201  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listene,r org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82d8385 not in the list
09-07 15:30:00.202  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.202  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.203  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.203  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:00.203  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.203  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8d0e8 removed from the list
09-07 15:30:00.203  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:00.203  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.203  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:00.203  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.204  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cf0a0b removed from the list
,09-07 15:30:00.204  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:00.205  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7d301 added. We now have 2 listener(s)
,09-07 15:30:00.206  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 15:30:00.206  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.207  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:30:00.207  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:00.207  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2555a6 added. We now have 9 listener(s)
09-07 15:30:00.207  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:30:00.208  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:30:00.211  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:00.218  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:30:00.221   873  4169 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155888, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:30:00.222  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:30:00.222  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:30:00.223  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:00.224  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abe1394 added. We now have 3 listener(s)
,09-07 15:30:00.225  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:00.226  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:30:00.227  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:30:00.227  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:00.227  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:00.227  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d9e3d added. We now have 10 listener(s)
09-07 15:30:00.228  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:30:00.228  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:00.228  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 15:30:00.228  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:00.228  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:00.228  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:00.229  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:00.232  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 15:30:00.232  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:30:00.241   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-07 15:30:00.241  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:30:00.242  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 15:30:00.243  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:30:00.247  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:30:00.247  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:30:00.247  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:30:00.248  3738  3787 D BluetoothAdapter: STATE_ON
,09-07 15:30:00.251  4115  4125 D BtGatt.GattService: registerClient() - UUID=d20448af-a76d-4c5f-942e-725bd8d24483
,09-07 15:30:00.253  4115  4131 D BtGatt.GattService: onClientRegistered() - UUID=d20448af-a76d-4c5f-942e-725bd8d24483, clientIf=5
09-07 15:30:00.254  3738  3750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 15:30:00.256  4115  4132 D BtGatt.GattService: start scan with filters
,09-07 15:30:00.263  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 15:30:00.263  4115  4135 D BtGatt.ScanManager: handling starting scan
09-07 15:30:00.263  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:30:00.264  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:30:00.264  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 15:30:00.265  4115  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c2536a
,09-07 15:30:00.267  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:30:00.267  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:30:00.268  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:30:00.270  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:30:00.272  4115  4131 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 15:30:00.272  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.274  4115  4135 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 15:30:00.279  3738  3787 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 15:30:00.279  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:30:00.279  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 15:30:00.279  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.279  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:30:00.280  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:30:00.280  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 15:30:00.280  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:30:00.280  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:30:00.280  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:30:00.280  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 15:30:00.281  3738  3787 D BluetoothAdapter: STATE_ON
09-07 15:30:00.282  4115  4132 D BtGatt.GattService: stopScan() - queue size =1
,09-07 15:30:00.283  4115  4144 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 15:30:00.284  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 15:30:00.284  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:30:00.284  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 15:30:00.284  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 15:30:00.284  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:30:00.288  4115  4131 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 15:30:00.288  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:30:00.288  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.288  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:30:00.289  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:30:00.289  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:00.289  4115  4135 D BtGatt.ScanManager: Starting BLE batch scan
09-07 15:30:00.290  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:30:00.290  4115  4135 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 15:30:00.292  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:00.292  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:00.292  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:30:00.296  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:00.297  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:30:00.297  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:00.298  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:00.298  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.298  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:30:00.298  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.298  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7d301 removed from the list
09-07 15:30:00.298  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.299  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2555a6 removed from the list
09-07 15:30:00.299  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:00.299  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:00.300  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.300  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:00.303  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:30:00.303  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 15:30:00.303  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.303  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2555a6 not in the list
,09-07 15:30:00.304  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.304  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:00.305  4115  4131 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 15:30:00.305  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.305  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.306  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:30:00.306  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.306  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d9e3d removed from the list
,09-07 15:30:00.306  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:00.306  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.307  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:00.307  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.307  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abe1394 removed from the list
09-07 15:30:00.308  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:00.309  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8ae139 added. We now have 2 listener(s)
,09-07 15:30:00.312  4115  4131 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 15:30:00.312  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.313  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:30:00.313  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.313  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:30:00.314  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:00.314  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd7737e added. We now have 9 listener(s)
,09-07 15:30:00.314  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:30:00.315  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-07 15:30:00.320  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:00.320  4115  4131 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 15:30:00.320  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.320  4115  4135 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:00.325  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:30:00.327  4115  4131 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 15:30:00.327  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.327  4115  4135 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 15:30:00.328  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:30:00.328  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:30:00.329  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:00.330  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@570412c added. We now have 3 listener(s),
09-07 15:30:00.330  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:00.332  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:30:00.332  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:30:00.332  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:00.332  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:00.333  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:00.332  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8af57f5 added. We now have 10 listener(s)
09-07 15:30:00.333  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:00.333  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:00.334  4115  4131 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 15:30:00.334  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.335  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 15:30:00.335  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:00.335  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:30:00.335  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:00.335  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 15:30:00.338  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 15:30:00.339  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:30:00.342  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:30:00.343  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 15:30:00.343  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:30:00.346  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:30:00.346  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:30:00.346  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:30:00.347  3738  3787 D BluetoothAdapter: STATE_ON
,09-07 15:30:00.348  4115  4125 D BtGatt.GattService: registerClient() - UUID=1e49bc9c-913f-481f-a6d0-527a10f14de0
09-07 15:30:00.349  4115  4131 D BtGatt.GattService: onClientRegistered() - UUID=1e49bc9c-913f-481f-a6d0-527a10f14de0, clientIf=5
,09-07 15:30:00.349  3738  3750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 15:30:00.349  4115  4144 D BtGatt.GattService: start scan with filters
,09-07 15:30:00.352  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 15:30:00.352  4115  4135 D BtGatt.ScanManager: handling starting scan
09-07 15:30:00.352  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:30:00.352  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 15:30:00.352  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 15:30:00.355  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:30:00.355  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 15:30:00.355  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:30:00.357  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:30:00.358  4115  4131 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 15:30:00.358  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.359  4115  4135 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 15:30:00.360  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 15:30:00.360  3738  3787 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 15:30:00.360  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:00.360  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:30:00.360  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:00.361  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:00.361  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.361  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:30:00.361  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.361  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8ae139 removed from the list
09-07 15:30:00.361  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.361  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd7737e removed from the list
09-07 15:30:00.361  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:00.361  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:00.362  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.362  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 15:30:00.362  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.362  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:00.363  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:30:00.363  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.363  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.363  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd7737e not in the list
,09-07 15:30:00.363  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:30:00.363  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:30:00.363  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:30:00.364  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 15:30:00.364  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:30:00.364  4115  4131 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 15:30:00.364  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.365  3738  3787 D BluetoothAdapter: STATE_ON
09-07 15:30:00.365  4115  4135 D BtGatt.ScanManager: Starting BLE batch scan
09-07 15:30:00.365  4115  4135 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 15:30:00.365  4115  4132 D BtGatt.GattService: stopScan() - queue size =1
,09-07 15:30:00.366  4115  4126 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 15:30:00.366  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:30:00.366  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:30:00.366  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:30:00.367  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:30:00.367  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:30:00.368  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:30:00.368  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:30:00.368  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:30:00.368  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 15:30:00.369  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:30:00.370  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:30:00.370  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:00.370  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:30:00.371  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.371  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:30:00.371  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.371  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8af57f5 removed from the list
09-07 15:30:00.371  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:30:00.371  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.371  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.371  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 15:30:00.371  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@570412c removed from the list
09-07 15:30:00.372  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:00.372  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6a7e71 added. We now have 2 listener(s)
,09-07 15:30:00.374  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:30:00.374  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.374  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:00.374  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:00.374  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8447456 added. We now have 9 listener(s)
09-07 15:30:00.374  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:00.375  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:00.375  4115  4131 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 15:30:00.375  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.377  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:30:00.382  4115  4131 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:00.382  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:00.382  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.384  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.384  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:30:00.385  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:30:00.385  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5789c4 added. We now have 3 listener(s)
,09-07 15:30:00.386  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 15:30:00.389  4115  4131 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 15:30:00.389  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:00.389  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.389  4115  4135 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:30:00.390  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
09-07 15:30:00.390  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:30:00.390  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:30:00.390  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:00.391  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d790ad added. We now have 10 listener(s)
,09-07 15:30:00.391  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:30:00.391  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:00.391  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:30:00.391  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 15:30:00.391  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:00.391  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:30:00.394  3738  3787 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 15:30:00.395  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:30:00.396  4115  4131 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 15:30:00.396  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.396  4115  4135 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 15:30:00.399  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:30:00.399  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 15:30:00.399  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:30:00.402  4115  4131 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 15:30:00.402  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.403  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:30:00.403  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:30:00.403  3738  3787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:30:00.404  3738  3787 D BluetoothAdapter: STATE_ON
,09-07 15:30:00.405  4115  4132 D BtGatt.GattService: registerClient() - UUID=631cc818-c16e-4377-b89e-868de7e10407
,09-07 15:30:00.406  4115  4131 D BtGatt.GattService: onClientRegistered() - UUID=631cc818-c16e-4377-b89e-868de7e10407, clientIf=5
,09-07 15:30:00.406  3738  3750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 15:30:00.406  4115  4126 D BtGatt.GattService: start scan with filters
,09-07 15:30:00.408  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 15:30:00.408  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:30:00.408  4115  4135 D BtGatt.ScanManager: handling starting scan
09-07 15:30:00.408  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 15:30:00.408  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 15:30:00.411  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:30:00.411  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:30:00.411  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:30:00.413  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:30:00.414  4115  4131 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 15:30:00.414  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.414  4115  4135 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 15:30:00.417  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:30:00.417  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:00.417  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 15:30:00.417  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:30:00.418  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.418  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:30:00.418  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.418  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6a7e71 removed from the list
,09-07 15:30:00.418  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.418  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8447456 removed from the list
,09-07 15:30:00.418  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:00.418  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:30:00.418  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.419  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-07 15:30:00.419  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.419  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:00.420  4115  4131 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 15:30:00.420  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:00.420  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.420  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.420  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.420  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8447456 not in the list
09-07 15:30:00.420  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:30:00.420  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 15:30:00.420  4115  4135 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:30:00.420  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:30:00.420  4115  4135 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 15:30:00.420  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 15:30:00.420  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 15:30:00.421  3738  3787 D BluetoothAdapter: STATE_ON
,09-07 15:30:00.421  4115  4125 D BtGatt.GattService: stopScan() - queue size =1
09-07 15:30:00.422  4115  4132 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 15:30:00.422  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-07 15:30:00.422  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:30:00.422  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 15:30:00.422  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:30:00.423  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:30:00.424  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:30:00.424  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:30:00.424  3738  3787 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:30:00.424  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:30:00.424  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.425  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:00.425  3738  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:30:00.425  3738  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:30:00.426  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.426  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:00.426  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.426  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d790ad removed from the list
,09-07 15:30:00.426  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:30:00.426  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.426  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.426  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.426  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5789c4 removed from the list
,09-07 15:30:00.427  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:00.427  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1898aa9 added. We now have 2 listener(s)
09-07 15:30:00.428  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:30:00.428  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.429  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:00.429  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:30:00.429  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@785b82e added. We now have 9 listener(s)
,09-07 15:30:00.429  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:00.429  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:30:00.430  4115  4131 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 15:30:00.431  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:30:00.432  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:30:00.436  3738  3787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:30:00.437  4115  4131 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 15:30:00.437  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.441  3738  3787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:30:00.441  3738  3787 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:30:00.441  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:30:00.441  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39c4d5c added. We now have 3 listener(s)
09-07 15:30:00.443  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:30:00.443  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 15:30:00.443  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:30:00.443  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:30:00.444  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:30:00.444  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a472865 added. We now have 10 listener(s)
09-07 15:30:00.444  3738  3787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:30:00.444  3738  3787 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:30:00.444  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:30:00.444  3738  3787 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:30:00.444  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:30:00.444  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.444  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:30:00.444  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.444  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1898aa9 removed from the list
09-07 15:30:00.444  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:30:00.445  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@785b82e removed from the list
09-07 15:30:00.448  3738  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:30:00.448  3738  3787 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:30:00.448  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.448  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.449  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.449  4115  4131 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 15:30:00.449  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.449  4115  4135 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:30:00.451  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:00.451  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.451  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.452  3738  3787 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@785b82e not in the list
09-07 15:30:00.452  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:30:00.452  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.453  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:30:00.453  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:30:00.453  3738  3787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:30:00.453  3738  3787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a472865 removed from the list
09-07 15:30:00.453  3738  3787 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:30:00.453  3738  3787 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:30:00.453  3738  3787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:30:00.453  3738  3787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:30:00.453  3738  3787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39c4d5c removed from the list
09-07 15:30:00.454  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-07 15:30:00.454  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 15:30:00.454  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 15:30:00.454  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:30:00.454  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 15:30:00.454  3738  3787 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:30:00.456  4115  4131 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 15:30:00.457  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.457  4115  4135 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 15:30:00.460  3738  4190 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: My test thread name)
09-07 15:30:00.460  3738  4190 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: My test thread name)
,09-07 15:30:00.460  3738  4190 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 15:30:00.462  4115  4131 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 15:30:00.462  4115  4131 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:30:00.462  3738  4191 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: My test thread name)
09-07 15:30:00.462  3738  4191 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: My test thread name)
,09-07 15:30:00.462  3738  4191 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 15:30:00.464  3738  3787 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 15:30:00.465  3738  3787 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-07 15:30:00.465  3738  3787 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 15:30:00.465  3738  3787 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 15:30:00.465  3738  3787 D com.test.thalitest.ThaliTestRunner: Total duration: 22893 ms
,09-07 15:30:00.466  3738  3787 I jxcore-log: *Native tests were executed*
09-07 15:30:00.466  3738  3787 I jxcore-log: 
09-07 15:30:00.467  3738  3787 I jxcore-log: Total number of executed tests:  80
09-07 15:30:00.467  3738  3787 I jxcore-log: 
09-07 15:30:00.467  3738  3787 I jxcore-log: Number of passed tests:  80
09-07 15:30:00.467  3738  3787 I jxcore-log: 
09-07 15:30:00.467  3738  3787 I jxcore-log: Number of failed tests:  0
09-07 15:30:00.467  3738  3787 I jxcore-log: 
09-07 15:30:00.467  3738  3787 I jxcore-log: Number of ignored tests:  0
09-07 15:30:00.467  3738  3787 I jxcore-log: 
,09-07 15:30:00.468  3738  3787 I jxcore-log: Total duration:  22893
09-07 15:30:00.468  3738  3787 I jxcore-log: 
09-07 15:30:00.468  3738  3787 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 15:30:00.468  3738  3787 I jxcore-log: 
,09-07 15:30:00.474  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.474  3738  3787 I jxcore-log: 
09-07 15:30:00.476  3738  3738 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 15:30:00.478  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.478  3738  3787 I jxcore-log: 
09-07 15:30:00.479  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.479  3738  3787 I jxcore-log: 
09-07 15:30:00.479  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.479  3738  3787 I jxcore-log: 
09-07 15:30:00.480  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.480  3738  3787 I jxcore-log: 
09-07 15:30:00.482  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.482  3738  3787 I jxcore-log: 
,09-07 15:30:00.484  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.484  3738  3787 I jxcore-log: 
,09-07 15:30:00.486  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:00.486  3738  3787 I jxcore-log: 
,09-07 15:30:00.487  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:00.487  3738  3787 I jxcore-log: 
,09-07 15:30:00.487  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.487  3738  3787 I jxcore-log: 
,09-07 15:30:00.488  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.488  3738  3787 I jxcore-log: 
,09-07 15:30:00.489  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:30:00.489  3738  3787 I jxcore-log: 
,09-07 15:30:00.490  2010  2641 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 15:30:00.491  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:00.491  3738  3787 I jxcore-log: 
,09-07 15:30:00.492  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:30:00.492  3738  3787 I jxcore-log: 
,09-07 15:30:00.493  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.493  3738  3787 I jxcore-log: 
,09-07 15:30:00.494  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.494  3738  3787 I jxcore-log: 
,09-07 15:30:00.494  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.494  3738  3787 I jxcore-log: 
,09-07 15:30:00.495  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.495  3738  3787 I jxcore-log: 
,09-07 15:30:00.496  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.496  3738  3787 I jxcore-log: 
,09-07 15:30:00.497  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.497  3738  3787 I jxcore-log: 
,09-07 15:30:00.497  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-07 15:30:00.497  3738  3787 I jxcore-log: 
,09-07 15:30:00.498  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.498  3738  3787 I jxcore-log: 
,09-07 15:30:00.499  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.499  3738  3787 I jxcore-log: 
,09-07 15:30:00.500  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:30:00.500  3738  3787 I jxcore-log: 
,09-07 15:30:00.501  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:30:00.501  3738  3787 I jxcore-log: 
,09-07 15:30:00.502  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:30:00.502  3738  3787 I jxcore-log: 
09-07 15:30:00.504  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.504  3738  3787 I jxcore-log: 
09-07 15:30:00.504  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.504  3738  3787 I jxcore-log: 
,09-07 15:30:00.505  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.505  3738  3787 I jxcore-log: 
,09-07 15:30:00.506  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.506  3738  3787 I jxcore-log: 
,09-07 15:30:00.506  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.506  3738  3787 I jxcore-log: 
,09-07 15:30:00.508  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:30:00.508  3738  3787 I jxcore-log: 
,09-07 15:30:00.793  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:30:00.796  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:30:00.796  3738  3787 I jxcore-log: 
,09-07 15:30:00.871  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:30:00.874  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:30:00.874  3738  3787 I jxcore-log: 
,09-07 15:30:00.926  3738  3738 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:30:00.929  3738  3787 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:30:00.929  3738  3787 I jxcore-log: 
,09-07 15:30:01.085  4192  4192 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-07 15:30:01.091  4192  4192 D AndroidRuntime: CheckJNI is OFF
,09-07 15:30:01.134  4192  4192 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-07 15:30:01.180  4192  4192 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 15:30:01.203  4192  4192 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 15:30:01.215   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-07 15:30:01.215   873   886 I ActivityManager: Killing 3738:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-07 15:30:01.321   873  1524 D GraphicsStats: Buffer count: 2
,09-07 15:30:01.321   873  1990 I WindowState: WIN DEATH: Window{4b4e94f u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 15:30:01.322   873  1304 D WifiService: Client connection lost with reason: 4
,09-07 15:30:01.331   873   896 W PackageSettings: Skipping PackageSetting{2557ecf com.example.hello/10273} due to missing metadata
,09-07 15:30:01.376   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-07 15:30:01.377   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-07 15:30:01.378   873   896 I art     : Starting a blocking GC Explicit
,09-07 15:30:01.382   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-07 15:30:01.382   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 15:30:01.382   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.382   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.382   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:30:01.382   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-07 15:30:01.388   873   886 I ActivityManager:   Force finishing activity ActivityRecord{fbb24e4 u0 com.test.thalitest/.MainActivity t4}
,09-07 15:30:01.396   873  1984 W ActivityManager: Spurious death for ProcessRecord{420eef9 0:com.test.thalitest/u0a0}, curProc for 3738: null
,09-07 15:30:01.427   873   896 I art     : Explicit concurrent mark sweep GC freed 13567(939KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 825us total 47.549ms
,09-07 15:30:01.459   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 15:30:01.461  4192  4192 I art     : System.exit called, status: 0
09-07 15:30:01.461  4192  4192 I AndroidRuntime: VM exiting with result code 0.
,09-07 15:30:01.464   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-07 15:30:01.482   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-07 15:30:01.487  4115  4115 D BluetoothMapAppObserver: onReceive
,09-07 15:30:01.487  4115  4115 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-07 15:30:01.488  2010  2272 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 15:30:01.494   873  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 15:30:01.494  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-07 15:30:01.495  3583  3583 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 15:30:01.508  1874  4204 I Keyboard.Facilitator.DecoderInitializer: run()
,09-07 15:30:01.513  1947  1947 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-07 15:30:01.516   873  1995 I ActivityManager: Start proc 4205:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 15:30:01.532  1874  4204 I Decoder : createOrResetDecoder
,09-07 15:30:01.569  4205  4205 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 15:30:01.576  1510  1510 I ConfigService: onCreate
,09-07 15:30:01.586   873  1995 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3738 uid 10000
,09-07 15:30:01.586   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 15:30:01.586  1510  4218 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-07 15:30:01.587  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-07 15:30:01.601  1874  4204 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-07 15:30:01.632   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-07 15:30:01.633   873   885 E PackageManager: Failed to write settings, restoring backup
09-07 15:30:01.633   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 15:30:01.633   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 15:30:01.633   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 15:30:01.633   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 15:30:01.633   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 15:30:01.633   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.633   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.633   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 15:30:01.633  1963  2054 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-07 15:30:01.635  4205  4205 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 15:30:01.637   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-07 15:30:01.637   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 15:30:01.637   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.637   873   886 E DropBoxManagerService: 	... 13 more
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase:, 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.644  4205  4220 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.,java:102)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.644  4205  4220 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:30:01.648   873  1694 I ActivityManager: Start proc 4223:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-07 15:30:01.649  1963  2054 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 15:30:01.649  1963  2054 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1963
09-07 15:30:01.649  1963  2054 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.649  1963  2054 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:30:01.652   873  1993 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 15:30:01.653   873  4231 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:30:01.653   873  4231 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.653   873  4231 E DropBoxManagerService: 	... 5 more
09-07 15:30:01.658  1963  2054 I Process : Sending signal. PID: 1963 SIG: 9
09-07 15:30:01.662  1874  4204 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 15:30:01.664  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 15:30:01.664  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 15:30:01.666  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 15:30:01.666  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 15:30:01.666  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 15:30:01.667  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 15:30:01.667  1874  4204 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 15:30:01.667  1874  4204 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 15:30:01.667  1874  4204 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 15:30:01.667  1874  4204 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 15:30:01.667  1874  4204 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 15:30:01.668  1874  4204 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 15:30:01.671  4205  4237 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 15:30:01.673   873  1995 I ActivityManager: Start proc 4238:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-07 15:30:01.729  4238  4238 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-07 15:30:01.767   873  1984 D GraphicsStats: Buffer count: 1
,09-07 15:30:01.767   873   883 I WindowState: WIN DEATH: Window{f0717b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-07 15:30:01.775  1510  1510 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-07 15:30:01.776  1510  1510 D AndroidRuntime: Shutting down VM
,09-07 15:30:01.776  1510  1510 E AndroidRuntime: FATAL EXCEPTION: main
09-07 15:30:01.776  1510  1510 E AndroidRuntime: Process: com.google.process.gapps, PID: 1510
09-07 15:30:01.776  1510  1510 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 15:30:01.776  1510  1510 E AndroidRuntime: 	... 8 more
,09-07 15:30:01.781   873  1984 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1963) has died
,09-07 15:30:01.782   873  1984 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-07 15:30:01.783   873  1984 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-07 15:30:01.803   873   886 I ActivityManager: Start proc 4255:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 15:30:01.808   873  4262 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:30:01.808   873  4262 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.808   873  4262 E DropBoxManagerService: 	... 5 more
,09-07 15:30:01.811  1510  1510 I Process : Sending signal. PID: 1510 SIG: 9
,09-07 15:30:01.817  4205  4220 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-07 15:30:01.832  1720  4266 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,09-07 15:30:01.832  1720  4266 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@dd58983
,09-07 15:30:01.832   873  1524 I ActivityManager: Process com.google.process.gapps (pid 1510) early provider death
,09-07 15:30:01.835  4205  4237 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.835  4205  4237 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 15:30:01.835  4205  4237 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 15:30:01.835  4205  4237 E AndroidRuntime: Process: android.process.acore, PID: 4205
09-07 15:30:01.835  4205  4237 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.835  4205  4237 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 15:30:01.836  4205  4220 I Process : Sending signal. PID: 4205 SIG: 9
,09-07 15:30:01.844   873  1304 D WifiService: Client connection lost with reason: 4
,09-07 15:30:01.848   873  1524 I ActivityManager: Process com.google.process.gapps (pid 1510) has died
,09-07 15:30:01.849   873  1524 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-07 15:30:01.849   873  1524 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,09-07 15:30:01.849   873  1524 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,09-07 15:30:01.849   873  1524 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,09-07 15:30:01.851   873  1995 W ActivityManager: Spurious death for ProcessRecord{bc3c541 0:com.google.process.gapps/u0a11}, curProc for 1510: null
,09-07 15:30:01.853   873  4269 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:30:01.853   873  4269 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	,at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.853   873  4269 E DropBoxManagerService: 	... 5 more
,09-07 15:30:01.854  4255  4255 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:30:01.854  4255  4255 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:30:01.854  4255  4255 D AndroidRuntime: Shutting down VM
,09-07 15:30:01.865   873  1994 I ActivityManager: Start proc 4270:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-07 15:30:01.868  1720  1720 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-07 15:30:01.873  4255  4255 E AndroidRuntime: FATAL EXCEPTION: main
09-07 15:30:01.873  4255  4255 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4255
09-07 15:30:01.873  4255  4255 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 15:30:01.873  4255  4255 E AndroidRuntime: 	... 10 more
09-07 15:30:01.874   873  1694 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 15:30:01.875  4255  4255 I Process : Sending signal. PID: 4255 SIG: 9
09-07 15:30:01.880   873  4282 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:30:01.880   873  4282 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.880   873  4282 E DropBoxManagerService: 	... 5 more
09-07 15:30:01.891   873   884 I ActivityManager: Process android.process.acore (pid 4205) has died
09-07 15:30:01.891   873   884 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-07 15:30:01.897  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 15:30:01.897  1720  1720 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 15:30:01.899  4270  4270 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-07 15:30:01.900   873  1365 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4255) has died
09-07 15:30:01.901  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 15:30:01.901  1720  1720 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 15:30:01.902   873  1365 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 15:30:01.904  4270  4270 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:30:01.906  4270  4270 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 15:30:01.907  4270  4270 D AndroidRuntime: Shutting down VM
09-07 15:30:01.908  4270  4270 E AndroidRuntime: FATAL EXCEPTION: main
09-07 15:30:01.908  4270  4270 E AndroidRuntime: Process: com.google.process.gapps, PID: 4270
09-07 15:30:01.908  4270  4270 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 15:30:01.908  4270  4270 E AndroidRuntime: 	... 10 more
09-07 15:30:01.914  1720  4285 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-07 15:30:01.917   873   886 I ActivityManager: Start proc 4286:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 15:30:01.922  4270  4270 I Process : Sending signal. PID: 4270 SIG: 9
09-07 15:30:01.930  2030  4299 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-07 15:30:01.930   873  4297 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:30:01.930   873  4297 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.930   873  4297 E DropBoxManagerService: 	... 5 more
,09-07 15:30:01.932  1720  4285 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-07 15:30:01.932  1720  4285 E AndroidRuntime: Process: com.google.android.gms, PID: 1720
09-07 15:30:01.932  1720  4285 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:30:01.932  1720  4285 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,09-07 15:30:01.934  1720  4285 I Process : Sending signal. PID: 1720 SIG: 9
09-07 15:30:01.935   873  4301 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:30:01.935   873  4301 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:30:01.935   873  4301 E DropBoxManagerService: 	... 5 more
09-07 15:30:01.940   873  1694 I ActivityManager: Process com.google.process.gapps (pid 4270) has died
09-07 15:30:01.940   873  1694 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a938802 u0 com.google.android.gms/.gcm.GcmService}
09-07 15:30:01.940   873  1694 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a22d367 u0 com.google.android.gms/.config.ConfigService}
09-07 15:30:01.940   873  1694 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{26f0fc3 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
09-07 15:30:01.941   873  1694 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{26cd360 u0 com.google.android.gms/.auth.GetToken}
09-07 15:30:01.952   873  1694 I ActivityManager: Start proc 4302:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,09-07 15:30:01.980  4286  4286 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:30:01.980  4286  4286 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 15:30:01.980  4286  4286 D AndroidRuntime: Shutting down VM
09-07 15:30:01.983   278   278 E lowmemorykiller: Error writing /proc/1720/oom_score_adj; errno=22

```
