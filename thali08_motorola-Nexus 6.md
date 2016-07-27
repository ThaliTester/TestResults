#### Test 78968685940d272_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-27 09:40:20.034   874  1318 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-27 09:40:20.707  3767  3767 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 09:40:20.712  3767  3767 D AndroidRuntime: CheckJNI is OFF
07-27 09:40:20.755  3767  3767 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 09:40:20.804  3767  3767 I Radio-JNI: register_android_hardware_Radio DONE
07-27 09:40:20.827  3767  3767 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 09:40:20.831   874  2084 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 09:40:20.873  1814  2175 W SearchService: Abort, client detached.
07-27 09:40:20.889  1814  2165 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fd3f70a
07-27 09:40:20.889  1814  2172 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-27 09:40:20.889  1814  1814 I HotwordDetector: Closing mic
07-27 09:40:20.890  3767  3767 D AndroidRuntime: Shutting down VM
07-27 09:40:20.913   874  1705 I ActivityManager: Start proc 3776:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 09:40:20.937   376  2174 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-27 09:40:20.941   376  2174 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-27 09:40:20.947   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-27 09:40:20.950  1814  2169 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-27 09:40:20.950  1814  2171 I MicroRecognitionRnrImpl: Detection finished
07-27 09:40:20.991  3776  3776 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-27 09:40:21.013  3776  3776 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-27 09:40:21.020  3776  3776 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3885-3887)
07-27 09:40:21.020  3776  3776 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 09:40:21.041  3776  3776 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc05849}
07-27 09:40:21.041  3776  3776 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 09:40:21.041  3776  3776 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 09:40:21.048  3776  3776 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 09:40:21.049  3776  3776 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 09:40:21.061  3776  3776 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-27 09:40:21.072  3776  3776 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 09:40:21.072  3776  3776 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 09:40:21.072  3776  3776 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 09:40:21.072  3776  3776 I Adreno  : Build Date                       : 10/20/15
07-27 09:40:21.072  3776  3776 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 09:40:21.072  3776  3776 I Adreno  : Local Branch                     : M14
07-27 09:40:21.072  3776  3776 I Adreno  : Remote Branch                    : 
07-27 09:40:21.072  3776  3776 I Adreno  : Remote Branch                    : 
07-27 09:40:21.072  3776  3776 I Adreno  : Reconstruct Branch               : 
,07-27 09:40:21.119   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efb8a57:true
,07-27 09:40:21.173  3776  3776 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 09:40:21.201  3776  3776 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-27 09:40:21.287  3776  3814 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 09:40:21.300  3776  3801 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-27 09:40:21.334  3776  3814 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 09:40:21.406   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms
,07-27 09:40:21.417  1668  1668 I Keyboard.Facilitator: onFinishInput()
,07-27 09:40:21.513  3776  3776 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3776
,07-27 09:40:21.663  3776  3776 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 09:40:21.720   874  1401 I ActivityManager: Killing 2378:com.google.android.talk/u0a61 (adj 15): empty #17
,07-27 09:40:21.815   874  1401 I ActivityManager: Killing 3240:com.google.android.music:main/u0a66 (adj 15): empty #18
,07-27 09:40:21.930  3776  3817 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1705248464
,07-27 09:40:21.934  3776  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 09:40:21.934  3776  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 09:40:21.934  3776  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 09:40:21.934  3776  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 09:40:21.934  3776  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 09:40:21.934  3776  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f038c7d added. We now have 1 listener(s)
,07-27 09:40:21.936  3776  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-27 09:40:21.938  3776  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 09:40:21.938  3776  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 09:40:21.938  3776  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 09:40:21.941  3776  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bb4840 added. We now have 1 listener(s)
07-27 09:40:21.941  3776  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 09:40:21.947   874  1319 D WifiService: New client listening to asynchronous messages
07-27 09:40:21.949  3776  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-27 09:40:21.953  3776  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 09:40:21.953  3776  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-27 09:40:21.953  3776  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-27 09:40:21.954  3776  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 09:40:21.960  3776  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 09:40:21.961  3776  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:40:21.968  3776  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 09:40:21.968  3776  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-27 09:40:21.968  3776  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 09:40:21.971  3776  3776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:40:21.972  3776  3817 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 09:40:21.975  3776  3776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:40:21.991  3776  3776 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 09:40:22.660  3776  3827 W jxcore-log: Initializing JXcore engine
,07-27 09:40:22.660  3776  3827 W jxcore-log: JXcore engine is ready
,07-27 09:40:22.701  3827  3827 W Thread-338: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8937 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-27 09:40:22.701  3827  3827 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12701]" dev="sockfs" ino=12701 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 09:40:22.701  3827  3827 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-27 09:40:22.704  3827  3827 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26195]" dev="sockfs" ino=26195 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 09:40:22.717  3776  3827 W jxcore-log: Starting JXcore engine
,07-27 09:40:22.800  3776  3827 W jxcore-log: Platform android
07-27 09:40:22.800  3776  3827 W jxcore-log: 
,07-27 09:40:22.800  3776  3827 W jxcore-log: Process ARCH arm
07-27 09:40:22.800  3776  3827 W jxcore-log: 
,07-27 09:40:23.010  3776  3827 I jxcore-log: JXcore Cordova bridge is ready!
07-27 09:40:23.010  3776  3827 I jxcore-log: 
07-27 09:40:23.011  3776  3827 W jxcore-log: JXcore engine is started
,07-27 09:40:23.019  3776  3817 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 09:40:23.023  3776  3776 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 09:40:26.921  3465  3835 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:40:26.933  3465  3836 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:40:26.941  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:26.943  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:26.961  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:40:26.961  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:40:26.961  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:40:26.962  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:27.002  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:27.009  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:27.042  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:40:27.042  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:40:27.043  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:40:27.043  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:27.078  3465  3836 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:40:27.079  3465  3835 E BooksSync: Soft error
07-27 09:40:27.079  3465  3835 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:40:27.079  3465  3835 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:40:27.079  3465  3835 E BooksSync: Sync error
07-27 09:40:27.079  3465  3835 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:40:27.079  3465  3835 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:40:27.079  3465  3835 I BooksSync: Finished books sync
,07-27 09:40:27.082   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129699, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:40:31.118  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:31.121  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:31.122  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:31.136  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-27 09:40:31.136  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-27 09:40:31.136  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:40:31.136  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:31.146  3376  3376 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:40:31.146  3376  3376 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 09:40:31.147  3376  3376 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-27 09:40:33.489  3776  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 09:40:33.489  3776  3827 I jxcore-log: 
,07-27 09:40:33.492  3776  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 09:40:33.492  3776  3827 I jxcore-log: 
,07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:40:33.503  3776  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 09:40:33.508  3776  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 09:40:33.510  3776  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 09:40:33.510  3776  3827 I jxcore-log: 
,07-27 09:40:33.512  3776  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 09:40:33.512  3776  3827 I jxcore-log: 
,07-27 09:40:33.847  3776  3827 I jxcore-log: Unit Test app is loaded
07-27 09:40:33.847  3776  3827 I jxcore-log: 
,07-27 09:40:33.853  3776  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 09:40:33.853  3776  3827 I jxcore-log: 
,07-27 09:40:33.858  3776  3827 I jxcore-log: My device name is: motorola-Nexus 6
07-27 09:40:33.858  3776  3827 I jxcore-log: 
,07-27 09:40:33.859  3776  3827 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 09:40:33.859  3776  3827 I jxcore-log: 
,07-27 09:40:33.869  3776  3776 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 09:40:37.914  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 09:40:37.914  3776  3827 I jxcore-log: 
,07-27 09:40:38.307  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 09:40:38.307  3776  3827 I jxcore-log: 
,07-27 09:40:38.332  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 09:40:38.332  3776  3827 I jxcore-log: 
,07-27 09:40:38.338  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 09:40:38.338  3776  3827 I jxcore-log: 
,07-27 09:40:38.354  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 09:40:38.354  3776  3827 I jxcore-log: 
,07-27 09:40:38.358  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 09:40:38.358  3776  3827 I jxcore-log: 
,07-27 09:40:40.395  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 09:40:40.395  3776  3827 I jxcore-log: 
,07-27 09:40:40.408  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 09:40:40.408  3776  3827 I jxcore-log: 
,07-27 09:40:40.417  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 09:40:40.417  3776  3827 I jxcore-log: 
,07-27 09:40:40.576  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 09:40:40.576  3776  3827 I jxcore-log: 
,07-27 09:40:41.388  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 09:40:41.388  3776  3827 I jxcore-log: 
,07-27 09:40:41.396   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=144263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:40:41.445  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 09:40:41.445  3776  3827 I jxcore-log: 
,07-27 09:40:41.451  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 09:40:41.451  3776  3827 I jxcore-log: 
,07-27 09:40:41.658  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 09:40:41.658  3776  3827 I jxcore-log: 
,07-27 09:40:41.680  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 09:40:41.680  3776  3827 I jxcore-log: 
,07-27 09:40:41.686  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 09:40:41.686  3776  3827 I jxcore-log: 
,07-27 09:40:41.692  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 09:40:41.692  3776  3827 I jxcore-log: 
,07-27 09:40:41.708  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 09:40:41.708  3776  3827 I jxcore-log: 
,07-27 09:40:41.729  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 09:40:41.729  3776  3827 I jxcore-log: 
,07-27 09:40:41.816  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 09:40:41.816  3776  3827 I jxcore-log: 
,07-27 09:40:41.822  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 09:40:41.822  3776  3827 I jxcore-log: 
,07-27 09:40:41.848  3776  3827 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 09:40:41.848  3776  3827 I jxcore-log: 
,07-27 09:40:41.863  3776  3827 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 09:40:41.865  3776  3827 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 09:40:41.865  3776  3827 I jxcore-log: 
,07-27 09:40:47.177   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-27 09:40:47.189  1668  1668 I Keyboard.Facilitator: onFinishInput()
,07-27 09:40:47.193   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 09:40:47.193   874   894 I Adreno  : Build Date                       : 10/20/15
07-27 09:40:47.193   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 09:40:47.193   874   894 I Adreno  : Local Branch                     : M14
07-27 09:40:47.193   874   894 I Adreno  : Remote Branch                    : 
07-27 09:40:47.193   874   894 I Adreno  : Remote Branch                    : 
07-27 09:40:47.193   874   894 I Adreno  : Reconstruct Branch               : 
,07-27 09:40:47.231   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (663 us)
,07-27 09:40:47.864  3776  3776 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 09:40:47.864  3776  3776 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-27 09:40:47.902   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-27 09:40:47.903  3776  3776 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e308467 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e35556e, 16908290=android.view.AbsSavedState$1@e35556e}, android:focusedViewId=100}]}]
,07-27 09:40:47.903  3776  3776 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-27 09:40:47.904  3776  3776 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-27 09:40:47.904  3776  3776 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-27 09:40:47.919   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-27 09:40:47.923   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-27 09:40:47.927   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,07-27 09:40:47.927   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-27 09:40:47.955   874   883 I art     : Background partial concurrent mark sweep GC freed 14270(1004KB) AllocSpace objects, 5(112KB) LOS objects, 33% free, 28MB/43MB, paused 1.248ms total 125.946ms
,07-27 09:40:48.164   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-27 09:40:48.169   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-27 09:40:48.175   874  1345 D SurfaceControl: Excessive delay in setPowerMode(): 252ms
07-27 09:40:48.177   874   894 I DreamManagerService: Entering dreamland.
07-27 09:40:48.177   874   894 I PowerManagerService: Dozing...
,07-27 09:40:48.181   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-27 09:40:48.247   376  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-27 09:40:48.247   376  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,07-27 09:40:48.264  1738  3847 D NfcService: Discovery configuration equal, not updating.
,07-27 09:40:48.273   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 09:40:48.291   874  1318 E native  : do suspend false
,07-27 09:40:48.315   874  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,07-27 09:40:48.335   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 09:40:48.342   874  1318 E native  : do suspend true
,07-27 09:40:48.384   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-27 09:40:48.384   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,07-27 09:40:48.779   874  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,07-27 09:40:52.371  1878  2504 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:40:54.196   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:40:57.363  2896  3853 V KeepSync: Connecting to GoogleApiClient
,07-27 09:40:57.364   874  1721 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:40:57.392  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:40:57.395  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-27 09:40:57.445  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:40:57.446  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:40:57.446  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:40:57.446  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:57.464  3415  3854 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:40:57.464  3415  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:40:57.464  3415  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	... 12 more
07-27 09:40:57.464  3415  3854 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at fal.a(PG:38)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:40:57.464  3415  3854 E HttpOperation: 	... 14 more
,07-27 09:40:57.514  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-27 09:40:57.514  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 09:40:57.514  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:40:57.514  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:57.515  1531  1919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 09:40:57.515  1531  1919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:40:57.515  1531  1919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:40:57.515  1531  1919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:57.541  1963  3855 V BaseAuthAsyncOperation: access token request failed
,07-27 09:40:57.542  2896  3853 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:40:57.556  3415  3854 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:40:57.556  3415  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at hec.a(PG:42)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at hee.a(PG:102)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at czr.a(PG:65)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at kka.a(PG:108)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:40:57.556  3415  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	... 15 more
07-27 09:40:57.556  3415  3854 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at fal.a(PG:38)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:40:57.556  3415  3854 E HttpOperation: 	... 17 more
,07-27 09:40:57.556  3415  3854 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:40:57.556  3415  3854 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	... 15 more
07-27 09:40:57.556  3415  3854 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:40:57.556  3415  3854 E ExperimentLoader: 	... 17 more
,07-27 09:40:57.646  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 09:40:57.646  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 09:40:57.646  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:40:57.646  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:40:57.674  2896  3853 E KeepSync: IOException
07-27 09:40:57.674  2896  3853 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:40:57.674  2896  3853 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:40:57.674  2896  3853 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:40:57.674  2896  3853 E KeepSync: 	... 10 more
,07-27 09:40:57.674  2896  3853 W KeepSync: Sync result 2
,07-27 09:40:57.693   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 132562, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:40:57.727   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130412, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:41:00.051   874  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,07-27 09:41:18.606  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:41:18.608  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:41:18.629  3503  3862 V GoogleAuthProtoRequest: [303] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:41:18.696  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 09:41:18.696  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-27 09:41:18.696  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:41:18.696  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: [303] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: [303] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:41:18.716  3503  3862 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:41:33.343   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:41:47.201  1668  1725 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-27 09:41:47.202  1668  1725 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-27 09:41:47.233  1531  1531 I ConfigService: onCreate
,07-27 09:41:52.302  1531  1531 I ConfigService: onDestroy
,07-27 09:42:12.156   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:42:27.018  1531  2002 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:42:34.047  3465  3867 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:42:34.081  3465  3868 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:42:34.094  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:42:34.096  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-27 09:42:34.120  1531  2073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 09:42:34.120  1531  2073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:42:34.120  1531  2073 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:42:34.120  1531  2073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:42:34.145  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:42:34.149  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:42:34.174  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:42:34.175  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:42:34.175  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:42:34.175  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:42:34.195  3465  3868 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:42:34.196  3465  3867 E BooksSync: Soft error
07-27 09:42:34.196  3465  3867 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:42:34.196  3465  3867 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:42:34.196  3465  3867 E BooksSync: Sync error
07-27 09:42:34.196  3465  3867 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:42:34.196  3465  3867 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:42:34.196  3465  3867 I BooksSync: Finished books sync
,07-27 09:42:34.212   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 256746, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:42:51.316   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=274184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:43:07.787  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:07.788  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:07.812  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:43:07.812  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:43:07.812  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:43:07.812  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:43:07.835  3415  3875 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:43:07.835  3415  3875 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:43:07.835  3415  3875 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	... 12 more
07-27 09:43:07.835  3415  3875 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at fal.a(PG:38)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:43:07.835  3415  3875 E HttpOperation: 	... 14 more
,07-27 09:43:07.873  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:43:07.873  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:43:07.874  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:43:07.874  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:43:07.896  3415  3875 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:43:07.896  3415  3875 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at hec.a(PG:42)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at hee.a(PG:102)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at czr.a(PG:65)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at kka.a(PG:108)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:43:07.896  3415  3875 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	... 15 more
07-27 09:43:07.896  3415  3875 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at fal.a(PG:38)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:43:07.896  3415  3875 E HttpOperation: 	... 17 more
,07-27 09:43:07.896  3415  3875 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:43:07.896  3415  3875 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	... 15 more
07-27 09:43:07.896  3415  3875 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:43:07.896  3415  3875 E ExperimentLoader: 	... 17 more
,07-27 09:43:08.044   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 290331, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:43:38.155  2896  3880 V KeepSync: Connecting to GoogleApiClient
07-27 09:43:38.156   874  1799 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:43:38.193  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:38.194  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:38.223  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 09:43:38.223  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 09:43:38.223  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:43:38.223  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:43:38.264  1963  3881 V BaseAuthAsyncOperation: access token request failed
,07-27 09:43:38.265  2896  3880 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:43:38.336  1531  2073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 09:43:38.336  1531  2073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 09:43:38.336  1531  2073 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:43:38.336  1531  2073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:43:38.348  2896  3880 E KeepSync: IOException
07-27 09:43:38.348  2896  3880 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:43:38.348  2896  3880 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:43:38.348  2896  3880 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:43:38.348  2896  3880 E KeepSync: 	... 10 more
07-27 09:43:38.348  2896  3880 W KeepSync: Sync result 2
,07-27 09:43:38.355   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 292237, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:43:45.156   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=328024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:43:48.762  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:48.764  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:48.778  3503  3882 V GoogleAuthProtoRequest: [304] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:43:48.801  1531  1919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-27 09:43:48.801  1531  1919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-27 09:43:48.801  1531  1919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:43:48.802  1531  1919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:43:48.817  3503  3882 W ExperimentUpdateService: [304] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: [304] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:43:48.818  3503  3882 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:43:58.739  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:58.754  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:58.758  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:43:58.832  1531  1919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 09:43:58.832  1531  1919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-27 09:43:58.833  1531  1919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:43:58.833  1531  1919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:43:58.887  1531  1919 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 09:43:58.887  1531  1919 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 09:43:58.887  1531  1919 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 09:43:58.887  1531  1919 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-27 09:43:58.887  1531  1919 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:43:58.887  1531  1919 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:43:58.887  1531  1919 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:43:58.904  3376  3406 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 09:43:58.904  3376  3406 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 09:43:58.904  3376  3406 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-27 09:43:58.904  3376  3406 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-27 09:43:58.904  3376  3406 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-27 09:43:58.904  3376  3406 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 09:43:58.904  3376  3406 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:44:38.303   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:45:01.503   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:45:40.703   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:46:47.965  3465  3894 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:46:48.009  3465  3895 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:46:48.024  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:46:48.026  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-27 09:46:48.071  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:46:48.071  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:46:48.072  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:46:48.072  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:46:48.131  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:46:48.135  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:46:48.185  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:46:48.186  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:46:48.186  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:46:48.186  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:46:48.220  3465  3895 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:46:48.222  3465  3894 E BooksSync: Soft error
07-27 09:46:48.222  3465  3894 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:46:48.222  3465  3894 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 09:46:48.222  3465  3894 E BooksSync: Sync error
07-27 09:46:48.222  3465  3894 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:46:48.222  3465  3894 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:46:48.222  3465  3894 I BooksSync: Finished books sync
,07-27 09:46:48.235   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 510672, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:47:27.681  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:47:27.684  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:47:27.708  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:47:27.708  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:47:27.708  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:47:27.708  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:47:27.722  3415  3900 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:47:27.722  3415  3900 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:47:27.722  3415  3900 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	... 12 more
07-27 09:47:27.722  3415  3900 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at fal.a(PG:38)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:47:27.722  3415  3900 E HttpOperation: 	... 14 more
,07-27 09:47:27.774  1531  1919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:47:27.774  1531  1919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:47:27.774  1531  1919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:47:27.774  1531  1919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:47:27.788  3415  3900 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:47:27.788  3415  3900 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at hec.a(PG:42)
07-27 09:47:27.788  3415  3900 E HttpOperation: ,	at hee.a(PG:102)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at czr.a(PG:65)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at kka.a(PG:108)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:47:27.788  3415  3900 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	... 15 more
07-27 09:47:27.788  3415  3900 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at fal.a(PG:38)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:47:27.788  3415  3900 E HttpOperation: 	... 17 more
,07-27 09:47:27.788  3415  3900 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:47:27.788  3415  3900 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	... 15 more
07-27 09:47:27.788  3415  3900 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:47:27.788  3415  3900 E ExperimentLoader: 	... 17 more
,07-27 09:47:27.950   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 550384, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:47:48.941  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:47:48.943  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:47:48.958  3503  3902 V GoogleAuthProtoRequest: [305] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:47:48.990  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-27 09:47:48.991  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 09:47:48.991  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:47:48.991  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:47:49.011  3503  3902 W ExperimentUpdateService: [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:47:49.012  3503  3902 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:48:01.830  2896  3904 V KeepSync: Connecting to GoogleApiClient
,07-27 09:48:01.831   874  1401 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:48:01.885  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:48:01.887  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:48:01.938  1531  1919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 09:48:01.939  1531  1919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 09:48:01.939  1531  1919 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:48:01.939  1531  1919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:48:01.967  1963  3905 V BaseAuthAsyncOperation: access token request failed
,07-27 09:48:01.968  2896  3904 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:48:02.036  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 09:48:02.036  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 09:48:02.036  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:48:02.036  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:48:02.062  2896  3904 E KeepSync: IOException
07-27 09:48:02.062  2896  3904 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:48:02.062  2896  3904 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:48:02.062  2896  3904 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:48:02.062  2896  3904 E KeepSync: 	... 10 more
,07-27 09:48:02.062  2896  3904 W KeepSync: Sync result 2
,07-27 09:48:02.073   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 584576, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:48:04.463   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:48:43.530   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=626397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:49:04.236   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:49:43.370   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=686237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:55:15.661  3465  3929 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:55:15.682  3465  3932 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:55:15.696  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:55:15.699  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:55:15.726  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 09:55:15.727  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:55:15.727  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:55:15.727  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:55:15.764  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:55:15.767  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:55:15.792  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:55:15.793  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:55:15.793  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:55:15.793  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:55:15.811  3465  3932 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:55:15.812  3465  3929 E BooksSync: Soft error
07-27 09:55:15.812  3465  3929 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:55:15.812  3465  3929 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 09:55:15.812  3465  3929 E BooksSync: Sync error
07-27 09:55:15.812  3465  3929 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:55:15.812  3465  3929 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:55:15.813  3465  3929 I BooksSync: Finished books sync
,07-27 09:55:15.823   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1018287, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:55:18.907  1963  3934 I EventLogService: Opted in for usage reporting
,07-27 09:55:18.910  1963  3934 I EventLogService: Aggregate from 1469604100382 (log), 1469604100382 (data)
,07-27 09:55:19.024  1963  3934 W EventLogAggregator: Unknown tag: snet_gcore
07-27 09:55:19.024  1963  3934 W EventLogAggregator: Unknown tag: snet_launch_service
,07-27 09:55:19.089  1963  3934 I ServiceDumpSys: dumping service [account]
,07-27 09:55:23.876   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1026743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 09:55:32.596   874  2008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1035464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:55:49.177  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:55:49.179  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:55:49.190  3503  3939 V GoogleAuthProtoRequest: [306] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:55:49.215  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 09:55:49.215  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 09:55:49.215  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:55:49.215  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:55:49.229  3503  3939 W ExperimentUpdateService: [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:55:49.230  3503  3939 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:56:07.188  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:56:07.194  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:56:07.260  1531  2073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:56:07.261  1531  2073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:56:07.261  1531  2073 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:56:07.261  1531  2073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:56:07.296  3415  3942 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:56:07.296  3415  3942 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at czp.a(PG:9087)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:07.296  3415  3942 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	... 12 more
07-27 09:56:07.296  3415  3942 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at fal.a(PG:38)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:56:07.296  3415  3942 E HttpOperation: 	... 14 more
,07-27 09:56:07.586  1531  2073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 09:56:07.586  1531  2073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:56:07.586  1531  2073 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:56:07.587  1531  2073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:56:07.604  3415  3945 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:56:07.604  3415  3945 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:07.604  3415  3945 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	... 12 more
07-27 09:56:07.604  3415  3945 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at fal.a(PG:38)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:56:07.604  3415  3945 E HttpOperation: 	... 14 more
,07-27 09:56:07.651  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:56:07.651  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:56:07.652  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:56:07.652  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:56:07.671  3415  3945 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:56:07.671  3415  3945 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at hec.a(PG:42)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at hee.a(PG:102)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at czr.a(PG:65)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at kka.a(PG:108)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at czp.a(PG:19176)
,07-27 09:56:07.671  3415  3945 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:07.671  3415  3945 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	... 15 more
07-27 09:56:07.671  3415  3945 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at fal.a(PG:38)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:56:07.671  3415  3945 E HttpOperation: 	... 17 more
07-27 09:56:07.672  3415  3945 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:56:07.672  3415  3945 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	... 15 more
07-27 09:56:07.672  3415  3945 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:56:07.672  3415  3945 E ExperimentLoader: 	... 17 more
,07-27 09:56:07.787   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 550819, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:56:41.012  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:56:41.014  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:56:41.039  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:56:41.039  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:56:41.039  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:56:41.039  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:56:41.053  3415  3950 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:56:41.053  3415  3950 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:41.053  3415  3950 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	... 12 more
07-27 09:56:41.053  3415  3950 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at fal.a(PG:38)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:56:41.053  3415  3950 E HttpOperation: 	... 14 more
,07-27 09:56:41.132  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:56:41.132  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:56:41.132  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:56:41.132  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:56:41.155  3415  3950 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:56:41.155  3415  3950 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at hec.a(PG:42)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at hee.a(PG:102)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at czr.a(PG:65)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at kka.a(PG:108)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:41.155  3415  3950 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	... 15 more
07-27 09:56:41.155  3415  3950 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at fal.a(PG:38)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:56:41.155  3415  3950 E HttpOperation: 	... 17 more
,07-27 09:56:41.155  3415  3950 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:56:41.155  3415  3950 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	... 15 more
07-27 09:56:41.155  3415  3950 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:56:41.155  3415  3950 E ExperimentLoader: 	... 17 more
,07-27 09:56:41.312   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1103579, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:57:11.453  2896  3953 V KeepSync: Connecting to GoogleApiClient
,07-27 09:57:11.454   874  1796 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:57:11.515  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:57:11.521  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:57:11.548  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 09:57:11.549  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 09:57:11.549  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:57:11.549  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:57:11.571  1963  3954 V BaseAuthAsyncOperation: access token request failed
,07-27 09:57:11.572  2896  3953 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:57:11.619  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 09:57:11.619  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 09:57:11.619  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:57:11.619  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:57:11.635  2896  3953 E KeepSync: IOException
07-27 09:57:11.635  2896  3953 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:57:11.635  2896  3953 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:57:11.635  2896  3953 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:57:11.635  2896  3953 E KeepSync: 	... 10 more
,07-27 09:57:11.635  2896  3953 W KeepSync: Sync result 2
,07-27 09:57:11.649   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1111645, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:57:47.530  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:57:47.533  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:57:47.558  1531  1919 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:57:47.559  1531  1919 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:57:47.559  1531  1919 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:57:47.559  1531  1919 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:57:47.576  3415  3958 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:57:47.576  3415  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:57:47.576  3415  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	... 12 more
07-27 09:57:47.576  3415  3958 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at fal.a(PG:38)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:57:47.576  3415  3958 E HttpOperation: 	... 14 more
,07-27 09:57:47.603  1531  2753 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 09:57:47.603  1531  2753 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:57:47.604  1531  2753 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:57:47.604  1531  2753 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:57:47.619  3415  3958 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:57:47.619  3415  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jdm.a(PG:82),
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jcs.i(PG:143)
,07-27 09:57:47.619  3415  3958 E HttpOperation: 	at hec.a(PG:42)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at hee.a(PG:102)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at czr.a(PG:65)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at kka.a(PG:108)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:57:47.619  3415  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	... 15 more
07-27 09:57:47.619  3415  3958 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at fal.a(PG:38)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:57:47.619  3415  3958 E HttpOperation: 	... 17 more
07-27 09:57:47.619  3415  3958 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:57:47.619  3415  3958 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	... 15 more
07-27 09:57:47.619  3415  3958 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:57:47.619  3415  3958 E ExperimentLoader: 	... 17 more
,07-27 09:57:47.752   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1170029, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:58:35.986   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:59:59.736  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:59:59.738  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:59:59.770  1531  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:59:59.771  1531  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:59:59.771  1531  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:59:59.771  1531  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:59:59.786  3415  3971 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:59:59.786  3415  3971 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:59:59.786  3415  3971 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	... 12 more
07-27 09:59:59.786  3415  3971 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at fal.a(PG:38)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:59:59.786  3415  3971 E HttpOperation: 	... 14 more
,07-27 09:59:59.873  1531  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 09:59:59.873  1531  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:59:59.873  1531  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:59:59.873  1531  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:59:59.894  3415  3971 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:59:59.894  3415  3971 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at hec.a(PG:42)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at hee.a(PG:102)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at czr.a(PG:65)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at kka.a(PG:108)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:59:59.894  3415  3971 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	... 15 more
07-27 09:59:59.894  3415  3971 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at fal.a(PG:38)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:59:59.894  3415  3971 E HttpOperation: 	... 17 more
,07-27 09:59:59.895  3415  3971 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:59:59.895  3415  3971 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: ,	at czq.run(PG:1686)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	... 15 more
07-27 09:59:59.895  3415  3971 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:59:59.895  3415  3971 E ExperimentLoader: 	... 17 more
,07-27 10:00:00.032   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1302317, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms)
```
