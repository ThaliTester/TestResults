#### Test 72145431744cc2c_thali03_LGE-Nexus 5 Logs


```
--------- beginning of system
07-12 11:35:59.713   787  1324 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@bb22778
,--------- beginning of main
07-12 11:36:00.489  3015  3015 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:36:00.493  3015  3015 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:00.528  3015  3015 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:36:00.564  3015  3015 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:36:00.582  3015  3015 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:36:00.585   787  1332 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:36:00.609  1399  1410 W SearchService: Abort, client detached.
07-12 11:36:00.614  3015  3015 D AndroidRuntime: Shutting down VM
07-12 11:36:00.622  1399  1561 I DeviceStateChecker: DeviceStateChecker cancelled
07-12 11:36:00.625  1399  1399 I MicroDetector: Keeping mic open: false
07-12 11:36:00.625  1399  1399 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@4b01307
07-12 11:36:00.625  1399  1516 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-12 11:36:00.647   787  1245 I ActivityManager: Start proc 3031:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-12 11:36:00.674   197  1588 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-12 11:36:00.674   197  1588 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-12 11:36:00.680  1399  1586 I MicroRecognitionRunner: Detection finished
07-12 11:36:00.681  1399  1560 I MicroRecognitionRunner: Stopping hotword detection.
07-12 11:36:00.722  3031  3031 I WebViewFactory: Loading com.google.android.webview version 51.0.2704.81 (code 270408100)
07-12 11:36:00.750  3031  3031 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 469-471)
07-12 11:36:00.750  3031  3031 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-12 11:36:00.772  3031  3031 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6420755}
07-12 11:36:00.772  3031  3031 I cr_LibraryLoader: Expected native library version number "51.0.2704.81", actual native library version number "51.0.2704.81"
07-12 11:36:00.773  3031  3031 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:36:00.795   787   892 D WifiService: New client listening to asynchronous messages
07-12 11:36:00.806  3031  3031 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-12 11:36:00.820  3031  3031 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-12 11:36:00.821  3031  3031 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
07-12 11:36:00.833  3031  3031 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:00.880   787   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f2636b5:true
07-12 11:36:00.915   787   800 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3031 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:00.925  3031  3031 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
07-12 11:36:00.932  3031  3031 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 11:36:00.933  3031  3031 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
07-12 11:36:00.944  3031  3031 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-12 11:36:00.966  3031  3031 I cr_Ime  : ImeThread is not enabled.
07-12 11:36:00.976  3031  3079 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-12 11:36:01.011   787   983 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/3031 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:01.048  3031  3087 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:01.069  3031  3087 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:36:01.090  3031  3087 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-12 11:36:01.132   189   189 D SurfaceFlinger: shader cache generated - 24 shaders in 136.431870 ms
07-12 11:36:01.166  3031  3079 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 11:36:01.219   787   808 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +591ms
07-12 11:36:01.270  3031  3031 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3031
07-12 11:36:01.271  3031  3031 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
07-12 11:36:01.271  3031  3031 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
07-12 11:36:01.361  3031  3031 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-12 11:36:01.362   787   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:01.437   787  1356 I ActivityManager: Killing 2335:com.google.android.gms.feedback/u0a7 (adj 15): empty #17
07-12 11:36:01.520   787  1245 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
07-12 11:36:01.570  3031  3098 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1721304784
07-12 11:36:01.573  3031  3098 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:01.573  3031  3098 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:01.573  3031  3098 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:01.573  3031  3098 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:01.573  3031  3098 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:36:01.573  3031  3098 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49c9901 added. We now have 1 listener(s)
07-12 11:36:01.575  3031  3098 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
07-12 11:36:01.577  3031  3098 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-12 11:36:01.577  3031  3098 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:01.577  3031  3098 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:36:01.580  3031  3098 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f961194 added. We now have 1 listener(s)
07-12 11:36:01.580  3031  3098 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 11:36:01.581  3031  3098 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:01.582  3031  3098 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:36:01.583  3031  3098 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:01.584  3031  3098 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:01.584  3031  3098 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:01.584  3031  3098 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 11:36:01.586  3031  3098 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:36:01.586  3031  3098 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
07-12 11:36:01.589  3031  3098 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:01.589  3031  3098 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:01.589  3031  3098 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:01.589  3031  3098 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:01.590  3031  3098 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 11:36:01.615  3031  3031 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:02.383  3031  3099 W jxcore-log: Initializing JXcore engine
,07-12 11:36:02.383  3031  3099 W jxcore-log: JXcore engine is ready
,07-12 11:36:02.409  3099  3099 W Thread-274: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10316]" dev="sockfs" ino=10316 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-12 11:36:02.409  3099  3099 W Thread-274: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-12 11:36:02.409  3099  3099 W Thread-274: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[20501]" dev="sockfs" ino=20501 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 11:36:02.432  3031  3099 W jxcore-log: Starting JXcore engine
,07-12 11:36:02.511  3031  3099 W jxcore-log: Platform android
07-12 11:36:02.511  3031  3099 W jxcore-log: 
,07-12 11:36:02.511  3031  3099 W jxcore-log: Process ARCH arm
07-12 11:36:02.511  3031  3099 W jxcore-log: 
,07-12 11:36:02.533   787   803 I ActivityManager: Start proc 3105:com.google.android.gms.feedback/u0a7 for service com.google.android.gms/.feedback.FeedbackService
,07-12 11:36:02.639  3105  3105 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:36:02.639  3105  3105 I MultiDex: install
07-12 11:36:02.639  3105  3105 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:02.659  3105  3105 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:36:02.669  3105  3105 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-12 11:36:02.669  3105  3105 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:36:02.674  3105  3105 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:36:02.707  3105  3105 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:02.719  3105  3105 D ChimeraCfgMgr: Reading stored module config
,07-12 11:36:02.721  3031  3099 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:02.721  3031  3099 I jxcore-log: 
07-12 11:36:02.721  3031  3099 W jxcore-log: JXcore engine is started
,07-12 11:36:02.725  3031  3098 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:36:02.728  3031  3031 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:02.749   787  1324 I ActivityManager: Killing 2305:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,07-12 11:36:02.803  3105  3126 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-12 11:36:10.698  1263  1553 I Finsky  : [66] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-12 11:36:10.847  1263  1553 I Finsky  : [66] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-12 11:36:10.847  1263  1263 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-12 11:36:12.711  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:36:12.711  3031  3099 I jxcore-log: 
,07-12 11:36:12.713  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:36:12.713  3031  3099 I jxcore-log: 
,07-12 11:36:12.714  3031  3099 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:12.714  3031  3099 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:12.714  3031  3099 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:12.714  3031  3099 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:12.716  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:36:12.716  3031  3099 I jxcore-log: 
07-12 11:36:12.717  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:36:12.717  3031  3099 I jxcore-log: 
,07-12 11:36:13.055  3031  3099 I jxcore-log: Unit Test app is loaded
07-12 11:36:13.055  3031  3099 I jxcore-log: 
,07-12 11:36:13.059  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:36:13.059  3031  3099 I jxcore-log: 
,07-12 11:36:13.064   787  1357 D WifiService: setWifiEnabled: true pid=3031, uid=10026
,07-12 11:36:13.064   787  1357 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 11:36:13.068   193   786 D SoftapController: Softap fwReload - Ok
07-12 11:36:13.070   193   786 D CommandListener: Setting iface cfg
07-12 11:36:13.070   193   786 D CommandListener: Trying to bring down wlan0
07-12 11:36:13.071  3031  3031 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-12 11:36:13.073  3031  3099 I jxcore-log: My device name is: LGE-Nexus 5
07-12 11:36:13.073  3031  3099 I jxcore-log: 
07-12 11:36:13.075  3031  3099 I jxcore-log: WARN testUtils: myNameCallback not set!
07-12 11:36:13.075  3031  3099 I jxcore-log: 
07-12 11:36:13.078   193   786 D CommandListener: Clearing all IP addresses on wlan0
07-12 11:36:13.080   787   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 11:36:13.080   787   807 I ActivityManager: Start proc 3162:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 11:36:13.200  3162  3162 D AdapterServiceConfig: Adding HeadsetService
,07-12 11:36:13.201  3162  3162 D AdapterServiceConfig: Adding A2dpService
07-12 11:36:13.201  3162  3162 D AdapterServiceConfig: Adding HidService
07-12 11:36:13.201  3162  3162 D AdapterServiceConfig: Adding HealthService
07-12 11:36:13.201  3162  3162 D AdapterServiceConfig: Adding PanService
07-12 11:36:13.201  3162  3162 D AdapterServiceConfig: Adding GattService
07-12 11:36:13.201  3162  3162 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 11:36:13.216   787   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0ec780:true
,07-12 11:36:13.217  3162  3162 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 11:36:13.220  3162  3162 I bt_bluedroid: init
,07-12 11:36:13.220  3162  3179 I BluetoothAdapterState: Entering OffState
,07-12 11:36:13.230  3162  3180 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 11:36:13.231  3162  3180 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-12 11:36:13.231  3162  3180 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:36:13.231  3162  3180 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 11:36:13.232  3162  3162 I bt_bluedroid: get_profile_interface socket
,07-12 11:36:13.236  3162  3162 I bt_bluedroid: get_profile_interface sdp
,07-12 11:36:13.238  3162  3183 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-12 11:36:13.240  3162  3183 D BluetoothAdapterProperties: Name is: Nexus 5
,07-12 11:36:13.240  3162  3174 I bt_bluedroid: config_hci_snoop_log
,07-12 11:36:13.241   787   807 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,07-12 11:36:13.244  3162  3179 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 11:36:13.247  3162  3179 D BluetoothAdapterProperties: Setting state to 14
,07-12 11:36:13.247  3162  3179 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 11:36:13.249  3162  3179 D BluetoothBondStateMachine: make
,07-12 11:36:13.250  3162  3184 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 11:36:13.259  3162  3179 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:36:13.259  3162  3162 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-12 11:36:13.261  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
07-12 11:36:13.261  3162  3162 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 11:36:13.262  3162  3162 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:36:13.262  3162  3162 D BtGatt.GattService: start()
07-12 11:36:13.262  3162  3162 I bt_bluedroid: get_profile_interface gatt
07-12 11:36:13.262  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
07-12 11:36:13.262  3162  3162 D BtGatt.AdvertiseManager: advertise manager created
,07-12 11:36:13.269  3162  3162 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:13.269  3162  3162 V BluetoothAdapterState: isTurningOn()=false
07-12 11:36:13.269  3162  3162 V BluetoothAdapterState: isBleTurningOn()=true
,07-12 11:36:13.270  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:36:13.272  3162  3179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-12 11:36:13.272  3162  3179 I bt_bluedroid: enable
07-12 11:36:13.272  3162  3180 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 11:36:13.274  3162  3180 I bt_hci  : start_up
,07-12 11:36:13.282  3162  3180 I bt_vendor: alloc value 0xb39e5631
,07-12 11:36:13.282  3162  3180 I bt_vendor: init
07-12 11:36:13.282  3162  3180 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 11:36:13.282  3162  3180 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 11:36:13.318  3162  3180 D bt_hci  : start_up starting async portion
,07-12 11:36:13.320  3162  3188 I bt_hci  : event_finish_startup
07-12 11:36:13.320  3162  3188 I bt_hci_h4: hal_open
07-12 11:36:13.320  3162  3188 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-12 11:36:13.323  3162  3188 I bt_userial_vendor: device fd = 49 open
,07-12 11:36:13.404  3162  3188 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 11:36:13.431  3162  3188 D bt_hwcfg: Chipset BCM4335C0
,07-12 11:36:13.431  3162  3188 D bt_hwcfg: Target name = [BCM4335C0]
07-12 11:36:13.431  3162  3188 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-12 11:36:13.766  3162  3188 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 11:36:13.766  3162  3188 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:36:13.766  3162  3188 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 11:36:13.862   787   807 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 11:36:13.864   787   891 D wifi    : set interface wlan0 flags (UP)
,07-12 11:36:13.864   787   891 I WifiHAL : Initializing wifi
,07-12 11:36:13.864   787   891 I WifiHAL : Creating socket
07-12 11:36:13.866   787   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-12 11:36:13.866   787   891 D wifi    : Did set static halHandle = 0x930a9370
,07-12 11:36:13.866   787   891 D wifi    : halHandle = 0x930a9370, mVM = 0xb4d3c000, mCls = 0x2017f2
07-12 11:36:13.866   787   891 D wifi    : array field set
07-12 11:36:13.869   787   891 I WifiNative-HAL: interface[0] = p2p0
07-12 11:36:13.869   787   891 I WifiNative-HAL: interface[1] = wlan0
07-12 11:36:13.879  3031  3031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:13.883  3162  3188 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-12 11:36:13.883  3162  3188 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
,07-12 11:36:13.885   787   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 11:36:13.894   787  3194 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1828023440
07-12 11:36:13.894   787  3194 D wifi    : waitForHalEvents called, vm = 0xb4d3c000, obj = 0x2017f2, env = 0x930bdf00
07-12 11:36:13.899   787   803 I ActivityManager: Start proc 3196:com.android.settings/1000 for broadcast com.android.settings/.widget.SettingsAppWidgetProvider
07-12 11:36:13.911  3162  3188 I bt_hwcfg: vendor lib fwcfg completed
07-12 11:36:13.911  3162  3188 I bt_vendor: firmware callback
07-12 11:36:13.911  3162  3188 I bt_hci  : firmware_config_callback
,07-12 11:36:13.918  3162  3207 I bt_btu  : btu_task pending for preload complete event
07-12 11:36:13.918  3162  3207 I bt_btu_task: Bluetooth chip preload is complete
07-12 11:36:13.918  3162  3207 I bt_btu  : btu_task received preload complete event
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_HCI
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_SMP
,07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:36:13.924  3162  3207 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 11:36:13.978  3196  3196 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-12 11:36:13.980  3195  3195 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 11:36:13.997   787   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bcecbf3:true
,07-12 11:36:14.003  3195  3195 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:14.007  3196  3196 D LocalBluetoothProfileManager: Adding local MAP profile
,07-12 11:36:14.008  3196  3196 D BluetoothMap: Create BluetoothMap proxy object
,07-12 11:36:14.012  3196  3196 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-12 11:36:14.029   787  1324 I ActivityManager: Start proc 3221:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
07-12 11:36:14.029   787  1324 I ActivityManager: Killing 2487:com.google.android.music:main/u0a58 (adj 15): empty #17
,07-12 11:36:14.080  3195  3195 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:14.142  3162  3207 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39639b5
,07-12 11:36:14.142  3162  3207 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39639b5 
,07-12 11:36:14.183  3162  3183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 11:36:14.183  3162  3183 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
07-12 11:36:14.184  3162  3183 D BluetoothAdapterProperties: Name is: Nexus 5
07-12 11:36:14.186  3031  3031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:14.187  3162  3183 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:36:14.187  3162  3183 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 11:36:14.188  3162  3183 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-12 11:36:14.188  3162  3183 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-12 11:36:14.188  3162  3183 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
07-12 11:36:14.189  3162  3183 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
,07-12 11:36:14.189  3162  3183 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-12 11:36:14.189  3162  3183 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
07-12 11:36:14.189  3162  3183 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
,07-12 11:36:14.191  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,07-12 11:36:14.194  3162  3162 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 11:36:14.196  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,07-12 11:36:14.199  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,07-12 11:36:14.200  3162  3162 D HidService: getHidService(): service is NULL
,07-12 11:36:14.201  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,07-12 11:36:14.204  3162  3162 D HidService: getHidService(): service is NULL
,07-12 11:36:14.204  3162  3162 D HidService: getHidService(): service is NULL
,07-12 11:36:14.204  3162  3162 D HidService: getHidService(): service is NULL
07-12 11:36:14.204  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
07-12 11:36:14.205  3162  3162 D HidService: getHidService(): service is NULL
,07-12 11:36:14.207  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,07-12 11:36:14.208  3162  3162 D HidService: getHidService(): service is NULL
,07-12 11:36:14.209  3162  3183 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,07-12 11:36:14.210  3162  3162 D HidService: getHidService(): service is NULL
,07-12 11:36:14.211  3162  3183 D bt_hci  : do_postload posting postload work item
,07-12 11:36:14.211  3162  3188 I bt_hci  : event_postload
07-12 11:36:14.211  3162  3188 I bt_vendor: sco_config_cb
,07-12 11:36:14.211  3162  3188 I bt_hci  : sco_config_callback postload finished.
,07-12 11:36:14.213  3162  3188 I bt_vendor: low_power_mode_cb
,07-12 11:36:14.214  3162  3183 D bt_bte_conf: Device ID record 1 : primary
07-12 11:36:14.214  3162  3183 D bt_bte_conf:   vendorId            = 000f
,07-12 11:36:14.214  3162  3183 D bt_bte_conf:   vendorIdSource      = 0001
07-12 11:36:14.214  3162  3183 D bt_bte_conf:   product             = 1200
07-12 11:36:14.214  3162  3183 D bt_bte_conf:   version             = 1436
07-12 11:36:14.214  3162  3183 D bt_bte_conf:   clientExecutableURL = 
07-12 11:36:14.214  3162  3183 D bt_bte_conf:   serviceDescription  = 
07-12 11:36:14.214  3162  3183 D bt_bte_conf:   documentationURL    = 
07-12 11:36:14.214  3162  3183 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 11:36:14.214  3162  3180 D bt_stack_manager: event_start_up_stack finished
07-12 11:36:14.217  3162  3179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 11:36:14.218  3162  3179 D BluetoothAdapterProperties: Setting state to 15
07-12 11:36:14.218  3162  3179 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-12 11:36:14.218  3162  3179 I BluetoothAdapterState: Entering BleOnState
,07-12 11:36:14.221  3162  3179 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 11:36:14.221  3162  3179 D BluetoothAdapterProperties: Setting state to 11
07-12 11:36:14.221  3162  3179 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 11:36:14.223  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
07-12 11:36:14.224  3162  3162 D HeadsetService: Received start request. Starting profile...
07-12 11:36:14.224  3162  3162 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 11:36:14.227  3162  3162 D HeadsetStateMachine: make
,07-12 11:36:14.231   787   891 D WifiConfigStore: Loading config and enabling all networks 
07-12 11:36:14.233  3162  3179 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:36:14.233  3031  3031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:14.233  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:14.235  3031  3031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:14.235  3031  3031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:14.237   787   891 D WifiConfigStore: loaded 0 passpoint configs
07-12 11:36:14.239   787   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 11:36:14.240  3162  3162 D HeadsetStateMachine: max_hf_connections = 1
07-12 11:36:14.240  3162  3162 I bt_bluedroid: get_profile_interface handsfree
07-12 11:36:14.240  3162  3183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 11:36:14.240   787   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 11:36:14.240   787   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-12 11:36:14.240   787   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-12 11:36:14.243  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
07-12 11:36:14.243   787   891 D WifiNative-HAL: Setting external_sim to 1
07-12 11:36:14.243   787   787 D BluetoothA2dp: Proxy object connected
07-12 11:36:14.243  3162  3183 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-12 11:36:14.243   787   891 D wifi    : setting dfs flag to true, 0x998aa860
07-12 11:36:14.244   787   891 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:14.244   787   891 D wifi    : setting scan oui 0x998aa860
07-12 11:36:14.244   787   891 D WifiHAL : Sending mac address OUI
07-12 11:36:14.244  3162  3162 D A2dpService: Received start request. Starting profile...
07-12 11:36:14.244  3162  3162 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:36:14.245  3162  3162 I bt_bluedroid: get_profile_interface avrcp
,07-12 11:36:14.253  3162  3162 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 11:36:14.253  3162  3162 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:36:14.253  3162  3162 D A2dpStateMachine: make
07-12 11:36:14.255  3162  3162 I bt_bluedroid: get_profile_interface a2dp
07-12 11:36:14.255  3162  3183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-12 11:36:14.259  3162  3246 D A2dpStateMachine: Enter Disconnected: -2
,07-12 11:36:14.260  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
,07-12 11:36:14.261   933   933 D BluetoothInputDevice: Proxy object connected
07-12 11:36:14.261   933   933 D HidProfile: Bluetooth service connected
07-12 11:36:14.261  3196  3196 D BluetoothInputDevice: Proxy object connected
07-12 11:36:14.262  3162  3162 D HidService: Received start request. Starting profile...
07-12 11:36:14.262  3162  3162 I bt_bluedroid: get_profile_interface hidhost
07-12 11:36:14.262  3162  3162 D HidService: setHidService(): set to: null
,07-12 11:36:14.262  3162  3162 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 11:36:14.262  3162  3183 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3945099
07-12 11:36:14.262  3162  3183 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 11:36:14.263  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
,07-12 11:36:14.263  3162  3162 D HealthService: Received start request. Starting profile...
07-12 11:36:14.263  3196  3196 D HidProfile: Bluetooth service connected
07-12 11:36:14.264   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:36:14.264  3162  3162 I bt_bluedroid: get_profile_interface health
,07-12 11:36:14.265  3162  3162 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 11:36:14.265   787   787 D RttService: SCAN_AVAILABLE : 3
,07-12 11:36:14.265   787   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-12 11:36:14.265   787   909 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:14.266   193   786 D CommandListener: Setting iface cfg
07-12 11:36:14.266   193   786 D CommandListener: Trying to bring up p2p0
07-12 11:36:14.267   787   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 11:36:14.273  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
,07-12 11:36:14.274  3196  3196 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 11:36:14.274   933   933 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 11:36:14.274  3162  3162 D PanService: Received start request. Starting profile...
07-12 11:36:14.274   933   933 D PanProfile: Bluetooth service connected
07-12 11:36:14.274  3162  3162 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-12 11:36:14.274  3162  3162 I bt_bluedroid: get_profile_interface pan
07-12 11:36:14.274  3162  3183 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:36:14.274   787   891 E native  : do suspend false
,07-12 11:36:14.280  3162  3162 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e22137
,07-12 11:36:14.280   787   890 D WifiNative-HAL: p2pGetDeviceAddress
07-12 11:36:14.280   787   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
07-12 11:36:14.281   933   933 D BluetoothMap: Proxy object connected
07-12 11:36:14.281  3162  3162 D BluetoothMapService: Received start request. Starting profile...
07-12 11:36:14.281  3162  3162 D BluetoothMapService: start()
07-12 11:36:14.282   933   933 D MapProfile: Bluetooth service connected
07-12 11:36:14.282   933   933 D BluetoothMap: getConnectedDevices()
07-12 11:36:14.282   933   933 D BluetoothMap: Bluetooth is Not enabled
,07-12 11:36:14.283  3162  3162 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-12 11:36:14.283   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-12 11:36:14.283  3162  3162 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-12 11:36:14.284  3162  3162 D BluetoothMapAppObserver: createReceiver()
07-12 11:36:14.284  3162  3162 D BluetoothMapAppObserver: initObservers()
07-12 11:36:14.284  3162  3162 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 11:36:14.287   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:36:14.288  3196  3196 D PanProfile: Bluetooth service connected
,07-12 11:36:14.289  3196  3196 D BluetoothMap: Proxy object connected
,07-12 11:36:14.289  3196  3196 D MapProfile: Bluetooth service connected
07-12 11:36:14.289  3196  3196 D BluetoothMap: getConnectedDevices()
07-12 11:36:14.290  3196  3196 D BluetoothMap: Bluetooth is Not enabled
,07-12 11:36:14.293  3162  3241 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,07-12 11:36:14.297  3162  3162 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:14.297  3162  3162 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:14.297  3162  3162 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:14.297  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:14.298  3162  3162 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:14.298  3162  3162 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:14.298  3162  3162 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:14.298  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 11:36:14.299  3162  3162 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:14.300  3162  3179 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 11:36:14.300  3162  3179 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:36:14.300  3162  3179 D BluetoothAdapterProperties: State =  11
07-12 11:36:14.302  3162  3183 D BluetoothAdapterProperties: Scan Mode:21
,07-12 11:36:14.302  3162  3183 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 11:36:14.302  3162  3179 D BluetoothAdapterProperties: Setting state to 12
07-12 11:36:14.302  3162  3179 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 11:36:14.302  3196  3206 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 11:36:14.302  3162  3179 I BluetoothAdapterState: Entering OnState
,07-12 11:36:14.303   933   945 D BluetoothPbap: onBluetoothStateChange: up=true
,07-12 11:36:14.304   787   807 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:14.304   933  1412 D BluetoothMap: onBluetoothStateChange: up=true
07-12 11:36:14.304  3031  3031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-12 11:36:14.305  3196  3213 D BluetoothPan: onBluetoothStateChange on: true
07-12 11:36:14.305  3196  3206 D BluetoothPbap: onBluetoothStateChange: up=true
,07-12 11:36:14.306   787   807 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 11:36:14.308  3196  3213 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-12 11:36:14.308  1308  1454 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 11:36:14.309   787   807 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:14.309   933   944 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 11:36:14.309   787   807 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:14.309  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:14.310   933  1546 D BluetoothPan: onBluetoothStateChange on: true
07-12 11:36:14.311   787   787 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 11:36:14.311  3162  3162 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 11:36:14.311  3162  3162 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 11:36:14.313  3031  3031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:14.316   933  1127 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 11:36:14.318  3196  3196 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 11:36:14.318  3162  3162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:14.321  3162  3162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:14.322  3162  3162 D ObexServerSockets: Succeed to create listening sockets 
07-12 11:36:14.322  3162  3162 D ObexServerSockets0: startAccept()
07-12 11:36:14.322  3162  3162 D ObexServerSockets0: prepareForNewConnect()
07-12 11:36:14.322  3196  3196 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:36:14.323  3162  3162 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-12 11:36:14.323  3162  3162 D BluetoothSdpJni: SDP Create record success - handle: 0
07-12 11:36:14.324  3162  3162 D BluetoothMapService: onReceive
07-12 11:36:14.324  3162  3162 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:14.324  3162  3162 D BluetoothMapService: STATE_ON
07-12 11:36:14.325  3162  3253 D ObexServerSockets0: Accepting socket connection...
07-12 11:36:14.325  3162  3254 D ObexServerSockets0: Accepting socket connection...
,07-12 11:36:14.329   933   933 D BluetoothA2dp: Proxy object connected
,07-12 11:36:14.331   933  1127 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 11:36:14.336  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.337  3196  3196 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
,07-12 11:36:14.338  3196  3196 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.344  3162  3162 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 11:36:14.344  3162  3162 D ObexServerSockets0: prepareForNewConnect()
,07-12 11:36:14.351   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.353   933  1127 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
07-12 11:36:14.354   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.364  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.365  3196  3196 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-12 11:36:14.366  3196  3196 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.372  3221  3221 W InstanceID/Rpc: Found 10007
,07-12 11:36:14.386  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.389  3196  3196 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-12 11:36:14.391  3196  3196 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.399   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.401   933  1127 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-12 11:36:14.403   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.403  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.404  3196  3196 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-12 11:36:14.405  3196  3196 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.407   787   807 D BluetoothHeadset: Proxy object connected
,07-12 11:36:14.409  1308  1454 D BluetoothHeadset: Proxy object connected
,07-12 11:36:14.410   787   807 D BluetoothHeadset: Proxy object connected
07-12 11:36:14.410   787   807 D BluetoothHeadset: Proxy object connected
,07-12 11:36:14.421  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.422  3196  3196 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-12 11:36:14.424  3196  3196 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.429  3196  3213 D BluetoothHeadset: Proxy object connected
,07-12 11:36:14.434  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.436   933  1546 D BluetoothHeadset: Proxy object connected
,07-12 11:36:14.441  3196  3196 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-12 11:36:14.441   933   933 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:14.444  3196  3196 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.449   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.450  3196  3196 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.452  3196  3196 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-12 11:36:14.454  3196  3196 D MapProfile: getConnectionStatus: status is: 0
07-12 11:36:14.454  3196  3196 D BluetoothA2dp: Proxy object connected
,07-12 11:36:14.456   933  1127 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-12 11:36:14.457  3196  3196 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:14.457   787  1357 I ActivityManager: Killing 2589:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-12 11:36:14.533   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.551  1558  1558 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 11:36:14.559  1558  1558 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-12 11:36:14.566   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.569  1558  1558 I BeaconBle: BLE 'JB+' software access layer enabled
,07-12 11:36:14.569   933  1127 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-12 11:36:14.572   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.581  1558  1558 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 11:36:14.589   787   892 D WifiService: New client listening to asynchronous messages
,07-12 11:36:14.602   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.614  1558  3274 D BluetoothAdapter: startLeScan(): null
,07-12 11:36:14.616   933  1127 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-12 11:36:14.618   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.618  1558  3274 D BluetoothAdapter: STATE_ON
,07-12 11:36:14.619  3196  3196 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 11:36:14.626  3162  3174 D BtGatt.GattService: registerClient() - UUID=9c5cf7ee-38b4-4823-a5b4-d34987747cc4
,07-12 11:36:14.627  3162  3183 D BtGatt.GattService: onClientRegistered() - UUID=9c5cf7ee-38b4-4823-a5b4-d34987747cc4, clientIf=5
07-12 11:36:14.627  1558  1626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-12 11:36:14.629  3162  3261 D BtGatt.GattService: start scan with filters
,07-12 11:36:14.632  3162  3187 D BtGatt.ScanManager: handling starting scan
,07-12 11:36:14.634  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-12 11:36:14.635  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 11:36:14.635  3162  3187 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 11:36:14.635  3162  3183 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 11:36:14.643   933   933 D BluetoothPbap: Proxy object connected
,07-12 11:36:14.643   933   933 D PbapServerProfile: Bluetooth service connected
,07-12 11:36:14.643  3196  3196 D DockEventReceiver: finishStartingService: stopping service
,07-12 11:36:14.644  3162  3276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:14.649  3196  3196 D BluetoothPbap: Proxy object connected
07-12 11:36:14.650  3196  3196 D PbapServerProfile: Bluetooth service connected
,07-12 11:36:14.657   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.659   933  1127 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-12 11:36:14.663  1558  1558 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 11:36:14.665   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.667  1558  3280 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 11:36:14.669  1558  1558 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 11:36:14.683  3162  3284 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:14.688  3162  3284 I BtOppRfcommListener: Accept thread started.
,07-12 11:36:14.689  1558  3280 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 11:36:14.711   933  1127 D BluetoothMap: getConnectedDevices()
,07-12 11:36:14.712   933  1127 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-12 11:36:14.713   933  1127 D MapProfile: getConnectionStatus: status is: 0
,07-12 11:36:14.805  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:36:14.904  1558  3244 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:36:14.906  1558  3244 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: java.io.IOException: Not connected
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at rbw.run(:com.google.android.gms:1101)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:14.906  1558  3244 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:36:14.946  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:36:15.098  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:36:15.105  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:36:15.109  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:36:15.486  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:36:15.953  1558  3244 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:36:15.954  1558  3244 E NearbyDiscovery: ServerTask:  Server task exception with status: 7
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: java.io.IOException: Not connected
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at rdn.a(:com.google.android.gms:1158)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at rdi.b(:com.google.android.gms:83)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at rdi.a(:com.google.android.gms:104)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at ree.a(:com.google.android.gms:232)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at reh.run(:com.google.android.gms:75)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:15.954  1558  3244 E NearbyDiscovery: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:36:15.989  3195  3195 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-12 11:36:16.010   787   891 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-12 11:36:16.021   787   891 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-12 11:36:16.022   787   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:16.031   787   891 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-12 11:36:16.083   787   891 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-12 11:36:16.085  3195  3195 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-12 11:36:16.141  1558  3274 D BluetoothAdapter: stopLeScan()
,07-12 11:36:16.142  1558  3274 D BluetoothAdapter: STATE_ON
,07-12 11:36:16.143  3162  3243 D BtGatt.GattService: stopScan() - queue size =1
,07-12 11:36:16.144  3162  3187 D BtGatt.ScanManager: stop scan
07-12 11:36:16.144  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 11:36:16.144  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 11:36:16.144  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 11:36:16.144  3162  3261 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 11:36:16.219  3195  3195 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 11:36:16.253  3195  3195 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 11:36:16.254  3195  3195 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-12 11:36:16.261   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:36:16.274   787   891 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:36:16.274   787   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:16.275   787   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-12 11:36:16.290   787   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:16.300   193   786 D CommandListener: Setting iface cfg
,07-12 11:36:16.308   787   891 D WifiStateMachine: Start Dhcp Watchdog 1
07-12 11:36:16.318  1558  3274 D BluetoothAdapter: startLeScan(): null
,07-12 11:36:16.324  1558  3274 D BluetoothAdapter: STATE_ON
,07-12 11:36:16.327   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:16.327   787   893 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
07-12 11:36:16.327  3162  3261 D BtGatt.GattService: registerClient() - UUID=c397124d-8d2a-46f9-a8cf-04a65b0f48f7
07-12 11:36:16.328  3162  3183 D BtGatt.GattService: onClientRegistered() - UUID=c397124d-8d2a-46f9-a8cf-04a65b0f48f7, clientIf=5
07-12 11:36:16.328  1558  1652 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-12 11:36:16.328  3162  3174 D BtGatt.GattService: start scan with filters
07-12 11:36:16.328   787   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
07-12 11:36:16.331  3162  3187 D BtGatt.ScanManager: handling starting scan
07-12 11:36:16.333  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-12 11:36:16.333  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
,07-12 11:36:16.333  3162  3187 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 11:36:16.333  3162  3183 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 11:36:16.681   787  3322 D DhcpClient: Receive thread started
,07-12 11:36:16.763   787   891 E native  : do suspend false
,07-12 11:36:16.773   787  3304 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 11:36:16.782   787  3322 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170787, domain null
,07-12 11:36:16.782   787  3304 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170787 seconds
07-12 11:36:16.783   787  3304 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-12 11:36:16.791   787  3322 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 11:36:16.791   787  3304 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-12 11:36:16.793   193   786 D CommandListener: Setting iface cfg
,07-12 11:36:16.796   787   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
07-12 11:36:16.799   787  3304 D DhcpClient: Scheduling renewal in 86399s
07-12 11:36:16.804   787   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-12 11:36:16.805   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-12 11:36:16.806   787   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-12 11:36:16.807   787   893 D ConnectivityService: Adding iface wlan0 to network 100
07-12 11:36:16.823   787   891 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:36:16.878   787   893 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 11:36:16.878   787   893 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-12 11:36:16.880   787   893 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-12 11:36:16.881   787   893 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-12 11:36:16.882   787   893 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-12 11:36:16.889   787   893 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:16.893   787   893 D ConnectivityService: scheduleUnvalidatedPrompt 100
,07-12 11:36:16.893   787   893 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:16.893   787   893 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:16.893   787   893 D ConnectivityService:    accepting network in place of null
07-12 11:36:16.894   787   891 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 11:36:16.894   787   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 11:36:16.895   787   893 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:36:16.909   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=106616, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:36:16.929   193   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:36:16.950   193   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:36:16.951   787   893 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,07-12 11:36:16.954   787   893 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-12 11:36:16.954   787   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:16.955   787   893 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:16.956   787   807 D Tethering: MasterInitialState.processMessage what=3
07-12 11:36:16.961  3031  3031 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 11:36:16.973   787   787 I ActivityManager: Start proc 3343:com.google.android.apps.photos/u0a83 for service com.google.android.apps.photos/.onboarding.autosignin.AutoSignInAndSyncJobService
,07-12 11:36:16.982  1399  1399 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:36:17.001  3031  3031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 11:36:17.002   787  1332 I ActivityManager: Start proc 3360:com.google.android.setupwizard/u0a16 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,07-12 11:36:17.006  3031  3031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 11:36:17.009  2482  2482 W ChromiumNet: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21629]" dev="sockfs" ino=21629 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
,07-12 11:36:17.048  3360  3360 W System  : ClassLoader referenced unknown path: /system/priv-app/SetupWizard/lib/arm
,07-12 11:36:17.105   787   802 I ActivityManager: Start proc 3384:com.google.android.apps.plus/u0a63 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,07-12 11:36:17.110   787  1275 D AlarmManagerService: Setting time of day to sec=1468316176
,07-12 11:36:16.545   787  1275 W AlarmManagerService: Unable to set rtc to 1468316176: Invalid argument
,07-12 11:36:16.620  3360  3360 E SetupWizard: tickleCheckinService called after completing user setup
,07-12 11:36:16.622   787  3302 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:811::200e
,07-12 11:36:16.629  1572  3400 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:36:16.631  3360  3360 I SetupWizard.LoggingHelper: Connected to Google Play Services.
,07-12 11:36:16.639   787  3401 D GpsLocationProvider: NTP server returned: 1468316176546 (Tue Jul 12 11:36:16 GMT+02:00 2016) reference: 106819 certainty: 8 system time offset: -93
,07-12 11:36:16.641   787   802 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26284, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:36:16.642   787   802 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 139644, reason: UserStart
,07-12 11:36:16.685   787  3302 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:36:16 GMT], X-Android-Received-Millis=[1468316176684], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468316176655]}
,07-12 11:36:16.686   787   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 11:36:16.686   787   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-12 11:36:16.686   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:16.687   787   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 11:36:16.707   787  1332 I ActivityManager: Start proc 3406:com.google.android.apps.maps/u0a57 for service com.google.android.apps.maps/com.google.android.apps.gmm.offline.OfflineGcmTaskService
,07-12 11:36:16.738  1572  3379 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-12 11:36:16.815  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:36:16.815  3031  3099 I jxcore-log: 
,07-12 11:36:16.816  3360  3381 I SetupWizard.FrpHelper: FRP status: supported: false, challengeRequired: false
,07-12 11:36:17.051  3105  3116 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-12 11:36:17.052  3105  3116 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-12 11:36:17.057  3105  3116 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000006/n/armeabi
07-12 11:36:17.058  3105  3116 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-12 11:36:17.059  3105  3116 D ChimeraFileApk: Classloading successful. Optimized code found.
07-12 11:36:17.061  3105  3116 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-12 11:36:17.076  1558  3274 D BluetoothAdapter: stopLeScan()
,07-12 11:36:17.077  1558  3274 D BluetoothAdapter: STATE_ON
,07-12 11:36:17.077  3162  3261 D BtGatt.GattService: stopScan() - queue size =1
07-12 11:36:17.078  3162  3174 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 11:36:17.078  3162  3187 D BtGatt.ScanManager: stop scan
07-12 11:36:17.078  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-12 11:36:17.078  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 11:36:17.078  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 11:36:17.078  1558  3274 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 11:36:17.083  3406  3406 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:36:17.096  3406  3406 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-12 11:36:17.096  3406  3406 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:36:17.100  3406  3406 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:36:17.124  3105  3116 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-12 11:36:17.131  3406  3406 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:17.301  3406  3423 D ChimeraCfgMgr: Reading stored module config
,07-12 11:36:17.317  1572  1572 V Herrevad: NQAS connected
,07-12 11:36:17.318  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:36:17.318  3031  3099 I jxcore-log: 
,07-12 11:36:17.347  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:36:17.347  3031  3099 I jxcore-log: 
,07-12 11:36:17.349  3406  3423 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000006/n/armeabi
07-12 11:36:17.350  2793  3464 W SyncManagerImpl: Initiating sync for AccountId 3a3529a (com.google.android.apps.docs)
,07-12 11:36:17.352  3406  3423 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-12 11:36:17.352  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:36:17.352  3031  3099 I jxcore-log: 
,07-12 11:36:17.356   787   983 D WifiService: acquireWifiLockLocked: WifiLock{SyncManagerImpl type=1 binder=android.os.BinderProxy@ba14775}
,07-12 11:36:17.357  3406  3423 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-12 11:36:17.371  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:36:17.371  3031  3099 I jxcore-log: 
,07-12 11:36:17.375  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:36:17.375  3031  3099 I jxcore-log: 
,07-12 11:36:17.423  2793  3464 W SyncManagerImpl: Started sync for AccountId 3a3529a
,07-12 11:36:17.438  2793  3464 W Flag    : Duration spec must be at least 2 characters long: 
,07-12 11:36:17.439  3406  3423 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-12 11:36:17.471  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:17.478  1572  3468 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,07-12 11:36:17.509  1558  1567 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@fa2a459)
,07-12 11:36:17.618  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:36:17.620  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:36:17.690  1572  3488 I iu.SyncManager: SYNC; picasa accounts
,07-12 11:36:17.704  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:17.706  1572  1572 D NetworkLogImpl: Loaded NetworkSpeedPredictor
07-12 11:36:17.707  1572  1572 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:36:17.718  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:17.721  1572  3488 I iu.UploadsManager: num queued entries: 0
,07-12 11:36:17.722  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:17.739  1572  3488 I iu.UploadsManager: num updated entries: 0
07-12 11:36:17.741  1572  3488 I iu.SyncManager: NEXT; no task
,07-12 11:36:17.744   787   800 I ActivityManager: Start proc 3489:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 11:36:17.763  2793  3464 W jna     : Application name is not set. Call Builder#setApplicationName.
,07-12 11:36:17.764  2793  3464 W jna     : Application name is not set. Call Builder#setApplicationName.
,07-12 11:36:17.786  2793  3464 W jna     : Application name is not set. Call Builder#setApplicationName.
,07-12 11:36:17.792  3489  3489 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-12 11:36:17.829  1558  3484 I GCM     : GCM config loaded
,07-12 11:36:17.933  3489  3489 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 11:36:17.933  3489  3489 I MultiDex: install
07-12 11:36:17.933  3489  3489 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:17.982   787  1357 D ConnectivityService: listenForNetwork for Listen from uid/pid:10063/3384 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-12 11:36:18.002  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.140  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.152  3489  3489 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-12 11:36:18.152  3489  3489 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:18.152  3489  3489 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:18.167  3489  3489 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:18.182  3489  3525 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:18.344  3489  3489 I NSApplication: Starting up...
,07-12 11:36:18.377   787  1245 I ActivityManager: Start proc 3549:com.qualcomm.timeservice/u0a68 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,07-12 11:36:18.403  3549  3549 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-12 11:36:18.412  3549  3549 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316178412
,07-12 11:36:18.412  3549  3549 D         : TimeServiceNative: User Time to be set is 1468316178412
07-12 11:36:18.412  3549  3549 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:36:18.412  3549  3549 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-12 11:36:18.412  3549  3549 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316178412
07-12 11:36:18.413   211   577 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-12 11:36:18.413  3549  3549 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,07-12 11:36:18.413   211  3562 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316178412
07-12 11:36:18.413   211  3562 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316178412, operation = 0
07-12 11:36:18.413   211  3562 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/2/71 3:39:55
07-12 11:36:18.413   211  3562 D QC-time-services: Daemon:Value read from RTC seconds = 52630795000
07-12 11:36:18.413   211  3562 D QC-time-services: Daemon:new time 1468316178412 
07-12 11:36:18.413   211  3562 D QC-time-services: Daemon: delta 1415685383412 genoff 1415685383412 
07-12 11:36:18.414   211  3562 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685383412 to memory
07-12 11:36:18.414   211  3562 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
07-12 11:36:18.414   211  3562 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:36:18.419   211  3562 D QC-time-services: Updating the TOD offset
07-12 11:36:18.419   211  3562 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685383412 to memory
07-12 11:36:18.419   211  3562 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
07-12 11:36:18.419   211  3562 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:36:18.423   211  3562 D QC-time-services: Daemon:Update to modem bit set
07-12 11:36:18.423   211  3562 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-12 11:36:18.423   211  3562 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1152351378412
,07-12 11:36:18.424  3549  3549 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-12 11:36:18.426   211   577 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-12 11:36:18.427   211   575 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-12 11:36:18.449  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:36:18.449  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:36:18.568  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.568  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.610   787  1356 I ActivityManager: Start proc 3563:com.google.android.calendar/u0a28 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-12 11:36:18.643  3563  3563 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.calendar-1/lib/arm
,07-12 11:36:18.670  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.671  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.736  3384  3483 I art     : Note: end time exceeds epoch: 
07-12 11:36:18.736  3384  3483 I art     : Note: end time exceeds epoch: 
,07-12 11:36:18.768   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:18.798   787   800 I ActivityManager: Start proc 3593:com.google.android.deskclock/u0a33 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-12 11:36:18.799   787   800 I ActivityManager: Killing 2756:com.google.android.partnersetup/u0a11 (adj 15): empty #17
07-12 11:36:18.800  3563  3563 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-12 11:36:18.950   787  1319 I ActivityManager: Killing 2777:com.android.musicfx/u0a13 (adj 15): empty #17
,07-12 11:36:18.955  2793  3464 W SyncManagerImpl: Sync for AccountId 3a3529a took 1294 ms
,07-12 11:36:18.962  3593  3593 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.deskclock-2/lib/arm
,07-12 11:36:19.096   787  1319 D WifiService: releaseWifiLockLocked: WifiLock{SyncManagerImpl type=1 binder=android.os.BinderProxy@ba14775}
,07-12 11:36:19.099  3593  3593 I GAv4    : Google Analytics 8.4.87 is starting up. To enable debug logging on a device run:
07-12 11:36:19.099  3593  3593 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:19.099  3593  3593 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:19.101  2793  3464 W SyncManagerImpl: Sync completed for AccountId 3a3529a (com.google.android.apps.docs)
,07-12 11:36:19.107   787  1324 I ActivityManager: Killing 2854:com.quickoffice.android/u0a65 (adj 15): empty #17
,07-12 11:36:19.210  3593  3593 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:19.221  3593  3593 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:19.226  3593  3593 I AlarmClock: AlarmInitReceiver android.intent.action.TIME_SET
,07-12 11:36:19.234  3593  3617 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:19.265   787  1325 I ActivityManager: Killing 2714:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-12 11:36:19.591  1558  1558 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:19.595  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:36:19.595  3031  3099 I jxcore-log: 
,07-12 11:36:19.607  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:36:19.607  3031  3099 I jxcore-log: 
,07-12 11:36:19.614  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:36:19.614  3031  3099 I jxcore-log: 
,07-12 11:36:19.777  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:36:19.777  3031  3099 I jxcore-log: 
,07-12 11:36:20.100  1558  3265 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 11:36:20.163   787   800 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.phenotype.service.PhenotypeCommitChimeraService (has extras) } U=0: not found
,07-12 11:36:20.250  1558  3630 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-12 11:36:20.266  1572  1639 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.ocr
,07-12 11:36:20.276  1558  3656 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-12 11:36:20.276  1558  1629 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
,07-12 11:36:20.280  1558  3656 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:20.280  1558  1629 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
,07-12 11:36:20.282  1558  3630 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-12 11:36:20.285  1558  3656 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:20.285  1558  1629 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
07-12 11:36:20.285  1558  1629 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.tapandpay
,07-12 11:36:20.534  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:36:20.534  3031  3099 I jxcore-log: 
,07-12 11:36:20.591  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:36:20.591  3031  3099 I jxcore-log: 
,07-12 11:36:20.597  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:36:20.597  3031  3099 I jxcore-log: 
,07-12 11:36:20.815  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:36:20.815  3031  3099 I jxcore-log: 
,07-12 11:36:20.838  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:36:20.838  3031  3099 I jxcore-log: 
,07-12 11:36:20.842  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:36:20.842  3031  3099 I jxcore-log: 
,07-12 11:36:20.848  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:36:20.848  3031  3099 I jxcore-log: 
,07-12 11:36:20.865  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:36:20.865  3031  3099 I jxcore-log: 
,07-12 11:36:20.886  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:36:20.886  3031  3099 I jxcore-log: 
,07-12 11:36:20.957  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:20.982  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:36:20.982  3031  3099 I jxcore-log: 
,07-12 11:36:20.987  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:36:20.987  3031  3099 I jxcore-log: 
,07-12 11:36:21.013  3031  3099 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:36:21.013  3031  3099 I jxcore-log: 
,07-12 11:36:21.022  3031  3099 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-12 11:36:21.023  3031  3099 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 11:36:21.023  3031  3099 I jxcore-log: 
,07-12 11:36:21.031  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:21.073  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:36:21.073  3031  3099 I jxcore-log: 
,07-12 11:36:21.074  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:36:21.074  3031  3099 I jxcore-log: 
,07-12 11:36:21.075  3031  3099 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:36:21.075  3031  3099 I jxcore-log: 
,07-12 11:36:21.080  1572  3679 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-12 11:36:21.081  1572  3679 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-12 11:36:21.262   787  1332 I ActivityManager: Start proc 3688:com.google.android.gms.unstable/u0a7 for service com.google.android.gms/.droidguard.DroidGuardService
,07-12 11:36:21.328  3688  3688 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 11:36:21.328  3688  3688 I MultiDex: install
07-12 11:36:21.328  3688  3688 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:21.348  3688  3688 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:36:21.358  3688  3688 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-12 11:36:21.359  3688  3688 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:36:21.362  3688  3688 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:36:21.385  3688  3688 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:21.394  3688  3688 D ChimeraCfgMgr: Reading stored module config
,07-12 11:36:21.461  3688  3705 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-12 11:36:21.515   197  1071 D WVCdm   : Instantiating CDM.
,07-12 11:36:21.517   197   197 I WVCdm   : CdmEngine::OpenSession
,07-12 11:36:21.517   197   197 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 11:36:21.527   197   197 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-12 11:36:21.530   197   197 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-12 11:36:21.530   197   197 D DrmWidevineDash: Service_Initialize: starts!
07-12 11:36:21.530   197   197 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-12 11:36:21.530   197   197 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 11:36:21.549   197   197 D QSEECOMAPI: : Loaded image: APP id = 3
,07-12 11:36:21.549   197   197 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-12 11:36:21.549   197   197 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3487000
07-12 11:36:21.550   197   197 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3487000
,07-12 11:36:21.563   197   197 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-12 11:36:21.563   197   197 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-12 11:36:21.568   197   197 D DrmWidevineDash: hlos api version =  10
07-12 11:36:21.568   197   197 D DrmWidevineDash: tz api version =  10
,07-12 11:36:21.568   197   197 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 11:36:21.568   197   197 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-12 11:36:21.588   197   197 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-12 11:36:21.588   197   197 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 11:36:21.588   197   197 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbed0e214
,07-12 11:36:21.594   197   197 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-12 11:36:21.594   197   197 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-12 11:36:21.594   197   197 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608c408, dataLength=8
,07-12 11:36:21.601   197   197 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-12 11:36:21.613   197   197 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60be800, wrapped_rsa_key_length=1280
,07-12 11:36:21.622   197   197 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-12 11:36:21.622   197   197 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:36:21.631   197   830 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:36:21.631   197   830 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,07-12 11:36:21.631   197   830 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:36:21.631   197   830 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb257f6e0, idLength=0xb37bef2c
,07-12 11:36:21.641   197   830 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-12 11:36:21.642   197   830 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-12 11:36:21.647   197   830 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-12 11:36:21.647   197   830 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-12 11:36:21.647   197   830 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-12 11:36:21.647   197   830 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-12 11:36:21.651   197   830 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-12 11:36:21.652   197   830 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-12 11:36:21.657   197   830 D DrmWidevineDash: hlos api version =  10
,07-12 11:36:21.657   197   830 D DrmWidevineDash: tz api version =  10
07-12 11:36:21.657   197   830 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 11:36:21.657   197   830 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-12 11:36:21.662   197   830 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-12 11:36:21.662   197   830 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-12 11:36:21.662   197   830 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-12 11:36:21.667   197   830 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-12 11:36:21.667   197   830 D WVCdm   : PrepareKeyRequest: nonce=2417338068
07-12 11:36:21.667   197   830 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb48e4c00
07-12 11:36:21.667   197   830 D DrmWidevineDash: message_length=1639, signature=0xb60b6c00, signature_length=3011244036
,07-12 11:36:21.742   197   830 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-12 11:36:21.743   197  1071 I WVCdm   : CdmEngine::CloseSession
,07-12 11:36:21.743   197  1071 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-12 11:36:21.748   197  1071 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-12 11:36:21.748   197  1071 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-12 11:36:21.753   197  1071 D DrmWidevineDash: Service_Uninitialize: starts!
,07-12 11:36:21.753   197  1071 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-12 11:36:21.753   197  1071 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-12 11:36:21.754   197  1071 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-12 11:36:21.755   197  1071 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-12 11:36:22.084  3746  3746 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 11:36:22.176  3746  3746 I dex2oat : dex2oat took 94.840ms (threads: 4) arena alloc=276KB java alloc=39KB native alloc=1793KB free=1790KB
,07-12 11:36:22.181  3688  3698 W System  : ClassLoader referenced unknown path: 
,07-12 11:36:22.186  3688  3698 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:22.247  3688  3698 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:22.285  3688  3698 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:22.907  1558  3756 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:22.907  1558  3754 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:36:22.926  1558  3756 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:22.926  1558  3754 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:36:22.955  1558  3756 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:22.956  1558  3754 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:36:22.956  1558  3754 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-12 11:36:22.959  1558  3754 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:23.744  3563  3578 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:36:24.327   787   893 D ConnectivityService: handlePromptUnvalidated 100
,07-12 11:36:26.040   787   800 I ActivityManager: Killing 2911:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,07-12 11:36:27.447   787   983 I ActivityManager: Killing 2962:com.google.android.gms:car/u0a7 (adj 15): empty #17
,07-12 11:36:28.755   787   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,07-12 11:36:30.836   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:32.040   787   803 I ActivityManager: Waited long enough for: ServiceRecord{a0a77a1 u0 com.google.android.apps.maps/com.google.android.apps.gmm.offline.OfflineAutoUpdateService}
,07-12 11:36:33.887   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:36.316   787   891 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:36:39.957   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:49.749  1572  3784 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:36:49.758   787   802 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 139644, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:36:49.759   787   802 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 205489, reason: UserStart
,07-12 11:36:52.081   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:55.128   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:57.994   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:36:58.155   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:37:00.850   787   810 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 11:37:00.850   787   810 I PowerManagerService: Sleeping (uid 1000)...
,07-12 11:37:00.856   189   291 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (495 us)
,07-12 11:37:00.856   787   810 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:37:00.890  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:37:00.891  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 11:37:00.942  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@19264a0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c437ad8, 16908290=android.view.AbsSavedState$1@c437ad8}, android:focusedViewId=100}]}],
07-12 11:37:00.942  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:37:00.942  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:37:00.942  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:37:01.410   787   810 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:37:01.422   787   810 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-12 11:37:01.425   787   808 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 11:37:01.433   189   189 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
07-12 11:37:01.433   189   189 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-12 11:37:01.715   189   189 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-12 11:37:01.716   787   912 D SurfaceControl: Excessive delay in setPowerMode(): 291ms
07-12 11:37:01.717  1788  1795 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-12 11:37:01.734   197   830 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-12 11:37:01.755   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:37:01.766   787   891 E native  : do suspend false
,07-12 11:37:01.773   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:37:01.786   197  1071 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-12 11:37:01.791   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:37:01.793   787   891 E native  : do suspend true
,07-12 11:37:01.802  1242  1242 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-12 11:37:01.837  1558  1558 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-12 11:37:01.839  1558  1558 I BeaconBle: BLE 'JB+' software access layer enabled
,07-12 11:37:01.850  1558  3842 D BluetoothAdapter: startLeScan(): null
,07-12 11:37:01.851  1558  3842 D BluetoothAdapter: STATE_ON
,07-12 11:37:01.853  3162  3174 D BtGatt.GattService: registerClient() - UUID=378cdc83-9bb9-4a13-8330-560dc03434e5
,07-12 11:37:01.853  3162  3183 D BtGatt.GattService: onClientRegistered() - UUID=378cdc83-9bb9-4a13-8330-560dc03434e5, clientIf=5
,07-12 11:37:01.853  1558  1571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 11:37:01.853  3162  3243 D BtGatt.GattService: start scan with filters
,07-12 11:37:01.855  3162  3187 D BtGatt.ScanManager: handling starting scan
,07-12 11:37:01.857  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-12 11:37:01.857  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 11:37:01.857  3162  3187 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 11:37:01.857  3162  3183 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 11:37:02.244  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:02.260   787   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,07-12 11:37:02.280  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:02.299  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:02.319  1558  3244 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:37:02.363  1558  3244 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:02.364  1558  3244 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-12 11:37:02.366  1558  3244 V BaseAppContext: GmsRequestQueue started.
,07-12 11:37:02.827  1572  1572 V Herrevad: NQAS connected
,07-12 11:37:02.930  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:37:02.931  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:37:03.367  1558  3842 D BluetoothAdapter: stopLeScan()
,07-12 11:37:03.371  1558  3842 D BluetoothAdapter: STATE_ON
,07-12 11:37:03.372  3162  3172 D BtGatt.GattService: stopScan() - queue size =1
,07-12 11:37:03.377  3162  3187 D BtGatt.ScanManager: stop scan
,07-12 11:37:03.377  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
,07-12 11:37:03.377  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
,07-12 11:37:03.377  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-12 11:37:03.397  3162  3262 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 11:37:03.589  1558  3842 D BluetoothAdapter: startLeScan(): null
,07-12 11:37:03.596  1558  3842 D BluetoothAdapter: STATE_ON
07-12 11:37:03.605  3162  3262 D BtGatt.GattService: registerClient() - UUID=ef85ce4f-9988-41cf-91af-ca5a1d3fb4a2
07-12 11:37:03.606  3162  3183 D BtGatt.GattService: onClientRegistered() - UUID=ef85ce4f-9988-41cf-91af-ca5a1d3fb4a2, clientIf=5
07-12 11:37:03.607  1558  1570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 11:37:03.609  3162  3261 D BtGatt.GattService: start scan with filters
07-12 11:37:03.616  3162  3187 D BtGatt.ScanManager: handling starting scan
07-12 11:37:03.622  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-12 11:37:03.622  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
,07-12 11:37:03.622  3162  3187 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 11:37:03.693  3162  3183 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 11:37:04.071  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:04.192  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:04.244  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:04.465  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:37:04.867  1558  3842 D BluetoothAdapter: stopLeScan()
,07-12 11:37:04.871  1558  3842 D BluetoothAdapter: STATE_ON
07-12 11:37:04.872  3162  3174 D BtGatt.GattService: stopScan() - queue size =1
07-12 11:37:04.874  3162  3187 D BtGatt.ScanManager: stop scan
07-12 11:37:04.874  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 11:37:04.874  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
,07-12 11:37:04.874  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 11:37:04.897  3162  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 11:37:04.898  1558  3842 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 11:37:05.998   787   983 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1572 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:06.048  1572  3910 W DriveInitializer: Background init thread started
,07-12 11:37:06.149  1572  3910 W DriveInitializer: Background init thread ended
,07-12 11:37:06.443  1558  1706 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:37:07.384   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157657, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:37:07.853  1558  3838 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 11:37:16.320   787   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,07-12 11:38:04.434   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=214707, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:38:19.613  1572  1572 V Herrevad: NQAS connected
,07-12 11:38:19.649  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:38:19.649  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:38:19.760   190   190 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6cca030
07-12 11:38:19.760   190   190 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
07-12 11:38:19.760   190   190 I rmt_storage: wakelock acquired: 1, error no: 2
07-12 11:38:19.760   190   422 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228146384)
,07-12 11:38:19.826   190   422 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,07-12 11:38:19.826   190   422 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
07-12 11:38:19.826   190   422 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228146384) wakelock released: 1, error no: 0
07-12 11:38:19.826   190   422 I rmt_storage: 
,07-12 11:38:19.828   190   190 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6cca030
,07-12 11:38:21.996   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=232269, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:38:54.514   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264787, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:39:19.715  1572  1572 V Herrevad: NQAS connected
,07-12 11:39:19.767  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:39:19.768  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:39:54.177  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:39:54.181  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:39:54.181  1558  1558 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:39:59.214   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329487, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:40:19.508   787   883 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-12 11:40:19.509   787   787 V KeyguardServiceDelegate: onStartedWakingUp()
,07-12 11:40:19.512   787   810 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-12 11:40:19.537  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-12 11:40:19.537  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-12 11:40:19.537  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-12 11:40:19.537  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-12 11:40:19.544   787   810 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@f564d12)
07-12 11:40:19.549   197   899 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-12 11:40:19.557   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:40:19.557   787  1325 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-12 11:40:19.562   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:19.562   787   891 E native  : do suspend false
,07-12 11:40:19.572   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:40:19.590  1242  1242 I LanguageModelDownload: onCreate()
,07-12 11:40:19.601  1242  3987 I LanguageModelDownload: Unable to format log message: 'onRunTask() : Tag = %slm_download_metered_task' error:'java.util.MissingFormatArgumentException: Format specifier: s'
,07-12 11:40:19.604  1242  3987 I LanguageModelDownload: onRunTask() : Metered ... Too Soon ... Done
,07-12 11:40:19.612  1572  1572 V Herrevad: NQAS connected
,07-12 11:40:19.615  1242  1242 I LanguageModelDownload: onDestroy()
,07-12 11:40:19.627  1788  1795 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
07-12 11:40:19.628   787   808 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-12 11:40:19.628   189   189 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
07-12 11:40:19.628   189   189 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-12 11:40:19.654  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:40:19.656  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:40:19.666  1558  1558 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-12 11:40:19.682   787   801 I ActivityManager: Start proc 4004:com.google.android.apps.fitness/u0a82 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-12 11:40:19.721  4004  4004 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.fitness-2/lib/arm
,07-12 11:40:19.792   787   810 I DisplayPowerController: Unblocked screen on after 280 ms
,07-12 11:40:19.793   787   810 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-12 11:40:19.837  1558  1558 I BeaconBle: Building BLE scanner compat:  'L/M' hardware access layer is not available: btAdapter.isOffloadedFilteringSupported() is false.
,07-12 11:40:19.839  1558  1558 I BeaconBle: BLE 'JB+' software access layer enabled
,07-12 11:40:19.852  1558  4032 D BluetoothAdapter: startLeScan(): null
,07-12 11:40:19.854  1558  4032 D BluetoothAdapter: STATE_ON
,07-12 11:40:19.855  3162  3243 D BtGatt.GattService: registerClient() - UUID=0356febb-4d11-4462-b5ef-c54899c4f8ee
07-12 11:40:19.855  3162  3183 D BtGatt.GattService: onClientRegistered() - UUID=0356febb-4d11-4462-b5ef-c54899c4f8ee, clientIf=5
07-12 11:40:19.855  1558  1571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 11:40:19.856  3162  3172 D BtGatt.GattService: start scan with filters
,07-12 11:40:19.857  3162  3187 D BtGatt.ScanManager: handling starting scan
,07-12 11:40:19.858  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-12 11:40:19.858  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 11:40:19.858  3162  3187 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 11:40:19.859  3162  3183 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 11:40:19.883   189   189 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-12 11:40:19.883   787   912 D SurfaceControl: Excessive delay in setPowerMode(): 256ms
,07-12 11:40:19.935  4004  4004 W Fit     : No acount yet, skipping caching values.
,07-12 11:40:19.937   787  1319 I ActivityManager: Killing 1399:com.google.android.googlequicksearchbox:search/u0a19 (adj 15): empty #17
,07-12 11:40:19.953   787   951 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ], android.os.BinderProxy@20347d1)
07-12 11:40:19.953   787   892 D WifiService: Client connection lost with reason: 4
07-12 11:40:19.953   787   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-12 11:40:19.953   787   893 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-12 11:40:20.075  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:20.086  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:20.117  1558  4018 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:40:20.401  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:20.657  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:20.779  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Sluchawki Bose len=14 dev_type=3
,07-12 11:40:21.168  1558  4018 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:40:21.363  1558  4032 D BluetoothAdapter: stopLeScan()
,07-12 11:40:21.364  1558  4032 D BluetoothAdapter: STATE_ON
,07-12 11:40:21.365  3162  3261 D BtGatt.GattService: stopScan() - queue size =1
07-12 11:40:21.365  3162  3174 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 11:40:21.365  3162  3187 D BtGatt.ScanManager: stop scan
07-12 11:40:21.365  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 11:40:21.365  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 11:40:21.365  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-12 11:40:21.538  1558  4032 D BluetoothAdapter: startLeScan(): null
,07-12 11:40:21.540  1558  4032 D BluetoothAdapter: STATE_ON
,07-12 11:40:21.542  3162  3174 D BtGatt.GattService: registerClient() - UUID=3884a5c7-d63b-4ee2-8d20-7ec909935e7f
,07-12 11:40:21.542  3162  3183 D BtGatt.GattService: onClientRegistered() - UUID=3884a5c7-d63b-4ee2-8d20-7ec909935e7f, clientIf=5
07-12 11:40:21.542  1558  1571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 11:40:21.542  3162  3262 D BtGatt.GattService: start scan with filters
,07-12 11:40:21.545  3162  3187 D BtGatt.ScanManager: handling starting scan
,07-12 11:40:21.547  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
,07-12 11:40:21.547  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=2 mLastConfiguredScanSetting=-2147483648
07-12 11:40:21.547  3162  3187 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 8000
07-12 11:40:21.547  3162  3183 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-12 11:40:21.985  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:22.089  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:22.223  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=Sluchawki Bose len=14 dev_type=3
,07-12 11:40:22.496  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:22.558  1558  4018 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:40:22.576   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:22.667  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:22.757  3162  3183 D bt_btif_gattc: btif_gattc_update_properties BLE device name=estimote len=8 dev_type=2
,07-12 11:40:22.904  1558  4032 D BluetoothAdapter: stopLeScan()
,07-12 11:40:22.908  1558  4032 D BluetoothAdapter: STATE_ON
07-12 11:40:22.908  3162  3262 D BtGatt.GattService: stopScan() - queue size =1
07-12 11:40:22.909  3162  3187 D BtGatt.ScanManager: stop scan
07-12 11:40:22.909  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-12 11:40:22.909  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=2
07-12 11:40:22.909  3162  3187 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-12 11:40:22.924  3162  3243 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 11:40:22.924  1558  4032 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 11:40:23.618  1558  4018 W Settings: Setting development_settings_enabled has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:40:25.630   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:25.894  1558  4027 I BeaconBle: Scan : No clients left, canceling alarm.
,07-12 11:40:56.274   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386547, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:41:01.998   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:41:14.131   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:41:17.186   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:41:19.898  1572  1572 V Herrevad: NQAS connected
,07-12 11:41:20.008  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:41:20.010  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:41:20.075  1572  1639 V Herrevad: [111] otf.a: Skipping report; opted out of usage reporting
,07-12 11:41:20.228   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:41:21.695   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411968, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:41:23.248   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:41:54.194   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=444467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:42:18.005   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468278, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:42:19.672  1558  1706 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:42:20.087  1572  1572 V Herrevad: NQAS connected
,07-12 11:42:20.175  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:42:20.176  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:42:20.431   787   810 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-12 11:42:20.431   787   810 I PowerManagerService: Sleeping (uid 1000)...
,07-12 11:42:20.455  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:42:20.455  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 11:42:20.491  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@19264a0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c437ad8, 16908290=android.view.AbsSavedState$1@c437ad8}, android:focusedViewId=100}]}]
,07-12 11:42:20.491  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:42:20.491  3031  3031 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:42:20.491  3031  3031 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:42:20.903   787   810 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:42:20.922   787   808 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 11:42:20.953   189   189 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,07-12 11:42:20.958   189   189 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-12 11:42:21.253   189   189 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-12 11:42:21.254   787   912 D SurfaceControl: Excessive delay in setPowerMode(): 331ms
07-12 11:42:21.254  1788  1795 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-12 11:42:21.257   197   899 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-12 11:42:21.269  1242  1242 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-12 11:42:21.270   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:42:21.274   787   891 E native  : do suspend true
,07-12 11:42:50.514   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=500787, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:42:51.405  1572  1572 V Herrevad: NQAS connected
,07-12 11:42:51.463  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:42:51.464  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:42:56.314   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=506587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:43:23.874   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=534147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:43:59.786   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=570059, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:44:20.273  1572  1572 V Herrevad: NQAS connected
,07-12 11:44:20.300  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:44:20.301  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:44:32.274   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=602547, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:44:59.516   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=629789, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:45:20.370  1572  1572 V Herrevad: NQAS connected
,07-12 11:45:20.425  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:45:20.426  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:45:32.034   787  3303 D NetlinkSocketObserver: NeighborEvent{elapsedMs=662307, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:46:20.497  1572  1572 V Herrevad: NQAS connected
,07-12 11:46:20.578  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:46:20.580  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:47:20.634  1572  1572 V Herrevad: NQAS connected
,07-12 11:47:20.659  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:47:20.660  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:48:20.759  1572  1572 V Herrevad: NQAS connected
,07-12 11:48:20.821  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:48:20.822  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:49:20.890  1572  1572 V Herrevad: NQAS connected
,07-12 11:49:20.939  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:49:20.941  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:50:21.028  1572  1572 V Herrevad: NQAS connected
,07-12 11:50:21.066  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:50:21.067  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:51:21.080   787   880 I ActivityManager: Start proc 4345:com.google.android.googlequicksearchbox:search/u0a19 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.speech.grammar.GrammarCompilationService
,07-12 11:51:21.192  1572  1572 V Herrevad: NQAS connected
,07-12 11:51:21.230  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:51:21.232  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:51:21.273  1572  4369 I EventLogChimeraService: Aggregate from 1468315017803 (log), 1468315017803 (data)
,07-12 11:51:21.335   787   892 D WifiService: New client listening to asynchronous messages
,07-12 11:51:21.368  4345  4383 W ModelDownloadController: Cannot find any speech config location.
,07-12 11:51:21.368  4345  4383 W ModelDownloadController: Cannot find any speech config location.
,07-12 11:51:21.402  1572  4385 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 11:51:21.414  1572  4385 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 11:51:21.422  4345  4377 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-12 11:51:21.467  4345  4377 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-12 11:51:21.467  4345  4377 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-12 11:51:21.475  4345  4377 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,07-12 11:51:21.475  4345  4377 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-12 11:51:21.491  4345  4377 I ContextCompilationHandl: Recognition context unchanged for CONTACT_NAMES en-US
,07-12 11:51:21.491  4345  4377 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-12 11:51:21.594  1572  4396 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-12 11:51:21.657  1572  1704 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-12 11:51:21.731  4345  4377 I GsaNativeCrashHandler: Loaded shared library: nativecrashreporter
,07-12 11:51:22.137  4345  4377 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-12 11:51:22.171  1572  1641 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-12 11:51:22.191  1572  1641 E Icing   : No scoring data for corpus [21]
,07-12 11:51:22.218  1572  1644 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 11:51:22.238  1572  1644 E Icing   : No scoring data for corpus [15]
,07-12 11:51:22.264  1572  1641 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 11:51:22.312  1572  1644 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 11:51:22.329  1572  1644 E Icing   : No scoring data for corpus [22]
,07-12 11:51:22.330  4345  4377 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-12 11:51:22.332   787  1357 I ActivityManager: Killing 3196:com.android.settings/1000 (adj 15): empty #17
,07-12 11:51:22.339   787   892 D WifiService: Client connection lost with reason: 4
,07-12 11:52:21.357  1572  1572 V Herrevad: NQAS connected
,07-12 11:52:21.418  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:52:21.419  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:53:21.497  1572  1572 V Herrevad: NQAS connected
,07-12 11:53:21.533  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:53:21.534  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:54:21.637  1572  1572 V Herrevad: NQAS connected
,07-12 11:54:21.662  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:54:21.663  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:54:50.005   787   802 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 11:55:21.733  1572  1572 V Herrevad: NQAS connected
,07-12 11:55:21.766  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:55:21.767  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:56:21.875  1572  1572 V Herrevad: NQAS connected
,07-12 11:56:21.903  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:56:21.904  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:57:21.966  1572  1572 V Herrevad: NQAS connected
,07-12 11:57:22.036  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:57:22.037  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:58:22.108  1572  1572 V Herrevad: NQAS connected
,07-12 11:58:22.150  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:58:22.151  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:59:22.270  1572  1572 V Herrevad: NQAS connected
,07-12 11:59:22.309  1572  1639 W Herrevad: Invalid mccmnc 
,07-12 11:59:22.310  1572  1639 W Herrevad: Invalid mccmnc 
,TIME-OUT KILL (timeout was 1400000ms),07-12 11:59:32.378  4647  4647 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:59:32.382  4647  4647 D AndroidRuntime: CheckJNI is OFF
07-12 11:59:32.420  4647  4647 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:59:32.463  4647  4647 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:59:32.483  4647  4647 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 11:59:32.490   787   803 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
07-12 11:59:32.490   787   803 I ActivityManager: Killing 3031:com.test.thalitest/u0a26 (adj 0): stop com.test.thalitest
07-12 11:59:32.555   787  1356 D GraphicsStats: Buffer count: 2
07-12 11:59:32.555   787  1356 I WindowState: WIN DEATH: Window{5d95287 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 11:59:32.555   787  1319 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@58ee9b0)
07-12 11:59:32.557   787   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:59:32.557   787   893 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:59:32.557   787   892 D WifiService: Client connection lost with reason: 4
07-12 11:59:32.576   787   818 W PackageSettings: Skipping PackageSetting{f49969 com.example.hello/10116} due to missing metadata
07-12 11:59:32.613   787   803 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-12 11:59:32.614   787   803 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-12 11:59:32.619   787   803 E ActivityManager: Failure starting process com.test.thalitest
07-12 11:59:32.619   787   803 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-12 11:59:32.619   787   803 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:59:32.619   787   803 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:59:32.619   787   803 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:59:32.619   787   803 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 11:59:32.620   787   803 I ActivityManager:   Force finishing activity ActivityRecord{1b18e51 u0 com.test.thalitest/.MainActivity t46}
07-12 11:59:32.622   787   818 I art     : Starting a blocking GC Explicit
07-12 11:59:32.626   787  1319 W ActivityManager: Spurious death for ProcessRecord{72d5029 0:com.test.thalitest/u0a26}, curProc for 3031: null
07-12 11:59:32.668   787   818 I art     : Explicit concurrent mark sweep GC freed 36310(2MB) AllocSpace objects, 11(236KB) LOS objects, 33% free, 25MB/38MB, paused 763us total 43.409ms
07-12 11:59:32.681   787   818 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-12 11:59:32.683  4647  4647 I art     : System.exit called, status: 0
07-12 11:59:32.683  4647  4647 I AndroidRuntime: VM exiting with result code 0.
07-12 11:59:32.693   787   818 I ActivityManager: Start proc 4664:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
07-12 11:59:32.694   787   818 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
07-12 11:59:32.746   787   803 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-12 11:59:32.752   787   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 11:59:32.753  1558  1645 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 11:59:32.753  3162  3162 D BluetoothMapAppObserver: onReceive
07-12 11:59:32.753  3162  3162 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-12 11:59:32.788  2079  4688 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-12 11:59:32.796   787  1325 I ActivityManager: Start proc 4690:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
07-12 11:59:32.802  1308  1308 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-12 11:59:32.814  2079  2097 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjAB1612984) - 
07-12 11:59:32.818   787   889 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
--------- beginning of crash
07-12 11:59:32.822  2079  2097 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
07-12 11:59:32.822  2079  2097 E AndroidRuntime: Process: android.process.acore, PID: 2079
07-12 11:59:32.822  2079  2097 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:59:32.822  2079  2097 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: Can't write: system_app_crash
07-12 11:59:32.831   787  4710 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 11:59:32.831   787  4710 E DropBoxManagerService: 	... 5 more
07-12 11:59:32.834  2079  4688 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
07-12 11:59:32.834  2079  4688 I Process : Sending signal. PID: 2079 SIG: 9
07-12 11:59:32.849  4690  4690 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-12 11:59:32.873   787   787 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 11:59:32.874   787   801 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3031 uid 10026
07-12 11:59:32.875   787   800 I ActivityManager: Process android.process.acore (pid 2079) has died
07-12 11:59:32.875   787   800 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms

```
