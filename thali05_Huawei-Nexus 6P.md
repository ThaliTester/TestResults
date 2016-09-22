#### Test 83268893919c9ad_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 04:34:33.783   928  5219 D NetlinkSocketObserver: NeighborEvent{elapsedMs=188637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-22 04:34:34.065   535   535 I ServiceManager: Waiting for service AtCmdFwd...
09-22 04:34:34.246  5460  5460 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 04:34:34.252  5460  5460 D AndroidRuntime: CheckJNI is OFF
09-22 04:34:34.277  5460  5460 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 04:34:34.306  5460  5460 I Radio-JNI: register_android_hardware_Radio DONE
09-22 04:34:34.321  5460  5460 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 04:34:34.325   928  3398 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 04:34:34.366   928  3398 I ActivityManager: Start proc 5469:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 04:34:34.375  5460  5460 D AndroidRuntime: Shutting down VM
,09-22 04:34:34.706   928  3811 I WindowManager: Screenshot max retries 4 of Token{d5911a4 ActivityRecord{b512837 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{516e72f u0 Starting com.test.thalitest} drawState=4
,09-22 04:34:34.773  5469  5469 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 04:34:34.807  5469  5469 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-22 04:34:34.833  5469  5469 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 9667-9688)
09-22 04:34:34.833  5469  5469 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 04:34:34.853  5469  5469 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a5515c6}
09-22 04:34:34.853  5469  5469 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 04:34:34.853  5469  5469 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 04:34:34.858  5469  5469 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-22 04:34:34.860  5469  5469 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 04:34:34.895  5469  5469 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 04:34:34.908  5469  5469 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 04:34:34.909  5469  5469 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 04:34:34.909  5469  5469 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 04:34:34.909  5469  5469 I Adreno  : Build Date                       : 12/06/15
09-22 04:34:34.909  5469  5469 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 04:34:34.909  5469  5469 I Adreno  : Local Branch                     : mybranch17112971
09-22 04:34:34.909  5469  5469 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 04:34:34.909  5469  5469 I Adreno  : Remote Branch                    : NONE
09-22 04:34:34.909  5469  5469 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 04:34:34.952   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8599872:true
,09-22 04:34:34.981   403   403 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15290]" dev="sockfs" ino=15290 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 04:34:34.981   403   403 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15290]" dev="sockfs" ino=15290 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 04:34:34.991  5469  5469 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 04:34:34.999  5469  5469 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 04:34:35.024   403   403 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31507]" dev="sockfs" ino=31507 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 04:34:35.024   403   403 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31507]" dev="sockfs" ino=31507 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 04:34:35.026  5469  5506 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 04:34:35.027  3567  3567 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15295]" dev="sockfs" ino=15295 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 04:34:35.027  3567  3567 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15295]" dev="sockfs" ino=15295 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 04:34:35.032  5469  5493 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 04:34:35.064  5469  5506 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 04:34:35.066   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 04:34:35.140   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +431ms (total +800ms)
,09-22 04:34:35.166  5469  5469 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5469
,09-22 04:34:35.270  5469  5469 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 04:34:35.414  5469  5509 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -566490832
,09-22 04:34:35.418  5469  5509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 04:34:35.418  5469  5509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 04:34:35.418  5469  5509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 04:34:35.418  5469  5509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 04:34:35.418  5469  5509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 04:34:35.418  5469  5509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eb263f added. We now have 1 listener(s)
,09-22 04:34:35.421  5469  5509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-22 04:34:35.421  5469  5509 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 04:34:35.421  5469  5509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:34:35.422  5469  5509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 04:34:35.423  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-22 04:34:35.424  5469  5509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1f766a added. We now have 1 listener(s)
09-22 04:34:35.424  5469  5509 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 04:34:35.435   928  2981 D WifiService: New client listening to asynchronous messages
,09-22 04:34:35.436  5469  5509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 04:34:35.436  5469  5509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-22 04:34:35.436  5469  5509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 04:34:35.436  5469  5509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 04:34:35.436  5469  5509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 04:34:35.449   928   938 I ActivityManager: Start proc 5515:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-22 04:34:35.451  5469  5509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:35.451  5469  5509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-22 04:34:35.457  5469  5509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:35.458  5469  5509 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:35.458  5469  5509 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 04:34:35.458  5469  5509 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:34:35.458  5469  5509 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 04:34:35.460  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:35.462  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:35.475  5469  5469 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 04:34:35.491  5515  5515 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,09-22 04:34:35.543  5515  5528 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,09-22 04:34:35.599  5515  5528 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,09-22 04:34:35.634  5515  5528 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-22 04:34:35.665  5515  5515 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-22 04:34:35.673  5541  5541 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-395104710.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-395104710.dex
,09-22 04:34:35.706  5541  5541 I dex2oat : dex2oat took 33.718ms (threads: 2) arena alloc=139KB java alloc=37KB native alloc=1258KB free=1045KB
,09-22 04:34:35.766  5515  5515 W InstanceID/Rpc: Found 10012
,09-22 04:34:35.843  5469  5525 W jxcore-log: Initializing JXcore engine
,09-22 04:34:35.843  5469  5525 W jxcore-log: JXcore engine is ready
,09-22 04:34:35.867  5525  5525 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12002 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-22 04:34:35.867  5525  5525 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15386]" dev="sockfs" ino=15386 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 04:34:35.867  5525  5525 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 04:34:35.867  5525  5525 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[29528]" dev="sockfs" ino=29528 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 04:34:35.877  5469  5525 W jxcore-log: Starting JXcore engine
,09-22 04:34:35.934  5469  5525 W jxcore-log: Platform android
09-22 04:34:35.934  5469  5525 W jxcore-log: 
,09-22 04:34:35.934  5469  5525 W jxcore-log: Process ARCH arm
09-22 04:34:35.934  5469  5525 W jxcore-log: 
,09-22 04:34:36.029  5469  5525 I jxcore-log: JXcore Cordova bridge is ready!
09-22 04:34:36.029  5469  5525 I jxcore-log: 
,09-22 04:34:36.029  5469  5525 W jxcore-log: JXcore engine is started
,09-22 04:34:36.044  5469  5509 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 04:34:36.047  5469  5469 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 04:34:36.066   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 04:34:36.150   928   939 I ActivityManager: Killing 4877:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-22 04:34:37.067   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 04:34:38.068   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 04:34:39.068   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 04:34:40.835   928  5219 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-22 04:34:42.542  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 04:34:42.542  5469  5525 I jxcore-log: 
,09-22 04:34:42.543  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 04:34:42.543  5469  5525 I jxcore-log: 
,09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:42.547  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 04:34:42.549  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 04:34:42.551  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 04:34:42.551  5469  5525 I jxcore-log: 
,09-22 04:34:42.552  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 04:34:42.552  5469  5525 I jxcore-log: 
,09-22 04:34:42.905  5469  5525 D executeNativeTests: Running unit tests
,09-22 04:34:42.946  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 04:34:42.946  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b added. We now have 2 listener(s)
09-22 04:34:42.947  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:34:42.947  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 04:34:42.947  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:34:42.947  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:34:42.947  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 added. We now have 2 listener(s)
09-22 04:34:42.947  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 04:34:42.948  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 04:34:42.950  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:42.953  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:42.954  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:42.954  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 04:34:42.956  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 04:34:42.956  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 04:34:42.956  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 04:34:42.957  5469  5525 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 04:34:42.957  5469  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 04:34:42.957  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 04:34:42.957  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 04:34:42.957  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 04:34:42.958  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:42.958  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:42.958  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:42.958  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:42.958  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:42.958  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:34:42.959  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:34:42.959  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b removed from the list
09-22 04:34:42.959  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:42.959  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 removed from the list
09-22 04:34:42.960  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:42.960  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:42.960  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.961  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:42.961  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:34:42.962  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:42.962  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:42.962  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:42.962  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:42.964  5469  5525 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 04:34:42.964  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 04:34:42.964  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:42.964  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:42.964  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:42.964  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 04:34:42.964  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.964  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:42.964  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:42.964  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:42.967  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:42.967  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:42.967  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:42.967  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.967  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:42.967  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.968  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:42.968  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 04:34:42.968  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:42.968  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 04:34:42.971  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 04:34:42.972  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:42.972  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:42.972  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:42.972  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:42.972  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:42.972  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.972  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:42.972  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:42.972  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:42.972  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:42.972  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:42.972  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.973  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 04:34:42.973  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:42.973  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:42.973  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:42.973  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:42.973  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:42.974  5469  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 04:34:42.975  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:42.979  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:42.980  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:42.980  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:34:42.980  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:34:42.980  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 04:34:42.980  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 04:34:42.980  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:42.980  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 04:34:42.985  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:42.989  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:42.989  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 04:34:42.989  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 04:34:42.993  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 04:34:42.994  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 04:34:42.994  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 04:34:42.995  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-22 04:34:42.996  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-22 04:34:42.996  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 04:34:42.996  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-22 04:34:42.997  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 04:34:42.997  5469  5525 D BluetoothAdapter: STATE_ON
,09-22 04:34:42.999  4469  4480 D BtGatt.GattService: registerClient() - UUID=35593530-5f83-48ef-bf60-45c04bb37075
09-22 04:34:43.000  4469  4562 D BtGatt.GattService: onClientRegistered() - UUID=35593530-5f83-48ef-bf60-45c04bb37075, clientIf=5
09-22 04:34:43.001  5469  5480 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 04:34:43.002  4469  4483 D BtGatt.GattService: start scan with filters
,09-22 04:34:43.010  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 04:34:43.010  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-22 04:34:43.010  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 04:34:43.010  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 04:34:43.010  4469  4565 D BtGatt.ScanManager: handling starting scan
09-22 04:34:43.011  4469  4565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:34:43.012  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:34:43.012  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 04:34:43.012  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:34:43.013  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 04:34:43.014  5469  5525 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 04:34:43.015  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.015  5469  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 04:34:43.015  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.015  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 04:34:43.015  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.015  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 04:34:43.015  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-22 04:34:43.015  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:34:43.015  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:34:43.015  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:34:43.016  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 04:34:43.016  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 04:34:43.016  5469  5525 D BluetoothAdapter: STATE_ON
09-22 04:34:43.016  4469  4480 D BtGatt.GattService: stopScan() - queue size =1
09-22 04:34:43.017  4469  4483 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 04:34:43.017  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 04:34:43.017  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 04:34:43.017  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-22 04:34:43.017  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 04:34:43.017  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 04:34:43.017  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.018  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 04:34:43.018  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 04:34:43.018  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 04:34:43.018  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:34:43.018  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 04:34:43.019  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.019  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:34:43.019  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.019  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 04:34:43.019  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.019  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.019  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.019  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.019  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.019  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.019  5469  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 04:34:43.020  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:34:43.021  4469  4562 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 04:34:43.022  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:43.022  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:43.023  4469  4565 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 04:34:43.023  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.023  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:34:43.023  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:34:43.023  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 04:34:43.023  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 04:34:43.023  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:43.023  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 04:34:43.026  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.029  4469  4562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 04:34:43.029  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.029  4469  4565 D BtGatt.ScanManager: Starting BLE batch scan
09-22 04:34:43.029  4469  4565 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 04:34:43.029  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.031  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 04:34:43.031  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 04:34:43.035  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 04:34:43.035  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 04:34:43.035  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 04:34:43.037  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 04:34:43.037  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 04:34:43.037  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 04:34:43.037  5469  5525 D BluetoothAdapter: STATE_ON
,09-22 04:34:43.038  4469  4483 D BtGatt.GattService: registerClient() - UUID=7897aada-0a9b-46a5-81cc-048810284fac
09-22 04:34:43.039  4469  4562 D BtGatt.GattService: onClientRegistered() - UUID=7897aada-0a9b-46a5-81cc-048810284fac, clientIf=5
,09-22 04:34:43.039  5469  5479 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 04:34:43.040  4469  4480 D BtGatt.GattService: start scan with filters
09-22 04:34:43.041  4469  4562 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 04:34:43.041  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.042  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 04:34:43.042  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 04:34:43.042  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 04:34:43.042  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 04:34:43.043  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:34:43.043  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 04:34:43.043  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:34:43.044  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 04:34:43.045  5469  5525 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 04:34:43.046  4469  4562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 04:34:43.046  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.046  5469  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 04:34:43.046  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.047  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.047  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 04:34:43.047  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.047  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 04:34:43.047  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 04:34:43.047  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:34:43.047  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:34:43.047  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:34:43.047  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-22 04:34:43.047  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 04:34:43.048  5469  5525 D BluetoothAdapter: STATE_ON
09-22 04:34:43.048  4469  4711 D BtGatt.GattService: stopScan() - queue size =1
09-22 04:34:43.049  4469  4480 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 04:34:43.049  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 04:34:43.049  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 04:34:43.049  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 04:34:43.049  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 04:34:43.049  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 04:34:43.050  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.050  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 04:34:43.050  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 04:34:43.050  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 04:34:43.051  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:34:43.051  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.051  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.051  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.052  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 04:34:43.052  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.052  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.052  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.052  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.052  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.052  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.052  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.052  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.052  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.052  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 04:34:43.052  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.052  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.053  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.053  5469  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 04:34:43.053  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:34:43.055  4469  4562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 04:34:43.055  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.055  4469  4565 D BtGatt.ScanManager: stopping BLe Batch
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:43.056  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 04:34:43.057  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.057  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:34:43.057  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:34:43.057  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 04:34:43.057  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-22 04:34:43.057  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:43.057  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 04:34:43.058  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 04:34:43.058  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 04:34:43.059  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.061  4469  4562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 04:34:43.061  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.061  4469  4565 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 04:34:43.063  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 04:34:43.064  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.065  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 04:34:43.065  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 04:34:43.066  4469  4562 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 04:34:43.066  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 04:34:43.067  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 04:34:43.067  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 04:34:43.068  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 04:34:43.068  4469  4565 D BtGatt.ScanManager: handling starting scan
09-22 04:34:43.068  5469  5525 D BluetoothAdapter: STATE_ON
,09-22 04:34:43.069  4469  4480 D BtGatt.GattService: registerClient() - UUID=3aa7b3a7-4d08-4589-a9de-5a01a9e66c8e
09-22 04:34:43.069  4469  4562 D BtGatt.GattService: onClientRegistered() - UUID=3aa7b3a7-4d08-4589-a9de-5a01a9e66c8e, clientIf=5
,09-22 04:34:43.070  5469  5479 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 04:34:43.070  4469  4731 D BtGatt.GattService: start scan with filters
09-22 04:34:43.072  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 04:34:43.072  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 04:34:43.072  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 04:34:43.072  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 04:34:43.072  4469  4562 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 04:34:43.072  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.073  4469  4565 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 04:34:43.074  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:34:43.074  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-22 04:34:43.074  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:34:43.075  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 04:34:43.076  5469  5525 I io.jxcore.node.ConnectionHelper: start: OK
09-22 04:34:43.076  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.076  5469  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 04:34:43.076  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.076  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 04:34:43.076  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.076  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 04:34:43.076  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 04:34:43.076  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:34:43.076  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:34:43.076  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:34:43.076  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 04:34:43.076  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 04:34:43.077  5469  5525 D BluetoothAdapter: STATE_ON
09-22 04:34:43.077  4469  4562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 04:34:43.077  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.077  4469  4731 D BtGatt.GattService: stopScan() - queue size =1
09-22 04:34:43.077  4469  4565 D BtGatt.ScanManager: Starting BLE batch scan
09-22 04:34:43.077  4469  4565 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 04:34:43.078  4469  4483 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 04:34:43.078  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 04:34:43.078  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 04:34:43.078  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 04:34:43.078  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 04:34:43.078  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 04:34:43.079  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.079  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 04:34:43.079  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 04:34:43.079  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 04:34:43.079  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:34:43.080  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 04:34:43.080  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.080  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.080  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.080  5469  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 04:34:43.080  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.080  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.080  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.081  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.081  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:34:43.081  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
,09-22 04:34:43.081  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.081  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.081  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.081  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.083  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.083  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.083  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.083  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.083  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.083  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
,09-22 04:34:43.084  5469  5525 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-22 04:34:43.084  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.084  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.084  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.084  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.084  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.084  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:34:43.084  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.084  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.085  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.085  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.085  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.085  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.085  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.085  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.085  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.085  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 04:34:43.085  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.085  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.086  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 04:34:43.086  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.086  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.086  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.086  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.086  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.086  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.086  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
,09-22 04:34:43.086  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.086  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.086  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.086  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.086  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.086  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.086  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:34:43.088  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 04:34:43.088  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.088  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.088  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.088  4469  4562 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 04:34:43.088  5469  5525 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-22 04:34:43.088  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.088  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.088  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.088  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.088  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 04:34:43.088  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.089  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.089  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.089  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.089  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.089  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.089  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 04:34:43.089  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.089  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.089  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.090  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.090  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.090  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.090  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.091  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-22 04:34:43.091  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.091  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.091  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-22 04:34:43.091  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.091  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.091  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.091  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.091  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.091  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.091  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.091  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.091  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.091  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.091  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.092  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 04:34:43.092  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 04:34:43.092  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 04:34:43.092  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 04:34:43.092  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 04:34:43.092  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.092  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.092  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.093  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.093  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.093  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.093  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.093  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.093  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.093  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.093  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:34:43.093  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.093  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.093  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.093  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.093  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.093  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.094  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 04:34:43.094  4469  4562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 04:34:43.094  5469  5525 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 04:34:43.094  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.094  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-22 04:34:43.097  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 04:34:43.097  5469  5525 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 04:34:43.097  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-22 04:34:43.098  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 04:34:43.098  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-22 04:34:43.098  5469  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 04:34:43.098  5469  5525 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-22 04:34:43.098  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 04:34:43.098  5469  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 04:34:43.098  5469  5525 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-22 04:34:43.098  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 04:34:43.098  5469  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 04:34:43.098  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-22 04:34:43.100  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-22 04:34:43.101  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-22 04:34:43.101  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-22 04:34:43.101  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-22 04:34:43.101  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-22 04:34:43.101  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-22 04:34:43.101  5469  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 04:34:43.101  5469  5525 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-22 04:34:43.101  5469  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-22 04:34:43.102  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.102  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.102  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.102  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.102  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.102  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.102  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-22 04:34:43.102  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.102  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.102  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.102  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.102  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.102  4469  4562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 04:34:43.103  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.103  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.103  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.103  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.103  4469  4565 D BtGatt.ScanManager: stopping BLe Batch
09-22 04:34:43.103  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.103  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.103  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.103  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.104  5469  5525 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-22 04:34:43.104  5469  5600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:34:43.104  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.104  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.104  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.104  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.104  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.104  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.104  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.104  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.104  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.104  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.104  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.104  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.104  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.104  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.105  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.105  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.105  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.106  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.104  4711  4711 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32002]" dev="sockfs" ino=32002 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 04:34:43.104  4711  4711 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32002]" dev="sockfs" ino=32002 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 04:34:43.107  5469  5525 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-22 04:34:43.107  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.107  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.107  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.107  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.107  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.107  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.107  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.107  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.107  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.108  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.108  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.108  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.108  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.108  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.108  5469  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-22 04:34:43.108  4469  4562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 04:34:43.108  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.108  5469  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-22 04:34:43.108  4469  4565 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 04:34:43.108  5469  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-22 04:34:43.109  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.109  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.109  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.109  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.109  5469  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-22 04:34:43.109  5469  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-22 04:34:43.109  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 04:34:43.109  5469  5525 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-22 04:34:43.109  5469  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 04:34:43.109  5469  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-22 04:34:43.109  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 04:34:43.109  5469  5525 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-22 04:34:43.109  5469  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 04:34:43.109  5469  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 04:34:43.109  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 04:34:43.109  5469  5525 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-22 04:34:43.110  4469  4691 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-22 04:34:43.110  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.110  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.110  5469  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-22 04:34:43.110  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.110  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.110  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.110  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.110  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.110  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.110  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.110  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.110  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.110  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.110  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.110  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.110  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.111  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.111  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.111  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.111  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.111  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.111  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.111  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.111  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.111  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.111  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.111  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.111  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.111  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.111  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.111  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.111  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.111  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.111  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.111  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.111  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.112  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.112  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.112  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.112  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.112  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.112  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.112  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.112  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.112  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.112  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.112  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.112  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.114  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.114  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.114  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.114  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.114  4469  4562 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 04:34:43.114  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.115  5469  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 04:34:43.115  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:43.116  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-22 04:34:43.116  5469  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-22 04:34:43.116  5469  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-22 04:34:43.116  4469  4565 D BtGatt.ScanManager: handling starting scan
09-22 04:34:43.116  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-22 04:34:43.116  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 04:34:43.116  5469  5469 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 04:34:43.116  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.116  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 04:34:43.116  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 04:34:43.117  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 04:34:43.117  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.117  5469  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 04:34:43.117  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.117  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.117  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:34:43.117  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:34:43.117  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:34:43.117  5469  5469 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 04:34:43.117  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.117  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.117  5469  5602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:34:43.118  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.118  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.118  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.118  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.118  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.118  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.118  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.118  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.118  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.118  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.118  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.118  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:34:43.118  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.118  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:34:43.118  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.118  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.118  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.118  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.118  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.117  4480  4480 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29648]" dev="sockfs" ino=29648 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 04:34:43.119  5469  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 04:34:43.119  5469  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-22 04:34:43.119  5469  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 04:34:43.120  5469  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 04:34:43.117  4480  4480 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29648]" dev="sockfs" ino=29648 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 04:34:43.121  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.121  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.121  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.121  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.121  5469  5525 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-22 04:34:43.121  4469  4562 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 04:34:43.122  5469  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 04:34:43.122  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.122  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 04:34:43.122  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 04:34:43.122  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.122  4469  4565 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 04:34:43.122  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.122  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.122  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.122  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.122  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.122  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.122  5469  5525 I org.thaliproject.p2p.btconnectorli,b.DiscoveryManager: dispose
09-22 04:34:43.122  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.122  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.122  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.122  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.122  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.122  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.123  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.123  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.123  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.123  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.124  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.125  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.125  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.125  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.125  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.125  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.125  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.125  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.125  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.125  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.125  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.125  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.125  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.125  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.126  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.126  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.126  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.126  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.126  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:34:43.126  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:34:43.126  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:34:43.126  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:34:43.126  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.126  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.126  4469  4562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 04:34:43.126  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.126  5469  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dfb16b not in the list
09-22 04:34:43.126  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.126  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.126  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:43.126  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.126  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.126  4469  4565 D BtGatt.ScanManager: Starting BLE batch scan
09-22 04:34:43.126  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:34:43.127  4469  4565 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 04:34:43.127  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:34:43.127  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:34:43.127  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:34:43.127  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:34:43.127  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80f54c8 not in the list
09-22 04:34:43.128  5469  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-22 04:34:43.128  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 04:34:43.128  5469  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-22 04:34:43.128  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 04:34:43.128  5469  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-22 04:34:43.128  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 04:34:43.128  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-22 04:34:43.129  5469  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 04:34:43.129  5469  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 04:34:43.129  5469  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-22 04:34:43.129  5469  5525 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-22 04:34:43.130  5469  5525 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-22 04:34:43.130  5469  5525 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-22 04:34:43.130  5469  5525 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-22 04:34:43.130  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:34:43.130  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4966a6a added. We now have 2 listener(s)
09-22 04:34:43.130  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:34:43.131  5469  5525 D BluetoothAdapter: enable(): BT is already enabled..!
09-22 04:34:43.131   928  3560 D WifiService: setWifiEnabled: true pid=5469, uid=10077
09-22 04:34:43.131   928  3560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 04:34:43.132  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:34:43.132  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73cb5b added. We now have 3 listener(s)
09-22 04:34:43.132  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:34:43.135  4469  4562 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 04:34:43.135  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 04:34:43.137  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:34:43.138  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca57ff8 added. We now have 4 listener(s)
09-22 04:34:43.138  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:34:43.139  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:34:43.139  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1453cd1 added. We now have 5 listener(s)
09-22 04:34:43.139  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:34:43.139  4469  4562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 04:34:43.139  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.140   928   938 D WifiService: setWifiEnabled: false pid=5469, uid=10077
09-22 04:34:43.140   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 04:34:43.143   928  2978 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-22 04:34:43.143   928  2978 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-22 04:34:43.143   928  2978 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 04:34:43.144   928  2978 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 04:34:43.145  4469  4562 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 04:34:43.145  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.145  4469  4565 D BtGatt.ScanManager: stopping BLe Batch
09-22 04:34:43.145  4469  4558 D BluetoothAdapterState: Current state: ON, message: 23
09-22 04:34:43.145  4469  4558 D BluetoothAdapterProperties: Setting state to 13
09-22 04:34:43.145  4469  4558 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 04:34:43.147  4469  4558 D BluetoothAdapterProperties: onBluetoothDisable()
09-22 04:34:43.147  4469  4558 I BluetoothAdapterState: Entering PendingCommandState
09-22 04:34:43.148  4469  4469 D BluetoothMapService: onReceive
09-22 04:34:43.148  4469  4469 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 04:34:43.148  4469  4469 D BluetoothMapService: STATE_TURNING_OFF
09-22 04:34:43.148  4469  4469 D BluetoothMapService: MAP Service closeService in
09-22 04:34:43.148  4469  4469 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 04:34:43.148  4469  4469 D ObexServerSockets0: shutdown(block = true)
09-22 04:34:43.149  4469  4469 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 04:34:43.149  4469  4733 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-22 04:34:43.149  4469  4469 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 04:34:43.149  4469  4691 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 04:34:43.150  4469  4734 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 04:34:43.151  4469  4469 I BtOppRfcommListener: stopping Accept Thread
09-22 04:34:43.152  4469  5159 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 04:34:43.152  4469  5159 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 04:34:43.153  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:43.153  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:43.154  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.154  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.154   928  5220 D DhcpClient: Clearing IP address
09-22 04:34:43.155   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-22 04:34:43.161   507   921 D CommandListener: Setting iface cfg
09-22 04:34:43.162   928  5221 D DhcpClient: Receive thread stopped
09-22 04:34:43.169  3614  5275 V NativeCrypto: Read error: ssl=0x7f5ad38380: I/O error during system call, Connection timed out
09-22 04:34:43.170  3614  5275 V NativeCrypto: SSL shutdown failed: ssl=0x7f5ad38380: I/O error during system call, Broken pipe
09-22 04:34:43.172   928   941 I ActivityManager: Start proc 5605:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-22 04:34:43.172   928  3567 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-22 04:34:43.173   928  5218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-22 04:34:43.173  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:34:43.173  4469  4562 D BluetoothAdapterProperties: Scan Mode:20
09-22 04:34:43.174  4469  4558 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-22 04:34:43.175  4469  4562 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 04:34:43.176  4469  4469 D HeadsetService: Received stop request...Stopping profile...
09-22 04:34:43.176  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.176  4469  4565 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 04:34:43.177  3540  3963 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:43.177   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:43.178  3125  3742 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:43.178  3125  3125 D HeadsetProfile: Bluetooth service disconnected
,09-22 04:34:43.178   928   928 D BluetoothHeadset: Proxy object disconnected
,09-22 04:34:43.178   928   928 D BluetoothHeadset: Proxy object disconnected
,09-22 04:34:43.178  4469  4469 D A2dpService: Received stop request...Stopping profile...
09-22 04:34:43.178  4469  4723 D A2dpStateMachine: Exit Disconnected: -1
09-22 04:34:43.179  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:43.179  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:43.179  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.179  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 04:34:43.179  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:34:43.180   928  5218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-22 04:34:43.181   928  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-22 04:34:43.181   928  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-22 04:34:43.182   928   928 D BluetoothA2dp: Proxy object disconnected
09-22 04:34:43.182   928  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-22 04:34:43.183  3125  3125 D BluetoothA2dp: Proxy object disconnected
,09-22 04:34:43.183  4469  4469 D HidService: Received stop request...Stopping profile...
09-22 04:34:43.183  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.183  4469  4469 D HidService: Stopping Bluetooth HidService
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 04:34:43.183  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:43.183   533   533 E Parcel  : Reading a NULL string not supported here.
09-22 04:34:43.183   928  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-22 04:34:43.183   928  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-22 04:34:43.184  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.184  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:43.185   928   928 D RttService: SCAN_AVAILABLE : 1
09-22 04:34:43.185   928  3091 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-22 04:34:43.186  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:43.186  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:43.188  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:43.188  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 04:34:43.189  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.189  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:43.189   928  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-22 04:34:43.190  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:43.190  3502  3668 W QCNEJ   : |CORE| network lost: 100
09-22 04:34:43.191  3502  3668 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 04:34:43.192  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.192  4469  4469 V BluetoothAdapterState: isTurningOn()=false
,09-22 04:34:43.192  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.192  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:43.192  3125  3125 D BluetoothInputDevice: Proxy object disconnected
09-22 04:34:43.193  3125  3125 D HidProfile: Bluetooth service disconnected
09-22 04:34:43.194  4469  4469 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 04:34:43.194  4469  4469 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 04:34:43.194  4469  4681 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:43.194  4469  4681 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 04:34:43.194  4469  4681 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:43.194  4469  4469 D HealthService: Received stop request...Stopping profile...
09-22 04:34:43.194  4469  4562 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 04:34:43.195  4469  4562 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 04:34:43.195  4469  4562 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 04:34:43.195  4469  4562 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:34:43.195  4469  4469 D PanService: Received stop request...Stopping profile...
09-22 04:34:43.197  4469  4469 D BluetoothMapService: Received stop request...Stopping profile...
09-22 04:34:43.197  4469  4469 D BluetoothMapService: stop()
09-22 04:34:43.197  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-22 04:34:43.197  3125  3125 D PanProfile: Bluetooth service disconnected
,09-22 04:34:43.198  4469  4469 D BluetoothMapAppObserver: deinitObservers()
09-22 04:34:43.198  4469  4469 D BluetoothMapAppObserver: removeReceiver()
,09-22 04:34:43.201  4469  4469 D SapService: Received stop request...Stopping profile...
,09-22 04:34:43.201  4469  4469 V SapService: stop()
09-22 04:34:43.202  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.202  4469  4469 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:43.202  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.202  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:43.205  4469  4562 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-22 04:34:43.205  4469  4681 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:43.205  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.205  4469  4681 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:43.205  4469  4469 V BluetoothAdapterState: isTurningOn()=false
,09-22 04:34:43.205  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.205  4469  4681 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 04:34:43.205  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:43.205  4469  4681 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 04:34:43.205  4469  4681 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 04:34:43.205  4469  4681 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 04:34:43.205  4469  4469 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-22 04:34:43.205  4469  4469 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 04:34:43.205  4469  4562 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 04:34:43.205  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:43.206  4469  4469 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 04:34:43.206  4469  4562 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 04:34:43.206  4469  4469 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.206  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:43.206  4469  4469 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 04:34:43.206  4469  4469 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 04:34:43.207  4469  4469 D BluetoothMapService: MAP Service closeService in
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:34:43.208  4469  4469 D BluetoothMapService: cleanup()
09-22 04:34:43.208  4469  4469 D BluetoothMapService: MAP Service closeService in
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.208  4469  4469 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:43.209  4469  4558 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 04:34:43.209  4469  4558 D BluetoothAdapterProperties: Setting state to 15
09-22 04:34:43.209  4469  4558 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 04:34:43.209  4469  4558 I BluetoothAdapterState: Entering BleOnState
09-22 04:34:43.209   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:43.210  3125  3139 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 04:34:43.211  3125  3125 D BluetoothMap: Proxy object disconnected
09-22 04:34:43.211   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:43.211  3125  3125 D MapProfile: Bluetooth service disconnected
09-22 04:34:43.211  3125  3742 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 04:34:43.212  3125  3139 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 04:34:43.212   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 04:34:43.213  3125  3138 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:43.213   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 04:34:43.213  3540  3574 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:43.214  3125  3742 D BluetoothPan: onBluetoothStateChange on: false
09-22 04:34:43.215  3125  3139 D BluetoothMap: onBluetoothStateChange: up=false
09-22 04:34:43.215   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:43.215  4469  4558 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 04:34:43.216  4469  4558 D BluetoothAdapterProperties: Setting state to 16
09-22 04:34:43.216  4469  4558 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 04:34:43.216  4469  4558 D BluetoothAdapterProperties: onBleDisable
09-22 04:34:43.217  4469  4558 I BluetoothAdapterState: Entering PendingCommandState
09-22 04:34:43.217  4469  4559 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 04:34:43.218  4469  4562 D BluetoothAdapterProperties: Scan Mode:20
09-22 04:34:43.218  4469  4681 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 04:34:43.218  4469  4681 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:43.219  5605  5605 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-22 04:34:43.221  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.221  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:43.221  5469  5469 V io.jxcore.node.Connectiv,ityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:43.224  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:43.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:43.225  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.226  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.240   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 04:34:43.240   507   921 D TetherController: Setting IP forward enable = 0
,09-22 04:34:43.240  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 04:34:43.242   928  2978 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-22 04:34:43.242   928  2978 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 04:34:43.244   928  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-22 04:34:43.245   928  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-22 04:34:43.245   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-22 04:34:43.246   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d85cd65:true
09-22 04:34:43.248   928   945 D Tethering: MasterInitialState.processMessage what=3
09-22 04:34:43.249  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 04:34:43.250  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:43.252  4248  4248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5dc1712 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-22 04:34:43.252  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:43.254  4829  4829 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-22 04:34:43.264   928  3811 I ActivityManager: Start proc 5630:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-22 04:34:43.265  4920  4936 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-22 04:34:43.267  4920  4936 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-22 04:34:43.267  4920  4936 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 04:34:43.267  4920  4936 E SarControlService: no key has been found,reset the power
09-22 04:34:43.267  4920  4961 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 04:34:43.267  4920  4961 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 04:34:43.267  4920  4961 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 04:34:43.268  4949  4949 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 04:34:43.268  4949  4949 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-22 04:34:43.269  4920  4961 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 04:34:43.269  4920  4961 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 04:34:43.269  4920  4961 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 04:34:43.269  4949  4949 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 04:34:43.270  4949  4949 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 04:34:43.272  4949  4963 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b854c08 HexData = [00000000ea03000000000000ffffffff]
09-22 04:34:43.272  4949  4963 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 04:34:43.272  4949  4963 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-22 04:34:43.272  4949  4949 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 04:34:43.272  4920  4931 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-22 04:34:43.279  4949  4963 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b854c08 HexData = [00000000eb03000000000000ffffffff]
,09-22 04:34:43.279  4949  4963 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 04:34:43.279  4949  4963 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-22 04:34:43.279  4949  4949 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 04:34:43.280  4920  4932 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-22 04:34:43.291  5605  5605 D LocalBluetoothProfileManager: Adding local MAP profile
,09-22 04:34:43.293  5605  5605 D BluetoothMap: Create BluetoothMap proxy object
,09-22 04:34:43.300   507   921 E Netd    : netlink response contains error (No such file or directory)
,09-22 04:34:43.300   507   921 D TetherController: Setting IP forward enable = 0
,09-22 04:34:43.301   928  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-22 04:34:43.302   928  2978 D DhcpClient: doQuit
09-22 04:34:43.303   928  2978 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 04:34:43.303   928  5220 D DhcpClient: onQuitting
,09-22 04:34:43.304  3636  3636 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-22 04:34:43.308  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:43.308  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:43.309  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.309  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:43.311  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:43.311  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:34:43.312  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 04:34:43.312  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:43.314  5630  5630 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
09-22 04:34:43.316  5605  5605 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-22 04:34:43.320  3636  3636 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 04:34:43.325  3636  3636 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-22 04:34:43.327  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,09-22 04:34:43.331   928   939 I ActivityManager: Killing 4248:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-22 04:34:43.353  3636  3636 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 04:34:43.375  3636  3636 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 04:34:43.425  4469  4562 I bt_hci  : shut_down
,09-22 04:34:43.427  4469  4566 D bt_hwcfg: hw_epilog_process
,09-22 04:34:43.427  4469  4566 I bt_vendor: low_power_mode_cb
,09-22 04:34:43.430  4469  4566 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 04:34:43.430  4469  4566 I bt_vendor: epilog_cb
09-22 04:34:43.430  4469  4566 I bt_hci  : epilog_finished_callback
,09-22 04:34:43.432  4469  4562 I bt_hci_h4: hal_close
,09-22 04:34:43.432  4469  4562 I bt_userial_vendor: device fd = 54 close
,09-22 04:34:43.478  4308  4308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 04:34:43.478   928  2978 D wifi    : In wifi stop Hal
09-22 04:34:43.478   928  2978 D wifi    : halHandle = 0x7f6abb13e0, mVM = 0x7f756cd140, mCls = 0x200b32
09-22 04:34:43.478   928  3634 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 04:34:43.478   928  3634 D WifiHAL : Got a signal to exit!!!
09-22 04:34:43.478   928  3634 I WifiHAL : Exit wifi_event_loop
09-22 04:34:43.479   928  2978 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 04:34:43.479   928  2978 E WifiHAL : Event processing terminated
09-22 04:34:43.479   928  2978 D wifi    : In wifi cleaned up handler
09-22 04:34:43.479   928  2978 I WifiHAL : Internal cleanup completed
09-22 04:34:43.481  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:43.483  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:43.483  3485  4020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 04:34:43.502   928  3634 D wifi    : set interface wlan0 flags (DOWN)
,09-22 04:34:43.503   928  2978 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 04:34:43.539  4469  4559 D bt_stack_manager: event_shut_down_stack finished.
,09-22 04:34:43.539  4469  4558 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-22 04:34:43.541  4469  4558 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-22 04:34:43.541  4469  4469 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 04:34:43.542  4469  4469 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 04:34:43.542  4469  4469 D BtGatt.GattService: stop()
09-22 04:34:43.542  4469  4469 D BtGatt.AdvertiseManager: advertise clients cleared
,09-22 04:34:43.543  4469  4469 V BluetoothAdapterState: isTurningOff()=false
,09-22 04:34:43.543  4469  4469 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:43.543  4469  4469 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:43.543  4469  4469 V BluetoothAdapterState: isBleTurningOff()=true
09-22 04:34:43.544  4469  4558 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 04:34:43.544  4469  4558 D BluetoothAdapterProperties: Setting state to 10
09-22 04:34:43.544  4469  4558 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 04:34:43.544  4469  4558 I BluetoothAdapterState: Entering OffState
,09-22 04:34:43.545   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-22 04:34:43.549  5630  5630 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.549  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 04:34:43.550  5630  5630 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.550  5630  5630 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.550  5630  5630 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.550  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.551  5630  5630 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:583)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.551  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.551  4469  4469 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 04:34:43.552  4469  4469 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 04:34:43.552  4469  4469 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 04:34:43.553  4469  4559 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-22 04:34:43.555  5630  5630 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.555  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.556  5630  5630 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.556  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.557  5630  5630 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:34:43.557  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:34:43.565  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 04:34:43.568  4469  4559 D bt_stack_manager: event_clean_up_stack finished.
09-22 04:34:43.570  4469  4469 I art     : System.exit called, status: 0
09-22 04:34:43.570  4469  4469 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 04:34:43.590  5605  5605 D DockEventReceiver: finishStartingService: stopping service
09-22 04:34:43.591   928  3560 I ActivityManager: Killing 5249:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
09-22 04:34:43.616   928  3166 I ActivityManager: Process com.android.bluetooth (pid 4469) has died
09-22 04:34:43.618  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 04:34:43.618  5469  5469 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 04:34:43.629   928   939 I ActivityManager: Start proc 5669:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-22 04:34:43.702  5669  5669 D AdapterServiceConfig: Adding HeadsetService
,09-22 04:34:43.702  5669  5669 D AdapterServiceConfig: Adding A2dpService
09-22 04:34:43.702  5669  5669 D AdapterServiceConfig: Adding HidService
09-22 04:34:43.702  5669  5669 D AdapterServiceConfig: Adding HealthService
09-22 04:34:43.702  5669  5669 D AdapterServiceConfig: Adding PanService
09-22 04:34:43.702  5669  5669 D AdapterServiceConfig: Adding GattService
09-22 04:34:43.703  5669  5669 D AdapterServiceConfig: Adding BluetoothMapService
09-22 04:34:43.703  5669  5669 D AdapterServiceConfig: Adding SapService
,09-22 04:34:43.705   928   945 D Tethering: InitialState.processMessage what=4
,09-22 04:34:43.707   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 04:34:43.709   928  3584 I ActivityManager: Killing 5262:com.android.chrome/u0a39 (adj 15): empty #17
,09-22 04:34:43.775  3923  3923 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-22 04:34:43.779  3923  3923 D SystemUpdateService: onCreate
,09-22 04:34:43.783  3923  3923 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-22 04:34:43.787  3923  5681 I SystemUpdateService: active receiver: enabled
,09-22 04:34:43.792  3923  3923 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-22 04:34:43.797  3923  5246 I iu.UploadsManager: num queued entries: 0
,09-22 04:34:43.801  3923  5681 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 04:34:43.803  3923  3923 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 04:34:43.805  3923  3923 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 04:34:43.806  3923  5246 I iu.UploadsManager: num updated entries: 0
,09-22 04:34:43.808  3923  5246 I iu.SyncManager: NEXT; no task
,09-22 04:34:43.809  3923  5681 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-22 04:34:43.810  3923  5681 I SystemUpdateService: now status is 0 (complete)
09-22 04:34:43.810  3923  5681 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-22 04:34:43.810  3923  5681 I SystemUpdateService: file has been verified
09-22 04:34:43.810  3923  5681 I SystemUpdateService: OTA package size = 21989297
,09-22 04:34:43.817   928  3602 I ActivityManager: Start proc 5683:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-22 04:34:43.831  3923  5681 I SystemUpdateService: showing system update notification
,09-22 04:34:43.849  5683  5683 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-22 04:34:43.852  5683  5683 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 04:34:43.860  5683  5683 D SprintDMHelper: simOperator: 
,09-22 04:34:43.860  5683  5683 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 04:34:43.872   928   938 I ActivityManager: Start proc 5695:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-22 04:34:43.877  3923  3923 D SystemUpdateService: onDestroy
,09-22 04:34:43.880   928  3560 I ActivityManager: Killing 5279:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-22 04:34:43.967  5630  5660 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-22 04:34:43.986  4308  5709 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 04:34:43.994   928  3811 I ActivityManager: Start proc 5710:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-22 04:34:43.997   928  3811 I ActivityManager: Killing 4572:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-22 04:34:44.014   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb042bc:true
,09-22 04:34:44.060  5710  5710 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-22 04:34:44.244   928  5232 I ActivityManager: Killing 5330:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-22 04:34:44.275   928  3567 I ActivityManager: Start proc 5724:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-22 04:34:44.307  5724  5724 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-22 04:34:44.314   928  3602 I ActivityManager: Killing 3399:android.process.acore/u0a2 (adj 15): empty #17
,09-22 04:34:46.181   928  3584 D WifiService: setWifiEnabled: true pid=5469, uid=10077
09-22 04:34:46.181   928  3584 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 04:34:46.190   507   921 D SoftapController: Softap fwReload - Ok
,09-22 04:34:46.194   507   921 D CommandListener: Setting iface cfg
,09-22 04:34:46.195   507   921 D CommandListener: Trying to bring down wlan0
,09-22 04:34:46.200   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-22 04:34:46.204   928  2978 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 04:34:46.811   928  2978 D wifi    : set interface wlan0 flags (UP)
09-22 04:34:46.815   928  2978 I WifiHAL : Initializing wifi
09-22 04:34:46.815   928  2978 I WifiHAL : Creating socket
09-22 04:34:46.819   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-22 04:34:46.821   928  2978 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 04:34:46.821   928  2978 D wifi    : Did set static halHandle = 0x7f6abb13e0
09-22 04:34:46.821   928  2978 D wifi    : halHandle = 0x7f6abb13e0, mVM = 0x7f756cd140, mCls = 0x10146a
,09-22 04:34:46.822   928  2978 D wifi    : array field set
09-22 04:34:46.822   928  2978 I WifiNative-HAL: interface[0] = wlan0
,09-22 04:34:46.824   928  5742 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547251491808
09-22 04:34:46.825   928  5742 D wifi    : waitForHalEvents called, vm = 0x7f756cd140, obj = 0x10146a, env = 0x7f6ac4de40
,09-22 04:34:46.896  5743  5743 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 04:34:46.917  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 04:34:46.925  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 04:34:46.925  5743  5743 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 04:34:46.926   928  2978 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-22 04:34:46.933  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:46.938  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:46.943   928  2978 D WifiConfigStore: Loading config and enabling all networks 
,09-22 04:34:46.946  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:46.946  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:46.946  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:46.946  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:46.947  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:46.947  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:46.947  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:46.947  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:34:46.952   928  2978 D WifiConfigStore: loaded 0 passpoint configs
,09-22 04:34:46.952   928  2978 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 04:34:46.952   928  2978 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-22 04:34:46.953   928  2978 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-22 04:34:46.953   928  2978 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-22 04:34:46.954   928  2978 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-22 04:34:46.954   928  2978 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 04:34:46.954   928  2978 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 04:34:46.957   928  2978 D WifiNative-HAL: Setting external_sim to 1
,09-22 04:34:46.957  4308  4308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 04:34:46.958   928  2978 D wifi    : setting dfs flag to true, 0x7f5d8ffaa0
09-22 04:34:46.958   928  2978 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 04:34:46.958   928  2978 D wifi    : setting scan oui 0x7f5d8ffaa0
09-22 04:34:46.958   928  2978 D WifiHAL : Sending mac address OUI
,09-22 04:34:46.963   928  2978 E native  : do suspend false
,09-22 04:34:46.972   928  2978 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-22 04:34:46.972   928   928 D RttService: SCAN_AVAILABLE : 3
09-22 04:34:46.972   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 04:34:46.972   928  3091 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 04:34:46.973   507   921 D CommandListener: Setting iface cfg
,09-22 04:34:46.977   928  2968 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-22 04:34:46.977   928  2968 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 04:34:46.986   928  2968 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 04:34:46.986   928  2968 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 04:34:46.991   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=201847 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-22 04:34:49.190   928   939 D WifiService: setWifiEnabled: false pid=5469, uid=10077
09-22 04:34:49.190   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 04:34:49.196   928   928 D RttService: SCAN_AVAILABLE : 1
,09-22 04:34:49.196   928  3091 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 04:34:49.210   928  2978 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 04:34:49.212   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-22 04:34:49.220   928  2978 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 04:34:49.222  5743  5743 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-22 04:34:49.231  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:49.231  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:34:49.231  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:49.232  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:49.234  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:49.234  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:49.234  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 04:34:49.235  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:49.239  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 04:34:49.245  5743  5743 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 04:34:49.249  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 04:34:49.352   928  2978 D wifi    : In wifi stop Hal
,09-22 04:34:49.353   928  2978 D wifi    : halHandle = 0x7f6abb13e0, mVM = 0x7f756cd140, mCls = 0x10146a
09-22 04:34:49.353   928  5742 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 04:34:49.353   928  5742 D WifiHAL : Got a signal to exit!!!
09-22 04:34:49.353   928  5742 I WifiHAL : Exit wifi_event_loop
09-22 04:34:49.354   928  2978 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 04:34:49.354   928  2978 E WifiHAL : Event processing terminated
09-22 04:34:49.355   928  2978 D wifi    : In wifi cleaned up handler
09-22 04:34:49.355   928  2978 I WifiHAL : Internal cleanup completed
09-22 04:34:49.357  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:49.357  4308  4308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 04:34:49.359  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:49.362  3485  4020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 04:34:49.383   928  5742 D wifi    : set interface wlan0 flags (DOWN)
,09-22 04:34:49.384   928  2978 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 04:34:49.590   928   945 D Tethering: InitialState.processMessage what=4
,09-22 04:34:49.596   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 04:34:52.231   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a63931:true
,09-22 04:34:52.232  5669  5669 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 04:34:52.238  5669  5669 I bt_bluedroid: init
,09-22 04:34:52.238  5669  5747 I BluetoothAdapterState: Entering OffState
,09-22 04:34:52.242  5669  5748 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 04:34:52.243  5669  5748 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 04:34:52.243  5669  5748 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-22 04:34:52.243  5669  5748 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 04:34:52.244  5669  5669 I bt_bluedroid: get_profile_interface socket
,09-22 04:34:52.248  5669  5669 I bt_bluedroid: get_profile_interface sdp
,09-22 04:34:52.248  5669  5751 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 04:34:52.252  5669  5751 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 04:34:52.258  5669  5679 I bt_bluedroid: config_hci_snoop_log
09-22 04:34:52.261   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 04:34:52.268  5669  5747 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 04:34:52.269  5669  5747 D BluetoothAdapterProperties: Setting state to 14
,09-22 04:34:52.269  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 04:34:52.273  5669  5747 D BluetoothBondStateMachine: make
,09-22 04:34:52.276  5669  5752 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 04:34:52.281  5669  5747 I BluetoothAdapterState: Entering PendingCommandState
,09-22 04:34:52.283  5669  5669 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 04:34:52.287  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:34:52.288  5669  5669 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 04:34:52.289  5669  5669 D BtGatt.GattService: Received start request. Starting profile...
,09-22 04:34:52.289  5669  5669 D BtGatt.GattService: start()
09-22 04:34:52.289  5669  5669 I bt_bluedroid: get_profile_interface gatt
,09-22 04:34:52.290  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:34:52.291  5669  5669 D BtGatt.AdvertiseManager: advertise manager created
,09-22 04:34:52.297  5669  5669 V BluetoothAdapterState: isTurningOff()=false
,09-22 04:34:52.298  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:52.298  5669  5669 V BluetoothAdapterState: isBleTurningOn()=true
09-22 04:34:52.298  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:52.298  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 04:34:52.300  5669  5747 I bt_bluedroid: bt_bluedroid
,09-22 04:34:52.300  5669  5748 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 04:34:52.300  5669  5748 I bt_hci  : start_up
,09-22 04:34:52.308  5669  5748 I bt_vendor: alloc value 0xf3b6c871
09-22 04:34:52.308  5669  5748 I bt_vendor: init
,09-22 04:34:52.308  5669  5748 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 04:34:52.309  5669  5748 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 04:34:52.420  5669  5748 D bt_hci  : start_up starting async portion
,09-22 04:34:52.421  5669  5755 I bt_hci  : event_finish_startup
,09-22 04:34:52.421  5669  5755 I bt_hci_h4: hal_open
,09-22 04:34:52.422  5669  5755 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 04:34:52.426  5669  5755 I bt_userial_vendor: device fd = 54 open
09-22 04:34:52.421  5756  5756 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 04:34:52.439  5669  5755 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 04:34:52.442  5669  5755 D bt_hwcfg: Chipset BCM4358A3
,09-22 04:34:52.442  5669  5755 D bt_hwcfg: Target name = [BCM4358A3]
09-22 04:34:52.443  5669  5755 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 04:34:52.850  5669  5755 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 04:34:52.850  5669  5755 D bt_hwcfg: Settlement delay -- 100 ms
,09-22 04:34:52.850  5669  5755 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 04:34:52.985  5669  5755 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-22 04:34:52.985  5669  5755 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 04:34:52.987  5669  5755 I bt_hwcfg: vendor lib fwcfg completed
09-22 04:34:52.987  5669  5755 I bt_vendor: firmware callback
,09-22 04:34:52.987  5669  5755 I bt_hci  : firmware_config_callback
,09-22 04:34:52.997  5669  5760 I bt_btu  : btu_task pending for preload complete event
,09-22 04:34:52.998  5669  5760 I bt_btu_task: Bluetooth chip preload is complete
,09-22 04:34:52.999  5669  5760 I bt_btu  : btu_task received preload complete event
,09-22 04:34:53.007  5669  5760 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 04:34:53.007  5669  5760 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 04:34:53.007  5669  5760 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 04:34:53.007  5669  5760 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-22 04:34:53.007  5669  5760 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_SDP
,09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 04:34:53.008  5669  5760 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 04:34:53.009  5669  5760 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 04:34:53.009  5669  5760 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 04:34:53.093  5669  5760 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3aea549
,09-22 04:34:53.093  5669  5760 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3aea549 
,09-22 04:34:53.111  5669  5751 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 04:34:53.112  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 04:34:53.113  5669  5751 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 04:34:53.115  5669  5751 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 04:34:53.117  5669  5751 D BluetoothAdapterProperties: Scan Mode:20
,09-22 04:34:53.119  5669  5751 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-22 04:34:53.119  5669  5751 D bt_hci  : do_postload posting postload work item
09-22 04:34:53.119  5669  5755 I bt_hci  : event_postload
,09-22 04:34:53.119  5669  5755 I bt_vendor: sco_config_cb
09-22 04:34:53.119  5669  5755 I bt_hci  : sco_config_callback postload finished.
09-22 04:34:53.122  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:53.126  5669  5751 D bt_bte_conf: Device ID record 1 : primary
09-22 04:34:53.126  5669  5751 D bt_bte_conf:   vendorId            = 000f
09-22 04:34:53.126  5669  5751 D bt_bte_conf:   vendorIdSource      = 0001
09-22 04:34:53.126  5669  5751 D bt_bte_conf:   product             = 1200
,09-22 04:34:53.126  5669  5751 D bt_bte_conf:   version             = 1436
09-22 04:34:53.126  5669  5751 D bt_bte_conf:   clientExecutableURL = 
09-22 04:34:53.126  5669  5751 D bt_bte_conf:   serviceDescription  = 
,09-22 04:34:53.126  5669  5751 D bt_bte_conf:   documentationURL    = 
09-22 04:34:53.127  5669  5751 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 04:34:53.127  5669  5748 D bt_stack_manager: event_start_up_stack finished
09-22 04:34:53.129  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:53.129  5669  5755 I bt_vendor: low_power_mode_cb
09-22 04:34:53.130  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-22 04:34:53.131  5669  5747 D BluetoothAdapterProperties: Setting state to 15
09-22 04:34:53.131  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 04:34:53.133  5669  5747 I BluetoothAdapterState: Entering BleOnState
,09-22 04:34:53.137  5669  5747 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 04:34:53.137  5669  5747 D BluetoothAdapterProperties: Setting state to 11
,09-22 04:34:53.137  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-22 04:34:53.141  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:34:53.142  5669  5669 D HeadsetService: Received start request. Starting profile...
09-22 04:34:53.145  5669  5669 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-22 04:34:53.146  5669  5669 D HeadsetStateMachine: make
09-22 04:34:53.148  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:53.151  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:53.155  5669  5747 I BluetoothAdapterState: Entering PendingCommandState
,09-22 04:34:53.159  5669  5669 D HeadsetStateMachine: max_hf_connections = 1
09-22 04:34:53.159  5669  5669 I bt_bluedroid: get_profile_interface handsfree
09-22 04:34:53.160  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-22 04:34:53.160  5669  5751 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-22 04:34:53.164  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:34:53.164  5669  5669 D A2dpService: Received start request. Starting profile...
,09-22 04:34:53.165  5669  5669 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 04:34:53.166  5669  5669 I bt_bluedroid: get_profile_interface avrcp
,09-22 04:34:53.173  5669  5669 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 04:34:53.173  5669  5669 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 04:34:53.173  5669  5669 D A2dpStateMachine: make
09-22 04:34:53.175  5669  5669 I bt_bluedroid: get_profile_interface a2dp
,09-22 04:34:53.175  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-22 04:34:53.176  5669  5769 D A2dpStateMachine: Enter Disconnected: -2
09-22 04:34:53.177  5669  5669 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 04:34:53.178  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:34:53.179  5605  5605 D BluetoothInputDevice: Proxy object connected
,09-22 04:34:53.179  5669  5669 D HidService: Received start request. Starting profile...
09-22 04:34:53.179  5669  5669 I bt_bluedroid: get_profile_interface hidhost
09-22 04:34:53.179  5669  5669 D HidService: setHidService(): set to: null
09-22 04:34:53.179  5669  5751 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3acb56d
09-22 04:34:53.180  5605  5605 D HidProfile: Bluetooth service connected
09-22 04:34:53.180  5669  5669 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 04:34:53.180  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-22 04:34:53.181  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:34:53.181  5669  5669 D HealthService: Received start request. Starting profile...
,09-22 04:34:53.183  5669  5669 I bt_bluedroid: get_profile_interface health
09-22 04:34:53.184  5669  5669 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-22 04:34:53.185  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:34:53.186  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 04:34:53.186  5669  5669 D PanService: Received start request. Starting profile...
,09-22 04:34:53.187  5605  5605 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 04:34:53.187  5669  5669 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 04:34:53.187  5669  5669 I bt_bluedroid: get_profile_interface pan
09-22 04:34:53.187  5669  5751 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-22 04:34:53.189  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:34:53.190  5669  5669 D BluetoothMapService: Received start request. Starting profile...
,09-22 04:34:53.190  5669  5669 D BluetoothMapService: start()
09-22 04:34:53.193  5669  5669 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-22 04:34:53.193  5669  5669 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 04:34:53.194  5669  5669 D BluetoothMapAppObserver: createReceiver()
09-22 04:34:53.195  5669  5669 D BluetoothMapAppObserver: initObservers()
09-22 04:34:53.195  5669  5669 D BluetoothMapAppObserver: getEnabledAccountItems()
09-22 04:34:53.198  5605  5605 D PanProfile: Bluetooth service connected
09-22 04:34:53.198  5605  5605 D BluetoothMap: Proxy object connected
09-22 04:34:53.199  5605  5605 D MapProfile: Bluetooth service connected
09-22 04:34:53.199  5605  5605 D BluetoothMap: getConnectedDevices()
09-22 04:34:53.199  5605  5605 D BluetoothMap: Bluetooth is Not enabled
,09-22 04:34:53.200  5669  5669 V SapService: SapBinder()
09-22 04:34:53.200  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:34:53.204  5669  5669 D SapService: Received start request. Starting profile...
09-22 04:34:53.204  5669  5669 V SapService: start()
,09-22 04:34:53.207  5669  5669 V BluetoothAdapterState: isTurningOff()=false
,09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-22 04:34:53.208  5669  5765 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isTurningOn()=true
,09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:53.208  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:53.209  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:53.210  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:34:53.211  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:53.211  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-22 04:34:53.211  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:53.211  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:34:53.211  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 04:34:53.211  5669  5747 D BluetoothAdapterProperties: ScanMode =  20
09-22 04:34:53.211  5669  5747 D BluetoothAdapterProperties: State =  11
,09-22 04:34:53.213  5669  5751 D BluetoothAdapterProperties: Scan Mode:21
09-22 04:34:53.213  5669  5747 D BluetoothAdapterProperties: Setting state to 12
09-22 04:34:53.213  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 04:34:53.213  5669  5751 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 04:34:53.213   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:34:53.213  5669  5747 I BluetoothAdapterState: Entering OnState
,09-22 04:34:53.214  5605  5616 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-22 04:34:53.215  3125  3742 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:53.218  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:53.219  5669  5669 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 04:34:53.219  3125  3125 D BluetoothInputDevice: Proxy object connected
09-22 04:34:53.219  3125  3125 D HidProfile: Bluetooth service connected
09-22 04:34:53.219  5669  5669 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 04:34:53.220   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:34:53.220  5605  5617 D BluetoothPan: onBluetoothStateChange on: true
09-22 04:34:53.220  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:53.220  3125  3138 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 04:34:53.221  5669  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:34:53.222  3125  3742 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 04:34:53.223  5669  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:53.224  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:53.224  3125  3139 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:34:53.225  5669  5669 D ObexServerSockets: Succeed to create listening sockets 
09-22 04:34:53.225  5605  5616 D BluetoothMap: onBluetoothStateChange: up=true
09-22 04:34:53.225  5669  5669 D ObexServerSockets0: startAccept()
09-22 04:34:53.225  5669  5669 D ObexServerSockets0: prepareForNewConnect()
,09-22 04:34:53.225   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 04:34:53.226  3540  3963 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:34:53.226  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:53.227  3125  3138 D BluetoothPan: onBluetoothStateChange on: true
09-22 04:34:53.227  5669  5669 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 04:34:53.227  5669  5669 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 04:34:53.228  5669  5774 D ObexServerSockets0: Accepting socket connection...
,09-22 04:34:53.228  5669  5775 D ObexServerSockets0: Accepting socket connection...
09-22 04:34:53.229  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 04:34:53.229  3125  3125 D PanProfile: Bluetooth service connected
,09-22 04:34:53.229  3125  3138 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 04:34:53.230  3125  3125 D BluetoothA2dp: Proxy object connected
09-22 04:34:53.230   928   928 D BluetoothA2dp: Proxy object connected
09-22 04:34:53.232   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:34:53.232  5605  5617 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 04:34:53.232  3125  3125 D BluetoothMap: Proxy object connected
09-22 04:34:53.232  3125  3125 D MapProfile: Bluetooth service connected
09-22 04:34:53.232  3125  3125 D BluetoothMap: getConnectedDevices()
,09-22 04:34:53.235  5669  5669 D BluetoothMapService: onReceive
,09-22 04:34:53.235  5669  5669 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 04:34:53.235  5669  5669 D BluetoothMapService: STATE_ON
09-22 04:34:53.236   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-22 04:34:53.237  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:53.238  5669  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:34:53.238  5605  5605 D LocalBluetoothProfileManager: Adding local A2DP profile
09-22 04:34:53.238  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:53.240  5669  5776 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 04:34:53.240  5669  5776 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 04:34:53.243  5605  5605 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-22 04:34:53.249  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 04:34:53.251  5605  5605 D BluetoothA2dp: Proxy object connected
,09-22 04:34:53.255  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 04:34:53.259  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,09-22 04:34:53.262  3125  3125 D BluetoothPbap: Proxy object connected
09-22 04:34:53.262  5605  5605 D BluetoothPbap: Proxy object connected
09-22 04:34:53.262  3125  3125 D PbapServerProfile: Bluetooth service connected
,09-22 04:34:53.263  5605  5605 D PbapServerProfile: Bluetooth service connected
,09-22 04:34:53.265  5669  5669 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-22 04:34:53.265  5669  5669 D ObexServerSockets0: prepareForNewConnect()
,09-22 04:34:53.273  5669  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 04:34:53.287  5669  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 04:34:53.288  5669  5785 I BtOppRfcommListener: Accept thread started.
,09-22 04:34:53.315  3540  3574 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.316   928   928 D BluetoothHeadset: Proxy object connected
09-22 04:34:53.316  3125  3742 D BluetoothHeadset: Proxy object connected
09-22 04:34:53.316  3125  3125 D HeadsetProfile: Bluetooth service connected
09-22 04:34:53.316   928   928 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.316   928   928 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.320   928   945 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.325  3125  3139 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.325  3125  3125 D HeadsetProfile: Bluetooth service connected
,09-22 04:34:53.327  3540  5059 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.332   928   945 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.347  5605  5616 D BluetoothHeadset: Proxy object connected
,09-22 04:34:53.348  5605  5605 D HeadsetProfile: Bluetooth service connected
,09-22 04:34:55.208  5669  5747 D BluetoothAdapterState: Current state: ON, message: 23
,09-22 04:34:55.208  5669  5747 D BluetoothAdapterProperties: Setting state to 13
09-22 04:34:55.208  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 04:34:55.209  5669  5747 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 04:34:55.211  5669  5747 I BluetoothAdapterState: Entering PendingCommandState
09-22 04:34:55.215  5669  5669 D BluetoothMapService: onReceive
,09-22 04:34:55.216  5669  5669 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 04:34:55.217  5669  5669 D BluetoothMapService: STATE_TURNING_OFF
09-22 04:34:55.217  5669  5669 D BluetoothMapService: MAP Service closeService in
09-22 04:34:55.217  5669  5669 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 04:34:55.219  5669  5669 D ObexServerSockets0: shutdown(block = true)
09-22 04:34:55.220  5669  5669 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 04:34:55.220  5669  5774 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-22 04:34:55.220  5669  5669 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 04:34:55.220  5669  5762 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 04:34:55.220  5669  5775 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 04:34:55.220  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:55.220  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:55.221  5669  5669 I BtOppRfcommListener: stopping Accept Thread
09-22 04:34:55.221  5669  5785 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 04:34:55.221  5669  5785 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 04:34:55.222  5669  5751 D BluetoothAdapterProperties: Scan Mode:20
09-22 04:34:55.222  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-22 04:34:55.223  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 04:34:55.223  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:34:55.223  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 04:34:55.227  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:34:55.227  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 04:34:55.229  5469  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 04:34:55.230  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:34:55.232  5669  5669 D HeadsetService: Received stop request...Stopping profile...
09-22 04:34:55.232  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:55.233  5605  5605 D DockEventReceiver: finishStartingService: stopping service
09-22 04:34:55.234  5605  5616 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:55.234  3540  3571 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:55.235   928   928 D BluetoothHeadset: Proxy object disconnected
,09-22 04:34:55.235  3125  3138 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:55.235   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:55.236   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 04:34:55.237  5605  5605 D HeadsetProfile: Bluetooth service disconnected
09-22 04:34:55.238  3125  3125 D HeadsetProfile: Bluetooth service disconnected
09-22 04:34:55.239  5669  5669 D A2dpService: Received stop request...Stopping profile...
09-22 04:34:55.240  5669  5769 D A2dpStateMachine: Exit Disconnected: -1
09-22 04:34:55.240  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 04:34:55.241   928   928 D BluetoothA2dp: Proxy object disconnected
09-22 04:34:55.242  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:55.242  5669  5669 D HidService: Received stop request...Stopping profile...
09-22 04:34:55.242  5669  5669 D HidService: Stopping Bluetooth HidService
09-22 04:34:55.243  3125  3125 D BluetoothA2dp: Proxy object disconnected
,09-22 04:34:55.243  3125  3125 D BluetoothInputDevice: Proxy object disconnected
09-22 04:34:55.243  3125  3125 D HidProfile: Bluetooth service disconnected
09-22 04:34:55.243  5669  5669 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:55.243  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:55.244  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.244  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:34:55.244  5605  5605 D BluetoothA2dp: Proxy object disconnected
09-22 04:34:55.245  5605  5605 D BluetoothInputDevice: Proxy object disconnected
09-22 04:34:55.245  5605  5605 D HidProfile: Bluetooth service disconnected
,09-22 04:34:55.246  5669  5669 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 04:34:55.246  5669  5669 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 04:34:55.246  5669  5760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:55.246  5669  5760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:55.246  5669  5760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 04:34:55.248  5669  5669 V BluetoothAdapterState: isTurningOff()=true
,09-22 04:34:55.248  3125  3125 D BluetoothPbap: Proxy object disconnected
09-22 04:34:55.248  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:55.248  3125  3125 D PbapServerProfile: Bluetooth service disconnected
09-22 04:34:55.248  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.248  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:55.249  5605  5605 D BluetoothPbap: Proxy object disconnected
09-22 04:34:55.249  5605  5605 D PbapServerProfile: Bluetooth service disconnected
09-22 04:34:55.249  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 04:34:55.249  5669  5751 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 04:34:55.250  5669  5760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:55.250  5669  5760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:55.250  5669  5760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 04:34:55.251  5669  5760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 04:34:55.251  5669  5760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 04:34:55.251  5669  5760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 04:34:55.251  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 04:34:55.251  5669  5669 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:55.251  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:55.251  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.251  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:55.252  5669  5669 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 04:34:55.252  5669  5669 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-22 04:34:55.252  5669  5751 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 04:34:55.253  5669  5669 D HealthService: Received stop request...Stopping profile...
,09-22 04:34:55.257  5669  5669 D PanService: Received stop request...Stopping profile...
,09-22 04:34:55.258  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 04:34:55.258  3125  3125 D PanProfile: Bluetooth service disconnected
09-22 04:34:55.258  5669  5669 D BluetoothMapService: Received stop request...Stopping profile...
09-22 04:34:55.258  5669  5669 D BluetoothMapService: stop()
09-22 04:34:55.258  5669  5669 D BluetoothMapAppObserver: deinitObservers()
09-22 04:34:55.258  5669  5669 D BluetoothMapAppObserver: removeReceiver()
,09-22 04:34:55.257  5605  5605 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-22 04:34:55.261  5605  5605 D PanProfile: Bluetooth service disconnected
09-22 04:34:55.262  5605  5605 D BluetoothMap: Proxy object disconnected
09-22 04:34:55.262  5605  5605 D MapProfile: Bluetooth service disconnected
09-22 04:34:55.262  3125  3125 D BluetoothMap: Proxy object disconnected
09-22 04:34:55.263  3125  3125 D MapProfile: Bluetooth service disconnected
,09-22 04:34:55.265  5669  5669 D SapService: Received stop request...Stopping profile...
,09-22 04:34:55.265  5669  5669 V SapService: stop()
09-22 04:34:55.267  5669  5669 V BluetoothAdapterState: isTurningOff()=true
,09-22 04:34:55.267  5669  5669 V BluetoothAdapterState: isTurningOn()=false
,09-22 04:34:55.267  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.267  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:55.267  5669  5669 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 04:34:55.267  5669  5751 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 04:34:55.267  5669  5669 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 04:34:55.268  5669  5669 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:55.268  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:55.268  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.268  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:55.268  5669  5669 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 04:34:55.268  5669  5669 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-22 04:34:55.269  5669  5669 D BluetoothMapService: MAP Service closeService in
09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isTurningOff()=true
,09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isTurningOn()=false
,09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:34:55.269  5669  5669 D BluetoothMapService: cleanup()
,09-22 04:34:55.269  5669  5669 D BluetoothMapService: MAP Service closeService in
09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isTurningOff()=true
09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.269  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:34:55.270  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 04:34:55.270  5669  5747 D BluetoothAdapterProperties: Setting state to 15
09-22 04:34:55.270  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 04:34:55.270  5669  5747 I BluetoothAdapterState: Entering BleOnState
09-22 04:34:55.270   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:55.270  5605  5616 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 04:34:55.271  3125  3138 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 04:34:55.272   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:55.272  5605  5617 D BluetoothPan: onBluetoothStateChange on: false
09-22 04:34:55.273  5605  5616 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:55.273  3125  3742 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 04:34:55.274  3125  3139 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 04:34:55.275  3125  3138 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:55.276  5605  5617 D BluetoothMap: onBluetoothStateChange: up=false
09-22 04:34:55.277   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 04:34:55.277  3540  3780 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:55.278  3125  3742 D BluetoothPan: onBluetoothStateChange on: false
09-22 04:34:55.279  5605  5616 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 04:34:55.279  3125  3139 D BluetoothMap: onBluetoothStateChange: up=false
09-22 04:34:55.280   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 04:34:55.280  5605  5617 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 04:34:55.280  5669  5747 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 04:34:55.281  5669  5747 D BluetoothAdapterProperties: Setting state to 16
09-22 04:34:55.281  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 04:34:55.283  5669  5747 D BluetoothAdapterProperties: onBleDisable
09-22 04:34:55.283  5669  5747 I BluetoothAdapterState: Entering PendingCommandState
09-22 04:34:55.283  5669  5748 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 04:34:55.284  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 04:34:55.285  5669  5760 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 04:34:55.285  5669  5760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 04:34:55.285  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:55.286  5669  5751 D BluetoothAdapterProperties: Scan Mode:20
09-22 04:34:55.286  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:55.287  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:34:55.289  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:34:55.293  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 04:34:55.297  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,09-22 04:34:55.494  5669  5751 I bt_hci  : shut_down
,09-22 04:34:55.500  5669  5755 D bt_hwcfg: hw_epilog_process
,09-22 04:34:55.501  5669  5755 I bt_vendor: low_power_mode_cb
,09-22 04:34:55.503  5669  5755 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 04:34:55.504  5669  5755 I bt_vendor: epilog_cb
09-22 04:34:55.504  5669  5755 I bt_hci  : epilog_finished_callback
,09-22 04:34:55.508  5669  5751 I bt_hci_h4: hal_close
,09-22 04:34:55.509  5669  5751 I bt_userial_vendor: device fd = 54 close
,09-22 04:34:55.620  5669  5748 D bt_stack_manager: event_shut_down_stack finished.
,09-22 04:34:55.621  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-22 04:34:55.627  5669  5747 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-22 04:34:55.627  5669  5669 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 04:34:55.628  5669  5669 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 04:34:55.628  5669  5669 D BtGatt.GattService: stop()
,09-22 04:34:55.628  5669  5669 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 04:34:55.632  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-22 04:34:55.632  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-22 04:34:55.632  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:34:55.633  5669  5669 V BluetoothAdapterState: isBleTurningOff()=true
,09-22 04:34:55.633  5669  5747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 04:34:55.633  5669  5747 D BluetoothAdapterProperties: Setting state to 10
09-22 04:34:55.634  5669  5747 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 04:34:55.635  5669  5747 I BluetoothAdapterState: Entering OffState
,09-22 04:34:55.636   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-22 04:34:55.653  5669  5669 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-22 04:34:55.653  5669  5669 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 04:34:55.653  5669  5669 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-22 04:34:55.656  5669  5748 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 04:34:55.664  5669  5669 I art     : System.exit called, status: 0
,09-22 04:34:55.664  5669  5669 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 04:34:55.700   928  3584 I ActivityManager: Process com.android.bluetooth (pid 5669) has died
,09-22 04:34:58.205  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:34:58.205  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:35:01.213  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 04:35:01.214  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e19c237 added. We now have 6 listener(s)
09-22 04:35:01.214  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 04:35:01.221  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 04:35:01.221  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7aea3a4 added. We now have 7 listener(s)
09-22 04:35:01.221  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 04:35:01.223  5469  5525 I System.out: IsBluetoothEnabled
,09-22 04:35:01.232  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:01.252   928   945 I ActivityManager: Start proc 5793:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 04:35:01.319  5793  5793 D AdapterServiceConfig: Adding HeadsetService
09-22 04:35:01.319  5793  5793 D AdapterServiceConfig: Adding A2dpService
09-22 04:35:01.319  5793  5793 D AdapterServiceConfig: Adding HidService
09-22 04:35:01.320  5793  5793 D AdapterServiceConfig: Adding HealthService
09-22 04:35:01.320  5793  5793 D AdapterServiceConfig: Adding PanService
09-22 04:35:01.320  5793  5793 D AdapterServiceConfig: Adding GattService
09-22 04:35:01.320  5793  5793 D AdapterServiceConfig: Adding BluetoothMapService
09-22 04:35:01.320  5793  5793 D AdapterServiceConfig: Adding SapService
,09-22 04:35:01.331   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9902ad6:true
,09-22 04:35:01.332  5793  5793 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 04:35:01.336  5793  5793 I bt_bluedroid: init
,09-22 04:35:01.337  5793  5805 I BluetoothAdapterState: Entering OffState
,09-22 04:35:01.339  5793  5806 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-22 04:35:01.339  5793  5806 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 04:35:01.339  5793  5806 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 04:35:01.339  5793  5806 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 04:35:01.340  5793  5793 I bt_bluedroid: get_profile_interface socket
,09-22 04:35:01.342  5793  5809 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 04:35:01.342  5793  5793 I bt_bluedroid: get_profile_interface sdp
09-22 04:35:01.344  5793  5809 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 04:35:01.347  5793  5804 I bt_bluedroid: config_hci_snoop_log
,09-22 04:35:01.348   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 04:35:01.353  5793  5805 D BluetoothAdapterState: Current state: OFF, message: 0
09-22 04:35:01.353  5793  5805 D BluetoothAdapterProperties: Setting state to 14
09-22 04:35:01.353  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-22 04:35:01.354  5793  5805 D BluetoothBondStateMachine: make
09-22 04:35:01.356  5793  5811 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 04:35:01.359  5793  5805 I BluetoothAdapterState: Entering PendingCommandState
,09-22 04:35:01.361  5793  5793 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-22 04:35:01.363  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:35:01.363  5793  5793 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 04:35:01.364  5793  5793 D BtGatt.GattService: Received start request. Starting profile...
09-22 04:35:01.364  5793  5793 D BtGatt.GattService: start()
09-22 04:35:01.365  5793  5793 I bt_bluedroid: get_profile_interface gatt
09-22 04:35:01.366  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:35:01.366  5793  5793 D BtGatt.AdvertiseManager: advertise manager created
,09-22 04:35:01.372  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,09-22 04:35:01.372  5793  5793 V BluetoothAdapterState: isTurningOn()=false
09-22 04:35:01.372  5793  5793 V BluetoothAdapterState: isBleTurningOn()=true
09-22 04:35:01.372  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:35:01.373  5793  5805 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 04:35:01.374  5793  5805 I bt_bluedroid: bt_bluedroid
09-22 04:35:01.374  5793  5806 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 04:35:01.375  5793  5806 I bt_hci  : start_up
,09-22 04:35:01.379  5793  5806 I bt_vendor: alloc value 0xf3bbf871
,09-22 04:35:01.380  5793  5806 I bt_vendor: init
09-22 04:35:01.380  5793  5806 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 04:35:01.380  5793  5806 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 04:35:01.498  5793  5806 D bt_hci  : start_up starting async portion
09-22 04:35:01.499  5793  5814 I bt_hci  : event_finish_startup
09-22 04:35:01.499  5793  5814 I bt_hci_h4: hal_open
09-22 04:35:01.499  5793  5814 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 04:35:01.497  5815  5815 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 04:35:01.503  5793  5814 I bt_userial_vendor: device fd = 54 open
,09-22 04:35:01.520  5793  5814 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 04:35:01.524  5793  5814 D bt_hwcfg: Chipset BCM4358A3
,09-22 04:35:01.524  5793  5814 D bt_hwcfg: Target name = [BCM4358A3]
09-22 04:35:01.525  5793  5814 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 04:35:02.039  5793  5814 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 04:35:02.039  5793  5814 D bt_hwcfg: Settlement delay -- 100 ms
,09-22 04:35:02.039  5793  5814 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 04:35:02.175  5793  5814 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 04:35:02.175  5793  5814 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-22 04:35:02.177  5793  5814 I bt_hwcfg: vendor lib fwcfg completed
,09-22 04:35:02.178  5793  5814 I bt_vendor: firmware callback
,09-22 04:35:02.178  5793  5814 I bt_hci  : firmware_config_callback
,09-22 04:35:02.187  5793  5817 I bt_btu  : btu_task pending for preload complete event
09-22 04:35:02.188  5793  5817 I bt_btu_task: Bluetooth chip preload is complete
,09-22 04:35:02.188  5793  5817 I bt_btu  : btu_task received preload complete event
,09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_A2D
,09-22 04:35:02.194  5793  5817 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_BTM
09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_SDP
,09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_SMP
,09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 04:35:02.195  5793  5817 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 04:35:02.291  5793  5817 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b3d549
09-22 04:35:02.291  5793  5817 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b3d549 
,09-22 04:35:02.312  5793  5809 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 04:35:02.314  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 04:35:02.315  5793  5809 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 04:35:02.319  5793  5809 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 04:35:02.322  5793  5809 D BluetoothAdapterProperties: Scan Mode:20
,09-22 04:35:02.322  5793  5809 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 04:35:02.323  5793  5809 D bt_hci  : do_postload posting postload work item
09-22 04:35:02.323  5793  5814 I bt_hci  : event_postload
09-22 04:35:02.323  5793  5814 I bt_vendor: sco_config_cb
09-22 04:35:02.323  5793  5814 I bt_hci  : sco_config_callback postload finished.
,09-22 04:35:02.326  5793  5809 D bt_bte_conf: Device ID record 1 : primary
09-22 04:35:02.327  5793  5809 D bt_bte_conf:   vendorId            = 000f
09-22 04:35:02.327  5793  5809 D bt_bte_conf:   vendorIdSource      = 0001
09-22 04:35:02.327  5793  5809 D bt_bte_conf:   product             = 1200
09-22 04:35:02.327  5793  5809 D bt_bte_conf:   version             = 1436
09-22 04:35:02.327  5793  5809 D bt_bte_conf:   clientExecutableURL = 
,09-22 04:35:02.327  5793  5809 D bt_bte_conf:   serviceDescription  = 
09-22 04:35:02.327  5793  5809 D bt_bte_conf:   documentationURL    = 
09-22 04:35:02.327  5793  5809 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 04:35:02.328  5793  5806 D bt_stack_manager: event_start_up_stack finished
,09-22 04:35:02.329  5793  5805 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 04:35:02.330  5793  5805 D BluetoothAdapterProperties: Setting state to 15
09-22 04:35:02.330  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 04:35:02.331  5793  5805 I BluetoothAdapterState: Entering BleOnState
09-22 04:35:02.332  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:02.336  5793  5814 I bt_vendor: low_power_mode_cb
,09-22 04:35:02.337  5793  5805 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 04:35:02.338  5793  5805 D BluetoothAdapterProperties: Setting state to 11
,09-22 04:35:02.338  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 04:35:02.346  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:02.348  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:35:02.349  5793  5793 D HeadsetService: Received start request. Starting profile...
,09-22 04:35:02.352  5793  5793 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-22 04:35:02.352  5793  5793 D HeadsetStateMachine: make
,09-22 04:35:02.360  5793  5805 I BluetoothAdapterState: Entering PendingCommandState
,09-22 04:35:02.361  5793  5793 D HeadsetStateMachine: max_hf_connections = 1
09-22 04:35:02.361  5793  5793 I bt_bluedroid: get_profile_interface handsfree
09-22 04:35:02.361  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 04:35:02.362  5793  5809 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-22 04:35:02.366  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:35:02.367  5793  5793 D A2dpService: Received start request. Starting profile...
,09-22 04:35:02.368  5793  5793 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 04:35:02.368  5793  5793 I bt_bluedroid: get_profile_interface avrcp
,09-22 04:35:02.373  5793  5793 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-22 04:35:02.373  5793  5793 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-22 04:35:02.373  5793  5793 D A2dpStateMachine: make
,09-22 04:35:02.374  5793  5793 I bt_bluedroid: get_profile_interface a2dp
,09-22 04:35:02.375  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 04:35:02.376  5793  5826 D A2dpStateMachine: Enter Disconnected: -2
09-22 04:35:02.377  5793  5793 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 04:35:02.378  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:35:02.378  5793  5793 D HidService: Received start request. Starting profile...
09-22 04:35:02.378  5793  5793 I bt_bluedroid: get_profile_interface hidhost
09-22 04:35:02.378  5793  5793 D HidService: setHidService(): set to: null
09-22 04:35:02.379  5793  5809 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b1e56d
09-22 04:35:02.379  5793  5809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 04:35:02.379  5793  5793 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 04:35:02.380  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:35:02.380  5793  5793 D HealthService: Received start request. Starting profile...
,09-22 04:35:02.382  5793  5793 I bt_bluedroid: get_profile_interface health
09-22 04:35:02.382  5793  5793 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-22 04:35:02.383  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:35:02.384  5793  5793 D PanService: Received start request. Starting profile...
09-22 04:35:02.384  5793  5793 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 04:35:02.384  5793  5793 I bt_bluedroid: get_profile_interface pan
09-22 04:35:02.384  5793  5809 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 04:35:02.387  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:35:02.388  5793  5793 D BluetoothMapService: Received start request. Starting profile...
,09-22 04:35:02.388  5793  5793 D BluetoothMapService: start()
,09-22 04:35:02.391  5793  5793 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 04:35:02.392  5793  5793 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 04:35:02.392  5793  5793 D BluetoothMapAppObserver: createReceiver()
09-22 04:35:02.393  5793  5793 D BluetoothMapAppObserver: initObservers()
09-22 04:35:02.393  5793  5793 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 04:35:02.401  5793  5793 V SapService: SapBinder()
,09-22 04:35:02.401  5793  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
09-22 04:35:02.402  5793  5793 D SapService: Received start request. Starting profile...
09-22 04:35:02.402  5793  5793 V SapService: start()
,09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isTurningOff()=false
09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isTurningOn()=true
,09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isTurningOff()=false
09-22 04:35:02.405  5793  5824 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isTurningOn()=true
09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.405  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isTurningOff()=false
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isTurningOn()=true
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:35:02.406  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isTurningOff()=false
,09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isTurningOn()=true
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:35:02.406  5793  5793 V BluetoothAdapterState: isTurningOff()=false
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isTurningOn()=true
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isTurningOff()=false
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isTurningOn()=true
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.407  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:35:02.408  5793  5793 V BluetoothAdapterState: isTurningOff()=false
09-22 04:35:02.408  5793  5793 V BluetoothAdapterState: isTurningOn()=true
09-22 04:35:02.408  5793  5793 V BluetoothAdapterState: isBleTurningOn()=false
09-22 04:35:02.408  5793  5793 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 04:35:02.408  5793  5805 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 04:35:02.409  5793  5805 D BluetoothAdapterProperties: ScanMode =  20
09-22 04:35:02.409  5793  5805 D BluetoothAdapterProperties: State =  11
,09-22 04:35:02.409  5793  5805 D BluetoothAdapterProperties: Setting state to 12
09-22 04:35:02.409  5793  5805 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 04:35:02.411   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:35:02.411  5793  5805 I BluetoothAdapterState: Entering OnState
,09-22 04:35:02.412  5605  5617 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-22 04:35:02.414  5793  5809 D BluetoothAdapterProperties: Scan Mode:21
,09-22 04:35:02.414  5793  5809 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-22 04:35:02.417  3125  3742 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:02.418  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:02.419   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:35:02.419  3125  3125 D BluetoothInputDevice: Proxy object connected
09-22 04:35:02.419  3125  3125 D HidProfile: Bluetooth service connected
09-22 04:35:02.419  5605  5617 D BluetoothPan: onBluetoothStateChange on: true
09-22 04:35:02.420  5793  5793 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 04:35:02.420  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 04:35:02.420  5793  5793 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 04:35:02.421  5605  5616 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:35:02.422  5605  5605 D BluetoothInputDevice: Proxy object connected
09-22 04:35:02.422  5793  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:35:02.422  5605  5605 D HidProfile: Bluetooth service connected
09-22 04:35:02.423  3125  3139 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 04:35:02.424  5793  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 04:35:02.425  3125  3742 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 04:35:02.425  5793  5793 D ObexServerSockets: Succeed to create listening sockets 
09-22 04:35:02.425  5793  5793 D ObexServerSockets0: startAccept()
09-22 04:35:02.425  5793  5793 D ObexServerSockets0: prepareForNewConnect()
09-22 04:35:02.426  3125  3138 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:35:02.427  5793  5793 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 04:35:02.427  5793  5793 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 04:35:02.427  5605  5617 D BluetoothMap: onBluetoothStateChange: up=true
09-22 04:35:02.428  5793  5831 D ObexServerSockets0: Accepting socket connection...
09-22 04:35:02.428  5793  5832 D ObexServerSockets0: Accepting socket connection...
,09-22 04:35:02.429   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 04:35:02.429  3125  3125 D BluetoothA2dp: Proxy object connected
09-22 04:35:02.430   928   928 D BluetoothA2dp: Proxy object connected
09-22 04:35:02.430  3540  3780 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:35:02.431  3125  3742 D BluetoothPan: onBluetoothStateChange on: true
09-22 04:35:02.432  5605  5605 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 04:35:02.432  5605  5605 D PanProfile: Bluetooth service connected
09-22 04:35:02.432  5605  5605 D BluetoothMap: Proxy object connected
09-22 04:35:02.432  5605  5605 D MapProfile: Bluetooth service connected
09-22 04:35:02.432  5605  5605 D BluetoothMap: getConnectedDevices()
,09-22 04:35:02.433  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 04:35:02.433  5605  5617 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 04:35:02.433  3125  3125 D PanProfile: Bluetooth service connected
,09-22 04:35:02.436  3125  3139 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 04:35:02.439   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 04:35:02.439  3125  3125 D BluetoothMap: Proxy object connected
09-22 04:35:02.439  3125  3125 D MapProfile: Bluetooth service connected
09-22 04:35:02.439  3125  3125 D BluetoothMap: getConnectedDevices()
09-22 04:35:02.439  5605  5833 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 04:35:02.440  5605  5605 D BluetoothA2dp: Proxy object connected
09-22 04:35:02.443   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-22 04:35:02.443  5793  5793 D BluetoothMapService: onReceive
09-22 04:35:02.443  5793  5793 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 04:35:02.443  5793  5793 D BluetoothMapService: STATE_ON
,09-22 04:35:02.446  5793  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 04:35:02.447  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:02.448  5793  5834 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 04:35:02.448  5793  5834 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 04:35:02.450  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 04:35:02.458  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,09-22 04:35:02.461  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 04:35:02.464  5605  5605 D BluetoothPbap: Proxy object connected
09-22 04:35:02.464  3125  3125 D BluetoothPbap: Proxy object connected
09-22 04:35:02.464  3125  3125 D PbapServerProfile: Bluetooth service connected
09-22 04:35:02.464  5605  5605 D PbapServerProfile: Bluetooth service connected
09-22 04:35:02.465  5793  5793 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 04:35:02.465  5793  5793 D ObexServerSockets0: prepareForNewConnect()
09-22 04:35:02.465  5793  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 04:35:02.485  5793  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 04:35:02.486  5793  5842 I BtOppRfcommListener: Accept thread started.
,09-22 04:35:02.513  5605  5617 D BluetoothHeadset: Proxy object connected
,09-22 04:35:02.513  3540  3963 D BluetoothHeadset: Proxy object connected
09-22 04:35:02.514   928   928 D BluetoothHeadset: Proxy object connected
09-22 04:35:02.514  3125  3138 D BluetoothHeadset: Proxy object connected
09-22 04:35:02.514  3125  3125 D HeadsetProfile: Bluetooth service connected
09-22 04:35:02.514   928   928 D BluetoothHeadset: Proxy object connected
09-22 04:35:02.514   928   928 D BluetoothHeadset: Proxy object connected
,09-22 04:35:02.515  5605  5605 D HeadsetProfile: Bluetooth service connected
,09-22 04:35:02.519   928   945 D BluetoothHeadset: Proxy object connected
,09-22 04:35:02.524  5605  5833 D BluetoothHeadset: Proxy object connected
09-22 04:35:02.524  5605  5605 D HeadsetProfile: Bluetooth service connected
,09-22 04:35:02.527  3125  3742 D BluetoothHeadset: Proxy object connected
,09-22 04:35:02.527  3125  3125 D HeadsetProfile: Bluetooth service connected
,09-22 04:35:02.531  3540  3574 D BluetoothHeadset: Proxy object connected
,09-22 04:35:02.539   928   945 D BluetoothHeadset: Proxy object connected
,09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:03.250  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:03.254  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:03.257  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:03.257  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd50d added. We now have 8 listener(s)
09-22 04:35:03.257  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 04:35:03.263   928  3545 D WifiService: setWifiEnabled: false pid=5469, uid=10077
,09-22 04:35:03.264   928  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 04:35:03.269  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:03.269   928  3166 D WifiService: setWifiEnabled: true pid=5469, uid=10077
09-22 04:35:03.269   928  3166 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 04:35:03.275   507   921 D SoftapController: Softap fwReload - Ok
,09-22 04:35:03.279   507   921 D CommandListener: Setting iface cfg
09-22 04:35:03.279   507   921 D CommandListener: Trying to bring down wlan0
,09-22 04:35:03.280   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-22 04:35:03.283   928  2978 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 04:35:03.891   928  2978 D wifi    : set interface wlan0 flags (UP)
,09-22 04:35:03.896   928  2978 I WifiHAL : Initializing wifi
,09-22 04:35:03.896   928  2978 I WifiHAL : Creating socket
,09-22 04:35:03.899   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 04:35:03.904   928  2978 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 04:35:03.904   928  2978 D wifi    : Did set static halHandle = 0x7f6abb13e0
09-22 04:35:03.904   928  2978 D wifi    : halHandle = 0x7f6abb13e0, mVM = 0x7f756cd140, mCls = 0x148a
09-22 04:35:03.905   928  2978 D wifi    : array field set
09-22 04:35:03.905   928  2978 I WifiNative-HAL: interface[0] = wlan0
,09-22 04:35:03.906   928  5847 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547251491808
09-22 04:35:03.907   928  5847 D wifi    : waitForHalEvents called, vm = 0x7f756cd140, obj = 0x148a, env = 0x7f6ac69100
,09-22 04:35:03.964  5848  5848 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 04:35:03.985  5848  5848 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 04:35:03.995  5848  5848 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 04:35:03.995  5848  5848 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 04:35:04.008   928  2978 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 04:35:04.017   928  2978 D WifiConfigStore: Loading config and enabling all networks 
,09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:04.023  5469  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:04.025  5469  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:04.027  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:04.035   928  2978 D WifiConfigStore: loaded 0 passpoint configs
,09-22 04:35:04.035   928  2978 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 04:35:04.035   928  2978 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-22 04:35:04.036   928  2978 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-22 04:35:04.037   928  2978 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 04:35:04.037   928  2978 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 04:35:04.037   928  2978 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 04:35:04.038   928  2978 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 04:35:04.041   928  2978 D WifiNative-HAL: Setting external_sim to 1
,09-22 04:35:04.041  4308  4308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 04:35:04.041   928  2978 D wifi    : setting dfs flag to true, 0x7f5ada1e40
09-22 04:35:04.042   928  2978 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 04:35:04.042   928  2978 D wifi    : setting scan oui 0x7f5ada1e40
09-22 04:35:04.042   928  2978 D WifiHAL : Sending mac address OUI
,09-22 04:35:04.046   928  2978 E native  : do suspend false
,09-22 04:35:04.052   928  2978 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 04:35:04.053   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-22 04:35:04.053   928   928 D RttService: SCAN_AVAILABLE : 3
09-22 04:35:04.053   928  3091 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-22 04:35:04.054   507   921 D CommandListener: Setting iface cfg
,09-22 04:35:04.057   928  2968 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-22 04:35:04.058   928  2968 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 04:35:04.066   928  2968 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 04:35:04.066   928  2968 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 04:35:04.069   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-22 04:35:04.069   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-22 04:35:04.072   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=218927 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:04.287  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:04.296  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:04.304  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-22 04:35:04.305  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-22 04:35:04.309  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@209d24c Bundle[{}]
,09-22 04:35:04.309  5469  5525 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 04:35:04.310  5469  5525 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-22 04:35:04.311  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-22 04:35:04.311  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-22 04:35:04.312  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-22 04:35:04.314  5469  5525 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-22 04:35:04.321  5469  5525 I System.out: Running OutgoingSocketThread
,09-22 04:35:04.323  5469  5850 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,09-22 04:35:04.325  5469  5850 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44058
09-22 04:35:04.325  5469  5850 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 04:35:05.324  5469  5525 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-22 04:35:05.324  5469  5525 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,09-22 04:35:05.330  5469  5525 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-22 04:35:05.332  5469  5525 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-22 04:35:05.332  5469  5525 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-22 04:35:05.338  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 04:35:05.338  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb5dcc2 added. We now have 2 listener(s)
,09-22 04:35:05.342  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 04:35:05.342  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.342  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.343  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 04:35:05.343  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbe4ad3 added. We now have 9 listener(s)
09-22 04:35:05.343  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.344  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 04:35:05.348  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:05.353  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:05.355  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:05.355  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:35:05.356  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.356  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@671b509 added. We now have 3 listener(s)
,09-22 04:35:05.357  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.358  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.359  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.359  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.359  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 04:35:05.360  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189030e added. We now have 10 listener(s)
,09-22 04:35:05.360  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.360  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:35:05.360  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.360  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.360  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:35:05.360  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.360  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.361  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 04:35:05.361  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.361  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb5dcc2 removed from the list
09-22 04:35:05.361  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.361  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbe4ad3 removed from the list
09-22 04:35:05.361  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:35:05.361  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.362  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.362  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.364  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.364  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.364  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.364  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbe4ad3 not in the list
09-22 04:35:05.364  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.364  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:35:05.367  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.367  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.367  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 04:35:05.367  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189030e removed from the list
09-22 04:35:05.367  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.367  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.367  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.368  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.368  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@671b509 removed from the list
09-22 04:35:05.369  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.369  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@118c12f added. We now have 2 listener(s)
09-22 04:35:05.370  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 04:35:05.370  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.370  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.370  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.370  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0c33c added. We now have 9 listener(s)
09-22 04:35:05.371  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.371  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 04:35:05.374  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:05.377  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:05.379  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:05.380  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:35:05.380  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.380  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f56421a added. We now have 3 listener(s)
09-22 04:35:05.381  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.381  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.381  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.381  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.382  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.382  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fa414b added. We now have 10 listener(s)
09-22 04:35:05.382  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.382  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:35:05.382  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-22 04:35:05.382  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 04:35:05.382  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:35:05.382  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 04:35:05.382  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:05.385  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 04:35:05.385  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 04:35:05.389  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 04:35:05.390  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 04:35:05.390  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 04:35:05.394  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 04:35:05.394  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 04:35:05.394  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 04:35:05.395  5469  5525 D BluetoothAdapter: STATE_ON
09-22 04:35:05.397  5793  5822 D BtGatt.GattService: registerClient() - UUID=4dbfc5b9-8b92-4c66-8d8c-42bc41b2cd4b
09-22 04:35:05.398  5793  5809 D BtGatt.GattService: onClientRegistered() - UUID=4dbfc5b9-8b92-4c66-8d8c-42bc41b2cd4b, clientIf=5
,09-22 04:35:05.399  5469  5810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 04:35:05.400  5793  5803 D BtGatt.GattService: start scan with filters
,09-22 04:35:05.404  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 04:35:05.404  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 04:35:05.404  5793  5813 D BtGatt.ScanManager: handling starting scan
,09-22 04:35:05.404  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 04:35:05.404  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 04:35:05.406  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:35:05.407  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-22 04:35:05.407  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 04:35:05.408  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 04:35:05.408  5793  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6401d9
,09-22 04:35:05.410  5469  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-22 04:35:05.410  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.410  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 04:35:05.410  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.410  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 04:35:05.410  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 04:35:05.410  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:35:05.410  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:35:05.411  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:35:05.411  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 04:35:05.411  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 04:35:05.412  5469  5525 D BluetoothAdapter: STATE_ON
,09-22 04:35:05.412  5793  5823 D BtGatt.GattService: stopScan() - queue size =1
,09-22 04:35:05.413  5793  5803 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 04:35:05.414  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 04:35:05.414  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 04:35:05.414  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 04:35:05.414  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 04:35:05.414  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 04:35:05.414  5793  5809 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 04:35:05.414  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.415  5793  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 04:35:05.415  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:35:05.415  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 04:35:05.415  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 04:35:05.415  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 04:35:05.416  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:35:05.418  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:35:05.418  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 04:35:05.418  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:35:05.420  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 04:35:05.420  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:35:05.420  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.420  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.420  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:35:05.420  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.420  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 04:35:05.420  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:35:05.421  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.421  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@118c12f removed from the list
,09-22 04:35:05.421  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.421  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0c33c removed from the list
09-22 04:35:05.421  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:35:05.421  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.421  5793  5813 D BtGatt.ScanManager: Starting BLE batch scan
09-22 04:35:05.421  5793  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 04:35:05.421  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.422  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.423  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.423  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.423  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.423  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc0c33c not in the list
,09-22 04:35:05.423  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.423  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.424  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.424  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.424  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.424  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fa414b removed from the list
09-22 04:35:05.424  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.424  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.424  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.424  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.424  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f56421a removed from the list
09-22 04:35:05.425  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.425  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@829a727 added. We now have 2 listener(s)
09-22 04:35:05.426  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.426  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.427  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.427  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 04:35:05.427  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d43dd4 added. We now have 9 listener(s)
09-22 04:35:05.427  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 04:35:05.428  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 04:35:05.430  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:35:05.432  5793  5809 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 04:35:05.432  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:05.434  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:05.437  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:05.437  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:35:05.437  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.437  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142fa72 added. We now have 3 listener(s)
09-22 04:35:05.438  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 04:35:05.438  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.438  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.439  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 04:35:05.439  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.439  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.439  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.439  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ff8ec3 added. We now have 10 listener(s)
09-22 04:35:05.440  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.440  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.440  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 04:35:05.440  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:35:05.440  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 04:35:05.440  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 04:35:05.441  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 04:35:05.441  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 04:35:05.444  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 04:35:05.444  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 04:35:05.446  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 04:35:05.446  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.446  5793  5813 D BtGatt.ScanManager: stopping BLe Batch
,09-22 04:35:05.448  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 04:35:05.449  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 04:35:05.449  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 04:35:05.451  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 04:35:05.451  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.451  5793  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 04:35:05.452  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 04:35:05.452  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 04:35:05.453  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 04:35:05.453  5469  5525 D BluetoothAdapter: STATE_ON
,09-22 04:35:05.456  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-22 04:35:05.456  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.457  5793  5823 D BtGatt.GattService: registerClient() - UUID=e5b5a9b6-53ee-454b-bbb7-30a1935de330
,09-22 04:35:05.457  5793  5809 D BtGatt.GattService: onClientRegistered() - UUID=e5b5a9b6-53ee-454b-bbb7-30a1935de330, clientIf=5
09-22 04:35:05.457  5469  5479 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 04:35:05.458  5793  5804 D BtGatt.GattService: start scan with filters
,09-22 04:35:05.459  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 04:35:05.459  5793  5813 D BtGatt.ScanManager: handling starting scan
,09-22 04:35:05.460  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 04:35:05.460  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 04:35:05.460  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 04:35:05.462  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 04:35:05.462  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 04:35:05.462  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:35:05.463  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 04:35:05.464  5793  5809 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 04:35:05.464  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 04:35:05.464  5793  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 04:35:05.465  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 04:35:05.465  5469  5525 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-22 04:35:05.465  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:35:05.465  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.465  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:35:05.465  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.465  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.465  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 04:35:05.465  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.465  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@829a727 removed from the list
09-22 04:35:05.465  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 04:35:05.466  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d43dd4 removed from the list
09-22 04:35:05.466  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:35:05.466  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:35:05.466  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.466  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 04:35:05.466  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.466  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 04:35:05.469  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-22 04:35:05.469  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.470  5793  5813 D BtGatt.ScanManager: Starting BLE batch scan
09-22 04:35:05.470  5793  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 04:35:05.470  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.470  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 04:35:05.470  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.470  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d43dd4 not in the list
09-22 04:35:05.470  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:35:05.470  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:35:05.470  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:35:05.470  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 04:35:05.470  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 04:35:05.471  5469  5525 D BluetoothAdapter: STATE_ON
09-22 04:35:05.472  5793  5823 D BtGatt.GattService: stopScan() - queue size =1
09-22 04:35:05.472  5793  5804 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 04:35:05.472  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 04:35:05.473  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 04:35:05.473  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 04:35:05.473  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-22 04:35:05.473  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 04:35:05.473  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:35:05.474  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 04:35:05.474  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 04:35:05.474  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 04:35:05.474  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:35:05.475  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 04:35:05.475  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.475  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.475  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:35:05.475  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ff8ec3 removed from the list
09-22 04:35:05.475  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.475  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:35:05.475  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.475  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:35:05.475  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.476  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-22 04:35:05.476  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142fa72 removed from the list
09-22 04:35:05.476  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.476  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2541f added. We now have 2 listener(s)
09-22 04:35:05.477  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.477  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.477  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.478  5793  5809 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 04:35:05.478  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.478  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.478  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f59736c added. We now have 9 listener(s)
09-22 04:35:05.478  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.478  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 04:35:05.481  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:35:05.482  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 04:35:05.483  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:05.483  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:05.485  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:05.485  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:35:05.485  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.485  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15365ca added. We now have 3 listener(s)
09-22 04:35:05.486  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.486  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.486  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.486  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.487  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.487  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc2133b added. We now have 10 listener(s)
09-22 04:35:05.487  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.487  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:35:05.487  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 04:35:05.487  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 04:35:05.487  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:35:05.487  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 04:35:05.488  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:05.489  5469  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 04:35:05.489  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 04:35:05.489  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 04:35:05.489  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.489  5793  5813 D BtGatt.ScanManager: stopping BLe Batch
,09-22 04:35:05.492  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 04:35:05.493  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 04:35:05.493  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 04:35:05.493  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 04:35:05.494  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.494  5793  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 04:35:05.496  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 04:35:05.497  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 04:35:05.497  5469  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 04:35:05.497  5469  5525 D BluetoothAdapter: STATE_ON
,09-22 04:35:05.498  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 04:35:05.498  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.499  5793  5823 D BtGatt.GattService: registerClient() - UUID=9acd9c08-44f5-4466-a18a-3efc86ec6447
09-22 04:35:05.500  5793  5809 D BtGatt.GattService: onClientRegistered() - UUID=9acd9c08-44f5-4466-a18a-3efc86ec6447, clientIf=5
09-22 04:35:05.500  5469  5480 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 04:35:05.500  5793  5804 D BtGatt.GattService: start scan with filters
,09-22 04:35:05.502  5793  5813 D BtGatt.ScanManager: handling starting scan
,09-22 04:35:05.502  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 04:35:05.502  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 04:35:05.502  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 04:35:05.502  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 04:35:05.505  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 04:35:05.505  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 04:35:05.505  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 04:35:05.506  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 04:35:05.507  5793  5809 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 04:35:05.507  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.507  5793  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 04:35:05.511  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-22 04:35:05.511  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.511  5793  5813 D BtGatt.ScanManager: Starting BLE batch scan
09-22 04:35:05.511  5793  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 04:35:05.512  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 04:35:05.512  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.512  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:35:05.512  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.512  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.512  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 04:35:05.512  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.513  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2541f removed from the list
09-22 04:35:05.513  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.513  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f59736c removed from the list
09-22 04:35:05.513  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 04:35:05.513  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:35:05.513  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.513  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 04:35:05.513  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.513  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:35:05.515  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.515  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.515  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.515  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f59736c not in the list
09-22 04:35:05.515  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 04:35:05.515  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 04:35:05.515  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 04:35:05.515  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 04:35:05.515  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 04:35:05.516  5469  5525 D BluetoothAdapter: STATE_ON
09-22 04:35:05.516  5793  5803 D BtGatt.GattService: stopScan() - queue size =1
09-22 04:35:05.517  5793  5822 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 04:35:05.517  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 04:35:05.517  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 04:35:05.517  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 04:35:05.517  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 04:35:05.517  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 04:35:05.518  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:35:05.518  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 04:35:05.518  5469  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 04:35:05.518  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 04:35:05.519  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:35:05.519  5793  5809 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 04:35:05.519  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.520  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.520  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.520  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.520  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:35:05.520  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc2133b removed from the list
09-22 04:35:05.520  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.520  5469  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 04:35:05.520  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.520  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 04:35:05.520  5469  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 04:35:05.520  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.520  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15365ca removed from the list
09-22 04:35:05.521  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.521  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@534a817 added. We now have 2 listener(s)
09-22 04:35:05.522  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.522  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.523  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 04:35:05.523  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.523  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cc404 added. We now have 9 listener(s)
09-22 04:35:05.523  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.523  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 04:35:05.524  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 04:35:05.524  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 04:35:05.526  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 04:35:05.529  5793  5809 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 04:35:05.529  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.530  5793  5813 D BtGatt.ScanManager: stopping BLe Batch
,09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 04:35:05.530  5469  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 04:35:05.532  5469  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 04:35:05.532  5469  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 04:35:05.532  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 04:35:05.533  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eae422 added. We now have 3 listener(s)
,09-22 04:35:05.533  5793  5809 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 04:35:05.534  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 04:35:05.534  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.534  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 04:35:05.534  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 04:35:05.534  5793  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 04:35:05.534  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 04:35:05.534  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1aeb3 added. We now have 10 listener(s)
09-22 04:35:05.534  5469  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 04:35:05.534  5469  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 04:35:05.534  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.534  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 04:35:05.534  5469  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 04:35:05.534  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.534  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.534  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 04:35:05.534  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.534  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@534a817 removed from the list
09-22 04:35:05.535  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.535  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cc404 removed from the list
09-22 04:35:05.536  5469  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 04:35:05.536  5469  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-22 04:35:05.536  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.536  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 04:35:05.536  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.537  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.537  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.537  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.537  5469  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cc404 not in the list
09-22 04:35:05.537  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.537  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.538  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 04:35:05.538  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 04:35:05.538  5469  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 04:35:05.538  5469  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1aeb3 removed from the list
,09-22 04:35:05.538  5469  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 04:35:05.538  5469  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 04:35:05.538  5469  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 04:35:05.538  5469  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 04:35:05.538  5469  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eae422 removed from the list
09-22 04:35:05.538  5793  5809 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 04:35:05.538  5793  5809 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 04:35:05.539  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-22 04:35:05.539  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-22 04:35:05.539  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-22 04:35:05.539  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 04:35:05.539  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-22 04:35:05.539  5469  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 04:35:05.543  5469  5851 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
09-22 04:35:05.543  5469  5851 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-22 04:35:05.543  5469  5851 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-22 04:35:05.544  5469  5852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
09-22 04:35:05.544  5469  5852 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-22 04:35:05.545  5469  5852 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-22 04:35:05.546  5469  5525 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-22 04:35:05.546  5469  5525 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-22 04:35:05.546  5469  5525 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 04:35:05.546  5469  5525 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 04:35:05.546  5469  5525 D com.test.thalitest.ThaliTestRunner: Total duration: 22601 ms
,09-22 04:35:05.548  5469  5525 I jxcore-log: *Native tests were executed*
09-22 04:35:05.548  5469  5525 I jxcore-log: 
,09-22 04:35:05.548  5469  5525 I jxcore-log: Total number of executed tests:  80
09-22 04:35:05.548  5469  5525 I jxcore-log: 
09-22 04:35:05.548  5469  5525 I jxcore-log: Number of passed tests:  80
09-22 04:35:05.548  5469  5525 I jxcore-log: 
09-22 04:35:05.548  5469  5525 I jxcore-log: Number of failed tests:  0
09-22 04:35:05.548  5469  5525 I jxcore-log: 
09-22 04:35:05.549  5469  5525 I jxcore-log: Number of ignored tests:  0
09-22 04:35:05.549  5469  5525 I jxcore-log: 
09-22 04:35:05.549  5469  5525 I jxcore-log: Total duration:  22601
09-22 04:35:05.549  5469  5525 I jxcore-log: 
09-22 04:35:05.549  5469  5525 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 04:35:05.549  5469  5525 I jxcore-log: 
,09-22 04:35:05.552  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.552  5469  5525 I jxcore-log: 
09-22 04:35:05.555  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.555  5469  5525 I jxcore-log: 
09-22 04:35:05.556  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.556  5469  5525 I jxcore-log: 
09-22 04:35:05.557  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.557  5469  5525 I jxcore-log: 
09-22 04:35:05.558  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.558  5469  5525 I jxcore-log: 
09-22 04:35:05.559  5469  5469 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-22 04:35:05.560  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.560  5469  5525 I jxcore-log: 
09-22 04:35:05.562  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.562  5469  5525 I jxcore-log: 
09-22 04:35:05.563  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.563  5469  5525 I jxcore-log: 
09-22 04:35:05.564  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 04:35:05.564  5469  5525 I jxcore-log: 
09-22 04:35:05.565  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.565  5469  5525 I jxcore-log: 
09-22 04:35:05.566  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.566  5469  5525 I jxcore-log: 
09-22 04:35:05.567  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 04:35:05.567  5469  5525 I jxcore-log: 
09-22 04:35:05.568  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.568  5469  5525 I jxcore-log: 
,09-22 04:35:05.569  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.569  5469  5525 I jxcore-log: 
09-22 04:35:05.570  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.570  5469  5525 I jxcore-log: 
09-22 04:35:05.570  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.570  5469  5525 I jxcore-log: 
09-22 04:35:05.571  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.571  5469  5525 I jxcore-log: 
09-22 04:35:05.572  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.572  5469  5525 I jxcore-log: 
09-22 04:35:05.572  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.572  5469  5525 I jxcore-log: 
09-22 04:35:05.573  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.573  5469  5525 I jxcore-log: 
09-22 04:35:05.574  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.574  5469  5525 I jxcore-log: 
09-22 04:35:05.574  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 04:35:05.574  5469  5525 I jxcore-log: 
09-22 04:35:05.575  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.575  5469  5525 I jxcore-log: 
09-22 04:35:05.576  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.576  5469  5525 I jxcore-log: 
09-22 04:35:05.576  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.576  5469  5525 I jxcore-log: 
09-22 04:35:05.577  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.577  5469  5525 I jxcore-log: 
09-22 04:35:05.578  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.578  5469  5525 I jxcore-log: 
09-22 04:35:05.578  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.578  5469  5525 I jxcore-log: 
09-22 04:35:05.579  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 04:35:05.579  5469  5525 I jxcore-log: 
,09-22 04:35:05.918  5469  5469 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 04:35:05.923  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 04:35:05.923  5469  5525 I jxcore-log: 
,09-22 04:35:05.976  5469  5469 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 04:35:05.979  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 04:35:05.979  5469  5525 I jxcore-log: 
,09-22 04:35:06.020  5469  5469 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 04:35:06.023  5469  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 04:35:06.023  5469  5525 I jxcore-log: 
,09-22 04:35:06.039  5853  5853 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 04:35:06.045  5853  5853 D AndroidRuntime: CheckJNI is OFF
,09-22 04:35:06.077  5853  5853 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 04:35:06.111  5853  5853 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 04:35:06.127  5853  5853 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 04:35:06.135   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-22 04:35:06.136   928   941 I ActivityManager: Killing 5469:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-22 04:35:06.220   928  3398 I WindowState: WIN DEATH: Window{4e50222 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 04:35:06.220   928  2981 D WifiService: Client connection lost with reason: 4
09-22 04:35:06.221   928  3545 D GraphicsStats: Buffer count: 2
,09-22 04:35:06.275   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-22 04:35:06.275   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-22 04:35:06.276   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-22 04:35:06.276   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-22 04:35:06.276   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:35:06.276   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.276   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 04:35:06.276   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 04:35:06.276   928   941 I ActivityManager:   Force finishing activity ActivityRecord{b512837 u0 com.test.thalitest/.MainActivity t2}
09-22 04:35:06.277   928   951 I art     : Starting a blocking GC Explicit
09-22 04:35:06.282   928   939 W ActivityManager: Spurious death for ProcessRecord{ebe501b 0:com.test.thalitest/u0a77}, curProc for 5469: null
,09-22 04:35:06.286   928   946 W WindowManager: Attempted to add application window with unknown token Token{d5911a4 ActivityRecord{b512837 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-22 04:35:06.286   928   946 W WindowManager: Token{d5911a4 ActivityRecord{b512837 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{d5911a4 ActivityRecord{b512837 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-22 04:35:06.286   928   946 W WindowManager: view not successfully added to wm, removing view
09-22 04:35:06.286   928   946 W WindowManager: Exception when adding starting window
09-22 04:35:06.286   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{af4b482 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 04:35:06.286   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-22 04:35:06.286   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-22 04:35:06.286   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-22 04:35:06.286   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-22 04:35:06.286   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-22 04:35:06.286   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:35:06.286   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.286   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 04:35:06.286   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 04:35:06.353   928   951 I art     : Explicit concurrent mark sweep GC freed 26875(1675KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.332ms total 76.461ms
,09-22 04:35:06.353   928   937 I art     : WaitForGcToComplete blocked for 11.916ms for cause HeapTrim
,09-22 04:35:06.371   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-22 04:35:06.374  5853  5853 I art     : System.exit called, status: 0
,09-22 04:35:06.374  5853  5853 I AndroidRuntime: VM exiting with result code 0.
,09-22 04:35:06.391   928   951 I ActivityManager: Start proc 5863:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-22 04:35:06.392   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-22 04:35:06.397   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-22 04:35:06.401  5793  5793 D BluetoothMapAppObserver: onReceive
09-22 04:35:06.401  5793  5793 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-22 04:35:06.408  3485  3954 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-22 04:35:06.408  3430  3430 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-22 04:35:06.416   928  2908 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-22 04:35:06.421   928   941 I ActivityManager: Start proc 5876:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-22 04:35:06.425  3430  5874 I Keyboard.Facilitator.DecoderInitializer: run()
,09-22 04:35:06.431  3540  3540 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-22 04:35:06.432  3430  5874 I Decoder : createOrResetDecoder
,09-22 04:35:06.466   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-22 04:35:06.476  3614  3614 I ConfigService: onCreate
09-22 04:35:06.484    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-22 04:35:06.487    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 04:35:06.501    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 04:35:06.507  3430  5874 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-22 04:35:06.511  3578  3664 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-22 04:35:06.525   928  5232 I ActivityManager: Start proc 5892:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-22 04:35:06.525  3578  3664 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-22 04:35:06.525  3578  3664 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3578
09-22 04:35:06.525  3578  3664 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.525  3578  3664 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 04:35:06.530   928  3545 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-22 04:35:06.532   928  5901 E DropBoxManagerService: Can't write: system_app_crash
09-22 04:35:06.532   928  5901 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 04:35:06.532   928  5901 E DropBoxManagerService: 	... 5 more
,09-22 04:35:06.534  3578  3664 I Process : Sending signal. PID: 3578 SIG: 9
,09-22 04:35:06.555  5876  5876 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,09-22 04:35:06.590  3430  5874 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-22 04:35:06.606  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-22 04:35:06.606  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-22 04:35:06.619  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-22 04:35:06.619  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-22 04:35:06.620  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-22 04:35:06.620  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-22 04:35:06.634  3430  5874 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-22 04:35:06.634  3430  5874 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-22 04:35:06.635  3430  5874 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-22 04:35:06.635  3430  5874 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-22 04:35:06.635  3430  5874 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-22 04:35:06.635  3430  5874 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-22 04:35:06.686   928  3584 D GraphicsStats: Buffer count: 1
,09-22 04:35:06.686   928  2907 W InputDispatcher: channel '4729e70 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-22 04:35:06.687   928  2907 E InputDispatcher: channel '4729e70 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-22 04:35:06.687   928  3584 I WindowState: WIN DEATH: Window{4729e70 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-22 04:35:06.687   928  3584 W InputDispatcher: Attempted to unregister already unregistered input channel '4729e70 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-22 04:35:06.692   928  3166 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3578) has died
,09-22 04:35:06.693   928  3166 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-22 04:35:06.696   928  3166 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 04:35:06.712   928   941 I ActivityManager: Start proc 5913:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 04:35:06.715  5876  5876 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,09-22 04:35:06.733  5876  5925 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-22 04:35:06.764  5913  5913 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:35:06.764  5913  5913 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 04:35:06.764  5913  5913 D AndroidRuntime: Shutting down VM
,09-22 04:35:06.772  5913  5913 E AndroidRuntime: FATAL EXCEPTION: main
09-22 04:35:06.772  5913  5913 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5913
09-22 04:35:06.772  5913  5913 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 04:35:06.772  5913  5913 E AndroidRuntime: 	... 10 more
,09-22 04:35:06.775   928  5928 E DropBoxManagerService: Can't write: system_app_crash
09-22 04:35:06.775   928  5928 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 04:35:06.775   928  5928 E DropBoxManagerService: 	... 5 more
09-22 04:35:06.775   928  3398 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-22 04:35:06.776  5913  5913 I Process : Sending signal. PID: 5913 SIG: 9
,09-22 04:35:06.791   928  3602 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5913) has died
,09-22 04:35:06.792   928  3602 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 04:35:06.805   928   941 I ActivityManager: Start proc 5929:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 04:35:06.858  5929  5929 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:35:06.858  5929  5929 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 04:35:06.859  5929  5929 D AndroidRuntime: Shutting down VM
,09-22 04:35:06.869  5929  5929 E AndroidRuntime: FATAL EXCEPTION: main
09-22 04:35:06.869  5929  5929 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5929
09-22 04:35:06.869  5929  5929 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 04:35:06.869  5929  5929 E AndroidRuntime: 	... 10 more
09-22 04:35:06.872   928  3166 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-22 04:35:06.872   928  5941 E DropBoxManagerService: Can't write: system_app_crash
09-22 04:35:06.872   928  5941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 04:35:06.872   928  5941 E DropBoxManagerService: 	... 5 more
09-22 04:35:06.873  5929  5929 I Process : Sending signal. PID: 5929 SIG: 9
,09-22 04:35:06.877   382   472 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
