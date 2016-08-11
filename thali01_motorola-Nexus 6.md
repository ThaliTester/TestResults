#### Test 80912877b687439_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 10:49:05.960   872  2149 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 10:49:06.641  3666  3666 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 10:49:06.645  3666  3666 D AndroidRuntime: CheckJNI is OFF
08-11 10:49:06.681  3666  3666 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 10:49:06.755  3666  3666 I Radio-JNI: register_android_hardware_Radio DONE
08-11 10:49:06.784  3666  3666 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 10:49:06.788   872  1681 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 10:49:06.834  1815  1829 W SearchService: Abort, client detached.
08-11 10:49:06.841  3666  3666 D AndroidRuntime: Shutting down VM
08-11 10:49:06.842  1815  2151 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@61dabb1
08-11 10:49:06.843  1815  1815 I HotwordDetector: Closing mic
08-11 10:49:06.844  1815  2158 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 10:49:06.856   872  1759 I ActivityManager: Start proc 3675:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 10:49:06.906   376  2162 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 10:49:06.907   376  2162 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 10:49:06.919   376  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 10:49:06.922  1815  2157 I MicroRecognitionRnrImpl: Detection finished
08-11 10:49:06.922  1815  2155 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 10:49:06.945  3675  3675 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 10:49:06.965  3675  3675 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 10:49:06.976  3675  3675 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 6259-6266)
08-11 10:49:06.976  3675  3675 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 10:49:06.998  3675  3675 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d70aeca}
08-11 10:49:06.998  3675  3675 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 10:49:06.998  3675  3675 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 10:49:07.004  3675  3675 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 10:49:07.005  3675  3675 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 10:49:07.031  3675  3675 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 10:49:07.059  3675  3675 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 10:49:07.059  3675  3675 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 10:49:07.059  3675  3675 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 10:49:07.059  3675  3675 I Adreno  : Build Date                       : 10/20/15
08-11 10:49:07.059  3675  3675 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 10:49:07.059  3675  3675 I Adreno  : Local Branch                     : M14
08-11 10:49:07.059  3675  3675 I Adreno  : Remote Branch                    : 
08-11 10:49:07.059  3675  3675 I Adreno  : Remote Branch                    : 
08-11 10:49:07.059  3675  3675 I Adreno  : Reconstruct Branch               : 
,08-11 10:49:07.154   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37d619c:true
,08-11 10:49:07.197  3675  3675 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 10:49:07.212  3675  3675 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 10:49:07.279  3675  3715 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 10:49:07.290  3675  3700 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 10:49:07.328  3675  3715 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 10:49:07.383   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +541ms
,08-11 10:49:07.385  1657  1657 I Keyboard.Facilitator: onFinishInput()
,08-11 10:49:07.484  3675  3675 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3675
,08-11 10:49:07.582  3675  3675 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 10:49:07.665   872  1771 I ActivityManager: Killing 3101:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 10:49:07.713   872  1771 I ActivityManager: Killing 2978:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-11 10:49:07.830  3675  3717 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1696597712
,08-11 10:49:07.878  3675  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 10:49:07.878  3675  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 10:49:07.878  3675  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 10:49:07.878  3675  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 10:49:07.878  3675  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 10:49:07.879  3675  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e5e42e added. We now have 1 listener(s)
,08-11 10:49:07.895  3675  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 10:49:07.901  3675  3717 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 10:49:07.904  3675  3717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 10:49:07.906  3675  3717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-11 10:49:07.912  3675  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f964465 added. We now have 1 listener(s)
,08-11 10:49:07.913  3675  3717 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 10:49:07.915   872  1312 D WifiService: New client listening to asynchronous messages
,08-11 10:49:07.917  3675  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-11 10:49:07.917  3675  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 10:49:07.918  3675  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-11 10:49:07.918  3675  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-11 10:49:07.918  3675  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 10:49:07.923  3675  3717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 10:49:07.923  3675  3717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-11 10:49:07.929  3675  3717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 10:49:07.929  3675  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 10:49:07.930  3675  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 10:49:07.930  3675  3717 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 10:49:07.931  3675  3717 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 10:49:08.032  3675  3675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 10:49:08.034  3675  3675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 10:49:08.037  3675  3675 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 10:49:08.666  3675  3725 W jxcore-log: Initializing JXcore engine
08-11 10:49:08.666  3675  3725 W jxcore-log: JXcore engine is ready
,08-11 10:49:08.710  3725  3725 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 10:49:08.710  3725  3725 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11604]" dev="sockfs" ino=11604 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 10:49:08.710  3725  3725 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 10:49:08.710  3725  3725 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26807]" dev="sockfs" ino=26807 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 10:49:08.725  3675  3725 W jxcore-log: Starting JXcore engine
,08-11 10:49:08.811  3675  3725 W jxcore-log: Platform android
08-11 10:49:08.811  3675  3725 W jxcore-log: 
,08-11 10:49:08.811  3675  3725 W jxcore-log: Process ARCH arm
08-11 10:49:08.811  3675  3725 W jxcore-log: 
,08-11 10:49:09.039  3675  3725 I jxcore-log: JXcore Cordova bridge is ready!
08-11 10:49:09.039  3675  3725 I jxcore-log: 
,08-11 10:49:09.040  3675  3725 W jxcore-log: JXcore engine is started
,08-11 10:49:09.048  3675  3717 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 10:49:09.052  3675  3675 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 10:49:13.426   872  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-11 10:49:17.164  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 10:49:17.169  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 10:49:17.171  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 10:49:17.192  1500  1893 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 10:49:17.192  1500  1893 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 10:49:17.192  1500  1893 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 10:49:17.192  1500  1893 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 10:49:17.213  3416  3416 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 10:49:17.214  3416  3416 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 10:49:17.215  3416  3416 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-11 10:49:19.041  3675  3725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 10:49:19.041  3675  3725 I jxcore-log: 
,08-11 10:49:19.044  3675  3725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 10:49:19.044  3675  3725 I jxcore-log: 
,08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 10:49:19.056  3675  3725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 10:49:19.063  3675  3725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 10:49:19.071  3675  3725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 10:49:19.071  3675  3725 I jxcore-log: 
,08-11 10:49:19.079  3675  3725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 10:49:19.079  3675  3725 I jxcore-log: 
,08-11 10:49:19.436  3675  3725 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 10:49:19.437  3675  3725 I jxcore-log: Failed to execute UT.
08-11 10:49:19.437  3675  3725 I jxcore-log: 
08-11 10:49:19.437  3675  3725 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 10:49:19.437  3675  3725 I jxcore-log: 
,08-11 10:49:19.440  3675  3725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 10:49:19.440  3675  3725 I jxcore-log: 
,08-11 10:49:19.453  3477  3739 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 10:49:19.456  3675  3675 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 10:49:19.483  3477  3740 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 10:49:19.522  1500  2758 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 10:49:19.523  1500  2758 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 10:49:19.523  1500  2758 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 10:49:19.523  1500  2758 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 10:49:19.577  1500  2914 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 10:49:19.578  1500  2914 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 10:49:19.578  1500  2914 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 10:49:19.578  1500  2914 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 10:49:19.589  3477  3740 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 10:49:19.591  3477  3739 E BooksSync: Soft error
08-11 10:49:19.591  3477  3739 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 10:49:19.591  3477  3739 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 10:49:19.591  3477  3739 E BooksSync: Sync error
08-11 10:49:19.591  3477  3739 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 10:49:19.591  3477  3739 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 10:49:19.591  3477  3739 I BooksSync: Finished books sync
,08-11 10:49:19.596   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 10:49:20.030  3741  3741 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 10:49:20.035  3741  3741 D AndroidRuntime: CheckJNI is OFF
,08-11 10:49:20.070  3741  3741 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 10:49:20.114  3741  3741 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 10:49:20.134  3741  3741 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 10:49:20.145   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 10:49:20.146   872   885 I ActivityManager: Killing 3675:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 10:49:20.247   872   895 W PackageSettings: Skipping PackageSetting{833afc1 com.example.hello/10273} due to missing metadata
,08-11 10:49:20.262   872  1771 D GraphicsStats: Buffer count: 2
08-11 10:49:20.262   872  1767 I WindowState: WIN DEATH: Window{22a69cc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 10:49:20.265   872  1312 D WifiService: Client connection lost with reason: 4
,08-11 10:49:20.282   872   885 W ActivityManager: Force removing ActivityRecord{956c57d u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-11 10:49:20.302   872   895 I art     : Starting a blocking GC Explicit
,08-11 10:49:20.312   872  1771 W ActivityManager: Spurious death for ProcessRecord{49a7406 0:com.test.thalitest/u0a0}, curProc for 3675: null
,08-11 10:49:20.336   872  1745 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3675 uid 10000
,08-11 10:49:20.337  1657  1657 I Keyboard.Facilitator: onFinishInput()
,08-11 10:49:20.356   872   895 I art     : Explicit concurrent mark sweep GC freed 21092(1368KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 894us total 54.228ms
,08-11 10:49:20.381   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 10:49:20.384  3741  3741 I art     : System.exit called, status: 0
,08-11 10:49:20.384  3741  3741 I AndroidRuntime: VM exiting with result code 0.
,08-11 10:49:20.388   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 10:49:20.412  2570  2570 D BluetoothMapAppObserver: onReceive
08-11 10:49:20.412  2570  2570 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-11 10:49:20.415  1815  3756 I MicroRecognitionRnrImpl: Starting detection.
,08-11 10:49:20.418  1836  2029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 10:49:20.420  3548  3548 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-11 10:49:20.420   872  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 10:49:20.421  1657  1657 I Keyboard.Facilitator: resetDictionaries() : en_US
08-11 10:49:20.428  1815  3757 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@6b4575d
08-11 10:49:20.429   376  3762 I AudioFlinger: AudioFlinger's thread 0xb3440000 ready to run
,08-11 10:49:20.431  1657  3760 I Keyboard.Facilitator.DecoderInitializer: run()
,08-11 10:49:20.434  1657  3760 I Decoder : createOrResetDecoder
,08-11 10:49:20.449   376  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 10:49:20.450  1815  3757 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@6b4575d
,08-11 10:49:20.459   376  3762 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-11 10:49:20.460   376  3762 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-11 10:49:20.460   376  3762 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-11 10:49:20.470   376  3762 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
08-11 10:49:20.486  1754  1754 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 10:49:20.514  1500  1500 I ConfigService: onCreate
,08-11 10:49:20.528   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 10:49:20.545  1657  3760 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-11 10:49:20.556  1815  1815 I HotwordWorkerImpl: onReady
,08-11 10:49:20.559  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-11 10:49:20.560  1500  1500 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-11 10:49:20.560  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
08-11 10:49:20.560  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
08-11 10:49:20.560  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 10:49:20.560  1500  1500 E AndroidRuntime: 	... 8 more
,08-11 10:49:20.564  2992  3764 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 10:49:20.566   872  3770 E DropBoxManagerService: Can't write: system_app_crash
08-11 10:49:20.566   872  3770 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 10:49:20.566   872  3770 E DropBoxManagerService: 	... 5 more
,08-11 10:49:20.582   872  3771 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 10:49:20.586  1772  1854 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-11 10:49:20.588   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-11 10:49:20.590   872   884 E PackageManager: Failed to write settings, restoring backup
08-11 10:49:20.590   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 10:49:20.590   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 10:49:20.590   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 10:49:20.590   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 10:49:20.590   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 10:49:20.590   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:20.590   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 10:49:20.590   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 10:49:20.591   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-11 10:49:20.591   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 10:49:20.591   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 10:49:20.591   872   885 E DropBoxManagerService: 	... 13 more
08-11 10:49:20.592  2992  3764 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-11 10:49:20.593  2992  3764 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-11 10:49:20.593  2992  3764 E AndroidRuntime: Process: android.process.acore, PID: 2992
08-11 10:49:20.593  2992  3764 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 10:49:20.593  2992  3764 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 10:49:20.598   872  1769 I ActivityManager: Start proc 3773:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-11 10:49:20.599  1772  1854 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 10:49:20.599  1772  1854 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1772
08-11 10:49:20.599  1772  1854 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 10:49:20.599  1772  1854 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 10:49:20.602   872  3779 E DropBoxManagerService: Can't write: system_app_crash
08-11 10:49:20.602   872  3779 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 10:49:20.602   872  3779 E DropBoxManagerService: 	... 5 more
,08-11 10:49:20.604   872  3784 E DropBoxManagerService: Can't write: system_app_crash
08-11 10:49:20.604   872  3784 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 10:49:20.604   872  3784 E DropBoxManagerService: 	... 5 more
,08-11 10:49:20.605  1657  3760 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-11 10:49:20.607  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-11 10:49:20.607  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-11 10:49:20.611  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 10:49:20.611  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-11 10:49:20.611   872  3758 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 10:49:20.613  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-11 10:49:20.614  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-11 10:49:20.614  1657  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 10:49:20.614  1657  3760 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 10:49:20.614  1657  3760 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 10:49:20.615  1657  3760 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 10:49:20.615  1657  3760 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 10:49:20.615  1657  3760 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-11 10:49:20.625  1815  2034 W SearchService: Abort, client detached.
08-11 10:49:20.627  1815  1815 I HotwordDetector: Closing mic
08-11 10:49:20.627  1815  2151 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6b4575d
08-11 10:49:20.629  1815  3757 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-11 10:49:20.634   872  3771 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 10:49:20.634   872  3771 I Adreno  : Build Date                       : 10/20/15
08-11 10:49:20.634   872  3771 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 10:49:20.634   872  3771 I Adreno  : Local Branch                     : M14
08-11 10:49:20.634   872  3771 I Adreno  : Remote Branch                    : 
08-11 10:49:20.634   872  3771 I Adreno  : Remote Branch                    : 
08-11 10:49:20.634   872  3771 I Adreno  : Reconstruct Branch               : 
08-11 10:49:20.640   872  3771 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 10:49:20.680  1815  3787 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-11 10:49:20.683   376  3762 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 10:49:20.684   376  3762 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 10:49:20.689   872  1767 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-11 10:49:20.691   376  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 10:49:20.696  1815  2155 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 10:49:20.697  1815  3756 I MicroRecognitionRnrImpl: Detection finished,
,08-11 10:49:20.703  1772  1772 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@85e4aed new=com.google.android.velvet.VelvetApplication@85e4aed
,08-11 10:49:20.748  1772  1772 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-11 10:49:20.770  1866  3796 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-11 10:49:20.770  1866  3796 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 10:49:20.850   872   890 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +155ms
,08-11 10:49:20.936   279   279 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20100 id=8
08-11 10:49:20.936   279   279 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,08-11 10:49:20.936   279   279 E qdoverlay: src_rect mdp_rect x=720 y=0 w=720 h=2560
08-11 10:49:20.936   279   279 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-11 10:49:20.937   279   279 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-11 10:49:20.937   279   279 E qdoverlay: MdpCtrl close error in unset
,08-11 10:49:21.216   279   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 10:49:21.216   279   279 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-11 10:49:21.216   279   279 E qdoverlay: MdpCtrl close error in unset

```
