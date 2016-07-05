#### Test 7214543196063dc_thali03_LGE-Nexus 5 Logs


```
--------- beginning of system
07-05 14:03:49.387   787   954 I ActivityManager: Killing 2404:com.google.android.deskclock/u0a33 (adj 15): empty #17
,--------- beginning of main
07-05 14:03:50.575  2907  2907 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:03:50.579  2907  2907 D AndroidRuntime: CheckJNI is OFF
07-05 14:03:50.613  2907  2907 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:03:50.647  2907  2907 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:03:50.665  2907  2907 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:03:50.668   787  1332 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:03:50.693  1364  1378 W SearchService: Abort, client detached.
07-05 14:03:50.699  1364  1567 I DeviceStateChecker: DeviceStateChecker cancelled
07-05 14:03:50.700  1364  1364 I MicroDetector: Keeping mic open: false
07-05 14:03:50.700  1364  1364 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@5f85ef
07-05 14:03:50.700  1364  1473 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-05 14:03:50.705  2907  2907 D AndroidRuntime: Shutting down VM
07-05 14:03:50.730   787  1195 I ActivityManager: Start proc 2923:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
07-05 14:03:50.736  1364  1600 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
07-05 14:03:50.750   199  1583 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-05 14:03:50.750   199  1583 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-05 14:03:50.760  1364  1577 I MicroRecognitionRunner: Detection finished
07-05 14:03:50.760  1364  1566 I MicroRecognitionRunner: Stopping hotword detection.
07-05 14:03:50.825  2923  2923 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108600)
07-05 14:03:50.879  2923  2923 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 2285-2287)
07-05 14:03:50.879  2923  2923 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
07-05 14:03:50.897  2923  2923 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {356dba9}
07-05 14:03:50.897  2923  2923 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
07-05 14:03:50.898  2923  2923 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:03:50.911   787   892 D WifiService: New client listening to asynchronous messages
,07-05 14:03:50.923  2923  2923 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-05 14:03:50.934  2923  2923 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
07-05 14:03:50.934  2923  2923 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
,07-05 14:03:50.944  2923  2923 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:03:50.986   787   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@156be1e:true
,07-05 14:03:51.015   787  1320 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/2923 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:03:51.023  2923  2923 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,07-05 14:03:51.030  2923  2923 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 14:03:51.031  2923  2923 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-05 14:03:51.041  2923  2923 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-05 14:03:51.063  2923  2923 I cr_Ime  : ImeThread is not enabled.
,07-05 14:03:51.075  2923  2965 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 14:03:51.104   787   954 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/2923 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:03:51.126  2923  2969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 14:03:51.133  2923  2965 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 14:03:51.191   787   812 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +474ms
,07-05 14:03:51.196  2923  2923 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2923
,07-05 14:03:51.196  2923  2923 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,07-05 14:03:51.197  2923  2923 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,07-05 14:03:51.383  2923  2923 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:03:51.384   787   893 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:03:51.537  2923  2978 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1734489808
,07-05 14:03:51.540  2923  2978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:03:51.540  2923  2978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:03:51.540  2923  2978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:03:51.540  2923  2978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:03:51.540  2923  2978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 14:03:51.540  2923  2978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b819f95 added. We now have 1 listener(s)
07-05 14:03:51.542  2923  2978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
07-05 14:03:51.542  2923  2978 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
07-05 14:03:51.543  2923  2978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:03:51.543  2923  2978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 14:03:51.545   787  1320 I ActivityManager: Killing 2425:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-05 14:03:51.546  2923  2978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69c6838 added. We now have 1 listener(s)
07-05 14:03:51.546  2923  2978 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 14:03:51.547  2923  2978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:03:51.547  2923  2978 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-05 14:03:51.548  2923  2978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 14:03:51.548  2923  2978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 14:03:51.548  2923  2978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 14:03:51.548  2923  2978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 14:03:51.576  2923  2978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:03:51.576  2923  2978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,07-05 14:03:51.578  2923  2978 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:03:51.578  2923  2978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:03:51.578  2923  2978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:03:51.578  2923  2978 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 14:03:51.578  2923  2978 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:03:51.600  2923  2923 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:03:52.001  2923  2932 I art     : Background sticky concurrent mark sweep GC freed 57558(5MB) AllocSpace objects, 16(1096KB) LOS objects, 29% free, 18MB/25MB, paused 5.482ms total 56.276ms
,07-05 14:03:52.483  2923  2980 W jxcore-log: Initializing JXcore engine
,07-05 14:03:52.483  2923  2980 W jxcore-log: JXcore engine is ready
,07-05 14:03:52.506  2980  2980 W Thread-255: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10577]" dev="sockfs" ino=10577 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-05 14:03:52.506  2980  2980 W Thread-255: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:03:52.506  2980  2980 W Thread-255: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[20092]" dev="sockfs" ino=20092 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 14:03:52.529  2923  2980 W jxcore-log: Starting JXcore engine
,07-05 14:03:52.602  2923  2980 W jxcore-log: Platform android
07-05 14:03:52.602  2923  2980 W jxcore-log: 
,07-05 14:03:52.602  2923  2980 W jxcore-log: Process ARCH arm
07-05 14:03:52.602  2923  2980 W jxcore-log: 
,07-05 14:03:52.835  2923  2980 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:03:52.835  2923  2980 I jxcore-log: 
,07-05 14:03:52.836  2923  2980 W jxcore-log: JXcore engine is started
,07-05 14:03:52.841  2923  2978 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:03:52.843  2923  2923 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:03:57.142  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:03:57.142  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:03:57.163  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:03:57.297  2810  2840 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:03:57.309  2810  2840 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,07-05 14:03:57.309  2810  2840 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:03:57.312  2810  2840 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:03:57.334  2810  2840 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:00.772  1548  1640 I Finsky  : [110] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-05 14:04:00.957  1548  1640 I Finsky  : [110] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-05 14:04:00.958  1548  1548 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-05 14:04:02.637  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:02.637  2923  2980 I jxcore-log: 
,07-05 14:04:02.639  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:02.639  2923  2980 I jxcore-log: 
,07-05 14:04:02.640  2923  2980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:02.640  2923  2980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-05 14:04:02.640  2923  2980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:02.640  2923  2980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:02.642  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:02.642  2923  2980 I jxcore-log: 
,07-05 14:04:02.643  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:02.643  2923  2980 I jxcore-log: 
,07-05 14:04:03.010  2923  2980 I jxcore-log: Unit Test app is loaded
07-05 14:04:03.010  2923  2980 I jxcore-log: 
,07-05 14:04:03.016  2923  2923 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:03.018  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-05 14:04:03.018  2923  2980 I jxcore-log: 
,07-05 14:04:03.022   787  1195 D WifiService: setWifiEnabled: true pid=2923, uid=10026
07-05 14:04:03.022   787  1195 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-05 14:04:03.025   195   785 D SoftapController: Softap fwReload - Ok
,07-05 14:04:03.028   195   785 D CommandListener: Setting iface cfg
,07-05 14:04:03.028   195   785 D CommandListener: Trying to bring down wlan0
,07-05 14:04:03.028   195   785 D CommandListener: Clearing all IP addresses on wlan0
07-05 14:04:03.032  2923  2980 I jxcore-log: My device name is: LGE-Nexus 5
07-05 14:04:03.032  2923  2980 I jxcore-log: 
07-05 14:04:03.042   787   891 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-05 14:04:03.047   787   811 I ActivityManager: Start proc 3021:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding HeadsetService
,07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding A2dpService
07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding HidService
07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding HealthService
,07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding PanService
,07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding GattService
,07-05 14:04:03.181  3021  3021 D AdapterServiceConfig: Adding BluetoothMapService
,07-05 14:04:03.196   787   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19bd5e1:true
,07-05 14:04:03.197  3021  3021 D BluetoothAdapterState: make() - Creating AdapterState
,07-05 14:04:03.213  3021  3021 I bt_bluedroid: init
,07-05 14:04:03.214  3021  3034 I BluetoothAdapterState: Entering OffState
,07-05 14:04:03.239  3021  3035 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-05 14:04:03.239  3021  3035 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-05 14:04:03.240  3021  3035 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-05 14:04:03.240  3021  3035 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-05 14:04:03.241  3021  3021 I bt_bluedroid: get_profile_interface socket
,07-05 14:04:03.246  3021  3021 I bt_bluedroid: get_profile_interface sdp
,07-05 14:04:03.249  3021  3031 I bt_bluedroid: config_hci_snoop_log
,07-05 14:04:03.250   787   811 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-05 14:04:03.253  3021  3042 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-05 14:04:03.253  3021  3034 D BluetoothAdapterState: Current state: OFF, message: 0
,07-05 14:04:03.255  3021  3042 D BluetoothAdapterProperties: Name is: Nexus 5
,07-05 14:04:03.256  3021  3034 D BluetoothAdapterProperties: Setting state to 14
,07-05 14:04:03.256  3021  3034 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-05 14:04:03.258  3021  3034 D BluetoothBondStateMachine: make
,07-05 14:04:03.259  3021  3043 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-05 14:04:03.262  3021  3021 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-05 14:04:03.264  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
07-05 14:04:03.272  3021  3034 I BluetoothAdapterState: Entering PendingCommandState
07-05 14:04:03.272  3021  3021 D BtGatt.DebugUtils: handleDebugAction() action=null
07-05 14:04:03.272  3021  3021 D BtGatt.GattService: Received start request. Starting profile...
07-05 14:04:03.272  3021  3021 D BtGatt.GattService: start()
07-05 14:04:03.272  3021  3021 I bt_bluedroid: get_profile_interface gatt
,07-05 14:04:03.273  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
,07-05 14:04:03.273  3021  3021 D BtGatt.AdvertiseManager: advertise manager created
07-05 14:04:03.302  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:03.302  3021  3021 V BluetoothAdapterState: isTurningOn()=false
07-05 14:04:03.302  3021  3021 V BluetoothAdapterState: isBleTurningOn()=true
07-05 14:04:03.304  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:03.305  3021  3034 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-05 14:04:03.306  3021  3034 I bt_bluedroid: enable
07-05 14:04:03.306  3021  3035 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-05 14:04:03.312  3021  3035 I bt_hci  : start_up
,07-05 14:04:03.325  3021  3035 I bt_vendor: alloc value 0xb396a631
07-05 14:04:03.325  3021  3035 I bt_vendor: init
07-05 14:04:03.325  3021  3035 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-05 14:04:03.325  3021  3035 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-05 14:04:03.362  3021  3035 D bt_hci  : start_up starting async portion
07-05 14:04:03.362  3021  3048 I bt_hci  : event_finish_startup
07-05 14:04:03.362  3021  3048 I bt_hci_h4: hal_open
07-05 14:04:03.362  3021  3048 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-05 14:04:03.365  3021  3048 I bt_userial_vendor: device fd = 49 open
,07-05 14:04:03.447  3021  3048 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-05 14:04:03.474  3021  3048 D bt_hwcfg: Chipset BCM4335C0
,07-05 14:04:03.474  3021  3048 D bt_hwcfg: Target name = [BCM4335C0]
07-05 14:04:03.475  3021  3048 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-05 14:04:03.814  3021  3048 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-05 14:04:03.814  3021  3048 D bt_hwcfg: Settlement delay -- 100 ms
07-05 14:04:03.814  3021  3048 I bt_hwcfg: Setting fw settlement delay to 100 
,07-05 14:04:03.924   787   811 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-05 14:04:03.927   787   891 D wifi    : set interface wlan0 flags (UP)
,07-05 14:04:03.927   787   891 I WifiHAL : Initializing wifi
,07-05 14:04:03.927   787   891 I WifiHAL : Creating socket
,07-05 14:04:03.928   787   891 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-05 14:04:03.928   787   891 D wifi    : Did set static halHandle = 0x94b77360
07-05 14:04:03.928   787   891 D wifi    : halHandle = 0x94b77360, mVM = 0xb4cfc000, mCls = 0x201782
07-05 14:04:03.929   787   891 D wifi    : array field set
07-05 14:04:03.929   787   891 I WifiNative-HAL: interface[0] = p2p0
07-05 14:04:03.929   787   891 I WifiNative-HAL: interface[1] = wlan0
,07-05 14:04:03.932  3021  3048 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-05 14:04:03.932  3021  3048 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:B1:66
07-05 14:04:03.933   787  3063 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1799916704
07-05 14:04:03.933   787  3063 D wifi    : waitForHalEvents called, vm = 0xb4cfc000, obj = 0x201782, env = 0x94b73e80
,07-05 14:04:03.964  3021  3048 I bt_hwcfg: vendor lib fwcfg completed
,07-05 14:04:03.964  3021  3048 I bt_vendor: firmware callback
07-05 14:04:03.964  3021  3048 I bt_hci  : firmware_config_callback
,07-05 14:04:03.969  3021  3065 I bt_btu  : btu_task pending for preload complete event
07-05 14:04:03.969  3021  3065 I bt_btu_task: Bluetooth chip preload is complete
07-05 14:04:03.969  3021  3065 I bt_btu  : btu_task received preload complete event
,07-05 14:04:03.979  3021  3065 I         : BTE_InitTraceLevels -- TRC_HCI
,07-05 14:04:03.979  3021  3065 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-05 14:04:03.979  3021  3065 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-05 14:04:03.979  3021  3065 I         : BTE_InitTraceLevels -- TRC_AVDT
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_A2D
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_BTM
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_GAP
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_PAN
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_SDP
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_GATT
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_SMP
07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-05 14:04:03.980  3021  3065 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-05 14:04:03.994  3064  3064 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-05 14:04:04.016  3064  3064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-05 14:04:04.035  2923  2923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:04.036   787   891 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-05 14:04:04.043   787   803 I ActivityManager: Start proc 3067:com.android.settings/1000 for broadcast com.android.settings/.widget.SettingsAppWidgetProvider
,07-05 14:04:04.091  3067  3067 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-05 14:04:04.103  3064  3064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-05 14:04:04.112   787   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c45e78:true
,07-05 14:04:04.121  3067  3067 D LocalBluetoothProfileManager: Adding local MAP profile
,07-05 14:04:04.123  3067  3067 D BluetoothMap: Create BluetoothMap proxy object
,07-05 14:04:04.128  3067  3067 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-05 14:04:04.146   787  1320 I ActivityManager: Start proc 3079:com.google.android.apps.gcs/u0a37 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-05 14:04:04.147   787  1320 I ActivityManager: Killing 1776:com.google.android.apps.fitness/u0a82 (adj 15): empty #17
,07-05 14:04:04.199  3021  3065 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e89b5
,07-05 14:04:04.199  3021  3065 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e89b5 
,07-05 14:04:04.235  2923  2923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:04.235  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-05 14:04:04.237  2923  2923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:04.237  2923  2923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-05 14:04:04.240   787   891 D WifiConfigStore: Loading config and enabling all networks 
07-05 14:04:04.246   787   891 D WifiConfigStore: loaded 0 passpoint configs
,07-05 14:04:04.246  3021  3042 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-05 14:04:04.246  3021  3042 D BluetoothAdapterProperties: Address is:34:FC:EF:11:B1:66
,07-05 14:04:04.247  3021  3042 D BluetoothAdapterProperties: Name is: Nexus 5
07-05 14:04:04.248  3021  3042 D BluetoothAdapterProperties: Scan Mode:20
07-05 14:04:04.248  3021  3042 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-05 14:04:04.248   787   891 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-05 14:04:04.248   787   891 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-05 14:04:04.248   787   891 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-05 14:04:04.249   787   891 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:F4:F1:E1:5C:3B:E2
07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:85:54
07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:00:F4:6F:30:E0:6C
,07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:E0:DB:10:1F:C9:5E
,07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:08:EC:A9:50:76:27
07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:F8:95:C7:87:3C:51
,07-05 14:04:04.249  3021  3042 D BluetoothAdapterProperties: Adding bonded device:58:2A:F7:ED:96:BE
07-05 14:04:04.252  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
07-05 14:04:04.253  2923  2923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:04.255  3021  3021 I BluetoothHidServiceJni: classInitNative: succeeds
07-05 14:04:04.257  3021  3021 D HidService: getHidService(): service is NULL
,07-05 14:04:04.260  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
07-05 14:04:04.262  3021  3021 D HidService: getHidService(): service is NULL
,07-05 14:04:04.264   787   891 D WifiNative-HAL: Setting external_sim to 1
,07-05 14:04:04.265   787   891 D wifi    : setting dfs flag to true, 0x9b6f94c8
07-05 14:04:04.265   787   891 D WifiStateMachine: Setting OUI to DA-A1-19
07-05 14:04:04.265   787   891 D wifi    : setting scan oui 0x9b6f94c8
07-05 14:04:04.265   787   891 D WifiHAL : Sending mac address OUI
,07-05 14:04:04.267  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,07-05 14:04:04.268  3021  3021 D HidService: getHidService(): service is NULL
,07-05 14:04:04.270  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,07-05 14:04:04.271  3021  3021 D HidService: getHidService(): service is NULL
,07-05 14:04:04.273  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,07-05 14:04:04.274  3021  3021 D HidService: getHidService(): service is NULL
,07-05 14:04:04.276  3079  3079 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.gcs-1/lib/arm
07-05 14:04:04.277  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
07-05 14:04:04.278  3021  3021 D HidService: getHidService(): service is NULL
07-05 14:04:04.280  3021  3042 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
07-05 14:04:04.280   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:04.281  3021  3021 D HidService: getHidService(): service is NULL
07-05 14:04:04.282  3021  3042 D bt_hci  : do_postload posting postload work item
,07-05 14:04:04.282  3021  3048 I bt_hci  : event_postload
07-05 14:04:04.282  3021  3048 I bt_vendor: sco_config_cb
07-05 14:04:04.282  3021  3048 I bt_hci  : sco_config_callback postload finished.
07-05 14:04:04.283   787   787 D RttService: SCAN_AVAILABLE : 3
07-05 14:04:04.284   787   905 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-05 14:04:04.284  3021  3048 I bt_vendor: low_power_mode_cb
07-05 14:04:04.284   195   785 D CommandListener: Setting iface cfg
,07-05 14:04:04.284   195   785 D CommandListener: Trying to bring up p2p0
,07-05 14:04:04.285   787   890 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-05 14:04:04.285   787   891 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-05 14:04:04.289  3021  3042 D bt_bte_conf: Device ID record 1 : primary
07-05 14:04:04.289  3021  3042 D bt_bte_conf:   vendorId            = 000f
,07-05 14:04:04.289  3021  3042 D bt_bte_conf:   vendorIdSource      = 0001
07-05 14:04:04.289  3021  3042 D bt_bte_conf:   product             = 1200
07-05 14:04:04.289  3021  3042 D bt_bte_conf:   version             = 1436
07-05 14:04:04.289  3021  3042 D bt_bte_conf:   clientExecutableURL = 
07-05 14:04:04.289  3021  3042 D bt_bte_conf:   serviceDescription  = 
,07-05 14:04:04.289  3021  3042 D bt_bte_conf:   documentationURL    = 
07-05 14:04:04.289  3021  3042 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-05 14:04:04.289  3021  3035 D bt_stack_manager: event_start_up_stack finished
07-05 14:04:04.289  3021  3034 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-05 14:04:04.289  3021  3034 D BluetoothAdapterProperties: Setting state to 15
,07-05 14:04:04.289  3021  3034 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-05 14:04:04.290  3021  3034 I BluetoothAdapterState: Entering BleOnState
,07-05 14:04:04.296   787   891 E native  : do suspend false
,07-05 14:04:04.298   787  1329 I ActivityManager: Start proc 3110:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
07-05 14:04:04.299   787  1329 I ActivityManager: Killing 2277:com.google.android.calendar/u0a28 (adj 15): empty #17
07-05 14:04:04.301   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-05 14:04:04.301   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:04.646   787   890 D WifiNative-HAL: p2pGetDeviceAddress
07-05 14:04:04.647   787   890 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:ff:f0
,07-05 14:04:04.657  3021  3034 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-05 14:04:04.657  3021  3034 D BluetoothAdapterProperties: Setting state to 11
07-05 14:04:04.657  3021  3034 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-05 14:04:04.660  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
07-05 14:04:04.662  3021  3021 D HeadsetService: Received start request. Starting profile...
07-05 14:04:04.663  3021  3021 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-05 14:04:04.670  3021  3034 I BluetoothAdapterState: Entering PendingCommandState
07-05 14:04:04.670  3021  3021 D HeadsetStateMachine: make
07-05 14:04:04.685  3021  3021 D HeadsetStateMachine: max_hf_connections = 1
07-05 14:04:04.685  3021  3021 I bt_bluedroid: get_profile_interface handsfree
07-05 14:04:04.691  3021  3042 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-05 14:04:04.691  3021  3042 E bt_btif : btif_hf_upstreams_evt: Invalid index 45413
07-05 14:04:04.695  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
07-05 14:04:04.695   787   787 D BluetoothA2dp: Proxy object connected
07-05 14:04:04.696  3021  3021 D A2dpService: Received start request. Starting profile...
07-05 14:04:04.696  3021  3021 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-05 14:04:04.696  3021  3021 I bt_bluedroid: get_profile_interface avrcp
07-05 14:04:04.726  3021  3021 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-05 14:04:04.726  3021  3021 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-05 14:04:04.726  3021  3021 D A2dpStateMachine: make
07-05 14:04:04.728  3021  3021 I bt_bluedroid: get_profile_interface a2dp
07-05 14:04:04.728  3021  3042 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-05 14:04:04.770  3021  3132 D A2dpStateMachine: Enter Disconnected: -2
07-05 14:04:04.771  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
07-05 14:04:04.772  3067  3067 D BluetoothInputDevice: Proxy object connected
07-05 14:04:04.772   930   930 D BluetoothInputDevice: Proxy object connected
07-05 14:04:04.772   930   930 D HidProfile: Bluetooth service connected
,07-05 14:04:04.772  3067  3067 D HidProfile: Bluetooth service connected
07-05 14:04:04.772  3021  3021 D HidService: Received start request. Starting profile...
07-05 14:04:04.772  3021  3021 I bt_bluedroid: get_profile_interface hidhost
07-05 14:04:04.772  3021  3042 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38ca099
07-05 14:04:04.772  3021  3021 D HidService: setHidService(): set to: null
,07-05 14:04:04.772  3021  3042 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-05 14:04:04.773  3021  3021 I BluetoothHealthServiceJni: classInitNative: succeeds
07-05 14:04:04.774  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
07-05 14:04:04.774  3021  3021 D HealthService: Received start request. Starting profile...
,07-05 14:04:04.777  3021  3021 I bt_bluedroid: get_profile_interface health
,07-05 14:04:04.778  3021  3021 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-05 14:04:04.781  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
,07-05 14:04:04.782  3067  3067 D BluetoothPan: BluetoothPAN Proxy object connected
07-05 14:04:04.782  3067  3067 D PanProfile: Bluetooth service connected
,07-05 14:04:04.783  3021  3021 D PanService: Received start request. Starting profile...
07-05 14:04:04.783  3021  3021 D BluetoothPanServiceJni: initializeNative(L110): pan
07-05 14:04:04.783  3021  3021 I bt_bluedroid: get_profile_interface pan
,07-05 14:04:04.783  3021  3042 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-05 14:04:04.785   930   930 D BluetoothPan: BluetoothPAN Proxy object connected
,07-05 14:04:04.785   930   930 D PanProfile: Bluetooth service connected
,07-05 14:04:04.789  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67d32eb
,07-05 14:04:04.790   930   930 D BluetoothMap: Proxy object connected
,07-05 14:04:04.791   930   930 D MapProfile: Bluetooth service connected
,07-05 14:04:04.791   930   930 D BluetoothMap: getConnectedDevices()
,07-05 14:04:04.791  3021  3021 D BluetoothMapService: Received start request. Starting profile...
,07-05 14:04:04.791  3021  3021 D BluetoothMapService: start()
,07-05 14:04:04.791  3067  3067 D BluetoothMap: Proxy object connected
,07-05 14:04:04.791  3067  3067 D MapProfile: Bluetooth service connected
07-05 14:04:04.791  3067  3067 D BluetoothMap: getConnectedDevices()
07-05 14:04:04.792   930   930 D BluetoothMap: Bluetooth is Not enabled
07-05 14:04:04.793  3067  3067 D BluetoothMap: Bluetooth is Not enabled
,07-05 14:04:04.793  3021  3021 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-05 14:04:04.794  3021  3021 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-05 14:04:04.794  3021  3021 D BluetoothMapAppObserver: createReceiver()
07-05 14:04:04.795  3021  3021 D BluetoothMapAppObserver: initObservers()
,07-05 14:04:04.795  3021  3021 D BluetoothMapAppObserver: getEnabledAccountItems()
07-05 14:04:04.801  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:04.801  3021  3021 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:04.801  3021  3021 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:04.801  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
,07-05 14:04:04.802  3021  3130 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:04.803  3021  3021 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:04.803  3021  3034 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-05 14:04:04.803  3021  3034 D BluetoothAdapterProperties: ScanMode =  20
07-05 14:04:04.803  3021  3034 D BluetoothAdapterProperties: State =  11
07-05 14:04:04.804  3021  3034 D BluetoothAdapterProperties: Setting state to 12
07-05 14:04:04.804  3021  3034 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-05 14:04:04.804   787   811 D BluetoothA2dp: onBluetoothStateChange: up=true
07-05 14:04:04.804  3021  3034 I BluetoothAdapterState: Entering OnState
07-05 14:04:04.804  3021  3042 D BluetoothAdapterProperties: Scan Mode:21
07-05 14:04:04.805  3021  3042 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:04.805   930   943 D BluetoothPan: onBluetoothStateChange on: true
07-05 14:04:04.805  3067  3078 D BluetoothPan: onBluetoothStateChange on: true
07-05 14:04:04.806   787   811 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:04.807   930   941 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-05 14:04:04.807   787   811 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:04.808  3067  3077 D BluetoothMap: onBluetoothStateChange: up=true
,07-05 14:04:04.808  1304  1319 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:04.809  2923  2923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 14:04:04.810  3067  3078 D BluetoothPbap: onBluetoothStateChange: up=true
07-05 14:04:04.812   787   811 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:04.812  3067  3077 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-05 14:04:04.813   930  1404 D BluetoothPbap: onBluetoothStateChange: up=true
,07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:04.814  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-05 14:04:04.814   930   943 D BluetoothMap: onBluetoothStateChange: up=true
,07-05 14:04:04.816   787   787 I Telecom : BluetoothPhoneService: queryPhoneState
07-05 14:04:04.816  3021  3021 D BluetoothMapService: onReceive
07-05 14:04:04.816  3021  3021 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-05 14:04:04.816  3021  3021 D BluetoothMapService: STATE_ON
07-05 14:04:04.817  2923  2923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:04.819  3067  3067 D LocalBluetoothProfileManager: Adding local A2DP profile
07-05 14:04:04.820  3021  3021 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-05 14:04:04.821  3021  3021 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-05 14:04:04.822   930  1155 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-05 14:04:04.823  3067  3067 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-05 14:04:04.824  3021  3021 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:04.825   930   930 D BluetoothA2dp: Proxy object connected
,07-05 14:04:04.825   930  1155 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-05 14:04:04.826  3021  3021 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-05 14:04:04.828  3021  3021 D ObexServerSockets: Succeed to create listening sockets 
07-05 14:04:04.828  3021  3021 D ObexServerSockets0: startAccept()
07-05 14:04:04.828  3021  3021 D ObexServerSockets0: prepareForNewConnect()
07-05 14:04:04.829  3021  3021 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-05 14:04:04.830  3021  3021 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-05 14:04:04.831  3021  3153 D ObexServerSockets0: Accepting socket connection...
07-05 14:04:04.832  3021  3152 D ObexServerSockets0: Accepting socket connection...
07-05 14:04:04.838  3021  3021 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-05 14:04:04.838  3021  3021 D ObexServerSockets0: prepareForNewConnect()
07-05 14:04:04.840  3067  3067 D BluetoothMap: getConnectedDevices()
07-05 14:04:04.842  3067  3067 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
07-05 14:04:04.847  3067  3067 D MapProfile: getConnectionStatus: status is: 0
07-05 14:04:04.855   930  1155 D BluetoothMap: getConnectedDevices()
07-05 14:04:04.856   930  1155 D BluetoothMap: getConnectionState(58:2A:F7:ED:96:BE)
07-05 14:04:04.858   930  1155 D MapProfile: getConnectionStatus: status is: 0
07-05 14:04:04.867  3067  3067 D BluetoothMap: getConnectedDevices()
07-05 14:04:04.868  3067  3067 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-05 14:04:04.871  3067  3067 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:04.880  3067  3067 D BluetoothMap: getConnectedDevices()
,07-05 14:04:04.881  3067  3067 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
07-05 14:04:04.884  3067  3067 D MapProfile: getConnectionStatus: status is: 0
07-05 14:04:04.886  3110  3110 W InstanceID/Rpc: Found 10007
,07-05 14:04:04.890   930  1155 D BluetoothMap: getConnectedDevices()
,07-05 14:04:04.895  3067  3067 D BluetoothMap: getConnectedDevices()
,07-05 14:04:04.896  3067  3067 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-05 14:04:04.896   930  1155 D BluetoothMap: getConnectionState(E0:DB:10:1F:C9:5E)
,07-05 14:04:04.900  3067  3067 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:04.903   930  1155 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:04.907   787   811 D BluetoothHeadset: Proxy object connected
,07-05 14:04:04.908   787   811 D BluetoothHeadset: Proxy object connected
,07-05 14:04:04.909  1304  1449 D BluetoothHeadset: Proxy object connected
,07-05 14:04:04.912   787   811 D BluetoothHeadset: Proxy object connected
,07-05 14:04:04.914  3067  3067 D BluetoothMap: getConnectedDevices()
,07-05 14:04:04.916  3067  3067 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-05 14:04:04.916  3067  3067 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:04.925   787   798 I ActivityManager: Killing 1438:com.google.android.gm/u0a41 (adj 15): empty #17
,07-05 14:04:04.928   930   943 D BluetoothHeadset: Proxy object connected
,07-05 14:04:04.930  3067  3078 D BluetoothHeadset: Proxy object connected
,07-05 14:04:04.936   930   930 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:05.284  3067  3067 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.289  3067  3067 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-05 14:04:05.290  3067  3067 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:05.296  3067  3067 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.297  3067  3067 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
07-05 14:04:05.297  3067  3067 D MapProfile: getConnectionStatus: status is: 0
07-05 14:04:05.297  3067  3067 D BluetoothA2dp: Proxy object connected
,07-05 14:04:05.299  3067  3067 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:05.306   930  1155 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.307   930  1155 D BluetoothMap: getConnectionState(00:F4:6F:30:E0:6C)
,07-05 14:04:05.308   930  1155 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:05.310   787   892 D WifiService: New client listening to asynchronous messages
,07-05 14:04:05.360  1255  1255 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:05.363  1255  1255 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-05 14:04:05.370  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-05 14:04:05.401   930   930 D BluetoothPbap: Proxy object connected
,07-05 14:04:05.402   930   930 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:05.403  3021  3180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:05.405   930  1155 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.406   930  1155 D BluetoothMap: getConnectionState(F4:F1:E1:5C:3B:E2)
,07-05 14:04:05.407   930  1155 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:05.411  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,07-05 14:04:05.416  3067  3067 D BluetoothPbap: Proxy object connected
,07-05 14:04:05.416  3067  3067 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:05.422   930  1155 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.423   930  1155 D BluetoothMap: getConnectionState(F8:95:C7:87:3C:51)
,07-05 14:04:05.425  1255  1255 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:05.425   930  1155 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:05.430  1255  3185 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-05 14:04:05.433  1255  1255 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-05 14:04:05.448  3021  3191 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:05.454  3021  3191 I BtOppRfcommListener: Accept thread started.
,07-05 14:04:05.459  1255  3185 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-05 14:04:05.477   930  1155 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.478   930  1155 D BluetoothMap: getConnectionState(08:EC:A9:50:76:27)
,07-05 14:04:05.479   930  1155 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:05.487   930  1155 D BluetoothMap: getConnectedDevices()
,07-05 14:04:05.488   930  1155 D BluetoothMap: getConnectionState(F8:95:C7:87:85:54)
,07-05 14:04:05.489   930  1155 D MapProfile: getConnectionStatus: status is: 0
,07-05 14:04:05.880  3064  3064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-05 14:04:05.901   787   891 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-05 14:04:05.906   787   891 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-05 14:04:05.906   787   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:05.921   787   891 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-05 14:04:05.981   787   891 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-05 14:04:05.983  3064  3064 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-05 14:04:06.060  3064  3064 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-05 14:04:06.096  3064  3064 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-05 14:04:06.097  3064  3064 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-05 14:04:06.101   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:06.110   787   891 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 14:04:06.111   787   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-05 14:04:06.111   787   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-05 14:04:06.123   787   891 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:06.132   195   785 D CommandListener: Setting iface cfg
,07-05 14:04:06.139   787   891 D WifiStateMachine: Start Dhcp Watchdog 1
,07-05 14:04:06.151   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:06.151   787   893 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
07-05 14:04:06.152   787   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-05 14:04:06.196   787  3204 D DhcpClient: Receive thread started
,07-05 14:04:06.272   787   891 E native  : do suspend false
,07-05 14:04:06.281   787  3203 D DhcpClient: Broadcasting DHCPDISCOVER
,07-05 14:04:07.156  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:07.156  2923  2980 I jxcore-log: 
,07-05 14:04:07.557  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:07.557  2923  2980 I jxcore-log: 
,07-05 14:04:07.580  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:07.580  2923  2980 I jxcore-log: 
,07-05 14:04:07.585  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:07.585  2923  2980 I jxcore-log: 
,07-05 14:04:07.600  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:07.600  2923  2980 I jxcore-log: 
,07-05 14:04:07.604  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:07.604  2923  2980 I jxcore-log: 
,07-05 14:04:07.905   787  3204 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,07-05 14:04:07.906   787  3203 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-05 14:04:07.907   787  3203 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,07-05 14:04:07.915   787  3204 D DhcpClient: Received packet: 50:55:27:f0:ff:f0 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-05 14:04:07.915   787  3203 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-05 14:04:07.916   195   785 D CommandListener: Setting iface cfg
,07-05 14:04:07.919   787   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-05 14:04:07.924   787  3203 D DhcpClient: Scheduling renewal in 86399s
,07-05 14:04:07.928   787   891 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-05 14:04:07.929   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:04:07.930   787   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-05 14:04:07.931   787   893 D ConnectivityService: Adding iface wlan0 to network 100
07-05 14:04:07.943   787   891 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-05 14:04:08.006   787   893 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-05 14:04:08.006   787   893 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-05 14:04:08.009   787   893 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-05 14:04:08.010   787   893 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-05 14:04:08.011   787   893 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-05 14:04:08.021   787   893 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:08.024   787   893 D ConnectivityService: scheduleUnvalidatedPrompt 100
07-05 14:04:08.025   787   893 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-05 14:04:08.025   787   891 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-05 14:04:08.025   787   891 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-05 14:04:08.026   787   893 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:08.026   787   893 D ConnectivityService:    accepting network in place of null
07-05 14:04:08.026   787   893 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fff0/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-05 14:04:08.040   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109435, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:04:08.067   195   785 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:04:08.097   195   785 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:04:08.099   787   893 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,07-05 14:04:08.101   787   893 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-05 14:04:08.102   787   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-05 14:04:08.103   787   811 D Tethering: MasterInitialState.processMessage what=3
07-05 14:04:08.106   787  3201 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:400d:803::200e
07-05 14:04:08.109   787   893 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:08.113  2453  2453 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b2eb0b2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-05 14:04:08.116  2923  2923 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-05 14:04:08.117  2453  2453 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:08.123  2501  2501 E SetupWizard: tickleCheckinService called after completing user setup
,07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:08.135  2923  2923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:08.141  2923  2923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:04:08.147   787  1263 D AlarmManagerService: Setting time of day to sec=1467720248
07-05 14:04:08.575   787  1263 W AlarmManagerService: Unable to set rtc to 1467720248: Invalid argument
,07-05 14:04:08.592   787  3201 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jul 2016 12:04:08 GMT], X-Android-Received-Millis=[1467720248591], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467720248136]}
,07-05 14:04:08.592   787   893 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-05 14:04:08.593   787   893 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-05 14:04:08.593   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:08.594   787   893 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-05 14:04:08.617  2228  2296 I SQLiteDatabase: can't enable WAL for memory databases.
,07-05 14:04:08.619   787   802 I ActivityManager: Start proc 3237:com.google.android.apps.plus/u0a63 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,07-05 14:04:08.636  1657  3250 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-05 14:04:08.637   787  3251 D GpsLocationProvider: NTP server returned: 1467720248574 (Tue Jul 05 14:04:08 GMT+02:00 2016) reference: 109542 certainty: 3 system time offset: -62
,07-05 14:04:08.643   787  1250 V GpsLocationProvider: AGpsStatus is V2+: 1886680168
,07-05 14:04:08.643   787  1250 V GpsLocationProvider: AGPS IP is v4: 32617274
07-05 14:04:08.643   787  1250 V GpsLocationProvider: Converting IPv4 address(host_order) 32617274
07-05 14:04:08.643   787  1250 V GpsLocationProvider: Passing AGPS IP addr: size 4
07-05 14:04:08.643   787  1250 D GpsLocationProvider: Received Unknown AGPS status: 30767
,07-05 14:04:08.650  2228  2296 I SQLiteDatabase: can't enable WAL for memory databases.
,07-05 14:04:08.653  1229  1229 I LanguageModelDownload: onCreate()
,07-05 14:04:08.657  1229  3257 I LanguageModelDownload: Unable to format log message: 'onRunTask() : Tag = %slm_download_on_wifi_task' error:'java.util.MissingFormatArgumentException: Format specifier: s'
,07-05 14:04:08.657  1229  3257 I LanguageModelDownload: onRunTask() : WiFi ... Continue
07-05 14:04:08.657   787   802 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36933, reason: UserStart, SyncResult: databaseError: true stats []
,07-05 14:04:08.661  1229  1229 I DownloadManagerWrapper: onReceive() : Charging = true
,07-05 14:04:08.661   787   802 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141601, reason: UserStart
,07-05 14:04:08.662  1229  3257 I LanguageModelDatabase: reloading DB.
,07-05 14:04:08.706  1657  3247 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:04:08.723  1657  3262 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:04:08.724  1657  3262 I CheckinChimeraService: Checking schedule, now: 1467720248724 next: 1467398863200
,07-05 14:04:08.725  1657  3262 I CheckinChimeraService: active receiver: enabled
,07-05 14:04:08.726  1657  3262 I CheckinChimeraService: Preparing to send checkin request
,07-05 14:04:08.726  1657  3262 I EventLogChimeraService: Accumulating logs since 1467719271522
,07-05 14:04:08.742  1229  3257 I LanguageModelDatabase: populateEntry() : pt_BR = BUNDLED
,07-05 14:04:08.749  1657  3264 I iu.SyncManager: SYNC; picasa accounts
,07-05 14:04:08.762  1657  1657 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-05 14:04:08.764  1657  1657 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-05 14:04:08.781  1657  3264 I iu.UploadsManager: num queued entries: 0
,07-05 14:04:08.782  1657  3264 I iu.UploadsManager: num updated entries: 0
07-05 14:04:08.782  1657  3264 I iu.SyncManager: NEXT; no task
,07-05 14:04:08.817  1229  1229 I PeriodicTasksService: onCreate()
,07-05 14:04:08.819  1229  3267 I PeriodicTasksService: onRunTask()
,07-05 14:04:08.821  1229  3267 I PeriodicTasksService: onRunTask() : Done in 3 ms
,07-05 14:04:08.825  1229  1229 I PeriodicTasksService: onDestroy()
,07-05 14:04:08.830  1229  3257 I LanguageModelDatabase: populateEntry() : ru_RU = STAGED
,07-05 14:04:08.869  1229  3257 I LanguageModelDatabase: populateEntry() : ru_RU = BUNDLED
,07-05 14:04:08.883  1657  3262 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:04:08.889  1657  3262 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 14:04:08.984  1229  3257 I LanguageModelDatabase: populateEntry() : fr_FR = STAGED
,07-05 14:04:08.990  1657  3262 V CheckinRequestBuilder: No Subscriptions found on the device
,07-05 14:04:09.022  1229  3257 I LanguageModelDatabase: populateEntry() : fr_FR = BUNDLED
,07-05 14:04:09.062  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:09.062  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:09.088  1229  3257 I LanguageModelDatabase: populateEntry() : en_US = STAGED
,07-05 14:04:09.128  1229  3257 I LanguageModelDatabase: populateEntry() : en_US = BUNDLED
,07-05 14:04:09.174  1229  3257 I LanguageModelDatabase: populateEntry() : es = STAGED
,07-05 14:04:09.200  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:09.229  1229  3257 I LanguageModelDatabase: populateEntry() : es = BUNDLED
,07-05 14:04:09.292  1229  3257 I LanguageModelDatabase: populateEntry() : it_IT = STAGED
,07-05 14:04:09.310  1229  3257 I LanguageModelDatabase: populateEntry() : it_IT = BUNDLED
,07-05 14:04:09.339  1229  3257 I LanguageModelDatabase: populateEntry() : de_DE = STAGED
,07-05 14:04:09.367  1229  3257 I LanguageModelDatabase: populateEntry() : de_DE = BUNDLED
,07-05 14:04:09.405  1657  3285 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=210:priority=5:group=main]
,07-05 14:04:09.436  1255  3289 I CheckinUtil: Classify the device as Phone.
,07-05 14:04:09.493  2810  3294 W SyncManagerImpl: Initiating sync for AccountId 3a3529a (com.google.android.apps.docs)
,07-05 14:04:09.505   787   797 D WifiService: acquireWifiLockLocked: WifiLock{SyncManagerImpl type=1 binder=android.os.BinderProxy@f0fea91}
,07-05 14:04:09.543  2810  3294 W SyncManagerImpl: Started sync for AccountId 3a3529a
,07-05 14:04:09.555  2810  3294 W Flag    : Duration spec must be at least 2 characters long: 
,07-05 14:04:09.582   787   893 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:09.617   787   797 I ActivityManager: Start proc 3298:com.google.android.gms.unstable/u0a7 for service com.google.android.gms/.droidguard.DroidGuardService
,07-05 14:04:09.665  3298  3298 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:04:09.665  3298  3298 I MultiDex: install
07-05 14:04:09.665  3298  3298 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:09.696  3298  3298 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:04:09.697  1229  3257 I LanguageModelUpdater: Downloading metadata: https://www.gstatic.com/android/keyboard/dictionarypack/Accordion/metadata.json
,07-05 14:04:09.706  1255  1592 W Herrevad: Invalid mccmnc 
,07-05 14:04:09.707  1255  1592 W Herrevad: Invalid mccmnc 
,07-05 14:04:09.708  3298  3298 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,07-05 14:04:09.708  3298  3298 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:04:09.712  3298  3298 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:04:09.739  3298  3298 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:09.752  3298  3298 D ChimeraCfgMgr: Reading stored module config
,07-05 14:04:09.784   787   954 I ActivityManager: Start proc 3329:com.google.android.apps.photos/u0a83 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-05 14:04:09.821  3298  3326 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:04:09.856   199   899 D WVCdm   : Instantiating CDM.
,07-05 14:04:09.858   199   830 I WVCdm   : CdmEngine::OpenSession
07-05 14:04:09.859   199   830 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:04:09.881   199   830 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:04:09.888   199   830 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-05 14:04:09.888   199   830 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:04:09.888   199   830 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:09.888   199   830 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:09.927   199   830 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:04:09.927   199   830 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-05 14:04:09.927   199   830 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3466000
,07-05 14:04:09.927   199   830 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3466000
,07-05 14:04:09.958   199   830 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:04:09.958   199   830 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:09.965   199   830 D DrmWidevineDash: hlos api version =  10
07-05 14:04:09.965   199   830 D DrmWidevineDash: tz api version =  10
07-05 14:04:09.965   199   830 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:09.965   199   830 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:04:09.985   199   830 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:04:09.985   199   830 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:09.985   199   830 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb377f134
,07-05 14:04:09.993   199   830 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 14:04:09.994   199   830 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:04:09.994   199   830 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604bda8, dataLength=8
,07-05 14:04:09.999   199   830 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:04:10.006   199   830 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb6007c00, wrapped_rsa_key_length=1280
,07-05 14:04:10.013   199   830 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 14:04:10.013   199   830 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:04:10.014   199   899 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:04:10.014   199   899 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:10.014   199   899 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:10.014   199   899 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb221d160, idLength=0xb367cf2c
,07-05 14:04:10.034   199   899 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:04:10.034   199   899 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:04:10.044   199   899 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:04:10.044   199   899 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:04:10.044   199   899 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:04:10.044   199   899 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:04:10.051   199   899 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-05 14:04:10.051   199   899 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:10.059   199   899 D DrmWidevineDash: hlos api version =  10
,07-05 14:04:10.059   199   899 D DrmWidevineDash: tz api version =  10
07-05 14:04:10.059   199   899 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:10.059   199   899 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:04:10.067   199   899 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-05 14:04:10.067   199   899 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:04:10.067   199   899 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:04:10.077  1229  3257 I LanguageModelUpdater: Successfully downloaded metadata: https://www.gstatic.com/android/keyboard/dictionarypack/Accordion/metadata.json
,07-05 14:04:10.078  1229  3257 I LanguageModelUpdater: Staged metadata to: /data/user/0/com.google.android.inputmethod.latin/files/staging/metadata.json
07-05 14:04:10.078   199   899 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 14:04:10.078   199   899 D WVCdm   : PrepareKeyRequest: nonce=2210003137
07-05 14:04:10.078   199   899 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2224000
07-05 14:04:10.078   199   899 D DrmWidevineDash: message_length=1639, signature=0xb352f000, signature_length=3009925124
,07-05 14:04:10.079  1229  3257 I LanguageModelDatabase: reloading DB.
,07-05 14:04:10.094  1229  3257 I LanguageModelDatabase: populateEntry() : pt_BR = BUNDLED
,07-05 14:04:10.101  1229  3257 I LanguageModelDatabase: populateEntry() : ru_RU = STAGED
,07-05 14:04:10.107  1229  3257 I LanguageModelDatabase: populateEntry() : ru_RU = BUNDLED
,07-05 14:04:10.138  1229  3257 I LanguageModelDatabase: populateEntry() : fr_FR = STAGED
,07-05 14:04:10.139  1229  3257 I LanguageModelDatabase: populateEntry() : fr_FR = BUNDLED
,07-05 14:04:10.155   199   899 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:04:10.156   199   199 I WVCdm   : CdmEngine::CloseSession
07-05 14:04:10.156   199   199 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:04:10.170  1229  3257 I LanguageModelDatabase: populateEntry() : en_US = STAGED
07-05 14:04:10.176  1229  3257 I LanguageModelDatabase: populateEntry() : en_US = BUNDLED
,07-05 14:04:10.179   199   199 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 14:04:10.179   199   199 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:04:10.185   199   199 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:04:10.185   199   199 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:04:10.185   199   199 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:04:10.186   199   199 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:04:10.186   199   199 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:04:10.189  1229  3257 I LanguageModelDatabase: populateEntry() : es = STAGED
07-05 14:04:10.190  1229  3257 I LanguageModelDatabase: populateEntry() : es = BUNDLED
,07-05 14:04:10.197  1229  3257 I LanguageModelDatabase: populateEntry() : it_IT = STAGED
,07-05 14:04:10.199  1229  3257 I LanguageModelDatabase: populateEntry() : it_IT = BUNDLED
,07-05 14:04:10.201  1229  3257 I LanguageModelDatabase: populateEntry() : de_DE = STAGED
,07-05 14:04:10.201  1229  3257 I LanguageModelDatabase: populateEntry() : de_DE = BUNDLED
,07-05 14:04:10.213  1255  1592 V NQFileLogger: [86] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:04:10.216  1229  3257 I LanguageModelDatabase: findBestLanguageModelForKey() : Best Usable: LanguageModelDescriptor : Type = MAIN : Locale = en_US : Version = 20160322 : Status = BUNDLED : Path = /data/app/com.google.android.inputmethod.latin-2/base.apk : Length = 4438520 : Offset = 2562448
,07-05 14:04:10.217  1229  3257 I LanguageModelUpdater: Subtype: en_US. Usable LM already exists for [locale, version]: [en_US, 20160322]
,07-05 14:04:10.229  1229  3257 I LanguageModelDownload: onRunTask() : Done in 1561 ms
,07-05 14:04:10.233  1229  1229 I LanguageModelDownload: onDestroy()
,07-05 14:04:10.246  1255  1592 V ProcessReports: [86] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
07-05 14:04:10.297  3298  3309 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,07-05 14:04:10.301  3298  3309 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
07-05 14:04:10.301  3298  3309 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:04:10.307  3298  3309 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000003/n/armeabi
,07-05 14:04:10.308  3298  3309 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-05 14:04:10.310  3298  3309 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:04:10.312  3298  3309 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:04:10.328  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:10.331   787   798 D ConnectivityService: listenForNetwork for Listen from uid/pid:10063/3237 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-05 14:04:10.363  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:10.363  2923  2980 I jxcore-log: 
07-05 14:04:10.371  3298  3309 D GoogleCertificatesImpl: Fetched 154 Google release certificates
07-05 14:04:10.374  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:10.374  2923  2980 I jxcore-log: 
,07-05 14:04:10.383  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:10.383  2923  2980 I jxcore-log: 
,07-05 14:04:10.408  1255  1255 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:10.435  1255  3361 I PhenotypeConfigurator: Scheduling Phenotype every 3600 seconds, with flex of 1800 seconds
,07-05 14:04:10.471  3362  3362 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/the.apk --oat-file=/data/user/0/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/opt/the.dex
,07-05 14:04:10.503  3362  3362 I dex2oat : dex2oat took 32.723ms (threads: 4) arena alloc=41KB java alloc=21KB native alloc=1048KB free=999KB
,07-05 14:04:10.530  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:10.572  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:10.572  2923  2980 I jxcore-log: 
,07-05 14:04:10.666  1657  1657 I GCM     : Message from null null
,07-05 14:04:10.666  1657  1657 E GCM     : Dropping message from null
,07-05 14:04:10.672  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:10.672  2923  2980 I jxcore-log: 
07-05 14:04:10.673  1657  1657 I GCM     : Message from 745476177629 null
,07-05 14:04:10.680  1657  1657 I GCM     : Message from 745476177629 null
,07-05 14:04:10.702  1657  3383 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,07-05 14:04:10.717  3384  3384 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-05 14:04:10.737  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:10.737  2923  2980 I jxcore-log: 
,07-05 14:04:10.744  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:10.744  2923  2980 I jxcore-log: 
,07-05 14:04:10.775  3384  3384 I dex2oat : dex2oat took 58.708ms (threads: 4) arena alloc=57KB java alloc=55KB native alloc=1407KB free=1664KB
,07-05 14:04:10.780  3298  3309 W System  : ClassLoader referenced unknown path: 
,07-05 14:04:10.789  3298  3309 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:04:10.858  1255  3393 W WakefulBroadcastReceiver: No active wake lock id #1
,07-05 14:04:10.862   199   199 I WVCdm   : CdmEngine::OpenSession
,07-05 14:04:10.862   199   199 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
07-05 14:04:10.863   199   199 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-05 14:04:10.865   199   199 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-05 14:04:10.865   199   199 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:04:10.865   199   199 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:10.865   199   199 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:10.871  1255  3393 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
,07-05 14:04:10.881   199   199 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:04:10.882   199   199 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:04:10.882   199   199 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3466000
07-05 14:04:10.882   199   199 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3466000
,07-05 14:04:10.896   199   199 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:04:10.896   199   199 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:10.902   199   199 D DrmWidevineDash: hlos api version =  10
,07-05 14:04:10.902   199   199 D DrmWidevineDash: tz api version =  10
07-05 14:04:10.902   199   199 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:10.902   199   199 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:04:10.916   199   199 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:04:10.916   199   199 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:10.916   199   199 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbee01214
,07-05 14:04:10.920   199   199 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-05 14:04:10.920   199   199 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:04:10.920   199   199 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604bda8, dataLength=8
,07-05 14:04:10.927   199   199 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:04:10.928   199   199 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb607f400, wrapped_rsa_key_length=1280
,07-05 14:04:10.935   199   199 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-05 14:04:10.935   199   199 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-05 14:04:10.937   199   199 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:04:10.937   199   199 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:10.937   199   199 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:10.937   199   199 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb38bdf40, idLength=0xbee0100c
,07-05 14:04:10.947  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:10.948  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:10.948   199   199 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:04:10.948   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:04:10.954   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:04:10.954   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:04:10.954   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:04:10.954   199   199 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:04:10.960   199   199 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-05 14:04:10.960   199   199 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:10.965   199   199 D DrmWidevineDash: hlos api version =  10
,07-05 14:04:10.965   199   199 D DrmWidevineDash: tz api version =  10
07-05 14:04:10.965   199   199 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:10.965   199   199 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:04:10.970   199   199 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-05 14:04:10.970   199   199 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:04:10.970   199   199 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:04:10.975   199   199 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 14:04:10.975   199   199 D WVCdm   : PrepareKeyRequest: nonce=3569912289
,07-05 14:04:10.975   199   199 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2224700
07-05 14:04:10.975   199   199 D DrmWidevineDash: message_length=1670, signature=0xb60765c0, signature_length=3202355428
,07-05 14:04:10.989  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:10.989  2923  2980 I jxcore-log: 
,07-05 14:04:11.000  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:11.012  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:11.012  2923  2980 I jxcore-log: 
,07-05 14:04:11.017  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:11.017  2923  2980 I jxcore-log: 
,07-05 14:04:11.022  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:11.022  2923  2980 I jxcore-log: 
,07-05 14:04:11.038  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:11.038  2923  2980 I jxcore-log: 
,07-05 14:04:11.046   199   199 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:04:11.046   199   830 I WVCdm   : CdmEngine::CloseSession
07-05 14:04:11.046   199   830 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:04:11.051   199   830 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-05 14:04:11.051   199   830 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:04:11.057   199   830 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:04:11.057   199   830 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:04:11.057   199   830 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:04:11.057   199   830 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:04:11.057   199   830 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:04:11.060  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:11.060  2923  2980 I jxcore-log: 
,07-05 14:04:11.065  3298  3309 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:04:11.114  3298  3309 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:04:11.144  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:11.145  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:11.154  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:11.154  2923  2980 I jxcore-log: 
,07-05 14:04:11.159  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:11.159  2923  2980 I jxcore-log: 
,07-05 14:04:11.187  2923  2980 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:11.187  2923  2980 I jxcore-log: 
,07-05 14:04:11.198  2923  2980 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-05 14:04:11.200  2923  2980 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 14:04:11.200  2923  2980 I jxcore-log: 
,07-05 14:04:11.214  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:11.214  3237  3334 I art     : Note: end time exceeds epoch: 
,07-05 14:04:11.251  1255  3393 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:11.251  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-05 14:04:11.251  2923  2980 I jxcore-log: 
07-05 14:04:11.252  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-05 14:04:11.252  2923  2980 I jxcore-log: 
07-05 14:04:11.252  1255  3393 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
07-05 14:04:11.253  2923  2980 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:11.253  2923  2980 I jxcore-log: 
,07-05 14:04:11.262  1255  3393 V BaseAppContext: GmsRequestQueue started.
,07-05 14:04:11.313  1657  3262 I CheckinUtil: Classify the device as Phone.
,07-05 14:04:11.398  2810  3294 W jwd     : Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:11.398  2810  3294 W jwd     : Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:11.413  2810  3294 W jwd     : Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:11.441  1255  3361 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-05 14:04:11.580  1657  3262 I CheckinTask: Sending checkin request (10245 bytes)
,07-05 14:04:11.588   787   972 I ActivityManager: Killing 2453:com.google.android.music:main/u0a58 (adj 15): empty #17
,07-05 14:04:11.652   787  1295 I ActivityManager: Start proc 3422:com.google.android.youtube/u0a71 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:04:11.706  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:11.707  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:11.773  3422  3434 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:04:11.801  3422  3434 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:04:11.802  3422  3434 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:04:11.812  3422  3434 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:04:11.836  3422  3434 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:11.910  1255  3393 W WakefulBroadcastReceiver: No active wake lock id #2
,07-05 14:04:11.920  1657  3262 I CheckinResponseProcessor: From server: 1 gservices updates and 1 deletes
,07-05 14:04:11.957  3422  3454 D ChimeraCfgMgr: Reading stored module config
,07-05 14:04:12.000  3422  3454 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000003/n/armeabi
,07-05 14:04:12.001  3422  3454 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:04:12.002  3422  3454 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:04:12.008  3422  3454 D DynamitePackage: Instantiated singleton DynamitePackage.
,07-05 14:04:12.008  3422  3454 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,07-05 14:04:12.062  1392  1542 I GservicesProvider: main difference update completed
,07-05 14:04:12.068  1657  3262 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:04:12.072  1657  3262 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 14:04:12.083  2344  3469 I Babel_SMS: ApnsOta: OTA version -1
,07-05 14:04:12.096   787   972 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:04:12.098  2344  2344 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-05 14:04:12.098  2344  2344 W Babel   : BAM#gBA: invalid account id: -1
,07-05 14:04:12.098  2344  2344 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:04:12.099  2344  2344 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-05 14:04:12.109  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:12.110  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:12.113   787   798 I ActivityManager: Start proc 3482:com.google.android.configupdater/u0a2 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,07-05 14:04:12.148  3482  3482 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm
,07-05 14:04:12.172  3422  3422 W InstanceID/Rpc: Found 10007
,07-05 14:04:12.202  3482  3482 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,07-05 14:04:12.211  3482  3482 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,07-05 14:04:12.224  3482  3482 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,07-05 14:04:12.236  3482  3482 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,07-05 14:04:12.246  3482  3482 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,07-05 14:04:12.252  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:12.259  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:12.260  1657  3523 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 14:04:12.260  1657  3523 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 14:04:12.261  1657  3523 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
,07-05 14:04:12.264  1657  3523 D ChimeraCfgMgr: Beginning module configuration check
,07-05 14:04:12.271  1657  3523 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 14:04:12.286  3504  3504 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/1459442732877.jar --oat-file=/data/user/0/com.google.android.youtube/cache/1459442732877.dex
,07-05 14:04:12.300   787   797 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=3422, uid=10071 that is not exported from uid 10058
,07-05 14:04:12.308  1255  3453 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_identity_app_security_threat
,07-05 14:04:12.317  1255  3453 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_google_g_icon
,07-05 14:04:12.358  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:12.358  3237  3421 I art     : Note: end time exceeds epoch: 
,07-05 14:04:12.371  1657  1657 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,07-05 14:04:12.403  3504  3504 I dex2oat : dex2oat took 117.489ms (threads: 4) arena alloc=278KB java alloc=31KB native alloc=1705KB free=1622KB
,07-05 14:04:12.433   930   930 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,07-05 14:04:12.479   930   930 W PathParser: Points are too far apart 4.030360828967057
,07-05 14:04:12.479   930   930 W PathParser: Points are too far apart 4.030360538880159
07-05 14:04:12.481   930   930 W PathParser: Points are too far apart 4.030360828967057
07-05 14:04:12.481   930   930 W PathParser: Points are too far apart 4.030360538880159
,07-05 14:04:12.607  1255  3555 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:04:12.616  1657  3262 V CheckinRequestBuilder: No Subscriptions found on the device
,07-05 14:04:12.672  1657  3262 I CheckinUtil: Classify the device as Phone.
,07-05 14:04:12.729  1255  3453 W WakefulBroadcastReceiver: No active wake lock id #3
,07-05 14:04:12.856   787   797 I ActivityManager: Killing 2544:com.google.android.talk:matchstick/u0a51 (adj 15): empty #17
,07-05 14:04:12.886  2810  3294 W SyncManagerImpl: Sync for AccountId 3a3529a took 1907 ms
,07-05 14:04:12.897  1657  3563 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:04:12.905  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:12.917   787  1295 D WifiService: releaseWifiLockLocked: WifiLock{SyncManagerImpl type=1 binder=android.os.BinderProxy@f0fea91}
,07-05 14:04:12.923  2810  3294 W SyncManagerImpl: Sync completed for AccountId 3a3529a (com.google.android.apps.docs)
,07-05 14:04:12.960  1657  3262 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-05 14:04:12.977  1657  3262 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:04:12.988  1657  3262 I CheckinChimeraService: Checking schedule, now: 1467720252987 next: 1467762741961
,07-05 14:04:12.988  1657  3262 I CheckinChimeraService: active receiver: disabled
,07-05 14:04:13.002  1657  3568 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:13.003   787  1295 I ActivityManager: Killing 1907:com.android.providers.calendar/u0a1 (adj 15): empty #17
,07-05 14:04:13.032  1657  3571 V CheckinChimeraService: No Subscriptions found on the device
,07-05 14:04:13.041  1657  3571 I CheckinChimeraService: Checking schedule, now: 1467720253041 next: 1467762741961
,07-05 14:04:13.041  1657  3571 I CheckinChimeraService: active receiver: disabled
,07-05 14:04:13.054  1657  1657 D CheckinChimeraService: Recording last checkin time for package unspecified as 1467720253054
,07-05 14:04:13.057  1657  1657 D GoogleSignatureVerifier: Package manager can't find package com.google.android.apps.work.core, defaulting to false
,07-05 14:04:13.072  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:13.110  1657  3563 I PeopleSync: Setting subscription: result=true [5005f081]
,07-05 14:04:13.111  1657  3563 I PeopleSync: ***Sync canceled***, duration: -1 [5005f081]
,07-05 14:04:13.142  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_apps_corpus_label
07-05 14:04:13.142  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_apps_corpus_description
,07-05 14:04:13.142  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_device_source_apps_normal
07-05 14:04:13.143  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_contacts_corpus_label
07-05 14:04:13.143  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_contacts_corpus_description
07-05 14:04:13.143  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_device_source_contacts
,07-05 14:04:13.149   787   802 D SyncManager: handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 113556, mTimeoutStartTime 113556, mHistoryRowId 9, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 36927, reason: Periodic
,07-05 14:04:13.213  1657  3574 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:04:13.346  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:13.360  1657  1657 I DynamiteModule: Considering local module com.google.android.gms.flags:0 and remote module com.google.android.gms.flags:1
,07-05 14:04:13.360  1657  1657 I DynamiteModule: Selected remote version of com.google.android.gms.flags, version >= 1
,07-05 14:04:13.400  1255  1255 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=d73aad6e-eddd-489f-8721-e98f237ea335
,07-05 14:04:13.428  1657  3574 I PeopleSync: Setting subscription: result=true [5005f081]
,07-05 14:04:13.429  1657  3574 I PeopleSync: Starting sync, feed=null [5005f081]
,07-05 14:04:13.452  1229  1229 I LanguageModelDownload: onCreate()
,07-05 14:04:13.454  1229  3580 I LanguageModelDownload: Unable to format log message: 'onRunTask() : Tag = %slm_download_metered_task' error:'java.util.MissingFormatArgumentException: Format specifier: s'
,07-05 14:04:13.455  1229  3580 I LanguageModelDownload: onRunTask() : Metered ... Too Soon ... Done
,07-05 14:04:13.459  1229  1229 I LanguageModelDownload: onDestroy()
,07-05 14:04:13.514  1657  2320 D MdnsClient: #acquireLock. Multicast lock not held. Acquiring
,07-05 14:04:13.521  1657  3574 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,07-05 14:04:13.523  1255  1255 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,07-05 14:04:13.529   787   797 W ActivityManager: Unable to start service Intent { act=com.google.android.gms.measurement.REFRESH_ENABLED_STATE pkg=com.google.android.gms } U=0: not found
,07-05 14:04:13.584  1657  1657 D OcrModelBroadcastRcvr: com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:04:13.584  1657  1657 D OcrModelBroadcastRcvr: Updating OCR activity and model state
,07-05 14:04:13.594  1255  1602 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:13.599  1657  1657 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
,07-05 14:04:13.599  1657  1657 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
,07-05 14:04:13.603  1255  1592 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 14:04:13.610  1657  1657 D CmaSystemUpdateService: onCreate
07-05 14:04:13.610  1657  1657 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
,07-05 14:04:13.611  1657  3587 V PrereqChecker: Build version: 23
,07-05 14:04:13.611  1657  3587 V PrereqChecker: Model: Nexus 5
,07-05 14:04:13.611  1657  3587 V PrereqChecker: CPU_ABI: armeabi-v7a
07-05 14:04:13.612  1657  3587 V PrereqChecker: CPU_ABI2: armeabi
,07-05 14:04:13.615  1255  1545 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:04:13.616  1657  1657 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
,07-05 14:04:13.618  1657  3587 V PrereqChecker: Camera #0 is a rear-facing camera.
,07-05 14:04:13.619  1657  3587 D CreditCardPrerequisiteChecker: All prerequisites OK.
,07-05 14:04:13.619  1657  3587 I OcrModelUpdtStIntSvc: Updating ocr activity enabled=false (gservicesFlag=false, lowRamDevice=false, prereqCheck=true)
,07-05 14:04:13.641  1657  3588 I SystemUpdateTask: cancelUpdate (empty URL)
,07-05 14:04:13.641  1657  3588 I CmaSystemUpdateService: active receiver: disabled
,07-05 14:04:13.706  1255  1528 W System.err: java.lang.Exception: Error converting session
,07-05 14:04:13.709  1657  1657 D CmaSystemUpdateService: onDestroy
,07-05 14:04:13.712  1255  1528 W System.err: 	at slt.log(SourceFile:302)
,07-05 14:04:13.713  1255  1528 W System.err: 	at slt.toSession(SourceFile:269)
,07-05 14:04:13.713  1255  1528 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-05 14:04:13.713  1255  1528 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-05 14:04:13.713  1255  1528 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
,07-05 14:04:13.713  1255  1528 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:310)
07-05 14:04:13.713  1255  1528 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.verifyHostname(SourceFile:217)
07-05 14:04:13.713  1255  1528 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:507)
07-05 14:04:13.713  1255  1528 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:04:13.713  1255  1528 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
,07-05 14:04:13.713  1255  1528 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
,07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
,07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:04:13.715  1255  1528 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-05 14:04:13.716  1255  1528 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:943)
07-05 14:04:13.716  1255  1528 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:761)
07-05 14:04:13.716  1255  1528 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:660)
07-05 14:04:13.716  1255  1528 W System.err: 	at fpn.a(SourceFile:87)
07-05 14:04:13.716  1255  1528 W System.err: 	at fpn.a(SourceFile:135)
,07-05 14:04:13.716  1255  1528 W System.err: 	at eld.a(SourceFile:23157)
07-05 14:04:13.717  1255  1528 W System.err: 	at ejq.a(SourceFile:397)
07-05 14:04:13.717  1255  1528 W System.err: 	at ejp.a(SourceFile:31369)
07-05 14:04:13.717  1255  1528 W System.err: 	at ejp.a(SourceFile:313)
,07-05 14:04:13.717  1255  1528 W System.err: 	at fla.a(SourceFile:1201)
,07-05 14:04:13.717  1255  1528 W System.err: 	at fkz.a(SourceFile:530)
07-05 14:04:13.717  1255  1528 W System.err: 	at fkz.a(SourceFile:196)
,07-05 14:04:13.718  1255  1528 W System.err: 	at egp.a(SourceFile:284)
07-05 14:04:13.718  1255  1528 W System.err: 	at egp.a(SourceFile:204)
07-05 14:04:13.718  1255  1528 W System.err: 	at bdm.onTransact(SourceFile:137)
07-05 14:04:13.719  1255  1528 W System.err: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:04:13.719  1255  1528 W System.err: Caused by: java.io.IOException: Invalid session data
,07-05 14:04:13.719  1255  1528 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
07-05 14:04:13.719  1255  1528 W System.err: 	at slt.toSession(SourceFile:267)
,07-05 14:04:13.719  1255  1528 W System.err: 	... 34 more
,07-05 14:04:13.750  3079  3079 W InstanceID/Rpc: Found 10007
,07-05 14:04:13.769  1255  1545 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 14:04:13.772  1255  1545 I GCoreUlr: Unbound from all location providers
,07-05 14:04:13.797  1364  1477 I GservicesUpdateTask: Updating Gservices keys
,07-05 14:04:13.816  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:13.822  1657  3593 V AccountUtils: 0 accounts found with uca feature
,07-05 14:04:13.823  1657  3593 I GamesSyncAdapter: Starting sync for 3a3529a
,07-05 14:04:13.993   787   797 I ActivityManager: Start proc 3606:com.google.android.play.games.ui/u0a62 for service com.google.android.play.games/com.google.android.gms.games.service.PlayGamesBridgeService
,07-05 14:04:13.998  1255  1255 I GCoreUlr: DispatchingService.onDestroy()
,07-05 14:04:13.999  1255  1255 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-05 14:04:14.001  1255  1255 I GCoreUlr: Unbound from all location providers
,07-05 14:04:14.012  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:14.015  1255  1602 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:14.017  1255  1602 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:14.035  1255  1592 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,07-05 14:04:14.040  1255  1255 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,07-05 14:04:14.128  1255  1268 E System  : Uncaught exception thrown by finalizer
,07-05 14:04:14.128  1255  1268 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:04:14.128  1255  1268 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:04:14.128  1255  1268 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-05 14:04:14.128  1255  1268 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:04:14.128  1255  1268 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:04:14.128  1255  1268 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:04:14.133  2501  2501 I SetupWizard: Connected to Gservices successfully
,07-05 14:04:14.175  1657  3593 I GamesSyncAdapter: Sync duration for 3a3529a: 352
,07-05 14:04:14.221   787  1320 I ActivityManager: Killing 2782:com.android.musicfx/u0a13 (adj 15): empty #17
,07-05 14:04:14.264  1657  3593 E PopupManager: No content view usable to display popups. Popups will not be displayed in response to this client's calls. Use setViewForPopups() to set your content view.
,07-05 14:04:14.282  1657  3636 W GamesServiceBroker: Client connected with SDK 8487000, Services 9083438, and Games 37230038
,07-05 14:04:14.341  1255  2177 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 14:04:14.466  1255  1255 D WearableService: callingUid 10007, callindPid: 1255
,07-05 14:04:14.487  1255  3642 I CheckinUtil: Classify the device as Phone.
,07-05 14:04:14.545  1657  1664 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@78ad547)
,07-05 14:04:14.770  1657  1657 D PlayCommon: [1] DfeRequest.deliverResponse: Not delivering second response for request=[[ ] https://android.clients.google.com/fdfe/api/experiments 0xe8d195d1 NORMAL 1]
,07-05 14:04:14.773   787  1195 I ActivityManager: Killing 2861:com.quickoffice.android/u0a65 (adj 15): empty #17
,07-05 14:04:14.870   787   802 I ActivityManager: Start proc 3651:com.google.android.gm/u0a41 for service com.google.android.gm/.provider.MailSyncAdapterService
,07-05 14:04:14.926  3651  3651 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.gm-1/lib/arm
,07-05 14:04:14.957  3651  3651 W EasBundling: in EasBundling.init, isBundlingEnabled=true
,07-05 14:04:14.972  3651  3665 I Gmail   : getAccountsCursor
,07-05 14:04:14.973  3651  3666 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-05 14:04:15.000   787  1332 I ActivityManager: Start proc 3668:com.google.android.music:main/u0a58 for service com.google.android.music/.sync.google.MusicGcmTaskService
,07-05 14:04:15.059  3651  3651 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:15.073  3668  3668 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.music-1/lib/arm
,07-05 14:04:15.078  3668  3668 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:04:15.078  3668  3668 I MultiDex: install
07-05 14:04:15.078  3668  3668 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:15.098  3668  3668 I BaseStore: ConfigStore database version: 1
,07-05 14:04:15.123  3668  3668 I BaseStore: Store database version: 134
,07-05 14:04:15.129  3651  3690 I Gmail   : No Email application installed
,07-05 14:04:15.129  3651  3690 I EmailMigration: No data to migrate
,07-05 14:04:15.130  3651  3666 I Gmail   : Initiated Service map for: [gPop3, gLegacyImap, gEas, gmail]
,07-05 14:04:15.131  1657  3639 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
07-05 14:04:15.131  1657  3639 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,07-05 14:04:15.134  3651  3689 W Gmail   : Sync started for account: account:61035162
,07-05 14:04:15.140  3651  3651 I Exchange: EasService.onCreate
,07-05 14:04:15.143   787  1332 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm.exchange/com.android.exchange.service.EasService } U=0: not found
07-05 14:04:15.143  3651  3651 I Exchange: EasService.onCreate stoppedOldService=false
,07-05 14:04:15.145  3651  3694 I Exchange: RestartPingTask
,07-05 14:04:15.175  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:15.182   787   954 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 14:04:15.189  3651  3699 I Gmail   : getAccountsCursor
,07-05 14:04:15.196  3651  3651 I Exchange: RestartPingsTask did not start any pings.
,07-05 14:04:15.196  3651  3651 I Exchange: PSS stopIfIdle
07-05 14:04:15.196  3651  3651 I Exchange: PSS has no active accounts; stopping service.
,07-05 14:04:15.198  3651  3651 I Exchange: onDestroy
,07-05 14:04:15.198  3668  3668 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:15.200  3651  3700 I Gmail   : Observing account changes for notifications
,07-05 14:04:15.202  3668  3668 I GoogleHttpClient: Using GMS GoogleHttpClient
07-05 14:04:15.203  3651  3651 I Exchange: EasService.onCreate
07-05 14:04:15.203   787  1195 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm.exchange/com.android.exchange.service.EasService } U=0: not found
07-05 14:04:15.204  3651  3651 I Exchange: EasService.onCreate stoppedOldService=false
07-05 14:04:15.205  3651  3665 I Exchange: RestartPingTask
,07-05 14:04:15.206  3668  3668 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 14:04:15.209  3651  3651 I Exchange: RestartPingsTask did not start any pings.
,07-05 14:04:15.209  3651  3651 I Exchange: PSS stopIfIdle
07-05 14:04:15.209  3651  3651 I Exchange: PSS has no active accounts; stopping service.
07-05 14:04:15.209  3651  3651 I Exchange: onDestroy
,07-05 14:04:15.213  3668  3668 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
07-05 14:04:15.214  3668  3668 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:15.223  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:15.250  3651  3698 I Gmail   : notifyAccountChanged
07-05 14:04:15.252  3668  3668 D MusicLifecycle: com.google.android.music.MusicApplication generated event: Application created
,07-05 14:04:15.253  3651  3698 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:04:15.256  3651  3698 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:04:15.262  3651  3698 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:04:15.262  3651  3698 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:04:15.291  3668  3668 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:04:15.301  3651  3689 I Gmail   : notifyAccountChanged
,07-05 14:04:15.304  3668  3668 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
07-05 14:04:15.304  3668  3668 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:04:15.308  3668  3668 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:04:15.331  3668  3668 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 14:04:15.331  3668  3668 D AndroidMusic: GMSCore installation verified
,07-05 14:04:15.355  3651  3699 W Gmail   : AccountHistory cannot find the addedEvent of 61035162 (went back to 61035162)
,07-05 14:04:15.454  3651  3689 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24527, normalSync: true
,07-05 14:04:15.463  3668  3668 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-05 14:04:15.478  3668  3668 D MusicLifecycle: com.google.android.music.net.NetworkMonitor generated event: Service created
,07-05 14:04:15.480  3668  3668 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:15.499  3668  3668 D MusicLifecycle: com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,07-05 14:04:15.500  3651  3688 I Gmail   : getAccountsCursor
,07-05 14:04:15.503  3668  3668 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,07-05 14:04:15.506  3668  3668 D MusicLifecycle: com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,07-05 14:04:15.524  3668  3668 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fb3cdb9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-05 14:04:15.526  3651  3688 W Gmail   : AccountHistory cannot find the addedEvent of 61035162 (went back to 61035162)
,07-05 14:04:15.526  3668  3668 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:15.544  3668  3668 D MusicLifecycle: com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,07-05 14:04:15.564  3668  3668 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,07-05 14:04:15.566   787   797 I ActivityManager: Killing 2712:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-05 14:04:15.582  3651  3689 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,07-05 14:04:15.594  3651  3689 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,07-05 14:04:15.594  3651  3689 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,07-05 14:04:15.598  3651  3689 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,07-05 14:04:15.622  3651  3689 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:15.678  1657  3574 I PeopleSync: Sync finished, successful=true, took 2146ms
,07-05 14:04:15.685  1255  3718 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:15.696  1657  3574 I PeopleContactsSync: CP2 sync start [5005f081]
,07-05 14:04:15.705  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:15.707  1657  3574 I PeopleContactsSync: CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-05 14:04:15.711  1657  3574 I PeopleContactsSync: Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-05 14:04:15.714  1255  3718 D GoogleSignatureVerifier: Package manager can't find package null, defaulting to false
,07-05 14:04:15.718  1255  3718 I GLSUser : Method not found getActionBar
,07-05 14:04:15.754  1657  3574 I PeopleContactsSync: CP2 cleanup done, kept= duration=41 ms
,07-05 14:04:15.760  1657  3574 I PeopleContactsSync: ===CP2 sync finished, success=true, time=59,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,07-05 14:04:15.784  1657  3574 I PeopleSync: ***Sync finished***, duration: 2570 [5005f081]
,07-05 14:04:15.866  1657  3723 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:04:15.942  1657  2048 I art     : Waiting for a blocking GC DisableMovingGc
,07-05 14:04:15.948  1657  2048 I art     : WaitForGcToComplete blocked for 5.970ms for cause DisableMovingGc
,07-05 14:04:15.948  1657  2048 I art     : Starting a blocking GC DisableMovingGc
,07-05 14:04:15.966  3651  3666 I Gmail   : getAccountsCursor
,07-05 14:04:15.970  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:15.993  3651  3666 W Gmail   : AccountHistory cannot find the addedEvent of 61035162 (went back to 61035162)
,07-05 14:04:16.038   787   798 W AppOps  : Bad call: specified package com.google.android.gms under uid 10052 but it is really 10007
,07-05 14:04:16.096  3110  3727 I GAv4    : Google Analytics 8.4.87 is starting up. To enable debug logging on a device run:
07-05 14:04:16.096  3110  3727 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:16.096  3110  3727 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:16.110  3110  3727 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:16.112  3110  3727 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:16.115  3110  3737 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:16.455   787   893 D ConnectivityService: handlePromptUnvalidated 100
,07-05 14:04:16.819  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:16.823  1255  1592 W Herrevad: Invalid mccmnc 
,07-05 14:04:16.825  1255  1592 W Herrevad: Invalid mccmnc 
,07-05 14:04:16.837  3651  3689 I Gmail   : checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^sq_ig_i_social, ^sq_ig_i_promo, ^sq_ig_i_personal, ^f]), all([^b, userlabel:93982, userlabel:90242001, userlabel:2914615, userlabel:90242029, ^sps, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, userlabel:-1492383895, ^f, userlabel:94076, userlabel:823616170, userlabel:-1492276994, userlabel:-1492276990, ^p, userlabel:-1492276991, ^u, ^t, ^smartlabel_group, ^s, ^smartlabel_personal, userlabel:-812318908, ^smartlabel_social, ^sua, ^p_mtunsub, ^sq_ig_i_personal, ^g, ^r, ^punsub, ^smartlabel_promo, userlabel:-1497452393, ^i, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, ^lcs, userlabel:93692, userlabel:-244132349, ^sq_ig_i_social, ^p_ag, userlabel:3011, userlabel:1123230114, ^p_abs])
,07-05 14:04:16.939  1255  1592 V NQFileLogger: [86] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:04:16.958  1255  1592 V ProcessReports: [86] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 14:04:17.144  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:17.276  3651  3689 I Gmail   : getStartSyncRequest: handledServerOpId: 24722, upperFetchedConvoId: 1533544913819402240, lowerFetchedConvoId: 0, ackedClientOp: 0
,07-05 14:04:17.281   787  1320 I ActivityManager: Killing 3067:com.android.settings/1000 (adj 15): empty #17
,07-05 14:04:17.290   787   892 D WifiService: Client connection lost with reason: 4
,07-05 14:04:17.502  3771  3771 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/cache/1459442732877.jar --oat-file=/data/user/0/com.google.android.gms/cache/1459442732877.dex
,07-05 14:04:17.555  3771  3771 I dex2oat : dex2oat took 54.241ms (threads: 4) arena alloc=339KB java alloc=42KB native alloc=1833KB free=1494KB
,07-05 14:04:17.672  1255  1592 W Herrevad: Invalid mccmnc 
,07-05 14:04:17.678  1255  1592 W Herrevad: Invalid mccmnc 
,07-05 14:04:17.826  1255  1592 V NQFileLogger: [86] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:04:17.827  1255  1592 V ProcessReports: [86] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 14:04:17.877  1255  3765 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,07-05 14:04:17.930  1255  1545 I GCoreUlr: DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 14:04:17.934  1255  1545 I GCoreUlr: Unbound from all location providers
,07-05 14:04:17.961  3651  3689 I Gmail   : checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^sq_ig_i_social, ^sq_ig_i_promo, ^sq_ig_i_personal, ^f]), all([^b, userlabel:90242001, userlabel:93982, userlabel:2914615, userlabel:90242029, ^sps, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, ^f, userlabel:-1492383895, userlabel:94076, userlabel:823616170, userlabel:-1492276994, userlabel:-1492276990, ^p, userlabel:-1492276991, ^u, ^t, ^s, ^smartlabel_group, userlabel:-812318908, ^smartlabel_personal, ^smartlabel_social, ^p_mtunsub, ^sua, ^sq_ig_i_personal, ^g, ^punsub, ^r, userlabel:-1497452393, ^i, ^smartlabel_promo, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, userlabel:93692, ^lcs, userlabel:-244132349, ^sq_ig_i_social, userlabel:3011, ^p_ag, userlabel:1123230114, ^p_abs])
,07-05 14:04:17.967  1657  3785 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:04:17.985  1255  1255 I GCoreUlr: DispatchingService.onDestroy()
,07-05 14:04:17.985  1255  1255 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-05 14:04:17.988  1255  1255 I GCoreUlr: Unbound from all location providers
,07-05 14:04:17.990  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:18.187  3651  3689 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 1539016236736708609, highestHandledServerOp: 24722, normalSync: true
,07-05 14:04:18.265  1657  3785 I PeopleSync: Setting subscription: result=true [5005f081]
,07-05 14:04:18.313  2810  3798 W SyncManagerImpl: Initiating sync for AccountId 3a3529a (com.google.android.apps.docs)
,07-05 14:04:18.318   787   798 D WifiService: acquireWifiLockLocked: WifiLock{SyncManagerImpl type=1 binder=android.os.BinderProxy@db0ab0d}
,07-05 14:04:18.350  1255  3801 I VacuumService: Vacuum at: now=1467720258350 tag=VacuumService
,07-05 14:04:18.380  2810  3798 W SyncManagerImpl: Started sync for AccountId 3a3529a
,07-05 14:04:18.382  2810  3798 W Flag    : Duration spec must be at least 2 characters long: 
,07-05 14:04:18.409   930   930 D PhoneStatusBar: disable: < expand icons* alerts system_info* back home recent clock search quick_settings >
,07-05 14:04:18.570  2810  3798 W jwd     : Application name is not set. Call Builder#setApplicationName.
07-05 14:04:18.572  1255  1545 W Herrevad: Invalid mccmnc 
,07-05 14:04:18.573  1255  1545 W Herrevad: Invalid mccmnc 
,07-05 14:04:18.654  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:18.665  1255  1270 I art     : Background partial concurrent mark sweep GC freed 74850(5MB) AllocSpace objects, 17(340KB) LOS objects, 40% free, 21MB/35MB, paused 20.573ms total 51.656ms
,07-05 14:04:18.672  1255  1268 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2db7022)
,07-05 14:04:18.680  1255  1545 W Herrevad: Invalid mccmnc 
,07-05 14:04:18.682  3651  3689 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24736, normalSync: true
,07-05 14:04:18.682  1255  1545 W Herrevad: Invalid mccmnc 
,07-05 14:04:18.683  3651  3689 I Gmail   : lowestBackward conversation id 0
,07-05 14:04:18.693  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:18.792  1657  3809 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:04:18.801  3651  3689 I Gmail   : AppDataSearch: minSeqNo=0, maxSeqNo=0, lastCommittedSequence=94
,07-05 14:04:18.837  3651  3689 I Gmail   : notifyAccountChanged
,07-05 14:04:18.840  1255  1545 V Herrevad: [65] pou.a: Skipping report; opted out of usage reporting
07-05 14:04:18.841  3651  3694 I Gmail   : getAccountsCursor
,07-05 14:04:18.847  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:18.866  1255  1545 V NQFileLogger: [65] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 14:04:18.866  1255  1545 V ProcessReports: [65] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 14:04:18.868  3651  3694 W Gmail   : AccountHistory cannot find the addedEvent of 61035162 (went back to 61035162)
,07-05 14:04:18.897  3651  3689 I Gmail   : notifyAccountChanged
,07-05 14:04:18.898  3651  3665 I Gmail   : getAccountsCursor
,07-05 14:04:18.899  3651  3689 W Gmail   : Sync complete for account: account:61035162
,07-05 14:04:18.904  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:18.917  3651  3665 W Gmail   : AccountHistory cannot find the addedEvent of 61035162 (went back to 61035162)
,07-05 14:04:18.979  2810  3798 W SyncManagerImpl: Sync for AccountId 3a3529a took 417 ms
,07-05 14:04:18.983   787   972 D WifiService: releaseWifiLockLocked: WifiLock{SyncManagerImpl type=1 binder=android.os.BinderProxy@db0ab0d}
,07-05 14:04:18.984  2810  3798 W SyncManagerImpl: Sync completed for AccountId 3a3529a (com.google.android.apps.docs)
,07-05 14:04:18.988   787   798 I ActivityManager: Killing 2344:com.google.android.talk/u0a51 (adj 15): empty #17
,07-05 14:04:19.011  1255  3812 W System.err: java.lang.Exception: Error converting session
,07-05 14:04:19.012  1255  3812 W System.err: 	at slt.log(SourceFile:302)
,07-05 14:04:19.012  1255  3812 W System.err: 	at slt.toSession(SourceFile:269)
07-05 14:04:19.012  1255  3812 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-05 14:04:19.012  1255  3812 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-05 14:04:19.012  1255  3812 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-05 14:04:19.012  1255  3812 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:310)
,07-05 14:04:19.012  1255  3812 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.verifyHostname(SourceFile:217)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:507)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
,07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
,07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:943)
,07-05 14:04:19.013  1255  3812 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:761)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:669)
07-05 14:04:19.013  1255  3812 W System.err: 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:653)
07-05 14:04:19.013  1255  3812 W System.err: 	at ejm.a(SourceFile:233)
07-05 14:04:19.014  1255  3812 W System.err: 	at eju.a(SourceFile:263)
,07-05 14:04:19.014  1255  3812 W System.err: 	at eju.a(SourceFile:1141)
07-05 14:04:19.014  1255  3812 W System.err: 	at eiv.a(SourceFile:1093)
07-05 14:04:19.014  1255  3812 W System.err: 	at jxb.onPerformSync(SourceFile:98)
07-05 14:04:19.014  1255  3812 W System.err: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:19.014  1255  3812 W System.err: Caused by: java.io.IOException: Invalid session data
,07-05 14:04:19.014  1255  3812 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
07-05 14:04:19.014  1255  3812 W System.err: 	at slt.toSession(SourceFile:267)
07-05 14:04:19.014  1255  3812 W System.err: 	... 28 more
,07-05 14:04:19.393  3668  3668 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 14:04:19.393  3668  3668 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:19.399  3668  3818 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,07-05 14:04:19.500  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:19.893  1657  2320 I Icing   : Indexing 28BD5497C79FF5FD8126DB62EFBE21DAF39B3617 from com.google.android.gm
,07-05 14:04:19.929  1657  2320 I Icing   : Indexing done 28BD5497C79FF5FD8126DB62EFBE21DAF39B3617
,07-05 14:04:20.056  3651  3682 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:20.065   787   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,07-05 14:04:20.385  3668  3818 D MusicProfiler: http: duration=0479ms uri=https://mclients.googleapis.com/sj/v2.4/config?alt=json&hl=en_US&tier=none&dv=2817&max-results=0
,07-05 14:04:20.465  3668  3818 W InstanceID/Rpc: Found 10007
,07-05 14:04:20.507  3668  3668 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@5a2b6f9 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:04:20.520  3668  3668 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:04:20.523  3668  3818 I MusicSyncAdapter: Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
07-05 14:04:20.523  3668  3818 I MusicSyncAdapter: Periodic update
,07-05 14:04:20.537  3668  3668 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:04:20.545  3668  3710 I PlayCommon: [285] EventLogger.dispatchMessage: Starting to flush logs
,07-05 14:04:20.546  3668  3710 I PlayCommon: [285] EventLogger.dispatchMessage: Log flushed by 0 successful uploads
,07-05 14:04:20.547  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@5a2b6f9 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:04:20.560  3668  3668 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:20.565  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:04:20.573  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:04:20.580  3668  3851 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 14:04:20.580  3668  3851 I MusicLeanback: Stop autocaching.
,07-05 14:04:20.586  3668  3820 W MusicApiClient: Activity events list is null or empty. Skip reporting.
,07-05 14:04:20.588  3668  3668 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:20.607  3668  3668 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@5a2b6f9 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:04:20.615  3668  3668 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:04:20.617  1255  1255 D WearableService: callingUid 10007, callindPid: 1255
,07-05 14:04:20.617  3668  3818 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
,07-05 14:04:20.618  3668  3668 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:04:20.620  3668  3668 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@5a2b6f9 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:04:20.626  3668  3870 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-05 14:04:20.626  3668  3870 I MusicLeanback: Stop autocaching.
,07-05 14:04:20.647  3668  3668 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:20.651  3668  3668 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,07-05 14:04:20.651  3668  3668 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
,07-05 14:04:20.651  3668  3668 D MusicLifecycle: com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
,07-05 14:04:20.653  3668  3668 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service created
,07-05 14:04:20.658  3668  3668 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:20.664  3668  3856 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 14:04:20.665  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:04:20.670  3668  3668 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@5a2b6f9 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator (has extras) }
,07-05 14:04:20.674  3668  3668 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,07-05 14:04:20.674  3668  3668 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service destroyed
,07-05 14:04:20.677  3668  3668 D MusicLifecycle: com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,07-05 14:04:20.682  3668  3668 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:04:20.682  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@5a2b6f9 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver (has extras) }
,07-05 14:04:20.684  3668  3668 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:20.690  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
07-05 14:04:20.691  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:04:20.693  3668  3668 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:20.698  3668  3884 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 14:04:20.699  3668  3668 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:04:20.711  3668  3668 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:04:22.226   787   818 W PackageSettings: Skipping PackageSetting{4b3ce6d com.example.hello/10116} due to missing metadata
,07-05 14:04:22.993  1255  3603 D PlaceInferenceEngine: Stop called when not running
,07-05 14:04:22.995  1255  1602 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:23.039   787   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:04:23.106   787  1320 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=3422, uid=10071 that is not exported from uid 10058
,07-05 14:04:23.119  1364  3897 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 14:04:23.141  1657  3898 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-05 14:04:23.141  1657  3898 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoring.
,07-05 14:04:23.152  1657  3898 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:04:23.161  1364  3897 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 41 ms] updated apps [took 41 ms] 
,07-05 14:04:23.162  1657  2320 I Icing   : updateResources: need to parse pru{com.google.android.gms}
,07-05 14:04:23.165  1657  3921 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
,07-05 14:04:23.196  1255  1255 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 14:04:23.245  1255  1487 D GCoreFlp: FLP HAL exists but batch size is <= 0.  Disabling FLP HAL.
,07-05 14:04:23.255  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_apps_corpus_label
,07-05 14:04:23.255  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_apps_corpus_description
07-05 14:04:23.255  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_device_source_apps_normal
07-05 14:04:23.255  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_contacts_corpus_label
07-05 14:04:23.255  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name string/icing_contacts_corpus_description
07-05 14:04:23.255  1657  2320 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_device_source_contacts
,07-05 14:04:23.261  1255  1487 W GCoreFlp: No location to return for getLastLocation()
,07-05 14:04:23.280  1255  1487 D GCoreFlp: FLP HAL exists but batch size is <= 0.  Disabling FLP HAL.
,07-05 14:04:24.019   787   803 I ActivityManager: Waited long enough for: ServiceRecord{2440535 u0 com.google.android.apps.maps/com.google.android.apps.gmm.offline.OfflineRegionManagementService}
,07-05 14:04:24.285  1657  2320 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,07-05 14:04:24.294  1657  2320 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,07-05 14:04:28.434   787   891 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-05 14:04:50.304  3064  3064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-05 14:04:50.728   787   796 I art     : Background partial concurrent mark sweep GC freed 66591(3MB) AllocSpace objects, 9(176KB) LOS objects, 33% free, 25MB/38MB, paused 932us total 157.194ms
,07-05 14:04:50.766   787  1332 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1657 for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:04:50.771  3110  3935 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.keep
,07-05 14:04:50.813  1657  3962 W DriveInitializer: Background init thread started
,07-05 14:04:50.850  1657  3964 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-05 14:04:50.850  1657  3964 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 14:04:50.904  1657  3962 W DriveInitializer: Background init thread ended
,07-05 14:04:50.907  1657  3965 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:04:51.008   199   899 D WVCdm   : Instantiating CDM.
,07-05 14:04:51.008   199   830 I WVCdm   : CdmEngine::OpenSession
,07-05 14:04:51.009   199   830 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:04:51.013   199   830 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:04:51.015   199   830 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-05 14:04:51.015   199   830 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:04:51.015   199   830 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:51.015   199   830 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:51.034   199   830 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:04:51.035   199   830 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:04:51.035   199   830 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3466000
07-05 14:04:51.035   199   830 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3466000
,07-05 14:04:51.045   199   830 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:04:51.045   199   830 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:51.050   199   830 D DrmWidevineDash: hlos api version =  10
,07-05 14:04:51.050   199   830 D DrmWidevineDash: tz api version =  10
07-05 14:04:51.050   199   830 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:51.050   199   830 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:04:51.061   199   830 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-05 14:04:51.061   199   830 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:51.061   199   830 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb377f134
,07-05 14:04:51.066   199   830 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-05 14:04:51.066   199   830 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:04:51.066   199   830 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604bda8, dataLength=8
,07-05 14:04:51.072   199   830 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:04:51.072   199   830 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb6007600, wrapped_rsa_key_length=1280
,07-05 14:04:51.079   199   830 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-05 14:04:51.079   199   830 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:04:51.082   199   199 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-05 14:04:51.082   199   199 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:51.082   199   199 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:51.082   199   199 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb38bdde0, idLength=0xbee0100c
,07-05 14:04:51.098   199   199 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:04:51.099   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:04:51.104   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:04:51.104   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:04:51.104   199   199 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:04:51.104   199   199 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:04:51.109   199   199 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-05 14:04:51.109   199   199 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:51.114   199   199 D DrmWidevineDash: hlos api version =  10
07-05 14:04:51.114   199   199 D DrmWidevineDash: tz api version =  10
,07-05 14:04:51.114   199   199 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:51.114   199   199 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-05 14:04:51.119   199   199 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-05 14:04:51.119   199   199 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:04:51.119   199   199 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:04:51.125   199   199 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 14:04:51.125   199   199 D WVCdm   : PrepareKeyRequest: nonce=1735007226
07-05 14:04:51.125   199   199 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2224700
07-05 14:04:51.125   199   199 D DrmWidevineDash: message_length=1639, signature=0xb60765c0, signature_length=3202355428
,07-05 14:04:51.197   199   199 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
07-05 14:04:51.197   199   899 I WVCdm   : CdmEngine::CloseSession
07-05 14:04:51.197   199   899 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 14:04:51.205   199   899 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 14:04:51.205   199   899 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:04:51.213   199   899 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:04:51.213   199   899 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:04:51.213   199   899 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-05 14:04:51.213   199   899 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:04:51.214   199   899 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:04:51.250  3298  3363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:04:51.264  1657  3976 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-05 14:04:51.273   787   802 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141601, reason: UserStart, SyncResult: databaseError: true stats []
,07-05 14:04:51.274   787   802 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 216194, reason: UserStart
,07-05 14:04:51.296  3298  3363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:04:51.341  3298  3363 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-05 14:04:51.607  1255  1268 E System  : Uncaught exception thrown by finalizer
,07-05 14:04:51.608  1255  1268 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:04:51.608  1255  1268 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:04:51.608  1255  1268 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-05 14:04:51.608  1255  1268 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:04:51.608  1255  1268 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:04:51.608  1255  1268 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:04:51.806  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:51.807  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:51.897  1657  3983 D UdcContextInitService: registered all accounts: true
,07-05 14:04:53.446  1255  3987 E CommitToConfigurationOperation: Malformed snapshot token: 
,07-05 14:04:53.448  1255  3985 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:04:53.464  1255  3987 E CommitToConfigurationOperation: Malformed snapshot token: 
,07-05 14:04:53.466  1255  3985 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:04:53.481  1255  3987 E CommitToConfigurationOperation: Malformed snapshot token: 
,07-05 14:04:53.482  1255  3985 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:04:53.482  1255  3985 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-05 14:04:53.485  1255  3985 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:55.586  1255  1270 I art     : Background sticky concurrent mark sweep GC freed 99513(7MB) AllocSpace objects, 2(40KB) LOS objects, 21% free, 27MB/35MB, paused 1.230ms total 104.612ms
,07-05 14:04:56.936  1255  3985 W Uploader: GMM_PRIMES no longer exists, so no auth token.
,07-05 14:04:58.208   787   814 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 14:04:58.219   787   814 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:04:58.247   192  1535 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (696 us)
07-05 14:04:58.250   787   814 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-05 14:04:58.282  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 14:04:58.282  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:04:58.331  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@91ce197 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1d554a4, 16908290=android.view.AbsSavedState$1@1d554a4}, android:focusedViewId=100}]}]
,07-05 14:04:58.331  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:04:58.331  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:04:58.331  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:04:58.824   787   814 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 14:04:58.834   787   814 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-05 14:04:58.837   787   812 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:04:58.841   192   192 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
07-05 14:04:58.841   192   192 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 14:04:59.129   192   192 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-05 14:04:59.134   787   908 D SurfaceControl: Excessive delay in setPowerMode(): 297ms
07-05 14:04:59.134  1815  1832 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
07-05 14:04:59.140   199   830 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-05 14:04:59.147   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-05 14:04:59.167   787   891 E native  : do suspend false
,07-05 14:04:59.186   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
07-05 14:04:59.195   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
07-05 14:04:59.197   787   891 E native  : do suspend true
,07-05 14:04:59.208   199   199 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-05 14:04:59.214  1229  1229 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-05 14:04:59.229  1657  2320 D MdnsClient: Multicast lock held. Releasing
,07-05 14:05:00.181  1657  2320 D MdnsClient: #acquireLock. Multicast lock not held. Acquiring
,07-05 14:05:08.441   787   891 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,07-05 14:05:29.301  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:05:29.301  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:05:52.148  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:05:52.148  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:05:52.167  1255  1592 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> BAD_AUTHENTICATION. Account: <ELLIDED:-818113082>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:52.167  1255  1592 E Auth    : elc: Long live credential not available.
07-05 14:05:52.167  1255  1592 E Auth    : 	at eld.a(SourceFile:3099)
07-05 14:05:52.167  1255  1592 E Auth    : 	at ejq.a(SourceFile:397)
07-05 14:05:52.167  1255  1592 E Auth    : 	at ejp.a(SourceFile:31369)
07-05 14:05:52.167  1255  1592 E Auth    : 	at ejp.a(SourceFile:313)
07-05 14:05:52.167  1255  1592 E Auth    : 	at fla.a(SourceFile:1201)
07-05 14:05:52.167  1255  1592 E Auth    : 	at fkz.a(SourceFile:530)
07-05 14:05:52.167  1255  1592 E Auth    : 	at fkz.a(SourceFile:196)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egp.a(SourceFile:284)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egp.a(SourceFile:204)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egu.a(SourceFile:1510)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egt.a(SourceFile:920)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egt.e(SourceFile:534)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egt.d(SourceFile:454)
07-05 14:05:52.167  1255  1592 E Auth    : 	at egr.b(SourceFile:568)
07-05 14:05:52.167  1255  1592 E Auth    : 	at jtq.a(SourceFile:82)
07-05 14:05:52.167  1255  1592 E Auth    : 	at jsg.a(SourceFile:57)
07-05 14:05:52.167  1255  1592 E Auth    : 	at bnq.a(SourceFile:6096)
07-05 14:05:52.167  1255  1592 E Auth    : 	at bjz.run(SourceFile:52)
07-05 14:05:52.167  1255  1592 E Auth    : 	at bjx.a(SourceFile:258)
07-05 14:05:52.167  1255  1592 E Auth    : 	at bjx.handleMessage(SourceFile:251)
07-05 14:05:52.167  1255  1592 E Auth    : 	at jxi.run(SourceFile:141)
07-05 14:05:52.167  1255  1592 E Auth    : 	at jxq.run(SourceFile:438)
07-05 14:05:52.167  1255  1592 E Auth    : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:05:52.167  1255  1592 E Auth    : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:05:52.167  1255  1592 E Auth    : 	at kca.run(SourceFile:17)
07-05 14:05:52.167  1255  1592 E Auth    : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:05:52.184  1255  1592 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:52.506  1255  1592 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=UNKNOWN).  Giving up.
,07-05 14:05:52.773  1255  1592 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 14:06:56.140   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277108, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:07:29.591  1657  3385 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:07:52.372  1255  1608 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:07:53.854  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:53.858  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:53.858  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:54.284  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:54.445  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:54.614  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:54.830  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:07:58.900   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339868, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:08:54.460   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=395428, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:09:03.780   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404748, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:09:14.530  1657  3638 W PlayEventLogger: No account for auth token provided
,07-05 14:09:14.547  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:09:14.551  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:09:14.551  1255  1255 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:10:01.140   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=462108, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:10:07.470   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:10:49.420   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=510388, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:10:57.691   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518658, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:11:39.660   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=560628, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:12:00.212   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=581180, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:12:42.060   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=623028, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:12:59.941   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=640908, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:13:41.900   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=682868, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:14:19.692   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=720660, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:15:01.580   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=762548, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:15:51.407   787   883 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-05 14:15:51.408   787   787 V KeyguardServiceDelegate: onStartedWakingUp()
,07-05 14:15:51.410   787   814 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 14:15:51.424   787   814 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@70d40e)
07-05 14:15:51.424  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-05 14:15:51.424  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 14:15:51.425  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-05 14:15:51.425  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-05 14:15:51.441   787  1329 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-05 14:15:51.476   199   199 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-05 14:15:51.478   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:15:51.482   787   891 E native  : do suspend false
,07-05 14:15:51.489   787   891 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:15:51.506  1815  1832 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-05 14:15:51.506   787   812 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-05 14:15:51.507   192   192 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
07-05 14:15:51.507   192   192 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 14:15:51.585  1255  1255 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-05 14:15:51.603   787   798 I ActivityManager: Start proc 4155:com.google.android.apps.fitness/u0a82 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-05 14:15:51.640  4155  4155 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.fitness-1/lib/arm
,07-05 14:15:51.662   787   814 I DisplayPowerController: Unblocked screen on after 252 ms
,07-05 14:15:51.663   787   814 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-05 14:15:51.744   192   192 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-05 14:15:51.744   787   908 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,07-05 14:15:56.440   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=817408, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:16:33.340   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=854308, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:17:51.593  1255  1608 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:17:52.401   787   814 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:17:52.402   787   814 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:17:52.557  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:17:52.557  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-05 14:17:52.559  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@91ce197 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1d554a4, 16908290=android.view.AbsSavedState$1@1d554a4}, android:focusedViewId=100}]}]
07-05 14:17:52.559  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:17:52.559  2923  2923 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:17:52.560  2923  2923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:17:52.621   787   796 I art     : Background partial concurrent mark sweep GC freed 52276(3MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 25MB/38MB, paused 710us total 140.421ms
,07-05 14:17:53.027   787   814 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 14:17:53.045   787   812 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:17:53.050   192   192 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
07-05 14:17:53.050   192   192 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 14:17:53.322   192   192 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-05 14:17:53.324   787   908 D SurfaceControl: Excessive delay in setPowerMode(): 279ms
07-05 14:17:53.325  1815  1832 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-05 14:17:53.411   787   891 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:17:53.413   787   891 E native  : do suspend true
,07-05 14:17:53.415   199   899 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-05 14:17:53.426  1229  1229 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,07-05 14:17:53.445  1657  2320 D MdnsClient: Multicast lock held. Releasing
,07-05 14:18:28.450   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969418, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:18:37.000   787  3202 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977968, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:22:38.832   787   802 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms)
```
