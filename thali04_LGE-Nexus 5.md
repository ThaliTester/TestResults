#### Test 757892686f45c73_thali04_LGE-Nexus 5 Logs


```
--------- beginning of system
07-26 15:20:42.848   792  1526 I ActivityManager: Killing 2972:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,--------- beginning of main
07-26 15:20:44.832  3515  3515 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-26 15:20:44.836  3515  3515 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:44.870  3515  3515 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 15:20:44.905  3515  3515 I Radio-JNI: register_android_hardware_Radio DONE
07-26 15:20:44.923  3515  3515 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 15:20:44.926   792  1546 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:20:44.945   792  1546 I ActivityManager: Start proc 3531:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-26 15:20:44.947  3515  3515 D AndroidRuntime: Shutting down VM
07-26 15:20:45.007  3531  3531 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-26 15:20:45.046  3531  3531 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3510-3515)
07-26 15:20:45.046  3531  3531 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:45.072  3531  3531 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {20f75dd}
07-26 15:20:45.072  3531  3531 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:45.072  3531  3531 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:20:45.081  3531  3531 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-26 15:20:45.083  3531  3531 E SysUtils: ApplicationContext is null in ApplicationStatus
07-26 15:20:45.099  3531  3531 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-26 15:20:45.106  3531  3531 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:45.106  3531  3531 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:45.107  3531  3531 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-26 15:20:45.154   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc9f23d:true
,07-26 15:20:45.234  3531  3531 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:20:45.245  3531  3531 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-26 15:20:45.289  3531  3574 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-26 15:20:45.311  3531  3561 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-26 15:20:45.350  3531  3574 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:20:45.401   792   813 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +425ms (total +465ms)
,07-26 15:20:45.403  1243  1243 I Keyboard.Facilitator: onFinishInput()
,07-26 15:20:45.474  3531  3531 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3531
,07-26 15:20:45.557  3531  3531 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:20:45.673  3531  3579 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1657464528
07-26 15:20:45.677  3531  3579 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:45.677  3531  3579 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:45.677  3531  3579 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:45.677  3531  3579 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:45.677  3531  3579 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-26 15:20:45.677  3531  3579 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dc40f8 added. We now have 1 listener(s)
07-26 15:20:45.680  3531  3579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
07-26 15:20:45.681  3531  3579 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:20:45.682  3531  3579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:45.682  3531  3579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-26 15:20:45.684  3531  3579 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c3737 added. We now have 1 listener(s)
07-26 15:20:45.685  3531  3579 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:45.687   792   898 D WifiService: New client listening to asynchronous messages
07-26 15:20:45.688  3531  3579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:45.688  3531  3579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:45.688  3531  3579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:45.688  3531  3579 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-26 15:20:45.690  3531  3579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:45.690  3531  3579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
07-26 15:20:45.697  3531  3579 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:45.697  3531  3579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:45.697  3531  3579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:20:45.697  3531  3579 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:45.697  3531  3579 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:20:45.703  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:45.707  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:45.725  3531  3531 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:20:46.313  3531  3589 W jxcore-log: Initializing JXcore engine
,07-26 15:20:46.313  3531  3589 W jxcore-log: JXcore engine is ready
,07-26 15:20:46.349  3589  3589 W Thread-278: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7069]" dev="sockfs" ino=7069 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-26 15:20:46.349  3589  3589 W Thread-278: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-26 15:20:46.349  3589  3589 W Thread-278: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21612]" dev="sockfs" ino=21612 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-26 15:20:46.366  3531  3589 W jxcore-log: Starting JXcore engine
,07-26 15:20:46.451  3531  3589 W jxcore-log: Platform android
07-26 15:20:46.451  3531  3589 W jxcore-log: 
,07-26 15:20:46.451  3531  3589 W jxcore-log: Process ARCH arm
07-26 15:20:46.451  3531  3589 W jxcore-log: 
,07-26 15:20:46.631  3531  3589 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:46.631  3531  3589 I jxcore-log: 
,07-26 15:20:46.632  3531  3589 W jxcore-log: JXcore engine is started
,07-26 15:20:46.634  3531  3579 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:46.636  3531  3531 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:20:47.885   792  1208 I ActivityManager: Killing 2907:com.google.android.apps.photos/u0a65 (adj 15): empty #17
,07-26 15:20:55.787  2545  2577 I Finsky  : [218] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-26 15:20:55.923  1660  3601 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-26 15:20:55.925  1660  3601 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-26 15:20:55.940  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:20:56.006  2545  2577 I Finsky  : [218] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-26 15:20:56.007  2545  2545 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-26 15:20:56.144   792   803 I ActivityManager: Start proc 3609:com.google.android.gms.unstable/u0a8 for service com.google.android.gms/.droidguard.DroidGuardService
,07-26 15:20:56.209  3609  3609 I MultiDex: VM with version 2.1.0 has multidex support
07-26 15:20:56.209  3609  3609 I MultiDex: install
07-26 15:20:56.209  3609  3609 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-26 15:20:56.234  3609  3609 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-26 15:20:56.250  3609  3609 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-26 15:20:56.251  3609  3609 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-26 15:20:56.257  3609  3609 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-26 15:20:56.289  3609  3609 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-26 15:20:56.299  3609  3609 D ChimeraCfgMgr: Reading stored module config
,07-26 15:20:56.371  1744  1744 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=51b9dac9-6f2a-4400-aa76-7c6b6150f923
,07-26 15:20:56.398  3609  3624 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-26 15:20:56.398  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-26 15:20:56.399  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:20:56.456   198  1514 D WVCdm   : Instantiating CDM.
,07-26 15:20:56.457   198   905 I WVCdm   : CdmEngine::OpenSession
,07-26 15:20:56.457   198   905 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-26 15:20:56.473   198   905 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-26 15:20:56.477   198   905 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-26 15:20:56.477   198   905 D DrmWidevineDash: Service_Initialize: starts!
07-26 15:20:56.477   198   905 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-26 15:20:56.477   198   905 D QSEECOMAPI: : App is not loaded in QSEE
,07-26 15:20:56.510   198   905 D QSEECOMAPI: : Loaded image: APP id = 3
,07-26 15:20:56.511   198   905 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-26 15:20:56.511   198   905 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33d1000
07-26 15:20:56.511   198   905 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33d1000
,07-26 15:20:56.526   198   905 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-26 15:20:56.526   198   905 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-26 15:20:56.531   198   905 D DrmWidevineDash: hlos api version =  10
,07-26 15:20:56.531   198   905 D DrmWidevineDash: tz api version =  10
07-26 15:20:56.531   198   905 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-26 15:20:56.531   198   905 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-26 15:20:56.545   198   905 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-26 15:20:56.545   198   905 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-26 15:20:56.545   198   905 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb363d134
,07-26 15:20:56.550   198   905 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-26 15:20:56.550   198   905 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-26 15:20:56.550   198   905 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb4667178, dataLength=8
,07-26 15:20:56.560   198   905 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-26 15:20:56.566   198   905 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb345ec00, wrapped_rsa_key_length=1280
,07-26 15:20:56.573   198   905 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-26 15:20:56.573   198   905 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-26 15:20:56.575   198   836 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-26 15:20:56.575   198   836 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-26 15:20:56.575   198   836 I WVCdm   : CdmEngine::GenerateKeyRequest
07-26 15:20:56.575   198   836 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb342ac20, idLength=0xb373ef2c
,07-26 15:20:56.579  1744  1781 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:56.592   198   836 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-26 15:20:56.592   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-26 15:20:56.603   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-26 15:20:56.603   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,07-26 15:20:56.603   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-26 15:20:56.603   198   836 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-26 15:20:56.607  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-26 15:20:56.607  3531  3589 I jxcore-log: 
07-26 15:20:56.609  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-26 15:20:56.609  3531  3589 I jxcore-log: 
07-26 15:20:56.610   198   836 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-26 15:20:56.610   198   836 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-26 15:20:56.617   198   836 D DrmWidevineDash: hlos api version =  10
,07-26 15:20:56.617   198   836 D DrmWidevineDash: tz api version =  10
07-26 15:20:56.617   198   836 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-26 15:20:56.617   198   836 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:56.618  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:56.621  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:56.624  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-26 15:20:56.624  3531  3589 I jxcore-log: 
,07-26 15:20:56.624   198   836 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-26 15:20:56.624   198   836 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-26 15:20:56.624   198   836 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-26 15:20:56.627  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-26 15:20:56.627  3531  3589 I jxcore-log: 
,07-26 15:20:56.630   198   836 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-26 15:20:56.630   198   836 D WVCdm   : PrepareKeyRequest: nonce=3415771176
07-26 15:20:56.630   198   836 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4883c00
07-26 15:20:56.630   198   836 D DrmWidevineDash: message_length=1639, signature=0xb6076840, signature_length=3010719748
,07-26 15:20:56.635  1660  3607 D UdcContextInitService: registered all accounts: true
,07-26 15:20:56.638  1744  1817 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:56.655  1744  1791 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-26 15:20:56.716   198   836 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-26 15:20:56.717   198  1514 I WVCdm   : CdmEngine::CloseSession
07-26 15:20:56.717   198  1514 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-26 15:20:56.722   198  1514 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-26 15:20:56.722   198  1514 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-26 15:20:56.727   198  1514 D DrmWidevineDash: Service_Uninitialize: starts!
,07-26 15:20:56.727   198  1514 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-26 15:20:56.727   198  1514 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-26 15:20:56.728   198  1514 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-26 15:20:56.728   198  1514 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-26 15:20:56.970  3639  3639 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-26 15:20:57.017  3531  3589 D ExecuteNativeTests: Running unit tests
,07-26 15:20:57.032  3639  3639 I dex2oat : dex2oat took 62.361ms (threads: 4) arena alloc=273KB java alloc=67KB native alloc=1669KB free=1658KB
,07-26 15:20:57.038  3609  3619 W System  : ClassLoader referenced unknown path: 
,07-26 15:20:57.043  3609  3619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:20:57.078  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:20:57.078  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed added. We now have 2 listener(s)
07-26 15:20:57.079  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:20:57.079  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:57.079  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:57.079  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:57.079  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 added. We now have 2 listener(s)
07-26 15:20:57.079  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:57.080  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:20:57.081  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.084  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:57.085  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:20:57.085  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:57.087  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:20:57.087  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:20:57.087  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:20:57.088  3531  3589 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-26 15:20:57.088  3531  3589 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:20:57.088  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:20:57.088  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-26 15:20:57.088  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:20:57.089  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.089  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.089  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.089  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.089  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.089  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.089  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-26 15:20:57.089  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed removed from the list
07-26 15:20:57.089  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.089  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 removed from the list
,07-26 15:20:57.091  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.092  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.092  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.092  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.092  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.092  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.093  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:20:57.093  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.093  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.093  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.094  3531  3589 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-26 15:20:57.094  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.094  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.094  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:20:57.094  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:20:57.094  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:57.094  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.095  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.095  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.095  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.095  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.095  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.095  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.095  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.095  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.095  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.095  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.095  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.095  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:20:57.099  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:20:57.099  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.100  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.100  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.100  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.100  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.100  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.100  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.100  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.100  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.100  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.100  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.100  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.100  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.100  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.100  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.100  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.100  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.100  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.101  3531  3589 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:20:57.102  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.105  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:57.106  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.106  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:57.106  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:57.107  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:57.107  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.107  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:57.108  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.110  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.110  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:57.110  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:20:57.114  3531  3589 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:20:57.115  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:20:57.116  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:20:57.116  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:20:57.117  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:57.117  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:57.118  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.119  3531  3589 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:57.119  3531  3589 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:20:57.120  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.120  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.121  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.121  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.121  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.121  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.121  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.121  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.121  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.121  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.121  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.121  3531  3589 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:20:57.122  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.124  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:57.125  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.125  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:57.126  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:20:57.126  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:57.126  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.126  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:57.128  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:57.128  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.129  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.129  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:57.129  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.130  3531  3589 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:57.130  3531  3589 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:20:57.132  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.132  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.132  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.132  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.132  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.132  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.132  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.132  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.132  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.132  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.132  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.132  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.132  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.132  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.133  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.133  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.134  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.134  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.134  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.134  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.134  3531  3589 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:20:57.135  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.138  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:57.139  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.139  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:57.139  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:20:57.139  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:20:57.139  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.139  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:20:57.142  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.142  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:20:57.144  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.144  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:20:57.144  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.145  3531  3589 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:20:57.145  3531  3589 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:20:57.145  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.145  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.145  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.146  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.146  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.146  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.146  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.146  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.146  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:20:57.146  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.146  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.146  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.146  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.146  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.146  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.146  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.147  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.147  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.147  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.147  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.147  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.147  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.147  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.147  3531  3589 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-26 15:20:57.148  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.148  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.148  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.139  3619  3619 W Binder_1: type=1400 audit(0.0:8): avc: denied { read } for name="/" dev="tmpfs" ino=6477 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
07-26 15:20:57.148  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.148  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.148  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.148  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.148  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.148  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.148  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.148  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.148  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.148  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.148  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.148  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.148  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.149  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.149  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.149  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.149  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.149  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.149  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:20:57.149  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.149  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.149  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.150  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.150  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.150  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.150  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.150  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.150  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.150  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.150  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.150  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.150  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.150  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.150  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.150  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.151  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.151  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.151  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.151  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.151  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.151  3531  3589 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-26 15:20:57.151  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.151  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.151  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.151  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.151  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.151  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.151  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.151  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.151  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.151  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.151  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.151  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.151  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.151  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.152  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.152  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.152  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.152  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.152  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.152  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.152  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.153  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-26 15:20:57.153  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.153  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.153  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.153  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.153  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.153  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.153  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.153  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.153  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.153  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.153  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.153  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.153  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.153  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.153  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.154  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.154  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.154  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.154  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.154  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.154  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.154  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:20:57.154  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:20:57.154  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-26 15:20:57.154  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:20:57.155  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:20:57.155  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:20:57.155  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.155  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.155  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.155  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.155  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.155  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.155  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.155  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.155  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.155  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.155  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.155  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.155  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.155  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.155  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.155  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.156  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.156  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.156  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.156  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.156  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.156  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:57.156  3531  3589 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:20:57.156  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:20:57.158  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:57.158  3531  3589 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:20:57.159  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:20:57.159  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-26 15:20:57.159  3531  3589 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:20:57.159  3531  3589 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-26 15:20:57.160  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:57.160  3531  3589 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:20:57.160  3531  3589 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-26 15:20:57.160  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:57.160  3531  3589 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:20:57.160  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-26 15:20:57.162  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-26 15:20:57.162  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-26 15:20:57.162  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-26 15:20:57.163  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-26 15:20:57.163  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-26 15:20:57.163  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-26 15:20:57.163  3531  3589 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:20:57.163  3531  3589 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-26 15:20:57.163  3531  3649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 342)
07-26 15:20:57.164  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.164  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.164  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.164  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.164  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.164  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.164  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-26 15:20:57.164  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.164  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.164  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.164  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.164  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.164  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.164  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.164  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.165  3531  3649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:20:57.165  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.165  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.168  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.168  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.168  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.168  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.168  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.169  3531  3589 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-26 15:20:57.169  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.169  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.169  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.169  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.169  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.169  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.169  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.169  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.169  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.169  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.169  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.169  3531  3589, D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.169  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.170  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.170  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.170  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.171  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.171  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.171  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.171  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.171  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.171  3531  3589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-26 15:20:57.172  3531  3650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 342
07-26 15:20:57.172  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.172  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.172  3531  3650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 342)
07-26 15:20:57.172  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:20:57.172  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.172  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.172  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.172  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.172  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.172  3531  3650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 342)
07-26 15:20:57.172  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.172  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.172  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:57.172  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.172  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:57.172  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.172  3531  3649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 342)
,07-26 15:20:57.172  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.173  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.173  1959  2234 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
07-26 15:20:57.173  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.173  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.173  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 15:20:57.173  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.173  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.173  3531  3589 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-26 15:20:57.173  3531  3589 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-26 15:20:57.173  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-26 15:20:57.173  3531  3589 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-26 15:20:57.173  3531  3589 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-26 15:20:57.173  3531  3589 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-26 15:20:57.173  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:20:57.174  3531  3589 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-26 15:20:57.174  3531  3589 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-26 15:20:57.174  3531  3589 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:20:57.174  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:20:57.174  3531  3589 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-26 15:20:57.174  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.174  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.174  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.174  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.174  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.174  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.174  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.174  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.174  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.174  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.174  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.174  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.174  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.174  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.175  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:20:57.175  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.175  3609  3619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:20:57.175  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.175  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.175  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 15:20:57.175  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.175  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.175  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.175  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.175  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.175  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.175  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:20:57.175  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.175  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:20:57.175  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:57.176  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.176  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.176  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.176  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:20:57.176  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.176  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.176  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
,07-26 15:20:57.176  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:20:57.176  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.176  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.176  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.176  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:57.176  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.176  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.176  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.176  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.176  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:20:57.176  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.176  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.176  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.176  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.177  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.177  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.177  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:20:57.177  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.177  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:20:57.177  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.177  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.178  3531  3589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 15:20:57.178  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.178  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:20:57.179  3531  3531 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 15:20:57.179  3531  3531 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 15:20:57.179  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.179  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:20:57.179  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:20:57.180  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:20:57.180  3531  3651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:20:57.180  3531  3589 D BluetoothAdapter: STATE_ON
,07-26 15:20:57.180  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:20:57.180  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 15:20:57.180  3531  3589 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-26 15:20:57.180  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:20:57.180  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.182  3531  3651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-26 15:20:57.182  3531  3651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-26 15:20:57.182  3531  3651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 15:20:57.183  3531  3589 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:20:57.183  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.183  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.183  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.183  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.183  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.183  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.183  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.183  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.183  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.183  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.183  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.183  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.183  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.183  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.183  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.186  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.186  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.186  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.186  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.187  3531  3589 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-26 15:20:57.187  3531  3589 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:20:57.187  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:20:57.187  3531  3589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:20:57.187  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:20:57.187  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.187  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.187  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.187  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.187  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.187  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.187  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.187  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.187  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.187  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.187  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:20:57.187  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.187  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.188  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.188  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.188  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.188  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.189  3531  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:20:57.189  3531  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:20:57.189  3531  3531 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 15:20:57.189  3531  3531 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 15:20:57.191  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.191  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.191  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.191  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.191  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.191  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.191  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.191  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.191  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.191  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.191  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.191  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.191  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.191  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.191  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.191  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.191  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.192  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.192  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:20:57.192  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:20:57.192  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:20:57.192  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.192  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.192  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.192  3531  3589 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79802ed not in the list
07-26 15:20:57.192  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.192  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Discovery,Manager@ceba522 not in the list
07-26 15:20:57.192  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.192  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.192  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.192  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.192  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.193  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:20:57.193  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:20:57.193  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.193  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceba522 not in the list
07-26 15:20:57.194  3531  3589 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-26 15:20:57.194  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:20:57.194  3531  3589 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-26 15:20:57.194  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:20:57.194  3531  3589 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-26 15:20:57.194  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:20:57.195  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:20:57.195  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-26 15:20:57.196  3531  3589 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-26 15:20:57.196  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:20:57.196  3531  3589 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-26 15:20:57.196  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:20:57.196  3531  3589 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-26 15:20:57.196  3531  3589 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-26 15:20:57.196  3531  3589 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-26 15:20:57.196  3531  3589 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-26 15:20:57.197  3531  3589 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-26 15:20:57.197  3531  3589 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-26 15:20:57.197  3531  3589 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-26 15:20:57.197  3531  3589 D io.jxcore.node.ConnectionModel: hasConnection: We have an out,going connection with peer with ID outgoing
07-26 15:20:57.197  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:57.197  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7330e2b added. We now have 2 listener(s)
07-26 15:20:57.197  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:57.198  3531  3589 D BluetoothAdapter: enable(): BT is already enabled..!
07-26 15:20:57.198   792  1297 D WifiService: setWifiEnabled: true pid=3531, uid=10000
07-26 15:20:57.198   792  1297 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:20:57.199  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:57.199  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f505288 added. We now have 3 listener(s)
07-26 15:20:57.199  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:57.202  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:57.202  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b88c421 added. We now have 4 listener(s)
07-26 15:20:57.202  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:57.212  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:20:57.212  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@783c046 added. We now have 5 listener(s)
07-26 15:20:57.212  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:20:57.213   792  1334 D WifiService: setWifiEnabled: false pid=3531, uid=10000
07-26 15:20:57.214   792  1334 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:20:57.216   792   897 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 15:20:57.217   792   897 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-26 15:20:57.217   792   897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:20:57.217   792   897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:20:57.220  1959  2047 D BluetoothAdapterState: Current state: ON, message: 23
07-26 15:20:57.220  1959  2047 D BluetoothAdapterProperties: Setting state to 13
07-26 15:20:57.220  1959  2047 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:20:57.220  1959  2047 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:20:57.220  1959  2047 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:20:57.221  1959  1959 D BluetoothMapService: onReceive
07-26 15:20:57.221  1959  1959 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:20:57.221  1959  1959 D BluetoothMapService: STATE_TURNING_OFF
07-26 15:20:57.221  1959  1959 D BluetoothMapService: MAP Service closeService in
07-26 15:20:57.221  1959  1959 D BluetoothMapMasInstance0: MAP Service shutdown
07-26 15:20:57.221  1959  1959 D ObexServerSockets0: shutdown(block = true)
07-26 15:20:57.221  1959  2281 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-26 15:20:57.222  1959  1959 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:20:57.222  1959  1959 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:20:57.222  1959  2282 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-26 15:20:57.223  1959  2234 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 15:20:57.223  1959  1959 I BtOppRfcommListener: stopping Accept Thread
07-26 15:20:57.223  1959  2722 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:20:57.224  1959  2722 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:20:57.224   792   897 E native  : do suspend true
07-26 15:20:57.226  3609  3619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-26 15:20:57.232  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.232  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:57.233  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.233  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.235   792   808 I ActivityManager: Start proc 3660:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-26 15:20:57.235  1959  2054 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:57.236  1959  2047 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-26 15:20:57.239  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:57.240  1959  1959 D HeadsetService: Received stop request...Stopping profile...
07-26 15:20:57.242  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.243  1299  1327 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:57.244   792   792 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:57.244   792   792 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:57.244   947   961 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:57.244   792   792 D BluetoothHeadset: Proxy object disconnected
07-26 15:20:57.244   792  2786 D DhcpClient: Clearing IP address
07-26 15:20:57.245   194   648 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:20:57.245  1959  1959 D A2dpService: Received stop request...Stopping profile...
07-26 15:20:57.246  1959  2251 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:20:57.247  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.247  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:57.247   792   792 D BluetoothA2dp: Proxy object disconnected
07-26 15:20:57.247  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.247  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.247   194   648 D CommandListener: Setting iface cfg
07-26 15:20:57.248  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:57.248  1959  1959 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:57.248  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.248  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.248  1959  1959 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:57.249  1959  1959 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:20:57.249  1959  1959 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:20:57.249  1959  2054 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-26 15:20:57.249  1959  2208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:57.249  1959  2208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:57.249  1959  2054 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-26 15:20:57.250  1959  1959 D HidService: Received stop request...Stopping profile...
07-26 15:20:57.250  1959  1959 D HidService: Stopping Bluetooth HidService
07-26 15:20:57.251  1959  1959 D HealthService: Received stop request...Stopping profile...
07-26 15:20:57.251   947   947 D HeadsetProfile: Bluetooth service disconnected
07-26 15:20:57.251   947   947 D BluetoothA2dp: Proxy object disconnected
07-26 15:20:57.252   947   947 D BluetoothInputDevice: Proxy object disconnected
07-26 15:20:57.252   947   947 D HidProfile: Bluetooth service disconnected
07-26 15:20:57.253  1959  1959 D PanService: Received stop request...Stopping profile...
07-26 15:20:57.253  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.254   792   897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:20:57.254   792   899 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-26 15:20:57.254   792   899 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-26 15:20:57.256  1959  1959 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:57.256  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.256  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.256  1959  1959 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:57.257  1959  2054 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-26 15:20:57.257  1959  2208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:57.257  1959  2208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:57.257  1959  2208 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:20:57.257  1959  2208 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:20:57.257  1959  2208 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:20:57.257  1959  2208 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:20:57.257  1959  1959 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:20:57.257  1959  1959 D BluetoothMapService: stop()
07-26 15:20:57.261   947   947 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:20:57.261   947   947 D PanProfile: Bluetooth service disconnected
07-26 15:20:57.261   792   899 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-26 15:20:57.262  1959  1959 D BluetoothMapAppObserver: deinitObservers()
07-26 15:20:57.262  1959  1959 D BluetoothMapAppObserver: removeReceiver()
07-26 15:20:57.265  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.265  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:57.268   792   792 D RttService: SCAN_AVAILABLE : 1
07-26 15:20:57.268   792   911 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:20:57.268   947   947 D BluetoothMap: Proxy object disconnected
07-26 15:20:57.268   947   947 D MapProfile: Bluetooth service disconnected
07-26 15:20:57.269  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.269  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:57.271  1959  1959 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:57.271  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.271  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.271  1959  1959 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:57.271   792  2787 D DhcpClient: Receive thread stopped
07-26 15:20:57.271  1959  1959 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:20:57.271  1959  1959 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:20:57.271  1959  1959 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:57.271  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.272  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.272  1959  1959 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:57.272  1959  1959 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:20:57.272  1959  2054 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:20:57.272  1959  2054 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-26 15:20:57.272  1959  1959 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:20:57.272  1959  1959 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:57.272  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.272  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.272  1959  1959 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:57.272  1959  1959 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 15:20:57.272  1959  1959 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:20:57.273  1959  1959 D BluetoothMapService: MAP Service closeService in
07-26 15:20:57.273  1959  1959 V BluetoothAdapterState: isTurningOff()=true
07-26 15:20:57.273  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.273  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.273  1959  1959 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:20:57.273  1959  1959 D BluetoothMapService: cleanup()
07-26 15:20:57.273  1959  1959 D BluetoothMapService: MAP Service closeService in
07-26 15:20:57.273  1959  2047 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-26 15:20:57.274  1959  2047 D BluetoothAdapterProperties: Setting state to 15
07-26 15:20:57.274  1959  2047 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-26 15:20:57.274  1959  2047 I BluetoothAdapterState: Entering BleOnState
07-26 15:20:57.281   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:57.281   947  1650 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:20:57.282  1299  1402 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:57.283   947   960 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:57.283   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:57.283   792   812 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:20:57.283   947  1649 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:57.291   947   961 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:20:57.294   194   648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 15:20:57.299  1744  3114 V NativeCrypto: Read error: ssl=0x99a87c00: I/O error during system call, Connection timed out
07-26 15:20:57.301  1744  3114 V NativeCrypto: SSL shutdown failed: ssl=0x99a87c00: I/O error during system call, Broken pipe
07-26 15:20:57.301   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:20:57.302   947  1401 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:20:57.302  1744  3114 E GCM     : Wifi connection closed with errorCode 20
07-26 15:20:57.310   947  1650 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:20:57.311  1959  2047 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-26 15:20:57.311   792   897 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-26 15:20:57.311  1959  2047 D BluetoothAdapterProperties: Setting state to 16
07-26 15:20:57.311  1959  2047 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-26 15:20:57.313  1959  2047 D BluetoothAdapterProperties: onBleDisable
07-26 15:20:57.313  1959  2047 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:20:57.313  1959  2051 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-26 15:20:57.314  1959  2208 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-26 15:20:57.314  1959  2208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:20:57.315   792   897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:20:57.315   792   897 E native  : do suspend true
07-26 15:20:57.315  1959  2054 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:20:57.320  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:57.320  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:57.320  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.320  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:57.322  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:57.322  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.323  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.346   194   648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-26 15:20:57.346   194   648 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:20:57.346   792   899 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-26 15:20:57.346   792   899 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:20:57.347   792   897 D DhcpClient: doQuit
07-26 15:20:57.347   792   897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-26 15:20:57.348   792  2786 D DhcpClient: onQuitting
07-26 15:20:57.349   792   812 D Tethering: MasterInitialState.processMessage what=3
07-26 15:20:57.354  1423  1423 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-26 15:20:57.354  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:57.354  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:57.355  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.355  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:57.357  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:20:57.357  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:20:57.358  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:20:57.358  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:20:57.361  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.368  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.388  3660  3660 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-26 15:20:57.396  3660  3660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:20:57.402   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bc6167c:true
,07-26 15:20:57.414  3660  3660 D LocalBluetoothProfileManager: Adding local MAP profile
07-26 15:20:57.416  3660  3660 D BluetoothMap: Create BluetoothMap proxy object
07-26 15:20:57.417   194   648 E Netd    : netlink response contains error (No such file or directory)
07-26 15:20:57.418  1959  2054 I bt_hci  : shut_down
07-26 15:20:57.418  1959  2074 D bt_hwcfg: hw_epilog_process
07-26 15:20:57.421  1420  1420 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-26 15:20:57.422  1959  2074 I bt_vendor: low_power_mode_cb
07-26 15:20:57.423  3660  3660 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-26 15:20:57.427  3660  3660 D DockEventReceiver: finishStartingService: stopping service
07-26 15:20:57.431  1744  3608 W GLSUser : [AppCertManager] IOException while requesting key: 
07-26 15:20:57.431  1744  3608 W GLSUser : java.net.ConnectException: failed to connect to android.clients.google.com/172.217.21.46 (port 443) after 30000ms: connect failed: ENETUNREACH (Network is unreachable)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at java.net.Socket.connect(Socket.java:884)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:79)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at dal.a(:com.google.android.gms:233)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at dpb.a(:com.google.android.gms:263)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at dpb.a(:com.google.android.gms:4235)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at dpa.a(:com.google.android.gms:47)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at dou.a(:com.google.android.gms:55)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at dot.a(:com.google.android.gms:113)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.a(:com.google.android.gms:3054)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at nzi.run(:com.google.android.gms:179)
07-26 15:20:57.431  1744  3608 W GLSUser : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at libcore.io.Posix.connect(Native Method)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
07-26 15:20:57.431  1744  3608 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
07-26 15:20:57.431  1744  3608 W GLSUser : 	... 29 more
07-26 15:20:57.434  1420  1420 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-26 15:20:57.436   792   898 D WifiService: New client listening to asynchronous messages
07-26 15:20:57.439  1959  2074 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-26 15:20:57.439  1959  2074 I bt_vendor: epilog_cb
07-26 15:20:57.439  1959  2074 I bt_hci  : epilog_finished_callback
07-26 15:20:57.442  1959  2054 I bt_hci_h4: hal_close
07-26 15:20:57.442  1959  2054 I bt_userial_vendor: device fd = 49 close
,07-26 15:20:57.446  1420  1420 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-26 15:20:57.448  1959  2051 D bt_stack_manager: event_shut_down_stack finished.
,07-26 15:20:57.449  1959  2047 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-26 15:20:57.450  1959  1959 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:20:57.450  1959  2047 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-26 15:20:57.450  1959  1959 D BtGatt.GattService: Received stop request...Stopping profile...
,07-26 15:20:57.450  1959  1959 D BtGatt.GattService: stop()
07-26 15:20:57.450  1959  1959 D BtGatt.AdvertiseManager: advertise clients cleared
,07-26 15:20:57.451  1959  1959 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:20:57.451  1959  1959 V BluetoothAdapterState: isTurningOn()=false
07-26 15:20:57.451  1959  1959 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:20:57.451  1959  1959 V BluetoothAdapterState: isBleTurningOff()=true
07-26 15:20:57.451  1959  2047 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-26 15:20:57.452  1959  2047 D BluetoothAdapterProperties: Setting state to 10
07-26 15:20:57.452  1959  2047 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 15:20:57.452  1959  2047 I BluetoothAdapterState: Entering OffState
,07-26 15:20:57.452   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-26 15:20:57.465   792  1208 I ActivityManager: Start proc 3690:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-26 15:20:57.468  1959  1959 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-26 15:20:57.468  1959  1959 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-26 15:20:57.468  1959  1959 I BluetoothServiceJni: cleanupNative: return from cleanup
07-26 15:20:57.469  1959  2051 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-26 15:20:57.471  1959  1959 I art     : System.exit called, status: 0
07-26 15:20:57.471  1959  1959 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 15:20:57.475  1744  1791 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-26 15:20:57.477  1744  1791 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-26 15:20:57.483  1744  1791 V BaseAppContext: GmsRequestQueue started.
,07-26 15:20:57.503  1420  1420 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-26 15:20:57.511   792  1297 I ActivityManager: Process com.android.bluetooth (pid 1959) has died
,07-26 15:20:57.512  1420  1420 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-26 15:20:57.535   792  1208 I ActivityManager: Killing 2188:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-26 15:20:57.564  1744  1744 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
,07-26 15:20:57.602  1660  1802 V UdcCtxListenerSrv: handle intent
,07-26 15:20:57.606  1744  1791 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-26 15:20:57.614   792   897 D wifi    : In wifi stop Hal
07-26 15:20:57.614   792   897 D wifi    : halHandle = 0xaecebc50, mVM = 0xb4cfc000, mCls = 0x100c9a
07-26 15:20:57.614   792  1419 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-26 15:20:57.614   792  1419 D WifiHAL : Got a signal to exit!!!
07-26 15:20:57.614   792  1419 I WifiHAL : Exit wifi_event_loop
07-26 15:20:57.614   792   897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-26 15:20:57.614   792   897 E WifiHAL : Event processing terminated
07-26 15:20:57.614   792   897 D wifi    : In wifi cleaned up handler
07-26 15:20:57.614   792   897 I WifiHAL : Internal cleanup completed
07-26 15:20:57.614  2259  2259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:20:57.615  1744  1820 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:20:57.616  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:57.616  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:57.678  3690  3690 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at java.io.File.exists(File.java:361)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:20:57.678  3690  3690 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.678  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:20:57.679  3690  3690 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:20:57.679  3690  3690 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.e.b(PG:170)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-26 15:20:57.679  3690  3690 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.k.d(PG:583)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.e.b(PG:170)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:20:57.679  3690  3690 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.File.exists(File.java:361)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-26 15:20:57.679  3690  3690 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.File.exists(File.java:361)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.679,  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-26 15:20:57.679  3690  3690 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:20:57.679  3690  3690 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-26 15:20:57.681   792  1297 I ActivityManager: Killing 3071:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,07-26 15:20:57.715  3690  3715 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-26 15:20:57.722   792  1419 D wifi    : set interface wlan0 flags (DOWN)
,07-26 15:20:57.722   792   897 D WifiNative-HAL: HAL event thread stopped successfully
,07-26 15:20:57.723   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e39dd6:true
,07-26 15:20:57.734  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:57.737  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:57.750  3660  3660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:20:57.763   792  1320 I ActivityManager: Start proc 3728:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-26 15:20:57.764  3660  3660 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:20:57.808  3728  3728 D AdapterServiceConfig: Adding HeadsetService
07-26 15:20:57.808  3728  3728 D AdapterServiceConfig: Adding A2dpService
07-26 15:20:57.809  3728  3728 D AdapterServiceConfig: Adding HidService
07-26 15:20:57.809  3728  3728 D AdapterServiceConfig: Adding HealthService
07-26 15:20:57.809  3728  3728 D AdapterServiceConfig: Adding PanService
07-26 15:20:57.809  3728  3728 D AdapterServiceConfig: Adding GattService
07-26 15:20:57.809  3728  3728 D AdapterServiceConfig: Adding BluetoothMapService
,07-26 15:20:57.819   792  1546 I ActivityManager: Killing 2521:com.google.android.deskclock/u0a38 (adj 15): empty #17
,07-26 15:20:57.925   792   812 D Tethering: InitialState.processMessage what=4
,07-26 15:20:57.928  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:20:57.928   792   812 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-26 15:20:57.933  1744  3740 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:20:57.935  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:20:57.954   792  1208 I ActivityManager: Start proc 3741:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-26 15:20:57.961  1744  3740 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-26 15:20:58.062  2259  3757 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-26 15:20:58.079   792  1304 I ActivityManager: Start proc 3761:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-26 15:20:58.130  3761  3761 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-26 15:20:58.274   792  1208 I ActivityManager: Killing 2058:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-26 15:20:58.348  1660  1660 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-26 15:20:58.350  1660  2969 I iu.UploadsManager: num queued entries: 0
07-26 15:20:58.353  1660  2969 I iu.UploadsManager: num updated entries: 0
07-26 15:20:58.356  1660  2969 I iu.SyncManager: NEXT; no task
,07-26 15:20:58.371   792  1208 I ActivityManager: Start proc 3776:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-26 15:20:58.423  3776  3776 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-26 15:20:58.486  3776  3776 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-26 15:20:58.486  3776  3776 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-26 15:20:58.486  3776  3776 I GAv4    :   adb logcat -s GAv4
,07-26 15:20:58.494  3776  3776 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:20:58.497  3776  3776 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:20:58.502  3776  3794 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:20:58.601  3776  3776 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-26 15:20:58.633  3776  3776 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7099-7101)
,07-26 15:20:58.633  3776  3776 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:20:58.640  3776  3776 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4c16941}
07-26 15:20:58.640  3776  3776 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:58.640  3776  3776 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 15:20:58.646  3776  3776 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-26 15:20:58.647  3776  3776 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-26 15:20:58.656  3776  3776 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-26 15:20:58.660  3776  3776 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:58.660  3776  3776 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:58.661  3776  3776 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:20:58.696  3776  3822 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-26 15:20:58.705  3776  3776 I NSApplication: Starting up...
,07-26 15:20:58.714   792  1320 I ActivityManager: Killing 3229:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-26 15:20:58.751   792   802 I ActivityManager: Start proc 3827:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-26 15:20:58.771  3827  3827 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-26 15:20:58.798  3827  3827 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-26 15:20:58.801   792  1548 I ActivityManager: Killing 3413:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-26 15:20:59.627  1744  1791 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-26 15:20:59.628  1744  1791 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-26 15:21:00.249   792   802 D WifiService: setWifiEnabled: true pid=3531, uid=10000
,07-26 15:21:00.249   792   802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:21:00.257   194   648 D SoftapController: Softap fwReload - Ok
,07-26 15:21:00.260   194   648 D CommandListener: Setting iface cfg
,07-26 15:21:00.260   194   648 D CommandListener: Trying to bring down wlan0
,07-26 15:21:00.260   194   648 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:00.263   792   897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-26 15:21:01.021   792   897 D wifi    : set interface wlan0 flags (UP)
,07-26 15:21:01.021   792   897 I WifiHAL : Initializing wifi
07-26 15:21:01.021   792   897 I WifiHAL : Creating socket
,07-26 15:21:01.023   792   812 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-26 15:21:01.024   792   897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-26 15:21:01.024   792   897 D wifi    : Did set static halHandle = 0xaecebc50
07-26 15:21:01.024   792   897 D wifi    : halHandle = 0xaecebc50, mVM = 0xb4cfc000, mCls = 0x201626
07-26 15:21:01.024   792   897 D wifi    : array field set
07-26 15:21:01.024   792   897 I WifiNative-HAL: interface[0] = p2p0
07-26 15:21:01.024   792   897 I WifiNative-HAL: interface[1] = wlan0
07-26 15:21:01.026   792  3865 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1362183088
07-26 15:21:01.026   792  3865 D wifi    : waitForHalEvents called, vm = 0xb4cfc000, obj = 0x201626, env = 0x95cea640
,07-26 15:21:01.028   792   897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-26 15:21:01.028   792   897 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-26 15:21:01.030  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:01.031  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:01.060  3866  3866 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:21:01.098  3866  3866 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:01.107  3866  3866 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:02.067  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:02.068  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:02.068  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:21:02.068  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:02.071  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:02.071  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:02.071  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:02.071  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:02.083   792   897 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:21:02.093   792   897 D WifiConfigStore: loaded 0 passpoint configs
07-26 15:21:02.094   792   897 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:21:02.094   792   897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-26 15:21:02.094   792   897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-26 15:21:02.095   792   897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:21:02.095   792   897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-26 15:21:02.095   792   897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-26 15:21:02.095   792   897 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-26 15:21:02.097   792   897 D WifiNative-HAL: Setting external_sim to 1
07-26 15:21:02.098   792   897 D wifi    : setting dfs flag to true, 0x9ad63ec8
07-26 15:21:02.098   792   897 D WifiStateMachine: Setting OUI to DA-A1-19
,07-26 15:21:02.098   792   897 D wifi    : setting scan oui 0x9ad63ec8
07-26 15:21:02.098   792   897 D WifiHAL : Sending mac address OUI
07-26 15:21:02.099  2259  2259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:02.119   792   897 E native  : do suspend true
,07-26 15:21:02.123   792   897 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-26 15:21:02.123   792   897 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-26 15:21:02.123   792   792 D RttService: SCAN_AVAILABLE : 3
07-26 15:21:02.124   792   911 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:02.124   194   648 D CommandListener: Setting iface cfg
07-26 15:21:02.124   194   648 D CommandListener: Trying to bring up p2p0
07-26 15:21:02.124   792   896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-26 15:21:02.132   792   896 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 15:21:02.133   792   896 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-26 15:21:02.420   792  1334 I ActivityManager: Killing 3437:com.android.musicfx/u0a15 (adj 15): empty #17
,07-26 15:21:02.965   792  1548 I ActivityManager: Killing 1423:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,07-26 15:21:02.981   792   898 D WifiService: Client connection lost with reason: 4
,07-26 15:21:03.252   792   957 D WifiService: setWifiEnabled: false pid=3531, uid=10000
,07-26 15:21:03.252   792   957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:21:03.258   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:21:03.278   792   792 D RttService: SCAN_AVAILABLE : 1
,07-26 15:21:03.279   792   911 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:03.299   792   897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:21:03.300   194   648 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:03.318   792   897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-26 15:21:03.321  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:03.321  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:03.321  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:21:03.321  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:03.322  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:03.322  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:03.322  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:03.322  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:03.333  3866  3866 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-26 15:21:04.342  3866  3866 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-26 15:21:04.353  3866  3866 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-26 15:21:04.367  3866  3866 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-26 15:21:04.474   792   897 D wifi    : In wifi stop Hal
,07-26 15:21:04.474   792   897 D wifi    : halHandle = 0xaecebc50, mVM = 0xb4cfc000, mCls = 0x201626
07-26 15:21:04.475   792  3865 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-26 15:21:04.475   792  3865 D WifiHAL : Got a signal to exit!!!
07-26 15:21:04.475   792  3865 I WifiHAL : Exit wifi_event_loop
07-26 15:21:04.493  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:04.495  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:04.496  1744  1820 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:04.500   792   897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-26 15:21:04.500   792   897 E WifiHAL : Event processing terminated
07-26 15:21:04.500   792   897 D wifi    : In wifi cleaned up handler
07-26 15:21:04.501   792   897 I WifiHAL : Internal cleanup completed
,07-26 15:21:04.511  2259  2259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:04.623   792  3865 D wifi    : set interface wlan0 flags (DOWN)
07-26 15:21:04.623   792   897 D WifiNative-HAL: HAL event thread stopped successfully
,07-26 15:21:04.825   792   812 D Tethering: InitialState.processMessage what=4
,07-26 15:21:04.826   792   812 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-26 15:21:06.318   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@94f658:true
,07-26 15:21:06.318  3728  3728 D BluetoothAdapterState: make() - Creating AdapterState
07-26 15:21:06.322  3728  3728 I bt_bluedroid: init
07-26 15:21:06.323  3728  3903 I BluetoothAdapterState: Entering OffState
07-26 15:21:06.324  3728  3904 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-26 15:21:06.324  3728  3904 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:21:06.324  3728  3904 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:21:06.324  3728  3904 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-26 15:21:06.324  3728  3728 I bt_bluedroid: get_profile_interface socket
07-26 15:21:06.325  3728  3728 I bt_bluedroid: get_profile_interface sdp
07-26 15:21:06.326  3728  3739 I bt_bluedroid: config_hci_snoop_log
07-26 15:21:06.327   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-26 15:21:06.329  3728  3903 D BluetoothAdapterState: Current state: OFF, message: 0
07-26 15:21:06.329  3728  3903 D BluetoothAdapterProperties: Setting state to 14
07-26 15:21:06.329  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-26 15:21:06.330  3728  3903 D BluetoothBondStateMachine: make
07-26 15:21:06.332  3728  3907 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-26 15:21:06.332  3728  3907 D BluetoothAdapterProperties: Name is: Nexus 5
07-26 15:21:06.335  3728  3728 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-26 15:21:06.337  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
,07-26 15:21:06.337  3728  3903 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:21:06.337  3728  3728 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:21:06.338  3728  3728 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:21:06.338  3728  3728 D BtGatt.GattService: start()
07-26 15:21:06.338  3728  3728 I bt_bluedroid: get_profile_interface gatt
07-26 15:21:06.338  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:06.338  3728  3728 D BtGatt.AdvertiseManager: advertise manager created
07-26 15:21:06.339  3728  3908 I BluetoothBondStateMachine: StableState(): Entering Off State
07-26 15:21:06.341  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:06.341  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:06.341  3728  3728 V BluetoothAdapterState: isBleTurningOn()=true
07-26 15:21:06.342  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:06.342  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-26 15:21:06.342  3728  3903 I bt_bluedroid: enable
07-26 15:21:06.342  3728  3904 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-26 15:21:06.342  3728  3904 I bt_hci  : start_up
07-26 15:21:06.346  3728  3904 I bt_vendor: alloc value 0xb3979631
07-26 15:21:06.346  3728  3904 I bt_vendor: init
07-26 15:21:06.346  3728  3904 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-26 15:21:06.346  3728  3904 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-26 15:21:06.381  3728  3904 D bt_hci  : start_up starting async portion
,07-26 15:21:06.382  3728  3911 I bt_hci  : event_finish_startup
07-26 15:21:06.382  3728  3911 I bt_hci_h4: hal_open
07-26 15:21:06.382  3728  3911 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-26 15:21:06.385  3728  3911 I bt_userial_vendor: device fd = 49 open
,07-26 15:21:06.471  3728  3911 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:21:06.498  3728  3911 D bt_hwcfg: Chipset BCM4335C0
,07-26 15:21:06.498  3728  3911 D bt_hwcfg: Target name = [BCM4335C0]
07-26 15:21:06.498  3728  3911 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-26 15:21:06.955  3728  3911 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-26 15:21:06.956  3728  3911 D bt_hwcfg: Settlement delay -- 100 ms
07-26 15:21:06.956  3728  3911 I bt_hwcfg: Setting fw settlement delay to 100 
,07-26 15:21:07.073  3728  3911 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:21:07.074  3728  3911 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-26 15:21:07.101  3728  3911 I bt_hwcfg: vendor lib fwcfg completed
,07-26 15:21:07.101  3728  3911 I bt_vendor: firmware callback
07-26 15:21:07.101  3728  3911 I bt_hci  : firmware_config_callback
,07-26 15:21:07.114  3728  3913 I bt_btu  : btu_task pending for preload complete event
,07-26 15:21:07.114  3728  3913 I bt_btu_task: Bluetooth chip preload is complete
,07-26 15:21:07.114  3728  3913 I bt_btu  : btu_task received preload complete event
,07-26 15:21:07.123  3728  3913 I         : BTE_InitTraceLevels -- TRC_HCI
07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_AVRC
07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_A2D
,07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_BTM
,07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_GAP
,07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_PAN
07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:21:07.124  3728  3913 I         : BTE_InitTraceLevels -- TRC_GATT
07-26 15:21:07.125  3728  3913 I         : BTE_InitTraceLevels -- TRC_SMP
07-26 15:21:07.125  3728  3913 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:21:07.125  3728  3913 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-26 15:21:07.346  3728  3913 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f79b5
,07-26 15:21:07.346  3728  3913 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f79b5 
,07-26 15:21:07.442  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-26 15:21:07.443  3728  3907 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-26 15:21:07.481  3728  3907 D BluetoothAdapterProperties: Name is: Nexus 5
07-26 15:21:07.482  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:07.483  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:07.483  3728  3907 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:07.483  3728  3907 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:07.483  3728  3907 D bt_hci  : do_postload posting postload work item
07-26 15:21:07.483  3728  3911 I bt_hci  : event_postload
07-26 15:21:07.483  3728  3911 I bt_vendor: sco_config_cb
07-26 15:21:07.483  3728  3911 I bt_hci  : sco_config_callback postload finished.
07-26 15:21:07.501  3728  3911 I bt_vendor: low_power_mode_cb
07-26 15:21:07.511  3728  3907 D bt_bte_conf: Device ID record 1 : primary
07-26 15:21:07.511  3728  3907 D bt_bte_conf:   vendorId            = 000f
07-26 15:21:07.511  3728  3907 D bt_bte_conf:   vendorIdSource      = 0001
07-26 15:21:07.511  3728  3907 D bt_bte_conf:   product             = 1200
07-26 15:21:07.511  3728  3907 D bt_bte_conf:   version             = 1436
,07-26 15:21:07.511  3728  3907 D bt_bte_conf:   clientExecutableURL = 
07-26 15:21:07.511  3728  3907 D bt_bte_conf:   serviceDescription  = 
07-26 15:21:07.511  3728  3907 D bt_bte_conf:   documentationURL    = 
07-26 15:21:07.531  3728  3907 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-26 15:21:07.531  3728  3904 D bt_stack_manager: event_start_up_stack finished
,07-26 15:21:07.531  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-26 15:21:07.531  3728  3903 D BluetoothAdapterProperties: Setting state to 15
,07-26 15:21:07.531  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-26 15:21:07.533  3728  3903 I BluetoothAdapterState: Entering BleOnState
,07-26 15:21:07.533  3728  3903 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-26 15:21:07.533  3728  3903 D BluetoothAdapterProperties: Setting state to 11
,07-26 15:21:07.533  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-26 15:21:07.535  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
,07-26 15:21:07.541  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:07.543  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:07.547  3728  3728 D HeadsetService: Received start request. Starting profile...
07-26 15:21:07.548  3728  3728 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:21:07.548  3728  3728 D HeadsetStateMachine: make
07-26 15:21:07.552  3728  3903 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:21:07.562  3728  3728 D HeadsetStateMachine: max_hf_connections = 1
,07-26 15:21:07.562  3728  3728 I bt_bluedroid: get_profile_interface handsfree
,07-26 15:21:07.567  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-26 15:21:07.567  3728  3907 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-26 15:21:07.569  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:07.570  3728  3728 D A2dpService: Received start request. Starting profile...
07-26 15:21:07.570  3728  3728 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-26 15:21:07.570  3728  3728 I bt_bluedroid: get_profile_interface avrcp
07-26 15:21:07.574  3728  3728 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-26 15:21:07.574  3728  3728 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:21:07.574  3728  3728 D A2dpStateMachine: make
07-26 15:21:07.575  3728  3728 I bt_bluedroid: get_profile_interface a2dp
,07-26 15:21:07.578  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-26 15:21:07.582  3728  3728 I BluetoothHidServiceJni: classInitNative: succeeds
07-26 15:21:07.583  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:07.583  3728  3928 D A2dpStateMachine: Enter Disconnected: -2
07-26 15:21:07.584  3728  3728 D HidService: Received start request. Starting profile...
07-26 15:21:07.584  3728  3728 I bt_bluedroid: get_profile_interface hidhost
,07-26 15:21:07.584  3728  3907 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d9099
07-26 15:21:07.584  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-26 15:21:07.584  3728  3728 D HidService: setHidService(): set to: null
07-26 15:21:07.585  3728  3728 I BluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:21:07.585  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:07.586  3728  3728 D HealthService: Received start request. Starting profile...
,07-26 15:21:07.586  3660  3660 D BluetoothInputDevice: Proxy object connected
07-26 15:21:07.586  3660  3660 D HidProfile: Bluetooth service connected
07-26 15:21:07.587  3728  3728 I bt_bluedroid: get_profile_interface health
07-26 15:21:07.588  3728  3728 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-26 15:21:07.589  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:07.590  3728  3728 D PanService: Received start request. Starting profile...
07-26 15:21:07.590  3728  3728 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:21:07.590  3728  3728 I bt_bluedroid: get_profile_interface pan
07-26 15:21:07.590  3728  3907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-26 15:21:07.592  3728  3728 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
,07-26 15:21:07.593  3728  3728 D BluetoothMapService: Received start request. Starting profile...
,07-26 15:21:07.593  3728  3728 D BluetoothMapService: start()
07-26 15:21:07.594  3728  3728 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-26 15:21:07.594  3728  3728 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-26 15:21:07.594  3728  3728 D BluetoothMapAppObserver: createReceiver()
07-26 15:21:07.595  3728  3728 D BluetoothMapAppObserver: initObservers()
07-26 15:21:07.595  3728  3728 D BluetoothMapAppObserver: getEnabledAccountItems()
07-26 15:21:07.599  3660  3660 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:07.599  3660  3660 D PanProfile: Bluetooth service connected
07-26 15:21:07.599  3660  3660 D BluetoothMap: Proxy object connected
07-26 15:21:07.599  3660  3660 D MapProfile: Bluetooth service connected
07-26 15:21:07.611  3728  3920 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-26 15:21:07.611  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:07.611  3728  3728 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:07.611  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:21:07.611  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:07.612  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:07.612  3728  3728 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:07.612  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:07.612  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOn()=true
,07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:07.613  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:07.613  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-26 15:21:07.613  3728  3903 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:21:07.613  3728  3903 D BluetoothAdapterProperties: State =  11
07-26 15:21:07.614  3728  3903 D BluetoothAdapterProperties: Setting state to 12
,07-26 15:21:07.614  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-26 15:21:07.614   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:07.615   947  1650 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:21:07.616  3531  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:21:07.618  3728  3907 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:21:07.618  3728  3907 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:07.620   947   947 D BluetoothInputDevice: Proxy object connected
07-26 15:21:07.620   947   947 D HidProfile: Bluetooth service connected
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:07.621  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:07.622  3728  3903 I BluetoothAdapterState: Entering OnState
07-26 15:21:07.623  3660  3672 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:21:07.624  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:07.625  1299  1472 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:21:07.625   947   960 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:07.626  3728  3728 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:21:07.627  3728  3728 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-26 15:21:07.627   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:07.627   792   812 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:07.628  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:07.629   947   961 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:07.629  3728  3728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:07.629  3660  3674 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:07.630  3660  3660 D BluetoothMap: getConnectedDevices()
07-26 15:21:07.631  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:07.632  3728  3728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:07.635  3728  3728 D ObexServerSockets: Succeed to create listening sockets 
07-26 15:21:07.635   947  1401 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:07.635  3728  3728 D ObexServerSockets0: startAccept()
07-26 15:21:07.635  3728  3728 D ObexServerSockets0: prepareForNewConnect()
07-26 15:21:07.636   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:21:07.636  3728  3728 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-26 15:21:07.636  3728  3728 D BluetoothSdpJni: SDP Create record success - handle: 0
07-26 15:21:07.637   947  1649 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:07.637   792   792 D BluetoothA2dp: Proxy object connected
07-26 15:21:07.638   947   947 D BluetoothA2dp: Proxy object connected
07-26 15:21:07.639  3660  3672 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:21:07.640  3660  3674 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:07.640   947   947 D BluetoothMap: Proxy object connected
07-26 15:21:07.640   947   947 D MapProfile: Bluetooth service connected
07-26 15:21:07.640   947   947 D BluetoothMap: getConnectedDevices()
07-26 15:21:07.641   947  1401 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:21:07.644   947   947 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:07.644   947   947 D PanProfile: Bluetooth service connected
07-26 15:21:07.648  3728  3728 D BluetoothMapService: onReceive
07-26 15:21:07.648  3728  3728 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:07.648  3728  3728 D BluetoothMapService: STATE_ON
07-26 15:21:07.649  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:07.649   792   792 I Telecom : BluetoothPhoneService: queryPhoneState
07-26 15:21:07.650  3728  3947 D ObexServerSockets0: Accepting socket connection...
07-26 15:21:07.650  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:07.651  3728  3946 D ObexServerSockets0: Accepting socket connection...
07-26 15:21:07.669  3728  3728 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-26 15:21:07.669  3728  3728 D ObexServerSockets0: prepareForNewConnect()
07-26 15:21:07.673  3660  3660 D LocalBluetoothProfileManager: Adding local A2DP profile
07-26 15:21:07.675  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:07.678  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-26 15:21:07.681  3660  3660 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-26 15:21:07.690  3660  3660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:21:07.691  3660  3660 D BluetoothA2dp: Proxy object connected
,07-26 15:21:07.697  3660  3660 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:07.700   947   947 D BluetoothPbap: Proxy object connected
,07-26 15:21:07.700   947   947 D PbapServerProfile: Bluetooth service connected
,07-26 15:21:07.703  3728  3956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:07.704  3660  3660 D BluetoothPbap: Proxy object connected
,07-26 15:21:07.704  3660  3660 D PbapServerProfile: Bluetooth service connected
,07-26 15:21:07.717  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:07.720  1744  3959 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:21:07.722  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:21:07.727  1299  1317 D BluetoothHeadset: Proxy object connected
,07-26 15:21:07.727   792   792 D BluetoothHeadset: Proxy object connected
,07-26 15:21:07.727   792   792 D BluetoothHeadset: Proxy object connected
07-26 15:21:07.728   947   960 D BluetoothHeadset: Proxy object connected
07-26 15:21:07.728   792   812 D BluetoothHeadset: Proxy object connected
07-26 15:21:07.728   947   947 D HeadsetProfile: Bluetooth service connected
07-26 15:21:07.728   792   792 D BluetoothHeadset: Proxy object connected
07-26 15:21:07.729   947  1649 D BluetoothHeadset: Proxy object connected
,07-26 15:21:07.731   947   947 D HeadsetProfile: Bluetooth service connected
07-26 15:21:07.732  3728  3963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:07.734  3728  3963 I BtOppRfcommListener: Accept thread started.
,07-26 15:21:07.735  1744  3959 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-26 15:21:07.737   792   812 D BluetoothHeadset: Proxy object connected
,07-26 15:21:07.783  3660  3672 D BluetoothHeadset: Proxy object connected
07-26 15:21:07.784  3660  3660 D HeadsetProfile: Bluetooth service connected
,07-26 15:21:09.278  3728  3903 D BluetoothAdapterState: Current state: ON, message: 23
07-26 15:21:09.278  3728  3903 D BluetoothAdapterProperties: Setting state to 13
07-26 15:21:09.278  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-26 15:21:09.279  3728  3903 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:21:09.334  3728  3903 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:21:09.351  3728  3728 D BluetoothMapService: onReceive
07-26 15:21:09.351  3728  3728 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.351  3728  3728 D BluetoothMapService: STATE_TURNING_OFF
07-26 15:21:09.351  3728  3728 D BluetoothMapService: MAP Service closeService in
07-26 15:21:09.351  3728  3728 D BluetoothMapMasInstance0: MAP Service shutdown
07-26 15:21:09.351  3728  3728 D ObexServerSockets0: shutdown(block = true)
07-26 15:21:09.351  3728  3728 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:21:09.351  3728  3728 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:21:09.351  3728  3946 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-26 15:21:09.352  3728  3916 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 15:21:09.352  3728  3947 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-26 15:21:09.353  3728  3907 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:09.353  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:09.353  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:09.354  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.354  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:09.355  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:09.355  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:09.355  3531  3531 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bl,uetooth is disabled - will return stored value
07-26 15:21:09.356  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:09.356  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-26 15:21:09.357  3728  3728 I BtOppRfcommListener: stopping Accept Thread
07-26 15:21:09.357  3728  3963 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:09.357  3728  3963 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:21:09.358  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.359  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.363  3728  3728 D HeadsetService: Received stop request...Stopping profile...
07-26 15:21:09.365  3728  3728 V BluetoothAdapterState: isTurningOff()=true
07-26 15:21:09.365  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.365  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:09.365  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:09.366  3660  3674 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:09.367  1299  1402 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:09.367   792   792 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:09.367   792   792 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:09.367   947   961 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:09.367   947   947 D HeadsetProfile: Bluetooth service disconnected
07-26 15:21:09.367   792   792 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:09.367  3728  3728 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:21:09.367  3728  3728 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:09.368  3728  3913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:21:09.368  3728  3913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:21:09.368  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-26 15:21:09.368  3728  3907 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-26 15:21:09.395  3728  3728 D A2dpService: Received stop request...Stopping profile...
07-26 15:21:09.395  3728  3928 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:21:09.397   947   947 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:09.397  3728  3728 V BluetoothAdapterState: isTurningOff()=true
07-26 15:21:09.397  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.397  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:09.397  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:09.397   792   792 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:09.399  3728  3913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:21:09.400  3728  3913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:21:09.400  3728  3913 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:09.400  3728  3913 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:09.400  3728  3913 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:09.400  3728  3913 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:09.400  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-26 15:21:09.451  3728  3728 D HidService: Received stop request...Stopping profile...
07-26 15:21:09.451  3728  3728 D HidService: Stopping Bluetooth HidService
07-26 15:21:09.454  3728  3728 D HealthService: Received stop request...Stopping profile...
07-2,6 15:21:09.456  3728  3728 D PanService: Received stop request...Stopping profile...
07-26 15:21:09.461   947   947 D BluetoothInputDevice: Proxy object disconnected
07-26 15:21:09.461   947   947 D HidProfile: Bluetooth service disconnected
07-26 15:21:09.461   947   947 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:21:09.461   947   947 D PanProfile: Bluetooth service disconnected
07-26 15:21:09.461  3660  3660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:21:09.462  3728  3728 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:21:09.462  3728  3728 D BluetoothMapService: stop()
07-26 15:21:09.463  3728  3728 D BluetoothMapAppObserver: deinitObservers()
07-26 15:21:09.463  3728  3728 D BluetoothMapAppObserver: removeReceiver()
07-26 15:21:09.464  3660  3660 D HeadsetProfile: Bluetooth service disconnected
,07-26 15:21:09.464  3660  3660 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:09.464  3660  3660 D BluetoothInputDevice: Proxy object disconnected
07-26 15:21:09.464  3660  3660 D HidProfile: Bluetooth service disconnected
07-26 15:21:09.465  3728  3728 V BluetoothAdapterState: isTurningOff()=true
07-26 15:21:09.465  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.465  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:09.465  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:09.465  3728  3728 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-26 15:21:09.465  3728  3728 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:21:09.465  3728  3907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:21:09.466  3728  3728 V BluetoothAdapterState: isTurningOff()=true
07-26 15:21:09.466  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.466  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:09.466  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:09.466  3728  3728 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:21:09.466  3728  3907 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-26 15:21:09.466  3728  3728 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:21:09.467  3728  3728 V BluetoothAdapterState: isTurningOff()=true
07-26 15:21:09.467  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.467  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:21:09.467  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:21:09.467  3728  3728 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-26 15:21:09.467  3728  3728 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:21:09.468  3660  3660 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:21:09.468  3660  3660 D PanProfile: Bluetooth service disconnected
,07-26 15:21:09.468  3728  3728 D BluetoothMapService: MAP Service closeService in
07-26 15:21:09.468  3728  3728 V BluetoothAdapterState: isTurningOff()=true
07-26 15:21:09.468  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.468  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:09.469  3728  3728 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:21:09.469  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-26 15:21:09.469  3728  3903 D BluetoothAdapterProperties: Setting state to 15
07-26 15:21:09.469  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-26 15:21:09.469   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:09.469  3728  3728 D BluetoothMapService: cleanup()
07-26 15:21:09.469  3728  3728 D BluetoothMapService: MAP Service closeService in
07-26 15:21:09.470   947  1650 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:21:09.470  3728  3903 I BluetoothAdapterState: Entering BleOnState
07-26 15:21:09.473  3660  3660 D DockEventReceiver: finishStartingService: stopping service
07-26 15:21:09.474  3660  3672 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:21:09.474  1299  1471 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:09.474   947  1649 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:21:09.475   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:21:09.475   792   812 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:21:09.475   947  1401 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:09.475  3660  3996 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:21:09.476  3660  3674 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:21:09.476  3660  3660 D BluetoothMap: Proxy object disconnected
07-26 15:21:09.476  3660  3660 D MapProfile: Bluetooth service disconnected
,07-26 15:21:09.477   947   961 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:21:09.477   792   812 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:09.477   947   960 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:21:09.478  3660  3996 D BluetoothPan: onBluetoothStateChange on: false
,07-26 15:21:09.479  3660  3672 D BluetoothMap: onBluetoothStateChange: up=false
,07-26 15:21:09.481  3660  3674 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:21:09.481   947  1650 D BluetoothPan: onBluetoothStateChange on: false
,07-26 15:21:09.481  3728  3903 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-26 15:21:09.481  3728  3903 D BluetoothAdapterProperties: Setting state to 16
07-26 15:21:09.481  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-26 15:21:09.482  3728  3903 D BluetoothAdapterProperties: onBleDisable
07-26 15:21:09.482  3728  3903 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:21:09.482  3728  3904 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,07-26 15:21:09.483  3728  3913 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-26 15:21:09.483  3728  3913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:21:09.483  3728  3907 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:09.485  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.487  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.488  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.489  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.544  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:09.549  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:21:09.550  3660  3660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:21:09.555  3660  3660 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:09.564  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:09.567  1744  4004 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:21:09.569  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:21:09.577  1744  4004 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-26 15:21:09.585  3728  3907 I bt_hci  : shut_down
,07-26 15:21:09.585  3728  3911 D bt_hwcfg: hw_epilog_process
,07-26 15:21:09.590  3728  3911 I bt_vendor: low_power_mode_cb
,07-26 15:21:09.610  3728  3911 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-26 15:21:09.610  3728  3911 I bt_vendor: epilog_cb
07-26 15:21:09.610  3728  3911 I bt_hci  : epilog_finished_callback
,07-26 15:21:09.612  3728  3907 I bt_hci_h4: hal_close
,07-26 15:21:09.613  3728  3907 I bt_userial_vendor: device fd = 49 close
,07-26 15:21:09.618  3728  3904 D bt_stack_manager: event_shut_down_stack finished.
,07-26 15:21:09.618  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-26 15:21:09.619  3728  3903 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-26 15:21:09.619  3728  3728 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:21:09.620  3728  3728 D BtGatt.GattService: Received stop request...Stopping profile...
07-26 15:21:09.620  3728  3728 D BtGatt.GattService: stop()
,07-26 15:21:09.620  3728  3728 D BtGatt.AdvertiseManager: advertise clients cleared
,07-26 15:21:09.621  3728  3728 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:09.621  3728  3728 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:09.621  3728  3728 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:09.621  3728  3728 V BluetoothAdapterState: isBleTurningOff()=true
07-26 15:21:09.621  3728  3903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-26 15:21:09.621  3728  3903 D BluetoothAdapterProperties: Setting state to 10
07-26 15:21:09.621  3728  3903 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 15:21:09.622  3728  3903 I BluetoothAdapterState: Entering OffState
07-26 15:21:09.622   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-26 15:21:09.629  3728  3728 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-26 15:21:09.629  3728  3728 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-26 15:21:09.629  3728  3728 I BluetoothServiceJni: cleanupNative: return from cleanup
07-26 15:21:09.629  3728  3904 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-26 15:21:09.632  3728  3904 D bt_stack_manager: event_clean_up_stack finished.
,07-26 15:21:09.633  3728  3728 I art     : System.exit called, status: 0
07-26 15:21:09.633  3728  3728 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 15:21:09.681   792  1546 I ActivityManager: Process com.android.bluetooth (pid 3728) has died
,07-26 15:21:12.277  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:21:12.277  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:15.284  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:15.285  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dc0f34 added. We now have 6 listener(s)
07-26 15:21:15.285  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:15.288  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:15.288  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8c815d added. We now have 7 listener(s)
07-26 15:21:15.288  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:15.290  3531  3589 I System.out: IsBluetoothEnabled
07-26 15:21:15.300  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:15.341   792   812 I ActivityManager: Start proc 4019:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding HeadsetService
,07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding A2dpService
07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding HidService
07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding HealthService
07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding PanService
07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding GattService
07-26 15:21:15.387  4019  4019 D AdapterServiceConfig: Adding BluetoothMapService
,07-26 15:21:15.396   792   812 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@975d273:true
,07-26 15:21:15.396  4019  4019 D BluetoothAdapterState: make() - Creating AdapterState
,07-26 15:21:15.398  4019  4019 I bt_bluedroid: init
,07-26 15:21:15.399  4019  4031 I BluetoothAdapterState: Entering OffState
,07-26 15:21:15.400  4019  4032 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-26 15:21:15.400  4019  4032 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:21:15.400  4019  4032 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:21:15.400  4019  4032 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-26 15:21:15.401  4019  4019 I bt_bluedroid: get_profile_interface socket
,07-26 15:21:15.402  4019  4019 I bt_bluedroid: get_profile_interface sdp
,07-26 15:21:15.404  4019  4030 I bt_bluedroid: config_hci_snoop_log
,07-26 15:21:15.405   792   812 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-26 15:21:15.407  4019  4031 D BluetoothAdapterState: Current state: OFF, message: 0
07-26 15:21:15.407  4019  4031 D BluetoothAdapterProperties: Setting state to 14
07-26 15:21:15.407  4019  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-26 15:21:15.407  4019  4031 D BluetoothBondStateMachine: make
,07-26 15:21:15.409  4019  4035 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-26 15:21:15.410  4019  4035 D BluetoothAdapterProperties: Name is: Nexus 5
07-26 15:21:15.414  4019  4019 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-26 15:21:15.415  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:15.416  4019  4031 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:21:15.416  4019  4019 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-26 15:21:15.416  4019  4019 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:21:15.416  4019  4019 D BtGatt.GattService: start()
07-26 15:21:15.416  4019  4019 I bt_bluedroid: get_profile_interface gatt
07-26 15:21:15.417  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:15.417  4019  4019 D BtGatt.AdvertiseManager: advertise manager created
07-26 15:21:15.417  4019  4036 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-26 15:21:15.422  4019  4019 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:21:15.422  4019  4019 V BluetoothAdapterState: isTurningOn()=false
07-26 15:21:15.422  4019  4019 V BluetoothAdapterState: isBleTurningOn()=true
07-26 15:21:15.422  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:15.422  4019  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-26 15:21:15.422  4019  4031 I bt_bluedroid: enable
07-26 15:21:15.422  4019  4032 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-26 15:21:15.423  4019  4032 I bt_hci  : start_up
07-26 15:21:15.427  4019  4032 I bt_vendor: alloc value 0xb39ab631
,07-26 15:21:15.427  4019  4032 I bt_vendor: init
07-26 15:21:15.427  4019  4032 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-26 15:21:15.427  4019  4032 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-26 15:21:15.461  4019  4032 D bt_hci  : start_up starting async portion
,07-26 15:21:15.461  4019  4039 I bt_hci  : event_finish_startup
07-26 15:21:15.461  4019  4039 I bt_hci_h4: hal_open
07-26 15:21:15.461  4019  4039 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-26 15:21:15.464  4019  4039 I bt_userial_vendor: device fd = 49 open
,07-26 15:21:15.551  4019  4039 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:21:15.578  4019  4039 D bt_hwcfg: Chipset BCM4335C0
,07-26 15:21:15.578  4019  4039 D bt_hwcfg: Target name = [BCM4335C0]
07-26 15:21:15.578  4019  4039 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-26 15:21:16.122  4019  4039 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-26 15:21:16.123  4019  4039 D bt_hwcfg: Settlement delay -- 100 ms
,07-26 15:21:16.123  4019  4039 I bt_hwcfg: Setting fw settlement delay to 100 
,07-26 15:21:16.240  4019  4039 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-26 15:21:16.243  4019  4039 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-26 15:21:16.268  4019  4039 I bt_hwcfg: vendor lib fwcfg completed
,07-26 15:21:16.268  4019  4039 I bt_vendor: firmware callback
07-26 15:21:16.268  4019  4039 I bt_hci  : firmware_config_callback
,07-26 15:21:16.279  4019  4048 I bt_btu  : btu_task pending for preload complete event
,07-26 15:21:16.280  4019  4048 I bt_btu_task: Bluetooth chip preload is complete
,07-26 15:21:16.280  4019  4048 I bt_btu  : btu_task received preload complete event
,07-26 15:21:16.289  4019  4048 I         : BTE_InitTraceLevels -- TRC_HCI
,07-26 15:21:16.289  4019  4048 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-26 15:21:16.289  4019  4048 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:21:16.289  4019  4048 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-26 15:21:16.289  4019  4048 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_A2D
,07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_BTM
07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_GAP
,07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_PAN
07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_GATT
,07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_SMP
07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-26 15:21:16.290  4019  4048 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-26 15:21:16.525  4019  4048 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39299b5
,07-26 15:21:16.525  4019  4048 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39299b5 
,07-26 15:21:16.601  4019  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-26 15:21:16.601  4019  4035 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-26 15:21:16.622  4019  4035 D BluetoothAdapterProperties: Name is: Nexus 5
07-26 15:21:16.623  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:16.624  4019  4035 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:16.624  4019  4035 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:16.624  4019  4035 D bt_hci  : do_postload posting postload work item
07-26 15:21:16.624  4019  4039 I bt_hci  : event_postload
07-26 15:21:16.624  4019  4039 I bt_vendor: sco_config_cb
07-26 15:21:16.624  4019  4039 I bt_hci  : sco_config_callback postload finished.
07-26 15:21:16.641  4019  4039 I bt_vendor: low_power_mode_cb
07-26 15:21:16.642  4019  4035 D bt_bte_conf: Device ID record 1 : primary
07-26 15:21:16.642  4019  4035 D bt_bte_conf:   vendorId            = 000f
07-26 15:21:16.642  4019  4035 D bt_bte_conf:   vendorIdSource      = 0001
07-26 15:21:16.642  4019  4035 D bt_bte_conf:   product             = 1200
07-26 15:21:16.642  4019  4035 D bt_bte_conf:   version             = 1436
,07-26 15:21:16.642  4019  4035 D bt_bte_conf:   clientExecutableURL = 
,07-26 15:21:16.642  4019  4035 D bt_bte_conf:   serviceDescription  = 
,07-26 15:21:16.642  4019  4035 D bt_bte_conf:   documentationURL    = 
,07-26 15:21:16.661  4019  4035 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-26 15:21:16.661  4019  4032 D bt_stack_manager: event_start_up_stack finished
07-26 15:21:16.661  4019  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-26 15:21:16.662  4019  4031 D BluetoothAdapterProperties: Setting state to 15
,07-26 15:21:16.662  4019  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-26 15:21:16.663  4019  4031 I BluetoothAdapterState: Entering BleOnState
07-26 15:21:16.663  4019  4031 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-26 15:21:16.663  4019  4031 D BluetoothAdapterProperties: Setting state to 11
,07-26 15:21:16.663  4019  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-26 15:21:16.665  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:16.671  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:16.676  4019  4019 D HeadsetService: Received start request. Starting profile...
,07-26 15:21:16.677  4019  4019 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:21:16.677  4019  4019 D HeadsetStateMachine: make
07-26 15:21:16.681  4019  4031 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:21:16.688  4019  4019 D HeadsetStateMachine: max_hf_connections = 1
,07-26 15:21:16.688  4019  4019 I bt_bluedroid: get_profile_interface handsfree
07-26 15:21:16.701  4019  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-26 15:21:16.701  4019  4035 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-26 15:21:16.732  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:16.732  4019  4019 D A2dpService: Received start request. Starting profile...
07-26 15:21:16.733  4019  4019 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-26 15:21:16.733  4019  4019 I bt_bluedroid: get_profile_interface avrcp
07-26 15:21:16.775  4019  4019 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-26 15:21:16.775  4019  4019 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:21:16.775  4019  4019 D A2dpStateMachine: make
07-26 15:21:16.776  4019  4019 I bt_bluedroid: get_profile_interface a2dp
,07-26 15:21:16.777  4019  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-26 15:21:16.782  4019  4019 I BluetoothHidServiceJni: classInitNative: succeeds
07-26 15:21:16.782  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:16.782  4019  4064 D A2dpStateMachine: Enter Disconnected: -2
07-26 15:21:16.783  4019  4019 D HidService: Received start request. Starting profile...
07-26 15:21:16.783  4019  4019 I bt_bluedroid: get_profile_interface hidhost
07-26 15:21:16.783  4019  4035 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390b099
07-26 15:21:16.783  4019  4035 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-26 15:21:16.784  4019  4019 D HidService: setHidService(): set to: null
07-26 15:21:16.784  4019  4019 I BluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:21:16.785  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:16.785  4019  4019 D HealthService: Received start request. Starting profile...
,07-26 15:21:16.798  4019  4019 I bt_bluedroid: get_profile_interface health
07-26 15:21:16.799  4019  4019 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-26 15:21:16.799  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:16.800  4019  4019 D PanService: Received start request. Starting profile...
07-26 15:21:16.800  4019  4019 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:21:16.800  4019  4019 I bt_bluedroid: get_profile_interface pan
07-26 15:21:16.800  4019  4035 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-26 15:21:16.802  4019  4019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@522db7f
07-26 15:21:16.803  4019  4019 D BluetoothMapService: Received start request. Starting profile...
07-26 15:21:16.803  4019  4019 D BluetoothMapService: start()
07-26 15:21:16.804  4019  4019 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-26 15:21:16.805  4019  4019 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-26 15:21:16.805  4019  4019 D BluetoothMapAppObserver: createReceiver()
,07-26 15:21:16.805  4019  4019 D BluetoothMapAppObserver: initObservers()
07-26 15:21:16.805  4019  4019 D BluetoothMapAppObserver: getEnabledAccountItems()
07-26 15:21:16.819  4019  4055 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-26 15:21:16.819  4019  4019 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:16.819  4019  4019 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:16.819  4019  4019 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:16.819  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOn()=true
,07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOff()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isTurningOn()=true
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:21:16.822  4019  4019 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:21:16.823  4019  4031 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-26 15:21:16.823  4019  4031 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:21:16.823  4019  4031 D BluetoothAdapterProperties: State =  11
,07-26 15:21:16.823  4019  4031 D BluetoothAdapterProperties: Setting state to 12
07-26 15:21:16.823  4019  4031 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 15:21:16.824   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:16.824   947  1649 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:21:16.825  4019  4035 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:21:16.825  4019  4035 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-26 15:21:16.825  4019  4031 I BluetoothAdapterState: Entering OnState
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:16.827  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:16.828  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:16.829  3660  3996 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:21:16.830  1299  1471 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:16.830   947  1401 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:16.831   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:16.831   792   812 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:16.831   947   961 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:16.832  3660  3672 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:16.833  3660  3674 D BluetoothPbap: onBluetoothStateChange: up=true
,07-26 15:21:16.834  4019  4019 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:21:16.834  4019  4019 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-26 15:21:16.835   947   960 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:16.835   792   812 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:16.836   947  1650 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:16.837  4019  4019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:16.837  3660  3996 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:21:16.839  3660  3672 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:16.840  4019  4019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:16.841  4019  4019 D ObexServerSockets: Succeed to create listening sockets 
07-26 15:21:16.841  4019  4019 D ObexServerSockets0: startAccept()
07-26 15:21:16.841  4019  4019 D ObexServerSockets0: prepareForNewConnect()
07-26 15:21:16.841  3660  3674 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:16.841   947  1649 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:21:16.843  4019  4019 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-26 15:21:16.844   792   792 I Telecom : BluetoothPhoneService: queryPhoneState
07-26 15:21:16.848  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:16.849  4019  4019 D BluetoothSdpJni: SDP Create record success - handle: 0
07-26 15:21:16.850  4019  4070 D ObexServerSockets0: Accepting socket connection...
07-26 15:21:16.851   947   947 D BluetoothInputDevice: Proxy object connected
07-26 15:21:16.851   947   947 D HidProfile: Bluetooth service connected
07-26 15:21:16.858  3660  3660 D BluetoothInputDevice: Proxy object connected
07-26 15:21:16.858  3660  3660 D HidProfile: Bluetooth service connected
07-26 15:21:16.861  4019  4069 D ObexServerSockets0: Accepting socket connection...
07-26 15:21:16.866   792   792 D BluetoothA2dp: Proxy object connected
07-26 15:21:16.867  3660  3660 D BluetoothA2dp: Proxy object connected
,07-26 15:21:16.868  4019  4019 D BluetoothMapService: onReceive
07-26 15:21:16.868  4019  4019 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:16.868  4019  4019 D BluetoothMapService: STATE_ON
07-26 15:21:16.870  3660  3660 D BluetoothMap: Proxy object connected
07-26 15:21:16.870  3660  3660 D MapProfile: Bluetooth service connected
07-26 15:21:16.870  3660  3660 D BluetoothMap: getConnectedDevices()
07-26 15:21:16.873  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:16.878  3660  3660 D BluetoothPan: BluetoothPAN Proxy object connected
,07-26 15:21:16.878  3660  3660 D PanProfile: Bluetooth service connected
07-26 15:21:16.878  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-26 15:21:16.880  3660  3660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:21:16.883   947   947 D BluetoothA2dp: Proxy object connected
07-26 15:21:16.885   947   947 D BluetoothMap: Proxy object connected
07-26 15:21:16.885   947   947 D MapProfile: Bluetooth service connected
07-26 15:21:16.885   947   947 D BluetoothMap: getConnectedDevices()
,07-26 15:21:16.885  3660  3660 D DockEventReceiver: finishStartingService: stopping service
07-26 15:21:16.886   947   947 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:16.886   947   947 D PanProfile: Bluetooth service connected
,07-26 15:21:16.890   947   947 D BluetoothPbap: Proxy object connected
,07-26 15:21:16.890   947   947 D PbapServerProfile: Bluetooth service connected
07-26 15:21:16.890  4019  4019 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:21:16.890  4019  4019 D ObexServerSockets0: prepareForNewConnect()
,07-26 15:21:16.891  3660  3660 D BluetoothPbap: Proxy object connected
07-26 15:21:16.891  3660  3660 D PbapServerProfile: Bluetooth service connected
,07-26 15:21:16.892  4019  4092 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:16.903  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:16.907  1744  4098 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-26 15:21:16.908  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-26 15:21:16.908  4019  4099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:16.909  4019  4099 I BtOppRfcommListener: Accept thread started.
,07-26 15:21:16.920  1744  4098 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-26 15:21:16.925  3660  3672 D BluetoothHeadset: Proxy object connected
,07-26 15:21:16.925  3660  3660 D HeadsetProfile: Bluetooth service connected
07-26 15:21:16.925  1299  1327 D BluetoothHeadset: Proxy object connected
07-26 15:21:16.925   792   792 D BluetoothHeadset: Proxy object connected
07-26 15:21:16.925   792   792 D BluetoothHeadset: Proxy object connected
07-26 15:21:16.925   947   960 D BluetoothHeadset: Proxy object connected
07-26 15:21:16.925   947   947 D HeadsetProfile: Bluetooth service connected
,07-26 15:21:16.926   792   792 D BluetoothHeadset: Proxy object connected
,07-26 15:21:16.930  1299  1472 D BluetoothHeadset: Proxy object connected
,07-26 15:21:16.932   792   812 D BluetoothHeadset: Proxy object connected
,07-26 15:21:16.932   947  1650 D BluetoothHeadset: Proxy object connected
07-26 15:21:16.932   947   947 D HeadsetProfile: Bluetooth service connected
,07-26 15:21:16.935   792   812 D BluetoothHeadset: Proxy object connected
,07-26 15:21:16.941  3660  3674 D BluetoothHeadset: Proxy object connected
07-26 15:21:16.942  3660  3660 D HeadsetProfile: Bluetooth service connected
,07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:17.343  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:17.350  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:17.351  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:17.351  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82b9ad2 added. We now have 8 listener(s)
,07-26 15:21:17.351  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:17.353   792   802 D WifiService: setWifiEnabled: false pid=3531, uid=10000
07-26 15:21:17.353   792   802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:21:17.357  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:17.357   792   957 D WifiService: setWifiEnabled: true pid=3531, uid=10000
07-26 15:21:17.357   792   957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:21:17.359   194   648 D SoftapController: Softap fwReload - Ok
,07-26 15:21:17.361   194   648 D CommandListener: Setting iface cfg
,07-26 15:21:17.361   194   648 D CommandListener: Trying to bring down wlan0
,07-26 15:21:17.362   194   648 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:17.364   792   897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-26 15:21:18.113   792   897 D wifi    : set interface wlan0 flags (UP)
,07-26 15:21:18.113   792   897 I WifiHAL : Initializing wifi
,07-26 15:21:18.113   792   897 I WifiHAL : Creating socket
,07-26 15:21:18.115   792   897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-26 15:21:18.115   792   897 D wifi    : Did set static halHandle = 0xaecebc50
07-26 15:21:18.115   792   897 D wifi    : halHandle = 0xaecebc50, mVM = 0xb4cfc000, mCls = 0x201436
07-26 15:21:18.115   792   897 D wifi    : array field set
07-26 15:21:18.115   792   897 I WifiNative-HAL: interface[0] = p2p0
,07-26 15:21:18.115   792   812 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-26 15:21:18.115   792   897 I WifiNative-HAL: interface[1] = wlan0
,07-26 15:21:18.119   792   897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-26 15:21:18.119   792   897 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-26 15:21:18.119  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:18.124   792  4111 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1362183088
07-26 15:21:18.124   792  4111 D wifi    : waitForHalEvents called, vm = 0xb4cfc000, obj = 0x201436, env = 0x95ce9080
,07-26 15:21:18.152  4112  4112 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:21:18.194  4112  4112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:18.202  4112  4112 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:19.167  3531  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:19.175  3531  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:19.177   792   897 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:21:19.184   792   897 D WifiConfigStore: loaded 0 passpoint configs
,07-26 15:21:19.184   792   897 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:21:19.185   792   897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-26 15:21:19.185   792   897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-26 15:21:19.185   792   897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:21:19.185   792   897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-26 15:21:19.186   792   897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-26 15:21:19.186   792   897 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-26 15:21:19.188   792   897 D WifiNative-HAL: Setting external_sim to 1
07-26 15:21:19.188   792   897 D wifi    : setting dfs flag to true, 0x9ad63b80
,07-26 15:21:19.188   792   897 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:19.188   792   897 D wifi    : setting scan oui 0x9ad63b80
07-26 15:21:19.188   792   897 D WifiHAL : Sending mac address OUI
,07-26 15:21:19.189  2259  2259 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:19.209   792   897 E native  : do suspend true
,07-26 15:21:19.212   792   897 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-26 15:21:19.212   792   897 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-26 15:21:19.213   792   792 D RttService: SCAN_AVAILABLE : 3
07-26 15:21:19.213   792   911 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:19.214   194   648 D CommandListener: Setting iface cfg
07-26 15:21:19.214   194   648 D CommandListener: Trying to bring up p2p0
07-26 15:21:19.214   792   896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-26 15:21:19.222   792   896 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 15:21:19.222   792   896 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:19.366  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:19.367  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:19.369  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-26 15:21:19.369  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-26 15:21:19.370  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f93b09b Bundle[{}]
,07-26 15:21:19.370  3531  3589 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:21:19.370  3531  3589 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:21:19.370  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-26 15:21:19.371  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-26 15:21:19.371  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-26 15:21:19.372  3531  3589 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-26 15:21:19.378  3531  3589 I System.out: Running OutgoingSocketThread
,07-26 15:21:19.380  3531  4117 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 372)
07-26 15:21:19.381  3531  4117 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48240
07-26 15:21:19.381  3531  4117 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-26 15:21:20.382  3531  3589 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 373)
,07-26 15:21:20.383  3531  3589 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 373)
,07-26 15:21:20.383  3531  3589 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 373)
,07-26 15:21:20.383  3531  3589 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 373)
,07-26 15:21:20.392  3531  3589 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 378)
,07-26 15:21:20.392  3531  3589 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 378)
,07-26 15:21:20.392  3531  3589 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 378)
,07-26 15:21:20.394  3531  3589 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 379)
07-26 15:21:20.398  3531  3589 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 381)
07-26 15:21:20.404  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.404  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42917a3 added. We now have 2 listener(s)
07-26 15:21:20.410  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.411  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.411  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:21:20.415  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:20.415  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c4eaa0 added. We now have 9 listener(s)
07-26 15:21:20.416  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.417  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:20.429  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:20.437  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:20.438  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:20.438  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:21:20.439  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.440  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.440  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.440  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4921e added. We now have 3 listener(s)
07-26 15:21:20.441  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.441  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.441  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:20.441  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:20.441  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab8aff added. We now have 10 listener(s)
,07-26 15:21:20.441  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.441  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:20.441  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:20.441  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:20.441  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.441  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.441  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.441  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.441  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42917a3 removed from the list
,07-26 15:21:20.441  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.441  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c4eaa0 removed from the list
07-26 15:21:20.441  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:20.441  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.442  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.442  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.442  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:20.442  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:20.442  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:20.442  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c4eaa0 not in the list
07-26 15:21:20.442  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.442  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.443  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:20.443  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:20.443  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.443  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab8aff removed from the list
07-26 15:21:20.443  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.443  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.443  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:20.443  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.443  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4921e removed from the list
07-26 15:21:20.443  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.443  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89e10cc added. We now have 2 listener(s)
07-26 15:21:20.444  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.444  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.444  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:21:20.444  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:20.444  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e337f15 added. We now have 9 listener(s)
07-26 15:21:20.444  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.444  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:20.446  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:20.447  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:20.448  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:20.448  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:20.449  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.450  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.450  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:21:20.450  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b7d81b added. We now have 3 listener(s)
07-26 15:21:20.451  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-26 15:21:20.451  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.451  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:20.451  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:20.451  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16db8 added. We now have 10 listener(s)
07-26 15:21:20.451  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.451  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:21:20.451  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:20.451  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:20.451  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:20.453  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:21:20.453  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 15:21:20.455  3531  3589 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:21:20.455  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-26 15:21:20.455  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:21:20.455  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:21:20.456  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:20.456  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.457  3531  3589 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:20.457  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:20.457  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:20.458  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:20.458  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:20.458  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:20.459  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.459  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.459  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.459  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.459  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89e10cc removed from the list
07-26 15:21:20.459  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.459  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e337f15 removed from the list
07-26 15:21:20.459  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:20.459  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.459  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.459  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.459  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:20.459  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:20.459  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.459  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e337f15 not in the list
07-26 15:21:20.459  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.459  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.460  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:20.460  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:21:20.460  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:20.460  3531  3589 D org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:20.460  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:20.460  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.460  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16db8 removed from the list
07-26 15:21:20.460  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.460  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.460  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.460  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.460  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b7d81b removed from the list
07-26 15:21:20.461  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.461  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@771daf7 added. We now have 2 listener(s)
07-26 15:21:20.462  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.462  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.462  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:20.462  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:20.462  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3bad64 added. We now have 9 listener(s)
07-26 15:21:20.462  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.462  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:20.464  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:20.465  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:20.466  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:20.466  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:20.467  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.467  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.467  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.467  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec5c82 added. We now have 3 listener(s)
07-26 15:21:20.468  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.468  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.468  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:20.469  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:20.469  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45f2f93 added. We now have 10 listener(s)
07-26 15:21:20.469  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.469  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:20.469  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:20.469  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:20.469  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:20.469  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:20.471  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:21:20.471  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:20.473  3531  3589 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:21:20.473  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:20.474  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:21:20.474  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:21:20.474  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:20.475  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.475  3531  3589 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:20.475  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:20.476  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:20.476  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:20.476  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.476  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.476  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.476  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.476  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@771daf7 removed from the list
07-26 15:21:20.476  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.476  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3bad64 removed from the list
07-26 15:21:20.476  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:20.476  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.476  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.476  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.476  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:20.476  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:20.476  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.476  3531  3589 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3bad64 not in the list
07-26 15:21:20.477  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.477  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.477  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:20.477  3531  3589 D BluetoothAdapter: STATE_ON
07-26 15:21:20.477  3531  3589 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:20.477  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:20.477  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:20.477  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.477  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45f2f93 removed from the list
07-26 15:21:20.477  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.477  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.477  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.477  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.477  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec5c82 removed from the list
07-26 15:21:20.478  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.478  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bece added. We now have 2 listener(s)
07-26 15:21:20.479  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.479  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.479  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:20.479  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:20.479  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c331ef added. We now have 9 listener(s)
07-26 15:21:20.479  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.479  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:20.481  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:20.483  3531  3589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:20.483  3531  3589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:20.484  3531  3589 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:20.484  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.485  3531  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:20.485  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:20.485  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7335785 added. We now have 3 listener(s)
07-26 15:21:20.486  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-26 15:21:20.486  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:20.486  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:20.486  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:20.486  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b64f9da added. We now have 10 listener(s)
07-26 15:21:20.486  3531  3589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:20.486  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:20.486  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:20.486  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:20.486  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:20.488  3531  3589 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:21:20.488  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:20.490  3531  3589 E BluetoothAdapter: Bluetooth LE advertising not supported
07-26 15:21:20.490  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:20.490  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:21:20.491  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:21:20.491  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:20.492  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.492  3531  3589 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:20.493  3531  3589 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:20.493  3531  3589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:20.493  3531  3589 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:20.494  3531  3589 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:20.494  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.494  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:20.494  3531  3589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:20.494  3531  3589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bece removed from the list
07-26 15:21:20.494  3531  3589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:20.494  3531  3589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c331ef removed from the list
07-26 15:21:20.494  3531  3589 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:20.494  3531  3589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:20.494  3531  3589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:20.577  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-26 15:21:20.577  3531  3589 I jxcore-log: 
07-26 15:21:20.579  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:21:20.579  3531  3589 I jxcore-log: 
07-26 15:21:20.589  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:20.589  3531  3589 I jxcore-log: 
07-26 15:21:20.591  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.591  3531  3589 I jxcore-log: 
07-26 15:21:20.592  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:20.592  3531  3589 I jxcore-log: 
07-26 15:21:20.593  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.593  3531  3589 I jxcore-log: 
07-26 15:21:20.594  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.594  3531  3589 I jxcore-log: 
07-26 15:21:20.595  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.595  3531  3589 I jxcore-log: 
07-26 15:21:20.596  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.596  3531  3589 I jxcore-log: 
07-26 15:21:20.597  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.597  3531  3589 I jxcore-log: 
07-26 15:21:20.598  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.598  3531  3589 I jxcore-log: 
07-26 15:21:20.598  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.598  3531  3589 I jxcore-log: 
07-26 15:21:20.599  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.599  3531  3589 I jxcore-log: 
07-26 15:21:20.600  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.600  3531  3589 I jxcore-log: 
07-26 15:21:20.600  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.600  3531  3589 I jxcore-log: 
07-26 15:21:20.601  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.601  3531  3589 I jxcore-log: 
07-26 15:21:20.602  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.602  3531  3589 I jxcore-log: 
07-26 15:21:20.602  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:20.602  3531  3589 I jxcore-log: 
07-26 15:21:20.603  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.603  3531  3589 I jxcore-log: 
07-26 15:21:20.604  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.604  3531  3589 I jxcore-log: 
07-26 15:21:20.605  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.605  3531  3589 I jxcore-log: 
07-26 15:21:20.605  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.605  3531  3589 I jxcore-log: 
07-26 15:21:20.606  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.606  3531  3589 I jxcore-log: 
07-26 15:21:20.607  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.607  3531  3589 I jxcore-log: 
07-26 15:21:20.607  3531  3589 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:20.607  3531  3589 I jxcore-log: 
,07-26 15:21:24.929   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c8a030
,07-26 15:21:24.929   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-26 15:21:24.929   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
07-26 15:21:24.929   192   520 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229453008)
,07-26 15:21:25.032   192   520 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,07-26 15:21:25.032   192   520 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-26 15:21:25.032   192   520 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229453008) wakelock released: 1, error no: 0
07-26 15:21:25.032   192   520 I rmt_storage: 
,07-26 15:21:25.034   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c8a030
,07-26 15:21:39.960  1744  1922 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-26 15:21:45.407  1243  1360 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-26 15:21:45.407  1243  1360 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-26 15:21:51.057   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:21:51.078   792   897 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:21:57.402   792   899 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-26 15:22:52.635   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:22:52.656   792   897 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:23:54.238   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:23:54.260   792   897 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:24:39.712  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:24:39.743  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-26 15:24:39.746  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:24:56.298  1744  3149 V NativeCrypto: SSL shutdown failed: ssl=0x99e28200: I/O error during system call, Connection timed out
,07-26 15:25:56.753  3609  3637 V NativeCrypto: SSL shutdown failed: ssl=0xab1b3e00: I/O error during system call, Connection timed out
,07-26 15:25:57.023  1744  3149 V NativeCrypto: SSL shutdown failed: ssl=0x9b555c00: I/O error during system call, Connection timed out
,07-26 15:27:33.386   792   889 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-26 15:27:33.387   792   792 V KeyguardServiceDelegate: onStartedWakingUp()
07-26 15:27:33.388   792   815 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-26 15:27:33.395   792   815 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@bfdaff7)
,07-26 15:27:33.407   792   808 I ActivityManager: Start proc 4171:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
07-26 15:27:33.413   198   905 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-26 15:27:33.419   792   957 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-26 15:27:33.426   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:27:33.429   792   897 E native  : do suspend false
,07-26 15:27:33.437   792   897 D WifiConfigStore: No blacklist allowed without epno enabled
07-26 15:27:33.448  1276  1391 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
07-26 15:27:33.448  1276  1391 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-26 15:27:33.448  1276  1391 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-26 15:27:33.448  1276  1387 D BrcmNfcJni: RoutingManager::commitRouting
,07-26 15:27:33.448  1276  1391 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-26 15:27:33.454  1276  1387 D NfcService: Discovery configuration equal, not updating.
,07-26 15:27:33.459   792  1304 I ActivityManager: Start proc 4189:com.google.android.googlequicksearchbox:search/u0a22 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
,07-26 15:27:33.472  3531  3531 W IInputConnectionWrapper: reportFullscreenMode on inexistent InputConnection
07-26 15:27:33.472  3531  3531 W IInputConnectionWrapper: finishComposingText on inactive InputConnection
,07-26 15:27:33.472  1243  1243 I Keyboard.Facilitator: onFinishInput()
07-26 15:27:33.475  4171  4171 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-26 15:27:33.478  1965  1977 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
07-26 15:27:33.478   792   813 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-26 15:27:33.479   191   191 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
07-26 15:27:33.479   191   191 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-26 15:27:33.513   792  1304 I ActivityManager: Killing 2936:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,07-26 15:27:33.609  1744  1744 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-26 15:27:33.648   792   815 I DisplayPowerController: Unblocked screen on after 259 ms
,07-26 15:27:33.649   792   815 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-26 15:27:33.656   792  1546 I ActivityManager: Start proc 4228:com.google.android.partnersetup/u0a13 for content provider com.google.android.partnersetup/.RlzAppProvider
,07-26 15:27:33.686  4228  4228 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-26 15:27:33.714   191   191 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-26 15:27:33.714   792   914 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,07-26 15:27:33.815   792  1526 I ActivityManager: Killing 2649:android.process.acore/u0a4 (adj 15): empty #17
,07-26 15:27:33.928   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:27:34.005  1318  1508 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-26 15:27:34.005  1318  1508 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-26 15:27:34.013  4189  4189 I VS.Container: create_recognizer
,07-26 15:27:34.117  4189  4287 I MicroRecognitionRnrImpl: Starting detection.
,07-26 15:27:34.127  4189  4288 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@aa8889a
,07-26 15:27:34.130   198  4290 I AudioFlinger: AudioFlinger's thread 0xb2640000 ready to run
,07-26 15:27:34.137  4189  4288 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@aa8889a
,07-26 15:27:34.146   198  4290 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,07-26 15:27:34.146   198  4290 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
07-26 15:27:34.147   198  4290 D         : Failed to fetch the lookup information of the device 0000003E 
07-26 15:27:34.147   198  4290 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
07-26 15:27:34.147   198  4290 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
07-26 15:27:34.150   792   802 I ActivityManager: Start proc 4293:android.process.acore/u0a4 for content provider com.android.providers.contacts/.ContactsProvider2
07-26 15:27:34.150   198  4290 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,07-26 15:27:34.176  4293  4293 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-26 15:27:34.201  4293  4293 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-26 15:27:34.234  4189  4189 I HotwordWorkerImpl: onReady
,07-26 15:27:34.274  4293  4314 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-26 15:27:34.353  1660  4292 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-26 15:27:34.423  4293  4314 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,07-26 15:27:34.423  4293  4314 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-26 15:27:34.437   792   803 I ActivityManager: Start proc 4327:com.google.android.gm.exchange/u0a69 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,07-26 15:27:34.452   792  1334 I ActivityManager: Killing 3364:com.android.defcontainer/u0a5 (adj 15): empty #17
,07-26 15:27:34.479  4327  4327 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-26 15:27:34.501   792  1334 I ActivityManager: Start proc 4339:com.google.android.gm/u0a70 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,07-26 15:27:34.519   792  1548 I ActivityManager: Start proc 4351:com.google.process.gapps/u0a85 for content provider com.google.android.syncadapters.contacts/.GalProvider
,07-26 15:27:34.523   792  1546 I ActivityManager: Killing 2545:com.android.vending/u0a16 (adj 15): empty #17
,07-26 15:27:34.554   792  1526 I ActivityManager: Killing 3741:com.android.chrome/u0a34 (adj 15): empty #17
,07-26 15:27:34.568  4339  4339 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,07-26 15:27:34.627  4339  4365 I Gmail   : getAccountsCursor
,07-26 15:27:34.637  4339  4366 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-26 15:27:34.637  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:34.647  4351  4351 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-26 15:27:34.664  4351  4351 I GoogleHttpClient: GMS http client unavailable, use old client
,07-26 15:27:34.674  4293  4314 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-26 15:27:34.690  4293  4314 I ContactDirectoryManager: Discovered 0 contact directories in 366ms
,07-26 15:27:34.748  4339  4339 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-26 15:27:34.751   792   803 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-26 15:27:34.768  4339  4374 I Gmail   : Observing account changes for notifications
,07-26 15:27:34.778  4327  4327 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-26 15:27:34.802  4339  4385 I Gmail   : getAccountsCursor
,07-26 15:27:34.802  4339  4384 E Gmail   : Error finding the version of the Email provider.....
07-26 15:27:34.802  4339  4384 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-26 15:27:34.802  4339  4384 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-26 15:27:34.802  4339  4384 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-26 15:27:34.802  4339  4384 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-26 15:27:34.802  4339  4384 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:27:34.802  4339  4384 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:27:34.802  4339  4384 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-26 15:27:34.802  4339  4384 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-26 15:27:34.802  4339  4384 W EmailMigration: We do not support migrating this version of the Email provider.
,07-26 15:27:34.805  4327  4327 I Exchange: EasService.onCreate
,07-26 15:27:34.807  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:34.809  4327  4387 I Exchange: RestartPingTask
,07-26 15:27:34.823  4327  4327 I Exchange: RestartPingsTask did not start any pings.
,07-26 15:27:34.824  4327  4327 I Exchange: PSS stopIfIdle
07-26 15:27:34.824  4327  4327 I Exchange: PSS has no active accounts; stopping service.
,07-26 15:27:34.826  4327  4327 I Exchange: onDestroy
,07-26 15:27:34.834  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:34.922  4339  4396 I Gmail   : notifyAccountChanged
,07-26 15:27:34.923  4339  4366 I Gmail   : getAccountsCursor
,07-26 15:27:34.926  4339  4396 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-26 15:27:34.930  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:34.936  4339  4396 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-26 15:27:34.944  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:34.945  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:34.947  4339  4396 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-26 15:27:34.948  4339  4396 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-26 15:27:35.009  4339  4383 I Gmail   : getAccountsCursor
,07-26 15:27:35.014  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:35.282   792   897 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-26 15:27:35.284   792   897 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
07-26 15:27:35.284   792   897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:27:35.294   792   897 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-26 15:27:35.344   792   897 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-26 15:27:35.345  4112  4112 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-26 15:27:35.487  4112  4112 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-26 15:27:35.513  4112  4112 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-26 15:27:35.513  4112  4112 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:27:35.516   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:27:35.523   792   897 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-26 15:27:35.523   792   897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:27:35.523   792   899 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-26 15:27:35.529   792   897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:27:35.539   194   648 D CommandListener: Setting iface cfg
,07-26 15:27:35.543   792   897 D WifiStateMachine: Start Dhcp Watchdog 2
,07-26 15:27:35.552   792   899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-26 15:27:35.552   792   899 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,07-26 15:27:35.553   792  4408 D DhcpClient: Receive thread started
,07-26 15:27:35.554   792   897 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-26 15:27:35.634   792   897 E native  : do suspend false
,07-26 15:27:35.641   792  4407 D DhcpClient: Broadcasting DHCPDISCOVER
,07-26 15:27:35.648   792  4408 D DhcpClient: Received packet: 50:55:27:f0:fd:0b OFFER, ip /192.168.1.118, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172337, domain null
,07-26 15:27:35.649   792  4407 D DhcpClient: Got pending lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172337 seconds
07-26 15:27:35.649   792  4407 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.118 serverid=192.168.1.1
,07-26 15:27:35.657   792  4408 D DhcpClient: Received packet: 50:55:27:f0:fd:0b ACK: your new IP /192.168.1.118, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-26 15:27:35.657   792  4407 D DhcpClient: Confirmed lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-26 15:27:35.658   194   648 D CommandListener: Setting iface cfg
,07-26 15:27:35.661   792   897 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-26 15:27:35.664   792  4407 D DhcpClient: Scheduling renewal in 86399s
,07-26 15:27:35.667   792   897 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-26 15:27:35.668   792   897 D WifiConfigStore: No blacklist allowed without epno enabled
,07-26 15:27:35.668   792   899 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-26 15:27:35.673   792   899 D ConnectivityService: Adding iface wlan0 to network 101
07-26 15:27:35.677   792   897 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-26 15:27:35.713   792   899 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-26 15:27:35.713   792   899 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101,
07-26 15:27:35.714   792   899 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-26 15:27:35.715   792   899 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-26 15:27:35.716   792   899 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-26 15:27:35.723   792   899 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-26 15:27:35.728   792   899 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-26 15:27:35.728   792   899 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-26 15:27:35.728   792   899 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-26 15:27:35.728   792   897 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-26 15:27:35.728   792   899 D ConnectivityService:    accepting network in place of null
07-26 15:27:35.729   792   897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:27:35.729   792   899 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.118/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-26 15:27:35.755   194   648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:27:35.782   194   648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:27:35.784   792   899 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-26 15:27:35.784   792   899 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:27:35.785   792   899 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-26 15:27:35.787   792   812 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:27:35.811   792  1526 I ActivityManager: Start proc 4417:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-26 15:27:35.911  1660  1660 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-26 15:27:35.913  1660  2969 I iu.UploadsManager: num queued entries: 0
,07-26 15:27:35.914  1660  2969 I iu.UploadsManager: num updated entries: 0
07-26 15:27:35.914  1660  2969 I iu.SyncManager: NEXT; no task
,07-26 15:27:36.484   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=504939, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-26 15:27:37.528   792  4405 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.142,2a00:1450:4001:817::200e
,07-26 15:27:39.035  2259  4439 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-26 15:27:39.037   792  1548 I ActivityManager: Killing 3609:com.google.android.gms.unstable/u0a8 (adj 15): empty #17
,07-26 15:27:39.178   792  4405 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jul 2016 13:27:39 GMT], X-Android-Received-Millis=[1469539659177], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469539658987]}
,07-26 15:27:39.179   792   899 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-26 15:27:39.180   792   899 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-26 15:27:39.180   792   899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-26 15:27:39.184   792   899 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-26 15:27:39.292   792   802 I ActivityManager: Start proc 4470:com.google.android.gms.unstable/u0a8 for service com.google.android.gms/.droidguard.DroidGuardService
,07-26 15:27:39.348  4470  4470 I MultiDex: VM with version 2.1.0 has multidex support
,07-26 15:27:39.348  4470  4470 I MultiDex: install
,07-26 15:27:39.348  4470  4470 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-26 15:27:39.371  4470  4470 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-26 15:27:39.382  4470  4470 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-26 15:27:39.382  4470  4470 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-26 15:27:39.385  4470  4470 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-26 15:27:39.402  1744  4486 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-26 15:27:39.403  1744  4464 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-26 15:27:39.413  4470  4470 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-26 15:27:39.428  4470  4470 D ChimeraCfgMgr: Reading stored module config
,07-26 15:27:39.440  1744  4486 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-26 15:27:39.444  1744  4464 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-26 15:27:39.479  1744  4486 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-26 15:27:39.482  1744  4464 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-26 15:27:39.482  1744  4464 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-26 15:27:39.488  4470  4488 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-26 15:27:39.498  1744  4464 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-26 15:27:39.516   198   198 D WVCdm   : Instantiating CDM.
,07-26 15:27:39.517   198  1514 I WVCdm   : CdmEngine::OpenSession
,07-26 15:27:39.517   198  1514 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-26 15:27:39.520   198  1514 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-26 15:27:39.521   198  1514 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-26 15:27:39.521   198  1514 D DrmWidevineDash: Service_Initialize: starts!
07-26 15:27:39.521   198  1514 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-26 15:27:39.521   198  1514 D QSEECOMAPI: : App is not loaded in QSEE
,07-26 15:27:39.536   198  1514 D QSEECOMAPI: : Loaded image: APP id = 3
,07-26 15:27:39.537   198  1514 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-26 15:27:39.537   198  1514 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f49000
07-26 15:27:39.537   198  1514 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f49000
,07-26 15:27:39.548   198  1514 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-26 15:27:39.548   198  1514 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-26 15:27:39.554   198  1514 D DrmWidevineDash: hlos api version =  10
,07-26 15:27:39.554   198  1514 D DrmWidevineDash: tz api version =  10
07-26 15:27:39.554   198  1514 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-26 15:27:39.554   198  1514 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-26 15:27:39.567   198  1514 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-26 15:27:39.567   198  1514 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-26 15:27:39.567   198  1514 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb333f134
,07-26 15:27:39.577   198  1514 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-26 15:27:39.577   198  1514 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-26 15:27:39.577   198  1514 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604d068, dataLength=8
,07-26 15:27:39.584   198  1514 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-26 15:27:39.584   198  1514 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb6008800, wrapped_rsa_key_length=1280
,07-26 15:27:39.591   198  1514 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-26 15:27:39.591   198  1514 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-26 15:27:39.592   198   836 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-26 15:27:39.592   198   836 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-26 15:27:39.592   198   836 I WVCdm   : CdmEngine::GenerateKeyRequest
07-26 15:27:39.592   198   836 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb342ae20, idLength=0xb373ef2c
,07-26 15:27:39.619   198   836 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-26 15:27:39.619   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-26 15:27:39.624   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-26 15:27:39.624   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-26 15:27:39.624   198   836 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-26 15:27:39.624   198   836 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-26 15:27:39.628   198   836 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-26 15:27:39.628   198   836 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-26 15:27:39.633   198   836 D DrmWidevineDash: hlos api version =  10
07-26 15:27:39.633   198   836 D DrmWidevineDash: tz api version =  10
07-26 15:27:39.633   198   836 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-26 15:27:39.633   198   836 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-26 15:27:39.638   198   836 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-26 15:27:39.638   198   836 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-26 15:27:39.638   198   836 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-26 15:27:39.643   198   836 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-26 15:27:39.643   198   836 D WVCdm   : PrepareKeyRequest: nonce=809715045
07-26 15:27:39.643   198   836 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4883c00
07-26 15:27:39.643   198   836 D DrmWidevineDash: message_length=1639, signature=0xb6076840, signature_length=3010719748
,07-26 15:27:39.712   198   836 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-26 15:27:39.713   198   905 I WVCdm   : CdmEngine::CloseSession
07-26 15:27:39.713   198   905 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-26 15:27:39.717   198   905 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-26 15:27:39.717   198   905 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-26 15:27:39.722   198   905 D DrmWidevineDash: Service_Uninitialize: starts!
,07-26 15:27:39.722   198   905 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-26 15:27:39.722   198   905 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-26 15:27:39.723   198   905 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-26 15:27:39.723   198   905 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-26 15:27:39.772  4339  4373 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-26 15:27:39.807  4327  4376 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-26 15:27:41.587   792   899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-26 15:27:43.731   792   899 D ConnectivityService: handlePromptUnvalidated 101
,07-26 15:27:44.631   792   899 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-26 15:27:48.933   792   897 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,07-26 15:27:52.513  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:52.513  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:55.717   792   897 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-26 15:27:58.258  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:27:58.259  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:28:00.595  4537  4537 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-26 15:28:00.643  4537  4537 I dex2oat : dex2oat took 48.534ms (threads: 4) arena alloc=255KB java alloc=63KB native alloc=1662KB free=1665KB
,07-26 15:28:00.648  4470  4482 W System  : ClassLoader referenced unknown path: 
,07-26 15:28:00.653  4470  4482 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:28:00.709  4470  4482 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:28:00.789  4482  4482 W Binder_1: type=1400 audit(0.0:9): avc: denied { read } for name="/" dev="tmpfs" ino=6477 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,07-26 15:28:00.847  4470  4482 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-26 15:28:03.381   792   815 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-26 15:28:03.382   792   815 I PowerManagerService: Sleeping (uid 1000)...
07-26 15:28:03.408  4189  4199 W SearchService: Abort, client detached.
07-26 15:28:03.425  4189  4189 I HotwordDetector: Closing mic
,07-26 15:28:03.425  4189  4284 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@aa8889a
,07-26 15:28:03.426  4189  4288 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-26 15:28:03.478   198  4290 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-26 15:28:03.479   198  4290 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,07-26 15:28:03.485  4189  4287 I MicroRecognitionRnrImpl: Detection finished
07-26 15:28:03.485  4189  4285 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-26 15:28:03.509  1243  1243 I Keyboard.Facilitator: onFinishInput()
,07-26 15:28:03.524   792  1551 I ActivityManager: Killing 3660:com.android.settings/1000 (adj 15): empty #17
,07-26 15:28:03.533   792   898 D WifiService: Client connection lost with reason: 4
,07-26 15:28:03.561   792  1551 I ActivityManager: Killing 3690:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,07-26 15:28:03.909   792   815 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-26 15:28:03.928   792   813 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-26 15:28:03.931   191   191 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,07-26 15:28:03.931   191   191 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-26 15:28:04.212   191   191 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-26 15:28:04.214   792   914 D SurfaceControl: Excessive delay in setPowerMode(): 286ms
07-26 15:28:04.215  1965  1977 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-26 15:28:04.238   198   905 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-26 15:28:04.284   792   897 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:28:04.286   792   897 E native  : do suspend true
,07-26 15:28:04.784  1660  4583 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-26 15:28:05.895   792  1526 I ActivityManager: Killing 3827:com.google.android.apps.gcs/u0a82 (adj 15): empty #17
,07-26 15:28:15.719   792   897 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,07-26 15:28:34.456  1660  1802 D NetworkUsageDbReporter: Started reporting usage
,07-26 15:28:34.488  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:28:34.488  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-26 15:28:34.509   792   898 D WifiService: New client listening to asynchronous messages
,07-26 15:28:34.511  4189  4593 W CronetSyncConnectionRcs: Upload content type not set.
,07-26 15:28:34.611  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6371
,07-26 15:28:34.611  1660  1802 D NetworkUsageDbReporter: keeping row: 853
07-26 15:28:34.611  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15203
07-26 15:28:34.611  1660  1802 D NetworkUsageDbReporter: keeping row: 852
07-26 15:28:34.611  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 709
07-26 15:28:34.611  1660  1802 D NetworkUsageDbReporter: keeping row: 850
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 8736
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: keeping row: 849
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 18651
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: keeping row: 846
,07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2193
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: keeping row: 845
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 30480
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: keeping row: 843
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6512
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: keeping row: 842
07-26 15:28:34.612  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 95984
07-26 15:28:34.613  1660  1802 D NetworkUsageDbReporter: keeping row: 840
07-26 15:28:34.613  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 60216
07-26 15:28:34.613  1660  1802 D NetworkUsageDbReporter: keeping row: 839
07-26 15:28:34.613  1660  1802 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 293173
,07-26 15:28:34.613  1660  1802 D NetworkUsageDbReporter: keeping row: 837
,07-26 15:28:34.649  1660  1802 D NetworkUsageDbReporter: Finished reporting usage.
,07-26 15:29:03.524  1243  1360 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-26 15:29:03.524  1243  1360 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-26 15:29:09.212   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=597667, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-26 15:29:33.617  1744  1922 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-26 15:31:43.094   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=751549, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-26 15:32:15.532   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=783987, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-26 15:32:23.954   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=792407, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-26 15:33:00.060   792   808 I ActivityManager: Start proc 4641:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-26 15:33:00.092  4641  4641 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-26 15:33:00.106  4641  4641 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-26 15:33:00.106  4641  4641 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-26 15:33:00.106  4641  4641 I GAv4    :   adb logcat -s GAv4
,07-26 15:33:00.118  4641  4641 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:33:00.121  4641  4641 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:33:00.128  4641  4656 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:33:00.208   792  1548 I ActivityManager: Killing 4171:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,07-26 15:33:07.932   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=836387, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-26 15:33:13.984   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=842439, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-26 15:33:46.412   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=874867, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-26 15:33:57.344   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=885799, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-26 15:34:29.772   792  4406 D NetlinkSocketObserver: NeighborEvent{elapsedMs=918227, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-26 15:39:26.515   792   807 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),07-26 15:44:16.963  4674  4674 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-26 15:44:16.967  4674  4674 D AndroidRuntime: CheckJNI is OFF
07-26 15:44:17.001  4674  4674 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 15:44:17.035  4674  4674 I Radio-JNI: register_android_hardware_Radio DONE
07-26 15:44:17.054  4674  4674 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-26 15:44:17.060   792   808 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-26 15:44:17.060   792   808 I ActivityManager: Killing 3531:com.test.thalitest/u0a0 (adj 11): stop com.test.thalitest
07-26 15:44:17.099   792   898 D WifiService: Client connection lost with reason: 4
07-26 15:44:17.100   792   803 D GraphicsStats: Buffer count: 2
07-26 15:44:17.162   792   820 W PackageSettings: Skipping PackageSetting{b3e2003 com.example.hello/10278} due to missing metadata
07-26 15:44:17.183   792   820 I art     : Starting a blocking GC Explicit
07-26 15:44:17.231   792   820 I art     : Explicit concurrent mark sweep GC freed 42562(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 24MB/36MB, paused 755us total 40.697ms
07-26 15:44:17.254   792   820 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-26 15:44:17.256  4674  4674 I art     : System.exit called, status: 0
07-26 15:44:17.257  4674  4674 I AndroidRuntime: VM exiting with result code 0.
07-26 15:44:17.321   792   820 I ActivityManager: Start proc 4692:com.android.defcontainer/u0a5 for service com.android.defcontainer/.DefaultContainerService
07-26 15:44:17.322   792   820 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-26 15:44:17.364  1744  1817 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-26 15:44:17.364  4019  4019 D BluetoothMapAppObserver: onReceive
07-26 15:44:17.364  4019  4019 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-26 15:44:17.373   792   889 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-26 15:44:17.381  1299  1299 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-26 15:44:17.387  1243  1243 I Keyboard.Facilitator: resetDictionaries() : en_US
07-26 15:44:17.390  1243  4710 I Keyboard.Facilitator.DecoderInitializer: run()
07-26 15:44:17.395  4293  4314 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-26 15:44:17.403   792  1208 W ActivityManager: Spurious death for ProcessRecord{66a9d38 0:com.test.thalitest/u0a0}, curProc for 3531: null
07-26 15:44:17.429   792   803 I ActivityManager: Start proc 4712:com.android.musicfx/u0a15 for broadcast com.android.musicfx/.Compatibility$Receiver
--------- beginning of crash
07-26 15:44:17.439  4293  4314 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
07-26 15:44:17.439  4293  4314 E AndroidRuntime: Process: android.process.acore, PID: 4293
07-26 15:44:17.439  4293  4314 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:44:17.439  4293  4314 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
