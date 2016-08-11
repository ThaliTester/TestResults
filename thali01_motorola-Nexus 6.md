#### Test 797638305bc0289_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 13:29:11.720   873  1993 D NetlinkSocketObserver: NeighborEvent{elapsedMs=107463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 13:29:13.586  3739  3739 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 13:29:13.591  3739  3739 D AndroidRuntime: CheckJNI is OFF
08-11 13:29:13.634  3739  3739 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 13:29:13.686  3739  3739 I Radio-JNI: register_android_hardware_Radio DONE
08-11 13:29:13.710  3739  3739 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 13:29:13.718   873  1727 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 13:29:13.788  1800  3702 W SearchService: Abort, client detached.
08-11 13:29:13.792  1800  2125 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8046da2
08-11 13:29:13.792  1800  2134 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 13:29:13.792  1800  1800 I HotwordDetector: Closing mic
08-11 13:29:13.814  3739  3739 D AndroidRuntime: Shutting down VM
08-11 13:29:13.848   873  2967 I ActivityManager: Start proc 3749:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 13:29:13.860   375  2136 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 13:29:13.861   375  2136 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 13:29:13.868   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 13:29:13.870  1800  2129 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 13:29:13.870  1800  2132 I MicroRecognitionRnrImpl: Detection finished
08-11 13:29:13.945  3749  3749 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 13:29:13.987  3749  3749 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 13:29:14.007  3749  3749 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9747-9751)
08-11 13:29:14.007  3749  3749 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 13:29:14.032  3749  3749 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1df35c0}
08-11 13:29:14.032  3749  3749 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 13:29:14.032  3749  3749 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 13:29:14.043  3749  3749 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 13:29:14.045  3749  3749 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 13:29:14.069  3749  3749 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 13:29:14.086  3749  3749 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 13:29:14.086  3749  3749 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 13:29:14.086  3749  3749 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 13:29:14.086  3749  3749 I Adreno  : Build Date                       : 10/20/15
08-11 13:29:14.086  3749  3749 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 13:29:14.086  3749  3749 I Adreno  : Local Branch                     : M14
08-11 13:29:14.086  3749  3749 I Adreno  : Remote Branch                    : 
08-11 13:29:14.086  3749  3749 I Adreno  : Remote Branch                    : 
08-11 13:29:14.086  3749  3749 I Adreno  : Reconstruct Branch               : 
,08-11 13:29:14.148   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bde8325:true
,08-11 13:29:14.189  3749  3749 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 13:29:14.208  3749  3749 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 13:29:14.256  3749  3787 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 13:29:14.267  3749  3774 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 13:29:14.297  3749  3787 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 13:29:14.350   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +535ms
,08-11 13:29:14.351  1658  1658 I Keyboard.Facilitator: onFinishInput()
,08-11 13:29:14.421  3749  3749 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3749
,08-11 13:29:14.542  3749  3749 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 13:29:14.643   873   883 I ActivityManager: Killing 3090:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 13:29:14.681   873   883 I ActivityManager: Killing 2950:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-11 13:29:14.765  3749  3789 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1696859856
,08-11 13:29:14.770  3749  3789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 13:29:14.770  3749  3789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 13:29:14.770  3749  3789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 13:29:14.770  3749  3789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 13:29:14.770  3749  3789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 13:29:14.771  3749  3789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e3df44 added. We now have 1 listener(s)
,08-11 13:29:14.773  3749  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 13:29:14.774  3749  3789 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 13:29:14.775  3749  3789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 13:29:14.775  3749  3789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 13:29:14.778  3749  3789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4af2f3 added. We now have 1 listener(s)
08-11 13:29:14.778  3749  3789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 13:29:14.781   873  1308 D WifiService: New client listening to asynchronous messages
08-11 13:29:14.782  3749  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 13:29:14.782  3749  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 13:29:14.783  3749  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-11 13:29:14.783  3749  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 13:29:14.783  3749  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 13:29:14.784  3749  3789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 13:29:14.785  3749  3789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 13:29:14.790  3749  3789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 13:29:14.790  3749  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 13:29:14.790  3749  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 13:29:14.790  3749  3789 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 13:29:14.791  3749  3789 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 13:29:14.978  3749  3749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 13:29:14.990  3749  3749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 13:29:14.991  3749  3749 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 13:29:15.578  3749  3797 W jxcore-log: Initializing JXcore engine
08-11 13:29:15.578  3749  3797 W jxcore-log: JXcore engine is ready
,08-11 13:29:15.615  3797  3797 W Thread-341: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 13:29:15.615  3797  3797 W Thread-341: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11138]" dev="sockfs" ino=11138 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-11 13:29:15.615  3797  3797 W Thread-341: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 13:29:15.615  3797  3797 W Thread-341: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26859]" dev="sockfs" ino=26859 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 13:29:15.630  3749  3797 W jxcore-log: Starting JXcore engine
,08-11 13:29:15.706  3749  3797 W jxcore-log: Platform android
08-11 13:29:15.706  3749  3797 W jxcore-log: 
,08-11 13:29:15.707  3749  3797 W jxcore-log: Process ARCH arm
08-11 13:29:15.707  3749  3797 W jxcore-log: 
,08-11 13:29:15.869  3749  3797 I jxcore-log: JXcore Cordova bridge is ready!
08-11 13:29:15.869  3749  3797 I jxcore-log: 
,08-11 13:29:15.869  3749  3797 W jxcore-log: JXcore engine is started
,08-11 13:29:15.881  3749  3789 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 13:29:15.887  3749  3749 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 13:29:24.061  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 13:29:24.066  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 13:29:24.068  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 13:29:24.085  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 13:29:24.086  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 13:29:24.086  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 13:29:24.086  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 13:29:24.100  3468  3468 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 13:29:24.100  3468  3468 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 13:29:24.100  3468  3468 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-11 13:29:25.956  3749  3797 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 13:29:25.956  3749  3797 I jxcore-log: 
,08-11 13:29:25.959  3749  3797 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 13:29:25.959  3749  3797 I jxcore-log: 
,08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 13:29:25.971  3749  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 13:29:25.976  3749  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 13:29:25.978   873  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-11 13:29:25.979  3749  3797 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 13:29:25.979  3749  3797 I jxcore-log: 
,08-11 13:29:25.981  3749  3797 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 13:29:25.981  3749  3797 I jxcore-log: 
,08-11 13:29:26.314  3749  3797 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 13:29:26.314  3749  3797 I jxcore-log: Failed to execute UT.
08-11 13:29:26.314  3749  3797 I jxcore-log: 
,08-11 13:29:26.315  3749  3797 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 13:29:26.315  3749  3797 I jxcore-log: 
,08-11 13:29:26.319  3749  3797 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 13:29:26.319  3749  3797 I jxcore-log: 
08-11 13:29:26.332  3749  3749 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 13:29:26.955  3807  3807 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 13:29:26.960  3807  3807 D AndroidRuntime: CheckJNI is OFF
,08-11 13:29:26.996  3807  3807 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 13:29:27.039  3807  3807 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 13:29:27.060  3807  3807 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 13:29:27.074   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 13:29:27.075   873   886 I ActivityManager: Killing 3749:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 13:29:27.187   873  1754 I WindowState: WIN DEATH: Window{eef7f95 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 13:29:27.188   873  2968 D GraphicsStats: Buffer count: 2
08-11 13:29:27.189   873  1308 D WifiService: Client connection lost with reason: 4
,08-11 13:29:27.218   873   886 W ActivityManager: Force removing ActivityRecord{99921f2 u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-11 13:29:27.229   873   896 W PackageSettings: Skipping PackageSetting{db3202f com.example.hello/10273} due to missing metadata
,08-11 13:29:27.264   873   896 I art     : Starting a blocking GC Explicit
,08-11 13:29:27.268   873   883 W ActivityManager: Spurious death for ProcessRecord{d70040a 0:com.test.thalitest/u0a0}, curProc for 3749: null
,08-11 13:29:27.311   873   896 I art     : Explicit concurrent mark sweep GC freed 28350(1944KB) AllocSpace objects, 8(164KB) LOS objects, 33% free, 29MB/43MB, paused 837us total 44.447ms
,08-11 13:29:27.314   873  1727 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3749 uid 10000
,08-11 13:29:27.323  1658  1658 I Keyboard.Facilitator: onFinishInput()
,08-11 13:29:27.332   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1,
,08-11 13:29:27.334  3807  3807 I art     : System.exit called, status: 0
,08-11 13:29:27.334  3807  3807 I AndroidRuntime: VM exiting with result code 0.
,08-11 13:29:27.342   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 13:29:27.364  1658  1658 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-11 13:29:27.366  2559  2559 D BluetoothMapAppObserver: onReceive
,08-11 13:29:27.366  2559  2559 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 13:29:27.369  3588  3588 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) },
08-11 13:29:27.370  1872  2042 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 13:29:27.377  1658  3820 I Keyboard.Facilitator.DecoderInitializer: run()
,08-11 13:29:27.385   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 13:29:27.406  1800  1800 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-11 13:29:27.409  1658  3820 I Decoder : createOrResetDecoder
,08-11 13:29:27.420  1742  1742 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 13:29:27.446  1800  3826 I MicroRecognitionRnrImpl: Starting detection.
,08-11 13:29:27.447  1800  3827 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@7b8b7ae
08-11 13:29:27.450  1507  1507 I ConfigService: onCreate
08-11 13:29:27.452   375  3829 I AudioFlinger: AudioFlinger's thread 0xb1b40000 ready to run
,08-11 13:29:27.456   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 13:29:27.456  1800  3827 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@7b8b7ae
,08-11 13:29:27.466   375  3829 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-11 13:29:27.466   375  3829 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-11 13:29:27.466   375  3829 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-11 13:29:27.476   375  3829 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-11 13:29:27.477  1507  1507 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-11 13:29:27.477  1507  1507 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-11 13:29:27.484  1691  3825 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 13:29:27.488  1658  3820 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-11 13:29:27.498  1857  3832 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-11 13:29:27.498  1857  3832 D AccountUtils: Clearing selected account for com.test.thalitest
,08-11 13:29:27.500   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 13:29:27.515  1857  3832 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-11 13:29:27.519  1857  1857 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-11 13:29:27.519  1857  1857 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-11 13:29:27.533  1857  1857 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-11 13:29:27.533  1857  1857 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-11 13:29:27.535  1800  3840 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 13:29:27.535  1857  3838 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-11 13:29:27.535  1857  3838 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-11 13:29:27.536  1857  3838 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
08-11 13:29:27.536  1857  3838 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,--------- beginning of crash
08-11 13:29:27.536  1857  3838 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-11 13:29:27.536  1857  3838 E AndroidRuntime: Process: com.google.android.gms, PID: 1857
08-11 13:29:27.536  1857  3838 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.536  1857  3838 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:27.539  1857  3842 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 13:29:27.539  1857  3842 I Process : Sending signal. PID: 1857 SIG: 9
,08-11 13:29:27.560  1800  1800 I HotwordWorkerImpl: onReady
,08-11 13:29:27.570  1800  3840 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 13:29:27.571   873  3846 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 13:29:27.583   873  1386 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2d6a8df)
,08-11 13:29:27.584   873  1309 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 13:29:27.585   873  1309 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 13:29:27.588  1691  3825 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-11 13:29:27.588  1658  3820 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-11 13:29:27.590  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-11 13:29:27.590  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-11 13:29:27.592  1691  3825 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-11 13:29:27.592  1691  3825 E AndroidRuntime: Process: android.process.acore, PID: 1691
08-11 13:29:27.592  1691  3825 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.592  1691  3825 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:27.595  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-11 13:29:27.595  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-11 13:29:27.596  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-11 13:29:27.597   873  1729 I ActivityManager: Start proc 3851:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-11 13:29:27.597  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-11 13:29:27.598  1800  3840 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,08-11 13:29:27.598  1800  3840 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-11 13:29:27.598  1800  3840 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1800
08-11 13:29:27.598  1800  3840 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.598  1800  3840 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:27.598  1756  2153 E ReflectionEngine: Failed to save models
08-11 13:29:27.598  1756  2153 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.598  1756  2153 E ReflectionEngine: 	... 16 more
,08-11 13:29:27.602  1658  3820 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 13:29:27.602  1658  3820 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 13:29:27.602  1658  3820 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 13:29:27.602  1658  3820 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 13:29:27.602  1658  3820 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 13:29:27.602  1658  3820 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-11 13:29:27.614   873   883 I ActivityManager: Start proc 3863:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-11 13:29:27.616   873   884 I ActivityManager: Process com.google.android.gms (pid 1857) has died
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: Failed to write the stream file
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2427: open failed: EROFS (Read-only file system)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.619  1756  2153 E ObservedEventLogger: 	... 16 more
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: Failed to write the stream file
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.620  1756  2153 E ObservedEventLogger: 	... 16 more
08-11 13:29:27.624   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
08-11 13:29:27.624   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
08-11 13:29:27.624   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
08-11 13:29:27.625   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
,08-11 13:29:27.625   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
08-11 13:29:27.625   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
08-11 13:29:27.625   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
08-11 13:29:27.626   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20999ms
08-11 13:29:27.629   873  3874 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:27.629   873  3874 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.629   873  3874 E DropBoxManagerService: 	... 5 more
08-11 13:29:27.635   873  3846 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 13:29:27.635   873  3846 I Adreno  : Build Date                       : 10/20/15
08-11 13:29:27.635   873  3846 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 13:29:27.635   873  3846 I Adreno  : Local Branch                     : M14
08-11 13:29:27.635   873  3846 I Adreno  : Remote Branch                    : 
08-11 13:29:27.635   873  3846 I Adreno  : Remote Branch                    : 
08-11 13:29:27.635   873  3846 I Adreno  : Reconstruct Branch               : 
08-11 13:29:27.640   873  3875 E DropBoxManagerService: Can't write: system_app_crash
,08-11 13:29:27.640   873  3875 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.640   873  3875 E DropBoxManagerService: 	... 5 more
,08-11 13:29:27.641   873  3846 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 13:29:27.646  1756  1825 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-11 13:29:27.649  1756  1825 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 13:29:27.649  1756  1825 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1756
08-11 13:29:27.649  1756  1825 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.649  1756  1825 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 13:29:27.658   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 13:29:27.660   873   883 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-11 13:29:27.660   873   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 13:29:27.661   873   885 E PackageManager: Failed to write settings, restoring backup
08-11 13:29:27.661   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 13:29:27.661   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 13:29:27.661   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 13:29:27.661   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 13:29:27.661   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 13:29:27.661   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.661   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.661   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 13:29:27.664   873   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-11 13:29:27.667   873  3879 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:27.667   873  3879 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 1,3:29:27.667   873  3879 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.667   873  3879 E DropBoxManagerService: 	... 5 more
08-11 13:29:27.670   873   883 I ActivityManager: Killing 1756:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-11 13:29:27.674  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-11 13:29:27.681   873  1727 W WindowManager: Failed looking up window
08-11 13:29:27.681   873  1727 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@b60ff65 does not exist
08-11 13:29:27.681   873  1727 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8736)
08-11 13:29:27.681   873  1727 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8727)
08-11 13:29:27.681   873  1727 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:3105)
08-11 13:29:27.681   873  1727 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:198)
08-11 13:29:27.681   873  1727 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:284)
08-11 13:29:27.681   873  1727 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:130)
08-11 13:29:27.681   873  1727 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 13:29:27.684  3863  3863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-11 13:29:27.719   873  1729 D GraphicsStats: Buffer count: 2
,08-11 13:29:27.720  1800  1800 E AttachedClient: AttachedClient[7541962592902, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-11 13:29:27.720  1800  1800 E AttachedClient: android.os.DeadObjectException
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 13:29:27.720  1800  1800 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 13:29:27.720  1800  1800 I SearchService: Ignoring already detached client
,08-11 13:29:27.722  1800  1800 I HotwordDetector: Closing mic
,08-11 13:29:27.722  1800  2125 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7b8b7ae
08-11 13:29:27.722  1800  3827 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-11 13:29:27.742   873   883 I ActivityManager: Start proc 3881:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-11 13:29:27.745   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-11 13:29:27.745   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 13:29:27.745   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.745   873   886 E DropBoxManagerService: 	... 13 more
08-11 13:29:27.749   873  1776 W ActivityManager: Spurious death for ProcessRecord{b59dae7 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1756: null
,08-11 13:29:27.790   375  3829 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-11 13:29:27.790   375  3829 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 13:29:27.794   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 13:29:27.795  3881  3881 E SQLiteDatabase: 	at com.android.internal.os.Zygo,teInit.main(ZygoteInit.java:616)
,08-11 13:29:27.795  3881  3881 D AndroidRuntime: Shutting down VM
,08-11 13:29:27.802  1800  3826 I MicroRecognitionRnrImpl: Detection finished
,08-11 13:29:27.803  1800  2129 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-11 13:29:27.811  3881  3881 E AndroidRuntime: FATAL EXCEPTION: main
08-11 13:29:27.811  3881  3881 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3881
08-11 13:29:27.811  3881  3881 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 13:29:27.811  3881  3881 E AndroidRuntime: 	... 10 more
,08-11 13:29:27.815   873  3896 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:27.815   873  3896 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.815   873  3896 E DropBoxManagerService: 	... 5 more
,08-11 13:29:27.816   873  1754 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 13:29:27.816   873  3846 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 13:29:27.816   873  3846 I Adreno  : Build Date                       : 10/20/15
08-11 13:29:27.816   873  3846 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 13:29:27.816   873  3846 I Adreno  : Local Branch                     : M14
08-11 13:29:27.816   873  3846 I Adreno  : Remote Branch                    : 
08-11 13:29:27.816   873  3846 I Adreno  : Remote Branch                    : 
08-11 13:29:27.816   873  3846 I Adreno  : Reconstruct Branch               : 
,08-11 13:29:27.819   873  3846 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 13:29:27.833  1800  3895 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-11 13:29:27.842   873   883 I ActivityManager: Start proc 3899:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-11 13:29:27.875  3863  3898 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.875  3863  3898 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:27.875  3863  3898 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-11 13:29:27.875  3863  3898 E AndroidRuntime: Process: com.android.keychain, PID: 3863
08-11 13:29:27.875  3863  3898 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.875  3863  3898 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:27.877   873  3912 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:27.877   873  3912 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:27.877   873  3912 E DropBoxManagerService: 	... 5 more
,08-11 13:29:27.897   873   873 I ActivityManager: Start proc 3913:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-11 13:29:27.922  3899  3899 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 13:29:27.932  3899  3899 I MultiDex: VM with version 2.1.0 has multidex support
,08-11 13:29:27.932  3899  3899 I MultiDex: install
,08-11 13:29:27.932  3899  3899 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 13:29:27.959  3913  3913 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-11 13:29:27.969   873   891 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-11 13:29:27.997  3913  3913 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.documentsui/databases/recents.db'.
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 13:29:27.997  3913  3913 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 13:29:28.009  3913  3913 D AndroidRuntime: Shutting down VM
,08-11 13:29:28.011  3913  3913 E AndroidRuntime: FATAL EXCEPTION: main
08-11 13:29:28.011  3913  3913 E AndroidRuntime: Process: com.android.documentsui, PID: 3913
08-11 13:29:28.011  3913  3913 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-11 13:29:28.011  3913  3913 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 13:29:2,8.011  3913  3913 E AndroidRuntime: 	... 8 more
,08-11 13:29:28.015  1359  2130 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10000)] disk I/O error
,08-11 13:29:28.016  1359  2130 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-11 13:29:28.016  1359  2130 E AndroidRuntime: Process: android.process.media, PID: 1359
08-11 13:29:28.016  1359  2130 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1215)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.-wrap1(DownloadReceiver.java)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:28.016  1359  2130 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:28.018   873  3926 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:28.018   873  3926 E DropBoxManagerService: 	... 5 more
,08-11 13:29:28.018   873  3927 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:28.018   873  3927 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:28.018   873  3927 E DropBoxManagerService: 	... 5 more
,08-11 13:29:28.095   873  1751 I ActivityManager: Start proc 3929:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,08-11 13:29:28.156  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/ExternalStorageProvider/lib/arm
,08-11 13:29:28.178  3929  3929 D ExternalStorage: After updating volumes, found 1 active roots
,08-11 13:29:28.234  3899  3899 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 13:29:28.271  3899  3899 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 13:29:28.277  1507  2315 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-11 13:29:28.318   873   886 W ActivityManager: Activity pause timeout for ActivityRecord{f3d32a9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t9 f}
,08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: Failed to open lock file
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: java.io.FileNotFoundException: /data/user/0/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:171)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:28.372  3899  3945 W NativeLibraryUtils: 	... 3 more
,08-11 13:29:28.424   873  1727 I ActivityManager: Start proc 3948:com.android.shell/2000 for content provider com.android.shell/.BugreportStorageProvider
,08-11 13:29:28.454   873  1751 I ActivityManager: Killing 2847:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-11 13:29:28.514  3948  3948 W System  : ClassLoader referenced unknown path: /system/priv-app/Shell/lib/arm
,08-11 13:29:28.577  3899  3899 I GAv4-SVC: Google Analytics 8.1.86 is starting up.
,08-11 13:29:28.603  3913  3925 D Documents: Update found 8 roots in 613ms
,08-11 13:29:28.632  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-11 13:29:28.633  1658  3820 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-11 13:29:28.633  1658  3820 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-11 13:29:28.652  1658  3820 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-11 13:29:28.652  1658  3820 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-11 13:29:28.658  1658  3820 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-11 13:29:28.658  1658  3820 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-11 13:29:28.658  1658  3820 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-11 13:29:28.658  1658  3820 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-11 13:29:28.661  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 13:29:28.667  3899  3899 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-11 13:29:28.707  3899  3969 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/reminders.db'.
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:28.707  3899  3969 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:28.708  3899  3970 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method,)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:28.708  3899  3969 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_analytics_v4.db'.
,08-11 13:29:28.710  3899  3967 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:28.710  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.measurement.n.run(SourceFile:388)
,08-11 13:29:28.719  3396  3396 D WearableService: callingUid 10011, callindPid: 3396
,08-11 13:29:28.725  3899  3970 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 13:29:28.730  1872  2257 E MDM     : [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 13:29:28.736  3899  3970 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-11 13:29:28.738  3899  3970 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 13:29:28.710  3899  3967 E GAv4-SVC: Opening the database failed, dropping the table and recreating it
,08-11 13:29:28.754  3899  3970 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-11 13:29:28.755  3899  3970 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 13:29:28.759  3899  3967 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-11 13:29:28.771  3899  3967 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_analytics_v4.db'.
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:28.771  3899  3967 E SQLiteDatabase: 	at com.google.android.gms.measurement.n.run(SourceFile:388)
08-11 13:29:28.771  3899  3967 E GAv4-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,08-11 13:29:28.775  3899  3969 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,08-11 13:29:28.779  3899  3975 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-11 13:29:28.784  3899  3975 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-11 13:29:28.784  3899  3967 W GAv4-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,08-11 13:29:28.785  3899  3975 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-11 13:29:28.785  3899  3967 E GAv4-SVC: Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,08-11 13:29:28.791  3899  3975 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-11 13:29:28.801  3899  3976 D LocationInitializer: Restart initialization of location
,08-11 13:29:28.813  3899  3960 I Icing   : Storage manager: low false usage 2.01MB avail 21.47GB capacity 22.09GB
,08-11 13:29:28.823  3899  3978 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/plus.db'.
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:28.823  3899  3978 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:28.836  3899  3978 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2
08-11 13:29:28.836  3899  3978 E AndroidRuntime: Process: com.google.android.gms, PID: 3899
08-11 13:29:28.836  3899  3978 E AndroidRuntime: java.lang.RuntimeException: An error occurred while executing doInBackground()
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:28.836  3899  3978 E AndroidRuntime: 	... 4 more
,08-11 13:29:28.854   873  3982 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:28.854   873  3982 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:28.854   873  3982 E DropBoxManagerService: 	... 5 more
,08-11 13:29:28.860  1872  1991 W GCoreFlp: No location to return for getLastLocation()
,08-11 13:29:28.862  1507  3977 W FusedLocationProvider: location=null
,08-11 13:29:28.865  3899  3960 W Icing   : Received bad json for section weights override -- ignoring.
,08-11 13:29:28.869  3899  3960 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,08-11 13:29:28.869  3899  3960 W Icing   : Received bad json for section weights override -- ignoring.
08-11 13:29:28.869  3899  3960 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,08-11 13:29:28.896  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
,08-11 13:29:28.897  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
,08-11 13:29:28.897  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Trie initialize fail
08-11 13:29:28.897  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
08-11 13:29:28.897  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
08-11 13:29:28.898  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
,08-11 13:29:28.898  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
08-11 13:29:28.899  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
08-11 13:29:28.899  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
08-11 13:29:28.899  3899  3960 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
,08-11 13:29:28.899  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
,08-11 13:29:28.901  3899  3960 E Icing   : Init docstore failed
08-11 13:29:28.901  3899  3960 E Icing   : Index init failed, resetting corpora
,08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
,08-11 13:29:28.908  3899  3960 E Icing   : Clearing index failed
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
,08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-2 failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-34 failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
08-11 13:29:28.908  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
,08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
,08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
,08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
08-11 13:29:28.909  3899  3960 E Icing   : Clearing docstore failed
08-11 13:29:28.909  3899  3960 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
08-11 13:29:28.910  3899  3960 E Icing   : Deleting compact status failed
,08-11 13:29:30.364  2928  3986 V KeepSync: Connecting to GoogleApiClient
,08-11 13:29:30.364   873  2968 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 13:29:30.480  3899  3987 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/DocList.db'.
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:30.480  3899  3987 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
,08-11 13:29:30.481  3899  3987 I Process : Sending signal. PID: 3899 SIG: 9
,08-11 13:29:30.574   873  1751 I ActivityManager: Process com.google.android.gms (pid 3899) has died
,08-11 13:29:30.575   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.signin.service.SignInBrokerService in 1000ms
,08-11 13:29:30.576   873  1751 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{bba3ad4 u0 com.google.android.gms/.icing.service.IndexService}
08-11 13:29:30.577   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.signin.service.SignInAsyncService in 10998ms
,08-11 13:29:30.578   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 20997ms
08-11 13:29:30.575  2928  3986 V KeepSync: GoogleApiClient failed to connect with error code: 8
08-11 13:29:30.578   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 30997ms
08-11 13:29:30.579   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.people.service.PeopleService in 40996ms
08-11 13:29:30.579   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 50996ms
,08-11 13:29:30.580  2928  3986 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-11 13:29:30.580   873  1751 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{b49f0 u0 com.google.android.gms/.analytics.service.AnalyticsService}
,08-11 13:29:30.593  2928  3986 E AndroidRuntime: FATAL EXCEPTION: SyncAdapterThread-3
08-11 13:29:30.593  2928  3986 E AndroidRuntime: Process: com.google.android.keep, PID: 2928
08-11 13:29:30.593  2928  3986 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at com.android.common.content.SQLiteContentProvider.update(SourceFile:153)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.cleanDeleteState(SourceFile:460)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.cleanDatabase(SourceFile:435)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:185)
08-11 13:29:30.593  2928  3986 E AndroidRuntime: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,08-11 13:29:30.608   873  3990 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:30.608   873  3990 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:30.608   873  3990 E DropBoxManagerService: 	... 5 more
,08-11 13:29:30.619   873   885 W AtomicFile: Couldn't rename file /data/system/sync/status.bin to backup file /data/system/sync/status.bin.bak
,08-11 13:29:30.621   873   885 W SyncManager: Error writing status
08-11 13:29:30.621   873   885 W SyncManager: java.io.IOException: Couldn't create directory /data/system/sync/status.bin
08-11 13:29:30.621   873   885 W SyncManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 13:29:30.621   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.writeStatusLocked(SyncStorageEngine.java:2456)
08-11 13:29:30.621   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.stopSyncEvent(SyncStorageEngine.java:1434)
08-11 13:29:30.621   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.stopSyncEvent(SyncManager.java:3334)
08-11 13:29:30.621   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledH(SyncManager.java:3102)
08-11 13:29:30.621   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2241)
08-11 13:29:30.621   873   885 W SyncManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:30.621   873   885 W SyncManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:30.621   873   885 W SyncManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:30.794  1507  2891 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 13:29:30.795  1507  2891 E DatabaseUtils: Writing exception to parcel
08-11 13:29:30.795  1507  2891 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at com.google.android.gsf.subscribedfeeds.AbstractSyncableContentProvider.delete(AbstractSyncableContentProvider.java:328)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
08-11 13:29:30.795  1507  2891 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 13:29:30.797   873   891 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-11 13:29:30.816   873   885 W AtomicFile: Couldn't rename file /data/system/sync/status.bin to backup file /data/system/sync/status.bin.bak
,08-11 13:29:30.817   873   885 W SyncManager: Error writing status
08-11 13:29:30.817   873   885 W SyncManager: java.io.IOException: Couldn't create directory /data/system/sync/status.bin
08-11 13:29:30.817   873   885 W SyncManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 13:29:30.817   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.writeStatusLocked(SyncStorageEngine.java:2456)
08-11 13:29:30.817   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.stopSyncEvent(SyncStorageEngine.java:1434)
08-11 13:29:30.817   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.stopSyncEvent(SyncManager.java:3334)
08-11 13:29:30.817   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledH(SyncManager.java:3102)
08-11 13:29:30.817   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2241)
08-11 13:29:30.817   873   885 W SyncManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:29:30.817   873   885 W SyncManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 13:29:30.817   873   885 W SyncManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 13:29:30.832  3508  3991 E EsApplication: Uncaught exception in background thread Thread[SyncAdapterThread-2,5,main]
08-11 13:29:30.832  3508  3991 E EsApplication: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:177)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:135)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:544)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at czp.a(PG:6863)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at czq.run(PG:1612)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:30.832  3508  3991 E EsApplication: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:30.847  3508  3508 E AndroidRuntime: FATAL EXCEPTION: SyncAdapterThread-2
08-11 13:29:30.847  3508  3508 E AndroidRuntime: Process: com.google.android.apps.plus, PID: 3508
08-11 13:29:30.847  3508  3508 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:177)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:135)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:544)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at czp.a(PG:6863)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at czq.run(PG:1612)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:30.847  3508  3508 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:30.848  1507  3993 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791),
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:30.848  1507  3993 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113),
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:30.849  1507  3993 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:30.855  1507  3993 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-11 13:29:30.855  1507  3993 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,08-11 13:29:30.855   873  3994 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:30.855   873  3994 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:30.855   873  3994 E DropBoxManagerService: 	... 5 more
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:30.856  1507  3993 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:31.621   873   886 I ActivityManager: Start proc 3995:com.google.android.gms/u0a11 for service com.google.android.gms/.signin.service.SignInBrokerService
,08-11 13:29:31.738  3995  3995 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 13:29:31.758  3995  3995 I MultiDex: VM with version 2.1.0 has multidex support
,08-11 13:29:31.758  3995  3995 I MultiDex: install
08-11 13:29:31.758  3995  3995 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 13:29:31.932  3995  3995 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 13:29:31.955  3995  3995 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 13:29:31.963  1507  2484 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: Failed to open lock file
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: java.io.FileNotFoundException: /data/user/0/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:171)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:31.966  3995  4010 W NativeLibraryUtils: 	... 3 more
,08-11 13:29:32.015  3995  4011 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/DocList.db'.
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:32.015  3995  4011 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
,08-11 13:29:32.016  3995  4011 E AndroidRuntime: FATAL EXCEPTION: Open database in background
08-11 13:29:32.016  3995  4011 E AndroidRuntime: Process: com.google.android.gms, PID: 3995
08-11 13:29:32.016  3995  4011 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:32.016  3995  4011 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
,08-11 13:29:32.023   873  4012 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:32.023   873  4012 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:32.023   873  4012 E DropBoxManagerService: 	... 5 more
,08-11 13:29:32.026  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-11 13:29:32.058   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7c7414b u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{cbc98c5 3995 com.google.android.gms/10011/u0 remote:f79c33c}: process crashing
,08-11 13:29:32.063  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 13:29:32.077   873  1690 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/3995 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 13:29:32.161  3995  4016 W DriveInitializer: Background init thread started
,08-11 13:29:32.165  3995  4017 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/reminders.db'.
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:32.165  3995  4017 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:1017)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:491)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:434)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 13:29:32.165  3995  4017 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-11 13:29:32.167  3995  4017 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,08-11 13:29:32.168  3995  4016 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/DocList.db'.
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:246)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:327)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1048)
08-11 13:29:32.168  3995  4016 E SQLiteDatabase: 	at com.google.android.gms.drive.s.run(SourceFile:63)
,08-11 13:29:32.169  3995  3995 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-11 13:29:32.170  3995  4016 E DocListDatabase: Failed to delete from ContentFileDeletionLock143 table
08-11 13:29:32.170  3995  4016 E DocListDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:246)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:327)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1048)
08-11 13:29:32.170  3995  4016 E DocListDatabase: 	at com.google.android.gms.drive.s.run(SourceFile:63)
08-11 13:29:32.170  3995  4016 W DriveInitializer: Background init thread ended
08-11 13:29:32.171  3995  4016 I Process : Sending signal. PID: 3995 SIG: 9
,08-11 13:29:32.245   873  1729 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@98a6340)
,08-11 13:29:32.246   873  1309 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 13:29:32.247   873  1751 I ActivityManager: Process com.google.android.gms (pid 3995) has died
08-11 13:29:32.248   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.signin.service.SignInBrokerService in 1000ms
08-11 13:29:32.249   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.signin.service.SignInAsyncService in 10999ms
08-11 13:29:32.250   873  1309 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-11 13:29:32.251   873  1751 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ab25e02 u0 com.google.android.gms/.usagereporting.service.UsageReportingService}
08-11 13:29:32.252   873  1751 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a2a9f42 u0 com.google.android.gms/.feedback.FeedbackService}
,08-11 13:29:32.253   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.people.service.PeopleService in 10995ms
,08-11 13:29:32.253   873  1751 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 20995ms
,08-11 13:29:32.274  1872  2295 E MDM     : [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 13:29:32.292   873  1394 I ActivityManager: Start proc 4020:com.google.android.gms/u0a11 for broadcast com.google.android.gms/.photos.InitializePhotosIntentReceiver
,08-11 13:29:32.397  4020  4020 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 13:29:32.425  4020  4020 I MultiDex: VM with version 2.1.0 has multidex support
08-11 13:29:32.425  4020  4020 I MultiDex: install
08-11 13:29:32.425  4020  4020 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 13:29:32.446   873   891 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-11 13:29:32.585  1507  1507 I ConfigService: onDestroy
,08-11 13:29:32.596  4020  4020 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 13:29:32.600   873  1993 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 13:29:32.627  4020  4020 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 13:29:32.678   976   976 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
08-11 13:29:32.678   976   976 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
08-11 13:29:32.679   976   976 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
08-11 13:29:32.679   976   976 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: Failed to open lock file
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: java.io.FileNotFoundException: /data/user/0/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:171)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:32.711  4020  4036 W NativeLibraryUtils: 	... 3 more
,08-11 13:29:32.719   375  1264 D         : csd_client_error_cb: error -2 cb_data 0xb41d4060
,08-11 13:29:32.719   385  1050 E ThermalEngine: qmi_clnt_error_cb: with error -2 called for clnt FUSION
08-11 13:29:32.720   375  1264 D         : csd_client_error_cb: MDM reset
,08-11 13:29:32.720   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb0
,08-11 13:29:32.720   385  1050 E ThermalEngine: modem_clnt_error_cb: with -2 called for clnt 0x6
08-11 13:29:32.720   393  1061 I Atfwd_Daemon: Modem Out Of Service --> Release ATCOP service client handles, if any
,08-11 13:29:32.720   393  1061 I Atfwd_Daemon: release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
,08-11 13:29:32.721   375  1262 E         : deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
,08-11 13:29:32.721   375  1262 E         : csd_service_deinit: Error -1 deiniting CSD
,08-11 13:29:32.722   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb6
08-11 13:29:32.722   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb4
,08-11 13:29:32.723   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb1
,08-11 13:29:32.723   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb3
08-11 13:29:32.723   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb2
08-11 13:29:32.724   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb7
08-11 13:29:32.726   385  4039 I ThermalEngine: qmi: Instance id 157 for fusion TS
08-11 13:29:32.727   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb1
,08-11 13:29:32.728   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb0
08-11 13:29:32.731   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rmnet_usb5
08-11 13:29:32.731   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb3
08-11 13:29:32.732   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb2
08-11 13:29:32.732   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb4
08-11 13:29:32.733   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb5
08-11 13:29:32.733   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb6
08-11 13:29:32.733   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb7
08-11 13:29:32.734   393  1061 I Atfwd_Daemon: Received sys_event: 2 from QMI devId: rev_rmnet_usb8
,08-11 13:29:32.747   375  1262 E         : csd_service_deinit: notifier handle release rc:0
,08-11 13:29:32.757   375  1262 D         : csd_service_init: qmi_client_notifier_init() successful
,08-11 13:29:32.818   385  1058 E ThermalEngine: qmi_clnt_error_cb: with error -2 called for clnt MODEM
,08-11 13:29:32.843  1800  4064 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-11 13:29:32.844  4020  4065 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/DocList.db'.
,08-11 13:29:32.844  4020  4065 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:32.844  4020  4065 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
,08-11 13:29:32.845  4020  4065 E AndroidRuntime: FATAL EXCEPTION: Open database in background
08-11 13:29:32.845  4020  4065 E AndroidRuntime: Process: com.google.android.gms, PID: 4020
08-11 13:29:32.845  4020  4065 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-11 13:29:32.845  4020  4065 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
,08-11 13:29:32.847   873  1394 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
,08-11 13:29:32.847   873  1394 I ActivityManager: Killing 4020:com.google.android.gms/u0a11 (adj 0): crash
08-11 13:29:32.848   873  4066 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:29:32.848   873  4066 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 13:29:32.848   873  4066 E DropBoxManagerService: 	... 5 more
,08-11 13:29:32.858   873  1708 E LocSvc_ApiV02: E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2686]: Service unavailable error
,08-11 13:29:32.858   873  1780 E LocSvc_ApiV02: E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2686]: Service unavailable error
,08-11 13:29:32.886   391   980 D QC-time-services: Daemon:genoff_modem_qmi_init: Initiallizing QMI 
,08-11 13:29:32.886   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
,08-11 13:29:32.887   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
08-11 13:29:32.887   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
,08-11 13:29:32.888   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
,08-11 13:29:32.888   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
08-11 13:29:32.889   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
,08-11 13:29:32.889   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
08-11 13:29:32.890   391   980 E QMI_FW  : QMUXD: WARNING qmi_qmux_if_pwr_up_init failed! rc=-1
08-11 13:29:32.890   391   980 E QC-time-services: Daemon:genoff_modem_qmi_init: qmi_client_get_service_list returned -2num_services 0
,08-11 13:29:32.892   873  1690 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,08-11 13:29:32.894   873  3988 W ActivityManager: Spurious death for ProcessRecord{22be422 0:com.google.android.gms/u0a11}, curProc for 4020: null
,08-11 13:29:32.897   873  1394 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
08-11 13:29:32.897  1507  2821 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-11 13:29:32.899  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-11 13:29:32.905  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 13:29:32.906   873  1751 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,08-11 13:29:32.908   873  1729 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,08-11 13:29:32.910   873  1690 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,08-11 13:29:32.912   873   886 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,08-11 13:29:32.913   873  1690 W BroadcastQueue: Unable to launch app com.google.android.gms/10011 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,08-11 13:29:32.913  1872  2319 E MDM     : [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 13:29:32.958   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-11 13:29:32.958   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-11 13:29:32.958   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-11 13:29:32.958   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-11 13:29:32.958   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-11 13:29:32.958   280   280 E qdoverlay: MdpCtrl close error in unset
08-11 13:29:32.972  1742  3293 V ImsSenderRxr: Read packet: 15 bytes
08-11 13:29:32.972  1742  3293 D ImsSenderRxr:  Tag -1 3 213 0
,08-11 13:29:32.974   375  1279 I str_params: key: 'all_call_states' value: ''
,08-11 13:29:32.974   375  1316 I str_params: key: 'all_call_states' value: ''
08-11 13:29:32.975   375  1315 I str_params: key: 'all_call_states' value: ''

```
