#### Test 75789268d2ecd3a_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
07-08 14:02:32.385   791  2491 D NetlinkSocketObserver: NeighborEvent{elapsedMs=107745, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:02:33.011  3536  3536 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:02:33.014  3536  3536 D AndroidRuntime: CheckJNI is OFF
07-08 14:02:33.048  3536  3536 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:02:33.082  3536  3536 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:02:33.101  3536  3536 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-08 14:02:33.104   791  1313 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-08 14:02:33.128   791  1313 I ActivityManager: Start proc 3552:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-08 14:02:33.134  3536  3536 D AndroidRuntime: Shutting down VM
07-08 14:02:33.190  3552  3552 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-08 14:02:33.221  3552  3552 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8594-8596)
07-08 14:02:33.222  3552  3552 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:02:33.242  3552  3552 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a1af650}
07-08 14:02:33.242  3552  3552 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:02:33.243  3552  3552 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-08 14:02:33.249  3552  3552 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-08 14:02:33.250  3552  3552 E SysUtils: ApplicationContext is null in ApplicationStatus
07-08 14:02:33.261  3552  3552 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-08 14:02:33.265  3552  3552 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-08 14:02:33.265  3552  3552 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-08 14:02:33.266  3552  3552 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-08 14:02:33.315   791   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eeded5c:true
,07-08 14:02:33.385  3552  3552 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-08 14:02:33.396  3552  3552 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-08 14:02:33.443  3552  3597 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-08 14:02:33.463  3552  3584 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-08 14:02:33.501  3552  3597 I OpenGLRenderer: Initialized EGL, version 1.4
,07-08 14:02:33.546   791   809 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +389ms (total +430ms)
,07-08 14:02:33.549  1234  1234 I Keyboard.Facilitator: onFinishInput()
,07-08 14:02:33.613  3552  3552 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3552
,07-08 14:02:33.693  3552  3552 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-08 14:02:33.818  3552  3603 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1674393296
,07-08 14:02:33.823  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-08 14:02:33.823  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-08 14:02:33.823  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-08 14:02:33.823  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-08 14:02:33.823  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-08 14:02:33.823  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d884827 added. We now have 1 listener(s)
,07-08 14:02:33.826  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,07-08 14:02:33.827  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-08 14:02:33.827  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:33.827  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-08 14:02:33.830  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@866cf72 added. We now have 1 listener(s)
07-08 14:02:33.830  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:33.833   791   893 D WifiService: New client listening to asynchronous messages
,07-08 14:02:33.834  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-08 14:02:33.835  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:02:33.835  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-08 14:02:33.837  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:02:33.837  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:33.841  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:33.841  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-08 14:02:33.841  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:02:33.842  3552  3603 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:02:33.842  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:33.843  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:33.871  3552  3552 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-08 14:02:34.590  3552  3610 W jxcore-log: Initializing JXcore engine
,07-08 14:02:34.590  3552  3610 W jxcore-log: JXcore engine is ready
,07-08 14:02:34.622  3610  3610 W Thread-282: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8645]" dev="sockfs" ino=8645 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-08 14:02:34.622  3610  3610 W Thread-282: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-08 14:02:34.622  3610  3610 W Thread-282: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21523]" dev="sockfs" ino=21523 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-08 14:02:34.641   791   801 I ActivityManager: Killing 2961:com.google.android.configupdater/u0a36 (adj 15): empty #17
,07-08 14:02:34.647  3552  3610 W jxcore-log: Starting JXcore engine
,07-08 14:02:34.790  3552  3610 W jxcore-log: Platform android
07-08 14:02:34.790  3552  3610 W jxcore-log: 
,07-08 14:02:34.790  3552  3610 W jxcore-log: Process ARCH arm
07-08 14:02:34.790  3552  3610 W jxcore-log: 
,07-08 14:02:35.026  3552  3610 I jxcore-log: JXcore Cordova bridge is ready!
07-08 14:02:35.026  3552  3610 I jxcore-log: 
07-08 14:02:35.026  3552  3610 W jxcore-log: JXcore engine is started
,07-08 14:02:35.037  3552  3603 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-08 14:02:35.040  3552  3552 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-08 14:02:44.654  3094  3137 I Finsky  : [262] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-08 14:02:44.743  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:44.743  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:44.826  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:02:44.838  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-08 14:02:44.838  3552  3610 I jxcore-log: 
,07-08 14:02:44.841  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-08 14:02:44.841  3552  3610 I jxcore-log: 
,07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:44.844  3552  3610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:44.845  3552  3610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:44.847  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-08 14:02:44.847  3552  3610 I jxcore-log: 
,07-08 14:02:44.849  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-08 14:02:44.849  3552  3610 I jxcore-log: 
07-08 14:02:44.850  1626  3636 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-08 14:02:44.850  1626  3636 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-08 14:02:44.897  3094  3137 I Finsky  : [262] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-08 14:02:44.898  3094  3094 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-08 14:02:45.057  1626  3640 D UdcContextInitService: registered all accounts: true
,07-08 14:02:45.113   198   900 D WVCdm   : Instantiating CDM.
,07-08 14:02:45.114   198   827 I WVCdm   : CdmEngine::OpenSession
,07-08 14:02:45.115   198   827 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
07-08 14:02:45.118   198   827 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-08 14:02:45.120   198   827 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
07-08 14:02:45.120   198   827 D DrmWidevineDash: Service_Initialize: starts!
07-08 14:02:45.121   198   827 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-08 14:02:45.121   198   827 D QSEECOMAPI: : App is not loaded in QSEE
,07-08 14:02:45.139   198   827 D QSEECOMAPI: : Loaded image: APP id = 3
,07-08 14:02:45.141   198   827 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-08 14:02:45.141   198   827 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3317000
,07-08 14:02:45.141   198   827 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3317000
,07-08 14:02:45.157   198   827 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-08 14:02:45.157   198   827 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-08 14:02:45.163   198   827 D DrmWidevineDash: hlos api version =  10
,07-08 14:02:45.163   198   827 D DrmWidevineDash: tz api version =  10
07-08 14:02:45.163   198   827 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-08 14:02:45.163   198   827 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-08 14:02:45.175   198   827 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-08 14:02:45.175   198   827 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-08 14:02:45.175   198   827 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb373f134
,07-08 14:02:45.181   198   827 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-08 14:02:45.181   198   827 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-08 14:02:45.181   198   827 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb600c678, dataLength=8
,07-08 14:02:45.187   198   827 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-08 14:02:45.188   198   827 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb5fc8800, wrapped_rsa_key_length=1280
,07-08 14:02:45.195   198   827 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-08 14:02:45.196   198   827 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-08 14:02:45.196   198   198 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-08 14:02:45.196   198   198 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-08 14:02:45.197   198   198 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-08 14:02:45.197   198   198 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2655180, idLength=0xbed9b00c
,07-08 14:02:45.210   198   198 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-08 14:02:45.210   198   198 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-08 14:02:45.216   198   198 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-08 14:02:45.216   198   198 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-08 14:02:45.216   198   198 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-08 14:02:45.216   198   198 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-08 14:02:45.222   198   198 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-08 14:02:45.222   198   198 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-08 14:02:45.227   198   198 D DrmWidevineDash: hlos api version =  10
,07-08 14:02:45.227   198   198 D DrmWidevineDash: tz api version =  10
07-08 14:02:45.227   198   198 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-08 14:02:45.227   198   198 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-08 14:02:45.233   198   198 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-08 14:02:45.233   198   198 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-08 14:02:45.233   198   198 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-08 14:02:45.239   198   198 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-08 14:02:45.239   198   198 D WVCdm   : PrepareKeyRequest: nonce=694379226
07-08 14:02:45.239   198   198 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb3389700
07-08 14:02:45.239   198   198 D DrmWidevineDash: message_length=1639, signature=0xb6036480, signature_length=3201937636
,07-08 14:02:45.274  3552  3610 I jxcore-log: Unit Test app is loaded
07-08 14:02:45.274  3552  3610 I jxcore-log: 
,07-08 14:02:45.280  3552  3552 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-08 14:02:45.281  3552  3603 D JX-Cordova: Running tests
07-08 14:02:45.284  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:45.284  3552  3610 I jxcore-log: 
07-08 14:02:45.290  3552  3610 I jxcore-log: My device name is: LGE-Nexus 5
07-08 14:02:45.290  3552  3610 I jxcore-log: 
,07-08 14:02:45.340  3552  3603 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-08 14:02:45.340  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:02:45.340  3552  3603 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-08 14:02:45.340  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:02:45.340  3552  3603 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-08 14:02:45.340  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-08 14:02:45.341  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-08 14:02:45.341  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-08 14:02:45.342  3552  3603 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-08 14:02:45.342  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-08 14:02:45.342  3552  3603 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-08 14:02:45.342  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-08 14:02:45.342  3552  3603 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-08 14:02:45.342  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:02:45.342  3552  3603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-08 14:02:45.342  3552  3603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-08 14:02:45.343  3552  3603 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-08 14:02:45.343  3552  3603 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-08 14:02:45.343  3552  3603 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-08 14:02:45.343  3552  3603 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-08 14:02:45.343  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:45.343  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21cea30 added. We now have 2 listener(s)
07-08 14:02:45.343  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:45.345  3552  3603 D BluetoothAdapter: enable(): BT is already enabled..!
07-08 14:02:45.345   791  1313 D WifiService: setWifiEnabled: true pid=3552, uid=10000
07-08 14:02:45.345   791  1313 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:02:45.346  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:45.346  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ca86a9 added. We now have 3 listener(s)
07-08 14:02:45.346  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:45.349  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:45.349  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f9042e added. We now have 4 listener(s)
07-08 14:02:45.349  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:45.350  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:45.350  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae0fbcf added. We now have 5 listener(s)
07-08 14:02:45.350  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:45.351   791   801 D WifiService: setWifiEnabled: false pid=3552, uid=10000
07-08 14:02:45.351   791   801 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:45.354   198   198 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-08 14:02:45.355   791   892 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-08 14:02:45.356   791   892 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
,07-08 14:02:45.356   791   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:02:45.356   791   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:45.357   198  1398 I WVCdm   : CdmEngine::CloseSession
,07-08 14:02:45.357   198  1398 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-08 14:02:45.359  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:02:45.361  1815  1867 D BluetoothAdapterState: Current state: ON, message: 23
,07-08 14:02:45.361  1815  1867 D BluetoothAdapterProperties: Setting state to 13
,07-08 14:02:45.361  1815  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-08 14:02:45.361  1815  1867 D BluetoothAdapterProperties: onBluetoothDisable()
07-08 14:02:45.363  1815  1867 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:45.363  1815  1815 D BluetoothMapService: onReceive
07-08 14:02:45.363  1815  1815 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:02:45.363  1815  1815 D BluetoothMapService: STATE_TURNING_OFF
07-08 14:02:45.363  1815  1815 D BluetoothMapService: MAP Service closeService in
07-08 14:02:45.364  1815  1815 D BluetoothMapMasInstance0: MAP Service shutdown
,07-08 14:02:45.364  1815  1815 D ObexServerSockets0: shutdown(block = true)
,07-08 14:02:45.364  1815  1963 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-08 14:02:45.364  1815  1815 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:02:45.364  1815  1815 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:02:45.364  1815  1937 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-08 14:02:45.364  1815  1964 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-08 14:02:45.364  1815  1815 I BtOppRfcommListener: stopping Accept Thread
,07-08 14:02:45.364  1815  2674 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-08 14:02:45.364  1815  2674 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:45.366  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:45.367   791   892 E native  : do suspend true
,07-08 14:02:45.367  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:45.367  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:45.372  2695  2757 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-08 14:02:45.373  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:45.374   791   804 I ActivityManager: Start proc 3648:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-08 14:02:45.376  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:45.377  1815  1872 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:45.377  1815  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:02:45.378   198  1398 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-08 14:02:45.378   198  1398 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-08 14:02:45.382  1815  1815 D HeadsetService: Received stop request...Stopping profile...
,07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:45.382  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:45.383  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:45.384   930   947 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:45.384  1296  1422 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:45.385   791   791 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:45.385   791   791 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:45.385   791   791 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:45.385  1815  1815 D A2dpService: Received stop request...Stopping profile...
07-08 14:02:45.385  1815  1944 D A2dpStateMachine: Exit Disconnected: -1
07-08 14:02:45.387   194   786 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:45.388   791  2493 D DhcpClient: Clearing IP address
07-08 14:02:45.388   791   791 D BluetoothA2dp: Proxy object disconnected
07-08 14:02:45.389  1815  1815 D HidService: Received stop request...Stopping profile...
07-08 14:02:45.389  1815  1815 D HidService: Stopping Bluetooth HidService
07-08 14:02:45.390  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:45.390  1815  1815 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:45.390  1815  1815 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:45.390  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.390  1815  1815 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:45.392  1815  1815 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:02:45.392  1815  1815 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-08 14:02:45.392   930   930 D HeadsetProfile: Bluetooth service disconnected
07-08 14:02:45.392  1815  1815 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:45.392   930   930 D BluetoothA2dp: Proxy object disconnected
07-08 14:02:45.392  1815  1815 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:45.392  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.392  1815  1815 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:45.392   930   930 D BluetoothInputDevice: Proxy object disconnected
07-08 14:02:45.392   930   930 D HidProfile: Bluetooth service disconnected
07-08 14:02:45.392  1815  1909 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:45.392  1815  1909 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:45.392  1815  1872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-08 14:02:45.392  1815  1872 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-08 14:02:45.392   194   786 D CommandListener: Setting iface cfg
07-08 14:02:45.392  1815  1815 D HealthService: Received stop request...Stopping profile...
07-08 14:02:45.393   791  2497 D DhcpClient: Receive thread stopped
07-08 14:02:45.405  2816  2902 V NativeCrypto: Read error: ssl=0xa09bee00: I/O error during system call, Connection timed out
07-08 14:02:45.406  2816  2902 V NativeCrypto: Write error: ssl=0xa09bee00: I/O error during system call, Broken pipe
07-08 14:02:45.406  2816  2902 V NativeCrypto: Write error: ssl=0xa09bee00: I/O error during system call, Broken pipe
07-08 14:02:45.406  2816  2902 V NativeCrypto: SSL shutdown failed: ssl=0xa09bee00: I/O error during system call, Broken pipe
07-08 14:02:45.407   198  1398 D DrmWidevineDash: Service_Uninitialize: starts!
07-08 14:02:45.407   198  1398 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-08 14:02:45.407   198  1398 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-08 14:02:45.407   198  1398 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-08 14:02:45.408   198  1398 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
07-08 14:02:45.412  1762  2609 V NativeCrypto: Read error: ssl=0x9a4b5800: I/O error during system call, Connection timed out
07-08 14:02:45.415  1762  2609 V NativeCrypto: SSL shutdown failed: ssl=0x9a4b5800: I/O error during system call, Broken pipe
07-08 14:02:45.416  1815  1815 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:45.416  1815  1815 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:45.416  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.416  1815  1815 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:45.416  1815  1815 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:02:45.417  1815  1815 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-08 14:02:45.417  1815  1872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:02:45.417  1815  1872 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:02:45.417  1815  1909 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:45.417  1815  1909 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:45.417  1815  1909 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:02:45.417  1815  1909 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:02:45.417  1815  1909 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:02:45.417  1815  1909 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:02:45.417  1815  1815 D PanService: Received stop request...Stopping profile...
07-08 14:02:45.419  1762  2609 E GCM     : Wifi connection closed with errorCode 20
07-08 14:02:45.419   791   801 D ConnectivityService: reportNetworkConnectivity(100, false) by 10008
07-08 14:02:45.419   791  2490 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10008
07-08 14:02:45.421   930   930 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:02:45.421   930   930 D PanProfile: Bluetooth service disconnected
07-08 14:02:45.422  1815  1815 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:45.422  1815  1815 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:45.422  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.422  1815  1815 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:45.422  1815  1815 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:02:45.422  1815  1872 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-08 14:02:45.422  1815  1815 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-08 14:02:45.423  1815  1815 D BluetoothMapService: Received stop request...Stopping profile...
07-08 14:02:45.424  1815  1815 D BluetoothMapService: stop()
07-08 14:02:45.424  1815  1815 D BluetoothMapAppObserver: deinitObservers()
07-08 14:02:45.424  1815  1815 D BluetoothMapAppObserver: removeReceiver()
07-08 14:02:45.426   930   930 D BluetoothMap: Proxy object disconnected
07-08 14:02:45.426   930   930 D MapProfile: Bluetooth service disconnected
07-08 14:02:45.427  1815  1815 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:45.427  1815  1815 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:45.427  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.427  1815  1815 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:45.427  1815  1815 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-08 14:02:45.427  1815  1815 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:02:45.427  1815  1815 D BluetoothMapService: MAP Service closeService in
07-08 14:02:45.427  1815  1815 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:45.427  1815  1815 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:45.428  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.428  1815  1815 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:45.428  1815  1815 D BluetoothMapService: cleanup()
07-08 14:02:45.428  1815  1815 D BluetoothMapService: MAP Service closeService in
07-08 14:02:45.428  1815  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:02:45.428  1815  1867 D BluetoothAdapterProperties: Setting state to 15
07-08 14:02:45.428  1815  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-08 14:02:45.429  1815  1867 I BluetoothAdapterState: Entering BleOnState
07-08 14:02:45.430   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:45.430   930  1401 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:02:45.432   791  2490 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-08 14:02:45.432   930   951 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:02:45.432   791   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-08 14:02:45.432   791   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-08 14:02:45.433   791   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-08 14:02:45.436   930  1401 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:02:45.437   791   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:45.437   791   808 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:45.437   791   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:45.438   930   947 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:02:45.438   791   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:45.438  1296  1445 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:45.439   930   951 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:45.439  1815  1867 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-08 14:02:45.439  1815  1867 D BluetoothAdapterProperties: Setting state to 16
07-08 14:02:45.439  1815  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-08 14:02:45.439  1815  1867 D BluetoothAdapterProperties: onBleDisable
07-08 14:02:45.439  1815  1867 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:45.440  1815  1868 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:02:45.441  1815  1909 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-08 14:02:45.441  1815  1909 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:45.441  1815  1872 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:45.444  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:45.445  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:45.464   791   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:02:45.464   791   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-08 14:02:45.464   791   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-08 14:02:45.493   791   800 I art     : Background partial concurrent mark sweep GC freed 38245(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 24MB/36MB, paused 1.626ms total 121.018ms
07-08 14:02:45.510   791   894 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-08 14:02:45.511   791   791 D RttService: SCAN_AVAILABLE : 1
07-08 14:02:45.511   791   906 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.,util.StateMachine$SmHandler }
07-08 14:02:45.516   791   892 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-08 14:02:45.519   791   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:02:45.519   791   892 E native  : do suspend true
07-08 14:02:45.544  1815  1872 I bt_hci  : shut_down
07-08 14:02:45.544  1815  1883 D bt_hwcfg: hw_epilog_process
07-08 14:02:45.545   194   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:02:45.554  1815  1883 I bt_vendor: low_power_mode_cb
07-08 14:02:45.564  3648  3648 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-08 14:02:45.568   194   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:02:45.568   194   786 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:45.568   791   894 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-08 14:02:45.569   791   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:02:45.569  1815  1883 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-08 14:02:45.569  1815  1883 I bt_vendor: epilog_cb
07-08 14:02:45.569  1815  1883 I bt_hci  : epilog_finished_callback
07-08 14:02:45.570   791   808 D Tethering: MasterInitialState.processMessage what=3
07-08 14:02:45.571  1368  1368 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-08 14:02:45.573  1815  1872 I bt_hci_h4: hal_close
07-08 14:02:45.574  1815  1872 I bt_userial_vendor: device fd = 49 close
07-08 14:02:45.575  2508  2508 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@308771a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:45.577  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:45.578  1815  1868 D bt_stack_manager: event_shut_down_stack finished.
,07-08 14:02:45.579  1815  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-08 14:02:45.580  1815  1815 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:02:45.580  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:45.581  1815  1815 D BtGatt.GattService: Received stop request...Stopping profile...
07-08 14:02:45.581  1815  1815 D BtGatt.GattService: stop()
07-08 14:02:45.582  1815  1815 D BtGatt.AdvertiseManager: advertise clients cleared
07-08 14:02:45.582  1815  1867 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:45.583  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:45.583  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:45.584  1815  1815 V BluetoothAdapterState: isTurningOff()=false
07-08 14:02:45.584  1815  1815 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:45.584  1815  1815 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:45.584  1815  1815 V BluetoothAdapterState: isBleTurningOff()=true
07-08 14:02:45.584  1815  1867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:02:45.584  1815  1867 D BluetoothAdapterProperties: Setting state to 10
07-08 14:02:45.584  1815  1867 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-08 14:02:45.584  1815  1867 I BluetoothAdapterState: Entering OffState
07-08 14:02:45.585   791   808 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 7 receivers.
,07-08 14:02:45.600  1815  1815 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-08 14:02:45.600  1815  1815 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:02:45.600  1815  1815 I BluetoothServiceJni: cleanupNative: return from cleanup
07-08 14:02:45.600  1815  1868 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-08 14:02:45.606  2695  2757 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-08 14:02:45.620  1815  1868 D bt_stack_manager: event_clean_up_stack finished.
07-08 14:02:45.620  1815  1815 I art     : System.exit called, status: 0
07-08 14:02:45.620  1815  1815 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-08 14:02:45.626   194   786 E Netd    : netlink response contains error (No such file or directory)
07-08 14:02:45.631   791   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-08 14:02:45.632   791   892 D DhcpClient: doQuit
07-08 14:02:45.632   791   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-08 14:02:45.632   791  2493 D DhcpClient: onQuitting
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:45.636  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:45.636  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:45.636  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:45.648  2695  2757 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-08 14:02:45.732  1271  1271 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-08 14:02:45.735   791  1313 I ActivityManager: Process com.android.bluetooth (pid 1815) has died
,07-08 14:02:45.735   791  1313 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,07-08 14:02:45.740  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:45.746   791   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3323ffa:true
,07-08 14:02:45.753   791   963 I ActivityManager: Start proc 3675:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-08 14:02:45.761  1762  3641 W GLSUser : [AppCertManager] IOException while requesting key: 
,07-08 14:02:45.763  3648  3648 D LocalBluetoothProfileManager: Adding local MAP profile
07-08 14:02:45.764  3648  3648 D BluetoothMap: Create BluetoothMap proxy object
,07-08 14:02:45.774  1271  1271 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-08 14:02:45.784  1271  1271 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-08 14:02:45.786  3648  3648 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-08 14:02:45.791  3648  3648 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:45.804  1762  1798 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:02:45.808  1762  1798 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-08 14:02:45.814  1762  1798 V BaseAppContext: GmsRequestQueue started.
,07-08 14:02:45.817  3675  3675 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:02:45.817  3675  3675 D AdapterServiceConfig: Adding A2dpService
07-08 14:02:45.817  3675  3675 D AdapterServiceConfig: Adding HidService
,07-08 14:02:45.818  3675  3675 D AdapterServiceConfig: Adding HealthService
07-08 14:02:45.818  3675  3675 D AdapterServiceConfig: Adding PanService
,07-08 14:02:45.818  3675  3675 D AdapterServiceConfig: Adding GattService
07-08 14:02:45.818  3675  3675 D AdapterServiceConfig: Adding BluetoothMapService
,07-08 14:02:45.834   791   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca70f11:true
07-08 14:02:45.835  1762  1762 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
,07-08 14:02:45.842   791   893 D WifiService: New client listening to asynchronous messages
,07-08 14:02:45.850  3648  3648 D BluetoothPbap: Proxy object connected
,07-08 14:02:45.851  3648  3648 D PbapServerProfile: Bluetooth service connected
07-08 14:02:45.851  3648  3648 D BluetoothPbap: Proxy object disconnected
07-08 14:02:45.851  3648  3648 D PbapServerProfile: Bluetooth service disconnected
,07-08 14:02:45.855  1271  1271 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-08 14:02:45.863   791  1315 I ActivityManager: Start proc 3699:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-08 14:02:45.866   791  1339 I ActivityManager: Killing 2730:com.google.android.apps.photos/u0a65 (adj 15): empty #17
,07-08 14:02:45.895  1271  1271 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-08 14:02:46.166   791   892 D wifi    : In wifi stop Hal
,07-08 14:02:46.166   791   892 D wifi    : halHandle = 0x95697d30, mVM = 0xb4cfc000, mCls = 0x100a42
,07-08 14:02:46.168   791  1269 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-08 14:02:46.168   791  1269 D WifiHAL : Got a signal to exit!!!
07-08 14:02:46.168   791  1269 I WifiHAL : Exit wifi_event_loop
,07-08 14:02:46.171  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:46.173   791   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-08 14:02:46.173   791   892 E WifiHAL : Event processing terminated
07-08 14:02:46.173   791   892 D wifi    : In wifi cleaned up handler
07-08 14:02:46.173   791   892 I WifiHAL : Internal cleanup completed
07-08 14:02:46.174  1762  1888 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-08 14:02:46.175  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:46.176  2212  2212 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:02:46.277  1762  1798 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-08 14:02:46.294   791  1269 D wifi    : set interface wlan0 flags (DOWN)
,07-08 14:02:46.294   791   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-08 14:02:46.392  3699  3699 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:46.392  3699  3699 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.392  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:46.393  3699  3699 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:46.393  3699  3699 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.e.b(PG:170)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:02:46.393  3699  3699 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.k.d(PG:583)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.e.b(PG:170)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:02:46.393  3699  3699 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-,08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:02:46.393  3699  3699 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:02:46.393  3699  3699 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictM,ode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:46.393  3699  3699 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-08 14:02:46.396   791   802 I ActivityManager: Killing 2164:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-08 14:02:46.417  3699  3738 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-08 14:02:46.422   791   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@266f602:true
,07-08 14:02:46.497   791   808 D Tethering: InitialState.processMessage what=4
,07-08 14:02:46.517  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:46.520   791   808 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-08 14:02:46.520  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:46.529  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:46.538  3648  3648 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:46.554  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:46.557  1762  3749 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:02:46.558  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:02:46.581  1762  3749 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-08 14:02:46.590   791   963 I ActivityManager: Start proc 3750:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-08 14:02:46.669  2212  3764 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-08 14:02:46.679   791  1315 I ActivityManager: Start proc 3765:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-08 14:02:46.720  3765  3765 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-08 14:02:46.863   791  2100 I ActivityManager: Killing 2508:com.google.android.music:main/u0a60 (adj 15): empty #17
,07-08 14:02:46.952  1626  1626 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-08 14:02:46.953  1626  2756 I iu.UploadsManager: num queued entries: 0
07-08 14:02:46.954  1626  2756 I iu.UploadsManager: num updated entries: 0
07-08 14:02:46.954  1626  2756 I iu.SyncManager: NEXT; no task
,07-08 14:02:46.969   791  1315 I ActivityManager: Start proc 3783:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-08 14:02:46.998  3783  3783 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-08 14:02:47.037  3783  3783 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-08 14:02:47.037  3783  3783 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:02:47.037  3783  3783 I GAv4    :   adb logcat -s GAv4
,07-08 14:02:47.047  3783  3783 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:47.052  3783  3783 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:47.064  3783  3801 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:47.140  3783  3783 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-08 14:02:47.173  3783  3783 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2546-2548)
07-08 14:02:47.173  3783  3783 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:02:47.180  3783  3783 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1829104}
,07-08 14:02:47.180  3783  3783 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:02:47.180  3783  3783 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-08 14:02:47.186  3783  3783 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-08 14:02:47.187  3783  3783 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-08 14:02:47.197  3783  3783 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-08 14:02:47.201  3783  3783 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-08 14:02:47.201  3783  3783 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-08 14:02:47.201  3783  3783 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-08 14:02:47.246  3783  3837 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-08 14:02:47.249  3783  3783 I NSApplication: Starting up...
,07-08 14:02:47.259   791   801 I ActivityManager: Killing 2860:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-08 14:02:47.580   791   972 I ActivityManager: Start proc 3845:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-08 14:02:47.623  3845  3845 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-08 14:02:47.652  3845  3845 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-08 14:02:47.662   791   972 I ActivityManager: Killing 3287:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-08 14:02:47.911  1762  1798 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-08 14:02:47.912  1762  1798 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-08 14:02:49.425  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-08 14:02:49.425  3552  3610 I jxcore-log: 
,07-08 14:02:49.824  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-08 14:02:49.824  3552  3610 I jxcore-log: 
,07-08 14:02:49.847  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-08 14:02:49.847  3552  3610 I jxcore-log: 
,07-08 14:02:49.851  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-08 14:02:49.851  3552  3610 I jxcore-log: 
,07-08 14:02:49.868  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-08 14:02:49.868  3552  3610 I jxcore-log: 
,07-08 14:02:49.871  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-08 14:02:49.871  3552  3610 I jxcore-log: 
,07-08 14:02:50.368   791  1474 D WifiService: setWifiEnabled: true pid=3552, uid=10000
07-08 14:02:50.368   791  1474 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:02:50.371   194   786 D SoftapController: Softap fwReload - Ok
07-08 14:02:50.373   194   786 D CommandListener: Setting iface cfg
07-08 14:02:50.373   194   786 D CommandListener: Trying to bring down wlan0
07-08 14:02:50.373   194   786 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:50.375   791   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:02:50.738   791  1313 I ActivityManager: Killing 2914:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-08 14:02:51.144   791   892 D wifi    : set interface wlan0 flags (UP)
07-08 14:02:51.144   791   892 I WifiHAL : Initializing wifi
,07-08 14:02:51.144   791   892 I WifiHAL : Creating socket
07-08 14:02:51.145   791   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-08 14:02:51.145   791   892 D wifi    : Did set static halHandle = 0x95697d30
,07-08 14:02:51.145   791   892 D wifi    : halHandle = 0x95697d30, mVM = 0xb4cfc000, mCls = 0x201a7e
,07-08 14:02:51.145   791   892 D wifi    : array field set
07-08 14:02:51.145   791   892 I WifiNative-HAL: interface[0] = p2p0
,07-08 14:02:51.146   791   892 I WifiNative-HAL: interface[1] = wlan0
07-08 14:02:51.147   791   808 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-08 14:02:51.150  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:51.150   791   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-08 14:02:51.150  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:51.151   791   892 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-08 14:02:51.153   791  3899 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1788248784
07-08 14:02:51.153   791  3899 D wifi    : waitForHalEvents called, vm = 0xb4cfc000, obj = 0x201a7e, env = 0x99f9dd00
,07-08 14:02:51.188  3900  3900 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-08 14:02:51.228  3900  3900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:02:51.506  3900  3900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:02:51.587   791   972 I ActivityManager: Killing 3452:com.android.musicfx/u0a15 (adj 15): empty #17
,07-08 14:02:51.845  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-08 14:02:51.845  3552  3610 I jxcore-log: 
,07-08 14:02:51.856  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-08 14:02:51.856  3552  3610 I jxcore-log: 
,07-08 14:02:51.864  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-08 14:02:51.864  3552  3610 I jxcore-log: 
,07-08 14:02:52.016  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-08 14:02:52.016  3552  3610 I jxcore-log: 
,07-08 14:02:52.104  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-08 14:02:52.104  3552  3610 I jxcore-log: 
,07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:52.156  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:02:52.156  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:52.157  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:52.157  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:52.158   791   892 D WifiConfigStore: Loading config and enabling all networks 
,07-08 14:02:52.159  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-08 14:02:52.159  3552  3610 I jxcore-log: 
07-08 14:02:52.167  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-08 14:02:52.167  3552  3610 I jxcore-log: 
07-08 14:02:52.167   791   892 D WifiConfigStore: loaded 0 passpoint configs
07-08 14:02:52.167   791   892 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:02:52.167   791   892 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-08 14:02:52.167   791   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-08 14:02:52.168   791   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:02:52.168   791   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-08 14:02:52.168   791   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-08 14:02:52.168   791   892 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-08 14:02:52.171   791   892 D WifiNative-HAL: Setting external_sim to 1
07-08 14:02:52.171  2212  2212 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-08 14:02:52.171   791   892 D wifi    : setting dfs flag to true, 0x98275010
07-08 14:02:52.171   791   892 D WifiStateMachine: Setting OUI to DA-A1-19
,07-08 14:02:52.171   791   892 D wifi    : setting scan oui 0x98275010
07-08 14:02:52.171   791   892 D WifiHAL : Sending mac address OUI
,07-08 14:02:52.192   791   892 E native  : do suspend true
,07-08 14:02:52.196   791   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-08 14:02:52.196   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-08 14:02:52.196   791   791 D RttService: SCAN_AVAILABLE : 3
07-08 14:02:52.196   791   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-08 14:02:52.197   194   786 D CommandListener: Setting iface cfg
07-08 14:02:52.197   194   786 D CommandListener: Trying to bring up p2p0
07-08 14:02:52.197   791   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-08 14:02:52.206   791   891 D WifiNative-HAL: p2pGetDeviceAddress
07-08 14:02:52.207   791   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-08 14:02:52.368  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-08 14:02:52.368  3552  3610 I jxcore-log: 
,07-08 14:02:52.389  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-08 14:02:52.389  3552  3610 I jxcore-log: 
,07-08 14:02:52.393  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-08 14:02:52.393  3552  3610 I jxcore-log: 
,07-08 14:02:52.398  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-08 14:02:52.398  3552  3610 I jxcore-log: 
,07-08 14:02:52.414  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-08 14:02:52.414  3552  3610 I jxcore-log: 
,07-08 14:02:52.434  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-08 14:02:52.434  3552  3610 I jxcore-log: 
,07-08 14:02:52.520  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-08 14:02:52.520  3552  3610 I jxcore-log: 
,07-08 14:02:52.525  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-08 14:02:52.525  3552  3610 I jxcore-log: 
,07-08 14:02:52.549  3552  3610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-08 14:02:52.549  3552  3610 I jxcore-log: 
,07-08 14:02:52.558  3552  3610 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-08 14:02:52.559  3552  3610 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-08 14:02:52.559  3552  3610 I jxcore-log: 
,07-08 14:02:52.603  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:52.603  3552  3610 I jxcore-log: 
,07-08 14:02:52.604  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:52.604  3552  3610 I jxcore-log: 
07-08 14:02:52.605  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:52.605  3552  3610 I jxcore-log: 
,07-08 14:02:52.605  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:52.605  3552  3610 I jxcore-log: 
,07-08 14:02:52.607  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:52.607  3552  3610 I jxcore-log: 
07-08 14:02:52.608  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:52.608  3552  3610 I jxcore-log: 
07-08 14:02:52.608  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:52.608  3552  3610 I jxcore-log: 
,07-08 14:02:52.609  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:02:52.609  3552  3610 I jxcore-log: 
,07-08 14:02:55.372   791  1213 D WifiService: setWifiEnabled: false pid=3552, uid=10000,
,07-08 14:02:55.373   791  1213 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:55.386   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:02:55.407   791   791 D RttService: SCAN_AVAILABLE : 1
07-08 14:02:55.408   791   906 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-08 14:02:55.434   791   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:02:55.434   194   786 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:55.436   791   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:55.441  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:55.441  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:55.442  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:55.442  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:55.442  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:55.442  3552  3610 I jxcore-log: 
07-08 14:02:55.443  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:02:55.443  3552  3610 I jxcore-log: 
,07-08 14:02:55.454  3900  3900 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-08 14:02:56.455  3900  3900 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-08 14:02:56.461  3900  3900 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-08 14:02:56.471  3900  3900 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-08 14:02:56.578   791   892 D wifi    : In wifi stop Hal
07-08 14:02:56.578   791   892 D wifi    : halHandle = 0x95697d30, mVM = 0xb4cfc000, mCls = 0x201a7e
,07-08 14:02:56.578   791  3899 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-08 14:02:56.578   791  3899 D WifiHAL : Got a signal to exit!!!
07-08 14:02:56.578   791  3899 I WifiHAL : Exit wifi_event_loop
07-08 14:02:56.593  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:56.597  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:56.599  1762  1888 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-08 14:02:56.604   791   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-08 14:02:56.604   791   892 E WifiHAL : Event processing terminated
07-08 14:02:56.604   791   892 D wifi    : In wifi cleaned up handler
07-08 14:02:56.604   791   892 I WifiHAL : Internal cleanup completed
,07-08 14:02:56.625  2212  2212 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:02:56.733   791  3899 D wifi    : set interface wlan0 flags (DOWN)
,07-08 14:02:56.733   791   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-08 14:02:56.937   791   808 D Tethering: InitialState.processMessage what=4
,07-08 14:02:56.938   791   808 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-08 14:02:57.244   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c8a030
07-08 14:02:57.244   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-08 14:02:57.244   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
,07-08 14:02:57.244   192   470 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229453008)
,07-08 14:02:57.319   192   470 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,07-08 14:02:57.319   192   470 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-08 14:02:57.319   192   470 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229453008) wakelock released: 1, error no: 0
07-08 14:02:57.319   192   470 I rmt_storage: 
,07-08 14:02:57.321   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c8a030
,07-08 14:03:00.460  3675  3675 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:03:00.462  3675  3675 I bt_bluedroid: init
07-08 14:03:00.462  3675  3949 I BluetoothAdapterState: Entering OffState
,07-08 14:03:00.465  3675  3950 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-08 14:03:00.465  3675  3950 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-08 14:03:00.465  3675  3950 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-08 14:03:00.465  3675  3950 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-08 14:03:00.465  3675  3675 I bt_bluedroid: get_profile_interface socket
07-08 14:03:00.466  3675  3675 I bt_bluedroid: get_profile_interface sdp
07-08 14:03:00.468  3675  3686 I bt_bluedroid: config_hci_snoop_log
07-08 14:03:00.468   791   808 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-08 14:03:00.470  3675  3949 D BluetoothAdapterState: Current state: OFF, message: 0
07-08 14:03:00.471  3675  3949 D BluetoothAdapterProperties: Setting state to 14
07-08 14:03:00.471  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-08 14:03:00.471  3675  3949 D BluetoothBondStateMachine: make
07-08 14:03:00.473  3675  3953 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-08 14:03:00.474  3675  3953 D BluetoothAdapterProperties: Name is: Nexus 5
07-08 14:03:00.477  3675  3675 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-08 14:03:00.478  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
07-08 14:03:00.479  3675  3949 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:00.479  3675  3675 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:03:00.479  3675  3675 D BtGatt.GattService: Received start request. Starting profile...
07-08 14:03:00.479  3675  3675 D BtGatt.GattService: start()
07-08 14:03:00.479  3675  3675 I bt_bluedroid: get_profile_interface gatt
07-08 14:03:00.480  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
07-08 14:03:00.480  3675  3675 D BtGatt.AdvertiseManager: advertise manager created
07-08 14:03:00.480  3675  3954 I BluetoothBondStateMachine: StableState(): Entering Off State
07-08 14:03:00.484  3675  3675 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:00.484  3675  3675 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:00.484  3675  3675 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:03:00.484  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:00.484  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:03:00.484  3675  3949 I bt_bluedroid: enable
07-08 14:03:00.484  3675  3950 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:03:00.485  3675  3950 I bt_hci  : start_up
07-08 14:03:00.490  3675  3950 I bt_vendor: alloc value 0xb3939631
07-08 14:03:00.490  3675  3950 I bt_vendor: init
07-08 14:03:00.490  3675  3950 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-08 14:03:00.490  3675  3950 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-08 14:03:00.525  3675  3950 D bt_hci  : start_up starting async portion
,07-08 14:03:00.525  3675  3957 I bt_hci  : event_finish_startup
07-08 14:03:00.525  3675  3957 I bt_hci_h4: hal_open
07-08 14:03:00.525  3675  3957 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-08 14:03:00.528  3675  3957 I bt_userial_vendor: device fd = 49 open
,07-08 14:03:00.614  3675  3957 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:03:00.641  3675  3957 D bt_hwcfg: Chipset BCM4335C0
,07-08 14:03:00.641  3675  3957 D bt_hwcfg: Target name = [BCM4335C0]
07-08 14:03:00.642  3675  3957 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-08 14:03:00.978  3675  3957 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:03:00.978  3675  3957 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:03:00.978  3675  3957 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:03:01.096  3675  3957 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:03:01.097  3675  3957 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-08 14:03:01.125  3675  3957 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:03:01.125  3675  3957 I bt_vendor: firmware callback
,07-08 14:03:01.125  3675  3957 I bt_hci  : firmware_config_callback
,07-08 14:03:01.139  3675  3968 I bt_btu  : btu_task pending for preload complete event
,07-08 14:03:01.139  3675  3968 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:03:01.139  3675  3968 I bt_btu  : btu_task received preload complete event
,07-08 14:03:01.149  3675  3968 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:03:01.149  3675  3968 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-08 14:03:01.149  3675  3968 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-08 14:03:01.149  3675  3968 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-08 14:03:01.149  3675  3968 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_A2D
07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_BTM
,07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_GAP
07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_PAN
07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_SDP
07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_GATT
07-08 14:03:01.150  3675  3968 I         : BTE_InitTraceLevels -- TRC_SMP
07-08 14:03:01.151  3675  3968 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-08 14:03:01.151  3675  3968 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:03:01.374  3675  3968 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b79b5
,07-08 14:03:01.374  3675  3968 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b79b5 
,07-08 14:03:01.440  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:03:01.440  3675  3953 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-08 14:03:01.475  3675  3953 D BluetoothAdapterProperties: Name is: Nexus 5
,07-08 14:03:01.476  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:01.477  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:01.477  3675  3953 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:01.477  3675  3953 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:03:01.477  3675  3953 D bt_hci  : do_postload posting postload work item
07-08 14:03:01.477  3675  3957 I bt_hci  : event_postload
07-08 14:03:01.477  3675  3957 I bt_vendor: sco_config_cb
07-08 14:03:01.477  3675  3957 I bt_hci  : sco_config_callback postload finished.
,07-08 14:03:01.495  3675  3957 I bt_vendor: low_power_mode_cb
07-08 14:03:01.495  3675  3953 D bt_bte_conf: Device ID record 1 : primary
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   vendorId            = 000f
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   vendorIdSource      = 0001
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   product             = 1200
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   version             = 1436
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   clientExecutableURL = 
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   serviceDescription  = 
07-08 14:03:01.495  3675  3953 D bt_bte_conf:   documentationURL    = 
07-08 14:03:01.515  3675  3953 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-08 14:03:01.515  3675  3950 D bt_stack_manager: event_start_up_stack finished
07-08 14:03:01.515  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-08 14:03:01.515  3675  3949 D BluetoothAdapterProperties: Setting state to 15
07-08 14:03:01.515  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:03:01.516  3675  3949 I BluetoothAdapterState: Entering BleOnState
07-08 14:03:01.517  3675  3949 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:03:01.517  3675  3949 D BluetoothAdapterProperties: Setting state to 11
07-08 14:03:01.517  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-08 14:03:01.519  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
07-08 14:03:01.529  3675  3675 D HeadsetService: Received start request. Starting profile...
07-08 14:03:01.530  3675  3675 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-08 14:03:01.530  3675  3675 D HeadsetStateMachine: make
07-08 14:03:01.539  3675  3675 D HeadsetStateMachine: max_hf_connections = 1
07-08 14:03:01.539  3675  3675 I bt_bluedroid: get_profile_interface handsfree
07-08 14:03:01.539  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-08 14:03:01.540  3675  3953 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-08 14:03:01.541  3675  3949 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:01.544  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
,07-08 14:03:01.544  3675  3675 D A2dpService: Received start request. Starting profile...
07-08 14:03:01.544  3675  3675 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-08 14:03:01.545  3675  3675 I bt_bluedroid: get_profile_interface avrcp
,07-08 14:03:01.548  3675  3675 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-08 14:03:01.549  3675  3675 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-08 14:03:01.549  3675  3675 D A2dpStateMachine: make
,07-08 14:03:01.549  3675  3675 I bt_bluedroid: get_profile_interface a2dp
07-08 14:03:01.550  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-08 14:03:01.550  3675  3991 D A2dpStateMachine: Enter Disconnected: -2
,07-08 14:03:01.552  3675  3675 I BluetoothHidServiceJni: classInitNative: succeeds
07-08 14:03:01.552  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
,07-08 14:03:01.554  3675  3675 D HidService: Received start request. Starting profile...
,07-08 14:03:01.554  3675  3675 I bt_bluedroid: get_profile_interface hidhost
07-08 14:03:01.554  3675  3675 D HidService: setHidService(): set to: null
07-08 14:03:01.554  3675  3953 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3899099
07-08 14:03:01.554  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-08 14:03:01.555  3675  3675 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-08 14:03:01.555  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
07-08 14:03:01.555  3675  3675 D HealthService: Received start request. Starting profile...
,07-08 14:03:01.557  3675  3675 I bt_bluedroid: get_profile_interface health
,07-08 14:03:01.557  3675  3675 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-08 14:03:01.558  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
,07-08 14:03:01.558  3675  3675 D PanService: Received start request. Starting profile...
,07-08 14:03:01.558  3648  3648 D BluetoothInputDevice: Proxy object connected
,07-08 14:03:01.559  3675  3675 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-08 14:03:01.559  3675  3675 I bt_bluedroid: get_profile_interface pan
07-08 14:03:01.560  3675  3953 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-08 14:03:01.560  3648  3648 D HidProfile: Bluetooth service connected
07-08 14:03:01.560  3675  3675 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a373f68
,07-08 14:03:01.561  3675  3675 D BluetoothMapService: Received start request. Starting profile...
07-08 14:03:01.561  3675  3675 D BluetoothMapService: start()
07-08 14:03:01.562  3675  3675 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-08 14:03:01.563  3675  3675 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-08 14:03:01.563  3675  3675 D BluetoothMapAppObserver: createReceiver()
07-08 14:03:01.563  3648  3648 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:03:01.563  3648  3648 D PanProfile: Bluetooth service connected
07-08 14:03:01.563  3675  3675 D BluetoothMapAppObserver: initObservers()
07-08 14:03:01.564  3675  3675 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-08 14:03:01.564  3648  3648 D BluetoothMap: Proxy object connected
07-08 14:03:01.564  3648  3648 D MapProfile: Bluetooth service connected
07-08 14:03:01.564  3648  3648 D BluetoothMap: getConnectedDevices()
07-08 14:03:01.564  3648  3648 D BluetoothMap: Bluetooth is Not enabled
07-08 14:03:01.567  3675  3675 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:01.567  3675  3675 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:01.567  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:01.567  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:01.568  3675  3979 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:01.568  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:01.569  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:01.569  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-08 14:03:01.569  3675  3949 D BluetoothAdapterProperties: ScanMode =  20
07-08 14:03:01.569  3675  3949 D BluetoothAdapterProperties: State =  11
07-08 14:03:01.569  3675  3949 D BluetoothAdapterProperties: Setting state to 12
07-08 14:03:01.569  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-08 14:03:01.570  3675  3949 I BluetoothAdapterState: Entering OnState
07-08 14:03:01.570   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:03:01.570  3675  3953 D BluetoothAdapterProperties: Scan Mode:21
07-08 14:03:01.571  3675  3953 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:03:01.574   930  1401 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-08 14:03:01.575   930   930 D BluetoothA2dp: Proxy object connected
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:01.576  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:01.578  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:01.579  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:01.579  3552  3610 I jxcore-log: 
,07-08 14:03:01.579   930   930 D BluetoothInputDevice: Proxy object connected
07-08 14:03:01.579   930   930 D HidProfile: Bluetooth service connected
,07-08 14:03:01.579  3648  3658 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:03:01.580   930  1401 D BluetoothPbap: onBluetoothStateChange: up=true
,07-08 14:03:01.581   930   951 D BluetoothMap: onBluetoothStateChange: up=true
,07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:01.582  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:01.582   930   930 D BluetoothMap: Proxy object connected
07-08 14:03:01.582   930   930 D MapProfile: Bluetooth service connected
07-08 14:03:01.582   930   930 D BluetoothMap: getConnectedDevices()
07-08 14:03:01.582  3648  3660 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:03:01.583   791   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:01.583  3648  3658 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:03:01.584  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:01.584   791   808 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:03:01.584  3648  3660 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:03:01.585  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:01.585  3552  3610 I jxcore-log: 
07-08 14:03:01.585   791   791 D BluetoothA2dp: Proxy object connected
,07-08 14:03:01.585   791   808 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:01.586   930  1401 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:03:01.587   930   930 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:03:01.587   791   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:01.587   930   930 D PanProfile: Bluetooth service connected
,07-08 14:03:01.587  1296  1314 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:01.587  3675  3675 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:03:01.588  3675  3675 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-08 14:03:01.588   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:01.588  3675  3675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:01.589   791   791 I Telecom : BluetoothPhoneService: queryPhoneState
,07-08 14:03:01.591  3675  3675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:03:01.591  3675  3675 D ObexServerSockets: Succeed to create listening sockets 
,07-08 14:03:01.591  3675  3675 D ObexServerSockets0: startAccept()
07-08 14:03:01.591  3675  3675 D ObexServerSockets0: prepareForNewConnect()
,07-08 14:03:01.593  3675  3675 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-08 14:03:01.593  3675  3675 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-08 14:03:01.594  3675  3675 D BluetoothMapService: onReceive
07-08 14:03:01.594  3675  3675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-08 14:03:01.594  3675  3675 D BluetoothMapService: STATE_ON
07-08 14:03:01.594  3648  3648 D LocalBluetoothProfileManager: Adding local A2DP profile
07-08 14:03:01.594  3675  4003 D ObexServerSockets0: Accepting socket connection...
,07-08 14:03:01.595  3675  4004 D ObexServerSockets0: Accepting socket connection...
,07-08 14:03:01.597  3648  3648 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-08 14:03:01.600  3648  3648 D BluetoothA2dp: Proxy object connected
,07-08 14:03:01.616  3675  3675 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-08 14:03:01.616  3675  3675 D ObexServerSockets0: prepareForNewConnect()
,07-08 14:03:01.621  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:01.624  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:03:01.627  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:03:01.631  3648  3648 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:01.634   930   930 D BluetoothPbap: Proxy object connected
,07-08 14:03:01.634   930   930 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:01.635  3675  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:01.639  3648  3648 D BluetoothPbap: Proxy object connected
,07-08 14:03:01.639  3648  3648 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:01.652  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:01.664  1762  4015 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:03:01.665  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:03:01.666  3675  4019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:01.666  3675  4019 I BtOppRfcommListener: Accept thread started.
,07-08 14:03:01.686   930   947 D BluetoothHeadset: Proxy object connected
,07-08 14:03:01.686   930   930 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:01.687   791   808 D BluetoothHeadset: Proxy object connected
07-08 14:03:01.687  1296  1312 D BluetoothHeadset: Proxy object connected
07-08 14:03:01.688  1296  1312 D BluetoothHeadset: Proxy object connected
,07-08 14:03:01.688   791   791 D BluetoothHeadset: Proxy object connected
07-08 14:03:01.688   791   791 D BluetoothHeadset: Proxy object connected
07-08 14:03:01.688   791   791 D BluetoothHeadset: Proxy object connected
,07-08 14:03:01.691   930  1401 D BluetoothHeadset: Proxy object connected
,07-08 14:03:01.694  1762  4015 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-08 14:03:01.695   930   930 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:01.699  3648  3660 D BluetoothHeadset: Proxy object connected
,07-08 14:03:01.700  3648  3648 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:05.405  3675  3949 D BluetoothAdapterState: Current state: ON, message: 23
,07-08 14:03:05.405  3675  3949 D BluetoothAdapterProperties: Setting state to 13
,07-08 14:03:05.405  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-08 14:03:05.406  3675  3949 D BluetoothAdapterProperties: onBluetoothDisable()
07-08 14:03:05.426  3675  3949 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:03:05.451  3675  3675 D BluetoothMapService: onReceive
07-08 14:03:05.451  3675  3675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-08 14:03:05.451  3675  3675 D BluetoothMapService: STATE_TURNING_OFF
07-08 14:03:05.451  3675  3675 D BluetoothMapService: MAP Service closeService in
07-08 14:03:05.451  3675  3675 D BluetoothMapMasInstance0: MAP Service shutdown
,07-08 14:03:05.451  3675  3675 D ObexServerSockets0: shutdown(block = true)
07-08 14:03:05.451  3675  3675 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-08 14:03:05.451  3675  3675 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-08 14:03:05.452  3675  4003 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-08 14:03:05.452  3675  3971 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-08 14:03:05.452  3675  4004 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,07-08 14:03:05.452  3675  3675 I BtOppRfcommListener: stopping Accept Thread
,07-08 14:03:05.452  3675  4019 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-08 14:03:05.452  3675  4019 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-08 14:03:05.457  3675  3953 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:05.459  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:03:05.461  3675  3675 D HeadsetService: Received stop request...Stopping profile...
07-08 14:03:05.462  3675  3675 D A2dpService: Received stop request...Stopping profile...
,07-08 14:03:05.462  3675  3991 D A2dpStateMachine: Exit Disconnected: -1
,07-08 14:03:05.463   930   930 D BluetoothA2dp: Proxy object disconnected
,07-08 14:03:05.464   930  1401 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:05.464   930   930 D HeadsetProfile: Bluetooth service disconnected
07-08 14:03:05.464  1296  1445 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:05.465  3648  3658 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:05.465  3675  3675 D HidService: Received stop request...Stopping profile...
,07-08 14:03:05.465  3675  3675 D HidService: Stopping Bluetooth HidService
07-08 14:03:05.465   930   930 D BluetoothInputDevice: Proxy object disconnected
07-08 14:03:05.465   930   930 D HidProfile: Bluetooth service disconnected
07-08 14:03:05.466   791   791 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:05.466   791   791 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:05.466   791   791 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:05.466   791   791 D BluetoothA2dp: Proxy object disconnected
07-08 14:03:05.466  3675  3675 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:05.466  3675  3675 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:03:05.466  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:05.466  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:05.467  3675  3675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:03:05.467  3675  3675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-08 14:03:05.467  3675  3675 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:05.467  3675  3675 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:03:05.467  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:05.467  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:05.468  3675  3968 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:05.468  3675  3968 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:05.468  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-08 14:03:05.468  3675  3953 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:05.499  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:05.499  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:05.500  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:05.501  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:05.501  3675  3968 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:05.501  3675  3968 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:05.502  3675  3968 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:03:05.502  3675  3968 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:03:05.502  3675  3968 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:03:05.502  3675  3968 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:03:05.502  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-08 14:03:05.578  3675  3675 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:05.578  3675  3675 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:03:05.578  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:05.578  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:05.578  3675  3675 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:03:05.578  3675  3953 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-08 14:03:05.580  3675  3675 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-08 14:03:05.580  3675  3675 D HealthService: Received stop request...Stopping profile...
,07-08 14:03:05.581  3675  3675 D PanService: Received stop request...Stopping profile...
07-08 14:03:05.582   930   930 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:03:05.582   930   930 D PanProfile: Bluetooth service disconnected
07-08 14:03:05.582  3675  3675 D BluetoothMapService: Received stop request...Stopping profile...
07-08 14:03:05.582  3675  3675 D BluetoothMapService: stop()
07-08 14:03:05.583  3675  3675 D BluetoothMapAppObserver: deinitObservers()
,07-08 14:03:05.583  3675  3675 D BluetoothMapAppObserver: removeReceiver()
07-08 14:03:05.583   930   930 D BluetoothMap: Proxy object disconnected
07-08 14:03:05.583   930   930 D MapProfile: Bluetooth service disconnected
07-08 14:03:05.584  3675  3675 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:05.584  3675  3675 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:05.584  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:05.584  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:05.584  3675  3675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:03:05.584  3675  3953 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-08 14:03:05.584  3675  3675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-08 14:03:05.585  3675  3675 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:05.585  3675  3675 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:05.585  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:05.585  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:05.585  3675  3675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-08 14:03:05.606  3675  3675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:03:05.607  3675  3675 D BluetoothMapService: MAP Service closeService in
,07-08 14:03:05.607  3675  3675 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:05.607  3675  3675 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:05.607  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:05.607  3675  3675 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:05.607  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:03:05.607  3675  3949 D BluetoothAdapterProperties: Setting state to 15
07-08 14:03:05.607  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-08 14:03:05.608  3675  3949 I BluetoothAdapterState: Entering BleOnState
07-08 14:03:05.608   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:03:05.608  3648  3658 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:03:05.609   930   951 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:03:05.610  3648  3660 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:03:05.610   930  1401 D BluetoothPbap: onBluetoothStateChange: up=false
,07-08 14:03:05.611   930   947 D BluetoothMap: onBluetoothStateChange: up=false
,07-08 14:03:05.611  3675  3675 D BluetoothMapService: cleanup()
07-08 14:03:05.611  3675  3675 D BluetoothMapService: MAP Service closeService in
07-08 14:03:05.611  3648  3658 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:03:05.612   791   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:05.612  3648  3660 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:03:05.614  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:05.614  3552  3610 I jxcore-log: 
07-08 14:03:05.614  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:05.614  3552  3610 I jxcore-log: 
,07-08 14:03:05.621  3648  3658 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:05.621   791   808 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:03:05.621  3648  3660 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:03:05.622   791   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:05.622   930   951 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:03:05.623   791   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:05.625  1296  1314 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:05.625   930  1401 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:05.625  3675  3949 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-08 14:03:05.626  3675  3949 D BluetoothAdapterProperties: Setting state to 16
,07-08 14:03:05.626  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-08 14:03:05.627  3675  3949 D BluetoothAdapterProperties: onBleDisable
07-08 14:03:05.627  3675  3949 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:03:05.627  3675  3950 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:03:05.629  3675  3968 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-08 14:03:05.629  3675  3968 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:05.631  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:05.632  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:05.633  3675  3953 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:05.633  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:03:05.635  3648  3648 D HeadsetProfile: Bluetooth service disconnected
07-08 14:03:05.649  3648  3648 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:05.699  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:05.703  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:03:05.705  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:03:05.709  3648  3648 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:05.718  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:05.722  1762  4051 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:03:05.723  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:03:05.729  3675  3953 I bt_hci  : shut_down
,07-08 14:03:05.729  1762  4051 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-08 14:03:05.731  3675  3957 D bt_hwcfg: hw_epilog_process
,07-08 14:03:05.732  3675  3957 I bt_vendor: low_power_mode_cb
,07-08 14:03:05.756  3675  3957 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-08 14:03:05.756  3675  3957 I bt_vendor: epilog_cb
07-08 14:03:05.756  3675  3957 I bt_hci  : epilog_finished_callback
,07-08 14:03:05.758  3675  3953 I bt_hci_h4: hal_close
,07-08 14:03:05.758  3675  3953 I bt_userial_vendor: device fd = 49 close
,07-08 14:03:05.761  3675  3950 D bt_stack_manager: event_shut_down_stack finished.
07-08 14:03:05.762  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-08 14:03:05.763  3675  3949 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-08 14:03:05.763  3675  3675 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:03:05.763  3675  3675 D BtGatt.GattService: Received stop request...Stopping profile...
07-08 14:03:05.763  3675  3675 D BtGatt.GattService: stop()
07-08 14:03:05.763  3675  3675 D BtGatt.AdvertiseManager: advertise clients cleared
,07-08 14:03:05.764  3675  3675 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:05.764  3675  3675 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:05.764  3675  3675 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:05.764  3675  3675 V BluetoothAdapterState: isBleTurningOff()=true
07-08 14:03:05.764  3675  3949 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:03:05.764  3675  3949 D BluetoothAdapterProperties: Setting state to 10
07-08 14:03:05.764  3675  3949 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-08 14:03:05.764  3675  3949 I BluetoothAdapterState: Entering OffState
07-08 14:03:05.764   791   808 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-08 14:03:05.768  3675  3675 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-08 14:03:05.768  3675  3675 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:03:05.768  3675  3675 I BluetoothServiceJni: cleanupNative: return from cleanup
07-08 14:03:05.768  3675  3950 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-08 14:03:05.770  3675  3950 D bt_stack_manager: event_clean_up_stack finished.
,07-08 14:03:05.770  3675  3675 I art     : System.exit called, status: 0
,07-08 14:03:05.770  3675  3675 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:03:05.854   791  1213 I ActivityManager: Process com.android.bluetooth (pid 3675) has died
,07-08 14:03:10.403  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:10.403  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:10.410  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:10.411  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89be465 added. We now have 6 listener(s)
,07-08 14:03:10.411  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:10.414  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:10.415  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@515353a added. We now have 7 listener(s)
,07-08 14:03:10.415  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:10.416  3552  3603 I System.out: IsBluetoothEnabled
07-08 14:03:10.433  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:10.467   791   808 I ActivityManager: Start proc 4064:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-08 14:03:10.529  4064  4064 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:03:10.529  4064  4064 D AdapterServiceConfig: Adding A2dpService
07-08 14:03:10.530  4064  4064 D AdapterServiceConfig: Adding HidService
07-08 14:03:10.530  4064  4064 D AdapterServiceConfig: Adding HealthService
07-08 14:03:10.530  4064  4064 D AdapterServiceConfig: Adding PanService
07-08 14:03:10.530  4064  4064 D AdapterServiceConfig: Adding GattService
07-08 14:03:10.530  4064  4064 D AdapterServiceConfig: Adding BluetoothMapService
,07-08 14:03:10.539   791   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@661ead0:true
,07-08 14:03:10.539  4064  4064 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:03:10.541  4064  4064 I bt_bluedroid: init
,07-08 14:03:10.541  4064  4087 I BluetoothAdapterState: Entering OffState
,07-08 14:03:10.543  4064  4088 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-08 14:03:10.543  4064  4088 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:03:10.543  4064  4088 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-08 14:03:10.543  4064  4088 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-08 14:03:10.544  4064  4064 I bt_bluedroid: get_profile_interface socket
07-08 14:03:10.545  4064  4064 I bt_bluedroid: get_profile_interface sdp
,07-08 14:03:10.545  4064  4092 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-08 14:03:10.546  4064  4092 D BluetoothAdapterProperties: Name is: Nexus 5
,07-08 14:03:10.546  4064  4074 I bt_bluedroid: config_hci_snoop_log
,07-08 14:03:10.547   791   808 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-08 14:03:10.550  4064  4087 D BluetoothAdapterState: Current state: OFF, message: 0
,07-08 14:03:10.550  4064  4087 D BluetoothAdapterProperties: Setting state to 14
07-08 14:03:10.550  4064  4087 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-08 14:03:10.552  4064  4087 D BluetoothBondStateMachine: make
,07-08 14:03:10.554  4064  4094 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-08 14:03:10.556  4064  4087 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:10.557  4064  4064 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-08 14:03:10.558  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
,07-08 14:03:10.559  4064  4064 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:03:10.559  4064  4064 D BtGatt.GattService: Received start request. Starting profile...
07-08 14:03:10.559  4064  4064 D BtGatt.GattService: start()
,07-08 14:03:10.559  4064  4064 I bt_bluedroid: get_profile_interface gatt
07-08 14:03:10.559  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:10.559  4064  4064 D BtGatt.AdvertiseManager: advertise manager created
,07-08 14:03:10.563  4064  4064 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:10.563  4064  4064 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:10.563  4064  4064 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:03:10.563  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:10.564  4064  4087 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:03:10.564  4064  4087 I bt_bluedroid: enable
07-08 14:03:10.564  4064  4088 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-08 14:03:10.564  4064  4088 I bt_hci  : start_up
07-08 14:03:10.569  4064  4088 I bt_vendor: alloc value 0xb39a9631
07-08 14:03:10.569  4064  4088 I bt_vendor: init
07-08 14:03:10.569  4064  4088 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-08 14:03:10.569  4064  4088 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-08 14:03:10.605  4064  4088 D bt_hci  : start_up starting async portion
,07-08 14:03:10.606  4064  4098 I bt_hci  : event_finish_startup
07-08 14:03:10.606  4064  4098 I bt_hci_h4: hal_open
07-08 14:03:10.606  4064  4098 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-08 14:03:10.608  4064  4098 I bt_userial_vendor: device fd = 49 open
,07-08 14:03:10.695  4064  4098 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:03:10.721  4064  4098 D bt_hwcfg: Chipset BCM4335C0
,07-08 14:03:10.721  4064  4098 D bt_hwcfg: Target name = [BCM4335C0]
07-08 14:03:10.722  4064  4098 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-08 14:03:11.164  4064  4098 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:03:11.164  4064  4098 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:03:11.164  4064  4098 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:03:11.282  4064  4098 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-08 14:03:11.283  4064  4098 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-08 14:03:11.310  4064  4098 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:03:11.310  4064  4098 I bt_vendor: firmware callback
,07-08 14:03:11.310  4064  4098 I bt_hci  : firmware_config_callback
,07-08 14:03:11.322  4064  4106 I bt_btu  : btu_task pending for preload complete event
,07-08 14:03:11.322  4064  4106 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:03:11.322  4064  4106 I bt_btu  : btu_task received preload complete event
,07-08 14:03:11.333  4064  4106 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_A2D
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-08 14:03:11.334  4064  4106 I         : BTE_InitTraceLevels -- TRC_BTM
,07-08 14:03:11.336  4064  4106 I         : BTE_InitTraceLevels -- TRC_GAP
,07-08 14:03:11.336  4064  4106 I         : BTE_InitTraceLevels -- TRC_PAN
,07-08 14:03:11.337  4064  4106 I         : BTE_InitTraceLevels -- TRC_SDP
,07-08 14:03:11.337  4064  4106 I         : BTE_InitTraceLevels -- TRC_GATT
,07-08 14:03:11.337  4064  4106 I         : BTE_InitTraceLevels -- TRC_SMP
,07-08 14:03:11.337  4064  4106 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-08 14:03:11.337  4064  4106 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:03:11.572  4064  4106 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39279b5
,07-08 14:03:11.572  4064  4106 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39279b5 
,07-08 14:03:11.675  4064  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:03:11.675  4064  4092 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-08 14:03:11.695  4064  4092 D BluetoothAdapterProperties: Name is: Nexus 5
,07-08 14:03:11.697  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:11.697  4064  4092 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:11.697  4064  4092 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-08 14:03:11.697  4064  4092 D bt_hci  : do_postload posting postload work item
07-08 14:03:11.697  4064  4098 I bt_hci  : event_postload
07-08 14:03:11.697  4064  4098 I bt_vendor: sco_config_cb
07-08 14:03:11.697  4064  4098 I bt_hci  : sco_config_callback postload finished.
07-08 14:03:11.706  4064  4098 I bt_vendor: low_power_mode_cb
07-08 14:03:11.706  4064  4092 D bt_bte_conf: Device ID record 1 : primary
07-08 14:03:11.706  4064  4092 D bt_bte_conf:   vendorId            = 000f
07-08 14:03:11.706  4064  4092 D bt_bte_conf:   vendorIdSource      = 0001
07-08 14:03:11.706  4064  4092 D bt_bte_conf:   product             = 1200
07-08 14:03:11.706  4064  4092 D bt_bte_conf:   version             = 1436
,07-08 14:03:11.706  4064  4092 D bt_bte_conf:   clientExecutableURL = 
07-08 14:03:11.706  4064  4092 D bt_bte_conf:   serviceDescription  = 
07-08 14:03:11.706  4064  4092 D bt_bte_conf:   documentationURL    = 
07-08 14:03:11.706  4064  4092 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-08 14:03:11.706  4064  4088 D bt_stack_manager: event_start_up_stack finished
07-08 14:03:11.706  4064  4087 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-08 14:03:11.706  4064  4087 D BluetoothAdapterProperties: Setting state to 15
07-08 14:03:11.706  4064  4087 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:03:11.707  4064  4087 I BluetoothAdapterState: Entering BleOnState
07-08 14:03:11.708  4064  4087 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:03:11.708  4064  4087 D BluetoothAdapterProperties: Setting state to 11
07-08 14:03:11.708  4064  4087 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-08 14:03:11.711  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:11.720  4064  4064 D HeadsetService: Received start request. Starting profile...
07-08 14:03:11.721  4064  4064 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-08 14:03:11.721  4064  4064 D HeadsetStateMachine: make
07-08 14:03:11.725  4064  4087 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:11.731  4064  4064 D HeadsetStateMachine: max_hf_connections = 1
07-08 14:03:11.731  4064  4064 I bt_bluedroid: get_profile_interface handsfree
07-08 14:03:11.744  4064  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-08 14:03:11.745  4064  4092 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-08 14:03:11.767  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:11.767  4064  4064 D A2dpService: Received start request. Starting profile...
07-08 14:03:11.768  4064  4064 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-08 14:03:11.768  4064  4064 I bt_bluedroid: get_profile_interface avrcp
07-08 14:03:11.774  4064  4064 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-08 14:03:11.774  4064  4064 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-08 14:03:11.774  4064  4064 D A2dpStateMachine: make
07-08 14:03:11.777  4064  4064 I bt_bluedroid: get_profile_interface a2dp
07-08 14:03:11.778  4064  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-08 14:03:11.779  4064  4064 I BluetoothHidServiceJni: classInitNative: succeeds
07-08 14:03:11.780  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:11.780  4064  4119 D A2dpStateMachine: Enter Disconnected: -2
07-08 14:03:11.781  4064  4064 D HidService: Received start request. Starting profile...
07-08 14:03:11.781  4064  4064 I bt_bluedroid: get_profile_interface hidhost
07-08 14:03:11.781  4064  4092 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3909099
07-08 14:03:11.781  4064  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-08 14:03:11.782  4064  4064 D HidService: setHidService(): set to: null
07-08 14:03:11.782  4064  4064 I BluetoothHealthServiceJni: classInitNative: succeeds
07-08 14:03:11.783  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:11.783  4064  4064 D HealthService: Received start request. Starting profile...
07-08 14:03:11.799  4064  4064 I bt_bluedroid: get_profile_interface health
07-08 14:03:11.802  4064  4064 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-08 14:03:11.803  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:11.805  4064  4064 D PanService: Received start request. Starting profile...
07-08 14:03:11.805  4064  4064 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-08 14:03:11.805  4064  4064 I bt_bluedroid: get_profile_interface pan
07-08 14:03:11.806  4064  4092 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-08 14:03:11.809  4064  4064 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccde05a
07-08 14:03:11.811  4064  4064 D BluetoothMapService: Received start request. Starting profile...
07-08 14:03:11.811  4064  4064 D BluetoothMapService: start()
07-08 14:03:11.814  4064  4064 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-08 14:03:11.815  4064  4064 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-08 14:03:11.815  4064  4064 D BluetoothMapAppObserver: createReceiver()
,07-08 14:03:11.816  4064  4064 D BluetoothMapAppObserver: initObservers()
,07-08 14:03:11.816  4064  4064 D BluetoothMapAppObserver: getEnabledAccountItems()
07-08 14:03:11.824  4064  4064 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:11.824  4064  4064 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:11.824  4064  4064 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:11.824  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:11.824  4064  4113 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:11.825  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:11.828  4064  4064 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:11.828  4064  4087 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-08 14:03:11.828  4064  4087 D BluetoothAdapterProperties: ScanMode =  20
07-08 14:03:11.828  4064  4087 D BluetoothAdapterProperties: State =  11
,07-08 14:03:11.828  4064  4087 D BluetoothAdapterProperties: Setting state to 12
,07-08 14:03:11.828  4064  4087 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-08 14:03:11.829   930   951 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-08 14:03:11.830  4064  4087 I BluetoothAdapterState: Entering OnState
,07-08 14:03:11.830  4064  4092 D BluetoothAdapterProperties: Scan Mode:21
,07-08 14:03:11.831  4064  4092 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-08 14:03:11.832   930   930 D BluetoothA2dp: Proxy object connected
,07-08 14:03:11.832  3648  3660 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:11.833  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:11.837   930   947 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-08 14:03:11.838  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:11.839  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:11.839  3552  3610 I jxcore-log: 
07-08 14:03:11.839   930   930 D BluetoothInputDevice: Proxy object connected
,07-08 14:03:11.839   930   930 D HidProfile: Bluetooth service connected
07-08 14:03:11.840  3648  4140 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:03:11.841   930  1401 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:03:11.842   930   951 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:03:11.842  4064  4064 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-08 14:03:11.842  4064  4064 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-08 14:03:11.844  4064  4064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:03:11.844  3648  3658 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:03:11.845   791   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:11.845  3648  3660 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:03:11.846  4064  4064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-08 14:03:11.847  4064  4064 D ObexServerSockets: Succeed to create listening sockets 
07-08 14:03:11.847  4064  4064 D ObexServerSockets0: startAccept()
07-08 14:03:11.847  4064  4064 D ObexServerSockets0: prepareForNewConnect()
07-08 14:03:11.848  4064  4064 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-08 14:03:11.849  3648  4140 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:11.849  4064  4064 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-08 14:03:11.849   791   808 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:03:11.849   791   791 D BluetoothA2dp: Proxy object connected
07-08 14:03:11.850  3648  4141 D BluetoothPan: onBluetoothStateChange on: true
,07-08 14:03:11.852  4064  4142 D ObexServerSockets0: Accepting socket connection...
07-08 14:03:11.853   930   930 D BluetoothMap: Proxy object connected
07-08 14:03:11.853   930   930 D MapProfile: Bluetooth service connected
07-08 14:03:11.853   930   930 D BluetoothMap: getConnectedDevices()
07-08 14:03:11.854   791   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:11.854   930  1401 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:03:11.854  4064  4143 D ObexServerSockets0: Accepting socket connection...
,07-08 14:03:11.858  3648  3648 D BluetoothA2dp: Proxy object connected
07-08 14:03:11.859   930   930 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:03:11.859   930   930 D PanProfile: Bluetooth service connected
07-08 14:03:11.859   791   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:11.860  1296  1314 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:11.861   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:11.863   791   791 I Telecom : BluetoothPhoneService: queryPhoneState
07-08 14:03:11.864  4064  4064 D BluetoothMapService: onReceive
07-08 14:03:11.864  4064  4064 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-08 14:03:11.864  4064  4064 D BluetoothMapService: STATE_ON
07-08 14:03:11.864  3648  3648 D BluetoothInputDevice: Proxy object connected
07-08 14:03:11.864  3648  3648 D HidProfile: Bluetooth service connected
,07-08 14:03:11.868  3648  3648 D BluetoothMap: Proxy object connected
,07-08 14:03:11.869  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-08 14:03:11.869  3648  3648 D MapProfile: Bluetooth service connected
07-08 14:03:11.869  3648  3648 D BluetoothMap: getConnectedDevices()
07-08 14:03:11.870  3648  3648 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:03:11.870  3648  3648 D PanProfile: Bluetooth service connected
07-08 14:03:11.872  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:03:11.876  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:03:11.881  3648  3648 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:11.886  4064  4064 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-08 14:03:11.886  4064  4064 D ObexServerSockets0: prepareForNewConnect()
,07-08 14:03:11.888  3648  3648 D BluetoothPbap: Proxy object connected
07-08 14:03:11.888  3648  3648 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:11.890  4064  4150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:11.893   930   930 D BluetoothPbap: Proxy object connected
,07-08 14:03:11.893   930   930 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:11.899  1762  1762 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:11.904  1762  4153 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-08 14:03:11.905  1762  1762 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-08 14:03:11.918  4064  4157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:11.919  1762  4153 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-08 14:03:11.920  4064  4157 I BtOppRfcommListener: Accept thread started.
,07-08 14:03:11.946   930   951 D BluetoothHeadset: Proxy object connected
07-08 14:03:11.946   930   930 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:11.947  1296  1312 D BluetoothHeadset: Proxy object connected
07-08 14:03:11.947  3648  3660 D BluetoothHeadset: Proxy object connected
07-08 14:03:11.947  3648  3648 D HeadsetProfile: Bluetooth service connected
07-08 14:03:11.947   791   791 D BluetoothHeadset: Proxy object connected
,07-08 14:03:11.947   791   791 D BluetoothHeadset: Proxy object connected
07-08 14:03:11.947   791   791 D BluetoothHeadset: Proxy object connected
,07-08 14:03:11.950  3648  4140 D BluetoothHeadset: Proxy object connected
,07-08 14:03:11.950  3648  3648 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:11.954   791   808 D BluetoothHeadset: Proxy object connected
,07-08 14:03:11.960   791   808 D BluetoothHeadset: Proxy object connected
,07-08 14:03:11.961  1296  1422 D BluetoothHeadset: Proxy object connected
,07-08 14:03:11.961   930  1401 D BluetoothHeadset: Proxy object connected
07-08 14:03:11.962   930   930 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:12.479  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:12.485  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:12.488  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:12.488  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51b85eb added. We now have 8 listener(s)
,07-08 14:03:12.489  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:12.492  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:12.492  3552  3610 I jxcore-log: 
07-08 14:03:12.500   791  2100 D WifiService: setWifiEnabled: false pid=3552, uid=10000
,07-08 14:03:12.500   791  2100 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:03:12.513  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:12.514   791   972 D WifiService: setWifiEnabled: true pid=3552, uid=10000
07-08 14:03:12.514   791   972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:03:12.520   194   786 D SoftapController: Softap fwReload - Ok
,07-08 14:03:12.521   194   786 D CommandListener: Setting iface cfg
07-08 14:03:12.521   194   786 D CommandListener: Trying to bring down wlan0
07-08 14:03:12.522   194   786 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:03:12.523   791   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:03:13.255   791   892 D wifi    : set interface wlan0 flags (UP)
,07-08 14:03:13.255   791   892 I WifiHAL : Initializing wifi
07-08 14:03:13.255   791   892 I WifiHAL : Creating socket
,07-08 14:03:13.256   791   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-08 14:03:13.256   791   892 D wifi    : Did set static halHandle = 0x95697d30
,07-08 14:03:13.256   791   892 D wifi    : halHandle = 0x95697d30, mVM = 0xb4cfc000, mCls = 0x1412
07-08 14:03:13.256   791   892 D wifi    : array field set
07-08 14:03:13.256   791   892 I WifiNative-HAL: interface[0] = p2p0
07-08 14:03:13.256   791   892 I WifiNative-HAL: interface[1] = wlan0
,07-08 14:03:13.257   791   808 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-08 14:03:13.261   791   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-08 14:03:13.264  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:13.265   791  4185 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1788248784
07-08 14:03:13.265   791  4185 D wifi    : waitForHalEvents called, vm = 0xb4cfc000, obj = 0x1412, env = 0x8e879180
,07-08 14:03:13.320  4186  4186 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-08 14:03:13.361  4186  4186 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:03:13.370  4186  4186 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:03:13.398   791   892 D WifiConfigStore: Loading config and enabling all networks 
,07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:13.400  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:13.401  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:13.402  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:13.402  3552  3610 I jxcore-log: 
07-08 14:03:13.407   791   892 D WifiConfigStore: loaded 0 passpoint configs
07-08 14:03:13.407   791   892 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:03:13.408   791   892 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-08 14:03:13.408   791   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-08 14:03:13.409   791   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:03:13.409   791   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-08 14:03:13.409   791   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-08 14:03:13.409   791   892 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-08 14:03:13.413   791   892 D WifiNative-HAL: Setting external_sim to 1
,07-08 14:03:13.414   791   892 D wifi    : setting dfs flag to true, 0x98384550
07-08 14:03:13.414   791   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-08 14:03:13.414   791   892 D wifi    : setting scan oui 0x98384550
,07-08 14:03:13.414   791   892 D WifiHAL : Sending mac address OUI
07-08 14:03:13.414  2212  2212 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:03:13.428   791   892 E native  : do suspend true
,07-08 14:03:13.433   791   791 D RttService: SCAN_AVAILABLE : 3
,07-08 14:03:13.433   791   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-08 14:03:13.433   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:03:13.434   791   906 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-08 14:03:13.435   194   786 D CommandListener: Setting iface cfg
07-08 14:03:13.435   194   786 D CommandListener: Trying to bring up p2p0
07-08 14:03:13.435   791   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-08 14:03:13.444   791   891 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:03:13.445   791   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.547  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:14.553  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.560  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-08 14:03:14.562  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-08 14:03:14.584  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@79a826 Bundle[{}]
07-08 14:03:14.595  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.595  3552  3610 I jxcore-log: 
07-08 14:03:14.595  3552  3603 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:03:14.595  3552  3603 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-08 14:03:14.596  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-08 14:03:14.596  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-08 14:03:14.596  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-08 14:03:14.597  3552  3603 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-08 14:03:14.600  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-08 14:03:14.600  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-08 14:03:14.600  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-08 14:03:14.600  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-08 14:03:14.600  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-08 14:03:14.600  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.604  3552  3603 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 309)
07-08 14:03:14.604  3552  3603 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 309)
,07-08 14:03:14.604  3552  3603 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 309)
07-08 14:03:14.604  3552  3603 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 309)
07-08 14:03:14.605  3552  3603 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 315)
07-08 14:03:14.605  3552  3603 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 315)
07-08 14:03:14.605  3552  3603 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 315)
07-08 14:03:14.606  3552  3603 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 316)
07-08 14:03:14.606  3552  3603 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 318)
07-08 14:03:14.607  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.607  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e47cf48 added. We now have 2 listener(s)
07-08 14:03:14.608  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.608  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.608  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.609  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.609  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6b61e1 added. We now have 9 listener(s)
07-08 14:03:14.609  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:14.610  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:03:14.610  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:03:14.612  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.613  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:14.614  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.614  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.615  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.615  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.616  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.616  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22a95c7 added. We now have 3 listener(s)
07-08 14:03:14.616  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.616  3552  3610 I jxcore-log: 
07-08 14:03:14.617  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.617  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:03:14.617  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.618  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.618  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ae97f4 added. We now have 10 listener(s)
07-08 14:03:14.618  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.618  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.618  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.618  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.618  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.618  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.618  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.618  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.618  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e47cf48 removed from the list
07-08 14:03:14.618  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.618  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6b61e1 removed from the list
07-08 14:03:14.618  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.618  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.619  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.619  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.619  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.619  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6b61e1 not in the list
07-08 14:03:14.619  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.619  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.619  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.619  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ae97f4 removed from the list
07-08 14:03:14.619  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.619  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.619  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:,03:14.619  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.619  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22a95c7 removed from the list
07-08 14:03:14.619  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.619  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b3b1d added. We now have 2 listener(s)
07-08 14:03:14.620  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.620  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.620  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.620  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.620  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7493192 added. We now have 9 listener(s)
07-08 14:03:14.620  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.622  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:03:14.622  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:03:14.623  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.625  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:14.626  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.626  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.627  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.627  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.628  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.628  3552  3610 I jxcore-log: 
07-08 14:03:14.628  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.628  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btco,nnectorlib.ConnectionManager@b173f60 added. We now have 3 listener(s)
07-08 14:03:14.629  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.629  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.629  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.629  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.629  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2756c19 added. We now have 10 listener(s)
07-08 14:03:14.629  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.629  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:14.629  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:14.629  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.629  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:14.632  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.632  3552  3603 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:03:14.633  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.633  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.634  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.634  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.634  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.634  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.634  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.634  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:14.634  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.634  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b3b1d removed from the list
07-08 14:03:14.634  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.634  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeList,ener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7493192 removed from the list
07-08 14:03:14.634  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.634  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.634  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.634  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:03:14.634  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.634  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.634  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.634  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7493192 not in the list
07-08 14:03:14.638  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.639  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.639  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.639  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2756c19 removed from the list
07-08 14:03:14.639  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.639  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.639  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.639  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.639  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b173f60 removed from the list
07-08 14:03:14.639  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.639  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2de76bf added. We now have 2 listener(s)
07-08 14:03:14.640  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.641  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.641  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.641  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.641  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a0f18c added. We now have 9 listener(s)
07-08 14:03:14.641  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.642  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManag,erSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:03:14.643  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:03:14.645  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.648  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:14.649  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.650  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.650  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.650  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c560ea added. We now have 3 listener(s)
07-08 14:03:14.652  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-08 14:03:14.652  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:03:14.652  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.652  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.652  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8dbfdb added. We now have 10 listener(s)
07-08 14:03:14.652  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.652  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:14.653  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:14.653  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:14.653  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.653  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-08 14:03:14.654  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.657  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.657  3552  3603 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-08 14:03:14.657  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.657  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.657  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.657  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.657  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.657  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:14.657  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.657  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2de76bf removed from the list
07-08 14:03:14.657  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.657  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a0f18c removed from the list
07-08 14:03:14.657  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:14.658  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.658  3552  3610 I jxcore-log: 
07-08 14:03:14.658  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.658  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.659  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.659  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-08 14:03:14.659  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.659  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.659  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.659  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a0f18c not in the list
07-08 14:03:14.659  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.659  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:14.659  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.659  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8dbfdb removed from the list
07-08 14:03:14.659  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.660  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.660  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.660  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.660  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c560ea removed from the list
07-08 14:03:14.660  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.660  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff8551 added. We now have 2 listener(s)
,07-08 14:03:14.662  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.662  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.662  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.663  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.663  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810a1b6 added. We now have 9 listener(s)
07-08 14:03:14.663  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.664  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:03:14.664  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:03:14.666  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.668  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:14.669  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.669  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.669  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.669  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@521e624 added. We now have 3 listener(s)
,07-08 14:03:14.670  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.670  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:03:14.670  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.671  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.671  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@766258d added. We now have 10 listener(s)
07-08 14:03:14.671  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.671  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-08 14:03:14.671  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:14.671  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.671  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:14.671  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.672  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.673  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.673  3552  3610 I jxcore-log: 
,07-08 14:03:14.674  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-08 14:03:14.674  3552  3603 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-08 14:03:14.675  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.675  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.675  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:14.675  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:14.675  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:14.675  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:14.675  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.675  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fff8551 removed from the list
,07-08 14:03:14.675  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:14.675  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810a1b6 removed from the list
07-08 14:03:14.675  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.675  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.675  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.675  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:03:14.675  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.675  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.675  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.675  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810a1b6 not in the list
,07-08 14:03:14.675  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.676  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.676  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.676  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@766258d removed from the list
07-08 14:03:14.676  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.676  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.676  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.676  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.676  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@521e624 removed from the list
07-08 14:03:14.676  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.676  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c924f53 added. We now have 2 listener(s)
07-08 14:03:14.677  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-08 14:03:14.677  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.677  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.677  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.677  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba94090 added. We now have 9 listener(s)
07-08 14:03:14.677  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.679  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:03:14.679  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-08 14:03:14.680  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.682  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:14.683  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:14.683  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.683  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.683  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83e318e added. We now have 3 listener(s)
07-08 14:03:14.684  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-08 14:03:14.684  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.684  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.684  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.684  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7688daf added. We now have 10 listener(s)
07-08 14:03:14.684  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.684  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.684  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.684  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.684  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:14.684  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.684  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.684  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.684  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.684  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c924f53 removed from the list
07-08 14:03:14.684  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.684  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba94090 removed from the list
,07-08 14:03:14.685  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.685  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.685  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.685  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.685  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.685  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.685  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba94090 not in the list
07-08 14:03:14.685  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.685  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:14.685  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.685  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7688daf removed from the list
07-08 14:03:14.685  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.685  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.685  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.685  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:14.685  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83e318e removed from the list
07-08 14:03:14.686  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.686  3552  3610 I jxcore-log: 
07-08 14:03:14.686  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:14.686  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc added. We now have 2 listener(s)
07-08 14:03:14.687  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-08 14:03:14.687  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:14.687  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:14.687  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:14.687  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 added. We now have 9 listener(s)
07-08 14:03:14.687  3552  3603 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:14.688  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-08 14:03:14.688  3552  3603 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-08 14:03:14.689  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.691  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:14.692  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.692  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:03:14.693  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-08 14:03:14.693  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:03:14.693  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:03:14.693  3552  3603 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-08 14:03:14.693  3552  3603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-08 14:03:14.693  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-08 14:03:14.693  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-08 14:03:14.693  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:03:14.693  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.693  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.693  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.693  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.693  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.693  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.693  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:03:14.693  3552  3603 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc removed from the list
07-08 14:03:14.693  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.693  3552  3603 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 removed from the list
07-08 14:03:14.694  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.694  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.694  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:14.695  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.695  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.695  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.695  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.695  3552  3603 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-08 14:03:14.695  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:14.696  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.696  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.696  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.696  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.696  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.696  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.696  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.696  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:14.696  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
,07-08 14:03:14.696  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.696  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.696  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:14.696  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.696  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:14.696  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.696  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.697  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.697  3552  3610 I jxcore-log: 
07-08 14:03:14.697  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:03:14.697  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:03:14.698  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.698  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:14.698  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.698  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.698  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.698  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.698  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.698  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.698  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.698  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.698  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.698  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:14.698  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.698  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.698  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.698  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.698  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.698  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.698  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:14.698  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.698  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.699  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
,07-08 14:03:14.699  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.699  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.699  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.699  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.699  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.699  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.699  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.699  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:14.699  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.699  3552  3603 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:03:14.700  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.702  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:14.703  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:14.703  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.703  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:14.703  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:14.703  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:14.703  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:14.704  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.705  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.706  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.706  3552  3610 I jxcore-log: 
07-08 14:03:14.706  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.706  3552  3603 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:03:14.706  3552  3603 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:03:14.707  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.707  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.707  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:14.707  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.707  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:14.707  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:14.707  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.707  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.708  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.708  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.708  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.708  3552  3603 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:03:14.709  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.710  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:14.711  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.711  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:03:14.712  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:14.712  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:14.712  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.714  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.714  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.714  3552  3603 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-08 14:03:14.714  3552  3603 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:03:14.715  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.715  3552  3610 I jxcore-log: 
07-08 14:03:14.715  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.715  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.715  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.715  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.715  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:14.715  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:14.715  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.715  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:14.715  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
,07-08 14:03:14.715  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.715  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.716  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.716  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.716  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.716  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.716  3552  3603 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:03:14.717  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.719  3552  3603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:14.720  3552  3603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:14.720  3552  3603 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:14.720  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:14.720  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:14.720  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.720  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.720  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:14.721  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:14.722  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:14.722  3552  3610 I jxcore-log: 
07-08 14:03:14.723  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.723  3552  3603 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-08 14:03:14.723  3552  3603 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:03:14.723  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.723  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.723  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.723  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.723  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.723  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.723  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.723  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.723  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:14.723  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.723  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.723  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.724  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.724  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.724  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.724  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.724  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.724  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.724  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.724  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.725  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.725  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.725  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.725  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.725  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.725  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.725  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.725  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.725  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.725  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.725  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.725  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.725  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.725  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.725  3552  3603 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-08 14:03:14.725  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.725  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: C,onnectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.725  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.725  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.725  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.725  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.725  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.726  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.726  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.726  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.726  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.726  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.726  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.726  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.726  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.726  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.726  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-08 14:03:14.726  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.726  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.726  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.726  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.726  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.726  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.726  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.726  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.726  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.726  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.726  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.726  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.726  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.726  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.726  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.726  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.727  3552  3603 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-08 14:03:14.727  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.727  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.727  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.727  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.727  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.727  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.727  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.727  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.727  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.727  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.727  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.727  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.727  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.727  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.727  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.727  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.727  3552  3603 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-08 14:03:14.727  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.727  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.727  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.727  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.727  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.727  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.727  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.727  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.727  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.727  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.727  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.727  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.727  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.727  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.727  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.728  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.728  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:03:14.728  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:03:14.728  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:03:14.728  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:03:14.728  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:03:14.728  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:03:14.728  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.728  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.728  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.728  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.728  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.728  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.728  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.728  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.728  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.728  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.728  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.728  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.728  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.728  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.728  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.728  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.729  3552  3603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:03:14.729  3552  3603 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-08 14:03:14.729  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:03:14.729  3552  3603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:03:14.730  3552  3603 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-08 14:03:14.730  3552  3603 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:03:14.730  3552  3603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-08 14:03:14.730  3552  3603 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-08 14:03:14.731  3552  3603 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-08 14:03:14.731  3552  3603 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:03:14.731  3552  3603 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-08 14:03:14.731  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.731  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.731  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.731  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.731  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.731  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.731  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.731  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.731  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.731  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.731  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.732  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.732  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.732  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.732  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.732  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.732  3552  3603 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-08 14:03:14.732  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.732  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.732  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.732  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.732  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.732  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.732  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.732  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.732  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.732  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.732  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.732  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.732  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.732  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.732  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.732  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.733  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.733  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.733  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.733  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.733  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.733  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.733  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.733  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.733  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.733  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.733  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.733  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.733  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.733  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.733  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.733  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.733  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.733  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.733  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.733  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.733  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.733  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.733  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.733  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.733  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.733  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.733  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.734  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.734  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.734  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.734  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.734  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.734  3552  3603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-08 14:03:14.734  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.734  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.734  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.734  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.734  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.734  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.734  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.734  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.735  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.736  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.736  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.736  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.736  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.736  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.737  3552  3603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-08 14:03:14.737  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.738  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-08 14:03:14.738  3552  3603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-08 14:03:14.739  3552  3603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-08 14:03:14.739  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-08 14:03:14.739  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.739  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:03:14.739  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-08 14:03:14.739  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-08 14:03:14.739  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-08 14:03:14.739  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.739  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.739  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.739  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:03:14.739  3552  3603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:03:14.739  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:03:14.739  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.740  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.740  3552  3603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:14.740  3552  4210 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-08 14:03:14.740  3552  4210 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-08 14:03:14.740  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.740  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.740  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.740  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:03:14.740  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.740  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.740  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.740  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.740  3552  3552 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-08 14:03:14.740  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.740  3552  3552 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.740  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:03:14.740  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.740  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.740  3552  3552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:14.740  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.740  3552  3552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.740  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.740  3552  3552 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:14.740  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.740  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.740  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.740  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.743  3552  3552 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.743  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.743  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.743  3552  3552 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:14.743  3552  3552 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:14.743  3552  3552 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:14.746  3552  3552 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-08 14:03:14.746  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.746  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.746  3552  3552 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:14.746  3552  3552 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-08 14:03:14.746  3552  3552 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-08 14:03:14.746  3552  3552 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-08 14:03:14.746  3552  3603 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-08 14:03:14.746  3552  3603 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-08 14:03:14.746  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:03:14.746  3552  3603 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:03:14.747  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.747  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.747  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.747  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.747  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.747  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.747  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.747  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.747  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.747  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.747  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.747  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:14.747  3552  3603 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:14.747  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.747  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.747  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.748  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:14.748  3552  3610 I jxcore-log: 
07-08 14:03:14.749  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.749  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.749  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.749  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.749  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.749  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.749  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.749  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.749  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Liste,ner org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.749  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.749  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.749  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.749  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.749  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.749  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.749  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.750  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.750  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.750  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.750  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.750  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.750  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.750  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.750  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.750  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.750  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.750  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.750  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.750  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.750  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.750  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.750  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.750  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.750  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.750  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.750  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.750  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.750  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.750  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.750  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.750  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.751  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.751  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.751  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.751  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.751  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.751  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.751  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.751  3552  3603 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-08 14:03:14.751  3552  3603 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-08 14:03:14.751  3552  3552 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-08 14:03:14.751  3552  3603 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-08 14:03:14.752  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.752  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.752  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.752  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.752  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.752  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.752  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.752  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.752  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.752  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.752  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.752  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.752  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.752  3552  3603 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:14.752  3552  3603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:14.752  3552  3603 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:14.752  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.752  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.752  3552  3603 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@709d5bc not in the list
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.752  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.752  3552  3603 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:14.752  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.752  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.752  3552  3603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:14.752  3552  3603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:14.752  3552  3603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:14.752  3552  3603 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b77945 not in the list
07-08 14:03:14.753  3552  3603 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-08 14:03:14.753  3552  3603 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-08 14:03:14.753  3552  3603 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-08 14:03:14.753  3552  3603 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-08 14:03:14.753  3552  3603 E com.test.thalitest.ThaliTestRunner: Total duration: 29416 ms
07-08 14:03:14.753  3552  3603 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 29472ms. Plugin should use CordovaInterface.getThreadPool().
07-08 14:03:14.754  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-08 14:03:14.754  3552  3610 I jxcore-log: 
,07-08 14:03:33.551  1234  1340 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-08 14:03:33.551  1234  1340 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-08 14:03:33.613  1762  4222 I CheckinUtil: Classify the device as Phone.
,07-08 14:03:33.623  1762  4222 W FetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "cloudconfig.googleapis.com": No address associated with hostname
,07-08 14:03:33.644  1762  4224 I CheckinUtil: Classify the device as Phone.
,07-08 14:03:33.646  1762  4224 W FetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "cloudconfig.googleapis.com": No address associated with hostname
,07-08 14:03:33.661  1762  4225 I CheckinUtil: Classify the device as Phone.
,07-08 14:03:33.663  1762  4225 W FetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "cloudconfig.googleapis.com": No address associated with hostname
,07-08 14:03:33.678  1762  4226 I CheckinUtil: Classify the device as Phone.
,07-08 14:03:33.680  1762  4226 W FetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "cloudconfig.googleapis.com": No address associated with hostname
,07-08 14:03:45.270   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:03:45.290   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:03:45.610   791   894 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-08 14:04:44.833  1762  1992 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:04:44.857  1626  2898 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:04:46.946   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:04:46.973   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:05:48.642   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:05:48.671   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:06:26.810  1626  2842 V NativeCrypto: SSL shutdown failed: ssl=0x92fee600: I/O error during system call, Connection timed out
,07-08 14:06:27.737  1762  2673 V NativeCrypto: SSL shutdown failed: ssl=0xaeea2400: I/O error during system call, Connection timed out
,07-08 14:06:33.804  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:33.840  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:06:33.840  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:07:45.247  2695  2752 V NativeCrypto: SSL shutdown failed: ssl=0xb367f000: I/O error during system call, Connection timed out
,07-08 14:07:45.393  1762  2673 V NativeCrypto: SSL shutdown failed: ssl=0x9a430000: I/O error during system call, Connection timed out
,07-08 14:11:50.371   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:11:50.394   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:16:59.001  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:16:59.033  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:16:59.039  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:17:52.094   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:17:52.120   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:21:00.732   791   803 I UsageStatsService: User[0] Flushing usage stats to disk
,07-08 14:21:59.114  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:21:59.144  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:21:59.150  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:23:53.837   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:23:53.862   791   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:23:53.907  1626  4323 I EventLogChimeraService: Aggregate from 1467979283768 (log), 1467977951563 (data)
,07-08 14:23:54.055  1626  4341 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-08 14:25:09.976   791   884 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-08 14:25:09.976   791   791 V KeyguardServiceDelegate: onStartedWakingUp()
07-08 14:25:09.978   791   811 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-08 14:25:09.986  3552  3552 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-08 14:25:09.986  3552  3552 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-08 14:25:09.992   791   811 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@939a085)
,07-08 14:25:09.998   791   804 I ActivityManager: Start proc 4360:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
07-08 14:25:10.000   791  1313 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-08 14:25:10.000  3552  3552 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-08 14:25:10.000  3552  3552 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-08 14:25:10.009   198   827 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-08 14:25:10.015  1264  1409 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
07-08 14:25:10.015  1264  1409 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-08 14:25:10.015  1264  1409 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-08 14:25:10.015  1264  1402 D BrcmNfcJni: RoutingManager::commitRouting
07-08 14:25:10.015  1264  1409 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-08 14:25:10.019   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:10.024   791   892 E native  : do suspend false
,07-08 14:25:10.030   791   892 D WifiConfigStore: No blacklist allowed without epno enabled
,07-08 14:25:10.057  4360  4360 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-08 14:25:10.073  1825  1833 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-08 14:25:10.073   791   809 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-08 14:25:10.073   191   191 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
07-08 14:25:10.073   191   191 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-08 14:25:10.113  1762  1762 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-08 14:25:10.243   791   811 I DisplayPowerController: Unblocked screen on after 265 ms
,07-08 14:25:10.244   791   811 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-08 14:25:10.308   191   191 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-08 14:25:10.310   791   909 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,07-08 14:25:10.522   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:10.829  1264  1610 D NfcService: Discovery configuration equal, not updating.
,07-08 14:25:11.961   791   892 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-08 14:25:11.963   791   892 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-08 14:25:11.963   791   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:25:11.974   791   892 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-08 14:25:12.019   791   892 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-08 14:25:12.022  4186  4186 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-08 14:25:12.149  4186  4186 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:25:12.170  4186  4186 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-08 14:25:12.170  4186  4186 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-08 14:25:12.172   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:12.177   791   892 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:25:12.177   791   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:25:12.178   791   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:25:12.187   791   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:25:12.196   194   786 D CommandListener: Setting iface cfg
,07-08 14:25:12.198   791   892 D WifiStateMachine: Start Dhcp Watchdog 2
,07-08 14:25:12.206   791   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:25:12.206   791   894 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,07-08 14:25:12.208   791   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-08 14:25:12.216   791  4402 D DhcpClient: Receive thread started
,07-08 14:25:12.298   791   892 E native  : do suspend false
,07-08 14:25:12.305   791  4401 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:25:12.312   791  4402 D DhcpClient: Received packet: 50:55:27:f0:fd:0b OFFER, ip /192.168.1.118, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171371, domain null
,07-08 14:25:12.312   791  4401 D DhcpClient: Got pending lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171371 seconds
07-08 14:25:12.313   791  4401 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.118 serverid=192.168.1.1
,07-08 14:25:12.320   791  4402 D DhcpClient: Received packet: 50:55:27:f0:fd:0b ACK: your new IP /192.168.1.118, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-08 14:25:12.320   791  4401 D DhcpClient: Confirmed lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-08 14:25:12.321   194   786 D CommandListener: Setting iface cfg
,07-08 14:25:12.324   791   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-08 14:25:12.326   791  4401 D DhcpClient: Scheduling renewal in 86399s
,07-08 14:25:12.329   791   892 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-08 14:25:12.330   791   892 D WifiConfigStore: No blacklist allowed without epno enabled
07-08 14:25:12.331   791   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-08 14:25:12.332   791   894 D ConnectivityService: Adding iface wlan0 to network 101
07-08 14:25:12.340   791   892 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-08 14:25:12.371   791   894 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-08 14:25:12.372   791   894 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-08 14:25:12.373   791   894 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-08 14:25:12.374   791   894 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-08 14:25:12.375   791   894 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-08 14:25:12.385   791   894 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:25:12.390   791   894 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-08 14:25:12.390   791   894 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-08 14:25:12.390   791   894 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-08 14:25:12.390   791   892 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:25:12.390   791   894 D ConnectivityService:    accepting network in place of null
07-08 14:25:12.391   791   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:25:12.391   791   894 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.118/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:25:12.401   791  4400 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1467762, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:25:12.415   194   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:25:12.438   194   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:25:12.441   791   894 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-08 14:25:12.441   791   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:25:12.444   791   808 D Tethering: MasterInitialState.processMessage what=3
,07-08 14:25:12.447   791   894 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-08 14:25:12.459  1368  1368 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:25:12.464  3552  3552 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:25:12.466  3552  3552 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:25:12.468  3552  3610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:25:12.468  3552  3610 I jxcore-log: 
,07-08 14:25:12.488   791  4399 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.142,2a00:1450:4001:812::200e
,07-08 14:25:12.490  1626  1626 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-08 14:25:12.491  1626  2756 I iu.UploadsManager: num queued entries: 0
07-08 14:25:12.492  1626  2756 I iu.UploadsManager: num updated entries: 0
07-08 14:25:12.493  1626  2756 I iu.SyncManager: NEXT; no task
,07-08 14:25:12.538   791  4399 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jul 2016 12:25:12 GMT], X-Android-Received-Millis=[1467980712538], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467980712513]}
07-08 14:25:12.539   791   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-08 14:25:12.539   791   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-08 14:25:12.539   791   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-08 14:25:12.540   791   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:25:12.578  2212  4413 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-08 14:25:12.779   198   827 D WVCdm   : Instantiating CDM.
,07-08 14:25:12.780   198  1398 I WVCdm   : CdmEngine::OpenSession
07-08 14:25:12.780   198  1398 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-08 14:25:12.784   198  1398 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-08 14:25:12.786   198  1398 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-08 14:25:12.786   198  1398 D DrmWidevineDash: Service_Initialize: starts!
07-08 14:25:12.786   198  1398 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-08 14:25:12.786   198  1398 D QSEECOMAPI: : App is not loaded in QSEE
,07-08 14:25:12.806   198  1398 D QSEECOMAPI: : Loaded image: APP id = 3
,07-08 14:25:12.808   198  1398 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-08 14:25:12.808   198  1398 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3317000
07-08 14:25:12.808   198  1398 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3317000
,07-08 14:25:12.822   198  1398 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-08 14:25:12.822   198  1398 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-08 14:25:12.828   198  1398 D DrmWidevineDash: hlos api version =  10
,07-08 14:25:12.828   198  1398 D DrmWidevineDash: tz api version =  10
07-08 14:25:12.828   198  1398 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-08 14:25:12.828   198  1398 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-08 14:25:12.844   198  1398 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-08 14:25:12.844   198  1398 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-08 14:25:12.844   198  1398 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb25bf134
,07-08 14:25:12.850   198  1398 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-08 14:25:12.850   198  1398 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-08 14:25:12.850   198  1398 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb600c678, dataLength=8
,07-08 14:25:12.866   198  1398 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-08 14:25:12.868   198  1398 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb26a6400, wrapped_rsa_key_length=1280
,07-08 14:25:12.870  1762  4440 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-08 14:25:12.870  1762  4433 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-08 14:25:12.877   198  1398 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-08 14:25:12.877   198  1398 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-08 14:25:12.877   198   900 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-08 14:25:12.877   198   900 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-08 14:25:12.877   198   900 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-08 14:25:12.878   198   900 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb31ff0a0, idLength=0xb363cf2c
,07-08 14:25:12.891   198   900 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-08 14:25:12.891   198   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-08 14:25:12.898   198   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-08 14:25:12.898   198   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,07-08 14:25:12.898   198   900 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-08 14:25:12.898   198   900 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-08 14:25:12.904   198   900 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-08 14:25:12.904   198   900 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-08 14:25:12.905  1762  4440 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-08 14:25:12.906  1762  4433 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-08 14:25:12.911   198   900 D DrmWidevineDash: hlos api version =  10
,07-08 14:25:12.911   198   900 D DrmWidevineDash: tz api version =  10
07-08 14:25:12.911   198   900 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-08 14:25:12.911   198   900 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-08 14:25:12.917   198   900 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-08 14:25:12.917   198   900 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-08 14:25:12.918   198   900 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-08 14:25:12.924   198   900 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-08 14:25:12.924   198   900 D WVCdm   : PrepareKeyRequest: nonce=3494983391
07-08 14:25:12.924   198   900 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb3389000
07-08 14:25:12.924   198   900 D DrmWidevineDash: message_length=1639, signature=0xb34fb140, signature_length=3009662980
,07-08 14:25:12.928  1762  4440 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-08 14:25:12.929  1762  4433 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-08 14:25:12.929  1762  4433 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-08 14:25:12.934  1762  4433 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:25:13.002   198   900 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-08 14:25:13.002   198   827 I WVCdm   : CdmEngine::CloseSession
07-08 14:25:13.003   198   827 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-08 14:25:13.009   198   827 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-08 14:25:13.009   198   827 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-08 14:25:13.016   198   827 D DrmWidevineDash: Service_Uninitialize: starts!
07-08 14:25:13.016   198   827 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-08 14:25:13.016   198   827 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-08 14:25:13.017   198   827 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-08 14:25:13.017   198   827 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-08 14:25:13.150  2695  2705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-08 14:25:13.229  2695  2705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-08 14:25:13.289  2695  2705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-08 14:25:13.452  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:25:13.453  1762  1762 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-08 14:25:15.216   791   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:25:18.236   791   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:25:20.392   791   894 D ConnectivityService: handlePromptUnvalidated 101
,07-08 14:25:25.526   791   892 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,07-08 14:25:30.975   791  4400 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486336, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:25:39.969   791   811 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-08 14:25:39.970   791   811 I PowerManagerService: Sleeping (uid 1000)...
,07-08 14:25:40.141  3552  3552 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-08 14:25:40.141  3552  3552 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-08 14:25:40.160  3552  3552 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@79a826 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f15edc0, 16908290=android.view.AbsSavedState$1@f15edc0}, android:focusedViewId=100}]}]
07-08 14:25:40.160  3552  3552 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-08 14:25:40.160  3552  3552 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-08 14:25:40.160  3552  3552 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-08 14:25:40.185  1234  1234 I Keyboard.Facilitator: onFinishInput()
07-08 14:25:40.233   791   800 I art     : Background partial concurrent mark sweep GC freed 57465(3MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 24MB/36MB, paused 979us total 162.487ms
,07-08 14:25:40.599   791   811 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-08 14:25:40.617   191   191 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,07-08 14:25:40.617   791   809 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-08 14:25:40.617   191   191 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-08 14:25:40.905   191   191 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-08 14:25:40.905   791   909 D SurfaceControl: Excessive delay in setPowerMode(): 287ms
07-08 14:25:40.905  1825  1833 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-08 14:25:40.910   198   900 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-08 14:25:40.928   791   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:40.933   791   892 E native  : do suspend true
,07-08 14:25:52.377   791   892 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,TIME-OUT KILL (timeout was 1400000ms)
```
