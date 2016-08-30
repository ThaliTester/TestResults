#### Test 829120304df63d9_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 16:17:21.094  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:21.106  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:17:21.109  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:17:21.165  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 16:17:21.166  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:17:21.166  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:17:21.167  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 16:17:21.214  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 16:17:21.215  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 16:17:21.216  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 16:17:21.801  3823  3823 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 16:17:21.806  3823  3823 D AndroidRuntime: CheckJNI is OFF
08-30 16:17:21.849  3823  3823 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 16:17:21.899  3823  3823 I Radio-JNI: register_android_hardware_Radio DONE
08-30 16:17:21.921  3823  3823 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 16:17:21.926   875  1403 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 16:17:21.958  2039  2055 W SearchService: Abort, client detached.
08-30 16:17:21.967  2039  2344 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c66f877
08-30 16:17:21.967  2039  2039 I HotwordDetector: Closing mic
08-30 16:17:21.967  2039  2356 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 16:17:21.969  3823  3823 D AndroidRuntime: Shutting down VM
08-30 16:17:21.987   875  1972 I ActivityManager: Start proc 3833:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 16:17:22.029   377  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 16:17:22.029   377  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 16:17:22.038   377  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 16:17:22.039  2039  2355 I MicroRecognitionRnrImpl: Detection finished
08-30 16:17:22.040  2039  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 16:17:22.084  3833  3833 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 16:17:22.106  3833  3833 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 16:17:22.114  3833  3833 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9559-9561)
08-30 16:17:22.114  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:17:22.134  3833  3833 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f34f8c6}
08-30 16:17:22.134  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:17:22.135  3833  3833 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 16:17:22.141  3833  3833 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 16:17:22.143  3833  3833 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 16:17:22.172  3833  3833 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 16:17:22.183  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:17:22.183  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:17:22.183  3833  3833 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:17:22.183  3833  3833 I Adreno  : Build Date                       : 10/20/15
08-30 16:17:22.183  3833  3833 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:17:22.183  3833  3833 I Adreno  : Local Branch                     : M14
08-30 16:17:22.183  3833  3833 I Adreno  : Remote Branch                    : 
08-30 16:17:22.183  3833  3833 I Adreno  : Remote Branch                    : 
08-30 16:17:22.183  3833  3833 I Adreno  : Reconstruct Branch               : 
,08-30 16:17:22.244   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7622e3e:true
,08-30 16:17:22.279  3833  3833 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 16:17:22.294  3833  3833 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 16:17:22.358  3833  3871 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 16:17:22.370  3833  3858 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 16:17:22.443  3833  3871 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 16:17:22.501   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +531ms
08-30 16:17:22.505  1884  1884 I Keyboard.Facilitator: onFinishInput()
,08-30 16:17:22.564  3833  3833 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3833
,08-30 16:17:22.766  3833  3833 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 16:17:22.780   875  1971 I ActivityManager: Killing 2987:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 16:17:22.833   875  1971 I ActivityManager: Killing 3210:com.google.android.gm/u0a78 (adj 15): empty #18
,08-30 16:17:22.985  3833  3873 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1684014800
,08-30 16:17:23.000  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 16:17:23.000  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 16:17:23.000  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 16:17:23.000  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 16:17:23.000  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 16:17:23.000  3833  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab4e96a added. We now have 1 listener(s)
,08-30 16:17:23.008  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61,
08-30 16:17:23.009  3833  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:17:23.010  3833  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:17:23.010  3833  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 16:17:23.014  3833  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1907d1 added. We now have 1 listener(s)
,08-30 16:17:23.015  3833  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:17:23.019   875  1318 D WifiService: New client listening to asynchronous messages
,08-30 16:17:23.019  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:17:23.019  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 16:17:23.019  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 16:17:23.020  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 16:17:23.020  3833  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 16:17:23.022  3833  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:17:23.022  3833  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 16:17:23.027  3833  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:23.027  3833  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:17:23.027  3833  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 16:17:23.027  3833  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:17:23.028  3833  3873 I io.jxcore.node.LifeCycleMonitor: start: OK,
,08-30 16:17:23.093  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:23.095  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:23.098  3833  3833 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 16:17:23.965  3833  3884 W jxcore-log: Initializing JXcore engine
08-30 16:17:23.965  3833  3884 W jxcore-log: JXcore engine is ready
,08-30 16:17:23.999  3884  3884 W Thread-335: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 16:17:23.999  3884  3884 W Thread-335: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11795]" dev="sockfs" ino=11795 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 16:17:23.999  3884  3884 W Thread-335: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 16:17:23.999  3884  3884 W Thread-335: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26593]" dev="sockfs" ino=26593 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 16:17:24.030  3833  3884 W jxcore-log: Starting JXcore engine
,08-30 16:17:24.161  3833  3884 W jxcore-log: Platform android
08-30 16:17:24.161  3833  3884 W jxcore-log: 
08-30 16:17:24.161  3833  3884 W jxcore-log: Process ARCH arm
08-30 16:17:24.161  3833  3884 W jxcore-log: 
,08-30 16:17:24.516  3833  3884 I jxcore-log: JXcore Cordova bridge is ready!
08-30 16:17:24.516  3833  3884 I jxcore-log: 
,08-30 16:17:24.516  3833  3884 W jxcore-log: JXcore engine is started
,08-30 16:17:24.526  3833  3873 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 16:17:24.532  3833  3833 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 16:17:25.177   875  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 16:17:29.873  3621  3890 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 16:17:29.891  3621  3891 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 16:17:29.903  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:29.907  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:29.936  1511  2243 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 16:17:29.936  1511  2243 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:17:29.936  1511  2243 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:17:29.936  1511  2243 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:17:29.964  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:29.965  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:29.977  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:17:29.977  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:17:29.977  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:17:29.977  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:17:29.985  3621  3891 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 16:17:29.986  3621  3890 E BooksSync: Soft error
08-30 16:17:29.986  3621  3890 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:17:29.986  3621  3890 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 16:17:29.986  3621  3890 E BooksSync: Sync error
08-30 16:17:29.986  3621  3890 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:17:29.986  3621  3890 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:17:29.987  3621  3890 I BooksSync: Finished books sync
,08-30 16:17:29.991   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127276, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:17:38.405  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 16:17:38.405  3833  3884 I jxcore-log: 
,08-30 16:17:38.408  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 16:17:38.408  3833  3884 I jxcore-log: 
,08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:38.416  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:17:38.420  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:17:38.422  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 16:17:38.422  3833  3884 I jxcore-log: 
,08-30 16:17:38.424  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 16:17:38.424  3833  3884 I jxcore-log: 
,08-30 16:17:38.769  3833  3884 I jxcore-log: Running unit tests
08-30 16:17:38.769  3833  3884 I jxcore-log: 
,08-30 16:17:38.770  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:17:38.770  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aca2e51 added. We now have 2 listener(s)
08-30 16:17:38.771  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:17:38.771  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:17:38.771  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:17:38.771  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:17:38.771  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d896b6 added. We now have 2 listener(s)
08-30 16:17:38.772  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:17:38.772  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:17:38.774  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:38.778  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:17:38.780  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:38.780  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:17:38.781  3833  3884 D executeNativeTests: Running unit tests
,08-30 16:17:38.788  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:38.795  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:38.841  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:17:38.841  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 added. We now have 3 listener(s)
,08-30 16:17:38.842  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:17:38.842  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:17:38.842  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:17:38.842  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:17:38.842  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd added. We now have 3 listener(s)
,08-30 16:17:38.842  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:17:38.844  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:17:38.849  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:38.861  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:17:38.868  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:17:38.869  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:17:38.876  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:17:38.876  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:38.881  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 16:17:38.881  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:17:38.883  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:17:38.885  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:38.887  3833  3884 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 16:17:38.888  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 16:17:38.889  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:17:38.890  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:17:38.890  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:17:38.890  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:17:38.891  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:17:38.893  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:38.893  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:38.895  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:38.895  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:38.895  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:17:38.896  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:17:38.896  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 removed from the list
,08-30 16:17:38.896  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 16:17:38.897  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd removed from the list
08-30 16:17:38.897  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:38.897  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:38.898  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:38.899  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:38.901  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:38.901  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:38.901  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:38.901  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:38.903  3833  3884 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 16:17:38.904  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-30 16:17:38.904  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:38.904  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:38.904  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:38.905  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:38.905  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:38.905  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:38.905  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:38.905  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:38.905  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:38.905  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:38.905  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:38.905  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:38.906  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:38.907  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:17:38.908  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:38.908  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:38.908  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:38.914  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:17:38.915  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:17:38.916  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:17:38.917  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-30 16:17:38.917  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:17:38.917  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:17:38.917  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:17:38.917  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:17:38.917  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:17:38.917  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:38.917  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:38.917  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:38.917  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:38.917  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:38.917  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:38.917  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:38.918  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:38.918  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:38.918  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:38.918  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:38.918  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:38.918  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:38.918  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:38.920  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:38.920  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:38.920  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:38.920  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:17:38.921  3833  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:17:38.923  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:38.929  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:17:38.931  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:38.932  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:17:38.932  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:17:38.932  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:17:38.932  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:17:38.932  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:17:38.933  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:17:38.935  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:17:38.937  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:17:38.937  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:17:38.937  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:38.947  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:17:38.950  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:17:38.951  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:17:38.955  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 16:17:38.959  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 16:17:38.960  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 16:17:38.960  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:17:38.961  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:17:38.962  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:17:38.970  2670  2681 D BtGatt.GattService: registerClient() - UUID=1a47866d-89fb-4450-aaa4-f30b5823c383
,08-30 16:17:38.971  2670  2690 D BtGatt.GattService: onClientRegistered() - UUID=1a47866d-89fb-4450-aaa4-f30b5823c383, clientIf=5
,08-30 16:17:38.974  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 16:17:38.975  2670  2776 D BtGatt.GattService: start scan with filters
,08-30 16:17:38.980  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:17:38.980  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:17:38.981  2670  2695 D BtGatt.ScanManager: handling starting scan
08-30 16:17:38.981  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:17:38.981  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:17:38.983  2670  2695 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:17:38.986  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:17:38.986  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:17:38.987  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:17:38.990  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:17:38.993  2670  2690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:17:38.993  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:38.994  2670  2695 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:17:38.996  3833  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:17:39.005  2670  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 16:17:39.005  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:39.005  2670  2695 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:17:39.006  2670  2695 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-30 16:17:39.025  2670  2690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:17:39.025  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:39.035  2670  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 16:17:39.035  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:39.488  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 16:17:39.489  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:17:39.490  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 16:17:40.131   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 16:17:40.542  2670  2670 D BtGatt.ScanManager: awakened up at time 137989
,08-30 16:17:40.544  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:40.593  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 16:17:40.593  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:40.594  2670  2690 D BtGatt.GattService: current time is 138041331620
,08-30 16:17:40.595  2670  2690 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 16:17:40.601  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 16:17:40.603  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 16:17:40.604  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 16:17:40.605  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 16:17:40.606  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 16:17:40.607  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 16:17:42.094  2670  2670 D BtGatt.ScanManager: awakened up at time 139542
,08-30 16:17:42.097  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:42.142  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 16:17:42.142  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:42.295  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:42.306  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:42.311  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:17:42.356  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:17:42.356  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 16:17:42.357  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:17:42.357  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:17:42.395  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:17:42.396  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:17:42.399  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 16:17:43.627  2670  2670 D BtGatt.ScanManager: awakened up at time 141074
,08-30 16:17:43.629  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:43.659  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-30 16:17:43.659  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:43.659  2670  2690 D BtGatt.GattService: current time is 141106854504
,08-30 16:17:43.659  2670  2690 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 16:17:43.660  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 16:17:43.660  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 16:17:43.660  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 16:17:44.005  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:17:44.006  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:44.007  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:17:44.007  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:44.008  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 16:17:44.008  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:17:44.008  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:17:44.009  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:17:44.009  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:17:44.011  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:17:44.012  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:17:44.014  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:17:44.016  2670  2800 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:17:44.020  2670  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:17:44.021  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:17:44.021  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:17:44.022  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:17:44.022  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:17:44.023  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:17:44.026  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:17:44.028  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 16:17:44.028  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:17:44.029  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:17:44.031  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:17:44.035  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:17:44.035  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:17:44.036  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:17:44.037  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:17:44.037  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:44.037  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:17:44.038  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:44.038  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:44.038  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:44.038  2670  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:17:44.039  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:44.039  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:17:44.039  2670  2695 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:17:44.040  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:44.047  2670  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:17:44.047  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:44.048  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:44.080  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-30 16:17:44.080  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:44.081  2670  2690 D BtGatt.GattService: current time is 141528340983
08-30 16:17:44.081  2670  2690 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -93, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 16:17:44.082  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 16:17:44.083  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 16:17:44.083  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 16:17:44.084  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 16:17:44.536  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:17:46.185   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 16:17:49.041  3833  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 16:17:49.047  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:49.061  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:17:49.068  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:17:49.069  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:17:49.071  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:17:49.071  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 16:17:49.072  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:17:49.072  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:17:49.072  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:17:49.077  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:49.083  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:17:49.084  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:17:49.085  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:49.096  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:17:49.098  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:17:49.099  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:17:49.108  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:17:49.109  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:17:49.109  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:17:49.111  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:17:49.117  2670  2681 D BtGatt.GattService: registerClient() - UUID=c509f51a-8410-4fa5-8f10-d9396dec41f9
,08-30 16:17:49.118  2670  2690 D BtGatt.GattService: onClientRegistered() - UUID=c509f51a-8410-4fa5-8f10-d9396dec41f9, clientIf=5
,08-30 16:17:49.120  3833  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:17:49.121  2670  2800 D BtGatt.GattService: start scan with filters
,08-30 16:17:49.130  2670  2695 D BtGatt.ScanManager: handling starting scan
,08-30 16:17:49.130  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 16:17:49.131  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:17:49.131  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:17:49.131  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:17:49.143  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:17:49.144  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:17:49.145  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:17:49.149  2670  2690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:17:49.150  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:49.150  2670  2695 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:17:49.155  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:17:49.164  3833  3884 I io.jxcore.node.ConnectionHelper: start: OK,
,08-30 16:17:49.165  2670  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:17:49.166  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:49.166  2670  2695 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 16:17:49.166  2670  2695 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:17:49.169  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:49.169  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:17:49.170  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:49.170  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:17:49.170  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:49.170  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 16:17:49.170  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:17:49.170  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:17:49.170  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:17:49.170  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:17:49.170  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:17:49.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:17:49.171  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:17:49.172  2670  2681 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:17:49.173  2670  2800 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:17:49.173  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:17:49.173  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 16:17:49.173  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:17:49.173  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 16:17:49.173  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:17:49.175  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:17:49.178  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:17:49.178  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:17:49.178  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:17:49.179  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:17:49.180  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:17:49.180  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:17:49.180  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:17:49.181  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:49.181  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:49.181  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:17:49.181  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:49.181  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:49.181  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:49.181  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:49.181  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:49.182  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:49.182  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:49.183  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:49.183  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:17:49.183  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:49.183  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:49.184  3833  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:17:49.189  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:17:49.195  2670  2690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:17:49.195  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:17:49.198  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:17:49.200  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:17:49.200  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:17:49.202  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:17:49.203  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:17:49.203  2670  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:17:49.203  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:49.202  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:17:49.205  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:17:49.205  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:17:49.205  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:17:49.205  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:17:49.213  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:17:49.213  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:17:49.214  2670  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:17:49.214  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:49.214  2670  2695 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:17:49.221  2670  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 16:17:49.221  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:49.221  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:49.223  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:17:49.224  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:17:49.224  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:17:49.227  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 16:17:49.227  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:49.228  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:17:49.228  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:17:49.228  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:17:49.229  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:17:49.231  2670  2682 D BtGatt.GattService: registerClient() - UUID=ba03fa3b-228b-4ead-84f7-ba12bc2e6716
08-30 16:17:49.231  2670  2690 D BtGatt.GattService: onClientRegistered() - UUID=ba03fa3b-228b-4ead-84f7-ba12bc2e6716, clientIf=5
,08-30 16:17:49.231  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:17:49.232  2670  2800 D BtGatt.GattService: start scan with filters
,08-30 16:17:49.235  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:17:49.235  2670  2695 D BtGatt.ScanManager: handling starting scan
,08-30 16:17:49.235  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:17:49.235  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-30 16:17:49.235  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:17:49.238  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:17:49.238  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:17:49.238  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:17:49.239  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:17:49.241  2670  2690 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:17:49.242  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:49.242  2670  2695 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
08-30 16:17:49.242  3833  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:17:49.247  2670  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 16:17:49.248  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:49.248  2670  2695 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:17:49.248  2670  2695 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:17:49.258  2670  2690 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:17:49.258  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:49.263  2670  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 16:17:49.263  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:49.739  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 16:17:49.740  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:17:49.740  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 16:17:50.771  2670  2670 D BtGatt.ScanManager: awakened up at time 148218
,08-30 16:17:50.773  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:50.817  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 16:17:50.817  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:50.818  2670  2690 D BtGatt.GattService: current time is 148265301141
,08-30 16:17:50.818  2670  2690 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -91, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 16:17:50.818  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 16:17:50.819  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 16:17:50.819  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 16:17:50.819  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 16:17:50.819  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 16:17:50.822  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 16:17:52.321  2670  2670 D BtGatt.ScanManager: awakened up at time 149768
,08-30 16:17:52.323  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:52.337  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 16:17:52.337  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:52.798   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 16:17:52.806  1884  1884 I Keyboard.Facilitator: onFinishInput(),
,08-30 16:17:52.815   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:17:52.815   875   895 I Adreno  : Build Date                       : 10/20/15
08-30 16:17:52.815   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:17:52.815   875   895 I Adreno  : Local Branch                     : M14
08-30 16:17:52.815   875   895 I Adreno  : Remote Branch                    : 
08-30 16:17:52.815   875   895 I Adreno  : Remote Branch                    : 
08-30 16:17:52.815   875   895 I Adreno  : Reconstruct Branch               : 
,08-30 16:17:52.865   280   771 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (323 us)
,08-30 16:17:53.526  3833  3833 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 16:17:53.526  3833  3833 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 16:17:53.581   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 16:17:53.582  3833  3833 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7344d4c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8c9a816, 16908290=android.view.AbsSavedState$1@8c9a816}, android:focusedViewId=100}]}]
,08-30 16:17:53.582  3833  3833 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-30 16:17:53.583  3833  3833 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 16:17:53.583  3833  3833 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-30 16:17:53.585   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 16:17:53.590   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-30 16:17:53.591   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-30 16:17:53.591   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 16:17:53.823   280   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 16:17:53.826   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 16:17:53.827   875  1343 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
08-30 16:17:53.838   875   895 I DreamManagerService: Entering dreamland.
08-30 16:17:53.841   875   895 I PowerManagerService: Dozing...
08-30 16:17:53.842  2670  2670 D BtGatt.ScanManager: awakened up at time 151289
08-30 16:17:53.842   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
08-30 16:17:53.846  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:53.870  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-30 16:17:53.870  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:53.870  2670  2690 D BtGatt.GattService: current time is 151317615290
,08-30 16:17:53.870  2670  2690 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -93, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -52, 11, 57, -70, 107, -17, 1, 0, -111, 19, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -89, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 16:17:53.870  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 16:17:53.871  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
,08-30 16:17:53.871  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 16:17:53.871  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 16:17:53.871  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 16:17:53.872  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 16:17:53.872  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 16:17:53.898   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 16:17:53.898   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 16:17:53.911   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:17:53.914  1940  3901 D NfcService: Discovery configuration equal, not updating.
,08-30 16:17:53.928   875  1317 E native  : do suspend false
,08-30 16:17:53.945   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 16:17:53.961   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:17:53.969   875  1317 E native  : do suspend true
,08-30 16:17:54.040   377  1289 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 16:17:54.041   377  1289 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 16:17:54.243  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:54.243  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:54.244  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:17:54.244  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:54.244  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 16:17:54.245  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 16:17:54.245  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:17:54.245  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 16:17:54.246  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 16:17:54.246  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 16:17:54.246  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:17:54.249  3833  3884 D BluetoothAdapter: STATE_ON
08-30 16:17:54.251  2670  2776 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:17:54.253  2670  2682 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:17:54.254  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:17:54.255  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:17:54.255  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:17:54.255  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:17:54.256  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:17:54.260  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:17:54.261  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:17:54.261  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:17:54.261  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:17:54.263  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 16:17:54.266  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:17:54.267  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:17:54.267  2670  2690 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:17:54.267  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:54.267  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:17:54.268  2670  2695 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:17:54.278  2670  2690 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 16:17:54.278  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:17:54.278  2670  2695 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:17:54.301  2670  2690 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-30 16:17:54.302  2670  2690 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:17:54.302  2670  2690 D BtGatt.GattService: current time is 151749390334
,08-30 16:17:54.302  2670  2690 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 16:17:54.302  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 16:17:54.303  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 16:17:54.303  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 16:17:54.303  2670  2690 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 16:17:54.416   875  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 16:17:54.769  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:17:54.770  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:54.770  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 16:17:59.033  2022  2653 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 16:17:59.267  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:17:59.268  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:59.268  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:17:59.269  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.269  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.269  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:17:59.270  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.270  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.270  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.271  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.271  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.274  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.274  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.278  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:17:59.279  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:17:59.279  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.279  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:17:59.281  3833  3884 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 16:17:59.285  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:17:59.285  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:59.285  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.286  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:17:59.286  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.287  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.287  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list,
08-30 16:17:59.287  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.288  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.288  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:17:59.288  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.288  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.288  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.289  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.290  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:17:59.290  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.290  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.290  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:17:59.291  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:17:59.292  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:17:59.292  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:59.292  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:17:59.292  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.292  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:59.292  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.292  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
,08-30 16:17:59.292  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.292  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:17:59.292  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.293  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:59.293  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.293  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.293  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.295  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.295  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:17:59.295  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.295  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:17:59.296  3833  3884 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-30 16:17:59.296  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.296  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:59.296  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.296  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:17:59.296  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.296  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.296  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.297  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.297  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.297  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:17:59.297  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:59.297  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.297  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:59.297  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.299  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.299  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.299  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.299  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.300  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 16:17:59.300  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.300  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:59.300  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.300  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:17:59.300  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.300  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.300  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.301  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.301  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.301  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:17:59.301  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.301  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.301  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.301  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:17:59.303  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.303  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.303  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 16:17:59.303  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.304  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:17:59.304  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:17:59.304  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:17:59.304  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:17:59.305  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:17:59.305  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:17:59.305  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:17:59.305  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:17:59.305  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:17:59.305  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.305  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:59.305  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.305  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.305  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.305  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.306  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.306  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.306  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.306  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.306  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:17:59.306  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.306  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.306  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.308  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:17:59.308  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.309  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:17:59.309  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.310  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 16:17:59.310  3833  3884 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:17:59.310  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 16:17:59.313  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:17:59.313  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 16:17:59.313  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:17:59.314  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:17:59.315  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:17:59.316  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:17:59.316  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:17:59.316  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:17:59.316  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-30 16:17:59.317  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 16:17:59.317  3833  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:17:59.317  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 16:17:59.318  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:17:59.318  3833  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:17:59.318  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 16:17:59.318  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:17:59.318  3833  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 16:17:59.318  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 16:17:59.321  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 16:17:59.322  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 16:17:59.323  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 16:17:59.323  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 16:17:59.323  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 16:17:59.324  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 16:17:59.324  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:17:59.324  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 16:17:59.325  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.325  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:17:59.325  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.326  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.326  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.326  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.326  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 16:17:59.327  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.327  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.327  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.327  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.327  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.327  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.327  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.328  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.329  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.330  3833  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 399)
08-30 16:17:59.330  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.331  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.331  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.331  3833  3884 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-30 16:17:59.332  3833  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 399
08-30 16:17:59.333  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.333  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:59.333  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.333  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.333  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.333  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.333  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.333  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.333  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.333  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.334  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.334  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.334  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.334  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.335  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.335  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.335  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.336  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.336  3833  3906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:17:59.336  3833  3884 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 16:17:59.338  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.339  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:59.339  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.339  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.339  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.340  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.340  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.340  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.340  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.340  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.340  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.340  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.340  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.340  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.343  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.343  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.343  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.345  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.350  3833  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 16:17:59.350  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 16:17:59.350  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:17:59.350  3833  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 16:17:59.350  3833  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:17:59.350  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 16:17:59.350  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:17:59.350  3833  3884 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 16:17:59.350  3833  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:17:59.351  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:17:59.351  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:17:59.351  3833  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 16:17:59.351  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:17:59.351  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:17:59.351  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:17:59.351  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.351  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.351  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.351  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.351  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.352  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.352  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.352  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.352  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.352  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.352  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.354  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:17:59.354  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:17:59.354  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.354  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.355  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:17:59.355  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.355  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:17:59.355  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:17:59.355  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:17:59.355  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:17:59.355  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:17:59.355  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:17:59.355  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:00.182  3646  3910 V KeepSync: Connecting to GoogleApiClient
,08-30 16:18:00.183   875   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 16:18:00.225  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:00.227  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:00.277  1511  2243 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 16:18:00.278  1511  2243 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 16:18:00.278  1511  2243 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:18:00.278  1511  2243 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:00.299  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:18:00.299  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:18:00.299  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:18:00.299  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:00.305  1737  3911 V BaseAuthAsyncOperation: access token request failed
,08-30 16:18:00.306  3646  3910 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 16:18:00.324  3570  3909 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 16:18:00.324  3570  3909 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at blb.a(PG:3937)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at czp.a(PG:18188)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:18:00.324  3570  3909 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	... 12 more
08-30 16:18:00.324  3570  3909 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at fal.a(PG:38)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:18:00.324  3570  3909 E HttpOperation: 	... 14 more
,08-30 16:18:00.396  1511  2243 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:18:00.396  1511  2243 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:18:00.396  1511  2243 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:18:00.396  1511  2243 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 16:18:00.397  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 16:18:00.397  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 16:18:00.397  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:18:00.398  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:00.416  3570  3909 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 16:18:00.416  3570  3909 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at hec.a(PG:42)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at hee.a(PG:102)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at czr.a(PG:65)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at kka.a(PG:108)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at czp.a(PG:19176)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:18:00.416  3570  3909 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	... 15 more
08-30 16:18:00.416  3570  3909 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at fal.a(PG:38)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:18:00.416  3570  3909 E HttpOperation: 	... 17 more
08-30 16:18:00.417  3570  3909 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 16:18:00.417  3570  3909 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at hec.a(PG:42)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at hee.a(PG:102)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at czr.a(PG:65)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at kka.a(PG:108)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	... 15 more
08-30 16:18:00.417  3570  3909 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at fal.a(PG:38)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 16:18:00.417  3570  3909 E ExperimentLoader: 	... 17 more
,08-30 16:18:00.425  3646  3910 E KeepSync: IOException
08-30 16:18:00.425  3646  3910 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 16:18:00.425  3646  3910 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:18:00.425  3646  3910 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 16:18:00.425  3646  3910 E KeepSync: 	... 10 more
,08-30 16:18:00.426  3646  3910 W KeepSync: Sync result 2
,08-30 16:18:00.435   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132362, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:18:00.574   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 129437, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:18:02.526  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:02.715  1511  3914 I VacuumService: Vacuum at: now=1472566682715 tag=VacuumService
,08-30 16:18:02.718  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:02.793  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:18:02.793  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 16:18:02.794  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:18:02.794  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:02.807  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:18:02.808  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 16:18:02.808  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 16:18:02.891  1511  3915 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 16:18:02.894  1511  3915 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 16:18:02.924  1511  3915 W Uploader:  no longer exists, so no auth token.
,08-30 16:18:04.356  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:04.357  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:18:04.357  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:18:04.357  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.358  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.358  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:18:04.358  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:18:04.359  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:18:04.359  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:18:04.360  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:18:04.360  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:18:04.360  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.360  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:18:04.361  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:04.361  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:18:04.361  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:04.362  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:18:04.362  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:04.362  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.363  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.366  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:18:04.366  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:18:04.367  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.367  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:18:04.372  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 16:18:04.373  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:18:04.374  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 16:18:04.375  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 16:18:04.375  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 16:18:04.376  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 16:18:04.376  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 16:18:04.376  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 16:18:04.376  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:18:04.376  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 16:18:04.376  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 16:18:04.377  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 16:18:04.377  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:04.377  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 16:18:04.377  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:18:04.377  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:04.377  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:18:04.377  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:18:04.377  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 16:18:04.377  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:18:04.377  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.377  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 16:18:04.379  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:18:04.379  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:18:04.380  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:18:04.380  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:18:04.380  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:18:04.380  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:18:04.380  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:18:04.380  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:18:04.380  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:18:04.380  3833  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 16:18:04.380  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.381  3833  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:18:04.381  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.381  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:18:04.381  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.381  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:18:04.381  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:04.381  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.381  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.381  3833  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
08-30 16:18:04.381  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.381  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.383  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:18:04.383  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:18:04.383  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.383  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:18:04.384  3833  3884 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 16:18:04.385  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:18:04.385  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 16:18:04.387  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:18:04.387  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:18:04.387  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:18:04.387  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:18:04.388  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:18:04.388  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:18:04.388  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.388  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.388  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:18:04.388  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.388  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:18:04.388  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:18:04.388  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.389  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.389  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.389  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.390  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:18:04.390  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:18:04.390  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.391  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:18:04.396  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:18:04.396  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:18:04.396  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:18:04.396  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:18:04.396  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.396  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.397  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
08-30 16:18:04.397  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.397  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:18:04.397  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:04.397  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.397  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.397  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.397  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.399  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:18:04.399  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:18:04.399  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.399  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
,08-30 16:18:04.400  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:18:04.400  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:18:04.400  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:18:04.401  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:18:04.401  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.401  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.401  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1bdd54 not in the list
,08-30 16:18:04.401  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:04.401  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:18:04.401  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:18:04.401  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.401  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:04.401  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:04.401  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:04.403  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:18:04.403  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:18:04.403  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:04.403  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4504fd not in the list
08-30 16:18:04.404  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-30 16:18:04.404  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:18:04.404  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 16:18:04.404  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:18:04.405  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-30 16:18:04.405  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 16:18:04.408  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 16:18:04.408  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 16:18:04.409  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 16:18:04.409  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:18:04.409  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 16:18:04.409  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:18:04.409  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-30 16:18:04.409  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 16:18:04.410  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 16:18:04.410  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed,
08-30 16:18:04.411  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 16:18:04.411  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 16:18:04.411  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 16:18:04.411  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 16:18:04.412  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:18:04.412  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79b4384 added. We now have 3 listener(s)
08-30 16:18:04.412  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:18:04.415  3833  3884 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 16:18:04.415   875  3155 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,08-30 16:18:04.415   875  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:18:04.477  2670  2768 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 16:18:04.478  2670  2773 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-30 16:18:04.480  3833  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 399)
,08-30 16:18:04.880  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:18:05.192   875  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 16:18:06.430  1511  3915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-30 16:18:06.431  1511  3915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 16:18:06.431  1511  3915 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:18:06.431  1511  3915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:06.447  1511  3915 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 16:18:06.447  1511  3915 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 16:18:06.447  1511  3915 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 16:18:06.633  1511  3915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 16:18:06.633  1511  3915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 16:18:06.633  1511  3915 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:18:06.633  1511  3915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:06.663  1511  3915 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 16:18:06.663  1511  3915 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 16:18:06.663  1511  3915 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 16:18:07.448  1511  3915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-30 16:18:07.449  1511  3915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-30 16:18:07.449  1511  3915 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:18:07.449  1511  3915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:07.473  1511  3915 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 16:18:07.473  1511  3915 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-30 16:18:07.473  1511  3915 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-30 16:18:07.963   875  1858 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:18:09.424  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:18:09.425  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c6276d added. We now have 4 listener(s)
08-30 16:18:09.425  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:18:09.443  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:09.443  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c6276d removed from the list
08-30 16:18:09.444  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:09.444  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:18:09.444  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:09.447  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:18:09.447  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab02fa2 added. We now have 4 listener(s)
08-30 16:18:09.447  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:18:09.454  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:09.455  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab02fa2 removed from the list
,08-30 16:18:09.455  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:09.455  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:09.456  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:09.459  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:18:09.459  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d3d433 added. We now have 4 listener(s)
08-30 16:18:09.460  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:18:09.466   875  1403 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,08-30 16:18:09.467   875  1403 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:18:09.484  2670  2686 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 16:18:09.485  2670  2686 D BluetoothAdapterProperties: Setting state to 13
,08-30 16:18:09.485  2670  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 16:18:09.487  2670  2686 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 16:18:09.489  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:18:09.490  2670  2686 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:18:09.493  2670  2670 D BluetoothMapService: onReceive
08-30 16:18:09.493  2670  2670 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:18:09.494  2670  2670 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:18:09.495  2670  2670 D BluetoothMapService: MAP Service closeService in
08-30 16:18:09.495  2670  2670 D BluetoothMapMasInstance0: MAP Service shutdown
,08-30 16:18:09.495  2670  2670 D ObexServerSockets0: shutdown(block = true)
08-30 16:18:09.497  2670  2802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 16:18:09.498  2670  2670 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:18:09.498  2670  2803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 16:18:09.499  2670  2773 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 16:18:09.499  2670  2670 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:18:09.500  2670  2670 I BtOppRfcommListener: stopping Accept Thread
,08-30 16:18:09.500  2670  3429 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:18:09.501  2670  3429 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:18:09.501  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:09.501  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:18:09.503  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.503  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:09.503  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:18:09.506  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.509  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.512  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:09.512  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:18:09.513  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.513  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:09.515  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 16:18:09.517  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:09.517  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:18:09.518  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.518  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:09.519   875  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 16:18:09.520   875  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 16:18:09.520   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:18:09.520   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:09.521  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:09.529   875   888 I ActivityManager: Start proc 3929:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 16:18:09.530  2670  2690 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:18:09.530  2670  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 16:18:09.531   875  1317 E native  : do suspend true
,08-30 16:18:09.533  2670  2670 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:18:09.535  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.535  1374  1392 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:09.536  1374  1374 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:18:09.536   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:09.536   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:09.536   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 16:18:09.536  1955  1968 D BluetoothHeadset: Proxy object disconnected
08-30 16:18:09.537  2670  2670 D A2dpService: Received stop request...Stopping profile...
,08-30 16:18:09.537  2670  2780 D A2dpStateMachine: Exit Disconnected: -1
,08-30 16:18:09.537  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:09.539  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.540   875   875 D BluetoothA2dp: Proxy object disconnected
08-30 16:18:09.540  1374  1374 D BluetoothA2dp: Proxy object disconnected
,08-30 16:18:09.541  2670  2670 D HidService: Received stop request...Stopping profile...
08-30 16:18:09.541  2670  2670 D HidService: Stopping Bluetooth HidService
08-30 16:18:09.542  1374  1374 D BluetoothInputDevice: Proxy object disconnected
08-30 16:18:09.543  1374  1374 D HidProfile: Bluetooth service disconnected
08-30 16:18:09.543  2670  2670 D HealthService: Received stop request...Stopping profile...
08-30 16:18:09.544  2670  2670 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:18:09.544  2670  2670 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:09.544  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:09.544  2670  2670 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:09.544   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:18:09.545   875  1860 D DhcpClient: Clearing IP address
08-30 16:18:09.546  2670  2670 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:18:09.546  2670  2670 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 16:18:09.547  2670  2768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:09.547  2670  2768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:09.547  2670  2768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 16:18:09.547  2670  2690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 16:18:09.547  2670  2690 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 16:18:09.547  2670  2670 D PanService: Received stop request...Stopping profile...
,08-30 16:18:09.547   373   873 D CommandListener: Setting iface cfg
08-30 16:18:09.549  2670  2670 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:18:09.549  2670  2670 D BluetoothMapService: stop()
,08-30 16:18:09.549  2670  2670 D BluetoothMapAppObserver: deinitObservers()
08-30 16:18:09.549  2670  2670 D BluetoothMapAppObserver: removeReceiver()
08-30 16:18:09.550  1374  1374 D BluetoothMap: Proxy object disconnected
08-30 16:18:09.550  1374  1374 D MapProfile: Bluetooth service disconnected
08-30 16:18:09.551  2670  2670 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:18:09.551  2670  2670 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:09.551  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:09.551  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:18:09.551  2670  2670 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:18:09.551  1374  1374 D PanProfile: Bluetooth service disconnected
08-30 16:18:09.552  2670  2768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:09.552  2670  2768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:09.553  2670  2768 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:18:09.553  2670  2768 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:18:09.553  2670  2768 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:18:09.553  2670  2768 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:18:09.553  2670  2690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 16:18:09.553  2670  2670 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:09.553  2670  2670 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:09.553  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:09.553  2670  2670 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:09.553  2670  2670 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:18:09.553  2670  2670 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:18:09.553  2670  2690 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:18:09.554  2670  2670 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:09.554  2670  2670 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:09.554   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:18:09.554   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 16:18:09.554   875  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-30 16:18:09.555   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:18:09.555   875  1317 E native  : do suspend true
08-30 16:18:09.554  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:09.557   396   396 E Parcel  : Reading a NULL string not supported here.
08-30 16:18:09.555  2670  2670 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:09.560  1511  2453 V NativeCrypto: Read error: ssl=0x9b028a00: I/O error during system call, Connection timed out
08-30 16:18:09.561  2670  2670 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 16:18:09.561  2670  2690 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 16:18:09.562   875  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 16:18:09.563  1511  2453 V NativeCrypto: SSL shutdown failed: ssl=0x9b028a00: I/O error during system call, Broken pipe
08-30 16:18:09.567  2670  2670 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:18:09.568  2670  2670 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:09.568  2670  2670 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:09.568  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:09.568  2670  2670 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:09.568  2670  2670 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:18:09.569  2670  2670 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:18:09.570  2670  2670 D BluetoothMapService: MAP Service closeService in
08-30 16:18:09.570  2670  2670 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:09.570  2670  2670 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:09.570  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:09.570  2670  2670 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:09.570  2670  2670 D BluetoothMapService: cleanup()
08-30 16:18:09.571  2670  2670 D BluetoothMapService: MAP Service closeService in
08-30 16:18:09.571  2670  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 16:18:09.571  2670  2686 D BluetoothAdapterProperties: Setting state to 15
08-30 16:18:09.571  2670  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 16:18:09.571  1374  2073 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:18:09.572  2670  2686 I BluetoothAdapterState: Entering BleOnState
08-30 16:18:09.573   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:18:09.573   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:09.574   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:09.574   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:18:09.575  1374  1386 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:18:09.576   875  1866 D DhcpClient: Receive thread stopped
08-30 16:18:09.577  1955  2269 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:09.579  1374  1392 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:18:09.580  1374  2073 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:18:09.580  1374  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:18:09.581  1374  1392 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:18:09.581  2670  2686 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 16:18:09.581  2670  2686 D BluetoothAdapterProperties: Setting state to 16
08-30 16:18:09.581  2670  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 16:18:09.583  2670  2686 D BluetoothAdapterProperties: onBleDisable
08-30 16:18:09.583  2670  2686 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:18:09.583  2670  2687 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 16:18:09.583  2670  2690 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:18:09.584  2670  2768 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 16:18:09.584  2670  2768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:09.584  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:09.584  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:09.584  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.585  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:09.586  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:09.587  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:09.587  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:09.587  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:09.588  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:09.589  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:09.589  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.589  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:09.590  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.591  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.592  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.600   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:09.607  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 16:18:09.616  3929  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:18:09.623  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:18:09.626   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:09.627   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:18:09.627   875  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 16:18:09.627   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:09.633   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@86ac32e:true
,08-30 16:18:09.635   875  3155 I ActivityManager: Start proc 3945:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 16:18:09.639   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:18:09.640  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:09.641  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:09.643  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:09.643   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 16:18:09.649  3417  3417 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ab4e96a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-30 16:18:09.662   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 16:18:09.664  2022  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:18:09.667  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:09.667  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:09.668  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:09.668  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:09.669   875  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:18:09.670  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:09.670  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:09.671  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:09.671  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:09.672  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:09.672  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:09.673  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:09.673  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:09.687  3945  3945 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 16:18:09.694  3929  3929 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 16:18:09.695  3929  3929 D BluetoothMap: Create BluetoothMap proxy object
,08-30 16:18:09.700  3929  3929 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 16:18:09.707   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-30 16:18:09.715  3929  3929 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:18:09.720   875  1972 I ActivityManager: Killing 3417:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 16:18:09.784  2670  2690 I bt_hci  : shut_down
,08-30 16:18:09.797  2670  2696 D bt_hwcfg: hw_epilog_process
,08-30 16:18:09.797  2670  2696 I bt_vendor: low_power_mode_cb
,08-30 16:18:09.816  2670  2696 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 16:18:09.817  2670  2696 I bt_vendor: epilog_cb
,08-30 16:18:09.817  2670  2696 I bt_hci  : epilog_finished_callback
08-30 16:18:09.825  2670  2690 I bt_hci_h4: hal_close
,08-30 16:18:09.826  2670  2690 I bt_userial_vendor: device fd = 51 close
,08-30 16:18:09.860  3945  3945 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.860  3945  3945 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.860  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.861  3945  3945 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.861  3945  3945 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.861  3945  3945 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.861  3945  3945 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.861  3945  3945 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.861  3945  3945 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:18:09.861  3945  3945 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:18:09.874  3929  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:18:09.880  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:18:09.893  3929  3929 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:18:09.902   875  1403 I ActivityManager: Killing 3585:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 16:18:09.980  2670  2687 D bt_stack_manager: event_shut_down_stack finished.
,08-30 16:18:09.980  2670  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 16:18:09.982  2670  2686 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 16:18:09.982  2670  2670 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:18:09.983  2670  2670 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 16:18:09.983  2670  2670 D BtGatt.GattService: stop()
,08-30 16:18:09.983  2670  2670 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:18:09.984  2670  2670 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:09.984  2670  2670 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:09.984  2670  2670 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:09.984  2670  2670 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 16:18:09.984  2670  2686 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 16:18:09.984  2670  2686 D BluetoothAdapterProperties: Setting state to 10
08-30 16:18:09.984  2670  2686 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 16:18:09.985  2670  2686 I BluetoothAdapterState: Entering OffState
08-30 16:18:09.985  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:18:09.987   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-30 16:18:09.991  1737  1737 D SystemUpdateService: onCreate
,08-30 16:18:09.999  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:18:10.014  2670  2670 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 16:18:10.014  2670  2670 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 16:18:10.015  2670  2670 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 16:18:10.015  2670  2687 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 16:18:10.024  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 16:18:10.027  1737  2426 I iu.UploadsManager: num queued entries: 0
,08-30 16:18:10.027  1737  2426 I iu.UploadsManager: num updated entries: 0
,08-30 16:18:10.029  2670  2687 D bt_stack_manager: event_clean_up_stack finished.
,08-30 16:18:10.034  1737  3981 I SystemUpdateService: active receiver: enabled
,08-30 16:18:10.035  2670  2670 I art     : System.exit called, status: 0
,08-30 16:18:10.036  2670  2670 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 16:18:10.047  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:18:10.049  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:18:10.069  1737  3981 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:18:10.073   875  1971 I ActivityManager: Start proc 3984:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver,
,08-30 16:18:10.083  1737  2426 I iu.SyncManager: NEXT; no task
,08-30 16:18:10.086  1737  3981 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 16:18:10.086  1737  3981 I SystemUpdateService: now status is 0 (complete)
08-30 16:18:10.086  1737  3981 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 16:18:10.086  1737  3981 I SystemUpdateService: file has been verified
,08-30 16:18:10.087  1737  3981 I SystemUpdateService: OTA package size = 12249756
,08-30 16:18:10.119   875  1883 I ActivityManager: Process com.android.bluetooth (pid 2670) has died
,08-30 16:18:10.131  3984  3984 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 16:18:10.134  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:10.137  1737  3981 I SystemUpdateService: showing system update notification
,08-30 16:18:10.145  3984  3984 D SprintDMHelper: simOperator: 
,08-30 16:18:10.145  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:18:10.162   875  1969 I ActivityManager: Start proc 3996:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 16:18:10.191  1737  1737 D SystemUpdateService: onDestroy
,08-30 16:18:10.193   875   886 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 16:18:10.237  3945  3973 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 16:18:10.308   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7c2079a:true
,08-30 16:18:10.364  2471  4012 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 16:18:10.365   875  1971 I ActivityManager: Start proc 4013:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 16:18:10.428  4013  4013 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 16:18:10.479  4013  4013 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 16:18:10.479  4013  4013 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 16:18:10.479  4013  4013 I GAv4    :   adb logcat -s GAv4
,08-30 16:18:10.496  4013  4013 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:18:10.502  4013  4013 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:18:10.512  4013  4030 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:18:10.643  4013  4013 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 16:18:10.684  4013  4013 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 16:18:10.694  4013  4013 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8136-8141)
,08-30 16:18:10.694  4013  4013 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 16:18:10.707  4013  4013 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {592811a}
,08-30 16:18:10.708  4013  4013 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:18:10.708  4013  4013 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 16:18:10.718  4013  4013 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 16:18:10.720  4013  4013 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 16:18:10.738  4013  4013 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 16:18:10.751  4013  4013 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 16:18:10.751  4013  4013 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 16:18:10.751  4013  4013 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:18:10.751  4013  4013 I Adreno  : Build Date                       : 10/20/15
08-30 16:18:10.751  4013  4013 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:18:10.751  4013  4013 I Adreno  : Local Branch                     : M14
08-30 16:18:10.751  4013  4013 I Adreno  : Remote Branch                    : 
08-30 16:18:10.751  4013  4013 I Adreno  : Remote Branch                    : 
08-30 16:18:10.751  4013  4013 I Adreno  : Reconstruct Branch               : 
,08-30 16:18:10.820  4013  4013 I NSApplication: Starting up...
,08-30 16:18:10.835  4013  4059 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 16:18:10.864   875   886 I ActivityManager: Start proc 4064:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-30 16:18:10.865   875   886 I ActivityManager: Killing 3511:android.process.acore/u0a5 (adj 15): empty #17
,08-30 16:18:10.936  4064  4064 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 16:18:11.130   875  1966 I ActivityManager: Killing 3717:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 16:18:11.225   875  3155 I ActivityManager: Start proc 4078:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 16:18:11.316  4078  4078 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 16:18:11.371  4078  4078 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 16:18:11.441   875  2001 I ActivityManager: Killing 3734:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 16:18:14.506   875  1972 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,08-30 16:18:14.507   875  1972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:18:14.519   875  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:18:14.529  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:14.529  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:14.529  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:14.530  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:14.533  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:14.533  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:14.533  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:14.534  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:14.540  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:14.540  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:14.540  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:14.541  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:14.562   875  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-30 16:18:14.563   875  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 16:18:14.564   875  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 16:18:14.565   875  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 16:18:14.565   875  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 16:18:14.565   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 16:18:14.565   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 16:18:14.574   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 16:18:14.575   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:18:14.575   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:14.576   875  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 16:18:14.576   875  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 16:18:14.586   875  1317 E native  : do suspend true
,08-30 16:18:14.586   875  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 16:18:14.592   875  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 16:18:14.613   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:18:15.424   875  1966 I ActivityManager: Killing 2221:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 16:18:15.988   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:18:16.064   875  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.38 rxSuccessRate=9.38 delta 1000 -> 994
,08-30 16:18:16.066   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 16:18:16.066   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:16.089   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 16:18:16.137   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 16:18:16.139  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 16:18:16.571  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:18:16.615  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:18:16.615  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 16:18:16.620   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:18:16.632   875  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:18:16.633   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:18:16.633   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 16:18:16.653   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:16.664   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:16.665   875  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 16:18:16.675   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 16:18:16.709   875  4111 D DhcpClient: Receive thread started
,08-30 16:18:16.794   875  1317 E native  : do suspend false
,08-30 16:18:16.817   875  1860 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 16:18:16.838   875  4111 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172649, domain null
,08-30 16:18:16.839   875  1860 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172649 seconds
,08-30 16:18:16.843   875  1860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 16:18:16.858   875  4111 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 16:18:16.860   875  1860 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 16:18:16.867   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:16.879   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 16:18:16.881   875  1860 D DhcpClient: Scheduling renewal in 86399s
,08-30 16:18:16.881   875  1317 E native  : do suspend true
,08-30 16:18:16.913   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 16:18:16.916   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 16:18:16.918   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:18:16.921   875  1319 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 16:18:16.933   875  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:18:16.978   875  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 16:18:16.978   875  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 16:18:16.983   875  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 16:18:16.988   875  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 16:18:16.991   875  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 16:18:17.001   875  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 16:18:17.007   875  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 16:18:17.007   875  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 16:18:17.007   875  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-30 16:18:17.007   875  1319 D ConnectivityService:    accepting network in place of null
08-30 16:18:17.007   875  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 16:18:17.008   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:18:17.009   875  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:18:17.022   875  4110 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174469, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:18:17.041   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:17.089   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:17.093   875  4109 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 16:18:17.098   875  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 16:18:17.098   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:17.105   875  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 16:18:17.109   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:18:17.121  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:17.121  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:18:17.121  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:17.121  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:17.124  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:17.124  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:18:17.124  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:17.125  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:17.129  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:17.129  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:18:17.129  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:17.130  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:17.138  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:18:17.141  1737  1737 D SystemUpdateService: onCreate
,08-30 16:18:17.145  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:18:17.164  1737  4121 I SystemUpdateService: active receiver: enabled
,08-30 16:18:17.170  1737  4121 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:18:17.171   875  4109 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:18:17 GMT], X-Android-Received-Millis=[1472566697171], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472566697142]}
08-30 16:18:17.172  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-30 16:18:17.172   875  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 16:18:17.173   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 16:18:17.173   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 16:18:17.179   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 16:18:17.182  1737  2426 I iu.UploadsManager: num queued entries: 0
,08-30 16:18:17.184  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:18:17.186  1737  2426 I iu.UploadsManager: num updated entries: 0
,08-30 16:18:17.187  1737  2426 I iu.SyncManager: NEXT; no task
,08-30 16:18:17.189  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:18:17.190  1737  4121 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 16:18:17.191  1737  4121 I SystemUpdateService: now status is 0 (complete)
,08-30 16:18:17.191  1737  4121 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:18:17.191  1737  4121 I SystemUpdateService: file has been verified
08-30 16:18:17.191  1737  4121 I SystemUpdateService: OTA package size = 12249756
08-30 16:18:17.194  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:17.204  1737  4125 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-30 16:18:17.205  1737  4125 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 16:18:17.206  3984  3984 D SprintDMHelper: simOperator: 
08-30 16:18:17.206  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:18:17.208  1737  4125 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:18:17.212  1737  4121 I SystemUpdateService: showing system update notification
,08-30 16:18:17.230  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:17.234  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:17.289  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 16:18:17.289  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 16:18:17.289  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:18:17.289  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:17.291  1737  1737 D SystemUpdateService: onDestroy
,08-30 16:18:17.320  1737  4125 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-30 16:18:17.325  2471  4129 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 16:18:18.098   875  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 16:18:19.513   875  1883 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,08-30 16:18:19.513   875  1883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:18:19.550  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 16:18:19.558   875  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 16:18:19.558   875  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 16:18:19.559   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:18:19.559   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:19.598   875  1317 E native  : do suspend true
,08-30 16:18:19.611   875  1860 D DhcpClient: Clearing IP address
,08-30 16:18:19.613   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:18:19.617   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:19.626  1511  4133 V NativeCrypto: Read error: ssl=0x9a693a00: I/O error during system call, Connection timed out
,08-30 16:18:19.630  1511  4133 V NativeCrypto: SSL shutdown failed: ssl=0x9a693a00: I/O error during system call, Broken pipe
,08-30 16:18:19.631   875  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 16:18:19.632   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:18:19.632   875  1317 E native  : do suspend true
08-30 16:18:19.633   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 16:18:19.633   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 16:18:19.637   396   396 E Parcel  : Reading a NULL string not supported here.
,08-30 16:18:19.649   875  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 16:18:19.650   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:18:19.658   875  4111 D DhcpClient: Receive thread stopped
,08-30 16:18:19.692   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:19.743   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:19.744   875  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 16:18:19.745   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:19.750   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:18:19.751   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 16:18:19.770  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:19.771  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:19.771  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.771  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:19.772  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:19.772  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:19.772  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.772  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:19.773  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:19.773  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:19.773  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.773  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:19.782  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 16:18:19.784   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 16:18:19.788  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:19.788  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:19.789  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.789  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:19.789   875  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:18:19.790  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:19.790  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:19.790  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.790  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:19.790  1737  1737 D SystemUpdateService: onCreate
08-30 16:18:19.791  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:19.791  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:19.791  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:19.791  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:19.794  2022  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:18:19.796  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 16:18:19.810  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 16:18:19.812  1737  2426 I iu.UploadsManager: num queued entries: 0
,08-30 16:18:19.817  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:18:19.818  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:18:19.821  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:19.826  3984  3984 D SprintDMHelper: simOperator: 
,08-30 16:18:19.826  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:18:19.830  1737  4144 I SystemUpdateService: active receiver: enabled
,08-30 16:18:19.838  1737  2426 I iu.UploadsManager: num updated entries: 0
,08-30 16:18:19.838  1737  2426 I iu.SyncManager: NEXT; no task
,08-30 16:18:19.845  2471  4148 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 16:18:19.847  1737  4144 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:18:19.849  1737  4144 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 16:18:19.849   373   873 E Netd    : netlink response contains error (No such file or directory)
08-30 16:18:19.850  1737  4144 I SystemUpdateService: now status is 0 (complete)
,08-30 16:18:19.850  1737  4144 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:18:19.850  1737  4144 I SystemUpdateService: file has been verified
,08-30 16:18:19.850  1737  4144 I SystemUpdateService: OTA package size = 12249756
,08-30 16:18:19.880  1737  4144 I SystemUpdateService: showing system update notification
,08-30 16:18:19.895  1737  1737 D SystemUpdateService: onDestroy
,08-30 16:18:24.575   875   892 I ActivityManager: Start proc 4151:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 16:18:24.726  4151  4151 D AdapterServiceConfig: Adding HeadsetService
,08-30 16:18:24.727  4151  4151 D AdapterServiceConfig: Adding A2dpService
,08-30 16:18:24.727  4151  4151 D AdapterServiceConfig: Adding HidService
08-30 16:18:24.727  4151  4151 D AdapterServiceConfig: Adding HealthService
08-30 16:18:24.727  4151  4151 D AdapterServiceConfig: Adding PanService
08-30 16:18:24.727  4151  4151 D AdapterServiceConfig: Adding GattService
,08-30 16:18:24.728  4151  4151 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 16:18:24.743   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89b9d29:true
,08-30 16:18:24.743  4151  4151 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 16:18:24.752  4151  4151 I bt_bluedroid: init
,08-30 16:18:24.753  4151  4163 I BluetoothAdapterState: Entering OffState
,08-30 16:18:24.757  4151  4164 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 16:18:24.758  4151  4164 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:18:24.758  4151  4164 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:18:24.758  4151  4164 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 16:18:24.760  4151  4151 I bt_bluedroid: get_profile_interface socket
,08-30 16:18:24.762  4151  4151 I bt_bluedroid: get_profile_interface sdp
,08-30 16:18:24.767  4151  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:18:24.768  4151  4162 I bt_bluedroid: config_hci_snoop_log
08-30 16:18:24.769  4151  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:18:24.772   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 16:18:24.782  4151  4163 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 16:18:24.783  4151  4163 D BluetoothAdapterProperties: Setting state to 14
,08-30 16:18:24.784  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 16:18:24.790  4151  4163 D BluetoothBondStateMachine: make
,08-30 16:18:24.796  4151  4168 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 16:18:24.805  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:18:24.807  4151  4151 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 16:18:24.812  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:24.813  4151  4151 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:18:24.814  4151  4151 D BtGatt.GattService: Received start request. Starting profile...
,08-30 16:18:24.814  4151  4151 D BtGatt.GattService: start()
,08-30 16:18:24.814  4151  4151 I bt_bluedroid: get_profile_interface gatt
,08-30 16:18:24.816  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:24.817  4151  4151 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:18:24.827  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:24.827  4151  4151 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:24.827  4151  4151 V BluetoothAdapterState: isBleTurningOn()=true
08-30 16:18:24.827  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:24.828  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 16:18:24.829  4151  4163 I bt_bluedroid: enable
08-30 16:18:24.829  4151  4164 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 16:18:24.830  4151  4164 I bt_hci  : start_up
,08-30 16:18:24.850  4151  4164 I bt_vendor: alloc value 0xb399f189
,08-30 16:18:24.850  4151  4164 I bt_vendor: init
08-30 16:18:24.850  4151  4164 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 16:18:24.850  4151  4164 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 16:18:24.959  4151  4164 D bt_hci  : start_up starting async portion
,08-30 16:18:24.959  4151  4171 I bt_hci  : event_finish_startup
,08-30 16:18:24.960  4151  4171 I bt_hci_h4: hal_open
08-30 16:18:24.960  4151  4171 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 16:18:24.969  4151  4171 I bt_userial_vendor: device fd = 51 open
,08-30 16:18:25.002  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:18:25.012   875  1319 D ConnectivityService: handlePromptUnvalidated 101
,08-30 16:18:25.032  4151  4171 D bt_hwcfg: Chipset BCM4354A2
,08-30 16:18:25.032  4151  4171 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 16:18:25.033  4151  4171 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 16:18:25.690  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 16:18:25.692  4151  4171 D bt_hwcfg: Settlement delay -- 100 ms
08-30 16:18:25.692  4151  4171 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 16:18:25.809  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:18:25.810  4151  4171 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 16:18:25.839  4151  4171 I bt_hwcfg: vendor lib fwcfg completed
,08-30 16:18:25.839  4151  4171 I bt_vendor: firmware callback
,08-30 16:18:25.840  4151  4171 I bt_hci  : firmware_config_callback
,08-30 16:18:25.851  4151  4173 I bt_btu  : btu_task pending for preload complete event
,08-30 16:18:25.851  4151  4173 I bt_btu_task: Bluetooth chip preload is complete
08-30 16:18:25.851  4151  4173 I bt_btu  : btu_task received preload complete event
,08-30 16:18:25.863  4151  4173 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 16:18:25.864  4151  4173 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 16:18:25.864  4151  4173 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:18:25.864  4151  4173 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:18:25.865  4151  4173 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:18:25.865  4151  4173 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:18:25.865  4151  4173 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 16:18:25.866  4151  4173 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:18:25.866  4151  4173 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 16:18:25.866  4151  4173 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:18:25.867  4151  4173 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 16:18:25.867  4151  4173 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:18:25.868  4151  4173 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:18:25.868  4151  4173 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:18:25.868  4151  4173 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:18:26.005  4151  4173 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391cd9d
08-30 16:18:26.005  4151  4173 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391cd9d 
,08-30 16:18:26.015  4151  4167 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 16:18:26.017  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:18:26.018  4151  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:18:26.023  4151  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:18:26.027  4151  4167 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:18:26.028  4151  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:18:26.028  4151  4167 D bt_hci  : do_postload posting postload work item
08-30 16:18:26.029  4151  4171 I bt_hci  : event_postload
,08-30 16:18:26.029  4151  4171 I bt_vendor: sco_config_cb
08-30 16:18:26.029  4151  4171 I bt_hci  : sco_config_callback postload finished.
08-30 16:18:26.032  4151  4167 D bt_bte_conf: Device ID record 1 : primary
,08-30 16:18:26.032  4151  4167 D bt_bte_conf:   vendorId            = 000f
,08-30 16:18:26.032  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:26.032  4151  4167 D bt_bte_conf:   vendorIdSource      = 0001
08-30 16:18:26.033  4151  4167 D bt_bte_conf:   product             = 1200
08-30 16:18:26.033  4151  4167 D bt_bte_conf:   version             = 1436
,08-30 16:18:26.033  4151  4167 D bt_bte_conf:   clientExecutableURL = 
,08-30 16:18:26.033  4151  4167 D bt_bte_conf:   serviceDescription  = 
08-30 16:18:26.034  4151  4167 D bt_bte_conf:   documentationURL    = 
08-30 16:18:26.034  4151  4167 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 16:18:26.035  4151  4164 D bt_stack_manager: event_start_up_stack finished
,08-30 16:18:26.035  4151  4171 I bt_vendor: low_power_mode_cb
,08-30 16:18:26.036  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 16:18:26.036  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:26.036  4151  4163 D BluetoothAdapterProperties: Setting state to 15
08-30 16:18:26.036  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 16:18:26.038  4151  4163 I BluetoothAdapterState: Entering BleOnState
08-30 16:18:26.042  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:26.046  4151  4163 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 16:18:26.046  4151  4163 D BluetoothAdapterProperties: Setting state to 11
08-30 16:18:26.046  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 16:18:26.051  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:26.052  4151  4151 D HeadsetService: Received start request. Starting profile...
08-30 16:18:26.060  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:26.062  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:26.064  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:26.064  4151  4151 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:18:26.064  4151  4151 D HeadsetStateMachine: make
08-30 16:18:26.067  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:18:26.073  4151  4151 D HeadsetStateMachine: max_hf_connections = 1
,08-30 16:18:26.073  4151  4151 I bt_bluedroid: get_profile_interface handsfree
08-30 16:18:26.073  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 16:18:26.074  4151  4167 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 16:18:26.080  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:26.081  4151  4151 D A2dpService: Received start request. Starting profile...
08-30 16:18:26.081  4151  4151 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 16:18:26.081  4151  4151 I bt_bluedroid: get_profile_interface avrcp
,08-30 16:18:26.087  4151  4151 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:18:26.088  4151  4151 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 16:18:26.088  4151  4151 D A2dpStateMachine: make
08-30 16:18:26.089  4151  4151 I bt_bluedroid: get_profile_interface a2dp
,08-30 16:18:26.089  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 16:18:26.094  4151  4183 D A2dpStateMachine: Enter Disconnected: -2
,08-30 16:18:26.095  4151  4151 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 16:18:26.097  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:26.099  3929  3929 D BluetoothInputDevice: Proxy object connected
,08-30 16:18:26.099  4151  4151 D HidService: Received start request. Starting profile...
08-30 16:18:26.100  4151  4151 I bt_bluedroid: get_profile_interface hidhost
08-30 16:18:26.100  4151  4151 D HidService: setHidService(): set to: null
08-30 16:18:26.100  4151  4167 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fe3e5
08-30 16:18:26.100  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 16:18:26.100  3929  3929 D HidProfile: Bluetooth service connected
,08-30 16:18:26.101  4151  4151 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:18:26.101  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
08-30 16:18:26.102  4151  4151 D HealthService: Received start request. Starting profile...
,08-30 16:18:26.103  4151  4151 I bt_bluedroid: get_profile_interface health
,08-30 16:18:26.105  4151  4151 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 16:18:26.106  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
08-30 16:18:26.107  4151  4151 D PanService: Received start request. Starting profile...
08-30 16:18:26.108  4151  4151 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:18:26.108  4151  4151 I bt_bluedroid: get_profile_interface pan
,08-30 16:18:26.109  4151  4167 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:18:26.109  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:18:26.111  3929  3929 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:18:26.112  3929  3929 D PanProfile: Bluetooth service connected
,08-30 16:18:26.115  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:26.117  4151  4151 D BluetoothMapService: Received start request. Starting profile...
,08-30 16:18:26.117  3929  3929 D BluetoothMap: Proxy object connected
08-30 16:18:26.118  4151  4151 D BluetoothMapService: start()
08-30 16:18:26.118  3929  3929 D MapProfile: Bluetooth service connected
08-30 16:18:26.119  3929  3929 D BluetoothMap: getConnectedDevices()
,08-30 16:18:26.121  4151  4151 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 16:18:26.123  3929  3929 D BluetoothMap: Bluetooth is Not enabled
,08-30 16:18:26.123  4151  4151 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 16:18:26.123  4151  4151 D BluetoothMapAppObserver: createReceiver()
,08-30 16:18:26.125  4151  4151 D BluetoothMapAppObserver: initObservers()
,08-30 16:18:26.125  4151  4151 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 16:18:26.138  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:26.139  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:26.139  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:26.139  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:18:26.143  4151  4181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 16:18:26.143  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:26.143  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:26.143  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:26.143  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:26.144  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:26.145  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:26.145  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:26.145  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:26.145  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:26.145  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:26.145  4151  4151 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:18:26.146  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:26.146  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:26.147  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 16:18:26.147  4151  4163 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:18:26.147  4151  4163 D BluetoothAdapterProperties: State =  11
08-30 16:18:26.147  4151  4163 D BluetoothAdapterProperties: Setting state to 12
,08-30 16:18:26.147  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 16:18:26.148  4151  4163 I BluetoothAdapterState: Entering OnState
08-30 16:18:26.149  3929  3940 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:18:26.149  1374  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:18:26.150  4151  4167 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:18:26.150  4151  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:18:26.154  1374  1374 D BluetoothInputDevice: Proxy object connected
08-30 16:18:26.154  1374  1374 D HidProfile: Bluetooth service connected
08-30 16:18:26.155   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:18:26.156   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:26.156   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:26.156  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:26.156  3929  3939 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:18:26.157  3929  3940 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:18:26.157  4151  4151 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 16:18:26.157   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:18:26.157  4151  4151 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 16:18:26.158  1374  2073 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:18:26.158  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:26.159  4151  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:18:26.161  1955  2339 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:26.162  4151  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:18:26.162  1374  1392 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:26.162  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:26.164  4151  4151 D ObexServerSockets: Succeed to create listening sockets 
08-30 16:18:26.164  4151  4151 D ObexServerSockets0: startAccept()
08-30 16:18:26.164  4151  4151 D ObexServerSockets0: prepareForNewConnect()
08-30 16:18:26.164  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:26.168  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:26.168  4151  4151 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 16:18:26.170  4151  4189 D ObexServerSockets0: Accepting socket connection...
,08-30 16:18:26.170  4151  4151 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 16:18:26.171  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:26.171  1374  1374 D BluetoothMap: Proxy object connected
08-30 16:18:26.172  1374  1374 D MapProfile: Bluetooth service connected
08-30 16:18:26.172  1374  1374 D BluetoothMap: getConnectedDevices()
08-30 16:18:26.172  1374  2073 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:18:26.175  3929  3939 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:18:26.176  4151  4188 D ObexServerSockets0: Accepting socket connection...
,08-30 16:18:26.177   875   875 D BluetoothA2dp: Proxy object connected
08-30 16:18:26.178  1374  1392 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:18:26.178  1374  1374 D BluetoothA2dp: Proxy object connected
,08-30 16:18:26.180  1374  2073 D BluetoothPan: onBluetoothStateChange on: true
,08-30 16:18:26.182  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:18:26.182  1374  1374 D PanProfile: Bluetooth service connected
,08-30 16:18:26.183   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 16:18:26.184  4151  4151 D BluetoothMapService: onReceive
,08-30 16:18:26.185  4151  4151 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:18:26.185  4151  4151 D BluetoothMapService: STATE_ON
08-30 16:18:26.185  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:26.186  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:26.189  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:26.191  3929  3929 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 16:18:26.196  3929  3929 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 16:18:26.203  3929  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:18:26.205  4151  4151 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:18:26.205  4151  4151 D ObexServerSockets0: prepareForNewConnect()
,08-30 16:18:26.207  3929  3929 D BluetoothA2dp: Proxy object connected
,08-30 16:18:26.211  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:18:26.217  3929  3929 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:18:26.224  1374  1374 D BluetoothPbap: Proxy object connected
,08-30 16:18:26.224  1374  1374 D PbapServerProfile: Bluetooth service connected
,08-30 16:18:26.225  3929  3929 D BluetoothPbap: Proxy object connected
,08-30 16:18:26.226  3929  3929 D PbapServerProfile: Bluetooth service connected
,08-30 16:18:26.255  4151  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:18:26.268  1374  1392 D BluetoothHeadset: Proxy object connected
,08-30 16:18:26.269  1374  1374 D HeadsetProfile: Bluetooth service connected
08-30 16:18:26.269   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:18:26.269   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:18:26.269   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:18:26.270  1955  2269 D BluetoothHeadset: Proxy object connected
,08-30 16:18:26.275  4151  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:18:26.279  1374  1386 D BluetoothHeadset: Proxy object connected
,08-30 16:18:26.281  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-30 16:18:26.285  4151  4200 I BtOppRfcommListener: Accept thread started.
,08-30 16:18:26.300  3929  3939 D BluetoothHeadset: Proxy object connected
,08-30 16:18:26.302  3929  3929 D HeadsetProfile: Bluetooth service connected
,08-30 16:18:26.420  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:26.435  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:26.441  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:26.500  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:18:26.501  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 16:18:26.501  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:18:26.502  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:26.552  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:18:26.553  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:18:26.554  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 16:18:29.533  4151  4163 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 16:18:29.533  4151  4163 D BluetoothAdapterProperties: Setting state to 13
,08-30 16:18:29.533  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 16:18:29.535  4151  4163 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 16:18:29.537  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:18:29.554  4151  4151 D BluetoothMapService: onReceive
,08-30 16:18:29.554  4151  4151 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:18:29.555  4151  4151 D BluetoothMapService: STATE_TURNING_OFF
,08-30 16:18:29.555  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:29.556  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:29.555  4151  4151 D BluetoothMapService: MAP Service closeService in
,08-30 16:18:29.556  4151  4151 D BluetoothMapMasInstance0: MAP Service shutdown
,08-30 16:18:29.558  4151  4151 D ObexServerSockets0: shutdown(block = true)
08-30 16:18:29.558  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:29.558  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:29.559  4151  4188 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 16:18:29.562  4151  4167 D BluetoothAdapterProperties: Scan Mode:20,
08-30 16:18:29.563  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 16:18:29.563  4151  4151 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:18:29.564  3929  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
08-30 16:18:29.564  4151  4189 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 16:18:29.564  4151  4176 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 16:18:29.565  4151  4151 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 16:18:29.565  4151  4151 I BtOppRfcommListener: stopping Accept Thread
,08-30 16:18:29.565  4151  4200 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:18:29.568  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:29.568  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:29.569  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:29.569  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:29.570  4151  4200 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:18:29.572  4151  4151 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:18:29.575  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:29.575  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:29.577  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:18:29.577  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:29.578  4151  4151 D A2dpService: Received stop request...Stopping profile...
08-30 16:18:29.578  1374  2073 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:29.578  4151  4183 D A2dpStateMachine: Exit Disconnected: -1
08-30 16:18:29.579  1374  1374 D HeadsetProfile: Bluetooth service disconnected
08-30 16:18:29.579   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:29.580   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 16:18:29.580   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:29.580  3929  3940 D BluetoothHeadset: Proxy object disconnected
08-30 16:18:29.581  1955  2339 D BluetoothHeadset: Proxy object disconnected
,08-30 16:18:29.581  1374  1374 D BluetoothA2dp: Proxy object disconnected
,08-30 16:18:29.581   875   875 D BluetoothA2dp: Proxy object disconnected
08-30 16:18:29.582  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:29.584  3929  3929 D DockEventReceiver: finishStartingService: stopping service
08-30 16:18:29.585  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:29.586  3929  3929 D HeadsetProfile: Bluetooth service disconnected
08-30 16:18:29.587  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:29.588  3929  3929 D BluetoothA2dp: Proxy object disconnected
08-30 16:18:29.589  4151  4151 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:18:29.589  4151  4151 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:29.590  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:29.590  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:29.590  4151  4151 D HidService: Received stop request...Stopping profile...
,08-30 16:18:29.590  4151  4151 D HidService: Stopping Bluetooth HidService
08-30 16:18:29.591  1374  1374 D BluetoothInputDevice: Proxy object disconnected
08-30 16:18:29.591  1374  1374 D HidProfile: Bluetooth service disconnected
08-30 16:18:29.591  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:18:29.592  3929  3929 D BluetoothInputDevice: Proxy object disconnected
,08-30 16:18:29.592  3929  3929 D HidProfile: Bluetooth service disconnected
08-30 16:18:29.594  4151  4151 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:18:29.594  4151  4151 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:18:29.594  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 16:18:29.594  4151  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:29.594  4151  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:29.594  4151  4151 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:29.594  4151  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 16:18:29.594  4151  4151 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:29.594  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:29.594  4151  4167 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 16:18:29.594  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:29.595  4151  4151 D HealthService: Received stop request...Stopping profile...
08-30 16:18:29.597  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 16:18:29.597  4151  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:29.597  4151  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:29.597  4151  4173 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:18:29.597  4151  4173 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 16:18:29.598  4151  4151 D PanService: Received stop request...Stopping profile...
,08-30 16:18:29.598  4151  4173 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:18:29.598  4151  4173 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 16:18:29.599  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:18:29.599  1374  1374 D PanProfile: Bluetooth service disconnected
,08-30 16:18:29.599  3929  3929 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 16:18:29.599  4151  4151 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:18:29.600  4151  4151 D BluetoothMapService: stop()
,08-30 16:18:29.600  4151  4151 D BluetoothMapAppObserver: deinitObservers()
08-30 16:18:29.600  4151  4151 D BluetoothMapAppObserver: removeReceiver()
08-30 16:18:29.600  3929  3929 D PanProfile: Bluetooth service disconnected
08-30 16:18:29.601  3929  3929 D BluetoothMap: Proxy object disconnected
08-30 16:18:29.601  3929  3929 D MapProfile: Bluetooth service disconnected
08-30 16:18:29.601  1374  1374 D BluetoothMap: Proxy object disconnected
08-30 16:18:29.601  1374  1374 D MapProfile: Bluetooth service disconnected
08-30 16:18:29.603  3929  3929 D BluetoothPbap: Proxy object disconnected
,08-30 16:18:29.603  3929  3929 D PbapServerProfile: Bluetooth service disconnected
,08-30 16:18:29.603  1374  1374 D BluetoothPbap: Proxy object disconnected
,08-30 16:18:29.603  1374  1374 D PbapServerProfile: Bluetooth service disconnected
,08-30 16:18:29.603  4151  4151 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:18:29.603  4151  4151 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:29.604  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:29.604  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:18:29.604  4151  4151 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:18:29.604  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:18:29.604  4151  4151 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 16:18:29.606  4151  4151 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:29.606  4151  4151 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:29.606  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:29.606  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:29.607  4151  4151 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 16:18:29.607  4151  4167 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 16:18:29.607  4151  4151 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 16:18:29.607  4151  4151 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:29.607  4151  4151 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:29.607  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:29.607  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:29.608  4151  4151 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 16:18:29.608  4151  4151 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:18:29.609  4151  4151 D BluetoothMapService: MAP Service closeService in
08-30 16:18:29.609  4151  4151 V BluetoothAdapterState: isTurningOff()=true
08-30 16:18:29.609  4151  4151 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:18:29.609  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:29.609  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:29.609  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 16:18:29.609  4151  4163 D BluetoothAdapterProperties: Setting state to 15
,08-30 16:18:29.609  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 16:18:29.610  4151  4151 D BluetoothMapService: cleanup()
,08-30 16:18:29.610  4151  4151 D BluetoothMapService: MAP Service closeService in
08-30 16:18:29.610  3929  3939 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 16:18:29.610  4151  4163 I BluetoothAdapterState: Entering BleOnState
08-30 16:18:29.611  1374  1392 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:18:29.611  3929  4205 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:18:29.611   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:29.612  3929  3940 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:18:29.612   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:18:29.612   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:29.612  3929  3939 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:18:29.613  3929  4205 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:18:29.613   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:18:29.613  1374  2073 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:18:29.614  1955  2269 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:29.614  1374  1386 D BluetoothMap: onBluetoothStateChange: up=false,
08-30 16:18:29.615  1374  1392 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:18:29.615  3929  3940 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 16:18:29.616  1374  2073 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:18:29.616  1374  1386 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:18:29.617  4151  4163 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 16:18:29.617  4151  4163 D BluetoothAdapterProperties: Setting state to 16
08-30 16:18:29.617  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 16:18:29.617  4151  4163 D BluetoothAdapterProperties: onBleDisable
,08-30 16:18:29.619  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:18:29.619  4151  4164 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 16:18:29.620  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:29.620  4151  4167 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:18:29.620  4151  4173 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 16:18:29.620  4151  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:18:29.622  3929  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:18:29.623  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:29.626  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:18:29.627  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:29.628  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:29.629  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:29.630  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:29.635  3929  3929 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:18:29.821  4151  4167 I bt_hci  : shut_down
,08-30 16:18:29.822  4151  4171 D bt_hwcfg: hw_epilog_process
,08-30 16:18:29.833  4151  4171 I bt_vendor: low_power_mode_cb
,08-30 16:18:29.857  4151  4171 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 16:18:29.858  4151  4171 I bt_vendor: epilog_cb
08-30 16:18:29.858  4151  4171 I bt_hci  : epilog_finished_callback
,08-30 16:18:29.865  4151  4167 I bt_hci_h4: hal_close
,08-30 16:18:29.867  4151  4167 I bt_userial_vendor: device fd = 51 close
,08-30 16:18:29.991  4151  4164 D bt_stack_manager: event_shut_down_stack finished.
,08-30 16:18:29.993  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 16:18:29.999  4151  4151 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:18:29.999  4151  4163 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 16:18:30.001  4151  4151 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 16:18:30.001  4151  4151 D BtGatt.GattService: stop()
08-30 16:18:30.001  4151  4151 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:18:30.006  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:30.006  4151  4151 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:30.007  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:30.007  4151  4151 V BluetoothAdapterState: isBleTurningOff()=true
08-30 16:18:30.008  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 16:18:30.008  4151  4163 D BluetoothAdapterProperties: Setting state to 10
,08-30 16:18:30.008  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 16:18:30.010  4151  4163 I BluetoothAdapterState: Entering OffState
,08-30 16:18:30.011   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 16:18:30.036  4151  4151 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 16:18:30.037  4151  4151 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 16:18:30.037  4151  4164 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 16:18:30.045  4151  4164 D bt_stack_manager: event_clean_up_stack finished.
08-30 16:18:30.045  4151  4151 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 16:18:30.052  4151  4151 I art     : System.exit called, status: 0
,08-30 16:18:30.052  4151  4151 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 16:18:30.115   875  1966 I ActivityManager: Process com.android.bluetooth (pid 4151) has died
,08-30 16:18:34.529  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:18:34.529  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:34.534  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:34.534  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d3d433 removed from the list
08-30 16:18:34.535  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:18:34.535  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:18:34.535  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:34.538  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:18:34.539  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aaacd69 added. We now have 4 listener(s)
,08-30 16:18:34.540  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:18:34.541  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:34.542  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aaacd69 removed from the list
08-30 16:18:34.542  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:34.542  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:34.543  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:18:34.545  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:18:34.545  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d85a3ee added. We now have 4 listener(s)
08-30 16:18:34.545  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:18:39.558  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:39.604   875   892 I ActivityManager: Start proc 4212:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 16:18:39.740  4212  4212 D AdapterServiceConfig: Adding HeadsetService
,08-30 16:18:39.740  4212  4212 D AdapterServiceConfig: Adding A2dpService
08-30 16:18:39.741  4212  4212 D AdapterServiceConfig: Adding HidService
08-30 16:18:39.741  4212  4212 D AdapterServiceConfig: Adding HealthService
08-30 16:18:39.741  4212  4212 D AdapterServiceConfig: Adding PanService
08-30 16:18:39.741  4212  4212 D AdapterServiceConfig: Adding GattService
08-30 16:18:39.742  4212  4212 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 16:18:39.756  4212  4212 D BluetoothAdapterState: make() - Creating AdapterState
08-30 16:18:39.756   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee35134:true
,08-30 16:18:39.761  4212  4212 I bt_bluedroid: init
,08-30 16:18:39.762  4212  4224 I BluetoothAdapterState: Entering OffState
,08-30 16:18:39.764  4212  4225 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 16:18:39.764  4212  4225 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:18:39.764  4212  4225 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:18:39.764  4212  4225 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 16:18:39.765  4212  4212 I bt_bluedroid: get_profile_interface socket
,08-30 16:18:39.768  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:18:39.769  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:18:39.770  4212  4212 I bt_bluedroid: get_profile_interface sdp
,08-30 16:18:39.774  4212  4223 I bt_bluedroid: config_hci_snoop_log
,08-30 16:18:39.776   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 16:18:39.787  4212  4224 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 16:18:39.788  4212  4224 D BluetoothAdapterProperties: Setting state to 14,
08-30 16:18:39.788  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 16:18:39.792  4212  4224 D BluetoothBondStateMachine: make
,08-30 16:18:39.798  4212  4229 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 16:18:39.806  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:18:39.810  4212  4212 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 16:18:39.820  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:39.823  4212  4212 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:18:39.824  4212  4212 D BtGatt.GattService: Received start request. Starting profile...
,08-30 16:18:39.825  4212  4212 D BtGatt.GattService: start()
08-30 16:18:39.825  4212  4212 I bt_bluedroid: get_profile_interface gatt
,08-30 16:18:39.828  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
08-30 16:18:39.829  4212  4212 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:18:39.839  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:39.839  4212  4212 V BluetoothAdapterState: isTurningOn()=false
08-30 16:18:39.840  4212  4212 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 16:18:39.840  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:39.840  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 16:18:39.841  4212  4224 I bt_bluedroid: enable
,08-30 16:18:39.841  4212  4225 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 16:18:39.842  4212  4225 I bt_hci  : start_up
,08-30 16:18:39.849  4212  4225 I bt_vendor: alloc value 0xb399f189
,08-30 16:18:39.849  4212  4225 I bt_vendor: init
08-30 16:18:39.849  4212  4225 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 16:18:39.849  4212  4225 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 16:18:39.958  4212  4225 D bt_hci  : start_up starting async portion
,08-30 16:18:39.959  4212  4232 I bt_hci  : event_finish_startup
,08-30 16:18:39.959  4212  4232 I bt_hci_h4: hal_open
08-30 16:18:39.960  4212  4232 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 16:18:39.970  4212  4232 I bt_userial_vendor: device fd = 51 open
,08-30 16:18:40.001  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:18:40.033  4212  4232 D bt_hwcfg: Chipset BCM4354A2
,08-30 16:18:40.033  4212  4232 D bt_hwcfg: Target name = [BCM4354A2]
08-30 16:18:40.034  4212  4232 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 16:18:40.757  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 16:18:40.758  4212  4232 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 16:18:40.758  4212  4232 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 16:18:40.875  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:18:40.876  4212  4232 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 16:18:40.907  4212  4232 I bt_hwcfg: vendor lib fwcfg completed
,08-30 16:18:40.907  4212  4232 I bt_vendor: firmware callback
08-30 16:18:40.907  4212  4232 I bt_hci  : firmware_config_callback
,08-30 16:18:40.919  4212  4234 I bt_btu  : btu_task pending for preload complete event
,08-30 16:18:40.919  4212  4234 I bt_btu_task: Bluetooth chip preload is complete
,08-30 16:18:40.919  4212  4234 I bt_btu  : btu_task received preload complete event,
,08-30 16:18:40.931  4212  4234 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:18:40.931  4212  4234 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:18:40.931  4212  4234 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:18:40.932  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:18:40.932  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:18:40.932  4212  4234 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:18:40.932  4212  4234 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:18:40.933  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:18:40.933  4212  4234 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:18:40.933  4212  4234 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:18:40.933  4212  4234 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:18:40.934  4212  4234 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:18:40.934  4212  4234 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:18:40.934  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:18:40.934  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:18:41.066  4212  4234 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391cd9d
,08-30 16:18:41.066  4212  4234 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391cd9d 
,08-30 16:18:41.078  4212  4228 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 16:18:41.082  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 16:18:41.083  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:18:41.089  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:18:41.092  4212  4228 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:18:41.092  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:18:41.094  4212  4228 D bt_hci  : do_postload posting postload work item
,08-30 16:18:41.094  4212  4232 I bt_hci  : event_postload
,08-30 16:18:41.095  4212  4232 I bt_vendor: sco_config_cb
08-30 16:18:41.095  4212  4232 I bt_hci  : sco_config_callback postload finished.
08-30 16:18:41.097  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:41.100  4212  4228 D bt_bte_conf: Device ID record 1 : primary
08-30 16:18:41.100  4212  4228 D bt_bte_conf:   vendorId            = 000f
08-30 16:18:41.100  4212  4228 D bt_bte_conf:   vendorIdSource      = 0001
08-30 16:18:41.101  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:41.101  4212  4228 D bt_bte_conf:   product             = 1200
08-30 16:18:41.101  4212  4228 D bt_bte_conf:   version             = 1436
,08-30 16:18:41.101  4212  4232 I bt_vendor: low_power_mode_cb
08-30 16:18:41.101  4212  4228 D bt_bte_conf:   clientExecutableURL = 
08-30 16:18:41.101  4212  4228 D bt_bte_conf:   serviceDescription  = 
08-30 16:18:41.101  4212  4228 D bt_bte_conf:   documentationURL    = 
08-30 16:18:41.102  4212  4228 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 16:18:41.102  4212  4225 D bt_stack_manager: event_start_up_stack finished
08-30 16:18:41.104  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 16:18:41.105  4212  4224 D BluetoothAdapterProperties: Setting state to 15
08-30 16:18:41.105  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 16:18:41.107  4212  4224 I BluetoothAdapterState: Entering BleOnState
,08-30 16:18:41.114  4212  4224 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 16:18:41.114  4212  4224 D BluetoothAdapterProperties: Setting state to 11
08-30 16:18:41.115  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 16:18:41.123  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:41.124  4212  4212 D HeadsetService: Received start request. Starting profile...
,08-30 16:18:41.131  4212  4212 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:18:41.131  4212  4212 D HeadsetStateMachine: make
,08-30 16:18:41.132  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:41.135  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:41.144  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:18:41.144  4212  4212 D HeadsetStateMachine: max_hf_connections = 1
08-30 16:18:41.144  4212  4212 I bt_bluedroid: get_profile_interface handsfree
08-30 16:18:41.145  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 16:18:41.145  4212  4228 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 16:18:41.149  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:41.149  4212  4212 D A2dpService: Received start request. Starting profile...
,08-30 16:18:41.150  4212  4212 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:18:41.151  4212  4212 I bt_bluedroid: get_profile_interface avrcp
,08-30 16:18:41.157  4212  4212 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 16:18:41.158  4212  4212 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:18:41.158  4212  4212 D A2dpStateMachine: make
,08-30 16:18:41.159  4212  4212 I bt_bluedroid: get_profile_interface a2dp
,08-30 16:18:41.160  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 16:18:41.162  4212  4243 D A2dpStateMachine: Enter Disconnected: -2
,08-30 16:18:41.163  4212  4212 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 16:18:41.164  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:41.165  4212  4212 D HidService: Received start request. Starting profile...
,08-30 16:18:41.165  4212  4212 I bt_bluedroid: get_profile_interface hidhost
08-30 16:18:41.165  4212  4228 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fe3e5
,08-30 16:18:41.166  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 16:18:41.166  4212  4212 D HidService: setHidService(): set to: null
,08-30 16:18:41.169  4212  4212 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:18:41.169  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:18:41.170  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
08-30 16:18:41.171  4212  4212 D HealthService: Received start request. Starting profile...
,08-30 16:18:41.172  4212  4212 I bt_bluedroid: get_profile_interface health
,08-30 16:18:41.174  4212  4212 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 16:18:41.175  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:41.176  4212  4212 D PanService: Received start request. Starting profile...
,08-30 16:18:41.176  4212  4212 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:18:41.176  4212  4212 I bt_bluedroid: get_profile_interface pan
08-30 16:18:41.177  4212  4228 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 16:18:41.181  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:18:41.181  4212  4212 D BluetoothMapService: Received start request. Starting profile...
,08-30 16:18:41.181  4212  4212 D BluetoothMapService: start()
,08-30 16:18:41.185  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 16:18:41.186  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 16:18:41.186  4212  4212 D BluetoothMapAppObserver: createReceiver()
,08-30 16:18:41.188  4212  4212 D BluetoothMapAppObserver: initObservers()
,08-30 16:18:41.188  4212  4212 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 16:18:41.194  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:41.195  4212  4212 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:41.195  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:41.195  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:18:41.196  4212  4240 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:41.197  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isTurningOn()=true
08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:41.198  4212  4212 V BluetoothAdapterState: isTurningOff()=false
08-30 16:18:41.199  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:18:41.199  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:18:41.199  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:18:41.199  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 16:18:41.199  4212  4224 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:18:41.199  4212  4224 D BluetoothAdapterProperties: State =  11
,08-30 16:18:41.204  4212  4228 D BluetoothAdapterProperties: Scan Mode:21
,08-30 16:18:41.204  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:18:41.204  4212  4224 D BluetoothAdapterProperties: Setting state to 12
,08-30 16:18:41.204  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 16:18:41.204  4212  4224 I BluetoothAdapterState: Entering OnState
08-30 16:18:41.205  3929  4205 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:18:41.207  1374  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:41.208  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:41.210  3929  3939 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:41.210   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:41.210  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:41.210  3929  4205 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:18:41.210  1374  1374 D BluetoothInputDevice: Proxy object connected
,08-30 16:18:41.210  1374  1374 D HidProfile: Bluetooth service connected
08-30 16:18:41.211   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:18:41.211   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:41.211  3929  3940 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:18:41.213  3929  4205 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:41.214  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:18:41.214   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:18:41.214  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 16:18:41.214   875   875 D BluetoothA2dp: Proxy object connected
08-30 16:18:41.214  1374  2073 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:18:41.215  4212  4212 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 16:18:41.215  1374  1374 D BluetoothA2dp: Proxy object connected
08-30 16:18:41.216  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:18:41.216  1955  1968 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:41.217  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:18:41.217  1374  1392 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:18:41.218  3929  3929 D BluetoothMap: Proxy object connected
,08-30 16:18:41.218  3929  3929 D MapProfile: Bluetooth service connected
,08-30 16:18:41.218  3929  3929 D BluetoothMap: getConnectedDevices()
08-30 16:18:41.219  1374  1374 D BluetoothMap: Proxy object connected
,08-30 16:18:41.219  1374  1374 D MapProfile: Bluetooth service connected
,08-30 16:18:41.219  1374  2073 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:18:41.219  1374  1374 D BluetoothMap: getConnectedDevices()
08-30 16:18:41.219  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:18:41.220  3929  3939 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:18:41.221  4212  4212 D ObexServerSockets: Succeed to create listening sockets 
,08-30 16:18:41.221  4212  4212 D ObexServerSockets0: startAccept()
,08-30 16:18:41.221  4212  4212 D ObexServerSockets0: prepareForNewConnect()
,08-30 16:18:41.221  1374  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:18:41.221  1374  1392 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:18:41.223   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 16:18:41.225  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:41.227  3929  3929 D BluetoothA2dp: Proxy object connected
08-30 16:18:41.227  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:18:41.227  4212  4212 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 16:18:41.227  4212  4212 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 16:18:41.228  4212  4250 D ObexServerSockets0: Accepting socket connection...
08-30 16:18:41.228  4212  4251 D ObexServerSockets0: Accepting socket connection...
08-30 16:18:41.229  3929  3929 D BluetoothInputDevice: Proxy object connected,
08-30 16:18:41.229  3929  3929 D HidProfile: Bluetooth service connected
08-30 16:18:41.232  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:18:41.232  1374  1374 D PanProfile: Bluetooth service connected
08-30 16:18:41.232  4212  4212 D BluetoothMapService: onReceive
08-30 16:18:41.233  4212  4212 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:18:41.233  4212  4212 D BluetoothMapService: STATE_ON
08-30 16:18:41.236  3929  3929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:18:41.238  3929  3929 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:18:41.238  3929  3929 D PanProfile: Bluetooth service connected
,08-30 16:18:41.241  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:18:41.242  3929  3929 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:18:41.252  3929  3929 D BluetoothPbap: Proxy object connected
,08-30 16:18:41.253  3929  3929 D PbapServerProfile: Bluetooth service connected
,08-30 16:18:41.254  1374  1374 D BluetoothPbap: Proxy object connected
08-30 16:18:41.254  1374  1374 D PbapServerProfile: Bluetooth service connected
,08-30 16:18:41.260  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:18:41.260  4212  4212 D ObexServerSockets0: prepareForNewConnect()
08-30 16:18:41.261  4212  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:18:41.280  4212  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:18:41.281  4212  4259 I BtOppRfcommListener: Accept thread started.
,08-30 16:18:41.311  1374  1386 D BluetoothHeadset: Proxy object connected
,08-30 16:18:41.311   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:18:41.312   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:18:41.311   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:18:41.312   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:18:41.312  1374  1374 D HeadsetProfile: Bluetooth service connected
08-30 16:18:41.312   875   892 D BluetoothHeadset: Proxy object connected
08-30 16:18:41.312  3929  3939 D BluetoothHeadset: Proxy object connected,
08-30 16:18:41.312  1955  1967 D BluetoothHeadset: Proxy object connected
08-30 16:18:41.313  3929  3929 D HeadsetProfile: Bluetooth service connected
,08-30 16:18:41.334  1955  2142 D BluetoothHeadset: Proxy object connected
,08-30 16:18:41.335  1374  1392 D BluetoothHeadset: Proxy object connected
08-30 16:18:41.335  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:44.579  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:44.586  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:44.588  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:18:44.588  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d85a3ee removed from the list
08-30 16:18:44.589  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:18:44.589  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:18:44.589  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:44.592  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:18:44.592  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed808f added. We now have 4 listener(s)
08-30 16:18:44.593  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:18:44.598   875  2013 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,08-30 16:18:44.598   875  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:18:49.611  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:18:49.612   875   886 D WifiService: setWifiEnabled: true pid=3833, uid=10000
08-30 16:18:49.613   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:18:49.625   875  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:49.644  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:49.651  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:18:49.662  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:18:49.665  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:18:49.668   875  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-30 16:18:49.669   875  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 16:18:49.670   875  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 16:18:49.671   875  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 16:18:49.671   875  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 16:18:49.671   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 16:18:49.671   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 16:18:49.686   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 16:18:49.687   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 16:18:49.688   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:49.689   875  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
08-30 16:18:49.689   875  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 16:18:49.748   875  1317 E native  : do suspend true
,08-30 16:18:49.748   875  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 16:18:49.761   875  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 16:18:49.780   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:18:51.183   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:18:51.311   875  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.12 rxSuccessRate=11.00 delta 1000 -> 994
,08-30 16:18:51.312   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 16:18:51.312   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:51.330   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 16:18:51.401   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 16:18:51.405  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 16:18:51.845  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:18:51.890  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:18:51.890  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 16:18:51.895   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:18:51.908   875  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:18:51.909   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 16:18:51.913   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:51.945   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:18:51.964   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:51.967   875  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 16:18:51.978   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 16:18:52.008   875  4267 D DhcpClient: Receive thread started
,08-30 16:18:52.105   875  1317 E native  : do suspend false
,08-30 16:18:52.135   875  1860 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 16:18:52.149   875  4267 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-30 16:18:52.150   875  1860 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-30 16:18:52.154   875  1860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 16:18:52.168   875  4267 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 16:18:52.170   875  1860 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 16:18:52.175   373   873 D CommandListener: Setting iface cfg
,08-30 16:18:52.187   875  1860 D DhcpClient: Scheduling renewal in 86399s
,08-30 16:18:52.188   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 16:18:52.193   875  1317 E native  : do suspend true
,08-30 16:18:52.212   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 16:18:52.213   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 16:18:52.214   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:18:52.216   875  1319 D ConnectivityService: Adding iface wlan0 to network 102
08-30 16:18:52.218   875  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:18:52.279   875  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 16:18:52.280   875  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 16:18:52.284   875  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 16:18:52.287   875  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 16:18:52.288   875  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 16:18:52.298   875  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 16:18:52.304   875  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 16:18:52.304   875  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 16:18:52.304   875  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 16:18:52.305   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:18:52.305   875  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 16:18:52.305   875  1319 D ConnectivityService:    accepting network in place of null
,08-30 16:18:52.307   875  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:18:52.318   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209765, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:18:52.336   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:52.367   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:18:52.373   875  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 16:18:52.373   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:52.381   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:18:52.384   875  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 16:18:52.394   875  4265 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:52.405  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:18:52.408  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:52.412  1737  1737 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:52.414  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:18:52.417  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:52.422  1737  1737 D SystemUpdateService: onCreate
,08-30 16:18:52.426  1737  1737 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:18:52.444  1737  4276 I SystemUpdateService: active receiver: enabled
,08-30 16:18:52.447  1737  1737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 16:18:52.448  1737  2426 I iu.UploadsManager: num queued entries: 0
,08-30 16:18:52.457  1737  1737 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:18:52.458  1737  1737 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:18:52.460  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:18:52.470  1737  4278 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 16:18:52.470  1737  4278 W BaseAppContext: Using Auth Proxy for data requests.
08-30 16:18:52.470  3984  3984 D SprintDMHelper: simOperator: 
08-30 16:18:52.470  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:18:52.481  1737  4278 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:18:52.483   875  4265 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:18:52 GMT], X-Android-Received-Millis=[1472566732482], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472566732435]}
08-30 16:18:52.484   875  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 16:18:52.484   875  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 16:18:52.484   875  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 16:18:52.487   875  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 16:18:52.488  1737  2426 I iu.UploadsManager: num updated entries: 0
,08-30 16:18:52.505  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:18:52.510  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:18:52.511  1737  4276 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:18:52.533  1737  2426 I iu.SyncManager: NEXT; no task
08-30 16:18:52.533  1737  4276 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 16:18:52.533  1737  4276 I SystemUpdateService: now status is 0 (complete)
08-30 16:18:52.533  1737  4276 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:18:52.533  1737  4276 I SystemUpdateService: file has been verified
08-30 16:18:52.534  1737  4276 I SystemUpdateService: OTA package size = 12249756
,08-30 16:18:52.576  1737  4276 I SystemUpdateService: showing system update notification
,08-30 16:18:52.609  2471  4281 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 16:18:52.614  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 16:18:52.614  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 16:18:52.615  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:18:52.615  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:18:52.618  1737  1737 D SystemUpdateService: onDestroy
,08-30 16:18:52.647  1737  4278 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-30 16:18:52.661   875   884 I art     : Background partial concurrent mark sweep GC freed 45054(2MB) AllocSpace objects, 6(132KB) LOS objects, 33% free, 29MB/43MB, paused 1.266ms total 109.902ms
,08-30 16:18:52.848  1884  1937 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 16:18:52.848  1884  1937 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 16:18:52.883  1511  1511 I ConfigService: onCreate
,08-30 16:18:53.374   875  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:18:54.637  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:18:54.644  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:18:54.645  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:18:54.646  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed808f removed from the list
08-30 16:18:54.646  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:18:54.646  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:18:54.647  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:18:54.659  3833  4290 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-30 16:18:54.659  3833  4290 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 16:18:57.667  3833  4291 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-30 16:18:57.668  3833  4290 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 16:18:57.668  3833  4290 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 16:18:57.668  3833  4291 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 16:18:57.670  3833  4290 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 16:18:57.671  3833  4291 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 16:18:57.672  3833  4290 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 16:18:57.673  3833  4291 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 16:18:57.676  3833  4290 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 16:18:57.676  3833  4293 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Sender)
08-30 16:18:57.676  3833  4291 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 16:18:57.678  3833  4294 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Sender)
,08-30 16:18:57.680  3833  4296 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: IncomingSocketThread/Receiver)
,08-30 16:18:57.681  3833  4295 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Receiver)
,08-30 16:18:57.682  3833  4295 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: OutgoingSocketThread/Receiver)
08-30 16:18:57.682  3833  4295 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 16:18:57.682  3833  4295 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 16:18:57.682  3833  4296 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: IncomingSocketThread/Receiver)
08-30 16:18:57.683  3833  4296 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 16:18:57.683  3833  4296 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 16:18:57.952  1511  1511 I ConfigService: onDestroy
,08-30 16:19:00.310   875  1319 D ConnectivityService: handlePromptUnvalidated 102
,08-30 16:19:00.665  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 16:19:00.668  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 16:19:00.674  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7344d4c Bundle[{}]
,08-30 16:19:00.675  3833  3884 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:19:00.675  3833  3884 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 16:19:00.676  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 16:19:00.676  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 16:19:00.677  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 16:19:00.677  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 16:19:00.681  3833  3884 I System.out: Running OutgoingSocketThread
,08-30 16:19:00.683  3833  4298 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 16:19:00.683  3833  4298 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 16:19:03.694  3833  4298 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 16:19:03.695  3833  4298 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 16:19:03.695  3833  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 16:19:03.697  3833  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 16:19:03.699  3833  4299 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-30 16:19:03.699  3833  4299 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 16:19:03.700  3833  4299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 16:19:03.702  3833  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: OutgoingSocketThread/Sender)
08-30 16:19:03.702  3833  4298 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 16:19:03.703  3833  4299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 16:19:03.707  3833  4303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Sender)
,08-30 16:19:03.708  3833  4299 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 16:19:03.713  3833  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Receiver)
,08-30 16:19:03.714  3833  4302 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: OutgoingSocketThread/Receiver)
08-30 16:19:03.715  3833  4304 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: IncomingSocketThread/Receiver)
08-30 16:19:03.715  3833  4302 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 16:19:03.715  3833  4302 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 16:19:03.716  3833  4304 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: IncomingSocketThread/Receiver)
08-30 16:19:03.716  3833  4304 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 16:19:03.717  3833  4304 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 16:19:06.697  3833  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,08-30 16:19:06.699  3833  3884 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 16:19:06.700  3833  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 455)
,08-30 16:19:06.705  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:19:06.706  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce57f1c added. We now have 3 listener(s)
,08-30 16:19:06.707  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:19:06.707  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:19:06.708  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:19:06.708  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:19:06.708  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@619d725 added. We now have 4 listener(s)
08-30 16:19:06.708  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:19:06.709  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:19:06.712  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:19:06.722  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:19:06.728  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:19:06.728  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:19:06.729  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:19:06.730  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:19:06.730  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:19:06.730  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:06.730  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:06.731  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:19:06.731  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:19:06.731  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce57f1c removed from the list
08-30 16:19:06.731  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:06.732  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@619d725 removed from the list
,08-30 16:19:06.732  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:19:06.736  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:19:06.736  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:19:06.736  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:06.738  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:06.738  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:06.741  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:06.741  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:19:06.741  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:06.742  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@619d725 not in the list
08-30 16:19:06.742  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:06.742  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:06.745  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:19:06.745  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:06.745  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:19:06.746  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@619d725 not in the list
08-30 16:19:06.746  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:19:06.746  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:06.747  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:06.747  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce57f1c not in the list
,08-30 16:19:06.749  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:19:06.749  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4b96ab added. We now have 3 listener(s)
,08-30 16:19:06.755  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:19:06.756  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:19:06.756  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:19:06.756  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:19:06.757  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e597108 added. We now have 4 listener(s)
08-30 16:19:06.757  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:19:06.758  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:19:06.764  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:19:06.773  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:19:06.778  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:19:06.778  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:19:06.778  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:19:06.778  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:19:06.778  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:19:06.779  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:19:06.779  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:19:06.782  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:19:06.783  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:19:06.784  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:19:06.787  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:19:06.791  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:19:06.792  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:19:06.793  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:19:06.801  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:19:06.801  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:19:06.801  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:19:06.802  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:19:06.808  4212  4222 D BtGatt.GattService: registerClient() - UUID=105bcd0a-054d-40f9-9fae-4c23a4fb4e81
,08-30 16:19:06.810  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=105bcd0a-054d-40f9-9fae-4c23a4fb4e81, clientIf=5
,08-30 16:19:06.811  3833  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:19:06.812  4212  4241 D BtGatt.GattService: start scan with filters
,08-30 16:19:06.817  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:19:06.817  4212  4231 D BtGatt.ScanManager: handling starting scan
,08-30 16:19:06.817  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:19:06.818  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:19:06.818  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:19:06.819  4212  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9585f20
,08-30 16:19:06.829  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:19:06.830  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:19:06.831  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:19:06.831  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-30 16:19:06.831  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:06.833  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:19:06.837  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:19:06.844  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 16:19:06.845  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:19:06.845  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:19:06.845  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:06.845  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 16:19:06.845  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:19:06.846  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:19:06.846  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 16:19:06.846  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:19:06.846  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:19:06.846  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:19:06.846  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:19:06.846  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:06.847  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:19:06.847  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:19:06.847  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:19:06.848  4212  4222 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:19:06.849  4212  4241 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:19:06.849  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:19:06.850  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:19:06.850  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:19:06.850  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:19:06.850  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:19:06.851  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:19:06.851  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:19:06.851  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:19:06.851  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:19:06.852  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:19:06.853  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:19:06.853  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:19:06.853  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:19:06.865  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:19:06.865  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:06.873  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 16:19:06.873  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:06.882  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:19:06.882  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:06.883  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:19:06.892  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 16:19:06.892  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:06.893  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:19:06.901  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 16:19:06.901  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:07.355  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 16:19:07.355  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:19:07.355  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 16:19:09.854  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:19:09.855  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:19:09.855  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:19:09.856  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:09.856  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:09.856  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:19:09.857  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:19:09.857  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4b96ab removed from the list
08-30 16:19:09.857  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:09.858  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e597108 removed from the list
08-30 16:19:09.858  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:19:09.858  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:09.860  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:09.860  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:09.863  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:09.864  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:09.864  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:19:09.864  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e597108 not in the list
08-30 16:19:09.865  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:09.865  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:19:09.868  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:09.868  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:19:09.869  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:09.869  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e597108 not in the list
08-30 16:19:09.869  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:19:09.870  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:09.870  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:09.870  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4b96ab not in the list
08-30 16:19:09.873  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:19:09.873  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eccc5dd added. We now have 3 listener(s)
,08-30 16:19:09.876  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:19:09.876  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:19:09.876  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:19:09.876  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:19:09.876  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767c552 added. We now have 4 listener(s)
08-30 16:19:09.876  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:19:09.877  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:19:09.880  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:19:09.886  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:19:09.889  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:19:09.889  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:19:09.889  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 16:19:09.890  3833  3884 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 16:19:09.890  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-30 16:19:09.892  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:19:09.893  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 16:19:09.893  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 16:19:09.893  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 16:19:09.893  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:09.894  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 16:19:09.895  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 16:19:09.895  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 16:19:09.895  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 16:19:09.895  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 16:19:09.896  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:09.896  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:19:09.900  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:19:09.900  3833  4305 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:19:09.901  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 16:19:09.903  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:19:09.903  3833  4305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 16:19:09.903  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:19:09.908  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:19:09.909  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:19:09.909  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:19:09.911  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 16:19:09.912  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:19:09.912  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-30 16:19:09.913  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 16:19:09.914  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 16:19:09.914  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 16:19:09.915  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:19:09.917  4212  4223 D BtGatt.GattService: registerClient() - UUID=2a1757ea-c8d9-4c50-907c-8bc822d849c3
08-30 16:19:09.918  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=2a1757ea-c8d9-4c50-907c-8bc822d849c3, clientIf=5
08-30 16:19:09.919  3833  3844 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 16:19:09.921  4212  4230 D BtGatt.AdvertiseManager: message : 0
,08-30 16:19:09.925  4212  4230 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 16:19:09.941  4212  4228 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 16:19:09.949  4212  4228 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 16:19:09.951  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-30 16:19:09.951  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:19:09.953  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:19:09.955  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 16:19:09.956  3833  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-30 16:19:09.956  3833  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 16:19:09.956  3833  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 16:19:09.957  3833  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 16:19:09.957  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 16:19:09.957  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 16:19:09.965  3833  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 16:19:09.965  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 16:19:10.466  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 16:19:10.467  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:19:10.467  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,08-30 16:19:12.959  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:19:12.959  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-30 16:19:12.960  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:19:12.960  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 16:19:12.960  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 16:19:12.961  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 16:19:12.962  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 16:19:12.962  3833  4305 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 16:19:12.963  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 16:19:12.963  3833  4305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 16:19:12.963  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:19:12.963  3833  4305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:19:12.963  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:19:12.963  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:19:12.964  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:19:12.964  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:19:12.964  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:19:12.967  3833  3884 D BluetoothAdapter: STATE_ON
08-30 16:19:12.967  3833  3884 D BluetoothLeScanner: could not find callback wrapper
08-30 16:19:12.967  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:19:12.968  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 16:19:12.970  4212  4230 D BtGatt.AdvertiseManager: message : 1
08-30 16:19:12.972  4212  4230 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 16:19:12.982  4212  4228 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
08-30 16:19:12.982  4212  4228 D BtGatt.GattService: Client app is not null!
08-30 16:19:12.984  4212  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:19:12.986  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:19:12.986  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 16:19:12.986  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 16:19:12.987  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 16:19:12.987  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 16:19:12.990  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:19:12.990  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:19:12.991  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:19:12.992  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 16:19:12.995  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:19:12.996  3833  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 16:19:12.996  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:12.996  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:19:12.997  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:19:12.997  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:19:12.997  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eccc5dd removed from the list
08-30 16:19:12.997  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:19:12.997  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:12.998  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767c552 removed from the list
,08-30 16:19:12.998  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:19:12.998  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:19:12.998  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:13.000  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:13.000  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:13.002  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:13.002  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:13.002  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:13.003  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767c552 not in the list
08-30 16:19:13.003  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:13.003  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:13.004  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:13.004  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:13.004  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:13.004  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@767c552 not in the list
08-30 16:19:13.004  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:13.004  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:13.004  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:13.004  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eccc5dd not in the list
08-30 16:19:13.005  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:19:13.005  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f75ab7f added. We now have 3 listener(s)
,08-30 16:19:13.007  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:19:13.007  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:19:13.007  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:19:13.008  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:19:13.008  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294e74c added. We now have 4 listener(s)
08-30 16:19:13.008  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:19:13.008  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:19:13.010  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:19:13.016  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:19:13.018  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:19:13.018  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:19:13.019  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:19:13.019  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 16:19:13.019  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:19:13.019  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:19:13.020  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:19:13.021  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:19:13.022  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:19:13.023  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:19:13.023  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:19:13.026  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:19:13.027  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:19:13.027  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:19:13.030  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 16:19:13.030  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:19:13.030  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:19:13.031  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:19:13.033  4212  4248 D BtGatt.GattService: registerClient() - UUID=9b4e18d3-cd59-4e82-a4cd-fffdf5b4cf82
08-30 16:19:13.033  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=9b4e18d3-cd59-4e82-a4cd-fffdf5b4cf82, clientIf=5
,08-30 16:19:13.034  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:19:13.035  4212  4223 D BtGatt.GattService: start scan with filters
,08-30 16:19:13.039  4212  4231 D BtGatt.ScanManager: handling starting scan
,08-30 16:19:13.039  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 16:19:13.039  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:19:13.039  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:19:13.040  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:19:13.042  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:19:13.042  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:19:13.042  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:19:13.044  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:19:13.047  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:19:13.047  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:13.047  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:19:13.053  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:19:13.053  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:13.053  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:19:13.054  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:19:13.066  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:19:13.066  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:13.073  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:19:13.073  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:13.498  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:19:13.544  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 16:19:13.544  3833  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:19:13.544  3833  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 16:19:13.823   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:19:14.581  4212  4212 D BtGatt.ScanManager: awakened up at time 232028
,08-30 16:19:14.587  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:19:14.631  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,08-30 16:19:14.631  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:19:14.631  4212  4228 D BtGatt.GattService: current time is 232078760283
,08-30 16:19:14.632  4212  4228 D BtGatt.GattService: Batch record : [114, 77, -70, 94, -28, 79, 1, -128, -60, 30, 0, 0, 0, 35, 97, 126, -92, 22, -56, 1, -128, -90, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 114, 77, -70, 94, -28, 79, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 53, 33, -121, 80, 73, -44, 1, 0, -104, 14, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 10, -15, -18, 2, 2, -29, 21, 63, -65, 116, 120, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 16:19:14.633  4212  4228 D BtGatt.GattService: ScanRecord : []
08-30 16:19:14.634  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 16:19:14.634  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 16:19:14.634  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 16:19:14.635  4212  4228 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-30 16:19:14.635  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 16:19:14.635  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 10, -15, -18, 2, 2, -29, 21, 63, -65, 116, 120, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-30 16:19:14.636  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 16:19:14.636  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 16:19:14.640  3833  3833 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
08-30 16:19:14.640  3833  3833 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-30 16:19:16.055  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:19:16.056  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:19:16.056  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:19:16.056  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:16.057  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 16:19:16.057  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 16:19:16.057  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:19:16.057  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 16:19:16.058  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:19:16.058  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 16:19:16.058  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:19:16.061  3833  3884 D BluetoothAdapter: STATE_ON
,08-30 16:19:16.064  4212  4222 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:19:16.066  4212  4248 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:19:16.067  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:19:16.067  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:19:16.068  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 16:19:16.068  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:19:16.068  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:19:16.074  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:19:16.075  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 16:19:16.075  4212  4212 D BtGatt.ScanManager: awakened up at time 233522
,08-30 16:19:16.075  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:19:16.077  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:19:16.079  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:19:16.079  3833  3884 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-30 16:19:16.085  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:19:16.085  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:19:16.085  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:16.085  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:19:16.085  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:19:16.085  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:19:16.086  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:16.086  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:16.086  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:19:16.086  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:19:16.086  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f75ab7f removed from the list
08-30 16:19:16.086  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:16.086  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294e74c removed from the list
08-30 16:19:16.087  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:19:16.087  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.087  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:16.087  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.088  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:19:16.088  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:16.088  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:16.088  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294e74c not in the list
08-30 16:19:16.088  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:16.089  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.089  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:16.090  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:16.090  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:16.090  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@294e74c not in the list
08-30 16:19:16.090  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:16.090  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:16.090  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.090  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f75ab7f not in the list
08-30 16:19:16.091  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:19:16.091  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dee976 added. We now have 3 listener(s)
08-30 16:19:16.093  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:19:16.093  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:16.093  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:19:16.093  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:19:16.094  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:19:16.094  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:19:16.094  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:19:16.094  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94f8b77 added. We now have 4 listener(s)
08-30 16:19:16.094  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:19:16.095  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:19:16.097  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:19:16.103  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:19:16.105  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:19:16.105  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:19:16.106  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:19:16.106  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:19:16.106  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:19:16.106  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:16.106  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:19:16.106  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 16:19:16.106  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:19:16.106  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dee976 removed from the list
08-30 16:19:16.107  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:16.107  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94f8b77 removed from the list
,08-30 16:19:16.107  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-30 16:19:16.107  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:19:16.108  4212  4228 D BtGatt.GattService: current time is 233555324660
08-30 16:19:16.108  4212  4228 D BtGatt.GattService: Batch record : [114, 77, -70, 94, -28, 79, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 16:19:16.108  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:19:16.108  4212  4228 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-30 16:19:16.108  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 16:19:16.109  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 16:19:16.109  4212  4228 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 16:19:16.110  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:19:16.110  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:19:16.111  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.111  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:16.111  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.112  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:16.112  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:16.112  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:19:16.112  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94f8b77 not in the list
08-30 16:19:16.112  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:16.112  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.113  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:19:16.113  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:19:16.113  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:19:16.114  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94f8b77 not in the list
,08-30 16:19:16.114  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:19:16.114  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:19:16.114  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:19:16.114  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dee976 not in the list
08-30 16:19:16.115  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-30 16:19:16.115  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:19:16.115  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 16:19:16.115  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:19:16.115  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 16:19:16.115  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:19:16.586  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:19:18.130  3833  4306 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,08-30 16:19:20.128  3833  3884 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 464
,08-30 16:19:20.129  3833  3884 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 464, name: My test thread name)
,08-30 16:19:20.135  3833  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,08-30 16:19:20.136  3833  4307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 465, thread name: My test thread name)
08-30 16:19:20.136  3833  4307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 16:19:20.140  3833  3884 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 16:19:20.148  3833  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 469, name: My test thread name)
,08-30 16:19:20.149  3833  4308 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 469, thread name: My test thread name): Test exception.
08-30 16:19:20.150  3833  4308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 469, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 16:19:20.158  3833  3884 I jxcore-log: Total number of executed tests:  82
08-30 16:19:20.158  3833  3884 I jxcore-log: 
,08-30 16:19:20.159  3833  3884 I jxcore-log: Number of passed tests:  82
08-30 16:19:20.159  3833  3884 I jxcore-log: 
08-30 16:19:20.160  3833  3884 I jxcore-log: Number of failed tests:  0
08-30 16:19:20.160  3833  3884 I jxcore-log: 
,08-30 16:19:20.161  3833  3884 I jxcore-log: Number of ignored tests:  0
08-30 16:19:20.161  3833  3884 I jxcore-log: 
08-30 16:19:20.161  3833  3884 I jxcore-log: Total duration:  101313
08-30 16:19:20.161  3833  3884 I jxcore-log: 
,08-30 16:19:20.170  3833  3884 I jxcore-log: Unit Test app is loaded
08-30 16:19:20.170  3833  3884 I jxcore-log: 
,08-30 16:19:20.178  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.178  3833  3884 I jxcore-log: 
,08-30 16:19:20.183  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.183  3833  3884 I jxcore-log: 
,08-30 16:19:20.185  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.185  3833  3884 I jxcore-log: 
,08-30 16:19:20.186  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.186  3833  3884 I jxcore-log: 
,08-30 16:19:20.187  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 16:19:20.187  3833  3884 I jxcore-log: 
,08-30 16:19:20.189  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:19:20.189  3833  3884 I jxcore-log: 
,08-30 16:19:20.192  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.192  3833  3884 I jxcore-log: 
,08-30 16:19:20.194  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.194  3833  3884 I jxcore-log: 
,08-30 16:19:20.195  3833  3833 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 16:19:20.196  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 16:19:20.196  3833  3884 I jxcore-log: 
08-30 16:19:20.197  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:19:20.197  3833  3884 I jxcore-log: 
,08-30 16:19:20.198  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:19:20.198  3833  3884 I jxcore-log: 
08-30 16:19:20.199  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.199  3833  3884 I jxcore-log: 
,08-30 16:19:20.199  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.199  3833  3884 I jxcore-log: 
08-30 16:19:20.200  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.200  3833  3884 I jxcore-log: 
,08-30 16:19:20.201  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.201  3833  3884 I jxcore-log: 
,08-30 16:19:20.202  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.202  3833  3884 I jxcore-log: 
08-30 16:19:20.203  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.203  3833  3884 I jxcore-log: 
,08-30 16:19:20.205  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.205  3833  3884 I jxcore-log: 
,08-30 16:19:20.206  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.206  3833  3884 I jxcore-log: 
08-30 16:19:20.206  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.206  3833  3884 I jxcore-log: 
,08-30 16:19:20.208  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.208  3833  3884 I jxcore-log: 
08-30 16:19:20.208  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.208  3833  3884 I jxcore-log: 
,08-30 16:19:20.210  3833  4306 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-30 16:19:20.211  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.211  3833  3884 I jxcore-log: 
08-30 16:19:20.212  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.212  3833  3884 I jxcore-log: 
,08-30 16:19:20.212  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.212  3833  3884 I jxcore-log: 
08-30 16:19:20.213  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.213  3833  3884 I jxcore-log: 
08-30 16:19:20.213  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.213  3833  3884 I jxcore-log: 
,08-30 16:19:20.214  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.214  3833  3884 I jxcore-log: 
08-30 16:19:20.214  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.214  3833  3884 I jxcore-log: 
08-30 16:19:20.215  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.215  3833  3884 I jxcore-log: 
,08-30 16:19:20.215  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.215  3833  3884 I jxcore-log: 
08-30 16:19:20.216  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.216  3833  3884 I jxcore-log: 
,08-30 16:19:20.217  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.217  3833  3884 I jxcore-log: 
08-30 16:19:20.217  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.217  3833  3884 I jxcore-log: 
08-30 16:19:20.218  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.218  3833  3884 I jxcore-log: 
,08-30 16:19:20.218  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.218  3833  3884 I jxcore-log: 
08-30 16:19:20.218  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.218  3833  3884 I jxcore-log: 
08-30 16:19:20.219  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.219  3833  3884 I jxcore-log: 
,08-30 16:19:20.220  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.220  3833  3884 I jxcore-log: 
08-30 16:19:20.220  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.220  3833  3884 I jxcore-log: 
08-30 16:19:20.220  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:19:20.220  3833  3884 I jxcore-log: 
,08-30 16:19:20.221  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.221  3833  3884 I jxcore-log: 
08-30 16:19:20.221  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:19:20.221  3833  3884 I jxcore-log: 
08-30 16:19:20.222  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.222  3833  3884 I jxcore-log: 
,08-30 16:19:20.222  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.222  3833  3884 I jxcore-log: 
08-30 16:19:20.223  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.223  3833  3884 I jxcore-log: 
08-30 16:19:20.224  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.224  3833  3884 I jxcore-log: 
,08-30 16:19:20.224  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.224  3833  3884 I jxcore-log: 
08-30 16:19:20.225  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:19:20.225  3833  3884 I jxcore-log: 
08-30 16:19:20.225  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.225  3833  3884 I jxcore-log: 
,08-30 16:19:20.226  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 16:19:20.226  3833  3884 I jxcore-log: 
08-30 16:19:20.226  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.226  3833  3884 I jxcore-log: 
08-30 16:19:20.227  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:19:20.227  3833  3884 I jxcore-log: 
,08-30 16:19:20.227  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 16:19:20.227  3833  3884 I jxcore-log: 
08-30 16:19:20.228  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 16:19:20.228  3833  3884 I jxcore-log: 
08-30 16:19:20.229  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:19:20.229  3833  3884 I jxcore-log: 
08-30 16:19:20.229  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:19:20.229  3833  3884 I jxcore-log: 
,08-30 16:19:20.232  3833  3884 I jxcore-log: My device name is: motorola-Nexus 6
08-30 16:19:20.232  3833  3884 I jxcore-log: 
,08-30 16:19:20.234  3833  3884 I jxcore-log: Running for NATIVE network type
08-30 16:19:20.234  3833  3884 I jxcore-log: 
,08-30 16:19:22.722  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 16:19:22.722  3833  3884 I jxcore-log: 
,08-30 16:19:23.176  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 16:19:23.176  3833  3884 I jxcore-log: 
,08-30 16:19:23.203  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 16:19:23.203  3833  3884 I jxcore-log: 
,08-30 16:19:23.349   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=240796, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 16:19:24.583  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 16:19:24.583  3833  3884 I jxcore-log: 
,08-30 16:19:24.819  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-30 16:19:24.819  3833  3884 I jxcore-log: 
,08-30 16:19:24.825  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-30 16:19:24.825  3833  3884 I jxcore-log: 
,08-30 16:19:24.832  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
08-30 16:19:24.832  3833  3884 I jxcore-log: 
,08-30 16:19:24.911  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-30 16:19:24.911  3833  3884 I jxcore-log: 
,08-30 16:19:24.931  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-30 16:19:24.931  3833  3884 I jxcore-log: 
,08-30 16:19:24.937  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
08-30 16:19:24.937  3833  3884 I jxcore-log: 
,08-30 16:19:25.873  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
08-30 16:19:25.873  3833  3884 I jxcore-log: 
,08-30 16:19:26.040  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-30 16:19:26.040  3833  3884 I jxcore-log: 
,08-30 16:19:26.373  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-30 16:19:26.373  3833  3884 I jxcore-log: 
,08-30 16:19:26.386  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-30 16:19:26.386  3833  3884 I jxcore-log: 
,08-30 16:19:26.395  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-30 16:19:26.395  3833  3884 I jxcore-log: 
,08-30 16:19:26.402  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-30 16:19:26.402  3833  3884 I jxcore-log: 
,08-30 16:19:26.443  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-30 16:19:26.443  3833  3884 I jxcore-log: 
,08-30 16:19:26.491  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-30 16:19:26.491  3833  3884 I jxcore-log: 
,08-30 16:19:26.499  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-30 16:19:26.499  3833  3884 I jxcore-log: 
,08-30 16:19:26.507  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-30 16:19:26.507  3833  3884 I jxcore-log: 
,08-30 16:19:26.527  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-30 16:19:26.527  3833  3884 I jxcore-log: 
,08-30 16:19:26.532  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-30 16:19:26.532  3833  3884 I jxcore-log: 
,08-30 16:19:26.539  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-30 16:19:26.539  3833  3884 I jxcore-log: 
,08-30 16:19:26.555  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-30 16:19:26.555  3833  3884 I jxcore-log: 
,08-30 16:19:26.582  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-30 16:19:26.582  3833  3884 I jxcore-log: 
,08-30 16:19:26.593  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-30 16:19:26.593  3833  3884 I jxcore-log: 
,08-30 16:19:26.607  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-30 16:19:26.607  3833  3884 I jxcore-log: 
,08-30 16:19:26.618  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-30 16:19:26.618  3833  3884 I jxcore-log: 
,08-30 16:19:26.634  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-30 16:19:26.634  3833  3884 I jxcore-log: 
,08-30 16:19:26.645  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-30 16:19:26.645  3833  3884 I jxcore-log: 
,08-30 16:19:26.651  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-30 16:19:26.651  3833  3884 I jxcore-log: 
,08-30 16:19:26.658  3833  3884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-30 16:19:26.658  3833  3884 I jxcore-log: 
,08-30 16:19:26.672  3833  3884 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-30 16:19:26.673  3833  3884 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-30 16:19:26.673  3833  3884 I jxcore-log: 
,08-30 16:19:31.146  3621  4310 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 16:19:31.185  3621  4311 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 16:19:31.217  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:19:31.223  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:19:31.279  1511  2243 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:19:31.279  1511  2243 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 16:19:31.279  1511  2243 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:19:31.280  1511  2243 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:19:31.310  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:19:31.312  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:19:31.343  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:19:31.344  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 16:19:31.344  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:19:31.344  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:19:31.364  3621  4311 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 16:19:31.365  3621  4310 E BooksSync: Soft error
08-30 16:19:31.365  3621  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:19:31.365  3621  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:19:31.365  3621  4310 E BooksSync: Sync error
08-30 16:19:31.365  3621  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:19:31.365  3621  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:19:31.365  3621  4310 I BooksSync: Finished books sync
,08-30 16:19:31.377   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 248474, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:19:44.365   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:19:50.577   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 16:19:56.806  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:19:56.808  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:19:56.879  4078  4312 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:19:56.907  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 16:19:56.907  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-30 16:19:56.908  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:19:56.908  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:19:56.925  4078  4312 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:20:00.363  1511  2115 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 16:20:02.297  3621  4316 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 16:20:02.324  3621  4317 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 16:20:02.333  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:02.338  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:02.367  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 16:20:02.368  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:20:02.368  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:20:02.368  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:02.401  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:02.404  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:02.438  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:20:02.439  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 16:20:02.439  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:20:02.439  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:02.465  3621  4317 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 16:20:02.466  3621  4316 E BooksSync: Soft error
08-30 16:20:02.466  3621  4316 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:20:02.466  3621  4316 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:20:02.467  3621  4316 E BooksSync: Sync error
08-30 16:20:02.467  3621  4316 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:20:02.467  3621  4316 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:20:02.468  3621  4316 I BooksSync: Finished books sync
,08-30 16:20:02.477   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279636, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:20:11.564   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:20:17.430   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 16:20:27.355  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:27.357  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:27.373  4078  4322 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:20:27.400  1511  2243 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-30 16:20:27.400  1511  2243 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 16:20:27.400  1511  2243 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:20:27.400  1511  2243 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:20:27.423  4078  4322 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:20:32.817  3646  4333 V KeepSync: Connecting to GoogleApiClient
,08-30 16:20:32.818   875   886 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 16:20:32.834  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:32.835  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:20:32.856  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:20:32.856  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 16:20:32.856  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:20:32.856  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:32.874  3570  4334 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 16:20:32.874  3570  4334 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at blb.a(PG:3937)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at czp.a(PG:18188)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:20:32.874  3570  4334 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	... 12 more
08-30 16:20:32.874  3570  4334 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at fal.a(PG:38)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:20:32.874  3570  4334 E HttpOperation: 	... 14 more
,08-30 16:20:32.964  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:20:32.964  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:20:32.964  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:20:32.964  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:32.966  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-30 16:20:32.966  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 16:20:32.966  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:20:32.966  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:33.019  3570  4334 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 16:20:33.019  3570  4334 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at hec.a(PG:42)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at hee.a(PG:102)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at czr.a(PG:65)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at kka.a(PG:108)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at czp.a(PG:19176)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:20:33.019  3570  4334 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	... 15 more
08-30 16:20:33.019  3570  4334 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at fal.a(PG:38)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:20:33.019  3570  4334 E HttpOperation: 	... 17 more
08-30 16:20:33.019  3570  4334 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 16:20:33.019  3570  4334 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at hec.a(PG:42)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at hee.a(PG:102)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at czr.a(PG:65)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at kka.a(PG:108)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	... 15 more
08-30 16:20:33.019  3570  4334 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at fal.a(PG:38)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 16:20:33.019  3570  4334 E ExperimentLoader: 	... 17 more
,08-30 16:20:33.024  1737  4335 V BaseAuthAsyncOperation: access token request failed,
08-30 16:20:33.027  3646  4333 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 16:20:33.110  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 16:20:33.111  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 16:20:33.111  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:20:33.111  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:20:33.132  3646  4333 E KeepSync: IOException
08-30 16:20:33.132  3646  4333 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 16:20:33.132  3646  4333 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:20:33.132  3646  4333 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 16:20:33.132  3646  4333 E KeepSync: 	... 10 more
,08-30 16:20:33.133  3646  4333 W KeepSync: Sync result 2
,08-30 16:20:33.150   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 287898, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:20:33.188   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 284957, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:20:54.817   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=332264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:21:02.737   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:21:04.054  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:21:04.059  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:21:04.106  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-30 16:21:04.106  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 16:21:04.106  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:04.106  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:04.129  3570  4339 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 16:21:04.129  3570  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at blb.a(PG:3937)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at czp.a(PG:18188)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:21:04.129  3570  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	... 12 more
08-30 16:21:04.129  3570  4339 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at fal.a(PG:38)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:21:04.129  3570  4339 E HttpOperation: 	... 14 more
,08-30 16:21:04.208  1511  2243 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-30 16:21:04.208  1511  2243 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 16:21:04.208  1511  2243 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:04.208  1511  2243 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:04.233  3570  4339 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 16:21:04.233  3570  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at hec.a(PG:42)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at hee.a(PG:102)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at czr.a(PG:65)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at kka.a(PG:108)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at czp.a(PG:19176)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:21:04.233  3570  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	... 15 more
08-30 16:21:04.233  3570  4339 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at fal.a(PG:38)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:21:04.233  3570  4339 E HttpOperation: 	... 17 more
08-30 16:21:04.233  3570  4339 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 16:21:04.233  3570  4339 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at hec.a(PG:42)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at hee.a(PG:102)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at czr.a(PG:65)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at kka.a(PG:108)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	... 15 more
08-30 16:21:04.233  3570  4339 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at fal.a(PG:38)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 16:21:04.233  3570  4339 E ExperimentLoader: 	... 17 more
,08-30 16:21:04.335   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 341138, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:21:04.384  3621  4341 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 16:21:04.402  3621  4342 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 16:21:04.435  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 16:21:04.435  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:21:04.435  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:21:04.435  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:04.484  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:21:04.484  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:21:04.485  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:04.485  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:04.517  3621  4342 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 16:21:04.518  3621  4341 E BooksSync: Soft error
08-30 16:21:04.518  3621  4341 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:21:04.518  3621  4341 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:21:04.519  3621  4341 E BooksSync: Sync error
08-30 16:21:04.519  3621  4341 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:21:04.519  3621  4341 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 16:21:04.519  3621  4341 I BooksSync: Finished books sync
,08-30 16:21:04.534   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 341548, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:21:04.588  3646  4343 V KeepSync: Connecting to GoogleApiClient
08-30 16:21:04.589   875  2001 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 16:21:04.668  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 16:21:04.668  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 16:21:04.668  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:04.668  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:04.700  1737  4344 V BaseAuthAsyncOperation: access token request failed
,08-30 16:21:04.701  3646  4343 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 16:21:04.759  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 16:21:04.759  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 16:21:04.759  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:04.759  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:04.775  3646  4343 E KeepSync: IOException
08-30 16:21:04.775  3646  4343 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 16:21:04.775  3646  4343 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:21:04.775  3646  4343 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 16:21:04.775  3646  4343 E KeepSync: 	... 10 more
,08-30 16:21:04.775  3646  4343 W KeepSync: Sync result 2
,08-30 16:21:04.785   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 341827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:21:05.398  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:21:05.470  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 16:21:05.470  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 16:21:05.470  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:05.471  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:05.515  1511  1522 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-30 16:21:05.515  1511  1522 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-30 16:21:05.515  1511  1522 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-30 16:21:05.515  1511  1522 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-30 16:21:05.515  1511  1522 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-30 16:21:05.515  1511  1522 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-30 16:21:05.515  1511  1522 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 16:21:05.530  3529  3559 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-30 16:21:05.530  3529  3559 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-30 16:21:05.530  3529  3559 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-30 16:21:05.530  3529  3559 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-30 16:21:05.530  3529  3559 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-30 16:21:05.530  3529  3559 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-30 16:21:05.530  3529  3559 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-30 16:21:27.590  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:21:27.592  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:21:27.612  4078  4348 V GoogleAuthProtoRequest: [352] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:21:27.637  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 16:21:27.638  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 16:21:27.638  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:21:27.638  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:21:27.654  4078  4348 W ExperimentUpdateService: [352] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: [352] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:21:27.655  4078  4348 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:21:43.831   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:21:52.884   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=390331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:22:05.647  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:22:05.652  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:22:05.694  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:22:05.694  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:22:05.694  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:22:05.695  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:22:05.720  3570  4353 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 16:22:05.720  3570  4353 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at blb.a(PG:3937)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at czp.a(PG:18188)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:22:05.720  3570  4353 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	... 12 more
08-30 16:22:05.720  3570  4353 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at fal.a(PG:38)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:22:05.720  3570  4353 E HttpOperation: 	... 14 more
,08-30 16:22:05.756  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:22:05.756  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:22:05.757  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:22:05.757  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:22:05.771  3570  4353 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 16:22:05.771  3570  4353 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at hec.a(PG:42)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at hee.a(PG:102)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at czr.a(PG:65)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at kka.a(PG:108)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at czp.a(PG:19176)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:22:05.771  3570  4353 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	... 15 more
08-30 16:22:05.771  3570  4353 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at fal.a(PG:38)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:22:05.771  3570  4353 E HttpOperation: 	... 17 more
,08-30 16:22:05.771  3570  4353 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 16:22:05.771  3570  4353 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at hec.a(PG:42)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at hee.a(PG:102)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at czr.a(PG:65)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at kka.a(PG:108)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	... 15 more
08-30 16:22:05.771  3570  4353 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at fal.a(PG:38)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 16:22:05.771  3570  4353 E ExperimentLoader: 	... 17 more
,08-30 16:22:05.883   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 402787, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:22:08.897   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=406343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:22:17.950   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=415397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:22:33.058  1511  2115 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 16:22:33.964   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:22:36.126  3646  4356 V KeepSync: Connecting to GoogleApiClient
08-30 16:22:36.126   875  1401 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 16:22:36.167  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:22:36.172  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:22:36.195  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 16:22:36.195  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 16:22:36.195  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:22:36.195  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:22:36.214  1737  4357 V BaseAuthAsyncOperation: access token request failed
,08-30 16:22:36.215  3646  4356 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 16:22:36.269  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 16:22:36.269  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 16:22:36.269  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:22:36.269  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:22:36.290  3646  4356 E KeepSync: IOException
08-30 16:22:36.290  3646  4356 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 16:22:36.290  3646  4356 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:22:36.290  3646  4356 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 16:22:36.290  3646  4356 E KeepSync: 	... 10 more
,08-30 16:22:36.290  3646  4356 W KeepSync: Sync result 2
,08-30 16:22:36.300   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 404691, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:22:43.017   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:22:59.031   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=456478, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:23:07.874  3621  4359 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 16:23:07.912  3621  4360 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 16:23:07.927  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:23:07.930  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:23:07.978  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:23:07.978  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:23:07.979  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:23:07.979  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:23:08.033  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:23:08.038  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:23:08.083   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=465530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:23:08.091  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:23:08.091  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:23:08.091  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:23:08.092  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:23:08.128  3621  4360 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 16:23:08.130  3621  4359 E BooksSync: Soft error
08-30 16:23:08.130  3621  4359 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:23:08.130  3621  4359 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:23:08.130  3621  4359 E BooksSync: Sync error
08-30 16:23:08.130  3621  4359 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:23:08.130  3621  4359 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 16:23:08.130  3621  4359 I BooksSync: Finished books sync
,08-30 16:23:08.145   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 465229, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:23:24.097   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=481544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:23:27.833  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:23:27.836  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:23:27.850  4078  4362 V GoogleAuthProtoRequest: [353] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:23:27.879  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 16:23:27.879  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 16:23:27.880  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:23:27.880  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:23:27.916  4078  4362 W ExperimentUpdateService: [353] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: [353] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:23:27.917  4078  4362 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:23:33.151   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=490597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:23:49.164   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=506611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:23:57.497   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:24:08.199  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:24:08.201  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:24:08.233  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:24:08.234  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:24:08.234  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:24:08.234  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:24:08.248  3570  4366 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 16:24:08.248  3570  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at blb.a(PG:3937)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at czp.a(PG:18188)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:24:08.248  3570  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	... 12 more
08-30 16:24:08.248  3570  4366 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at fal.a(PG:38)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:24:08.248  3570  4366 E HttpOperation: 	... 14 more
,08-30 16:24:08.322  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 16:24:08.323  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 16:24:08.323  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:24:08.323  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:24:08.344  3570  4366 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 16:24:08.344  3570  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jdm.a(PG:82)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jcs.o(PG:406)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jcn.a(PG:1379)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jcs.i(PG:143)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at hec.a(PG:42)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at hee.a(PG:102)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at czr.a(PG:65)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at kka.a(PG:108)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at czp.a(PG:19176)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at czp.a(PG:9081)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at czq.run(PG:1686)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:24:08.344  3570  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jdj.a(PG:4091)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jdj.a(PG:1125)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jdm.a(PG:77)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	... 15 more
08-30 16:24:08.344  3570  4366 E HttpOperation: Caused by: faj: BadAuthentication
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at fal.a(PG:38)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	at jdj.a(PG:4089)
08-30 16:24:08.344  3570  4366 E HttpOperation: 	... 17 more
,08-30 16:24:08.345  3570  4366 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 16:24:08.345  3570  4366 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at hec.a(PG:42)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at hee.a(PG:102)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at czr.a(PG:65)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at kka.a(PG:108)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	... 15 more
08-30 16:24:08.345  3570  4366 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at fal.a(PG:38)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 16:24:08.345  3570  4366 E ExperimentLoader: 	... 17 more
,08-30 16:24:08.472   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 525339, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:24:14.230   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=531677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:24:23.324   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=540770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:24:39.350   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=556797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:24:41.338  3646  4370 V KeepSync: Connecting to GoogleApiClient
,08-30 16:24:41.339   875  2013 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 16:24:41.402  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:24:41.407  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:24:41.441  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 16:24:41.441  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-30 16:24:41.441  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:24:41.441  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:24:41.467  1737  4371 V BaseAuthAsyncOperation: access token request failed
,08-30 16:24:41.468  3646  4370 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 16:24:41.536  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-30 16:24:41.536  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 16:24:41.536  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:24:41.536  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:24:41.569  3646  4370 E KeepSync: IOException
08-30 16:24:41.569  3646  4370 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 16:24:41.569  3646  4370 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:24:41.569  3646  4370 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 16:24:41.569  3646  4370 E KeepSync: 	... 10 more
08-30 16:24:41.569  3646  4370 W KeepSync: Sync result 2
,08-30 16:24:41.582   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 558663, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:24:48.377   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=565824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:25:04.417   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=581864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:25:11.043   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=588490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:25:29.430   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=606876, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:25:38.497   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=615944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:25:54.603   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=632050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:26:03.644   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=641090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:26:19.670   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=657117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:26:28.710   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=666157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:26:44.737   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=682184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:26:53.777   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=691223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:27:09.803   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=707250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:27:18.830   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=716277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:27:34.870   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=732317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:27:43.883   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=741330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:27:59.884   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=757330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:28:08.950   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=766397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:28:24.950   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=782397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:28:34.003   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=791450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:28:50.017   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=807464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:28:57.783  3529  3529 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-30 16:28:57.838  1737  4387 I EventLogService: Opted in for usage reporting
,08-30 16:28:57.844  1737  4387 I EventLogService: Aggregate from 1472565537689 (log), 1472565537689 (data)
,08-30 16:28:57.887  1737  4387 W EventLogAggregator: Unknown tag: snet_gcore
,08-30 16:28:57.887  1737  4387 W EventLogAggregator: Unknown tag: snet_launch_service
,08-30 16:28:57.944  1737  4387 I ServiceDumpSys: dumping service [account]
,08-30 16:28:57.953  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:28:57.958  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:28:57.962  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:28:58.001  4078  4389 V GoogleAuthProtoRequest: [354] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:28:58.031  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 16:28:58.031  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-30 16:28:58.032  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:28:58.032  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:28:58.045  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 16:28:58.045  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-30 16:28:58.045  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:28:58.045  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:28:58.052  3529  3529 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-30 16:28:58.059  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:28:58.061  4078  4389 W ExperimentUpdateService: [354] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: [354] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:28:58.062  4078  4389 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:28:58.096  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 16:28:58.097  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 16:28:58.097  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:28:58.097  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:28:58.122  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:28:58.148  1511  4391 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 16:28:58.148  1511  4391 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 16:28:58.148  1511  4391 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:28:58.148  1511  4391 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:28:58.193  3529  3529 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-30 16:28:58.341  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:28:58.372  1511  4391 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 16:28:58.373  1511  4391 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-30 16:28:58.373  1511  4391 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:28:58.373  1511  4391 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:28:58.404  3529  3529 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-30 16:28:58.405  3529  3529 D Finsky  : [1] WearSupportService.startHygiene: disabled
08-30 16:28:58.405  3529  3529 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-30 16:28:58.410  3529  3608 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-30 16:28:58.411  3529  3529 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,08-30 16:28:59.070   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=816517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:29:13.384  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:13.391  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:13.394  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:13.425  1511  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:29:13.426  1511  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:29:13.426  1511  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:29:13.426  1511  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:29:13.463  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 16:29:13.464  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:29:13.464  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-30 16:29:15.084   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=832530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:29:24.137   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=841584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:29:33.743  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:33.763  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:33.770  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:33.867  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:29:33.868  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 16:29:33.868  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:29:33.869  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:29:33.934  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:29:33.935  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:29:33.940  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-30 16:29:40.150   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=857597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:29:49.190   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=866637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:29:54.369  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:54.395  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:54.404  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:29:54.504  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:29:54.505  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:29:54.505  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:29:54.506  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:29:54.576  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:29:54.577  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:29:54.580  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 16:30:05.217   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=882664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:30:14.257   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=891704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:30:14.958  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:14.970  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:14.973  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:15.015  1511  4391 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:30:15.015  1511  4391 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:30:15.016  1511  4391 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:30:15.016  1511  4391 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:30:15.055  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:30:15.057  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:30:15.057  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 16:30:20.577   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=898023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:30:35.309  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:35.325  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:35.330  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:35.387  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:30:35.388  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:30:35.388  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:30:35.389  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:30:35.438  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:30:35.439  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 16:30:35.440  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-30 16:30:39.324   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=916770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:30:45.644   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=923090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:30:55.779  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:55.795  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:55.800  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:30:55.874  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:30:55.874  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 16:30:55.875  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-30 16:30:55.875  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-30 16:30:55.935  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 16:30:55.935  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:30:55.936  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 16:31:04.390   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=941837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:31:10.710   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=948157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:31:29.457   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=966903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:31:35.777   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=973223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:31:54.524   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=991970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:32:00.843   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=998290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:32:19.590   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1017037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:32:25.910   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1023357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:32:44.657   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1042104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:32:50.963   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1048410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:33:09.723   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1067170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:33:16.043   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1073490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:33:34.790   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1092237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:33:41.083   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1098530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:33:59.844   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1117290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:34:06.150   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1123597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:34:24.910   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1142357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:34:31.216   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1148663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:34:49.977   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1167424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:35:03.510   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1180957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:35:15.044   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1192490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:35:28.577   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1206024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:35:40.097   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1217544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:35:41.355   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,08-30 16:35:53.643   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1231090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:36:05.177   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1242623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:36:18.710   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1256157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:36:30.244   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1267690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:36:43.777   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1281224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:36:55.324   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1292770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:36:58.252  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:36:58.254  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:36:58.286  4078  4415 V GoogleAuthProtoRequest: [355] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:36:58.334  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 16:36:58.335  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-30 16:36:58.335  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:36:58.335  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: [355] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: [355] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
,08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:36:58.349  4078  4415 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:37:33.911   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1331357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:37:45.457   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1342903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:37:58.977   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1356424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:38:10.524   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1367970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:38:24.043   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1381490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:38:35.590   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1393036, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:38:49.164   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1406610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:39:00.697   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1418144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:39:14.230   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1431677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:39:25.763   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1443210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:39:39.297   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:39:50.817   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1468263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:40:04.363   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1481810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:40:15.884   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1493330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:40:23.190   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1500637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 16:40:40.950   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1518397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:40:48.257   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1525704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-30 16:40:52.839  4423  4423 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 16:40:52.844  4423  4423 D AndroidRuntime: CheckJNI is OFF
08-30 16:40:52.880  4423  4423 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 16:40:52.951  4423  4423 I Radio-JNI: register_android_hardware_Radio DONE
08-30 16:40:52.980  4423  4423 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 16:40:52.996   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-30 16:40:52.996   875   888 I ActivityManager: Killing 3833:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-30 16:40:53.102   875   898 W PackageSettings: Skipping PackageSetting{dca33ed com.example.hello/10273} due to missing metadata
08-30 16:40:53.131   875  1318 D WifiService: Client connection lost with reason: 4
08-30 16:40:53.131   875  1969 D GraphicsStats: Buffer count: 2
08-30 16:40:53.133   875  2003 I WindowState: WIN DEATH: Window{694a2ee u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 16:40:53.161   875   898 I art     : Starting a blocking GC Explicit
08-30 16:40:53.172   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-30 16:40:53.172   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 16:40:53.173   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-30 16:40:53.173   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 16:40:53.173   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.173   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.173   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.173   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 16:40:53.174   875   888 I ActivityManager:   Force finishing activity ActivityRecord{c9382b7 u0 com.test.thalitest/.MainActivity t2}
08-30 16:40:53.182   875  1883 W ActivityManager: Spurious death for ProcessRecord{ec95c4a 0:com.test.thalitest/u0a0}, curProc for 3833: null
08-30 16:40:53.220   875   898 I art     : Explicit concurrent mark sweep GC freed 24631(1999KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 816us total 57.505ms
08-30 16:40:53.240   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 16:40:53.242  4423  4423 I art     : System.exit called, status: 0
08-30 16:40:53.242  4423  4423 I AndroidRuntime: VM exiting with result code 0.
08-30 16:40:53.248   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-30 16:40:53.276   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-30 16:40:53.286   875  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 16:40:53.287  2022  2267 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 16:40:53.287  1884  1884 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 16:40:53.288  4212  4212 D BluetoothMapAppObserver: onReceive
08-30 16:40:53.288  4212  4212 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 16:40:53.299  3705  3705 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 16:40:53.309  1884  4436 I Keyboard.Facilitator.DecoderInitializer: run()
08-30 16:40:53.313  1884  4436 I Decoder : createOrResetDecoder
08-30 16:40:53.333  1955  1955 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-30 16:40:53.336  1511  1511 I ConfigService: onCreate
08-30 16:40:53.353   875  1966 I ActivityManager: Start proc 4439:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-30 16:40:53.363   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 16:40:53.364  1511  4449 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-30 16:40:53.387  4439  4439 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-30 16:40:53.387  1973  2064 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 16:40:53.387   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 16:40:53.388   875   887 E PackageManager: Failed to write settings, restoring backup
08-30 16:40:53.388   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 16:40:53.388   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 16:40:53.388   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 16:40:53.388   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 16:40:53.388   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 16:40:53.388   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.388   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.388   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.392   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-30 16:40:53.392   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 16:40:53.392   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:40:53.392   875   888 E DropBoxManagerService: 	... 13 more
08-30 16:40:53.399   875   885 I ActivityManager: Start proc 4452:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-30 16:40:53.400  1973  2064 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 16:40:53.400  1973  2064 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1973
08-30 16:40:53.400  1973  2064 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.400  1973  2064 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.402   875  1971 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:40:53.405  1973  2064 I Process : Sending signal. PID: 1973 SIG: 9
08-30 16:40:53.408   875  4459 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:40:53.408   875  4459 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:40:53.408   875  4459 E DropBoxManagerService: 	... 5 more
08-30 16:40:53.415  1884  4436 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-30 16:40:53.484  1884  4436 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-30 16:40:53.485  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 16:40:53.486  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 16:40:53.490  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 16:40:53.490  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 16:40:53.490  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 16:40:53.490  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 16:40:53.491  1884  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 16:40:53.491  1884  4436 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 16:40:53.491  1884  4436 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 16:40:53.491  1884  4436 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 16:40:53.491  1884  4436 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 16:40:53.492  1884  4436 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-30 16:40:53.516  4439  4439 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-30 16:40:53.519   875  1403 D GraphicsStats: Buffer count: 1
08-30 16:40:53.519   875  3155 I WindowState: WIN DEATH: Window{c449481 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-30 16:40:53.524   875  2003 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1973) has died
08-30 16:40:53.525   875  2003 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 16:40:53.527   875  2003 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.529  4439  4468 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.529  4439  4468 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.546   875   888 I ActivityManager: Start proc 4473:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:40:53.556  1737  4471 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-30 16:40:53.557  1737  4471 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-30 16:40:53.559   875  2013 I ActivityManager: Start proc 4485:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-30 16:40:53.563  4439  4479 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 16:40:53.592  4485  4485 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:40:53.606  4473  4473 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:40:53.606  4473  4473 D AndroidRuntime: Shutting down VM
08-30 16:40:53.614  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-30 16:40:53.614  1511  1511 D AndroidRuntime: Shutting down VM
08-30 16:40:53.615  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:40:53.615  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-30 16:40:53.615  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 16:40:53.615  1511  1511 E AndroidRuntime: 	... 8 more
08-30 16:40:53.616  4473  4473 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:40:53.616  4473  4473 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4473
08-30 16:40:53.616  4473  4473 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:40:53.616  4473  4473 E AndroidRuntime: 	... 10 more
08-30 16:40:53.619   875   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:40:53.620   875  4502 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:40:53.620   875  4502 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:40:53.620   875  4502 E DropBoxManagerService: 	... 5 more
08-30 16:40:53.622  4473  4473 I Process : Sending signal. PID: 4473 SIG: 9
08-30 16:40:53.622   875  4503 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:40:53.622   875  4503 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:40:53.622   875  4503 E DropBoxManagerService: 	... 5 more
08-30 16:40:53.622  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
08-30 16:40:53.635   875  3155 I ActivityManager: Killing 3755:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-30 16:40:53.640  1737  4471 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-30 16:40:53.640  1737  4471 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-30 16:40:53.654  4439  4468 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.660  4439  4479 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 16:40:53.660  4439  4479 E AndroidRuntime: Process: android.process.acore, PID: 4439
08-30 16:40:53.660  4439  4479 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:40:53.660  4439  4479 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:40:53.661  4439  4468 I Process : Sending signal. PID: 4439 SIG: 9
08-30 16:40:53.693   875  2013 I ActivityManager: Process android.process.acore (pid 4439) has died
08-30 16:40:53.693   875  2013 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-30 16:40:53.694   875  1883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4473) has died
08-30 16:40:53.695   875  1883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 16:40:53.697   875  1318 D WifiService: Client connection lost with reason: 4
08-30 16:40:53.707   875  1969 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
08-30 16:40:53.707   875  1969 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-30 16:40:53.707   875  1969 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-30 16:40:53.707   875  1969 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-30 16:40:53.712  1737  1737 W RocketImpressions: ClearcutLogger connection suspended: 1
08-30 16:40:53.713   875  4504 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:40:53.713   875  4504 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:40:53.713   875  4504 E DropBoxManagerService: 	... 5 more
08-30 16:40:53.721   875   888 I ActivityManager: Start proc 4505:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
