#### Test 81418577b7b45c2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 14:23:10.913  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:10.931  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 14:23:10.936  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 14:23:10.998  1512  2147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 14:23:10.999  1512  2147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 14:23:10.999  1512  2147 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:10.999  1512  2147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 14:23:11.035  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 14:23:11.035  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 14:23:11.036  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-16 14:23:11.597  3779  3779 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 14:23:11.602  3779  3779 D AndroidRuntime: CheckJNI is OFF
08-16 14:23:11.637  3779  3779 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 14:23:11.679  3779  3779 I Radio-JNI: register_android_hardware_Radio DONE
08-16 14:23:11.700  3779  3779 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 14:23:11.706   872  2018 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 14:23:11.753  2068  2091 W SearchService: Abort, client detached.
08-16 14:23:11.762  2068  2068 I HotwordDetector: Closing mic
08-16 14:23:11.762  2068  2325 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6089cda
08-16 14:23:11.762  2068  2341 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 14:23:11.763  3779  3779 D AndroidRuntime: Shutting down VM
08-16 14:23:11.784   872  1611 I ActivityManager: Start proc 3788:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 14:23:11.826   375  2344 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 14:23:11.826   375  2344 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 14:23:11.834   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 14:23:11.836  2068  2328 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 14:23:11.837  2068  2340 I MicroRecognitionRnrImpl: Detection finished
08-16 14:23:11.866  3788  3788 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 14:23:11.894  3788  3788 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 14:23:11.901  3788  3788 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8833-8836)
08-16 14:23:11.901  3788  3788 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:23:11.915  3788  3788 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2313e59}
08-16 14:23:11.915  3788  3788 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:23:11.916  3788  3788 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:23:11.921  3788  3788 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 14:23:11.922  3788  3788 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 14:23:11.952  3788  3788 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 14:23:11.961  3788  3788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:23:11.961  3788  3788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:23:11.961  3788  3788 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 14:23:11.961  3788  3788 I Adreno  : Build Date                       : 10/20/15
08-16 14:23:11.961  3788  3788 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 14:23:11.961  3788  3788 I Adreno  : Local Branch                     : M14
08-16 14:23:11.961  3788  3788 I Adreno  : Remote Branch                    : 
08-16 14:23:11.961  3788  3788 I Adreno  : Remote Branch                    : 
08-16 14:23:11.961  3788  3788 I Adreno  : Reconstruct Branch               : 
,08-16 14:23:12.070   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10e8c3:true
,08-16 14:23:12.102  3788  3788 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 14:23:12.115  3788  3788 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 14:23:12.159  3788  3826 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 14:23:12.170  3788  3813 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 14:23:12.201  3788  3826 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 14:23:12.230  1891  1891 I Keyboard.Facilitator: onFinishInput()
,08-16 14:23:12.304   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +540ms
,08-16 14:23:12.413  3788  3788 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3788
,08-16 14:23:12.597   872  2018 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 14:23:12.599  3788  3788 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 14:23:12.635   872  2018 I ActivityManager: Killing 3212:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 14:23:12.757  3788  3829 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1680934608
,08-16 14:23:12.766  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 14:23:12.766  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 14:23:12.766  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 14:23:12.766  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 14:23:12.766  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 14:23:12.766  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df5e624 added. We now have 1 listener(s)
,08-16 14:23:12.769  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 14:23:12.770  3788  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:12.770  3788  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:23:12.771  3788  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 14:23:12.774  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a764f53 added. We now have 1 listener(s)
08-16 14:23:12.774  3788  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:12.784  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:12.785  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 14:23:12.784   872  1314 D WifiService: New client listening to asynchronous messages
,08-16 14:23:12.787  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 14:23:12.787  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 14:23:12.788  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 14:23:12.792  3788  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:12.794  3788  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 14:23:12.808  3788  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:12.809  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:12.809  3788  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 14:23:12.809  3788  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:12.810  3788  3829 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:23:12.812  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:12.814  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:12.843  3788  3788 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 14:23:13.375  3788  3798 I art     : Background sticky concurrent mark sweep GC freed 68771(6MB) AllocSpace objects, 18(1604KB) LOS objects, 30% free, 22MB/32MB, paused 632us total 125.217ms
,08-16 14:23:14.082  3788  3838 W jxcore-log: Initializing JXcore engine
,08-16 14:23:14.082  3788  3838 W jxcore-log: JXcore engine is ready
,08-16 14:23:14.130  3838  3838 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8987 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 14:23:14.130  3838  3838 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9676]" dev="sockfs" ino=9676 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 14:23:14.130  3838  3838 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 14:23:14.142  3788  3838 W jxcore-log: Starting JXcore engine
,08-16 14:23:14.130  3838  3838 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26049]" dev="sockfs" ino=26049 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 14:23:14.242  3788  3838 W jxcore-log: Platform android
08-16 14:23:14.242  3788  3838 W jxcore-log: 
,08-16 14:23:14.244  3788  3838 W jxcore-log: Process ARCH arm
08-16 14:23:14.244  3788  3838 W jxcore-log: 
,08-16 14:23:14.432  3788  3838 I jxcore-log: JXcore Cordova bridge is ready!
08-16 14:23:14.432  3788  3838 I jxcore-log: 
08-16 14:23:14.433  3788  3838 W jxcore-log: JXcore engine is started
,08-16 14:23:14.445  3788  3829 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 14:23:14.451  3788  3788 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 14:23:15.755   872  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 14:23:19.801  3591  3845 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 14:23:19.820  3591  3846 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 14:23:19.835  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:19.841  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:19.886  1512  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 14:23:19.886  1512  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 14:23:19.886  1512  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:19.886  1512  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:19.938  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:19.945  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:20.005  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 14:23:20.005  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 14:23:20.006  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:20.006  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:20.049  3591  3846 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 14:23:20.052  3591  3845 E BooksSync: Soft error
08-16 14:23:20.052  3591  3845 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 14:23:20.052  3591  3845 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 14:23:20.056  3591  3845 E BooksSync: Sync error
08-16 14:23:20.056  3591  3845 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 14:23:20.056  3591  3845 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 14:23:20.056  3591  3845 I BooksSync: Finished books sync
,08-16 14:23:20.069   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126693, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 14:23:24.489  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 14:23:24.489  3788  3838 I jxcore-log: 
,08-16 14:23:24.491  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 14:23:24.491  3788  3838 I jxcore-log: 
,08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:24.503  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:24.511  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:24.513  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 14:23:24.513  3788  3838 I jxcore-log: 
,08-16 14:23:24.515  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 14:23:24.515  3788  3838 I jxcore-log: 
,08-16 14:23:24.843  3788  3838 D ExecuteNativeTests: Running unit tests
,08-16 14:23:24.902  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:23:24.902  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb added. We now have 2 listener(s)
08-16 14:23:24.903  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:23:24.903  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:23:24.903  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:24.903  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:24.903  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 added. We now have 2 listener(s)
08-16 14:23:24.903  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:24.904  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:24.907  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:24.919  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:24.923  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:24.923  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:24.926  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 14:23:24.926  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 14:23:24.926  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 14:23:24.927  3788  3838 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 14:23:24.927  3788  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 14:23:24.927  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:23:24.927  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:23:24.927  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:23:24.928  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:24.929  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:24.929  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:24.929  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:24.929  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-16 14:23:24.929  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:24.929  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:24.929  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb removed from the list
08-16 14:23:24.929  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:24.929  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 removed from the list
08-16 14:23:24.930  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:24.933  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:24.934  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:24.934  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.934  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:24.934  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.936  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:24.937  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:24.937  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:24.937  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:24.939  3788  3838 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 14:23:24.939  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:24.939  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:24.939  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:24.939  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:24.939  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:24.939  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.939  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:24.939  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:24.940  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:24.940  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:24.940  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:24.940  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.940  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:24.940  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.941  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:24.941  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:24.941  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:24.941  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:23:24.946  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1,310:1310:1310:1310]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:23:24.947  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:23:24.948  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:23:24.948  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:24.948  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:24.948  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:24.948  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:24.948  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:24.948  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.948  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
,08-16 14:23:24.948  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:24.948  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:24.948  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:24.948  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:24.948  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.948  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:24.948  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:24.950  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:24.950  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:24.950  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:24.950  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:24.951  3788  3838 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:23:24.953  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:24.956  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:24.957  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:24.957  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:24.957  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:24.957  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:24.958  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:24.958  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:24.958  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:23:24.961  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:24.964  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 14:23:24.964  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:24.964  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:24.978  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:23:24.982  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:23:24.983  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:24.985  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 14:23:24.989  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 14:23:24.989  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 14:23:24.989  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:23:24.990  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:23:24.991  3788  3838 D BluetoothAdapter: STATE_ON
,08-16 14:23:24.994  2669  2684 D BtGatt.GattService: registerClient() - UUID=ea7092aa-3e66-4593-9e8b-00cef6563a57
,08-16 14:23:24.995  2669  2691 D BtGatt.GattService: onClientRegistered() - UUID=ea7092aa-3e66-4593-9e8b-00cef6563a57, clientIf=5
,08-16 14:23:24.997  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 14:23:24.999  2669  2786 D BtGatt.GattService: start scan with filters,
,08-16 14:23:25.001  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:25.002  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 14:23:25.002  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:25.002  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:25.003  2669  2694 D BtGatt.ScanManager: handling starting scan
08-16 14:23:25.004  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:25.004  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:25.005  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:23:25.006  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:23:25.009  2669  2694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:25.009  3788  3838 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 14:23:25.011  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.011  3788  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 14:23:25.011  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.012  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:23:25.012  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.012  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:25.012  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:25.012  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:25.012  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:25.012  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:25.012  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:25.013  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:23:25.013  3788  3838 D BluetoothAdapter: STATE_ON
,08-16 14:23:25.013  2669  2684 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:23:25.015  2669  2786 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:23:25.015  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:23:25.015  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:25.015  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 14:23:25.015  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:25.015  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:23:25.016  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:25.016  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:23:25.016  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:25.017  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:25.017  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:25.019  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:25.019  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:23:25.019  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:25.019  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.019  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.019  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:25.019  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.019  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.019  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.019  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:25.019  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.020  3788  3838 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:23:25.020  2669  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 14:23:25.020  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.021  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:25.022  2669  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:25.024  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:25.035  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:25.036  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:25.036  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:23:25.036  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:25.036  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 14:23:25.037  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:25.037  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:23:25.037  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:25.046  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.048  2669  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 14:23:25.048  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.049  2669  2694 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:25.049  2669  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:25.050  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 14:23:25.050  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:25.055  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:23:25.056  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 14:23:25.056  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:23:25.057  2669  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:23:25.057  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.060  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:23:25.061  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:23:25.061  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:23:25.062  3788  3838 D BluetoothAdapter: STATE_ON
08-16 14:23:25.062  2669  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:23:25.062  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.065  2669  2786 D BtGatt.GattService: registerClient() - UUID=3ea21730-27db-4486-ab59-bab69d7df74b
,08-16 14:23:25.065  2669  2691 D BtGatt.GattService: onClientRegistered() - UUID=3ea21730-27db-4486-ab59-bab69d7df74b, clientIf=5
08-16 14:23:25.065  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:23:25.065  2669  2684 D BtGatt.GattService: start scan with filters
,08-16 14:23:25.068  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 14:23:25.068  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:23:25.068  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:25.068  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:25.069  2669  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 14:23:25.069  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.069  2669  2694 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:23:25.072  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:25.072  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:23:25.072  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:25.074  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:23:25.076  2669  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:23:25.076  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.076  2669  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 14:23:25.077  3788  3838 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:23:25.079  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:25.079  3788  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 14:23:25.079  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.079  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:23:25.079  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.079  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:23:25.079  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:25.079  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:25.079  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:25.080  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 14:23:25.080  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:25.080  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:23:25.080  3788  3838 D BluetoothAdapter: STATE_ON
08-16 14:23:25.081  2669  2684 D BtGatt.GattService: stopScan() - queue size =0
08-16 14:23:25.082  2669  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:25.082  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.082  2669  2776 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:23:25.083  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:23:25.083  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:25.083  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:25.083  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:25.083  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 14:23:25.084  2669  2694 D BtGatt.ScanManager: handling starting scan
08-16 14:23:25.085  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:25.085  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:23:25.085  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:25.085  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:23:25.086  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:25.087  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.087  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.088  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:25.088  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
,08-16 14:23:25.088  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.088  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
,08-16 14:23:25.088  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:25.088  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:25.088  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:25.088  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:25.089  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.089  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.089  2669  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 14:23:25.090  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.090  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.090  2669  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:23:25.090  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.091  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:25.091  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.091  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
,08-16 14:23:25.092  3788  3838 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:23:25.094  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:25.094  2669  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:23:25.094  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.095  2669  2694 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:25.095  2669  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:25.099  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:25.101  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.101  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:25.101  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:25.101  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:25.101  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:25.101  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:25.101  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:23:25.103  2669  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:23:25.103  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.104  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:25.105  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 14:23:25.105  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:25.106  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.109  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:23:25.109  2669  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:23:25.109  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.110  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:23:25.110  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:25.115  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:23:25.115  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:23:25.115  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 14:23:25.115  3788  3838 D BluetoothAdapter: STATE_ON
08-16 14:23:25.115  2669  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:23:25.115  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.115  2669  2694 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:23:25.118  2669  2786 D BtGatt.GattService: registerClient() - UUID=77c006c2-974f-428b-a9ef-5ee321ca7de7
08-16 14:23:25.119  2669  2691 D BtGatt.GattService: onClientRegistered() - UUID=77c006c2-974f-428b-a9ef-5ee321ca7de7, clientIf=5
,08-16 14:23:25.119  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:23:25.119  2669  2684 D BtGatt.GattService: start scan with filters
,08-16 14:23:25.121  2669  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 14:23:25.121  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.121  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:25.121  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:23:25.121  2669  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 14:23:25.121  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 14:23:25.121  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:25.124  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:25.124  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:23:25.124  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:25.125  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:23:25.126  2669  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:25.126  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:25.127  3788  3838 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:23:25.127  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.127  3788  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 14:23:25.127  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.127  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:23:25.127  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.127  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:23:25.127  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:25.127  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:25.127  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:25.127  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:25.127  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:25.127  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:23:25.128  3788  3838 D BluetoothAdapter: STATE_ON
08-16 14:23:25.128  2669  2694 D BtGatt.ScanManager: handling starting scan
08-16 14:23:25.128  2669  2684 D BtGatt.GattService: stopScan() - queue size =0
,08-16 14:23:25.129  2669  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:23:25.129  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:23:25.129  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:25.129  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:25.130  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:25.130  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 14:23:25.130  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:25.131  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 14:23:25.131  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:25.131  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:23:25.131  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:25.132  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:23:25.133  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:25.133  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:25.133  2669  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 14:23:25.133  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.134  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.134  3788  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 14:23:25.134  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.134  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:25.134  2669  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 14:23:25.134  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.134  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.134  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:25.134  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.134  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.134  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.134  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.134  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.135  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.135  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.136  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.136  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.136  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.136  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.137  3788  3838 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 14:23:25.138  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:25.138  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.138  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.139  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.139  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.139  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.139  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.139  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.139  2669  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:23:25.140  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.140  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.140  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:25.140  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.140  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.140  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.140  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.140  2669  2694 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:25.140  2669  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:25.141  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:23:25.142  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.142  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.142  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.143  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:23:25.144  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.144  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.144  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:25.144  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.144  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.144  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.144  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.144  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.145  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.145  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.145  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.145  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.145  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.145  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.147  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:23:25.147  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.147  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.147  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.148  3788  3838 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 14:23:25.148  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.148  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.149  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:25.149  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:25.149  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.149  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.150  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.150  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.150  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.150  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.150  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.150  2669  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:23:25.150  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.150  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.150  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.150  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.152  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.152  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:25.152  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.152  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.153  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 14:23:25.153  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:25.153  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.154  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.154  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:25.154  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.154  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.154  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.154  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.155  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.155  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.155  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.155  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.155  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.155  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.155  2669  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:23:25.155  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.156  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.156  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.156  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.156  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
,08-16 14:23:25.157  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 14:23:25.157  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:23:25.157  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 14:23:25.157  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 14:23:25.157  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:23:25.157  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:23:25.158  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.158  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:23:25.158  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.158  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:25.158  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.158  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.158  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.158  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.158  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.158  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.159  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.159  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.159  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.159  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.160  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.160  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:25.160  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.160  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.161  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 14:23:25.161  3788  3838 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:23:25.161  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:23:25.163  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:25.163  3788  3838 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 14:23:25.163  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 14:23:25.163  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:23:25.163  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-16 14:23:25.163  2669  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:23:25.163  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:23:25.164  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:23:25.164  2669  2694 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:23:25.164  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:23:25.165  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:23:25.165  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 14:23:25.165  3788  3838 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:23:25.165  3788  3838 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 14:23:25.165  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:25.166  3788  3838 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 14:23:25.166  3788  3838 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 14:23:25.166  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:25.166  3788  3838 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:23:25.166  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 14:23:25.169  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 14:23:25.169  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 14:23:25.169  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 14:23:25.170  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 14:23:25.170  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 14:23:25.170  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 14:23:25.170  3788  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:25.170  3788  3838 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 14:23:25.170  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.171  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.171  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.171  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.171  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.171  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.171  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 14:23:25.171  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.171  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.171  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.172  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:25.172  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.172  2669  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:23:25.172  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.172  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.172  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.172  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.172  2669  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 14:23:25.173  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.173  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.173  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.173  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.174  3788  3838 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 14:23:25.174  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.174  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.174  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.174  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.174  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.174  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.175  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
,08-16 14:23:25.175  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.175  3788  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-16 14:23:25.175  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.175  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.175  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.175  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.175  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.175  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.175  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.176  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.176  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.176  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.176  3788  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 14:23:25.176  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.176  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.176  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.176  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.176  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.176  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.177  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.177  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.177  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.177  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.177  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.177  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.177  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.177  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.177  2669  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:25.177  2669  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:25.178  3788  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
08-16 14:23:25.178  3788  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
08-16 14:23:25.178  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.178  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.179  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.179  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.179  3788  3838 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-16 14:23:25.179  3788  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 14:23:25.179  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:23:25.179  3788  3838 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 14:23:25.179  3788  3838 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:23:25.179  3788  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 14:23:25.179  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:23:25.179  3788  3838 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 14:23:25.180  3788  3838 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:23:25.180  3788  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:23:25.180  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:23:25.180  3788  3838 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 14:23:25.180  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.180  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.180  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:25.180  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.180  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.180  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.180  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.180  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.180  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.180  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.180  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.180  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.180  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.180  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.181  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.181  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.181  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.182  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.182  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.182  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.182  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.182  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.182  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.182  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.182  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.182  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.182  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.182  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.182  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.182  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.182  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.183  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.183  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.183  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.183  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.183  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:25.183  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.183  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.183  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.183  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.183  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.183  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.183  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.183  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.183  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.183  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.183  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.184  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.185  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.185  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:25.185  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.185  3788  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 14:23:25.186  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:25.187  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 14:23:25.187  3788  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 14:23:25.187  3788  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 14:23:25.187  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 14:23:25.187  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 14:23:25.188  3788  3788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 14:23:25.188  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.188  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:23:25.188  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 14:23:25.188  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 14:23:25.188  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.188  3788  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 14:23:25.188  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
,08-16 14:23:25.188  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.188  3788  3788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 14:23:25.188  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:25.188  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:25.188  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:25.188  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.188  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.190  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:25.190  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.190  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:25.190  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.190  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:25.190  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.190  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:25.190  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.190  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:25.190  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.190  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.190  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.190  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.190  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
,08-16 14:23:25.190  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.190  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.190  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.190  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.190  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.191  3788  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 14:23:25.191  3788  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 14:23:25.191  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.191  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.191  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.192  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.192  3788  3788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 14:23:25.192  3788  3838 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 14:23:25.192  3788  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:23:25.192  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:23:25.193  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:23:25.194  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.194  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.194  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.194  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.194  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.194  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:25.194  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.194  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.194  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.194  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.194  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.194  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.194  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:25.194  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.196  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.196  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:25.196  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.196  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.198  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.198  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.198  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.198  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:25.198  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.199  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.199  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.199  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.199  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.199  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:25.199  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.199  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.199  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.199  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.199  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.199  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:25.199  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.200  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.200  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:25.200  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:25.200  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:25.200  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:25.200  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.200  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.200  3788  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d002ceb not in the list
08-16 14:23:25.200  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.200  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.200  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:25.200  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.201  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.201  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:25.201  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:25.202  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:25.202  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:25.202  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:25.202  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f84ea48 not in the list
08-16 14:23:25.202  3788  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 14:23:25.202  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:23:25.202  3788  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 14:23:25.202  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:23:25.203  3788  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-16 14:23:25.203  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:23:25.204  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:23:25.204  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 14:23:25.204  3788  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 14:23:25.204  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:23:25.204  3788  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 14:23:25.204  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:23:25.204  3788  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-16 14:23:25.205  3788  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 14:23:25.205  3788  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 14:23:25.205  3788  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 14:23:25.206  3788  3838 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 14:23:25.206  3788  3838 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 14:23:25.206  3788  3838 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 14:23:25.206  3788  3838 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 14:23:25.206  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:25.207  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4703ea added. We now have 2 listener(s)
08-16 14:23:25.207  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:25.208  3788  3838 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 14:23:25.209   872   882 D WifiService: setWifiEnabled: true pid=3788, uid=10000
08-16 14:23:25.209   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:23:25.210  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:25.210  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@86a26db added. We now have 3 listener(s)
08-16 14:23:25.210  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:25.217  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:25.217  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56b7578 added. We now have 4 listener(s)
08-16 14:23:25.217  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:25.219  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:25.219  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5bc451 added. We now have 5 listener(s)
08-16 14:23:25.219  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:25.222   872  2115 D WifiService: setWifiEnabled: false pid=3788, uid=10000
08-16 14:23:25.222   872  2115 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:23:25.226  2669  2686 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 14:23:25.226  2669  2686 D BluetoothAdapterProperties: Setting state to 13
,08-16 14:23:25.227  2669  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,08-16 14:23:25.227  2669  2686 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:23:25.227  2669  2686 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:25.227  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:25.233  2669  2669 D BluetoothMapService: onReceive
,08-16 14:23:25.233  2669  2669 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:25.233  2669  2669 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:23:25.234  2669  2669 D BluetoothMapService: MAP Service closeService in
08-16 14:23:25.234  2669  2669 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 14:23:25.234  2669  2669 D ObexServerSockets0: shutdown(block = true)
08-16 14:23:25.234  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:25.234  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:25.234  2669  2669 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 14:23:25.235  2669  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 14:23:25.235  2669  2669 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 14:23:25.235  2669  2773 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 14:23:25.235  2669  2788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 14:23:25.236  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:25.236  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.236  2669  2669 I BtOppRfcommListener: stopping Accept Thread
,08-16 14:23:25.236  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:25.236  2669  3421 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 14:23:25.237  2669  3421 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:23:25.238  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:23:25.239  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.240   872  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 14:23:25.240   872  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 14:23:25.240   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:23:25.241   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:23:25.242  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.245   872   885 I ActivityManager: Start proc 3855:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-16 14:23:25.249   872  1870 D DhcpClient: Clearing IP address
08-16 14:23:25.250  2669  2691 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:23:25.250   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:23:25.250  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.250  2669  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:25.251  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:25.252   371   870 D CommandListener: Setting iface cfg
08-16 14:23:25.253  2669  2669 D HeadsetService: Received stop request...Stopping profile...
08-16 14:23:25.253  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.253  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:25.254   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:25.254   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:25.255  1969  1981 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:25.255   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:25.255  1372  1383 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:25.255  1512  2491 V NativeCrypto: Read error: ssl=0x9b4d6000: I/O error during system call, Connection timed out
08-16 14:23:25.256  2669  2669 D A2dpService: Received stop request...Stopping profile...
08-16 14:23:25.257  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.257  2669  2779 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:23:25.259  1512  2491 V NativeCrypto: SSL shutdown failed: ssl=0x9b4d6000: I/O error during system call, Broken pipe
08-16 14:23:25.260   872   872 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:25.260  2669  2669 V BluetoothAdapterState: isTurn,ingOff()=true
08-16 14:23:25.260  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.260  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.260  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.260  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:25.262   872  2019 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-16 14:23:25.263   872  1867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-16 14:23:25.264  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.264   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 14:23:25.264   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 14:23:25.266   400   400 E Parcel  : Reading a NULL string not supported here.
08-16 14:23:25.266   872  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 14:23:25.267   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:23:25.268  2669  2669 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 14:23:25.268  2669  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 14:23:25.268  2669  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:25.268  2669  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:25.268  2669  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:25.268  2669  2691 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 14:23:25.268  2669  2669 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:23:25.269  2669  2669 D HidService: Received stop request...Stopping profile...
08-16 14:23:25.269  2669  2669 D HidService: Stopping Bluetooth HidService
08-16 14:23:25.270  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-16 14:23:25.270  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:25.271  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-16 14:23:25.271  1372  1372 D HidProfile: Bluetooth service disconnected
08-16 14:23:25.271  2669  2669 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:25.271  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.271  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.272  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:25.272  2669  2669 D HealthService: Received stop request...Stopping profile...
08-16 14:23:25.273   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:23:25.274   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 14:23:25.275   872  1887 D DhcpClient: Receive thread stopped
08-16 14:23:25.280  2669  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 14:23:25.280  2669  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:25.280  2669  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:25.280  2669  2760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:25.280  2669  2760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:25.280  2669  2760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:25.280  2669  2760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:25.281   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 14:23:25.282  2669  2669 D PanService: Received stop request...Stopping profile...
08-16 14:23:25.283   872  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:23:25.284  2669  2669 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:23:25.284  2669  2669 D BluetoothMapService: stop()
08-16 14:23:25.284  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:25.284  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:25.285   872  1867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-16 14:23:25.285  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.285  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:25.286  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:23:25.286  1372  1372 D PanProfile: Bluetooth service disconnected
08-16 14:23:25.287  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:25.287  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:25.287  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:25.287  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:25.287  2669  2669 D BluetoothMapAppObserver: deinitObservers()
08-16 14:23:25.287  2669  2669 D BluetoothMapAppObserver: removeReceiver()
08-16 14:23:25.289  2669  2669 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:25.289  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.289  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.289  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:25.289  2669  2669 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:23:25.289  2669  2669 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:23:25.289  1853  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:25.290  2669  2669 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:23:25.290  2669  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 14:23:25.290  2669  2691 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 14:23:25.290  2669  2669 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.290  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.291  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:25.291  2669  2669 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:23:25.291  2669  2669 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:23:25.292  2669  2669 D BluetoothMapService: MAP Service closeService in
08-16 14:23:25.292  2669  2669 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:25.292  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.292  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.292  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:25.293  2669  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 14:23:25.293  2669  2686 D BluetoothAdapterProperties: Setting state to 15
08-16 14:23:25.294  2669  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 14:23:25.295  1372  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:23:25.295  2669  2686 I BluetoothAdapterState: Entering BleOnState
08-16 14:23:25.296  1372  2076 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:23:25.296  2669  2669 D BluetoothMapService: cleanup()
08-16 14:23:25.296  1969  2134 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:25.296  2669  2669 D BluetoothMapService: MAP Service closeService in
08-16 14:23:25.296   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:25.296  1372  1384 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:23:25.297   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:25.297  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:25.297  1372  2076 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:23:25.298  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:25.298   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:25.298   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:25.299  2669  2686 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 14:23:25.299  2669  2686 D BluetoothAdapterProperties: Setting state to 16
08-16 14:23:25.299  2669  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 14:23:25.300  2669  2686 D BluetoothAdapterProperties: onBleDisable
08-16 14:23:25.300  2669  2686 I BluetoothAdapterState: Entering PendingCommandState
08-16 14:23:25.301  2669  2687 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 14:23:25.301  2669  2691 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:23:25.301  2669  2760 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 14:23:25.302  2669  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:25.302  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.304  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.305  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.306  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.329   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 14:23:25.345  3855  3855 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-16 14:23:25.350   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 14:23:25.351   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 14:23:25.351   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:25.353   872   889 D Tethering: MasterInitialState.processMessage what=3
08-16 14:23:25.354  3408  3408 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1aa258d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-16 14:23:25.355  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.356  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:25.362  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 14:23:25.367  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:23:25.369   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5bd13a9:true
08-16 14:23:25.380   872  2116 I ActivityManager: Start proc 3876:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 14:23:25.399   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-16 14:23:25.400   872  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 14:23:25.400   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 14:23:25.403  3855  3855 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 14:23:25.407  3855  3855 D BluetoothMap: Create BluetoothMap proxy object
,08-16 14:23:25.416  3876  3876 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 14:23:25.418  3855  3855 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 14:23:25.434  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:25.436   872  2116 I ActivityManager: Killing 3408:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 14:23:25.503  2669  2691 I bt_hci  : shut_down
,08-16 14:23:25.503  2669  2696 D bt_hwcfg: hw_epilog_process
,08-16 14:23:25.505  2669  2696 I bt_vendor: low_power_mode_cb
,08-16 14:23:25.525  2669  2696 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 14:23:25.526  2669  2696 I bt_vendor: epilog_cb
08-16 14:23:25.526  2669  2696 I bt_hci  : epilog_finished_callback
,08-16 14:23:25.563  2669  2691 I bt_hci_h4: hal_close
,08-16 14:23:25.564  2669  2691 I bt_userial_vendor: device fd = 51 close
,08-16 14:23:25.674  3876  3876 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.674  3876  3876 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.674  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.675  3876  3876 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.675  3876  3876 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
,08-16 14:23:25.675  3876  3876 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.675  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.678  3876  3876 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.678  3876  3876 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.678  3876  3876 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.678  3876  3876 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:25.678  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:25.691  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:23:25.724   872  1976 I ActivityManager: Start proc 3907:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-16 14:23:25.725   872  1976 I ActivityManager: Killing 3567:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 14:23:25.748  3876  3895 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 14:23:25.755   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d139ea:true
,08-16 14:23:25.789  2669  2687 D bt_stack_manager: event_shut_down_stack finished.
,08-16 14:23:25.789  2669  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 14:23:25.806  2669  2686 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 14:23:25.807  2669  2669 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:23:25.807  2669  2669 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 14:23:25.807  2669  2669 D BtGatt.GattService: stop()
,08-16 14:23:25.807  2669  2669 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:23:25.809  2669  2669 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:25.809  2669  2669 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:25.809  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:25.809  2669  2669 V BluetoothAdapterState: isBleTurningOff()=true
08-16 14:23:25.810  2669  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 14:23:25.810  2669  2686 D BluetoothAdapterProperties: Setting state to 10
08-16 14:23:25.810  2669  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 14:23:25.810  2669  2686 I BluetoothAdapterState: Entering OffState
08-16 14:23:25.811   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 14:23:25.826  2669  2669 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 14:23:25.826  2669  2669 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 14:23:25.826  2669  2669 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 14:23:25.827  2669  2687 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 14:23:25.830  2669  2687 D bt_stack_manager: event_clean_up_stack finished.
,08-16 14:23:25.834  3907  3907 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 14:23:25.835  2669  2669 I art     : System.exit called, status: 0
08-16 14:23:25.835  2669  2669 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 14:23:25.915   872  2115 I ActivityManager: Process com.android.bluetooth (pid 2669) has died
,08-16 14:23:25.924  3907  3907 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 14:23:25.952  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:25.995   872  1989 I ActivityManager: Start proc 3935:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 14:23:25.997  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:26.058  3935  3935 D AdapterServiceConfig: Adding HeadsetService
08-16 14:23:26.058  3935  3935 D AdapterServiceConfig: Adding A2dpService
08-16 14:23:26.058  3935  3935 D AdapterServiceConfig: Adding HidService
08-16 14:23:26.058  3935  3935 D AdapterServiceConfig: Adding HealthService
,08-16 14:23:26.058  3935  3935 D AdapterServiceConfig: Adding PanService
,08-16 14:23:26.059  3935  3935 D AdapterServiceConfig: Adding GattService
08-16 14:23:26.059  3935  3935 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 14:23:26.062   872   883 I ActivityManager: Killing 3464:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 14:23:26.207  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:26.243  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:23:26.249  1691  1691 D SystemUpdateService: onCreate
,08-16 14:23:26.254  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:23:26.263  1691  3947 I SystemUpdateService: active receiver: enabled
,08-16 14:23:26.272  1691  3947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:23:26.277  1691  3947 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 14:23:26.277  1691  3947 I SystemUpdateService: now status is 0 (complete)
,08-16 14:23:26.278  1691  3947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 14:23:26.278  1691  3947 I SystemUpdateService: file has been verified
08-16 14:23:26.279  1691  3947 I SystemUpdateService: OTA package size = 12249756
,08-16 14:23:26.283  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 14:23:26.291  1691  3947 I SystemUpdateService: showing system update notification
,08-16 14:23:26.291  1691  2462 I iu.UploadsManager: num queued entries: 0
,08-16 14:23:26.293  1691  2462 I iu.UploadsManager: num updated entries: 0
,08-16 14:23:26.302  1691  2462 I iu.SyncManager: NEXT; no task
,08-16 14:23:26.324  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:23:26.326  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 14:23:26.328  1691  1691 D SystemUpdateService: onDestroy
,08-16 14:23:26.360   872  1986 I ActivityManager: Start proc 3949:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 14:23:26.419  3949  3949 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 14:23:26.423  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:26.435  3949  3949 D SprintDMHelper: simOperator: 
08-16 14:23:26.435  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:23:26.458   872  1975 I ActivityManager: Start proc 3961:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 14:23:26.459   872  1975 I ActivityManager: Killing 3507:android.process.acore/u0a5 (adj 15): empty #17
,08-16 14:23:26.628  2278  3975 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 14:23:26.642   872  1611 I ActivityManager: Start proc 3976:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 14:23:26.646   872  1611 I ActivityManager: Killing 3671:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 14:23:26.721  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 14:23:26.774  3976  3976 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 14:23:26.774  3976  3976 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 14:23:26.774  3976  3976 I GAv4    :   adb logcat -s GAv4
,08-16 14:23:26.790  3976  3976 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 14:23:26.796  3976  3976 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 14:23:26.823  3976  3994 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 14:23:26.931  3976  3976 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 14:23:26.982  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 14:23:26.991  3976  3976 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3922-3926)
08-16 14:23:26.991  3976  3976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:23:27.004  3976  3976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f3c8bfd}
,08-16 14:23:27.005  3976  3976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:23:27.006  3976  3976 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 14:23:27.015  3976  3976 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 14:23:27.017  3976  3976 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 14:23:27.036  3976  3976 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 14:23:27.049  3976  3976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:23:27.049  3976  3976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:23:27.049  3976  3976 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 14:23:27.049  3976  3976 I Adreno  : Build Date                       : 10/20/15
08-16 14:23:27.049  3976  3976 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 14:23:27.049  3976  3976 I Adreno  : Local Branch                     : M14
08-16 14:23:27.049  3976  3976 I Adreno  : Remote Branch                    : 
08-16 14:23:27.049  3976  3976 I Adreno  : Remote Branch                    : 
08-16 14:23:27.049  3976  3976 I Adreno  : Reconstruct Branch               : 
,08-16 14:23:27.102  3976  3976 I NSApplication: Starting up...
,08-16 14:23:27.112  3976  4023 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 14:23:27.130   872   882 I ActivityManager: Start proc 4028:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 14:23:27.136   872   882 I ActivityManager: Killing 3686:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 14:23:27.231  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 14:23:27.417   872  1396 I ActivityManager: Killing 2053:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 14:23:28.239   872  2115 D WifiService: setWifiEnabled: true pid=3788, uid=10000
08-16 14:23:28.239   872  2115 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:23:28.255   872  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-16 14:23:28.264  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:28.264  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:28.265  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:28.265  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:28.268  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:28.269  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:28.269  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:28.269  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:28.297   872  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-16 14:23:28.298   872  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 14:23:28.299   872  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 14:23:28.300   872  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:23:28.300   872  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 14:23:28.300   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 14:23:28.300   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 14:23:28.314   872  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.38 rxSuccessRate=14.25 delta 1000 -> 994
,08-16 14:23:28.314   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 14:23:28.317   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:28.320   872  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 14:23:28.320   872  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 14:23:28.323   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 14:23:28.323   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:28.334   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 14:23:28.335   872  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 14:23:28.364   872  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 14:23:28.403   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 14:23:28.408  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 14:23:28.823  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 14:23:28.862  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 14:23:28.863  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 14:23:28.872   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:23:28.883   872  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 14:23:28.884   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:23:28.884   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 14:23:28.906   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:28.923   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:28.924   872  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 14:23:28.944   872  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 14:23:28.949   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 14:23:29.014   872  4051 D DhcpClient: Receive thread started
,08-16 14:23:29.102   872  1313 E native  : do suspend false
,08-16 14:23:29.124   872  1870 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 14:23:29.138   872  4051 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-16 14:23:29.140   872  1870 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-16 14:23:29.143   872  1870 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 14:23:29.156   872  4051 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 14:23:29.157   872  1870 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 14:23:29.162   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:29.173   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 14:23:29.174   872  1870 D DhcpClient: Scheduling renewal in 86399s
,08-16 14:23:29.191   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 14:23:29.195   872  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 14:23:29.195   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 14:23:29.197   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 14:23:29.200   872  1315 D ConnectivityService: Adding iface wlan0 to network 101
08-16 14:23:29.222   872  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 14:23:29.268   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 14:23:29.268   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 14:23:29.269   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 14:23:29.270   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 14:23:29.272   872  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 14:23:29.286   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 14:23:29.292   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 14:23:29.293   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-16 14:23:29.293   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 14:23:29.293   872  1315 D ConnectivityService:    accepting network in place of null
08-16 14:23:29.293   872  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 14:23:29.294   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 14:23:29.294   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 14:23:29.302   872  4050 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 14:23:29.350   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:23:29.395   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:813::200e
,08-16 14:23:29.406   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:23:29.417   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 14:23:29.418   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:29.425   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:23:29.432  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:29.432  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:29.432  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:29.432  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:29.432   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 14:23:29.437  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:29.437  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:29.437  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:29.437  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:29.449  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:23:29.454  1691  1691 D SystemUpdateService: onCreate
,08-16 14:23:29.458  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:23:29.463  1691  4063 I SystemUpdateService: active receiver: enabled
,08-16 14:23:29.466  1691  4063 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:23:29.468  1691  4063 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 14:23:29.468  1691  4063 I SystemUpdateService: now status is 0 (complete)
08-16 14:23:29.469  1691  4063 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 14:23:29.469  1691  4063 I SystemUpdateService: file has been verified
,08-16 14:23:29.469  1691  4063 I SystemUpdateService: OTA package size = 12249756
,08-16 14:23:29.472  1691  4063 I SystemUpdateService: showing system update notification
,08-16 14:23:29.477   872  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:23:29 GMT], X-Android-Received-Millis=[1471350209476], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471350209448]}
,08-16 14:23:29.478   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 14:23:29.478   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 14:23:29.478   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 14:23:29.479   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 14:23:29.478  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 14:23:29.486  1691  2462 I iu.UploadsManager: num queued entries: 0
,08-16 14:23:29.487  1691  2462 I iu.UploadsManager: num updated entries: 0
,08-16 14:23:29.487  1691  2462 I iu.SyncManager: NEXT; no task
,08-16 14:23:29.489  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:23:29.490  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 14:23:29.492  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:29.496  3949  3949 D SprintDMHelper: simOperator: 
08-16 14:23:29.496  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:23:29.501  1691  1691 D SystemUpdateService: onDestroy
08-16 14:23:29.505  1691  4067 I MDM     : [171] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 14:23:29.506  1691  4067 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 14:23:29.507  1691  4067 V GoogleAuthProtoRequest: [171] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 14:23:29.521  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:29.522  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:29.554  1512  2146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 14:23:29.554  1512  2146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 14:23:29.555  1512  2146 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:29.555  1512  2146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:29.574  1691  4067 E MDM     : [171] SitrepService.a: Error sending sitrep.
,08-16 14:23:29.576  3133  4072 V KeepSync: Connecting to GoogleApiClient
,08-16 14:23:29.577   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 14:23:29.636  2278  4070 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 14:23:29.637  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 14:23:29.637  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 14:23:29.637  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:29.637  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:29.653  1691  4079 V BaseAuthAsyncOperation: access token request failed
08-16 14:23:29.653  3133  4072 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 14:23:29.668  1512  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 14:23:29.668  1512  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 14:23:29.668  1512  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:29.668  1512  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:29.685  3001  4073 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 14:23:29.685  3001  4073 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jdm.a(PG:82)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jcs.o(PG:406)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jcn.a(PG:1379)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jcs.i(PG:143)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at blb.a(PG:3937)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at czp.a(PG:18188)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at czp.a(PG:9081)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at czq.run(PG:1686)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:29.685  3001  4073 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jdj.a(PG:4091)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jdj.a(PG:1125)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jdm.a(PG:77)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	... 12 more
08-16 14:23:29.685  3001  4073 E HttpOperation: Caused by: faj: BadAuthentication
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at fal.a(PG:38)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	at jdj.a(PG:4089)
08-16 14:23:29.685  3001  4073 E HttpOperation: 	... 14 more
,08-16 14:23:29.707  1512  2146 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 14:23:29.707  1512  2146 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 14:23:29.708  1512  2146 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:29.708  1512  2146 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:29.723  1512  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 14:23:29.723  1512  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 14:23:29.723  1512  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:29.723  1512  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:29.729  3133  4072 E KeepSync: IOException
08-16 14:23:29.729  3133  4072 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 14:23:29.729  3133  4072 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 14:23:29.729  3133  4072 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 14:23:29.729  3133  4072 E KeepSync: 	... 10 more
,08-16 14:23:29.729  3133  4072 W KeepSync: Sync result 2
,08-16 14:23:29.738   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128675, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 14:23:29.745  3001  4073 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 14:23:29.745  3001  4073 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jdm.a(PG:82)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jcs.o(PG:406)
,08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jcn.a(PG:1379)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jcs.i(PG:143)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at hec.a(PG:42)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at hee.a(PG:102)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at czr.a(PG:65)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at kka.a(PG:108)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at czp.a(PG:19176)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at czp.a(PG:9081)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at czq.run(PG:1686)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:29.745  3001  4073 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jdj.a(PG:4091)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jdj.a(PG:1125)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jdm.a(PG:77)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	... 15 more
08-16 14:23:29.745  3001  4073 E HttpOperation: Caused by: faj: BadAuthentication
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at fal.a(PG:38)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	at jdj.a(PG:4089)
08-16 14:23:29.745  3001  4073 E HttpOperation: 	... 17 more
,08-16 14:23:29.746  3001  4073 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 14:23:29.746  3001  4073 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at hec.a(PG:42)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at hee.a(PG:102)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at czr.a(PG:65)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at kka.a(PG:108)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	,... 15 more
08-16 14:23:29.746  3001  4073 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at fal.a(PG:38)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 14:23:29.746  3001  4073 E ExperimentLoader: 	... 17 more
,08-16 14:23:29.853   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128053, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 14:23:30.416   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 14:23:30.972   872  2115 I ActivityManager: Killing 3710:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 14:23:31.249   872   882 D WifiService: setWifiEnabled: false pid=3788, uid=10000
,08-16 14:23:31.250   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:23:31.280  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 14:23:31.283   872  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 14:23:31.283   872  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 14:23:31.283   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 14:23:31.284   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:31.302   872  1870 D DhcpClient: Clearing IP address
,08-16 14:23:31.303   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-16 14:23:31.311  1512  4078 V NativeCrypto: Read error: ssl=0x9ae3e000: I/O error during system call, Connection timed out
,08-16 14:23:31.317   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:31.333   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 14:23:31.333   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 14:23:31.335   872  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 14:23:31.336   400   400 E Parcel  : Reading a NULL string not supported here.
08-16 14:23:31.339  1512  4078 V NativeCrypto: SSL shutdown failed: ssl=0x9ae3e000: I/O error during system call, Broken pipe
08-16 14:23:31.341   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:23:31.345   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-16 14:23:31.349   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 14:23:31.350   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 14:23:31.352  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:31.352  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:31.352  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:31.352  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:31.353   872  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:23:31.353  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:31.353  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:31.353  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:31.353  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:31.354  1853  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:23:31.362   872  4051 D DhcpClient: Receive thread stopped
,08-16 14:23:31.386   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:23:31.407   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:23:31.407   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 14:23:31.407   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:31.411  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:31.411   872   889 D Tethering: MasterInitialState.processMessage what=3
08-16 14:23:31.411  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:31.411  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:31.416  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:23:31.420  1691  1691 D SystemUpdateService: onCreate
,08-16 14:23:31.422  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:23:31.434  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 14:23:31.438  1691  4090 I SystemUpdateService: active receiver: enabled
,08-16 14:23:31.441  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:23:31.449  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 14:23:31.437  1691  2462 I iu.UploadsManager: num queued entries: 0
,08-16 14:23:31.462   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-16 14:23:31.465  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:31.467  1691  2462 I iu.UploadsManager: num updated entries: 0
,08-16 14:23:31.468  3949  3949 I art     : Waiting for a blocking GC DisableMovingGc
,08-16 14:23:31.470  1691  4090 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:23:31.472  1691  2462 I iu.SyncManager: NEXT; no task
,08-16 14:23:31.472  1691  4090 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 14:23:31.472  1691  4090 I SystemUpdateService: now status is 0 (complete)
08-16 14:23:31.473  1691  4090 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 14:23:31.474  3949  3949 I art     : WaitForGcToComplete blocked for 6.143ms for cause DisableMovingGc
,08-16 14:23:31.474  3949  3949 I art     : Starting a blocking GC DisableMovingGc
08-16 14:23:31.473  1691  4090 I SystemUpdateService: file has been verified
08-16 14:23:31.475  3949  3949 D SprintDMHelper: simOperator: 
08-16 14:23:31.475  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:23:31.478  1691  4090 I SystemUpdateService: OTA package size = 12249756
,08-16 14:23:31.498  2278  4095 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 14:23:31.513  1691  4090 I SystemUpdateService: showing system update notification,
,08-16 14:23:31.521  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:31.528  1691  1691 D SystemUpdateService: onDestroy
,08-16 14:23:31.547  1512  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 14:23:31.547  1512  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 14:23:31.547  1512  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:31.547  1512  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:31.566  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 14:23:31.567  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 14:23:31.567  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 14:23:34.305  3935  3935 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 14:23:34.305   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@284aeed:true
,08-16 14:23:34.310  3935  3935 I bt_bluedroid: init
,08-16 14:23:34.311  3935  4100 I BluetoothAdapterState: Entering OffState
,08-16 14:23:34.313  3935  4101 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 14:23:34.313  3935  4101 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:23:34.313  3935  4101 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 14:23:34.313  3935  4101 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 14:23:34.314  3935  3935 I bt_bluedroid: get_profile_interface socket
,08-16 14:23:34.316  3935  3935 I bt_bluedroid: get_profile_interface sdp
08-16 14:23:34.320  3935  4104 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 14:23:34.322  3935  3945 I bt_bluedroid: config_hci_snoop_log
,08-16 14:23:34.323  3935  4104 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:23:34.324   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 14:23:34.332  3935  4100 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 14:23:34.332  3935  4100 D BluetoothAdapterProperties: Setting state to 14
,08-16 14:23:34.332  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 14:23:34.334  3935  4100 D BluetoothBondStateMachine: make
,08-16 14:23:34.338  3935  4105 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 14:23:34.343  3935  3935 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 14:23:34.345  3935  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:34.347  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:34.348  3935  3935 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:23:34.349  3935  3935 D BtGatt.GattService: Received start request. Starting profile...
,08-16 14:23:34.349  3935  3935 D BtGatt.GattService: start()
,08-16 14:23:34.349  3935  3935 I bt_bluedroid: get_profile_interface gatt
,08-16 14:23:34.350  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:34.350  3935  3935 D BtGatt.AdvertiseManager: advertise manager created
,08-16 14:23:34.360  3935  3935 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:34.360  3935  3935 V BluetoothAdapterState: isTurningOn()=false
,08-16 14:23:34.360  3935  3935 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 14:23:34.360  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:34.361  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4,
08-16 14:23:34.361  3935  4100 I bt_bluedroid: enable
,08-16 14:23:34.362  3935  4101 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 14:23:34.362  3935  4101 I bt_hci  : start_up
,08-16 14:23:34.371  3935  4101 I bt_vendor: alloc value 0xb3969189
,08-16 14:23:34.372  3935  4101 I bt_vendor: init
,08-16 14:23:34.372  3935  4101 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 14:23:34.372  3935  4101 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 14:23:34.481  3935  4101 D bt_hci  : start_up starting async portion
,08-16 14:23:34.481  3935  4108 I bt_hci  : event_finish_startup
,08-16 14:23:34.482  3935  4108 I bt_hci_h4: hal_open
,08-16 14:23:34.482  3935  4108 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 14:23:34.490  3935  4108 I bt_userial_vendor: device fd = 51 open
,08-16 14:23:34.522  3935  4108 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:23:34.554  3935  4108 D bt_hwcfg: Chipset BCM4354A2
,08-16 14:23:34.554  3935  4108 D bt_hwcfg: Target name = [BCM4354A2]
08-16 14:23:34.555  3935  4108 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 14:23:35.208  3935  4108 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 14:23:35.210  3935  4108 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 14:23:35.210  3935  4108 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 14:23:35.327  3935  4108 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:23:35.329  3935  4108 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 14:23:35.357  3935  4108 I bt_hwcfg: vendor lib fwcfg completed
,08-16 14:23:35.357  3935  4108 I bt_vendor: firmware callback
08-16 14:23:35.357  3935  4108 I bt_hci  : firmware_config_callback
,08-16 14:23:35.370  3935  4110 I bt_btu  : btu_task pending for preload complete event
,08-16 14:23:35.370  3935  4110 I bt_btu_task: Bluetooth chip preload is complete
08-16 14:23:35.371  3935  4110 I bt_btu  : btu_task received preload complete event
,08-16 14:23:35.380  3935  4110 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 14:23:35.381  3935  4110 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:23:35.381  3935  4110 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:23:35.381  3935  4110 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:23:35.382  3935  4110 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 14:23:35.382  3935  4110 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:23:35.382  3935  4110 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:23:35.382  3935  4110 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:23:35.383  3935  4110 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 14:23:35.383  3935  4110 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:23:35.383  3935  4110 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:23:35.383  3935  4110 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 14:23:35.384  3935  4110 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:23:35.384  3935  4110 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:23:35.384  3935  4110 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 14:23:35.522  3935  4110 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-16 14:23:35.523  3935  4110 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-16 14:23:35.534  3935  4104 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 14:23:35.536  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 14:23:35.537  3935  4104 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 14:23:35.541  3935  4104 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:23:35.546  3935  4104 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:23:35.547  3935  4104 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:23:35.547  3935  4104 D bt_hci  : do_postload posting postload work item
08-16 14:23:35.547  3935  4108 I bt_hci  : event_postload
08-16 14:23:35.547  3935  4108 I bt_vendor: sco_config_cb
08-16 14:23:35.547  3935  4108 I bt_hci  : sco_config_callback postload finished.
08-16 14:23:35.548  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:35.552  3935  4104 D bt_bte_conf: Device ID record 1 : primary
,08-16 14:23:35.552  3935  4104 D bt_bte_conf:   vendorId            = 000f
08-16 14:23:35.552  3935  4104 D bt_bte_conf:   vendorIdSource      = 0001
08-16 14:23:35.552  3935  4104 D bt_bte_conf:   product             = 1200
08-16 14:23:35.553  3935  4108 I bt_vendor: low_power_mode_cb
08-16 14:23:35.553  3935  4104 D bt_bte_conf:   version             = 1436
,08-16 14:23:35.553  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:35.553  3935  4104 D bt_bte_conf:   clientExecutableURL = 
08-16 14:23:35.554  3935  4104 D bt_bte_conf:   serviceDescription  = 
08-16 14:23:35.554  3935  4104 D bt_bte_conf:   documentationURL    = 
08-16 14:23:35.554  3935  4104 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 14:23:35.554  3935  4101 D bt_stack_manager: event_start_up_stack finished
08-16 14:23:35.555  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 14:23:35.555  3935  4100 D BluetoothAdapterProperties: Setting state to 15
,08-16 14:23:35.556  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 14:23:35.557  3935  4100 I BluetoothAdapterState: Entering BleOnState
,08-16 14:23:35.561  3935  4100 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 14:23:35.561  3935  4100 D BluetoothAdapterProperties: Setting state to 11
,08-16 14:23:35.561  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 14:23:35.566  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:35.567  3935  3935 D HeadsetService: Received start request. Starting profile...
08-16 14:23:35.571  3935  3935 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:23:35.571  3935  3935 D HeadsetStateMachine: make
08-16 14:23:35.572  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:35.575  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:35.587  3935  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:35.589  3935  3935 D HeadsetStateMachine: max_hf_connections = 1
,08-16 14:23:35.589  3935  3935 I bt_bluedroid: get_profile_interface handsfree
,08-16 14:23:35.589  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 14:23:35.590  3935  4104 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 14:23:35.597  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:35.598  3935  3935 D A2dpService: Received start request. Starting profile...
08-16 14:23:35.599  3935  3935 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 14:23:35.599  3935  3935 I bt_bluedroid: get_profile_interface avrcp
,08-16 14:23:35.607  3935  3935 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:23:35.607  3935  3935 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:23:35.607  3935  3935 D A2dpStateMachine: make
,08-16 14:23:35.609  3935  3935 I bt_bluedroid: get_profile_interface a2dp
,08-16 14:23:35.610  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-16 14:23:35.611  3935  4120 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:23:35.612  3935  3935 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:23:35.613  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:35.615  3855  3855 D BluetoothInputDevice: Proxy object connected
08-16 14:23:35.615  3935  3935 D HidService: Received start request. Starting profile...
,08-16 14:23:35.615  3935  3935 I bt_bluedroid: get_profile_interface hidhost
08-16 14:23:35.615  3935  3935 D HidService: setHidService(): set to: null
08-16 14:23:35.615  3935  4104 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
,08-16 14:23:35.616  3855  3855 D HidProfile: Bluetooth service connected
08-16 14:23:35.616  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 14:23:35.616  3935  3935 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:23:35.617  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:35.619  3935  3935 D HealthService: Received start request. Starting profile...
,08-16 14:23:35.621  3935  3935 I bt_bluedroid: get_profile_interface health
,08-16 14:23:35.622  3935  3935 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 14:23:35.623  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:23:35.624  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:35.626  3935  3935 D PanService: Received start request. Starting profile...
08-16 14:23:35.626  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 14:23:35.626  3935  3935 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:23:35.627  3935  3935 I bt_bluedroid: get_profile_interface pan
08-16 14:23:35.627  3935  4104 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 14:23:35.629  3935  3935 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:35.631  3935  3935 D BluetoothMapService: Received start request. Starting profile...
08-16 14:23:35.631  3935  3935 D BluetoothMapService: start()
,08-16 14:23:35.633  3935  3935 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 14:23:35.634  3935  3935 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 14:23:35.634  3935  3935 D BluetoothMapAppObserver: createReceiver()
,08-16 14:23:35.637  3935  3935 D BluetoothMapAppObserver: initObservers()
08-16 14:23:35.637  3935  3935 D BluetoothMapAppObserver: getEnabledAccountItems()
08-16 14:23:35.638  3855  3855 D PanProfile: Bluetooth service connected
08-16 14:23:35.639  3855  3855 D BluetoothMap: Proxy object connected
08-16 14:23:35.639  3855  3855 D MapProfile: Bluetooth service connected
08-16 14:23:35.639  3855  3855 D BluetoothMap: getConnectedDevices()
08-16 14:23:35.640  3855  3855 D BluetoothMap: Bluetooth is Not enabled
,08-16 14:23:35.646  3935  3935 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:35.646  3935  3935 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:35.646  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:35.646  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:35.649  3935  3935 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:35.649  3935  3935 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:35.649  3935  4117 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:23:35.649  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:35.649  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:35.650  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isTurningOn()=true
,08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:23:35.651  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:35.651  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 14:23:35.651  3935  4100 D BluetoothAdapterProperties: ScanMode =  20
,08-16 14:23:35.651  3935  4100 D BluetoothAdapterProperties: State =  11
08-16 14:23:35.652  3935  4100 D BluetoothAdapterProperties: Setting state to 12
08-16 14:23:35.652  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 14:23:35.652  3935  4100 I BluetoothAdapterState: Entering OnState
08-16 14:23:35.652  1372  2076 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 14:23:35.654  1372  1372 D BluetoothInputDevice: Proxy object connected
08-16 14:23:35.654  1372  1372 D HidProfile: Bluetooth service connected
08-16 14:23:35.654  3935  4104 D BluetoothAdapterProperties: Scan Mode:21
,08-16 14:23:35.655  3935  4104 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:23:35.655  1372  1384 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:23:35.656  1372  1372 D BluetoothMap: Proxy object connected
,08-16 14:23:35.656  1372  1372 D MapProfile: Bluetooth service connected
08-16 14:23:35.656  1372  1372 D BluetoothMap: getConnectedDevices()
08-16 14:23:35.656  1969  1981 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:35.658   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:35.658  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:35.658  1372  2076 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:23:35.660  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:23:35.660  1372  1372 D PanProfile: Bluetooth service connected
08-16 14:23:35.660   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:35.661  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:35.661   872   872 D BluetoothA2dp: Proxy object connected
08-16 14:23:35.664  3855  3865 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:23:35.664  1372  1384 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:35.664  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:35.666  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:35.666  3935  3935 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 14:23:35.666  3935  3935 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 14:23:35.667  1372  1372 D BluetoothA2dp: Proxy object connected
08-16 14:23:35.667  3935  3935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:23:35.667  1372  2076 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:23:35.669  3935  3935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:35.669  1372  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:35.670  3855  3868 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:23:35.670  3935  3935 D ObexServerSockets: Succeed to create listening sockets 
08-16 14:23:35.670  3935  3935 D ObexServerSockets0: startAccept()
08-16 14:23:35.670  3935  3935 D ObexServerSockets0: prepareForNewConnect()
08-16 14:23:35.671   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:35.671  3855  3865 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:23:35.671  3855  3868 D BluetoothPan: onBluetoothStateChange on: true
,08-16 14:23:35.671  3935  3935 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 14:23:35.671  3935  3935 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 14:23:35.671   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:35.672   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 14:23:35.673  3935  3935 D BluetoothMapService: onReceive
,08-16 14:23:35.673  3935  3935 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:35.673  3935  3935 D BluetoothMapService: STATE_ON
08-16 14:23:35.674  3935  4126 D ObexServerSockets0: Accepting socket connection...
08-16 14:23:35.675  3935  4125 D ObexServerSockets0: Accepting socket connection...
08-16 14:23:35.675  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:35.675  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:35.677  3855  3855 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 14:23:35.680  3855  3855 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 14:23:35.685  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:35.688  3855  3855 D BluetoothA2dp: Proxy object connected
,08-16 14:23:35.691  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:35.697  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:35.700  1372  1372 D BluetoothPbap: Proxy object connected
,08-16 14:23:35.700  3855  3855 D BluetoothPbap: Proxy object connected
08-16 14:23:35.700  3935  3935 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 14:23:35.700  1372  1372 D PbapServerProfile: Bluetooth service connected
08-16 14:23:35.700  3855  3855 D PbapServerProfile: Bluetooth service connected
08-16 14:23:35.700  3935  3935 D ObexServerSockets0: prepareForNewConnect()
,08-16 14:23:35.710  3935  4131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:35.722  3935  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:35.723  3935  4135 I BtOppRfcommListener: Accept thread started.
,08-16 14:23:35.760   872   872 D BluetoothHeadset: Proxy object connected
08-16 14:23:35.760   872   872 D BluetoothHeadset: Proxy object connected
,08-16 14:23:35.761  1969  2134 D BluetoothHeadset: Proxy object connected
08-16 14:23:35.762   872   872 D BluetoothHeadset: Proxy object connected
,08-16 14:23:35.762  1372  2076 D BluetoothHeadset: Proxy object connected
,08-16 14:23:35.763  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:35.770  1372  1383 D BluetoothHeadset: Proxy object connected
08-16 14:23:35.770  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:35.771   872   889 D BluetoothHeadset: Proxy object connected
08-16 14:23:35.771   872   889 D BluetoothHeadset: Proxy object connected
,08-16 14:23:35.783  3855  3868 D BluetoothHeadset: Proxy object connected
,08-16 14:23:35.785  3855  3855 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:37.270  3935  4100 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 14:23:37.270  3935  4100 D BluetoothAdapterProperties: Setting state to 13
,08-16 14:23:37.271  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:23:37.273  3935  4100 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 14:23:37.275  3935  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:37.281  3935  3935 D BluetoothMapService: onReceive
08-16 14:23:37.281  3935  3935 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:37.282  3935  3935 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:23:37.282  3935  3935 D BluetoothMapService: MAP Service closeService in
08-16 14:23:37.283  3935  3935 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 14:23:37.283  3935  3935 D ObexServerSockets0: shutdown(block = true)
08-16 14:23:37.284  3935  4125 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 14:23:37.290  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:37.290  3935  3935 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:37.291  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:37.291  3935  4126 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 14:23:37.291  3935  4104 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:23:37.292  3935  4112 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 14:23:37.292  3935  3935 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 14:23:37.292  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 14:23:37.293  3935  3935 I BtOppRfcommListener: stopping Accept Thread
08-16 14:23:37.293  3935  4135 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:23:37.294  3935  4135 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:23:37.294  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:37.295  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:37.296  3935  3935 D HeadsetService: Received stop request...Stopping profile...
08-16 14:23:37.298   872  1315 D ConnectivityService: handlePromptUnvalidated 101
08-16 14:23:37.301   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:37.302  3855  3865 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:37.302  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:37.303  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:37.304  3935  3935 D A2dpService: Received stop request...Stopping profile...
,08-16 14:23:37.305  3935  4120 D A2dpStateMachine: Exit Disconnected: -1
,08-16 14:23:37.305  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:37.306   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:37.306  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:37.308  1969  3492 D BluetoothHeadset: Proxy object disconnected
,08-16 14:23:37.311  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:37.312  1372  1372 D BluetoothA2dp: Proxy object disconnected
,08-16 14:23:37.313  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:37.314   872   872 D BluetoothHeadset: Proxy object disconnected
,08-16 14:23:37.314  3935  3935 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:37.314  3935  3935 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:37.314  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:37.315  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:37.315  1372  1384 D BluetoothHeadset: Proxy object disconnected
08-16 14:23:37.316  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-16 14:23:37.317   872   872 D BluetoothA2dp: Proxy object disconnected
,08-16 14:23:37.318  3935  3935 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 14:23:37.318  3935  3935 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:23:37.318  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 14:23:37.319  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:37.319  3935  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:37.319  3935  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:37.319  3935  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:37.319  3935  3935 D HidService: Received stop request...Stopping profile...
08-16 14:23:37.319  3935  3935 D HidService: Stopping Bluetooth HidService
08-16 14:23:37.321  3935  4104 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-16 14:23:37.322  3935  3935 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:37.322  3935  3935 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:37.322  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:37.322  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:37.323  3935  3935 D HealthService: Received stop request...Stopping profile...
,08-16 14:23:37.324  3855  3855 D HeadsetProfile: Bluetooth service disconnected
,08-16 14:23:37.325  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 14:23:37.325  3935  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:37.325  3855  3855 D BluetoothA2dp: Proxy object disconnected
,08-16 14:23:37.326  3935  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:37.326  3935  4110 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:37.326  3935  4110 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:37.326  3935  4110 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:37.326  3935  4110 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:37.327  3935  3935 D PanService: Received stop request...Stopping profile...
08-16 14:23:37.329  3935  3935 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:23:37.329  3935  3935 D BluetoothMapService: stop()
08-16 14:23:37.330  3935  3935 D BluetoothMapAppObserver: deinitObservers()
,08-16 14:23:37.330  3935  3935 D BluetoothMapAppObserver: removeReceiver()
08-16 14:23:37.330  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-16 14:23:37.330  1372  1372 D HidProfile: Bluetooth service disconnected
08-16 14:23:37.330  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:23:37.330  1372  1372 D PanProfile: Bluetooth service disconnected
,08-16 14:23:37.332  3935  3935 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:37.332  3935  3935 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:37.332  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:37.332  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:37.333  3935  3935 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:23:37.333  3935  3935 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:23:37.333  3935  4104 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 14:23:37.334  3935  3935 V BluetoothAdapterState: isTurningOff()=true
08-16 14:23:37.334  3935  3935 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:37.334  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:37.334  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:37.335  3935  3935 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 14:23:37.335  3935  4104 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 14:23:37.336  3935  3935 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:23:37.336  3935  3935 V BluetoothAdapterState: isTurningOff()=true
,08-16 14:23:37.337  3935  3935 V BluetoothAdapterState: isTurningOn()=false
,08-16 14:23:37.337  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:37.337  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:37.337  3935  3935 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:23:37.337  3935  3935 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:23:37.339  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:23:37.339  3935  3935 D BluetoothMapService: MAP Service closeService in
08-16 14:23:37.339  3935  3935 V BluetoothAdapterState: isTurningOff()=true
,08-16 14:23:37.339  3935  3935 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:37.339  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:37.339  3935  3935 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:37.339  3935  3935 D BluetoothMapService: cleanup()
,08-16 14:23:37.339  3935  3935 D BluetoothMapService: MAP Service closeService in
,08-16 14:23:37.340  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 14:23:37.340  3935  4100 D BluetoothAdapterProperties: Setting state to 15
08-16 14:23:37.340  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 14:23:37.340  1372  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 14:23:37.342  1372  2076 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:23:37.342  3855  3865 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:37.343  1969  1982 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:37.342  3935  4100 I BluetoothAdapterState: Entering BleOnState
08-16 14:23:37.343   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:37.344  1372  1384 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:23:37.344   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 14:23:37.344  3855  3868 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:23:37.345  1372  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:37.345  1372  2076 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:23:37.346  1372  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:37.348  3855  3868 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:23:37.352   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:37.352  3855  3865 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:23:37.353  3855  3868 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:23:37.353   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:23:37.353  3855  3865 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 14:23:37.353  3935  4100 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 14:23:37.353  3935  4100 D BluetoothAdapterProperties: Setting state to 16
08-16 14:23:37.354  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 14:23:37.354  3935  4100 D BluetoothAdapterProperties: onBleDisable
08-16 14:23:37.354  3935  4100 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:37.355  3935  4101 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 14:23:37.355  3935  4104 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:23:37.356  3935  4110 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 14:23:37.356  3935  4110 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:23:37.358  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:37.360  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:37.361  3855  3855 D DockEventReceiver: finishStartingService: stopping service
08-16 14:23:37.362  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:37.364  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:37.364  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:37.368  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:37.369  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:37.557  3935  4104 I bt_hci  : shut_down
,08-16 14:23:37.557  3935  4108 D bt_hwcfg: hw_epilog_process
,08-16 14:23:37.559  3935  4108 I bt_vendor: low_power_mode_cb
,08-16 14:23:37.588  3935  4108 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 14:23:37.588  3935  4108 I bt_vendor: epilog_cb
,08-16 14:23:37.588  3935  4108 I bt_hci  : epilog_finished_callback
,08-16 14:23:37.601  3935  4104 I bt_hci_h4: hal_close
,08-16 14:23:37.602  3935  4104 I bt_userial_vendor: device fd = 51 close
,08-16 14:23:37.724  3935  4101 D bt_stack_manager: event_shut_down_stack finished.
,08-16 14:23:37.726  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 14:23:37.732  3935  3935 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:23:37.733  3935  3935 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:23:37.734  3935  3935 D BtGatt.GattService: stop()
,08-16 14:23:37.734  3935  3935 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:23:37.736  3935  4100 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 14:23:37.740  3935  3935 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:37.740  3935  3935 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:37.740  3935  3935 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:23:37.741  3935  3935 V BluetoothAdapterState: isBleTurningOff()=true
08-16 14:23:37.742  3935  4100 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 14:23:37.743  3935  4100 D BluetoothAdapterProperties: Setting state to 10
08-16 14:23:37.743  3935  4100 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 14:23:37.747  3935  4100 I BluetoothAdapterState: Entering OffState
08-16 14:23:37.747   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 14:23:37.771  3935  3935 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 14:23:37.772  3935  3935 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 14:23:37.772  3935  4101 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 14:23:37.781  3935  4101 D bt_stack_manager: event_clean_up_stack finished.
,08-16 14:23:37.782  3935  3935 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 14:23:37.786  3935  3935 I art     : System.exit called, status: 0
,08-16 14:23:37.787  3935  3935 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 14:23:37.858   872  1975 I ActivityManager: Process com.android.bluetooth (pid 3935) has died
,08-16 14:23:40.267  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:40.267  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:43.277  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:43.277  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1da55b7 added. We now have 6 listener(s)
08-16 14:23:43.277  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:43.281  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:43.282  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29e7124 added. We now have 7 listener(s)
08-16 14:23:43.282  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:43.283  3788  3838 I System.out: IsBluetoothEnabled
,08-16 14:23:43.296  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:43.314   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 14:23:43.326   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 14:23:43.326   872   892 I Adreno  : Build Date                       : 10/20/15
08-16 14:23:43.326   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 14:23:43.326   872   892 I Adreno  : Local Branch                     : M14
08-16 14:23:43.326   872   892 I Adreno  : Remote Branch                    : 
08-16 14:23:43.326   872   892 I Adreno  : Remote Branch                    : 
08-16 14:23:43.326   872   892 I Adreno  : Reconstruct Branch               : 
,08-16 14:23:43.355   872   889 I ActivityManager: Start proc 4146:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 14:23:43.359   281   347 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (275 us)
,08-16 14:23:43.361  1891  1891 I Keyboard.Facilitator: onFinishInput()
,08-16 14:23:43.423  4146  4146 D AdapterServiceConfig: Adding HeadsetService
,08-16 14:23:43.424  4146  4146 D AdapterServiceConfig: Adding A2dpService
,08-16 14:23:43.424  4146  4146 D AdapterServiceConfig: Adding HidService
,08-16 14:23:43.424  4146  4146 D AdapterServiceConfig: Adding HealthService
,08-16 14:23:43.424  4146  4146 D AdapterServiceConfig: Adding PanService
,08-16 14:23:43.424  4146  4146 D AdapterServiceConfig: Adding GattService
08-16 14:23:43.425  4146  4146 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 14:23:43.439   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@57990ad:true
,08-16 14:23:43.439  4146  4146 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 14:23:43.446  4146  4146 I bt_bluedroid: init
08-16 14:23:43.447  4146  4159 I BluetoothAdapterState: Entering OffState
08-16 14:23:43.450  4146  4160 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 14:23:43.450  4146  4160 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:23:43.450  4146  4160 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:23:43.450  4146  4160 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 14:23:43.452  4146  4146 I bt_bluedroid: get_profile_interface socket
08-16 14:23:43.453  4146  4146 I bt_bluedroid: get_profile_interface sdp
,08-16 14:23:43.456  4146  4157 I bt_bluedroid: config_hci_snoop_log
,08-16 14:23:43.457   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 14:23:43.457  4146  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 14:23:43.458  4146  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:23:43.468  4146  4159 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 14:23:43.470  4146  4159 D BluetoothAdapterProperties: Setting state to 14
08-16 14:23:43.471  4146  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 14:23:43.473  4146  4159 D BluetoothBondStateMachine: make
,08-16 14:23:43.476  4146  4164 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 14:23:43.478  4146  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:43.479  4146  4146 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 14:23:43.480  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:43.481  4146  4146 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:23:43.482  4146  4146 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:23:43.482  4146  4146 D BtGatt.GattService: start()
08-16 14:23:43.482  4146  4146 I bt_bluedroid: get_profile_interface gatt
,08-16 14:23:43.483  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:43.483  4146  4146 D BtGatt.AdvertiseManager: advertise manager created
,08-16 14:23:43.488  4146  4146 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:43.489  4146  4146 V BluetoothAdapterState: isTurningOn()=false
08-16 14:23:43.489  4146  4146 V BluetoothAdapterState: isBleTurningOn()=true
08-16 14:23:43.489  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:43.490  4146  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 14:23:43.490  4146  4159 I bt_bluedroid: enable
08-16 14:23:43.490  4146  4160 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 14:23:43.491  4146  4160 I bt_hci  : start_up
,08-16 14:23:43.496  4146  4160 I bt_vendor: alloc value 0xb39c6189
,08-16 14:23:43.497  4146  4160 I bt_vendor: init
08-16 14:23:43.497  4146  4160 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 14:23:43.497  4146  4160 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 14:23:43.605  4146  4160 D bt_hci  : start_up starting async portion
,08-16 14:23:43.610  4146  4168 I bt_hci  : event_finish_startup
,08-16 14:23:43.610  4146  4168 I bt_hci_h4: hal_open
,08-16 14:23:43.610  4146  4168 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 14:23:43.621  4146  4168 I bt_userial_vendor: device fd = 51 open
,08-16 14:23:43.645  4146  4168 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:23:43.678  4146  4168 D bt_hwcfg: Chipset BCM4354A2
,08-16 14:23:43.678  4146  4168 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 14:23:43.679  4146  4168 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 14:23:43.964  3788  3788 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 14:23:43.965  3788  3788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 14:23:44.003   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 14:23:44.004  3788  3788 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ad582f7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9c7548d, 16908290=android.view.AbsSavedState$1@9c7548d}, android:focusedViewId=100}]}]
08-16 14:23:44.005  3788  3788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 14:23:44.007  3788  3788 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:23:44.007  3788  3788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 14:23:44.018   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 14:23:44.022   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-16 14:23:44.022   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-16 14:23:44.023   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 14:23:44.255   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 14:23:44.258   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 14:23:44.264   872  1341 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,08-16 14:23:44.271   872   892 I DreamManagerService: Entering dreamland.
,08-16 14:23:44.274   872   892 I PowerManagerService: Dozing...
,08-16 14:23:44.275   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 14:23:44.316   375  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 14:23:44.317   375  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 14:23:44.321   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:23:44.325   872  1313 E native  : do suspend false
,08-16 14:23:44.333  1955  4173 D NfcService: Discovery configuration equal, not updating.
,08-16 14:23:44.350   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:23:44.355   872  1313 E native  : do suspend true
,08-16 14:23:44.365  4146  4168 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 14:23:44.365  4146  4168 D bt_hwcfg: Settlement delay -- 100 ms
08-16 14:23:44.365  4146  4168 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 14:23:44.457   375  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 14:23:44.458   375  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 14:23:44.482  4146  4168 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:23:44.484  4146  4168 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 14:23:44.515  4146  4168 I bt_hwcfg: vendor lib fwcfg completed
,08-16 14:23:44.515  4146  4168 I bt_vendor: firmware callback
08-16 14:23:44.516  4146  4168 I bt_hci  : firmware_config_callback
,08-16 14:23:44.532  4146  4177 I bt_btu  : btu_task pending for preload complete event
,08-16 14:23:44.532  4146  4177 I bt_btu_task: Bluetooth chip preload is complete
08-16 14:23:44.532  4146  4177 I bt_btu  : btu_task received preload complete event
,08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:23:44.536  4146  4177 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:23:44.537  4146  4177 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 14:23:44.664  4146  4177 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3943d9d
,08-16 14:23:44.665  4146  4177 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3943d9d 
,08-16 14:23:44.676  4146  4163 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 14:23:44.678  4146  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 14:23:44.682  4146  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 14:23:44.687  4146  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:23:44.692  4146  4163 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:23:44.693  4146  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:23:44.693  4146  4163 D bt_hci  : do_postload posting postload work item
08-16 14:23:44.694  4146  4168 I bt_hci  : event_postload
08-16 14:23:44.694  4146  4168 I bt_vendor: sco_config_cb
,08-16 14:23:44.694  4146  4168 I bt_hci  : sco_config_callback postload finished.
08-16 14:23:44.696  4146  4168 I bt_vendor: low_power_mode_cb
08-16 14:23:44.697  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:44.698  4146  4163 D bt_bte_conf: Device ID record 1 : primary
08-16 14:23:44.698  4146  4163 D bt_bte_conf:   vendorId            = 000f
08-16 14:23:44.698  4146  4163 D bt_bte_conf:   vendorIdSource      = 0001
08-16 14:23:44.699  4146  4163 D bt_bte_conf:   product             = 1200
08-16 14:23:44.699  4146  4163 D bt_bte_conf:   version             = 1436
,08-16 14:23:44.699  4146  4163 D bt_bte_conf:   clientExecutableURL = 
,08-16 14:23:44.699  4146  4163 D bt_bte_conf:   serviceDescription  = 
08-16 14:23:44.700  4146  4163 D bt_bte_conf:   documentationURL    = 
08-16 14:23:44.700  4146  4163 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 14:23:44.701  4146  4160 D bt_stack_manager: event_start_up_stack finished
08-16 14:23:44.702  4146  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 14:23:44.702  4146  4159 D BluetoothAdapterProperties: Setting state to 15
,08-16 14:23:44.703  4146  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 14:23:44.704  4146  4159 I BluetoothAdapterState: Entering BleOnState
,08-16 14:23:44.709  4146  4159 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 14:23:44.709  4146  4159 D BluetoothAdapterProperties: Setting state to 11
,08-16 14:23:44.709  4146  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 14:23:44.721  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:44.722  4146  4146 D HeadsetService: Received start request. Starting profile...
08-16 14:23:44.725  4146  4146 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 14:23:44.725  4146  4146 D HeadsetStateMachine: make
08-16 14:23:44.727  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:44.745  4146  4146 D HeadsetStateMachine: max_hf_connections = 1
,08-16 14:23:44.745  4146  4146 I bt_bluedroid: get_profile_interface handsfree
08-16 14:23:44.745  4146  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 14:23:44.746  4146  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 14:23:44.758  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:44.758  4146  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:23:44.758  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:23:44.759  4146  4146 D A2dpService: Received start request. Starting profile...
,08-16 14:23:44.760  4146  4146 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 14:23:44.760  4146  4146 I bt_bluedroid: get_profile_interface avrcp
,08-16 14:23:44.770  4146  4146 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:23:44.770  4146  4146 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:23:44.770  4146  4146 D A2dpStateMachine: make
,08-16 14:23:44.773  4146  4146 I bt_bluedroid: get_profile_interface a2dp
08-16 14:23:44.775  4146  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 14:23:44.776  4146  4186 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:23:44.776  4146  4146 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:23:44.778  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:44.779  4146  4146 D HidService: Received start request. Starting profile...
08-16 14:23:44.779  4146  4146 I bt_bluedroid: get_profile_interface hidhost
,08-16 14:23:44.780  4146  4146 D HidService: setHidService(): set to: null
08-16 14:23:44.780  4146  4163 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39253e5
08-16 14:23:44.780  4146  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 14:23:44.781  4146  4146 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:23:44.782  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:44.783  4146  4146 D HealthService: Received start request. Starting profile...
,08-16 14:23:44.786  4146  4146 I bt_bluedroid: get_profile_interface health
08-16 14:23:44.786  4146  4146 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 14:23:44.787  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:44.788  4146  4146 D PanService: Received start request. Starting profile...
08-16 14:23:44.788  4146  4146 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:23:44.788  4146  4146 I bt_bluedroid: get_profile_interface pan
,08-16 14:23:44.789  4146  4163 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 14:23:44.791  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:44.791  4146  4146 V BluetoothAdapterState: isTurningOn()=true
,08-16 14:23:44.792  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:44.792  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:44.795  4146  4184 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:23:44.796  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
08-16 14:23:44.797  4146  4146 D BluetoothMapService: Received start request. Starting profile...
08-16 14:23:44.797  4146  4146 D BluetoothMapService: start()
,08-16 14:23:44.802  4146  4146 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 14:23:44.803  4146  4146 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 14:23:44.803  4146  4146 D BluetoothMapAppObserver: createReceiver()
,08-16 14:23:44.804  4146  4146 D BluetoothMapAppObserver: initObservers()
08-16 14:23:44.805  4146  4146 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 14:23:44.812  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:44.812  4146  4146 V BluetoothAdapterState: isTurningOn()=true
,08-16 14:23:44.812  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:23:44.812  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:23:44.813  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:23:44.814  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:23:44.815  4146  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 14:23:44.816  4146  4159 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:23:44.816  4146  4159 D BluetoothAdapterProperties: State =  11
08-16 14:23:44.816  4146  4159 D BluetoothAdapterProperties: Setting state to 12
08-16 14:23:44.816  4146  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:23:44.820  4146  4159 I BluetoothAdapterState: Entering OnState
08-16 14:23:44.820  1372  2076 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:23:44.824  4146  4163 D BluetoothAdapterProperties: Scan Mode:21
,08-16 14:23:44.825  4146  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:44.828  1372  1372 D BluetoothInputDevice: Proxy object connected
08-16 14:23:44.828  1372  1384 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:23:44.828  1372  1372 D HidProfile: Bluetooth service connected
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:44.828  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:44.832  4146  4146 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 14:23:44.833  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:44.833  4146  4146 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 14:23:44.836  3855  3865 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:44.836  4146  4146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:44.839  1969  3492 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:44.840  4146  4146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:44.840   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:44.841  1372  1383 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:23:44.841  4146  4146 D ObexServerSockets: Succeed to create listening sockets 
08-16 14:23:44.842  4146  4146 D ObexServerSockets0: startAccept()
08-16 14:23:44.842  4146  4146 D ObexServerSockets0: prepareForNewConnect()
,08-16 14:23:44.844   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:44.844  3855  3868 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 14:23:44.848  1372  2076 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:44.848  4146  4146 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 14:23:44.849  4146  4146 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 14:23:44.850  3855  3855 D BluetoothInputDevice: Proxy object connected
08-16 14:23:44.850  3855  3855 D HidProfile: Bluetooth service connected
08-16 14:23:44.850  1372  1384 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:23:44.852  1372  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:44.852  4146  4192 D ObexServerSockets0: Accepting socket connection...
08-16 14:23:44.853  3855  3865 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 14:23:44.853  4146  4194 D ObexServerSockets0: Accepting socket connection...
08-16 14:23:44.853  1372  1372 D BluetoothMap: Proxy object connected
08-16 14:23:44.853  1372  1372 D MapProfile: Bluetooth service connected
08-16 14:23:44.853  1372  1372 D BluetoothMap: getConnectedDevices()
08-16 14:23:44.854   872   872 D BluetoothA2dp: Proxy object connected
08-16 14:23:44.855   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:23:44.855  3855  3868 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:23:44.856  1372  1372 D BluetoothA2dp: Proxy object connected
08-16 14:23:44.857  3855  3865 D BluetoothPan: onBluetoothStateChange on: true
,08-16 14:23:44.858  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:23:44.858  1372  1372 D PanProfile: Bluetooth service connected
08-16 14:23:44.858   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:23:44.859  3855  3868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:23:44.860   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 14:23:44.861  4146  4146 D BluetoothMapService: onReceive
,08-16 14:23:44.861  4146  4146 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:44.861  4146  4146 D BluetoothMapService: STATE_ON
,08-16 14:23:44.863  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:44.864  3855  3855 D BluetoothA2dp: Proxy object connected
,08-16 14:23:44.865  3855  3855 D BluetoothMap: Proxy object connected
08-16 14:23:44.865  3855  3855 D MapProfile: Bluetooth service connected
08-16 14:23:44.865  3855  3855 D BluetoothMap: getConnectedDevices()
,08-16 14:23:44.867  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 14:23:44.867  3855  3855 D PanProfile: Bluetooth service connected
,08-16 14:23:44.871  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:44.876  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:44.877  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:44.886  3855  3855 D BluetoothPbap: Proxy object connected
,08-16 14:23:44.886  3855  3855 D PbapServerProfile: Bluetooth service connected
,08-16 14:23:44.889  1372  1372 D BluetoothPbap: Proxy object connected
,08-16 14:23:44.889  1372  1372 D PbapServerProfile: Bluetooth service connected
,08-16 14:23:44.892  4146  4146 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 14:23:44.892  4146  4146 D ObexServerSockets0: prepareForNewConnect()
,08-16 14:23:44.897  4146  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:44.910  4146  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:44.911  4146  4202 I BtOppRfcommListener: Accept thread started.
,08-16 14:23:44.942   872   872 D BluetoothHeadset: Proxy object connected
,08-16 14:23:44.942  3855  4193 D BluetoothHeadset: Proxy object connected
08-16 14:23:44.942  3855  3855 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:44.943   872   872 D BluetoothHeadset: Proxy object connected
08-16 14:23:44.943  1969  1982 D BluetoothHeadset: Proxy object connected
08-16 14:23:44.943   872   872 D BluetoothHeadset: Proxy object connected
08-16 14:23:44.944  1372  2076 D BluetoothHeadset: Proxy object connected
,08-16 14:23:44.944  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:44.953  1372  1384 D BluetoothHeadset: Proxy object connected
,08-16 14:23:44.953  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:44.955   872   889 D BluetoothHeadset: Proxy object connected
,08-16 14:23:44.958   872   889 D BluetoothHeadset: Proxy object connected
,08-16 14:23:44.960  3855  3868 D BluetoothHeadset: Proxy object connected
08-16 14:23:44.960  3855  3855 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:45.320  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:45.326  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:45.329  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:45.330  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b02642 added. We now have 8 listener(s)
,08-16 14:23:45.330  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:45.335   872  2115 D WifiService: setWifiEnabled: false pid=3788, uid=10000
,08-16 14:23:45.336   872  2115 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:23:45.349  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:45.350   872  1975 D WifiService: setWifiEnabled: true pid=3788, uid=10000
08-16 14:23:45.350   872  1975 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:23:45.362   872  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:45.380  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:45.388  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:45.406   872  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-16 14:23:45.407   872  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 14:23:45.408   872  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 14:23:45.409   872  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 14:23:45.409   872  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 14:23:45.409   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 14:23:45.410   872  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 14:23:45.431   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 14:23:45.432   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:45.433   872  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.07 delta 1000 -> 1000
08-16 14:23:45.433   872  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 14:23:45.433   872  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 14:23:45.434   872  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 14:23:45.448   872  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 14:23:45.448   872  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 14:23:45.453   872  1313 E native  : do suspend true
,08-16 14:23:45.497   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-16 14:23:45.497   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:45.509   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 14:23:45.586   872  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 14:23:45.588  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 14:23:46.024  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 14:23:46.059  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 14:23:46.060  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 14:23:46.064   872  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:23:46.072   872  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 14:23:46.072   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 14:23:46.073   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:46.097   872  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:46.113   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:46.114   872  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 14:23:46.123   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 14:23:46.159   872  4210 D DhcpClient: Receive thread started
,08-16 14:23:46.249   872  1313 E native  : do suspend false
,08-16 14:23:46.270   872  1870 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 14:23:46.283   872  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 14:23:46.284   872  1870 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 14:23:46.287   872  1870 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 14:23:46.302   872  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-16 14:23:46.303   872  1870 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 14:23:46.307   371   870 D CommandListener: Setting iface cfg
,08-16 14:23:46.320   872  1870 D DhcpClient: Scheduling renewal in 86399s
08-16 14:23:46.321   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 14:23:46.324   872  1313 E native  : do suspend true
,08-16 14:23:46.355   872  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 14:23:46.358   872  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 14:23:46.360   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 14:23:46.362   872  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 14:23:46.372   872  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:46.378  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:46.380  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:46.384  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 14:23:46.385  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 14:23:46.387  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ad582f7 Bundle[{}]
08-16 14:23:46.387  3788  3838 I io.jxcore.node.LifeCycleMonitor: start: OK,
08-16 14:23:46.388  3788  3838 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 14:23:46.388  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 14:23:46.389  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:23:46.389  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
08-16 14:23:46.390  3788  3838 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 14:23:46.394  3788  3838 I System.out: Running OutgoingSocketThread
,08-16 14:23:46.396  3788  4212 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
,08-16 14:23:46.398  3788  4212 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37502
,08-16 14:23:46.399  3788  4212 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 14:23:46.422   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 14:23:46.422   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 14:23:46.423   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 14:23:46.424   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 14:23:46.425   872  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 14:23:46.434   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 14:23:46.439   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 14:23:46.439   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 14:23:46.440   872  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 14:23:46.440   872  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 14:23:46.440   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 14:23:46.441   872  1315 D ConnectivityService:    accepting network in place of null,
08-16 14:23:46.442   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 14:23:46.451   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153386, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 14:23:46.472   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:23:46.502   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:23:46.510   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 14:23:46.511   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:46.516   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 14:23:46.520   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:23:46.523   872  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:802::200e
,08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:46.547  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:46.549  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:46.551  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:23:46.556  1691  1691 D SystemUpdateService: onCreate
,08-16 14:23:46.563  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:23:46.570  1691  4220 I SystemUpdateService: active receiver: enabled
,08-16 14:23:46.586  1691  4220 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:23:46.589  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 14:23:46.598  1691  4220 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 14:23:46.598  1691  4220 I SystemUpdateService: now status is 0 (complete)
,08-16 14:23:46.599  1691  4220 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 14:23:46.599  1691  4220 I SystemUpdateService: file has been verified
08-16 14:23:46.599  1691  4220 I SystemUpdateService: OTA package size = 12249756
08-16 14:23:46.592  1691  2462 I iu.UploadsManager: num queued entries: 0
,08-16 14:23:46.602  1691  2462 I iu.UploadsManager: num updated entries: 0
,08-16 14:23:46.604   872  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:23:46 GMT], X-Android-Received-Millis=[1471350226604], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471350226575]}
,08-16 14:23:46.605   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 14:23:46.605   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 14:23:46.605   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 14:23:46.606   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 14:23:46.609  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:23:46.611  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 14:23:46.615  1691  2462 I iu.SyncManager: NEXT; no task
,08-16 14:23:46.617  1691  4220 I SystemUpdateService: showing system update notification
,08-16 14:23:46.622  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:46.625  1691  4226 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 14:23:46.625  1691  4226 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 14:23:46.628  3949  3949 D SprintDMHelper: simOperator: 
08-16 14:23:46.628  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:23:46.629  1691  4226 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 14:23:46.658  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:46.659  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:23:46.684  1691  1691 D SystemUpdateService: onDestroy
,08-16 14:23:46.696  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 14:23:46.696  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 14:23:46.696  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 14:23:46.696  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:46.703  1512  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 14:23:46.703  1512  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 14:23:46.703  1512  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:46.703  1512  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:46.713  3001  4227 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 14:23:46.713  3001  4227 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jdm.a(PG:82)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jcs.o(PG:406)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jcn.a(PG:1379)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jcs.i(PG:143)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at blb.a(PG:3937)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at czp.a(PG:18188)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at czp.a(PG:9087)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at czq.run(PG:1686)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:46.713  3001  4227 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jdj.a(PG:4091)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jdj.a(PG:1125)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jdm.a(PG:77)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	... 12 more
08-16 14:23:46.713  3001  4227 E HttpOperation: Caused by: faj: BadAuthentication
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at fal.a(PG:38)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	at jdj.a(PG:4089)
08-16 14:23:46.713  3001  4227 E HttpOperation: 	... 14 more
,08-16 14:23:46.722  1691  4226 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-16 14:23:46.789  2278  4231 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 14:23:46.990  1512  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 14:23:46.991  1512  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 14:23:46.991  1512  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:23:46.992  1512  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:47.044  3001  4237 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 14:23:47.044  3001  4237 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jdm.a(PG:82)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jcs.o(PG:406)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jcn.a(PG:1379)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jcs.i(PG:143)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at blb.a(PG:3937)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at czp.a(PG:18188)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at czp.a(PG:9081)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at czq.run(PG:1686)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:47.044  3001  4237 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jdj.a(PG:4091)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jdj.a(PG:1125)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jdm.a(PG:77)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	... 12 more
08-16 14:23:47.044  3001  4237 E HttpOperation: Caused by: faj: BadAuthentication
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at fal.a(PG:38)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	at jdj.a(PG:4089)
08-16 14:23:47.044  3001  4237 E HttpOperation: 	... 14 more
,08-16 14:23:47.129  1512  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 14:23:47.129  1512  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 14:23:47.129  1512  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 14:23:47.131  1512  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:23:47.157  3001  4237 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 14:23:47.157  3001  4237 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jdm.a(PG:82)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jcs.o(PG:406)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jcn.a(PG:1379)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jcs.i(PG:143)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at hec.a(PG:42)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at hee.a(PG:102)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at czr.a(PG:65)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at kka.a(PG:108)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at czp.a(PG:19176)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at czp.a(PG:9081)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at czq.run(PG:1686)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:47.157  3001  4237 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jdj.a(PG:4091)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jdj.a(PG:1125)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jdm.a(PG:77)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	... 15 more
08-16 14:23:47.157  3001  4237 E HttpOperation: Caused by: faj: BadAuthentication
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at fal.a(PG:38)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	at jdj.a(PG:4089)
08-16 14:23:47.157  3001  4237 E HttpOperation: 	... 17 more
,08-16 14:23:47.157  3001  4237 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 14:23:47.157  3001  4237 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at hec.a(PG:42)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at hee.a(PG:102)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at czr.a(PG:65)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at kka.a(PG:108)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	... 15 more
08-16 14:23:47.157  3001  4237 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at fal.a(PG:38)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 14:23:47.157  3001  4237 E ExperimentLoader: 	... 17 more
,08-16 14:23:47.293   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 136789, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 14:23:47.397  3788  3838 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,08-16 14:23:47.397  3788  3838 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,08-16 14:23:47.407  3788  3838 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-16 14:23:47.410  3788  3838 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 14:23:47.410  3788  3838 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-16 14:23:47.418  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:23:47.419  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab49653 added. We now have 2 listener(s)
,08-16 14:23:47.426  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.426  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:23:47.427  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.427  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:47.428  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be37b90 added. We now have 9 listener(s)
08-16 14:23:47.429  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:47.430  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:47.432  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:47.439  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:47.442  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:47.443  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:47.443  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:23:47.443  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9e648e added. We now have 3 listener(s)
08-16 14:23:47.445  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.445  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.445  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:23:47.445  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:47.445  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e844af added. We now have 10 listener(s)
,08-16 14:23:47.445  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.446  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:47.446  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:23:47.446  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:47.446  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:47.446  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.446  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:47.446  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 14:23:47.446  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab49653 removed from the list
08-16 14:23:47.446  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.446  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be37b90 removed from the list
08-16 14:23:47.447  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:47.450  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:47.450  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:47.451  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.451  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.452  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.454  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:23:47.454  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.454  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.455  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be37b90 not in the list
08-16 14:23:47.455  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.455  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.457  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:47.458  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:47.458  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.458  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e844af removed from the list
,08-16 14:23:47.459  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:47.459  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.459  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:47.459  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:47.460  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9e648e removed from the list
,08-16 14:23:47.462  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:23:47.462  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc0bc added. We now have 2 listener(s)
,08-16 14:23:47.468  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.468  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.468  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:23:47.469  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:47.469  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f8845 added. We now have 9 listener(s)
08-16 14:23:47.469  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:47.470  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:47.474  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:47.479  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:47.482  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:47.482  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:47.482  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.482  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffe7ccb added. We now have 3 listener(s)
,08-16 14:23:47.484  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.484  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:23:47.484  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:23:47.484  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:47.484  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9632ca8 added. We now have 10 listener(s)
08-16 14:23:47.485  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.485  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:23:47.485  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:47.485  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:47.485  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:47.485  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:47.485  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:23:47.488  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:47.489  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 14:23:47.490  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:47.493  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:23:47.494  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 14:23:47.495  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:47.499  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:23:47.499  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:23:47.499  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 14:23:47.500  3788  3838 D BluetoothAdapter: STATE_ON
,08-16 14:23:47.504  4146  4183 D BtGatt.GattService: registerClient() - UUID=7fb2d397-f003-40ec-87b6-a06fcee19402
,08-16 14:23:47.506  4146  4163 D BtGatt.GattService: onClientRegistered() - UUID=7fb2d397-f003-40ec-87b6-a06fcee19402, clientIf=5
,08-16 14:23:47.507  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 14:23:47.508  4146  4191 D BtGatt.GattService: start scan with filters
,08-16 14:23:47.509   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 14:23:47.513  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 14:23:47.513  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:23:47.513  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:47.513  4146  4167 D BtGatt.ScanManager: handling starting scan
08-16 14:23:47.513  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:47.515  4146  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb1001b
,08-16 14:23:47.519  4146  4163 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 14:23:47.519  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.520  4146  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:23:47.522  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:47.522  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:47.522  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:23:47.527  4146  4163 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 14:23:47.527  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.528  4146  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:47.528  4146  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:47.529  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:23:47.534  3788  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 14:23:47.534  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:23:47.534  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 14:23:47.534  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.534  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:23:47.534  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,08-16 14:23:47.535  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 14:23:47.535  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 14:23:47.535  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 14:23:47.535  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,08-16 14:23:47.535  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:23:47.536  3788  3838 D BluetoothAdapter: STATE_ON
,08-16 14:23:47.537  4146  4156 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:23:47.537  4146  4157 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:23:47.538  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-16 14:23:47.538  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 14:23:47.538  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:47.538  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 14:23:47.538  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 14:23:47.540  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:47.540  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:23:47.540  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:47.540  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:47.541  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:47.542  4146  4163 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:23:47.542  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:47.542  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.542  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:47.543  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:47.547  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:47.547  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:47.547  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:47.547  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:47.547  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.547  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:47.547  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 14:23:47.548  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc0bc removed from the list
08-16 14:23:47.548  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.548  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f8845 removed from the list
08-16 14:23:47.548  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:47.548  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.549  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.549  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.550  4146  4163 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:23:47.550  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:47.550  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.550  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:47.550  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.550  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f8845 not in the list
08-16 14:23:47.550  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.551  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:47.552  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.552  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:47.552  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.552  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9632ca8 removed from the list
08-16 14:23:47.552  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:47.552  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.552  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.552  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:47.552  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffe7ccb removed from the list
,08-16 14:23:47.553  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.553  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5126b54 added. We now have 2 listener(s)
08-16 14:23:47.555  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:23:47.555  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.556  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.556  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:47.556  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c837afd added. We now have 9 listener(s)
08-16 14:23:47.556  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.556  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:47.559  4146  4163 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:23:47.559  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.559  4146  4167 D BtGatt.ScanManager: stopping BLe Batch
08-16 14:23:47.559  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:47.565  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:47.567  4146  4163 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 14:23:47.567  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.567  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.567  4146  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 14:23:47.567  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:47.569  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.569  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdfba43 added. We now have 3 listener(s)
08-16 14:23:47.570  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:47.571  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.571  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.571  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.571  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:47.571  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd4e8c0 added. We now have 10 listener(s)
08-16 14:23:47.571  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.571  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:47.572  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:23:47.572  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:47.572  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:47.572  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:47.573  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:47.573  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:23:47.573  4146  4163 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:47.574  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.580  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 14:23:47.580  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:47.584  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:23:47.584  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:23:47.584  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:47.588  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:23:47.588  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:23:47.588  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 14:23:47.589  3788  3838 D BluetoothAdapter: STATE_ON
,08-16 14:23:47.591  4146  4183 D BtGatt.GattService: registerClient() - UUID=fe673be0-53b5-4cee-b440-be364e137a7b
,08-16 14:23:47.591  4146  4163 D BtGatt.GattService: onClientRegistered() - UUID=fe673be0-53b5-4cee-b440-be364e137a7b, clientIf=5
08-16 14:23:47.592  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:23:47.592  4146  4191 D BtGatt.GattService: start scan with filters
,08-16 14:23:47.595  4146  4167 D BtGatt.ScanManager: handling starting scan
,08-16 14:23:47.595  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:47.595  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:23:47.595  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:47.595  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:47.597  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:47.598  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:47.598  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:23:47.600  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-16 14:23:47.603  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:23:47.603  3788  3838 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:23:47.603  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:47.603  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:23:47.603  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-16 14:23:47.603  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:47.603  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.603  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:23:47.604  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-16 14:23:47.604  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5126b54 removed from the list
,08-16 14:23:47.604  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:47.604  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c837afd removed from the list
08-16 14:23:47.604  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:47.604  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:47.604  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.604  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 14:23:47.604  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.605  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:47.605  4146  4163 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 14:23:47.605  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-16 14:23:47.605  4146  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:23:47.605  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:23:47.605  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:47.605  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:47.605  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c837afd not in the list
,08-16 14:23:47.606  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 14:23:47.606  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:47.606  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:47.606  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 14:23:47.606  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:23:47.606  3788  3838 D BluetoothAdapter: STATE_ON
,08-16 14:23:47.607  4146  4156 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:23:47.607  4146  4157 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:23:47.607  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:23:47.608  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:47.608  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 14:23:47.608  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 14:23:47.608  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:23:47.609  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:47.609  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 14:23:47.609  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:47.609  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:47.609  4146  4163 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:23:47.609  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.609  4146  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:47.610  4146  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 14:23:47.610  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.610  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:47.611  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:47.611  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:47.611  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.611  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:47.611  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.611  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd4e8c0 removed from the list
,08-16 14:23:47.611  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:47.611  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.611  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.611  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 14:23:47.611  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdfba43 removed from the list
08-16 14:23:47.612  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.612  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fd0ec added. We now have 2 listener(s)
,08-16 14:23:47.614  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:23:47.614  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.614  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.614  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:47.614  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19c0cb5 added. We now have 9 listener(s)
,08-16 14:23:47.614  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.614  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:23:47.616  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:47.618  4146  4163 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:23:47.618  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:47.621  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:47.623  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.623  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:47.623  4146  4163 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:23:47.623  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.624  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.624  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c2ebb added. We now have 3 listener(s)
,08-16 14:23:47.625  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:47.626  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.626  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.626  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.626  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:47.626  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f0fd8 added. We now have 10 listener(s)
08-16 14:23:47.627  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.627  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:23:47.628  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:47.627  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:47.629  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:47.629  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:47.629  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:23:47.633  4146  4163 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:23:47.633  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.633  4146  4167 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:23:47.633  3788  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 14:23:47.633  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:23:47.637  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:23:47.637  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 14:23:47.637  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:23:47.638  4146  4163 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:23:47.638  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.638  4146  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:23:47.642  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 14:23:47.642  4146  4163 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:47.642  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 14:23:47.642  3788  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 14:23:47.642  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.643  3788  3838 D BluetoothAdapter: STATE_ON
08-16 14:23:47.644  4146  4191 D BtGatt.GattService: registerClient() - UUID=d604e18e-954b-4e5f-b9b2-e279cccea331
,08-16 14:23:47.645  4146  4163 D BtGatt.GattService: onClientRegistered() - UUID=d604e18e-954b-4e5f-b9b2-e279cccea331, clientIf=5
08-16 14:23:47.645  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:23:47.645  4146  4183 D BtGatt.GattService: start scan with filters
08-16 14:23:47.647  4146  4167 D BtGatt.ScanManager: handling starting scan
,08-16 14:23:47.647  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:47.647  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:23:47.647  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:47.647  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:47.649  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:47.650  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:47.650  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:23:47.651  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:23:47.652  4146  4163 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 14:23:47.652  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.652  4146  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:23:47.655  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:47.655  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:23:47.655  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:47.655  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:47.656  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.656  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:47.656  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:47.656  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fd0ec removed from the list
,08-16 14:23:47.656  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.656  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19c0cb5 removed from the list
,08-16 14:23:47.656  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:47.656  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:47.656  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.656  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 14:23:47.656  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.656  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:47.657  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:47.657  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.657  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.657  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19c0cb5 not in the list
,08-16 14:23:47.657  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:47.657  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:47.657  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:47.657  4146  4163 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:23:47.657  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:47.657  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.657  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:23:47.658  4146  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:47.658  4146  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:47.658  3788  3838 D BluetoothAdapter: STATE_ON
08-16 14:23:47.658  4146  4191 D BtGatt.GattService: stopScan() - queue size =1
08-16 14:23:47.659  4146  4156 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:23:47.659  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:23:47.659  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:47.659  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:47.659  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:47.659  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 14:23:47.660  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:47.660  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 14:23:47.660  3788  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:47.660  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:47.660  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.661  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:47.661  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:47.661  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:47.661  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.661  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:23:47.661  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.661  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f0fd8 removed from the list
08-16 14:23:47.661  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:47.661  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.661  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.661  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:47.661  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c2ebb removed from the list
08-16 14:23:47.662  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.662  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7515184 added. We now have 2 listener(s)
08-16 14:23:47.663  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:23:47.663  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:23:47.663  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.664  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:47.664  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48e1d6d added. We now have 9 listener(s)
08-16 14:23:47.664  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.664  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:23:47.665  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:47.666  4146  4163 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:23:47.666  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:47.668  3788  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:47.670  3788  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:47.670  3788  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:47.671  4146  4163 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:23:47.671  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.671  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:47.671  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d3ba33 added. We now have 3 listener(s)
08-16 14:23:47.671  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:47.672  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:23:47.672  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:47.673  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:47.675  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:47.675  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:47.675  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5401f0 added. We now have 10 listener(s)
08-16 14:23:47.675  3788  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:47.676  3788  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:47.676  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:47.676  3788  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:47.676  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:47.676  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.676  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:47.676  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:47.676  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7515184 removed from the list
,08-16 14:23:47.676  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:47.676  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48e1d6d removed from the list
08-16 14:23:47.676  3788  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:47.677  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:47.677  4146  4163 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 14:23:47.677  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:47.677  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:47.677  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:47.677  4146  4167 D BtGatt.ScanManager: stopping BLe Batch
08-16 14:23:47.678  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:23:47.678  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.678  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:23:47.678  3788  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48e1d6d not in the list
08-16 14:23:47.678  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.678  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:47.678  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:47.678  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:47.679  3788  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 14:23:47.679  3788  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5401f0 removed from the list
,08-16 14:23:47.679  3788  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:47.679  3788  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:47.679  3788  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:47.679  3788  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:47.679  3788  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d3ba33 removed from the list
,08-16 14:23:47.679  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 14:23:47.679  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 14:23:47.680  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 14:23:47.680  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:47.680  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-16 14:23:47.680  3788  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:47.683  4146  4163 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:23:47.683  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-16 14:23:47.683  4146  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:23:47.684  3788  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
08-16 14:23:47.684  3788  4240 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
08-16 14:23:47.684  3788  4240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122,
08-16 14:23:47.685  3788  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
08-16 14:23:47.685  3788  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
,08-16 14:23:47.685  3788  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 14:23:47.686  3788  3838 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-16 14:23:47.686  3788  3838 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 14:23:47.686  3788  3838 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-16 14:23:47.686  3788  3838 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 14:23:47.686  3788  3838 D com.test.thalitest.ThaliTestRunner: Total duration: 22786 ms
08-16 14:23:47.688  4146  4163 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:47.688  4146  4163 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:47.688  3788  3838 I jxcore-log: Total number of executed tests:  80
08-16 14:23:47.688  3788  3838 I jxcore-log: 
08-16 14:23:47.688  3788  3838 I jxcore-log: Number of passed tests:  80
08-16 14:23:47.688  3788  3838 I jxcore-log: 
08-16 14:23:47.688  3788  3838 I jxcore-log: Number of failed tests:  0
08-16 14:23:47.688  3788  3838 I jxcore-log: 
08-16 14:23:47.688  3788  3838 I jxcore-log: Number of ignored tests:  0
08-16 14:23:47.688  3788  3838 I jxcore-log: 
,08-16 14:23:47.688  3788  3838 I jxcore-log: Total duration:  22786
08-16 14:23:47.688  3788  3838 I jxcore-log: 
08-16 14:23:47.689  3788  3838 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 14:23:47.689  3788  3838 I jxcore-log: 
08-16 14:23:47.691  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.691  3788  3838 I jxcore-log: 
,08-16 14:23:47.693  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.693  3788  3838 I jxcore-log: 
08-16 14:23:47.694  3788  3788 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 14:23:47.695  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.695  3788  3838 I jxcore-log: 
08-16 14:23:47.695  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.695  3788  3838 I jxcore-log: 
08-16 14:23:47.696  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.696  3788  3838 I jxcore-log: 
08-16 14:23:47.697  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.697  3788  3838 I jxcore-log: 
08-16 14:23:47.698  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.698  3788  3838 I jxcore-log: 
08-16 14:23:47.699  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.699  3788  3838 I jxcore-log: 
08-16 14:23:47.700  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.700  3788  3838 I jxcore-log: 
08-16 14:23:47.700  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:47.700  3788  3838 I jxcore-log: 
08-16 14:23:47.701  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:23:47.701  3788  3838 I jxcore-log: 
08-16 14:23:47.701  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:23:47.701  3788  3838 I jxcore-log: 
08-16 14:23:47.702  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.702  3788  3838 I jxcore-log: 
08-16 14:23:47.703  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.703  3788  3838 I jxcore-log: 
08-16 14:23:47.703  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.703  3788  3838 I jxcore-log: 
08-16 14:23:47.704  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.704  3788  3838 I jxcore-log: 
08-16 14:23:47.704  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.704  3788  3838 I jxcore-log: 
08-16 14:23:47.705  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.705  3788  3838 I jxcore-log: 
08-16 14:23:47.705  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.705  3788  3838 I jxcore-log: 
08-16 14:23:47.705  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.705  3788  3838 I jxcore-log: 
08-16 14:23:47.706  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.706  3788  3838 I jxcore-log: 
08-16 14:23:47.706  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:47.706  3788  3838 I jxcore-log: 
08-16 14:23:47.707  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:23:47.707  3788  3838 I jxcore-log: 
08-16 14:23:47.708  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:23:47.708  3788  3838 I jxcore-log: 
08-16 14:23:47.708  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.708  3788  3838 I jxcore-log: 
08-16 14:23:47.709  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.709  3788  3838 I jxcore-log: 
08-16 14:23:47.709  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.709  3788  3838 I jxcore-log: 
08-16 14:23:47.710  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.710  3788  3838 I jxcore-log: 
08-16 14:23:47.710  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.710  3788  3838 I jxcore-log: 
08-16 14:23:47.711  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:47.711  3788  3838 I jxcore-log: 
,08-16 14:23:48.044  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:23:48.049  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:48.049  3788  3838 I jxcore-log: 
,08-16 14:23:48.111  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:23:48.114  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:48.114  3788  3838 I jxcore-log: 
,08-16 14:23:48.161  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:23:48.165  3788  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:48.165  3788  3838 I jxcore-log: 
,08-16 14:23:48.347  4242  4242 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 14:23:48.352  4242  4242 D AndroidRuntime: CheckJNI is OFF
,08-16 14:23:48.395  4242  4242 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 14:23:48.445  4242  4242 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 14:23:48.468  4242  4242 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 14:23:48.482   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 14:23:48.482   872   885 I ActivityManager: Killing 3788:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 14:23:48.564   872  1975 D GraphicsStats: Buffer count: 2
,08-16 14:23:48.564   872  1396 I WindowState: WIN DEATH: Window{4ed88b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:23:48.566   872  1314 D WifiService: Client connection lost with reason: 4
,08-16 14:23:48.599   872   895 W PackageSettings: Skipping PackageSetting{2e9a91c com.example.hello/10273} due to missing metadata
,08-16 14:23:48.623   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 14:23:48.623   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 14:23:48.624   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-16 14:23:48.624   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
,08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 14:23:48.624   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:48.624   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:48.624   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:23:48.624   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 14:23:48.625   872   885 I ActivityManager:   Force finishing activity ActivityRecord{31c11f8 u0 com.test.thalitest/.MainActivity t2}
08-16 14:23:48.626   872   895 I art     : Starting a blocking GC Explicit
,08-16 14:23:48.638   872  1975 W ActivityManager: Spurious death for ProcessRecord{299da37 0:com.test.thalitest/u0a0}, curProc for 3788: null
,08-16 14:23:48.665   872   895 I art     : Explicit concurrent mark sweep GC freed 15121(1041KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 666us total 39.130ms
,08-16 14:23:48.696   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 14:23:48.698  4242  4242 I art     : System.exit called, status: 0
08-16 14:23:48.698  4242  4242 I AndroidRuntime: VM exiting with result code 0.
,08-16 14:23:48.702   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 14:23:48.729   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 14:23:48.733  1891  1891 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 14:23:48.734  4146  4146 D BluetoothMapAppObserver: onReceive
08-16 14:23:48.734  4146  4146 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 14:23:48.736  1891  4254 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 14:23:48.739  1853  2209 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 14:23:48.740   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:23:48.740  1891  4254 I Decoder : createOrResetDecoder
,08-16 14:23:48.744  3657  3657 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 14:23:48.769   872  2115 I ActivityManager: Start proc 4257:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 14:23:48.789  1969  1969 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 14:23:48.802  1512  1512 I ConfigService: onCreate
,08-16 14:23:48.808  4257  4257 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 14:23:48.817  1891  4254 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 14:23:48.832   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 14:23:48.836   872  1975 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3788 uid 10000
,08-16 14:23:48.837  1891  1891 I Keyboard.Facilitator: onFinishInput()
,08-16 14:23:48.853  1891  4254 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 14:23:48.861  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-16 14:23:48.861  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 14:23:48.862   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 14:23:48.862   872   884 E PackageManager: Failed to write settings, restoring backup
08-16 14:23:48.862   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 14:23:48.862   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 14:23:48.862   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 14:23:48.862   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 14:23:48.862   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 14:23:48.862   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:48.862   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:48.862   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:23:48.867   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-16 14:23:48.867   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 14:23:48.867   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:48.867   872   885 E DropBoxManagerService: 	... 13 more
,08-16 14:23:48.868  1991  2113 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 14:23:48.869  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 14:23:48.869  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 14:23:48.870  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 14:23:48.870  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 14:23:48.871  1891  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 14:23:48.871  1891  4254 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 14:23:48.871  1891  4254 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-16 14:23:48.871  1891  4254 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 14:23:48.871  1891  4254 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-16 14:23:48.871  1891  4254 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 14:23:48.880   872   883 I ActivityManager: Start proc 4274:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 14:23:48.881  1991  2113 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 14:23:48.881  1991  2113 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1991
08-16 14:23:48.881  1991  2113 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:48.881  1991  2113 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:23:48.883   872  1976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 14:23:48.883   872  4280 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:23:48.883   872  4280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:48.883   872  4280 E DropBoxManagerService: 	... 5 more
,08-16 14:23:48.888  1991  2113 I Process : Sending signal. PID: 1991 SIG: 9
,08-16 14:23:48.906  4257  4257 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 14:23:48.939   872  1989 I ActivityManager: Start proc 4288:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 14:23:48.979  4257  4287 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 14:23:48.994  4288  4288 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 14:23:49.012   872  1962 D GraphicsStats: Buffer count: 1
,08-16 14:23:49.012   872  1396 I WindowState: WIN DEATH: Window{202adb u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 14:23:49.018  1512  1512 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 14:23:49.019  1512  1512 D AndroidRuntime: Shutting down VM
08-16 14:23:49.019  1512  1512 E AndroidRuntime: FATAL EXCEPTION: main
08-16 14:23:49.019  1512  1512 E AndroidRuntime: Process: com.google.process.gapps, PID: 1512
08-16 14:23:49.019  1512  1512 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 14:23:49.019  1512  1512 E AndroidRuntime: 	... 8 more
,08-16 14:23:49.023   872  1611 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1991) has died
,08-16 14:23:49.024   872  1611 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 14:23:49.025   872  1611 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 14:23:49.044   872   885 I ActivityManager: Start proc 4305:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 14:23:49.047  1512  1512 I Process : Sending signal. PID: 1512 SIG: 9
08-16 14:23:49.048   872  4310 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:23:49.048   872  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:49.048   872  4310 E DropBoxManagerService: 	... 5 more
,08-16 14:23:49.078  4257  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.078  4257  4272 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:23:49.083  1691  4317 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-16 14:23:49.083  1691  4317 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@8f8e9a
,08-16 14:23:49.083   872  2115 I ActivityManager: Process com.google.process.gapps (pid 1512) early provider death
,08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.081  4257  4272 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:23:49.093   872  1314 D WifiService: Client connection lost with reason: 4
,08-16 14:23:49.095  4305  4305 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:49.095  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:23:49.095  4305  4305 D AndroidRuntime: Shutting down VM
,08-16 14:23:49.099   872  2115 I ActivityManager: Process com.google.process.gapps (pid 1512) has died
,08-16 14:23:49.100   872  2115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-16 14:23:49.100   872  2115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
08-16 14:23:49.100   872  2115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
08-16 14:23:49.100   872  2115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
,08-16 14:23:49.102   872  1396 W ActivityManager: Spurious death for ProcessRecord{7526493 0:com.google.process.gapps/u0a11}, curProc for 1512: null
,08-16 14:23:49.109  1691  1691 W RocketImpressions: ClearcutLogger connection suspended: 1
08-16 14:23:49.111  3001  3001 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
,08-16 14:23:49.119   872   883 I ActivityManager: Start proc 4319:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-16 14:23:49.120  4305  4305 E AndroidRuntime: FATAL EXCEPTION: main
08-16 14:23:49.120  4305  4305 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4305
08-16 14:23:49.120  4305  4305 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 14:23:49.120  4305  4305 E AndroidRuntime: 	... 10 more
,08-16 14:23:49.125   872  1396 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 14:23:49.126  4305  4305 I Process : Sending signal. PID: 4305 SIG: 9
,08-16 14:23:49.128   872  4326 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:23:49.128   872  4326 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:49.128   872  4326 E DropBoxManagerService: 	... 5 more
,08-16 14:23:49.137  4257  4272 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 14:23:49.147  4257  4287 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.147  4257  4287 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:23:49.147  4257  4287 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 14:23:49.147  4257  4287 E AndroidRuntime: Process: android.process.acore, PID: 4257
08-16 14:23:49.147  4257  4287 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
,08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.147  4257  4287 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:23:49.150   872  4334 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:49.150   872  4334 E DropBoxManagerService: 	... 5 more
08-16 14:23:49.151  4257  4287 I Process : Sending signal. PID: 4257 SIG: 9
,08-16 14:23:49.153  4319  4319 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-16 14:23:49.156  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-16 14:23:49.156  1691  1691 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-16 14:23:49.157  4319  4319 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-16 14:23:49.159  4319  4319 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450),
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:49.159  4319  4319 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:23:49.160  4319  4319 D AndroidRuntime: Shutting down VM
08-16 14:23:49.160  4319  4319 E AndroidRuntime: FATAL EXCEPTION: main
08-16 14:23:49.160  4319  4319 E AndroidRuntime: Process: com.google.process.gapps, PID: 4319
08-16 14:23:49.160  4319  4319 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.ope,nConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 14:23:49.160  4319  4319 E AndroidRuntime: 	... 10 more
,08-16 14:23:49.164   872  4335 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:23:49.164   872  4335 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:23:49.164   872  4335 E DropBoxManagerService: 	... 5 more
,08-16 14:23:49.164  4319  4319 I Process : Sending signal. PID: 4319 SIG: 9
,08-16 14:23:49.167   872  2019 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4305) has died
08-16 14:23:49.168   872  2019 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-16 14:23:49.162  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-16 14:23:49.174  1691  1691 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-16 14:23:49.180  1691  4337 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-16 14:23:49.184   872   885 I ActivityManager: Start proc 4338:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 14:23:49.185   279   279 E lowmemorykiller: Error writing /proc/4257/oom_score_adj; errno=22
08-16 14:23:49.185  2068  4336 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE

```
