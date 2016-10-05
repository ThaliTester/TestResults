#### Test 87966432c4e001b_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-05 13:34:05.886   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 13:34:05.887   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-05 13:34:06.405  5564  5564 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-05 13:34:06.410  5564  5564 D AndroidRuntime: CheckJNI is OFF
10-05 13:34:06.442  5564  5564 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-05 13:34:06.478  5564  5564 I Radio-JNI: register_android_hardware_Radio DONE
10-05 13:34:06.493  5564  5564 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-05 13:34:06.499   931   941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-05 13:34:06.540   931   941 I ActivityManager: Start proc 5574:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-05 13:34:06.554  5564  5564 D AndroidRuntime: Shutting down VM
,10-05 13:34:06.882   931   942 I WindowManager: Screenshot max retries 4 of Token{9362046 ActivityRecord{508a421 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{9b0b659 u0 Starting com.test.thalitest} drawState=2
,10-05 13:34:06.964  5574  5574 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-05 13:34:06.998  5574  5574 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-05 13:34:07.027  5574  5574 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 715-737)
,10-05 13:34:07.028  5574  5574 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-05 13:34:07.050  5574  5574 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a12b15d}
10-05 13:34:07.050  5574  5574 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-05 13:34:07.051  5574  5574 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-05 13:34:07.055  5574  5574 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-05 13:34:07.057  5574  5574 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-05 13:34:07.093  5574  5574 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-05 13:34:07.112  5574  5574 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-05 13:34:07.112  5574  5574 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-05 13:34:07.112  5574  5574 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-05 13:34:07.112  5574  5574 I Adreno  : Build Date                       : 12/06/15
10-05 13:34:07.112  5574  5574 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-05 13:34:07.112  5574  5574 I Adreno  : Local Branch                     : mybranch17112971
10-05 13:34:07.112  5574  5574 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-05 13:34:07.112  5574  5574 I Adreno  : Remote Branch                    : NONE
10-05 13:34:07.112  5574  5574 I Adreno  : Reconstruct Branch               : NOTHING
,10-05 13:34:07.158   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3d0d64:true
,10-05 13:34:07.193   739   739 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27498]" dev="sockfs" ino=27498 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:34:07.193   739   739 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[27498]" dev="sockfs" ino=27498 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:34:07.205  5574  5574 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-05 13:34:07.214  5574  5574 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-05 13:34:07.240  5574  5611 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-05 13:34:07.236   739   739 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31544]" dev="sockfs" ino=31544 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-05 13:34:07.239   739   739 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31544]" dev="sockfs" ino=31544 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:34:07.243  3618  3618 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27510]" dev="sockfs" ino=27510 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 13:34:07.243  3618  3618 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[27510]" dev="sockfs" ino=27510 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 13:34:07.246  5574  5598 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-05 13:34:07.274  5574  5611 I OpenGLRenderer: Initialized EGL, version 1.4
,10-05 13:34:07.346   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +460ms (total +834ms)
,10-05 13:34:07.371  5574  5574 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5574
,10-05 13:34:07.471  5574  5574 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-05 13:34:07.544  5574  5610 I chromium: [INFO:SkError.cpp(84)] Skia Error: Unknown error: ---- failed to create texture for cache [1442 1372]
10-05 13:34:07.544  5574  5610 I chromium: 
10-05 13:34:07.544  5574  5610 I chromium: 
,10-05 13:34:07.544  5574  5610 I chromium: [INFO:SkError.cpp(84)] Skia Error: Unknown error: Couldn't convert bitmap to texture.
10-05 13:34:07.544  5574  5610 I chromium: 
,10-05 13:34:07.606  5574  5614 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -580908752
,10-05 13:34:07.610  5574  5614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-05 13:34:07.610  5574  5614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-05 13:34:07.610  5574  5614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-05 13:34:07.610  5574  5614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-05 13:34:07.610  5574  5614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-05 13:34:07.610  5574  5614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bd08ea added. We now have 1 listener(s)
,10-05 13:34:07.613  5574  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-05 13:34:07.613  5574  5614 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:34:07.614  5574  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 13:34:07.614  5574  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-05 13:34:07.616  5574  5614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6794d51 added. We now have 1 listener(s)
,10-05 13:34:07.616  5574  5614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:07.621   931  2921 D WifiService: New client listening to asynchronous messages
,10-05 13:34:07.621  5574  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:34:07.621  5574  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-05 13:34:07.621  5574  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-05 13:34:07.621  5574  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-05 13:34:07.621  5574  5614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-05 13:34:07.623  5574  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:34:07.623  5574  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-05 13:34:07.626  5574  5614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:07.626  5574  5614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:34:07.626  5574  5614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-05 13:34:07.626  5574  5614 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:34:07.627  5574  5614 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-05 13:34:07.629  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:07.631  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:07.648  5574  5574 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-05 13:34:07.934  5574  5620 W jxcore-log: Initializing JXcore engine
10-05 13:34:07.934  5574  5620 W jxcore-log: JXcore engine is ready
,10-05 13:34:07.959  5620  5620 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12891 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-05 13:34:07.959  5620  5620 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14476]" dev="sockfs" ino=14476 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-05 13:34:07.959  5620  5620 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-05 13:34:07.959  5620  5620 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31521]" dev="sockfs" ino=31521 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-05 13:34:07.967  5574  5620 W jxcore-log: Starting JXcore engine
,10-05 13:34:08.016  5574  5620 W jxcore-log: Platform android
10-05 13:34:08.016  5574  5620 W jxcore-log: 
,10-05 13:34:08.016  5574  5620 W jxcore-log: Process ARCH arm
10-05 13:34:08.016  5574  5620 W jxcore-log: 
,10-05 13:34:08.117  5574  5620 I jxcore-log: JXcore Cordova bridge is ready!
10-05 13:34:08.117  5574  5620 I jxcore-log: 
,10-05 13:34:08.117  5574  5620 W jxcore-log: JXcore engine is started
,10-05 13:34:08.128  5574  5614 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-05 13:34:08.136  5574  5574 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-05 13:34:08.477   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:34:15.888   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:16.889   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:17.632  5574  5620 I jxcore-log: 2016-10-05 17:34:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-05 13:34:17.632  5574  5620 I jxcore-log: 
,10-05 13:34:17.634  5574  5620 I jxcore-log: 2016-10-05 17:34:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-05 13:34:17.634  5574  5620 I jxcore-log: 
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:17.638  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:17.639  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:34:17.641  5574  5620 I jxcore-log: 2016-10-05 17:34:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-05 13:34:17.641  5574  5620 I jxcore-log: 
,10-05 13:34:17.642  5574  5620 I jxcore-log: 2016-10-05 17:34:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-05 13:34:17.642  5574  5620 I jxcore-log: 
,10-05 13:34:17.890   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:17.892  5574  5620 I jxcore-log: 2016-10-05 17:34:17 - DEBUG UnitTest_app: 'Running unit tests'
10-05 13:34:17.892  5574  5620 I jxcore-log: 
,10-05 13:34:17.892  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:34:17.892  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdc573 added. We now have 2 listener(s)
,10-05 13:34:17.893  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:34:17.893  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:34:17.893  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:34:17.893  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:34:17.893  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e84c30 added. We now have 2 listener(s)
10-05 13:34:17.893  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:17.894  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:34:17.896  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:17.899  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:17.900  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:34:17.900  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:34:17.901  5574  5620 D executeNativeTests: Running unit tests
,10-05 13:34:17.907  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:17.913  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:17.939  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:34:17.939  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de added. We now have 3 listener(s)
10-05 13:34:17.940  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:34:17.940  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:34:17.940  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:34:17.940  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:34:17.940  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf added. We now have 3 listener(s)
10-05 13:34:17.940  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:17.941  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:34:17.942  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:17.945  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:17.945  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:34:17.945  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 13:34:17.947  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-05 13:34:17.947  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:17.947  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:17.947  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:17.948  5574  5620 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-05 13:34:17.948  5574  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-05 13:34:17.948  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 13:34:17.948  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:34:17.948  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:34:17.948  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-05 13:34:17.948  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:17.948  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:17.948  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:17.948  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:17.948  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.948  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:34:17.949  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:17.949  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:34:17.949  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de removed from the list
10-05 13:34:17.949  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:17.949  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf removed from the list
,10-05 13:34:17.951  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:17.958  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:17.958  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:17.958  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:17.959  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.959  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:17.959  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:17.959  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:17.959  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:17.960  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:17.960  5574  5620 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-05 13:34:17.961  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:17.961  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:17.961  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:17.961  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:17.961  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.961  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:17.961  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:17.961  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:17.961  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:17.961  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:17.961  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:17.961  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.961  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:17.961  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.961  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:17.962  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:17.962  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:34:17.962  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:17.962  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 13:34:17.964  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 13:34:17.965  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 13:34:17.965  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:17.965  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:17.965  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:17.965  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:17.965  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.965  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:17.965  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:17.965  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:17.966  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:17.966  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:17.966  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:17.966  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.966  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:17.966  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:17.966  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:17.966  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:17.966  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:17.966  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:17.966  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:17.967  5574  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 13:34:17.968  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:17.970  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:17.970  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:17.971  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:34:17.971  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:34:17.971  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:34:17.971  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:34:17.971  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:34:17.971  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:34:17.973  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:34:17.973  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 13:34:17.974  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:17.976  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 13:34:17.977  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:34:17.977  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 13:34:17.978  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:17.979  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-05 13:34:17.980  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-05 13:34:17.980  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 13:34:17.980  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:34:17.980  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:34:17.980  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:34:17.980  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:34:17.981  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:34:17.983  4535  4551 D BtGatt.GattService: registerClient() - UUID=706a14c0-99b8-4653-9b12-329b1220955d
10-05 13:34:17.985  4535  4623 D BtGatt.GattService: onClientRegistered() - UUID=706a14c0-99b8-4653-9b12-329b1220955d, clientIf=5
10-05 13:34:17.986  5574  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:34:17.987  4535  4560 D BtGatt.GattService: start scan with filters
10-05 13:34:17.992  4535  4628 D BtGatt.ScanManager: handling starting scan
10-05 13:34:17.993  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:34:17.993  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:34:17.993  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:34:17.993  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:34:17.993  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:34:17.993  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:34:17.994  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 13:34:17.995  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:34:17.995  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:34:17.995  4535  4628 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
10-05 13:34:17.995  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:34:17.995  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:34:17.997  5574  5620 I io.jxcore.node.ConnectionHelper: start: OK
10-05 13:34:18.002  4535  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:34:18.003  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:18.003  4535  4628 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:34:18.009  4535  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:34:18.010  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:18.010  4535  4628 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:34:18.010  4535  4628 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 13:34:18.022  4535  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:34:18.022  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:18.028  4535  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:34:18.029  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:34:18.496  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 13:34:18.497  5574  5574 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-05 13:34:18.497  5574  5574 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:34:18.892   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:19.239   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:34:19.893   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:20.894   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-05 13:34:23.001  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:23.001  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:23.001  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 13:34:23.001  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:23.001  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:34:23.001  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:34:23.002  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-05 13:34:23.002  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-05 13:34:23.002  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:34:23.002  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:34:23.003  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-05 13:34:23.003  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:34:23.004  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:34:23.005  4535  4760 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:34:23.007  4535  4551 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:34:23.008  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:34:23.009  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-05 13:34:23.009  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:34:23.009  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:34:23.009  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:34:23.009  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:34:23.009  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:34:23.010  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:34:23.011  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:34:23.012  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:34:23.012  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-05 13:34:23.012  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:34:23.012  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:34:23.012  4535  4535 D BtGatt.ScanManager: awakened up at time 236722
10-05 13:34:23.013  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:34:23.015  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:23.015  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:23.015  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:34:23.015  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:23.015  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:23.015  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:23.015  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:23.015  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:23.015  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:23.016  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:23.016  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:23.016  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:34:23.019  4535  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:34:23.019  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:23.019  4535  4628 D BtGatt.ScanManager: stopping BLe Batch
,10-05 13:34:23.029  4535  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 13:34:23.029  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:23.029  4535  4628 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:34:23.054  4535  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-05 13:34:23.054  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:23.054  4535  4623 D BtGatt.GattService: current time is 236764756504
10-05 13:34:23.055  4535  4623 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -89, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -86, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -79, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 13:34:23.057  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-05 13:34:23.058  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-05 13:34:23.059  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 13:34:23.059  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-05 13:34:23.060  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
10-05 13:34:23.060  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-05 13:34:23.517  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:34:25.287   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:34:25.895   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:26.897   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:27.898   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:28.018  5574  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-05 13:34:28.023  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:28.034  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:34:28.038  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:34:28.039  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:34:28.039  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:34:28.039  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:34:28.039  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-05 13:34:28.039  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:34:28.039  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 13:34:28.046  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-05 13:34:28.046  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 13:34:28.047  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:28.054  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:28.055  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 13:34:28.056  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-05 13:34:28.056  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:34:28.063  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:34:28.064  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:34:28.064  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:34:28.064  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:34:28.064  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 13:34:28.065  5574  5620 D BluetoothAdapter: STATE_ON
,10-05 13:34:28.070  4535  4780 D BtGatt.GattService: registerClient() - UUID=b4e7116e-4212-4a4e-8f7b-9ad5ad7ba749
,10-05 13:34:28.071  4535  4623 D BtGatt.GattService: onClientRegistered() - UUID=b4e7116e-4212-4a4e-8f7b-9ad5ad7ba749, clientIf=5
,10-05 13:34:28.072  5574  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:34:28.072  4535  4760 D BtGatt.GattService: start scan with filters
,10-05 13:34:28.077  4535  4628 D BtGatt.ScanManager: handling starting scan
10-05 13:34:28.077  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:34:28.077  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:34:28.077  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:34:28.077  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:34:28.078  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:34:28.078  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:34:28.078  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:34:28.082  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:34:28.082  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:34:28.082  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:34:28.085  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:34:28.087  4535  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:34:28.087  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.087  4535  4628 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 13:34:28.091  5574  5620 I io.jxcore.node.ConnectionHelper: start: OK
,10-05 13:34:28.095  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:28.095  5574  5620 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-05 13:34:28.095  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:28.095  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 13:34:28.095  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:28.095  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:34:28.095  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:28.096  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:34:28.096  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:34:28.096  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-05 13:34:28.096  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:34:28.096  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:34:28.096  4535  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:34:28.096  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:34:28.096  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.096  4535  4628 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:34:28.096  4535  4628 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 13:34:28.098  5574  5620 D BluetoothAdapter: STATE_ON
,10-05 13:34:28.098  4535  4551 D BtGatt.GattService: stopScan() - queue size =1
,10-05 13:34:28.099  4535  4782 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:34:28.100  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:34:28.100  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:34:28.100  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:34:28.100  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:34:28.100  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:34:28.100  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-05 13:34:28.101  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:34:28.101  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:34:28.102  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:34:28.102  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:34:28.102  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:34:28.102  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-05 13:34:28.103  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:34:28.103  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:34:28.105  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:28.105  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:28.105  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:28.105  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:28.105  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:34:28.105  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:34:28.105  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:28.105  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:28.105  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:28.105  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:28.105  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:28.105  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:28.106  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:28.106  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:28.108  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:28.108  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:28.108  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:28.108  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:28.109  5574  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 13:34:28.110  4535  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:34:28.110  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.113  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:28.118  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:34:28.118  4535  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:34:28.118  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:34:28.120  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:28.121  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:34:28.121  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:34:28.121  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:34:28.121  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:34:28.121  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:34:28.121  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 13:34:28.125  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:28.126  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:34:28.126  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 13:34:28.128  4535  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-05 13:34:28.128  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.129  4535  4628 D BtGatt.ScanManager: stopping BLe Batch
10-05 13:34:28.129  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:28.130  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:34:28.131  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-05 13:34:28.131  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:34:28.134  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 13:34:28.134  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:34:28.134  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:34:28.134  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:34:28.134  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:34:28.135  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:34:28.135  4535  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:34:28.135  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.135  4535  4628 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-05 13:34:28.137  4535  4782 D BtGatt.GattService: registerClient() - UUID=6470b630-54f4-43de-8ca7-a13900961731
10-05 13:34:28.138  4535  4623 D BtGatt.GattService: onClientRegistered() - UUID=6470b630-54f4-43de-8ca7-a13900961731, clientIf=5
,10-05 13:34:28.138  5574  5585 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:34:28.138  4535  4551 D BtGatt.GattService: start scan with filters
10-05 13:34:28.141  4535  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 13:34:28.141  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:34:28.142  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:34:28.142  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:34:28.142  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:34:28.142  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:34:28.142  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:34:28.142  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:34:28.142  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 13:34:28.142  4535  4628 D BtGatt.ScanManager: handling starting scan
,10-05 13:34:28.145  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:34:28.145  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:34:28.145  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 13:34:28.147  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:34:28.149  5574  5620 I io.jxcore.node.ConnectionHelper: start: OK
10-05 13:34:28.150  4535  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:34:28.150  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.150  4535  4628 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 13:34:28.155  4535  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:34:28.155  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:28.155  4535  4628 D BtGatt.ScanManager: Starting BLE batch scan
,10-05 13:34:28.155  4535  4628 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 13:34:28.164  4535  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 13:34:28.165  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:34:28.170  4535  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:34:28.170  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:34:28.646  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 13:34:28.646  5574  5574 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:34:28.647  5574  5574 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:34:28.899   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:29.900   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:30.900   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-05 13:34:31.332   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:34:33.149  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:33.149  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:34:33.150  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 13:34:33.150  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:33.150  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-05 13:34:33.150  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:33.150  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:34:33.150  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:34:33.151  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:34:33.151  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:34:33.151  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-05 13:34:33.151  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:34:33.153  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:34:33.155  4535  4551 D BtGatt.GattService: stopScan() - queue size =1
,10-05 13:34:33.157  4535  4780 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-05 13:34:33.158  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:34:33.158  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:34:33.158  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:34:33.158  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:34:33.159  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:34:33.159  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:34:33.159  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:34:33.159  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:34:33.161  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:34:33.162  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:34:33.162  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:34:33.162  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:34:33.162  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:34:33.163  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:34:33.165  4535  4535 D BtGatt.ScanManager: awakened up at time 246875
10-05 13:34:33.166  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:33.166  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:33.167  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:34:33.171  4535  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:34:33.171  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:33.171  4535  4628 D BtGatt.ScanManager: stopping BLe Batch
,10-05 13:34:33.180  4535  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:34:33.180  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:34:33.180  4535  4628 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:34:33.195  4535  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,10-05 13:34:33.195  4535  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:34:33.195  4535  4623 D BtGatt.GattService: current time is 246905766506
10-05 13:34:33.196  4535  4623 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -86, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 13:34:33.196  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 13:34:33.196  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-05 13:34:33.196  4535  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-05 13:34:33.668  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:34:33.669  5574  5574 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:33.669  5574  5574 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:34:34.363   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:34:38.167  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:38.168  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:34:38.168  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 13:34:38.168  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:34:38.168  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:38.168  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:34:38.168  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.169  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.169  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.169  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.169  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.169  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.171  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.171  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:38.173  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.174  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.174  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.174  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.175  5574  5620 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-05 13:34:38.177  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:38.178  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:34:38.178  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.178  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.178  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.179  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.179  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.179  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
,10-05 13:34:38.179  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.179  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.179  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.179  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.180  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.180  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:38.180  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.182  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.183  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.183  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.183  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.185  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 13:34:38.186  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:38.186  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.186  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.186  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.188  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.188  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.188  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:34:38.188  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.188  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.189  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.189  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.189  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.189  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.189  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:38.189  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.191  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.191  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.191  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.191  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.192  5574  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-05 13:34:38.192  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:38.192  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.192  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.192  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.193  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.193  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.193  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:34:38.193  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.193  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.193  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.193  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.193  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.193  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:38.193  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.193  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.195  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.195  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.195  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.195  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.196  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-05 13:34:38.197  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:38.197  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.197  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.197  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:34:38.197  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.197  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.197  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.197  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.197  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.197  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.197  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.198  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.198  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:38.198  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.198  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.200  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.200  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.200  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:38.200  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:38.201  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-05 13:34:38.201  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:38.202  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:38.202  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 13:34:38.202  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:34:38.202  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:34:38.202  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 13:34:38.202  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:38.202  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:34:38.202  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:38.202  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.202  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.202  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.203  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.203  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.203  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.203  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.203  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.203  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.203  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:34:38.203  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.203  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.203  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.203  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.206  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.206  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.207  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.207  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.209  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:34:38.210  5574  5620 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 13:34:38.210  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 13:34:38.214  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-05 13:34:38.214  5574  5620 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 13:34:38.214  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-05 13:34:38.215  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 13:34:38.216  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-05 13:34:38.216  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-05 13:34:38.216  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 13:34:38.217  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 13:34:38.217  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,10-05 13:34:38.218  5574  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 13:34:38.218  5574  5620 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-05 13:34:38.218  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:34:38.218  5574  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 13:34:38.218  5574  5620 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-05 13:34:38.219  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:34:38.219  5574  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 13:34:38.219  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-05 13:34:38.222  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-05 13:34:38.223  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-05 13:34:38.223  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-05 13:34:38.223  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-05 13:34:38.224  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-05 13:34:38.224  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,10-05 13:34:38.224  5574  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:34:38.224  5574  5620 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-05 13:34:38.224  5574  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-05 13:34:38.224  5574  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-05 13:34:38.224  5574  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-05 13:34:38.224  5574  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-05 13:34:38.225  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:38.225  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.225  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.225  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.225  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.225  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.225  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.225  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-05 13:34:38.226  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
,10-05 13:34:38.226  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.226  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.227  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.227  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.227  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.227  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.227  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.227  5574  5621 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-05 13:34:38.227  5574  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-05 13:34:38.227  5574  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-05 13:34:38.227  5574  5621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:34:38.228  5574  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
,10-05 13:34:38.229  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.229  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.229  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:38.229  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.230  5574  5620 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-05 13:34:38.230  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:38.230  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.230  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.231  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.231  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.231  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.231  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.231  5574  5621 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-05 13:34:38.231  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.231  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.231  5574  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-05 13:34:38.231  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.231  5574  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-05 13:34:38.231  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.231  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.231  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.231  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.231  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.229  4782  4782 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32542]" dev="sockfs" ino=32542 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:34:38.229  4782  4782 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32542]" dev="sockfs" ino=32542 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:34:38.233  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:34:38.233  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.233  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.234  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.235  5574  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-05 13:34:38.235  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:38.235  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.235  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 13:34:38.235  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.236  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.236  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.236  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.236  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.236  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.236  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:38.236  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.236  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.236  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.236  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.236  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.237  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:34:38.237  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.237  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.237  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.238  5574  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-05 13:34:38.238  5574  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-05 13:34:38.238  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 13:34:38.238  5574  5620 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-05 13:34:38.238  5574  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 13:34:38.238  5574  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,10-05 13:34:38.238  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 13:34:38.239  5574  5620 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-05 13:34:38.239  5574  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 13:34:38.239  5574  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 13:34:38.239  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 13:34:38.239  5574  5620 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-05 13:34:38.239  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:34:38.239  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:38.239  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:38.239  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:38.239  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.239  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.239  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.239  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
,10-05 13:34:38.239  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.239  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.239  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.240  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.240  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.240  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:38.240  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.241  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:38.241  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:38.241  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:38.241  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.242  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:34:38.242  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.242  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:38.242  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:38.242  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:38.242  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:38.242  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:38.242  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:38.242  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:38.242  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:40.417   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:34:40.901   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:41.902   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:42.903   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:43.243  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:43.243  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.243  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:34:43.244  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.244  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.244  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:43.244  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
,10-05 13:34:43.244  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:43.245  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:43.245  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:43.245  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:34:43.245  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.245  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:43.245  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:43.246  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
,10-05 13:34:43.246  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.246  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.246  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:43.246  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.246  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.246  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.247  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:43.249  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:43.249  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:34:43.249  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.250  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:43.254  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-05 13:34:43.254  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:34:43.256  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-05 13:34:43.261  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-05 13:34:43.261  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-05 13:34:43.261  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-05 13:34:43.261  5574  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-05 13:34:43.261  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-05 13:34:43.262  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:34:43.262  5574  5574 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-05 13:34:43.262  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:43.262  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-05 13:34:43.262  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-05 13:34:43.262  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-05 13:34:43.262  5574  5623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:34:43.262  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.262  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-05 13:34:43.262  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-05 13:34:43.263  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:43.263  5574  5574 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-05 13:34:43.263  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.263  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:34:43.263  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:34:43.263  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:34:43.263  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.263  4551  4551 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31586]" dev="sockfs" ino=31586 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:34:43.263  4551  4551 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31586]" dev="sockfs" ino=31586 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:34:43.265  5574  5623 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-05 13:34:43.265  5574  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-05 13:34:43.263  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.265  5574  5623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-05 13:34:43.266  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:34:43.267  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
,10-05 13:34:43.267  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:43.267  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:34:43.267  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:43.267  5574  5574 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-05 13:34:43.267  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:43.267  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:43.267  5574  5574 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:43.267  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:43.267  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:34:43.267  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.267  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.267  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:43.268  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:43.268  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.268  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.268  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:43.268  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.268  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:43.268  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.268  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.269  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:43.269  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:43.269  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.269  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.271  5574  5620 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-05 13:34:43.271  5574  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-05 13:34:43.271  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 13:34:43.271  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:34:43.271  5574  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:34:43.272  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:43.272  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:43.272  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:43.272  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:43.272  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.272  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.272  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:34:43.272  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:43.272  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.272  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.272  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:43.272  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.272  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.273  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:43.273  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.275  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:43.276  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:34:43.276  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.277  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.282  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:43.282  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:34:43.282  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:43.283  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:34:43.283  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.283  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.283  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:43.283  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:43.283  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.283  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.283  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:34:43.283  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.283  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.283  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.283  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.284  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:43.285  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:34:43.285  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.285  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.286  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:34:43.286  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:34:43.286  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:34:43.286  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:34:43.286  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.286  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.286  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:34:43.286  5574  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd486de not in the list
10-05 13:34:43.286  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:43.286  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.286  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:34:43.286  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.286  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.286  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:43.286  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:43.287  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:34:43.287  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:34:43.287  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:34:43.288  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24940bf not in the list
10-05 13:34:43.289  5574  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-05 13:34:43.289  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 13:34:43.289  5574  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-05 13:34:43.289  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-05 13:34:43.289  5574  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-05 13:34:43.289  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 13:34:43.291  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 13:34:43.291  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-05 13:34:43.292  5574  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-05 13:34:43.292  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 13:34:43.293  5574  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-05 13:34:43.293  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 13:34:43.293  5574  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-05 13:34:43.293  5574  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-05 13:34:43.293  5574  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-05 13:34:43.294  5574  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-05 13:34:43.294  5574  5620 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-05 13:34:43.294  5574  5620 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-05 13:34:43.294  5574  5620 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-05 13:34:43.294  5574  5620 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-05 13:34:43.295  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:34:43.295  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2764789 added. We now have 3 listener(s)
,10-05 13:34:43.295  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:43.297  5574  5620 D BluetoothAdapter: enable(): BT is already enabled..!
10-05 13:34:43.297   931  3358 D WifiService: setWifiEnabled: true pid=5574, uid=10077
10-05 13:34:43.298   931  3358 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:34:43.358  4535  4725 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-05 13:34:43.358  4535  4754 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-05 13:34:43.768  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:34:43.904   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:44.905   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:34:45.906   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-05 13:34:46.461   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:34:48.303  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 13:34:48.304  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31e638e added. We now have 4 listener(s)
10-05 13:34:48.304  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:48.317  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:48.317  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31e638e removed from the list
10-05 13:34:48.317  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:34:48.317  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:34:48.317  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:34:48.319  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:34:48.319  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@419d7af added. We now have 4 listener(s)
10-05 13:34:48.320  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:48.322  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:34:48.323  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@419d7af removed from the list
10-05 13:34:48.323  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:34:48.323  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:34:48.323  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:34:48.325  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:34:48.325  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1257bc added. We now have 4 listener(s)
,10-05 13:34:48.325  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:34:48.331   931  3618 D WifiService: setWifiEnabled: false pid=5574, uid=10077
,10-05 13:34:48.331   931  3618 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-05 13:34:48.336   931  2911 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 13:34:48.337   931  2911 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-05 13:34:48.337   931  2911 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:34:48.337   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:34:48.345  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:34:48.350  4535  4619 D BluetoothAdapterState: Current state: ON, message: 23
10-05 13:34:48.350  4535  4619 D BluetoothAdapterProperties: Setting state to 13
,10-05 13:34:48.351  4535  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-05 13:34:48.351  4535  4619 D BluetoothAdapterProperties: onBluetoothDisable()
,10-05 13:34:48.352  4535  4619 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:34:48.352  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:48.353  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:48.354  4535  4623 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:34:48.354  4535  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 13:34:48.356  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.356  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:48.357  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:34:48.361  4535  4535 D BluetoothMapService: onReceive
,10-05 13:34:48.361  4535  4535 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:34:48.361   931  5325 D DhcpClient: Clearing IP address
10-05 13:34:48.361  4535  4535 D BluetoothMapService: STATE_TURNING_OFF
10-05 13:34:48.362  4535  4535 D BluetoothMapService: MAP Service closeService in
10-05 13:34:48.362  4535  4535 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 13:34:48.362  4535  4535 D ObexServerSockets0: shutdown(block = true)
10-05 13:34:48.362  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.363  4535  4535 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:34:48.363  4535  4754 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 13:34:48.364  4535  4784 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 13:34:48.364   507   923 D CommandListener: Clearing all IP addresses on wlan0
10-05 13:34:48.365  4535  4783 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-05 13:34:48.363  4535  4535 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:34:48.368  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.368  4535  4535 I BtOppRfcommListener: stopping Accept Thread
10-05 13:34:48.369  4535  5239 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 13:34:48.370  4535  5239 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-05 13:34:48.372   507   923 D CommandListener: Setting iface cfg
,10-05 13:34:48.378  3521  5381 V NativeCrypto: Read error: ssl=0x7f7532f000: I/O error during system call, Connection timed out
10-05 13:34:48.381  3521  5381 V NativeCrypto: SSL shutdown failed: ssl=0x7f7532f000: I/O error during system call, Broken pipe
,10-05 13:34:48.382  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:48.382  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:48.383   931  3749 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-05 13:34:48.383  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:48.383  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:48.384   931  5323 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-05 13:34:48.386   931  5323 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-05 13:34:48.387  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:48.387  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:34:48.388   931   944 I ActivityManager: Start proc 5627:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-05 13:34:48.388  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.388  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:48.389   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-05 13:34:48.389   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-05 13:34:48.390   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-05 13:34:48.391  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.394  4535  4535 D HeadsetService: Received stop request...Stopping profile...
10-05 13:34:48.394   931  5326 D DhcpClient: Receive thread stopped
,10-05 13:34:48.396   931   931 D BluetoothHeadset: Proxy object disconnected
,10-05 13:34:48.396   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:34:48.396   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:34:48.397  3066  3921 D BluetoothHeadset: Proxy object disconnected
10-05 13:34:48.398  3726  3750 D BluetoothHeadset: Proxy object disconnected
,10-05 13:34:48.398  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.400  4535  4535 D A2dpService: Received stop request...Stopping profile...
10-05 13:34:48.400   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-05 13:34:48.401  4535  4771 D A2dpStateMachine: Exit Disconnected: -1
10-05 13:34:48.401   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-05 13:34:48.401  3066  3066 D HeadsetProfile: Bluetooth service disconnected
10-05 13:34:48.401  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:48.402  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:34:48.402   540   540 E Parcel  : Reading a NULL string not supported here.
,10-05 13:34:48.402  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.403  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:48.403   931   931 D RttService: SCAN_AVAILABLE : 1
,10-05 13:34:48.403   931  3018 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-05 13:34:48.406  3066  3066 D BluetoothA2dp: Proxy object disconnected
10-05 13:34:48.406   931   931 D BluetoothA2dp: Proxy object disconnected
10-05 13:34:48.408  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.408  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:48.409  4535  4535 D HidService: Received stop request...Stopping profile...
10-05 13:34:48.409  4535  4535 D HidService: Stopping Bluetooth HidService
10-05 13:34:48.409   931  2925 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-05 13:34:48.411  4535  4535 V BluetoothAdapterState: isTurningOff()=true
10-05 13:34:48.411  3676  3841 W QCNEJ   : |CORE| network lost: 100
10-05 13:34:48.412  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.412  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.412  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.412  3676  3841 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-05 13:34:48.413  4535  4535 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-05 13:34:48.414  4535  4535 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-05 13:34:48.414  4535  4725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:34:48.414  4535  4725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:34:48.414  4535  4725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:34:48.414  4535  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 13:34:48.414  4535  4535 D HealthService: Received stop request...Stopping profile...
,10-05 13:34:48.414  4535  4623 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-05 13:34:48.415  4535  4535 V BluetoothAdapterState: isTurningOff()=true
10-05 13:34:48.415  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.415  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.413  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:48.415  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.416  4535  4535 D PanService: Received stop request...Stopping profile...
10-05 13:34:48.415  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:48.416  3066  3066 D BluetoothInputDevice: Proxy object disconnected
10-05 13:34:48.416  3066  3066 D HidProfile: Bluetooth service disconnected
10-05 13:34:48.418  3066  3066 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 13:34:48.418  3066  3066 D PanProfile: Bluetooth service disconnected
10-05 13:34:48.418  4535  4725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:34:48.418  4535  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 13:34:48.419  4535  4725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:34:48.419  4535  4725 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:34:48.419  4535  4725 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:34:48.419  4535  4725 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:34:48.419  4535  4725 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:34:48.419  4535  4535 D BluetoothMapService: Received stop request...Stopping profile...
10-05 13:34:48.419  4535  4535 D BluetoothMapService: stop()
10-05 13:34:48.419  4535  4535 D BluetoothMapAppObserver: deinitObservers()
10-05 13:34:48.419  4535  4535 D BluetoothMapAppObserver: removeReceiver()
10-05 13:34:48.421  4535  4535 V BluetoothAdapterState: isTurningOff()=true
,10-05 13:34:48.421  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.421  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.421  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.421   931  2911 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-05 13:34:48.422  4535  4535 D SapService: Received stop request...Stopping profile...
10-05 13:34:48.422  4535  4535 V SapService: stop()
10-05 13:34:48.424  4535  4535 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 13:34:48.424  4535  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:34:48.424  4535  4535 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 13:34:48.424  4535  4535 V BluetoothAdapterState: isTurningOff()=true
10-05 13:34:48.424  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.424  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.424  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.424  4535  4535 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 13:34:48.425  4535  4623 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-05 13:34:48.425  4535  4535 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-05 13:34:48.425  4535  4535 V BluetoothAdapterState: isTurningOff()=true
10-05 13:34:48.425  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.425  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.425  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.425  4535  4535 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-05 13:34:48.425  4535  4535 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-05 13:34:48.426  4535  4535 D BluetoothMapService: MAP Service closeService in
10-05 13:34:48.426  4535  4535 V BluetoothAdapterState: isTurningOff()=true
10-05 13:34:48.426  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.426  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.426  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.426  4535  4535 D BluetoothMapService: cleanup()
10-05 13:34:48.427  4535  4535 D BluetoothMapService: MAP Service closeService in
10-05 13:34:48.427  4535  4535 V BluetoothAdapterState: isTurningOff()=true
10-05 13:34:48.427  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.427  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.427  4535  4535 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:34:48.427  4535  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 13:34:48.427  4535  4619 D BluetoothAdapterProperties: Setting state to 15
,10-05 13:34:48.427  4535  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 13:34:48.428  4535  4619 I BluetoothAdapterState: Entering BleOnState
10-05 13:34:48.428  3066  5573 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 13:34:48.429  3066  3066 D BluetoothMap: Proxy object disconnected
10-05 13:34:48.429  3066  3066 D MapProfile: Bluetooth service disconnected
10-05 13:34:48.432  3726  3748 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:34:48.433  3066  3318 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-05 13:34:48.436   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-05 13:34:48.437   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:34:48.438  3066  3077 D BluetoothPan: onBluetoothStateChange on: false
,10-05 13:34:48.438   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:34:48.439  3066  3078 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:34:48.439   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-05 13:34:48.439  3066  3921 D BluetoothMap: onBluetoothStateChange: up=false
10-05 13:34:48.440  3066  5573 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:34:48.440   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:34:48.440   931  2911 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:34:48.441  4535  4619 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 13:34:48.441  4535  4619 D BluetoothAdapterProperties: Setting state to 16
10-05 13:34:48.441  4535  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 13:34:48.442  4535  4619 D BluetoothAdapterProperties: onBleDisable
10-05 13:34:48.443  4535  4619 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:34:48.443  4535  4620 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 13:34:48.444  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.444  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:48.444  4535  4725 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 13:34:48.444  4535  4725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:34:48.445  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.445  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:48.445  4535  4623 D BluetoothAdapterProperties: Scan Mode:20
,10-05 13:34:48.449  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.449  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:48.453  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.453  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:34:48.455  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:48.457  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.457  5627  5627 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-05 13:34:48.459  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:48.463   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:34:48.464   931  2925 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-05 13:34:48.464   507   923 D CommandListener: Clearing all IP addresses on wlan0
10-05 13:34:48.464   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:34:48.465   507   923 D TetherController: Setting IP forward enable = 0
10-05 13:34:48.467   931   948 D Tethering: MasterInitialState.processMessage what=3
10-05 13:34:48.469   931  2911 D DhcpClient: doQuit
10-05 13:34:48.469   931  2911 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-05 13:34:48.469   931  5325 D DhcpClient: onQuitting
10-05 13:34:48.470  3389  3389 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 13:34:48.470  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:48.472  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:48.473  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.473  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:48.475  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.475  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:48.476  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.476  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:48.478  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:48.478  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:48.479  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Blu,etooth is disabled - will return stored value
10-05 13:34:48.479  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:48.481  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.482  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.483  3907  3907 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-05 13:34:48.488  5224  5224 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@549dbc8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-05 13:34:48.491  4984  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 13:34:48.491  4984  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:34:48.491  4984  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 13:34:48.491  4984  5007 E SarControlService: no key has been found,reset the power
10-05 13:34:48.492  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:34:48.492  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:34:48.492  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:34:48.492  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:34:48.493  5009  5009 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 13:34:48.493  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:34:48.493  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 13:34:48.494  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:34:48.495  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-05 13:34:48.495  5009  5009 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:34:48.497  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000ea03000000000000ffffffff]
10-05 13:34:48.497  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:34:48.497  5009  5023 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-05 13:34:48.498  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:34:48.498  4984  4994 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-05 13:34:48.501  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000eb03000000000000ffffffff]
10-05 13:34:48.501  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:34:48.501  5009  5023 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,10-05 13:34:48.502  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-05 13:34:48.502  4984  4995 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 13:34:48.503  3389  3389 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-05 13:34:48.508  3389  3389 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-05 13:34:48.510   507   916 W SocketClient: write error (Broken pipe)
10-05 13:34:48.510   507   916 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-05 13:34:48.510   507   916 W SocketListener: Error sending broadcast (Broken pipe)
,10-05 13:34:48.513  5627  5627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 13:34:48.516   507   923 E Netd    : netlink response contains error (No such file or directory)
10-05 13:34:48.517   507   923 D TetherController: Setting IP forward enable = 0
,10-05 13:34:48.518   931  2925 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-05 13:34:48.522   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce2a8d5:true
,10-05 13:34:48.524  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:34:48.536  3389  3389 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 13:34:48.539   931  3789 I ActivityManager: Start proc 5663:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-05 13:34:48.547  3389  3389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 13:34:48.572  5627  5627 D LocalBluetoothProfileManager: Adding local MAP profile
,10-05 13:34:48.574  5627  5627 D BluetoothMap: Create BluetoothMap proxy object
,10-05 13:34:48.600  5627  5627 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-05 13:34:48.612  5663  5663 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-05 13:34:48.622  5627  5627 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:34:48.631   931   942 I ActivityManager: Killing 4916:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-05 13:34:48.658   931  2911 D wifi    : In wifi stop Hal
,10-05 13:34:48.658   931  2911 D wifi    : halHandle = 0x7f63822400, mVM = 0x7f7fe4d140, mCls = 0x100a02
10-05 13:34:48.659  4958  4958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 13:34:48.660   931  3388 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 13:34:48.660   931  3388 D WifiHAL : Got a signal to exit!!!
10-05 13:34:48.660   931  3388 I WifiHAL : Exit wifi_event_loop
,10-05 13:34:48.660   931  2911 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-05 13:34:48.660  4535  4623 I bt_hci  : shut_down
10-05 13:34:48.661   931  2911 E WifiHAL : Event processing terminated
10-05 13:34:48.661   931  2911 D wifi    : In wifi cleaned up handler
10-05 13:34:48.661   931  2911 I WifiHAL : Internal cleanup completed
,10-05 13:34:48.661  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.661  4048  4167 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:34:48.662  4535  4631 D bt_hwcfg: hw_epilog_process
10-05 13:34:48.663  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.663  4535  4631 I bt_vendor: low_power_mode_cb
10-05 13:34:48.665  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:48.666  4535  4631 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-05 13:34:48.666  4535  4631 I bt_vendor: epilog_cb
10-05 13:34:48.666  4535  4631 I bt_hci  : epilog_finished_callback
,10-05 13:34:48.669  4535  4623 I bt_hci_h4: hal_close
10-05 13:34:48.670  4535  4623 I bt_userial_vendor: device fd = 54 close
,10-05 13:34:48.682   931  3388 D wifi    : set interface wlan0 flags (DOWN)
,10-05 13:34:48.682   931  2911 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 13:34:48.780  4535  4620 D bt_stack_manager: event_shut_down_stack finished.
,10-05 13:34:48.781  4535  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 13:34:48.782  4535  4619 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-05 13:34:48.782  4535  4535 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 13:34:48.783  4535  4535 D BtGatt.GattService: Received stop request...Stopping profile...
10-05 13:34:48.783  4535  4535 D BtGatt.GattService: stop()
10-05 13:34:48.783  4535  4535 D BtGatt.AdvertiseManager: advertise clients cleared
,10-05 13:34:48.784  4535  4535 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:34:48.784  4535  4535 V BluetoothAdapterState: isTurningOn()=false
10-05 13:34:48.784  4535  4535 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:34:48.784  4535  4535 V BluetoothAdapterState: isBleTurningOff()=true
10-05 13:34:48.785  4535  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-05 13:34:48.785  4535  4619 D BluetoothAdapterProperties: Setting state to 10
10-05 13:34:48.785  4535  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-05 13:34:48.785  4535  4619 I BluetoothAdapterState: Entering OffState
,10-05 13:34:48.786   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-05 13:34:48.792  4535  4535 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-05 13:34:48.792  4535  4535 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 13:34:48.792  4535  4535 I BluetoothServiceJni: cleanupNative: return from cleanup
10-05 13:34:48.793  4535  4620 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 13:34:48.810  4535  4620 D bt_stack_manager: event_clean_up_stack finished.
,10-05 13:34:48.816  4535  4535 I art     : System.exit called, status: 0
,10-05 13:34:48.816  4535  4535 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.k.d(PG:583)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.841  5663  5663 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:34:48.841  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:34:48.846  5627  5627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 13:34:48.849   931  3537 I ActivityManager: Process com.android.bluetooth (pid 4535) has died
10-05 13:34:48.864   931  3736 I ActivityManager: Start proc 5694:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
10-05 13:34:48.865  5627  5627 D DockEventReceiver: finishStartingService: stopping service
10-05 13:34:48.867   931   941 I ActivityManager: Killing 5353:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
10-05 13:34:48.884   931   948 D Tethering: InitialState.processMessage what=4
10-05 13:34:48.894   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 13:34:48.952  5694  5694 D AdapterServiceConfig: Adding HeadsetService
,10-05 13:34:48.952  5694  5694 D AdapterServiceConfig: Adding A2dpService
10-05 13:34:48.952  5694  5694 D AdapterServiceConfig: Adding HidService
10-05 13:34:48.952  5694  5694 D AdapterServiceConfig: Adding HealthService
10-05 13:34:48.953  5694  5694 D AdapterServiceConfig: Adding PanService
10-05 13:34:48.953  5694  5694 D AdapterServiceConfig: Adding GattService
10-05 13:34:48.953  5694  5694 D AdapterServiceConfig: Adding BluetoothMapService
10-05 13:34:48.953  5694  5694 D AdapterServiceConfig: Adding SapService
10-05 13:34:48.955   931   942 I ActivityManager: Killing 5366:com.android.chrome/u0a39 (adj 15): empty #17
,10-05 13:34:49.003  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:34:49.013  3800  3800 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 13:34:49.016  3800  3800 D SystemUpdateService: onCreate
,10-05 13:34:49.019  3800  3800 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 13:34:49.027  3800  3800 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 13:34:49.029  3800  5350 I iu.UploadsManager: num queued entries: 0
,10-05 13:34:49.029  3800  5350 I iu.UploadsManager: num updated entries: 0
,10-05 13:34:49.034  3800  3800 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 13:34:49.035  3800  3800 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 13:34:49.043  3800  5707 I SystemUpdateService: active receiver: enabled
,10-05 13:34:49.045  3800  5350 I iu.SyncManager: NEXT; no task
,10-05 13:34:49.048   931   942 I ActivityManager: Start proc 5709:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-05 13:34:49.051  3800  5707 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:34:49.053  3800  5707 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 13:34:49.054  3800  5707 I SystemUpdateService: now status is 0 (complete)
10-05 13:34:49.054  3800  5707 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:34:49.054  3800  5707 I SystemUpdateService: file has been verified
10-05 13:34:49.054  3800  5707 I SystemUpdateService: OTA package size = 21989297
,10-05 13:34:49.085  5709  5709 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-05 13:34:49.088  5709  5709 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:34:49.090  3800  5707 I SystemUpdateService: showing system update notification
,10-05 13:34:49.095  5709  5709 D SprintDMHelper: simOperator: 
,10-05 13:34:49.096  5709  5709 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:34:49.107   931  3358 I ActivityManager: Start proc 5721:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-05 13:34:49.128  3800  3800 D SystemUpdateService: onDestroy
,10-05 13:34:49.129   931   942 I ActivityManager: Killing 5385:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-05 13:34:49.204  4958  5735 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 13:34:49.212   931  3749 I ActivityManager: Start proc 5736:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-05 13:34:49.215   931  3749 I ActivityManager: Killing 5224:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-05 13:34:49.273  5736  5736 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-05 13:34:49.414  5663  5681 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-05 13:34:49.457   931   941 I ActivityManager: Killing 4633:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-05 13:34:49.471   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fdec:true
,10-05 13:34:49.510   931  3789 I ActivityManager: Start proc 5750:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-05 13:34:49.541  5750  5750 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-05 13:34:49.548   931   942 I ActivityManager: Killing 5434:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-05 13:34:53.359   931  3618 D WifiService: setWifiEnabled: true pid=5574, uid=10077
10-05 13:34:53.360   931  3618 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:34:53.368   507   923 D SoftapController: Softap fwReload - Ok
,10-05 13:34:53.374   507   923 D CommandListener: Setting iface cfg
,10-05 13:34:53.374   507   923 D CommandListener: Trying to bring down wlan0
10-05 13:34:53.376   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:34:53.381   931  2911 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 13:34:53.954   931  2911 D wifi    : set interface wlan0 flags (UP)
,10-05 13:34:53.954   931  2911 I WifiHAL : Initializing wifi
10-05 13:34:53.954   931  2911 I WifiHAL : Creating socket
,10-05 13:34:53.957   931  2911 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-05 13:34:53.957   931  2911 D wifi    : Did set static halHandle = 0x7f63822400
10-05 13:34:53.958   931  2911 D wifi    : halHandle = 0x7f63822400, mVM = 0x7f7fe4d140, mCls = 0x201962
,10-05 13:34:53.958   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-05 13:34:53.958   931  2911 D wifi    : array field set
10-05 13:34:53.959   931  2911 I WifiNative-HAL: interface[0] = wlan0
10-05 13:34:53.960   931  5768 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547130319872
10-05 13:34:53.960   931  5768 D wifi    : waitForHalEvents called, vm = 0x7f7fe4d140, obj = 0x201962, env = 0x7f6143c0c0
,10-05 13:34:54.024  5769  5769 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 13:34:54.039  5769  5769 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:34:54.052  5769  5769 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:34:54.052  5769  5769 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 13:34:54.062   931  2911 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 13:34:54.070  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:54.070  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:54.071  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:54.071  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:34:54.075  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:54.075  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:54.075  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:54.075  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:54.078  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:54.079  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:54.079  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:54.079  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:34:54.079   931  2911 D WifiConfigStore: Loading config and enabling all networks 
10-05 13:34:54.080  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:54.081  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:54.082  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:54.090   931  2911 D WifiConfigStore: loaded 0 passpoint configs
,10-05 13:34:54.090   931  2911 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 13:34:54.091   931  2911 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-05 13:34:54.091   931  2911 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-05 13:34:54.093   931  2911 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-05 13:34:54.093   931  2911 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 13:34:54.093   931  2911 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 13:34:54.093   931  2911 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 13:34:54.097  4958  4958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:34:54.097   931  2911 D WifiNative-HAL: Setting external_sim to 1
10-05 13:34:54.097   931  2911 D wifi    : setting dfs flag to true, 0x7f65c97200
10-05 13:34:54.098   931  2911 D WifiStateMachine: Setting OUI to DA-A1-19
,10-05 13:34:54.098   931  2911 D wifi    : setting scan oui 0x7f65c97200
10-05 13:34:54.098   931  2911 D WifiHAL : Sending mac address OUI
10-05 13:34:54.102   931  2911 E native  : do suspend false
,10-05 13:34:54.110   931  2911 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-05 13:34:54.110   931   931 D RttService: SCAN_AVAILABLE : 3
10-05 13:34:54.110   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-05 13:34:54.110   931  3018 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-05 13:34:54.111   507   923 D CommandListener: Setting iface cfg
,10-05 13:34:54.115   931  2896 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-05 13:34:54.115   931  2896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 13:34:54.124   931  2896 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 13:34:54.128   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267838 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-05 13:34:54.128   931  2896 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 13:34:57.279  5769  5769 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:34:57.286  5769  5769 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:34:57.291  5769  5769 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:34:57.294  5769  5769 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:34:57.349   931  2911 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 13:34:57.351   931  2911 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-05 13:34:57.351   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:34:57.362   931  2911 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 13:34:57.392   931  2911 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 13:34:57.394  5769  5769 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 13:34:57.812  5769  5769 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 13:34:57.844  5769  5769 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 13:34:57.845  5769  5769 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 13:34:57.857   931  2911 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-05 13:34:57.858   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-05 13:34:57.858   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 13:34:57.873   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:34:57.885   507   923 D CommandListener: Setting iface cfg
,10-05 13:34:57.889   931  2911 D WifiStateMachine: Start Dhcp Watchdog 2
,10-05 13:34:57.895   931  5777 D DhcpClient: Receive thread started
,10-05 13:34:57.898   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 13:34:57.898   931  2911 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-05 13:34:57.898   931  2925 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-05 13:34:57.978   931  2911 E native  : do suspend false
,10-05 13:34:57.991   931  5776 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 13:34:58.005   931  5777 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,10-05 13:34:58.006   931  5776 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,10-05 13:34:58.008   931  5776 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 13:34:58.022   931  5777 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 13:34:58.023   931  5776 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 13:34:58.026   507   923 D CommandListener: Setting iface cfg
,10-05 13:34:58.031   931  2911 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 13:34:58.034   931  5776 D DhcpClient: Scheduling renewal in 86399s
,10-05 13:34:58.045   931  2911 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-05 13:34:58.045   931  2911 D WifiConfigStore: No blacklist allowed without epno enabled
,10-05 13:34:58.046   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-05 13:34:58.048   931  2911 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 13:34:58.050   931  2925 D ConnectivityService: Adding iface wlan0 to network 101
,10-05 13:34:58.096   931  2925 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 13:34:58.096   931  2925 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-05 13:34:58.098   931  2925 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-05 13:34:58.099   931  2925 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-05 13:34:58.101   931  2925 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-05 13:34:58.108   931  2925 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 13:34:58.112   931  2925 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-05 13:34:58.112   931  2925 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-05 13:34:58.112   931  2925 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,10-05 13:34:58.112   931  2925 D ConnectivityService:    accepting network in place of null
10-05 13:34:58.112   931  2911 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 13:34:58.112   931  2911 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:34:58.113   931  2925 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 13:34:58.128   931  5775 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 13:34:58.134   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:34:58.155   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:34:58.159   931  2925 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-05 13:34:58.159  3676  3841 W QCNEJ   : |CORE| network available: 101
10-05 13:34:58.159   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:34:58.161   931  2925 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-05 13:34:58.162   931   948 D Tethering: MasterInitialState.processMessage what=3
,10-05 13:34:58.165  3676  3841 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 13:34:58.166  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:58.166  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:58.166  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.166  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:58.167  3676  3841 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-05 13:34:58.167  3676  3841 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-05 13:34:58.169  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:58.169  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:34:58.169  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.169  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:58.171  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:34:58.171  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:34:58.171  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.171  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:34:58.174  4984  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 13:34:58.174  4984  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:34:58.174  4984  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-05 13:34:58.174  4984  5007 E SarControlService: no key has been found,reset the power
10-05 13:34:58.175  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-05 13:34:58.175  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:34:58.175  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-05 13:34:58.175  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:34:58.175  5009  5009 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-05 13:34:58.177  3907  3907 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-05 13:34:58.179  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:34:58.179  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 13:34:58.179  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:34:58.179  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:34:58.180  5009  5009 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:34:58.182  3800  3800 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 13:34:58.183  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000ec03000000000000ffffffff]
,10-05 13:34:58.183  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:34:58.183  5009  5023 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-05 13:34:58.183  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000ed03000000000000ffffffff]
10-05 13:34:58.183  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:34:58.183  5009  5023 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-05 13:34:58.184  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:34:58.185  4984  4994 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 13:34:58.187  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-05 13:34:58.187  4984  4995 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 13:34:58.187  3800  3800 D SystemUpdateService: onCreate
10-05 13:34:58.191  3800  3800 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 13:34:58.197   931  5774 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-05 13:34:58.202  3800  3800 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 13:34:58.210  3800  5787 I SystemUpdateService: active receiver: enabled
,10-05 13:34:58.211  3800  3800 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 13:34:58.212  3800  3800 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 13:34:58.214  5709  5709 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-05 13:34:58.218  5709  5709 D SprintDMHelper: simOperator: 
10-05 13:34:58.218  5709  5709 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:34:58.227  3800  5350 I iu.UploadsManager: num queued entries: 0
,10-05 13:34:58.230  3800  5350 I iu.UploadsManager: num updated entries: 0
,10-05 13:34:58.240  3800  5350 I iu.SyncManager: NEXT; no task
,10-05 13:34:58.244   931  5774 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 17:34:58 GMT], X-Android-Received-Millis=[1475688898244], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475688898220]}
,10-05 13:34:58.245   931  2925 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 13:34:58.245   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-05 13:34:58.245   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 13:34:58.246   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-05 13:34:58.250  3800  5787 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:34:58.258  3800  5787 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-05 13:34:58.258  3800  5787 I SystemUpdateService: now status is 0 (complete)
10-05 13:34:58.258  3800  5787 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:34:58.258  3800  5787 I SystemUpdateService: file has been verified
10-05 13:34:58.258  3800  5787 I SystemUpdateService: OTA package size = 21989297
,10-05 13:34:58.264  3800  5787 I SystemUpdateService: showing system update notification
,10-05 13:34:58.273  3800  3800 D SystemUpdateService: onDestroy
,10-05 13:34:58.324  4958  5792 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 13:34:58.366   931   942 D WifiService: setWifiEnabled: false pid=5574, uid=10077
,10-05 13:34:58.366   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:34:58.369   931  2911 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 13:34:58.369   931  2911 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-05 13:34:58.369   931  2911 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:34:58.369   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:34:58.387   931  5776 D DhcpClient: Clearing IP address
10-05 13:34:58.388   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:34:58.390   507   923 D CommandListener: Setting iface cfg
10-05 13:34:58.392   931  5777 D DhcpClient: Receive thread stopped
,10-05 13:34:58.396  3521  5798 V NativeCrypto: Read error: ssl=0x7f64730e00: I/O error during system call, Connection timed out
10-05 13:34:58.397  3521  5798 V NativeCrypto: SSL shutdown failed: ssl=0x7f64730e00: I/O error during system call, Broken pipe
,10-05 13:34:58.406   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-05 13:34:58.407   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-05 13:34:58.411   540   540 E Parcel  : Reading a NULL string not supported here.
,10-05 13:34:58.414   931   931 D RttService: SCAN_AVAILABLE : 1
10-05 13:34:58.415   931  3018 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-05 13:34:58.416   931  2911 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-05 13:34:58.417   931  2925 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-05 13:34:58.419  3676  3841 W QCNEJ   : |CORE| network lost: 101
10-05 13:34:58.419  3676  3841 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-05 13:34:58.422   931  2911 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 13:34:58.441   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:34:58.462   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:34:58.462   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:34:58.462   931  2925 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-05 13:34:58.462   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:34:58.464   931   948 D Tethering: MasterInitialState.processMessage what=3
10-05 13:34:58.466  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:58.467  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:58.467  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.467  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:58.468   931  2911 D DhcpClient: doQuit
10-05 13:34:58.468   931  2911 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-05 13:34:58.468   931  5776 D DhcpClient: onQuitting
10-05 13:34:58.468  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:58.468  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:58.468  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.468  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:58.468  5769  5769 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 13:34:58.470  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:58.470  5574  5574 V io.jxcore.node.C,onnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:58.470  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:58.470  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.471  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:34:58.471  3907  3907 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-05 13:34:58.472  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:58.472  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:58.472  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.473  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:34:58.473  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:34:58.474  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:34:58.474  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:34:58.474  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:58.475  3800  3800 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 13:34:58.476  4984  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-05 13:34:58.477  4984  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:34:58.477  4984  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,10-05 13:34:58.477  4984  5007 E SarControlService: no key has been found,reset the power
10-05 13:34:58.477  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:34:58.477  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:34:58.477  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:34:58.478  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:34:58.478  5009  5009 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 13:34:58.479  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:34:58.479  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-05 13:34:58.479  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:34:58.479  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:34:58.479  5009  5009 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:34:58.482  3800  3800 D SystemUpdateService: onCreate
10-05 13:34:58.484  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000ee03000000000000ffffffff]
10-05 13:34:58.484  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:34:58.484  5009  5023 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,10-05 13:34:58.484  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:34:58.485  4984  4995 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 13:34:58.487  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000ef03000000000000ffffffff]
10-05 13:34:58.487  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:34:58.487  5009  5023 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-05 13:34:58.488  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:34:58.488  5769  5769 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-05 13:34:58.488  4984  4994 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 13:34:58.488  3800  3800 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 13:34:58.492  3800  5807 I SystemUpdateService: active receiver: enabled
10-05 13:34:58.492  5769  5769 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-05 13:34:58.497  3800  3800 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 13:34:58.502  3800  5350 I iu.UploadsManager: num queued entries: 0
,10-05 13:34:58.503  3800  5350 I iu.UploadsManager: num updated entries: 0
,10-05 13:34:58.504  3800  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:34:58.505  3800  3800 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-05 13:34:58.507  3800  3800 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-05 13:34:58.509  5709  5709 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:34:58.514  5709  5709 D SprintDMHelper: simOperator: 
10-05 13:34:58.514  5709  5709 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:34:58.521   507   923 E Netd    : netlink response contains error (No such file or directory)
,10-05 13:34:58.521  3800  5350 I iu.SyncManager: NEXT; no task
10-05 13:34:58.521  3800  5807 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-05 13:34:58.521  3800  5807 I SystemUpdateService: now status is 0 (complete)
10-05 13:34:58.521  3800  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:34:58.521  3800  5807 I SystemUpdateService: file has been verified
10-05 13:34:58.522   931  2925 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-05 13:34:58.523  3800  5807 I SystemUpdateService: OTA package size = 21989297
,10-05 13:34:58.525  4958  5811 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 13:34:58.537  5769  5769 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 13:34:58.544  3800  5807 I SystemUpdateService: showing system update notification
,10-05 13:34:58.547  5769  5769 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 13:34:58.554  3800  3800 D SystemUpdateService: onDestroy
,10-05 13:34:58.649   931  2911 D wifi    : In wifi stop Hal
10-05 13:34:58.649   931  2911 D wifi    : halHandle = 0x7f63822400, mVM = 0x7f7fe4d140, mCls = 0x201962
10-05 13:34:58.649   931  5768 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 13:34:58.649   931  5768 D WifiHAL : Got a signal to exit!!!
10-05 13:34:58.649   931  5768 I WifiHAL : Exit wifi_event_loop
,10-05 13:34:58.649   931  2911 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-05 13:34:58.649   931  2911 E WifiHAL : Event processing terminated
,10-05 13:34:58.650   931  2911 D wifi    : In wifi cleaned up handler
10-05 13:34:58.650   931  2911 I WifiHAL : Internal cleanup completed
10-05 13:34:58.650  4958  4958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:34:58.651  4048  4167 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:34:58.653  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:34:58.654  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:58.655  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:34:58.675   931  5768 D wifi    : set interface wlan0 flags (DOWN)
10-05 13:34:58.675   931  2911 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 13:34:58.883   931   948 D Tethering: InitialState.processMessage what=4
,10-05 13:34:58.889   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 13:34:59.160   931  2925 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-05 13:35:00.907   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:01.908   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:02.909   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:03.403   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b6bbb0:true
,10-05 13:35:03.404  5694  5694 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 13:35:03.409  5694  5694 I bt_bluedroid: init
10-05 13:35:03.409  5694  5813 I BluetoothAdapterState: Entering OffState
,10-05 13:35:03.412  5694  5814 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 13:35:03.412  5694  5814 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 13:35:03.412  5694  5814 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 13:35:03.413  5694  5814 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-05 13:35:03.413  5694  5694 I bt_bluedroid: get_profile_interface socket
,10-05 13:35:03.417  5694  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 13:35:03.417  5694  5694 I bt_bluedroid: get_profile_interface sdp
10-05 13:35:03.419  5694  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:35:03.425  5694  5705 I bt_bluedroid: config_hci_snoop_log
,10-05 13:35:03.426   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 13:35:03.432  5694  5813 D BluetoothAdapterState: Current state: OFF, message: 0
,10-05 13:35:03.432  5694  5813 D BluetoothAdapterProperties: Setting state to 14
10-05 13:35:03.432  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 13:35:03.434  5694  5813 D BluetoothBondStateMachine: make
,10-05 13:35:03.437  5694  5818 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 13:35:03.440  5694  5813 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:35:03.441  5694  5694 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 13:35:03.444  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:03.445  5694  5694 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 13:35:03.446  5694  5694 D BtGatt.GattService: Received start request. Starting profile...
10-05 13:35:03.446  5694  5694 D BtGatt.GattService: start()
10-05 13:35:03.446  5694  5694 I bt_bluedroid: get_profile_interface gatt
,10-05 13:35:03.447  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
10-05 13:35:03.448  5694  5694 D BtGatt.AdvertiseManager: advertise manager created
,10-05 13:35:03.454  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:35:03.455  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:03.455  5694  5694 V BluetoothAdapterState: isBleTurningOn()=true
10-05 13:35:03.455  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:03.455  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-05 13:35:03.457  5694  5813 I bt_bluedroid: bt_bluedroid
10-05 13:35:03.457  5694  5814 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-05 13:35:03.457  5694  5814 I bt_hci  : start_up
,10-05 13:35:03.464  5694  5814 I bt_vendor: alloc value 0xf3e38871
,10-05 13:35:03.464  5694  5814 I bt_vendor: init
10-05 13:35:03.464  5694  5814 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 13:35:03.464  5694  5814 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 13:35:03.577  5694  5814 D bt_hci  : start_up starting async portion
,10-05 13:35:03.577  5694  5821 I bt_hci  : event_finish_startup
10-05 13:35:03.577  5694  5821 I bt_hci_h4: hal_open
10-05 13:35:03.578  5694  5821 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 13:35:03.576  5822  5822 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:35:03.581  5694  5821 I bt_userial_vendor: device fd = 54 open
,10-05 13:35:03.595  5694  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 13:35:03.600  5694  5821 D bt_hwcfg: Chipset BCM4358A3
,10-05 13:35:03.600  5694  5821 D bt_hwcfg: Target name = [BCM4358A3]
10-05 13:35:03.600  5694  5821 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 13:35:03.910   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:03.982  5694  5821 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 13:35:03.983  5694  5821 D bt_hwcfg: Settlement delay -- 100 ms
,10-05 13:35:03.983  5694  5821 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 13:35:04.117  5694  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 13:35:04.117  5694  5821 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-05 13:35:04.119  5694  5821 I bt_hwcfg: vendor lib fwcfg completed
10-05 13:35:04.119  5694  5821 I bt_vendor: firmware callback
10-05 13:35:04.119  5694  5821 I bt_hci  : firmware_config_callback
,10-05 13:35:04.129  5694  5824 I bt_btu  : btu_task pending for preload complete event
,10-05 13:35:04.129  5694  5824 I bt_btu_task: Bluetooth chip preload is complete
,10-05 13:35:04.129  5694  5824 I bt_btu  : btu_task received preload complete event
,10-05 13:35:04.135  5694  5824 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 13:35:04.135  5694  5824 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 13:35:04.135  5694  5824 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-05 13:35:04.135  5694  5824 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-05 13:35:04.135  5694  5824 I         : BTE_InitTraceLevels -- TRC_AVRC
10-05 13:35:04.135  5694  5824 I         : BTE_InitTraceLevels -- TRC_A2D
10-05 13:35:04.136  5694  5824 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-05 13:35:04.136  5694  5824 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 13:35:04.136  5694  5824 I         : BTE_InitTraceLevels -- TRC_GAP
,10-05 13:35:04.136  5694  5824 I         : BTE_InitTraceLevels -- TRC_PAN
,10-05 13:35:04.136  5694  5824 I         : BTE_InitTraceLevels -- TRC_SDP
,10-05 13:35:04.136  5694  5824 I         : BTE_InitTraceLevels -- TRC_GATT
10-05 13:35:04.137  5694  5824 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 13:35:04.137  5694  5824 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-05 13:35:04.137  5694  5824 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 13:35:04.223  5694  5824 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3db6549
,10-05 13:35:04.224  5694  5824 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3db6549 
,10-05 13:35:04.238  5694  5817 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 13:35:04.240  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-05 13:35:04.241  5694  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 13:35:04.244  5694  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:35:04.247  5694  5817 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:35:04.247  5694  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-05 13:35:04.248  5694  5817 D bt_hci  : do_postload posting postload work item
10-05 13:35:04.248  5694  5821 I bt_hci  : event_postload
10-05 13:35:04.248  5694  5821 I bt_vendor: sco_config_cb
10-05 13:35:04.248  5694  5821 I bt_hci  : sco_config_callback postload finished.
10-05 13:35:04.253  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:04.256  5694  5817 D bt_bte_conf: Device ID record 1 : primary
10-05 13:35:04.256  5694  5817 D bt_bte_conf:   vendorId            = 000f
,10-05 13:35:04.256  5694  5817 D bt_bte_conf:   vendorIdSource      = 0001
10-05 13:35:04.256  5694  5817 D bt_bte_conf:   product             = 1200
,10-05 13:35:04.256  5694  5817 D bt_bte_conf:   version             = 1436
10-05 13:35:04.256  5694  5817 D bt_bte_conf:   clientExecutableURL = 
,10-05 13:35:04.256  5694  5817 D bt_bte_conf:   serviceDescription  = 
10-05 13:35:04.257  5694  5817 D bt_bte_conf:   documentationURL    = 
10-05 13:35:04.257  5694  5817 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 13:35:04.257  5694  5814 D bt_stack_manager: event_start_up_stack finished
10-05 13:35:04.258  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 13:35:04.258  5694  5821 I bt_vendor: low_power_mode_cb
,10-05 13:35:04.258  5694  5813 D BluetoothAdapterProperties: Setting state to 15
10-05 13:35:04.258  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 13:35:04.259  5694  5813 I BluetoothAdapterState: Entering BleOnState
10-05 13:35:04.260  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:04.263  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:04.265  5694  5813 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-05 13:35:04.265  5694  5813 D BluetoothAdapterProperties: Setting state to 11
10-05 13:35:04.265  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 13:35:04.273  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:04.274  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:04.277  5694  5694 D HeadsetService: Received start request. Starting profile...
10-05 13:35:04.277  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:04.279  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:04.280  5694  5694 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 13:35:04.280  5694  5694 D HeadsetStateMachine: make
10-05 13:35:04.284  5694  5813 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:35:04.290  5694  5694 D HeadsetStateMachine: max_hf_connections = 1
10-05 13:35:04.290  5694  5694 I bt_bluedroid: get_profile_interface handsfree
,10-05 13:35:04.291  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-05 13:35:04.291  5694  5817 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,10-05 13:35:04.294  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:04.295  5694  5694 D A2dpService: Received start request. Starting profile...
,10-05 13:35:04.296  5694  5694 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-05 13:35:04.296  5694  5694 I bt_bluedroid: get_profile_interface avrcp
,10-05 13:35:04.303  5694  5694 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-05 13:35:04.303  5694  5694 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 13:35:04.303  5694  5694 D A2dpStateMachine: make
,10-05 13:35:04.305  5694  5694 I bt_bluedroid: get_profile_interface a2dp
,10-05 13:35:04.305  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 13:35:04.307  5694  5832 D A2dpStateMachine: Enter Disconnected: -2
,10-05 13:35:04.307  5694  5694 I BluetoothHidServiceJni: classInitNative: succeeds
10-05 13:35:04.308  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
10-05 13:35:04.309  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:35:04.309  5694  5694 D HidService: Received start request. Starting profile...
10-05 13:35:04.310  5694  5694 I bt_bluedroid: get_profile_interface hidhost
10-05 13:35:04.310  5694  5694 D HidService: setHidService(): set to: null
10-05 13:35:04.310  5694  5817 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d9756d
10-05 13:35:04.310  5694  5694 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 13:35:04.311  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-05 13:35:04.311  5627  5627 D BluetoothInputDevice: Proxy object connected
10-05 13:35:04.311  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
10-05 13:35:04.312  5694  5694 D HealthService: Received start request. Starting profile...
10-05 13:35:04.312  5627  5627 D HidProfile: Bluetooth service connected
10-05 13:35:04.313  5694  5694 I bt_bluedroid: get_profile_interface health
10-05 13:35:04.314  5694  5694 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-05 13:35:04.315  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:04.316  5694  5694 D PanService: Received start request. Starting profile...
,10-05 13:35:04.316  5694  5694 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 13:35:04.316  5694  5694 I bt_bluedroid: get_profile_interface pan
10-05 13:35:04.317  5694  5817 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-05 13:35:04.319  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
10-05 13:35:04.319  5627  5627 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 13:35:04.319  5627  5627 D PanProfile: Bluetooth service connected
,10-05 13:35:04.321  5694  5694 D BluetoothMapService: Received start request. Starting profile...
10-05 13:35:04.321  5627  5627 D BluetoothMap: Proxy object connected
10-05 13:35:04.321  5694  5694 D BluetoothMapService: start()
,10-05 13:35:04.322  5627  5627 D MapProfile: Bluetooth service connected
10-05 13:35:04.322  5627  5627 D BluetoothMap: getConnectedDevices()
10-05 13:35:04.323  5627  5627 D BluetoothMap: Bluetooth is Not enabled
10-05 13:35:04.324  5694  5694 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-05 13:35:04.325  5694  5694 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-05 13:35:04.325  5694  5694 D BluetoothMapAppObserver: createReceiver()
10-05 13:35:04.326  5694  5694 D BluetoothMapAppObserver: initObservers()
10-05 13:35:04.326  5694  5694 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-05 13:35:04.332  5694  5694 V SapService: SapBinder()
10-05 13:35:04.332  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:04.332  5694  5694 D SapService: Received start request. Starting profile...
,10-05 13:35:04.332  5694  5694 V SapService: start()
,10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:35:04.336  5694  5830 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:04.336  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:04.337  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.338  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:04.338  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:04.338  5694  5694 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:04.338  5694  5694 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:04.338  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:04.338  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:35:04.340  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-05 13:35:04.340  5694  5813 D BluetoothAdapterProperties: ScanMode =  20
10-05 13:35:04.340  5694  5813 D BluetoothAdapterProperties: State =  11
10-05 13:35:04.340  5694  5813 D BluetoothAdapterProperties: Setting state to 12
10-05 13:35:04.340  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 13:35:04.341  5694  5813 I BluetoothAdapterState: Entering OnState
10-05 13:35:04.341  3066  5573 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:35:04.343  3726  3748 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:04.343  5694  5817 D BluetoothAdapterProperties: Scan Mode:21
,10-05 13:35:04.343  5627  5646 D BluetoothPan: onBluetoothStateChange on: true
,10-05 13:35:04.343  5694  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 13:35:04.344  3066  3078 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 13:35:04.344  5574  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 13:35:04.345   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:35:04.345  3066  3066 D BluetoothInputDevice: Proxy object connected
10-05 13:35:04.345  3066  3066 D HidProfile: Bluetooth service connected
10-05 13:35:04.346  3066  3077 D BluetoothPan: onBluetoothStateChange on: true
10-05 13:35:04.347   931   931 D BluetoothA2dp: Proxy object connected
10-05 13:35:04.348   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:04.348  5627  5643 D BluetoothMap: onBluetoothStateChange: up=true
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:04.348  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:35:04.348  5627  5639 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:35:04.349  3066  3921 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:35:04.350  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:35:04.350  3066  3066 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 13:35:04.350  3066  3066 D PanProfile: Bluetooth service connected
10-05 13:35:04.351  5694  5694 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 13:35:04.351   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:04.351  3066  3066 D BluetoothA2dp: Proxy object connected
10-05 13:35:04.351  3066  3318 D BluetoothMap: onBluetoothStateChange: up=true
10-05 13:35:04.351  5694  5694 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 13:35:04.353  3066  3066 D BluetoothMap: Proxy object connected
10-05 13:35:04.353  3066  3077 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:04.353  3066  3066 D MapProfile: Bluetooth service connected
10-05 13:35:04.353  3066  3066 D BluetoothMap: getConnectedDevices()
10-05 13:35:04.353  5694  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:35:04.353   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-05 13:35:04.354  5627  5646 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:04.354  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:35:04.357  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:35:04.357   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 13:35:04.358  5694  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:35:04.360  5627  5627 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-05 13:35:04.360  5694  5694 D ObexServerSockets: Succeed to create listening sockets 
10-05 13:35:04.360  5694  5694 D ObexServerSockets0: startAccept()
10-05 13:35:04.360  5694  5694 D ObexServerSockets0: prepareForNewConnect()
10-05 13:35:04.363  5694  5694 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 13:35:04.363  5694  5694 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 13:35:04.363  5694  5694 D BluetoothMapService: onReceive
10-05 13:35:04.363  5627  5627 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-05 13:35:04.363  5694  5694 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:35:04.363  5694  5694 D BluetoothMapService: STATE_ON
10-05 13:35:04.364  5694  5841 D ObexServerSockets0: Accepting socket connection...
10-05 13:35:04.364  5694  5842 D ObexServerSockets0: Accepting socket connection...
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:04.365  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:35:04.367  5694  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:35:04.367  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:35:04.367  5574  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 13:35:04.369  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:04.370  5694  5843 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 13:35:04.371  5694  5843 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-05 13:35:04.371  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:04.372  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:04.373  5627  5627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 13:35:04.375  5627  5627 D BluetoothA2dp: Proxy object connected
,10-05 13:35:04.379  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:35:04.383  5627  5627 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:35:04.385  5627  5627 D BluetoothPbap: Proxy object connected
10-05 13:35:04.386  5627  5627 D PbapServerProfile: Bluetooth service connected
,10-05 13:35:04.390  3066  3066 D BluetoothPbap: Proxy object connected
,10-05 13:35:04.390  3066  3066 D PbapServerProfile: Bluetooth service connected
10-05 13:35:04.390  5694  5694 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 13:35:04.390  5694  5694 D ObexServerSockets0: prepareForNewConnect()
10-05 13:35:04.394  5694  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:35:04.406  5694  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:35:04.408  5694  5851 I BtOppRfcommListener: Accept thread started.
,10-05 13:35:04.445   931   931 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.445   931   931 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.447   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.448   931   931 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.448  3066  3318 D BluetoothHeadset: Proxy object connected
10-05 13:35:04.448  3066  3066 D HeadsetProfile: Bluetooth service connected
10-05 13:35:04.449  3726  3750 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.451   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.454  3066  3921 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.454  3066  3066 D HeadsetProfile: Bluetooth service connected
10-05 13:35:04.454   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:35:04.467  5627  5646 D BluetoothHeadset: Proxy object connected
10-05 13:35:04.467  5627  5627 D HeadsetProfile: Bluetooth service connected
,10-05 13:35:04.911   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:05.911   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-05 13:35:06.120   931  2925 D ConnectivityService: handlePromptUnvalidated 101
,10-05 13:35:08.388  5694  5813 D BluetoothAdapterState: Current state: ON, message: 23
,10-05 13:35:08.389  5694  5813 D BluetoothAdapterProperties: Setting state to 13
,10-05 13:35:08.389  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-05 13:35:08.390  5694  5813 D BluetoothAdapterProperties: onBluetoothDisable()
10-05 13:35:08.392  5694  5813 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:35:08.397  5694  5694 D BluetoothMapService: onReceive
10-05 13:35:08.397  5694  5694 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:35:08.397  5694  5694 D BluetoothMapService: STATE_TURNING_OFF
10-05 13:35:08.397  5694  5694 D BluetoothMapService: MAP Service closeService in
10-05 13:35:08.398  5694  5694 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 13:35:08.398  5694  5694 D ObexServerSockets0: shutdown(block = true)
10-05 13:35:08.404  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:08.404  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:35:08.405  5627  5627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 13:35:08.405  5694  5817 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:35:08.405  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 13:35:08.405  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:35:08.406  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:35:08.408  5694  5694 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:35:08.408  5694  5694 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:35:08.408  5694  5826 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 13:35:08.408  5694  5842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 13:35:08.409  5694  5841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-05 13:35:08.410  5694  5694 I BtOppRfcommListener: stopping Accept Thread
10-05 13:35:08.411  5694  5851 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 13:35:08.411  5694  5851 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-05 13:35:08.411  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:08.411  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:35:08.412  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:35:08.412  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:35:08.415  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:08.416  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:35:08.416  5627  5627 D DockEventReceiver: finishStartingService: stopping service
10-05 13:35:08.416  5574  5574 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:35:08.416  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:35:08.417  5694  5694 D HeadsetService: Received stop request...Stopping profile...
,10-05 13:35:08.419   931   931 D BluetoothHeadset: Proxy object disconnected
,10-05 13:35:08.420   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:35:08.420   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:35:08.420  3066  3318 D BluetoothHeadset: Proxy object disconnected
,10-05 13:35:08.420  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:08.420  3726  3938 D BluetoothHeadset: Proxy object disconnected
10-05 13:35:08.421  5627  5639 D BluetoothHeadset: Proxy object disconnected
10-05 13:35:08.422  5627  5627 D HeadsetProfile: Bluetooth service disconnected
10-05 13:35:08.422  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:08.422  5694  5694 D A2dpService: Received stop request...Stopping profile...
10-05 13:35:08.424  5694  5832 D A2dpStateMachine: Exit Disconnected: -1
10-05 13:35:08.424  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:08.424   931   931 D BluetoothA2dp: Proxy object disconnected
10-05 13:35:08.426  5694  5694 D HidService: Received stop request...Stopping profile...
10-05 13:35:08.427  5694  5694 D HidService: Stopping Bluetooth HidService
,10-05 13:35:08.427  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:35:08.429  5627  5627 D BluetoothA2dp: Proxy object disconnected
,10-05 13:35:08.429  5627  5627 D BluetoothInputDevice: Proxy object disconnected
10-05 13:35:08.429  5627  5627 D HidProfile: Bluetooth service disconnected
10-05 13:35:08.429  5694  5694 D HealthService: Received stop request...Stopping profile...
10-05 13:35:08.429  3066  3066 D HeadsetProfile: Bluetooth service disconnected
10-05 13:35:08.430  3066  3066 D BluetoothA2dp: Proxy object disconnected
10-05 13:35:08.430  3066  3066 D BluetoothInputDevice: Proxy object disconnected
10-05 13:35:08.430  3066  3066 D HidProfile: Bluetooth service disconnected
10-05 13:35:08.431  5694  5694 D PanService: Received stop request...Stopping profile...
10-05 13:35:08.432  3066  3066 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 13:35:08.432  3066  3066 D PanProfile: Bluetooth service disconnected
10-05 13:35:08.432  5627  5627 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 13:35:08.432  5627  5627 D PanProfile: Bluetooth service disconnected
,10-05 13:35:08.432  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.432  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.433  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.433  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:35:08.434  5694  5694 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 13:35:08.435  5694  5694 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-05 13:35:08.435  5694  5824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:35:08.435  5694  5824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:35:08.435  5694  5824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:35:08.435  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 13:35:08.435  5694  5694 D BluetoothMapService: Received stop request...Stopping profile...
10-05 13:35:08.435  5694  5817 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 13:35:08.435  5694  5694 D BluetoothMapService: stop()
10-05 13:35:08.436  5694  5694 D BluetoothMapAppObserver: deinitObservers()
10-05 13:35:08.436  5694  5694 D BluetoothMapAppObserver: removeReceiver()
10-05 13:35:08.438  5694  5694 D SapService: Received stop request...Stopping profile...
10-05 13:35:08.438  5694  5694 V SapService: stop()
10-05 13:35:08.438  3066  3066 D BluetoothMap: Proxy object disconnected
10-05 13:35:08.438  3066  3066 D MapProfile: Bluetooth service disconnected
,10-05 13:35:08.437  5627  5627 D BluetoothMap: Proxy object disconnected
10-05 13:35:08.439  5627  5627 D MapProfile: Bluetooth service disconnected
10-05 13:35:08.439  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.439  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.439  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.439  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:08.440  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 13:35:08.440  5694  5824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:35:08.440  5694  5824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:35:08.440  5694  5824 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-05 13:35:08.441  5694  5824 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:35:08.441  5694  5824 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:35:08.441  5694  5824 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:35:08.442  3066  3066 D BluetoothPbap: Proxy object disconnected
10-05 13:35:08.442  5627  5627 D BluetoothPbap: Proxy object disconnected
,10-05 13:35:08.442  3066  3066 D PbapServerProfile: Bluetooth service disconnected
,10-05 13:35:08.442  5627  5627 D PbapServerProfile: Bluetooth service disconnected
,10-05 13:35:08.442  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.442  5694  5694 V BluetoothAdapterState: isTurningOn()=false
,10-05 13:35:08.442  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 13:35:08.442  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:08.442  5694  5694 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 13:35:08.443  5694  5694 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 13:35:08.443  5694  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:35:08.443  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.443  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.443  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.443  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:08.443  5694  5694 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 13:35:08.444  5694  5694 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-05 13:35:08.444  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.444  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.444  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.444  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:08.444  5694  5694 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-05 13:35:08.445  5694  5694 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-05 13:35:08.445  5694  5817 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-05 13:35:08.445  5694  5694 D BluetoothMapService: MAP Service closeService in
10-05 13:35:08.445  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:08.446  5694  5694 D BluetoothMapService: cleanup()
,10-05 13:35:08.446  5694  5694 D BluetoothMapService: MAP Service closeService in
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isTurningOff()=true
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.446  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:08.447  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 13:35:08.447  5694  5813 D BluetoothAdapterProperties: Setting state to 15
10-05 13:35:08.447  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,10-05 13:35:08.448  3066  3921 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 13:35:08.448  5694  5813 I BluetoothAdapterState: Entering BleOnState
10-05 13:35:08.449  5627  5643 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:35:08.450  3726  3748 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:35:08.450  5627  5639 D BluetoothPan: onBluetoothStateChange on: false
10-05 13:35:08.451  3066  5573 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 13:35:08.451   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:35:08.451  3066  3078 D BluetoothPan: onBluetoothStateChange on: false
10-05 13:35:08.452  5627  5646 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:35:08.452   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:35:08.452  5627  5643 D BluetoothMap: onBluetoothStateChange: up=false
10-05 13:35:08.453  5627  5639 D BluetoothPbap: onBluetoothStateChange: up=false
,10-05 13:35:08.454  3066  3318 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:35:08.455   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:35:08.457  3066  5573 D BluetoothMap: onBluetoothStateChange: up=false
10-05 13:35:08.457  3066  3078 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:35:08.458   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-05 13:35:08.458  5627  5646 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 13:35:08.458  5694  5813 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 13:35:08.458  5694  5813 D BluetoothAdapterProperties: Setting state to 16
10-05 13:35:08.458  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 13:35:08.459  5694  5813 D BluetoothAdapterProperties: onBleDisable
10-05 13:35:08.459  5694  5813 I BluetoothAdapterState: Entering PendingCommandState
10-05 13:35:08.459  5694  5814 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-05 13:35:08.460  5694  5817 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:35:08.461  5694  5824 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 13:35:08.461  5694  5824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-05 13:35:08.464  5627  5627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 13:35:08.465  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:08.466  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:08.467  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:08.469  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:08.470  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:08.471  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:35:08.472  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:08.476  5627  5627 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:35:08.674  5694  5817 I bt_hci  : shut_down
,10-05 13:35:08.684  5694  5821 D bt_hwcfg: hw_epilog_process
,10-05 13:35:08.685  5694  5821 I bt_vendor: low_power_mode_cb
,10-05 13:35:08.688  5694  5821 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 13:35:08.688  5694  5821 I bt_vendor: epilog_cb
10-05 13:35:08.688  5694  5821 I bt_hci  : epilog_finished_callback
,10-05 13:35:08.693  5694  5817 I bt_hci_h4: hal_close
,10-05 13:35:08.694  5694  5817 I bt_userial_vendor: device fd = 54 close
,10-05 13:35:08.807  5694  5814 D bt_stack_manager: event_shut_down_stack finished.
,10-05 13:35:08.808  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 13:35:08.812  5694  5813 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-05 13:35:08.812  5694  5694 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 13:35:08.815  5694  5694 D BtGatt.GattService: Received stop request...Stopping profile...
,10-05 13:35:08.815  5694  5694 D BtGatt.GattService: stop()
10-05 13:35:08.815  5694  5694 D BtGatt.AdvertiseManager: advertise clients cleared
10-05 13:35:08.818  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:35:08.818  5694  5694 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:08.818  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:08.819  5694  5694 V BluetoothAdapterState: isBleTurningOff()=true
,10-05 13:35:08.819  5694  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-05 13:35:08.819  5694  5813 D BluetoothAdapterProperties: Setting state to 10
,10-05 13:35:08.820  5694  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-05 13:35:08.821  5694  5813 I BluetoothAdapterState: Entering OffState
,10-05 13:35:08.823   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-05 13:35:08.838  5694  5694 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-05 13:35:08.838  5694  5694 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 13:35:08.839  5694  5694 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-05 13:35:08.841  5694  5814 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 13:35:08.848  5694  5694 I art     : System.exit called, status: 0
,10-05 13:35:08.848  5694  5694 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 13:35:08.875   931  3104 I ActivityManager: Process com.android.bluetooth (pid 5694) has died
,10-05 13:35:13.387  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:35:13.388  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:13.393  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:35:13.394  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1257bc removed from the list
,10-05 13:35:13.394  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:13.394  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:13.394  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:13.397  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 13:35:13.397  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8212a9a added. We now have 4 listener(s)
10-05 13:35:13.397  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:13.399  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:13.400  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8212a9a removed from the list
,10-05 13:35:13.400  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:35:13.400  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:13.400  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:13.402  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:13.402  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e363fcb added. We now have 4 listener(s)
10-05 13:35:13.402  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:35:18.413  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,10-05 13:35:18.450   931   948 I ActivityManager: Start proc 5859:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-05 13:35:18.541  5859  5859 D AdapterServiceConfig: Adding HeadsetService
,10-05 13:35:18.541  5859  5859 D AdapterServiceConfig: Adding A2dpService
10-05 13:35:18.541  5859  5859 D AdapterServiceConfig: Adding HidService
,10-05 13:35:18.542  5859  5859 D AdapterServiceConfig: Adding HealthService
,10-05 13:35:18.554  5859  5859 D AdapterServiceConfig: Adding PanService
10-05 13:35:18.554  5859  5859 D AdapterServiceConfig: Adding GattService
10-05 13:35:18.555  5859  5859 D AdapterServiceConfig: Adding BluetoothMapService
10-05 13:35:18.555  5859  5859 D AdapterServiceConfig: Adding SapService
,10-05 13:35:18.571   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ae37e9:true
,10-05 13:35:18.571  5859  5859 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 13:35:18.574  5859  5859 I bt_bluedroid: init
,10-05 13:35:18.575  5859  5871 I BluetoothAdapterState: Entering OffState
,10-05 13:35:18.578  5859  5872 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 13:35:18.578  5859  5872 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 13:35:18.578  5859  5872 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 13:35:18.578  5859  5872 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-05 13:35:18.579  5859  5859 I bt_bluedroid: get_profile_interface socket
,10-05 13:35:18.580  5859  5875 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-05 13:35:18.581  5859  5859 I bt_bluedroid: get_profile_interface sdp
10-05 13:35:18.582  5859  5875 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:35:18.585  5859  5870 I bt_bluedroid: config_hci_snoop_log
,10-05 13:35:18.587   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 13:35:18.591  5859  5871 D BluetoothAdapterState: Current state: OFF, message: 0
,10-05 13:35:18.591  5859  5871 D BluetoothAdapterProperties: Setting state to 14
10-05 13:35:18.591  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 13:35:18.593  5859  5871 D BluetoothBondStateMachine: make
,10-05 13:35:18.595  5859  5876 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 13:35:18.597  5859  5871 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:35:18.599  5859  5859 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 13:35:18.601  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:18.602  5859  5859 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 13:35:18.602  5859  5859 D BtGatt.GattService: Received start request. Starting profile...
10-05 13:35:18.602  5859  5859 D BtGatt.GattService: start()
10-05 13:35:18.602  5859  5859 I bt_bluedroid: get_profile_interface gatt
10-05 13:35:18.603  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:18.603  5859  5859 D BtGatt.AdvertiseManager: advertise manager created
,10-05 13:35:18.608  5859  5859 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:35:18.609  5859  5859 V BluetoothAdapterState: isTurningOn()=false
10-05 13:35:18.609  5859  5859 V BluetoothAdapterState: isBleTurningOn()=true
10-05 13:35:18.609  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:18.609  5859  5871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-05 13:35:18.611  5859  5871 I bt_bluedroid: bt_bluedroid
10-05 13:35:18.611  5859  5872 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-05 13:35:18.611  5859  5872 I bt_hci  : start_up
,10-05 13:35:18.616  5859  5872 I bt_vendor: alloc value 0xf3e99871
,10-05 13:35:18.617  5859  5872 I bt_vendor: init
10-05 13:35:18.617  5859  5872 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 13:35:18.617  5859  5872 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 13:35:18.724  5859  5872 D bt_hci  : start_up starting async portion
,10-05 13:35:18.725  5859  5879 I bt_hci  : event_finish_startup
10-05 13:35:18.726  5859  5879 I bt_hci_h4: hal_open
10-05 13:35:18.726  5859  5879 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 13:35:18.730  5859  5879 I bt_userial_vendor: device fd = 54 open
,10-05 13:35:18.726  5880  5880 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:35:18.746  5859  5879 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 13:35:18.749  5859  5879 D bt_hwcfg: Chipset BCM4358A3
,10-05 13:35:18.750  5859  5879 D bt_hwcfg: Target name = [BCM4358A3]
10-05 13:35:18.750  5859  5879 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 13:35:19.274  5859  5879 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 13:35:19.275  5859  5879 D bt_hwcfg: Settlement delay -- 100 ms
10-05 13:35:19.275  5859  5879 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 13:35:19.410  5859  5879 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-05 13:35:19.410  5859  5879 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-05 13:35:19.413  5859  5879 I bt_hwcfg: vendor lib fwcfg completed
10-05 13:35:19.413  5859  5879 I bt_vendor: firmware callback
,10-05 13:35:19.413  5859  5879 I bt_hci  : firmware_config_callback
,10-05 13:35:19.422  5859  5882 I bt_btu  : btu_task pending for preload complete event
,10-05 13:35:19.423  5859  5882 I bt_btu_task: Bluetooth chip preload is complete
10-05 13:35:19.423  5859  5882 I bt_btu  : btu_task received preload complete event
,10-05 13:35:19.429  5859  5882 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 13:35:19.429  5859  5882 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_AVDT
10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_AVRC
10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_A2D
,10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_BNEP
10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_GAP
10-05 13:35:19.430  5859  5882 I         : BTE_InitTraceLevels -- TRC_PAN
10-05 13:35:19.431  5859  5882 I         : BTE_InitTraceLevels -- TRC_SDP
10-05 13:35:19.431  5859  5882 I         : BTE_InitTraceLevels -- TRC_GATT
,10-05 13:35:19.431  5859  5882 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 13:35:19.431  5859  5882 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-05 13:35:19.431  5859  5882 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 13:35:19.526  5859  5882 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e17549
,10-05 13:35:19.526  5859  5882 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e17549 
,10-05 13:35:19.543  5859  5875 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 13:35:19.545  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:35:19.546  5859  5875 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 13:35:19.549  5859  5875 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:35:19.552  5859  5875 D BluetoothAdapterProperties: Scan Mode:20
,10-05 13:35:19.552  5859  5875 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 13:35:19.553  5859  5875 D bt_hci  : do_postload posting postload work item
,10-05 13:35:19.553  5859  5879 I bt_hci  : event_postload
,10-05 13:35:19.553  5859  5879 I bt_vendor: sco_config_cb
,10-05 13:35:19.553  5859  5879 I bt_hci  : sco_config_callback postload finished.
10-05 13:35:19.557  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:19.557  5859  5875 D bt_bte_conf: Device ID record 1 : primary
10-05 13:35:19.558  5859  5875 D bt_bte_conf:   vendorId            = 000f
10-05 13:35:19.558  5859  5875 D bt_bte_conf:   vendorIdSource      = 0001
10-05 13:35:19.558  5859  5875 D bt_bte_conf:   product             = 1200
,10-05 13:35:19.558  5859  5875 D bt_bte_conf:   version             = 1436
10-05 13:35:19.558  5859  5875 D bt_bte_conf:   clientExecutableURL = 
10-05 13:35:19.558  5859  5875 D bt_bte_conf:   serviceDescription  = 
10-05 13:35:19.558  5859  5875 D bt_bte_conf:   documentationURL    = 
10-05 13:35:19.558  5859  5875 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 13:35:19.558  5859  5872 D bt_stack_manager: event_start_up_stack finished
10-05 13:35:19.559  5859  5871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 13:35:19.560  5859  5871 D BluetoothAdapterProperties: Setting state to 15
10-05 13:35:19.560  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 13:35:19.562  5859  5879 I bt_vendor: low_power_mode_cb
10-05 13:35:19.563  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:19.563  5859  5871 I BluetoothAdapterState: Entering BleOnState
10-05 13:35:19.566  5859  5871 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-05 13:35:19.566  5859  5871 D BluetoothAdapterProperties: Setting state to 11
10-05 13:35:19.566  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 13:35:19.575  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:19.577  5859  5859 D HeadsetService: Received start request. Starting profile...
10-05 13:35:19.581  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:19.581  5859  5859 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 13:35:19.581  5859  5859 D HeadsetStateMachine: make
10-05 13:35:19.583  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:19.595  5859  5871 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:35:19.600  5859  5859 D HeadsetStateMachine: max_hf_connections = 1
,10-05 13:35:19.600  5859  5859 I bt_bluedroid: get_profile_interface handsfree
,10-05 13:35:19.601  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-05 13:35:19.601  5859  5875 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-05 13:35:19.604  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:19.605  5859  5859 D A2dpService: Received start request. Starting profile...
,10-05 13:35:19.606  5859  5859 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-05 13:35:19.606  5859  5859 I bt_bluedroid: get_profile_interface avrcp
,10-05 13:35:19.612  5859  5859 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-05 13:35:19.613  5859  5859 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 13:35:19.613  5859  5859 D A2dpStateMachine: make
10-05 13:35:19.614  5859  5859 I bt_bluedroid: get_profile_interface a2dp
10-05 13:35:19.614  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 13:35:19.617  5859  5891 D A2dpStateMachine: Enter Disconnected: -2
,10-05 13:35:19.618  5859  5859 I BluetoothHidServiceJni: classInitNative: succeeds
,10-05 13:35:19.618  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:19.619  5859  5859 D HidService: Received start request. Starting profile...
,10-05 13:35:19.619  5859  5859 I bt_bluedroid: get_profile_interface hidhost
10-05 13:35:19.619  5859  5859 D HidService: setHidService(): set to: null
10-05 13:35:19.619  5859  5875 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3df856d
10-05 13:35:19.620  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-05 13:35:19.621  5859  5859 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 13:35:19.622  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:19.623  5859  5859 D HealthService: Received start request. Starting profile...
10-05 13:35:19.623  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:35:19.625  5859  5859 I bt_bluedroid: get_profile_interface health
,10-05 13:35:19.626  5859  5859 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-05 13:35:19.627  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
10-05 13:35:19.627  5859  5859 D PanService: Received start request. Starting profile...
10-05 13:35:19.627  5859  5859 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 13:35:19.628  5859  5859 I bt_bluedroid: get_profile_interface pan
10-05 13:35:19.628  5859  5875 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-05 13:35:19.630  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:19.630  5859  5859 D BluetoothMapService: Received start request. Starting profile...
10-05 13:35:19.630  5859  5859 D BluetoothMapService: start()
10-05 13:35:19.633  5859  5859 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-05 13:35:19.633  5859  5859 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-05 13:35:19.634  5859  5859 D BluetoothMapAppObserver: createReceiver()
10-05 13:35:19.635  5859  5859 D BluetoothMapAppObserver: initObservers()
10-05 13:35:19.635  5859  5859 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-05 13:35:19.641  5859  5859 V SapService: SapBinder()
10-05 13:35:19.641  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:19.642  5859  5859 D SapService: Received start request. Starting profile...
10-05 13:35:19.642  5859  5859 V SapService: start()
,10-05 13:35:19.645  5859  5859 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:35:19.645  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.645  5859  5887 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-05 13:35:19.645  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.646  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:35:19.647  5859  5859 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:19.647  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.647  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.647  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:35:19.647  5859  5859 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.648  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:19.649  5859  5859 V BluetoothAdapterState: isTurningOff()=false
10-05 13:35:19.649  5859  5859 V BluetoothAdapterState: isTurningOn()=true
10-05 13:35:19.649  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:35:19.649  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:35:19.649  5859  5871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-05 13:35:19.649  5859  5871 D BluetoothAdapterProperties: ScanMode =  20
10-05 13:35:19.649  5859  5871 D BluetoothAdapterProperties: State =  11
10-05 13:35:19.650  5859  5871 D BluetoothAdapterProperties: Setting state to 12
10-05 13:35:19.650  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 13:35:19.651  3066  3077 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:35:19.652  5859  5871 I BluetoothAdapterState: Entering OnState
10-05 13:35:19.654  5627  5639 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:35:19.654  5859  5875 D BluetoothAdapterProperties: Scan Mode:21
10-05 13:35:19.654  5859  5875 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 13:35:19.654  5574  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-05 13:35:19.655  3726  3750 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:19.656  5627  5643 D BluetoothPan: onBluetoothStateChange on: true
10-05 13:35:19.658  3066  3921 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:19.658  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:35:19.659   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:35:19.660  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:35:19.660  5859  5859 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 13:35:19.660   931   931 D BluetoothA2dp: Proxy object connected
,10-05 13:35:19.660  3066  3318 D BluetoothPan: onBluetoothStateChange on: true
10-05 13:35:19.660  5859  5859 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 13:35:19.660  5627  5627 D BluetoothA2dp: Proxy object connected
10-05 13:35:19.661  5859  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:35:19.662  5627  5646 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:19.662  3066  3066 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 13:35:19.662  3066  3066 D PanProfile: Bluetooth service connected
10-05 13:35:19.663   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:19.663  5627  5643 D BluetoothMap: onBluetoothStateChange: up=true
,10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:19.665  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:35:19.666  5859  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:35:19.667  5627  5639 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:35:19.667  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:35:19.669  3066  3078 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:35:19.669  5859  5859 D ObexServerSockets: Succeed to create listening sockets 
10-05 13:35:19.669  5859  5859 D ObexServerSockets0: startAccept()
10-05 13:35:19.669  5859  5859 D ObexServerSockets0: prepareForNewConnect()
10-05 13:35:19.671  5859  5859 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 13:35:19.671  5859  5859 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 13:35:19.671  5627  5627 D BluetoothPan: BluetoothPAN Proxy object connected
,10-05 13:35:19.671  5627  5627 D PanProfile: Bluetooth service connected
10-05 13:35:19.672  5859  5897 D ObexServerSockets0: Accepting socket connection...
10-05 13:35:19.672  3066  3066 D BluetoothA2dp: Proxy object connected
10-05 13:35:19.672  5859  5898 D ObexServerSockets0: Accepting socket connection...
10-05 13:35:19.673  5627  5627 D BluetoothMap: Proxy object connected
10-05 13:35:19.673  5627  5627 D MapProfile: Bluetooth service connected
10-05 13:35:19.673  5627  5627 D BluetoothMap: getConnectedDevices()
10-05 13:35:19.673   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:35:19.674  3066  3318 D BluetoothMap: onBluetoothStateChange: up=true
,10-05 13:35:19.674  3066  3066 D BluetoothInputDevice: Proxy object connected
10-05 13:35:19.675  3066  3066 D HidProfile: Bluetooth service connected
10-05 13:35:19.676  3066  3077 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-05 13:35:19.676  3066  3066 D BluetoothMap: Proxy object connected
10-05 13:35:19.676  3066  3066 D MapProfile: Bluetooth service connected
10-05 13:35:19.676  3066  3066 D BluetoothMap: getConnectedDevices()
10-05 13:35:19.676   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-05 13:35:19.677  5627  5643 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-05 13:35:19.680  5627  5627 D BluetoothInputDevice: Proxy object connected
,10-05 13:35:19.680  5627  5627 D HidProfile: Bluetooth service connected
10-05 13:35:19.680   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 13:35:19.681  5859  5859 D BluetoothMapService: onReceive
10-05 13:35:19.681  5859  5859 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:35:19.681  5859  5859 D BluetoothMapService: STATE_ON
10-05 13:35:19.681  5574  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 13:35:19.683  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:19.685  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:19.685  5859  5900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:35:19.686  5859  5900 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 13:35:19.686  5859  5900 D BluetoothSdpJni: SDP Create record success - handle: 1
10-05 13:35:19.688  5627  5627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 13:35:19.694  3521  3521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:35:19.695  5627  5627 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:35:19.701  5627  5627 D BluetoothPbap: Proxy object connected
,10-05 13:35:19.701  5627  5627 D PbapServerProfile: Bluetooth service connected
,10-05 13:35:19.707  5859  5859 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 13:35:19.707  5859  5859 D ObexServerSockets0: prepareForNewConnect()
10-05 13:35:19.708  5859  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:35:19.712  3066  3066 D BluetoothPbap: Proxy object connected
10-05 13:35:19.712  3066  3066 D PbapServerProfile: Bluetooth service connected
,10-05 13:35:19.727  5859  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:35:19.729  5859  5908 I BtOppRfcommListener: Accept thread started.
,10-05 13:35:19.757   931   931 D BluetoothHeadset: Proxy object connected
,10-05 13:35:19.757   931   931 D BluetoothHeadset: Proxy object connected
10-05 13:35:19.757   931   931 D BluetoothHeadset: Proxy object connected
10-05 13:35:19.757  3066  3077 D BluetoothHeadset: Proxy object connected
10-05 13:35:19.758  3066  3066 D HeadsetProfile: Bluetooth service connected
10-05 13:35:19.758  3726  3938 D BluetoothHeadset: Proxy object connected
,10-05 13:35:19.758  5627  5639 D BluetoothHeadset: Proxy object connected
10-05 13:35:19.759  5627  5627 D HeadsetProfile: Bluetooth service connected
,10-05 13:35:19.763  5627  5643 D BluetoothHeadset: Proxy object connected
10-05 13:35:19.763   931   948 D BluetoothHeadset: Proxy object connected
10-05 13:35:19.764  5627  5627 D HeadsetProfile: Bluetooth service connected
,10-05 13:35:19.774   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:35:19.776  3066  3921 D BluetoothHeadset: Proxy object connected
,10-05 13:35:19.776  3066  3066 D HeadsetProfile: Bluetooth service connected
10-05 13:35:19.776   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:23.429  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:35:23.434  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:35:23.435  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:23.435  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e363fcb removed from the list
10-05 13:35:23.436  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:23.436  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:23.436  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:23.438  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:23.438  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68b33a8 added. We now have 4 listener(s)
10-05 13:35:23.438  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:23.442   931   942 D WifiService: setWifiEnabled: false pid=5574, uid=10077
10-05 13:35:23.442   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:35:25.913   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:26.914   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:27.916   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:28.452  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:28.453   931  3749 D WifiService: setWifiEnabled: true pid=5574, uid=10077
10-05 13:35:28.454   931  3749 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:35:28.462   507   923 D SoftapController: Softap fwReload - Ok
,10-05 13:35:28.469   507   923 D CommandListener: Setting iface cfg
,10-05 13:35:28.469   507   923 D CommandListener: Trying to bring down wlan0
10-05 13:35:28.471   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:35:28.477   931  2911 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 13:35:28.917   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:29.150   931  2911 D wifi    : set interface wlan0 flags (UP)
,10-05 13:35:29.150   931  2911 I WifiHAL : Initializing wifi
,10-05 13:35:29.150   931  2911 I WifiHAL : Creating socket
10-05 13:35:29.156   931  2911 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-05 13:35:29.156   931  2911 D wifi    : Did set static halHandle = 0x7f63822400
,10-05 13:35:29.157   931  2911 D wifi    : halHandle = 0x7f63822400, mVM = 0x7f7fe4d140, mCls = 0x10145a
10-05 13:35:29.157   931  2911 D wifi    : array field set
10-05 13:35:29.157   931  2911 I WifiNative-HAL: interface[0] = wlan0
10-05 13:35:29.159   931  5913 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547130319872
10-05 13:35:29.160   931  5913 D wifi    : waitForHalEvents called, vm = 0x7f7fe4d140, obj = 0x10145a, env = 0x7f6143e880
10-05 13:35:29.163   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-05 13:35:29.225  5914  5914 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 13:35:29.246  5914  5914 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:35:29.261   931  2911 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 13:35:29.268  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:29.272  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:29.292  5914  5914 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-05 13:35:29.293  5914  5914 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 13:35:29.307   931  2911 D WifiConfigStore: Loading config and enabling all networks 
,10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:29.312  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:35:29.314  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:35:29.319  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:35:29.319   931  2911 D WifiConfigStore: loaded 0 passpoint configs
10-05 13:35:29.320   931  2911 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-05 13:35:29.320   931  2911 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-05 13:35:29.321  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:35:29.321   931  2911 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-05 13:35:29.322   931  2911 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-05 13:35:29.322   931  2911 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 13:35:29.322   931  2911 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 13:35:29.322   931  2911 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 13:35:29.326   931  2911 D WifiNative-HAL: Setting external_sim to 1
10-05 13:35:29.326  4958  4958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:35:29.326   931  2911 D wifi    : setting dfs flag to true, 0x7f646d1a60
,10-05 13:35:29.327   931  2911 D WifiStateMachine: Setting OUI to DA-A1-19
10-05 13:35:29.327   931  2911 D wifi    : setting scan oui 0x7f646d1a60
10-05 13:35:29.327   931  2911 D WifiHAL : Sending mac address OUI
,10-05 13:35:29.332   931  2911 E native  : do suspend false
,10-05 13:35:29.339   931  2911 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-05 13:35:29.339   931   931 D RttService: SCAN_AVAILABLE : 3
10-05 13:35:29.340   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-05 13:35:29.340   931  3018 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 13:35:29.341   507   923 D CommandListener: Setting iface cfg
,10-05 13:35:29.345   931  2896 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-05 13:35:29.345   931  2896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 13:35:29.355   931  2896 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 13:35:29.356   931  2896 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 13:35:29.363   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303073 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-05 13:35:29.919   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:35:30.921   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-05 13:35:32.518  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:35:32.524  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:35:32.529  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:35:32.533  5914  5914 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:35:32.600   931  2911 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 13:35:32.601   931  2911 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-05 13:35:32.601   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:35:32.614   931  2911 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 13:35:32.647   931  2911 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 13:35:32.649  5914  5914 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 13:35:33.071  5914  5914 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 13:35:33.107  5914  5914 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 13:35:33.108  5914  5914 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 13:35:33.118   931  2911 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
10-05 13:35:33.118   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-05 13:35:33.118   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 13:35:33.134   931  2911 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:35:33.146   507   923 D CommandListener: Setting iface cfg
,10-05 13:35:33.152   931  2911 D WifiStateMachine: Start Dhcp Watchdog 3
,10-05 13:35:33.158   931  5919 D DhcpClient: Receive thread started
,10-05 13:35:33.163   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:33.163   931  2911 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-05 13:35:33.163   931  2925 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-05 13:35:33.244   931  2911 E native  : do suspend false
,10-05 13:35:33.255   931  5918 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 13:35:33.271   931  5919 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-05 13:35:33.271   931  5918 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
10-05 13:35:33.272   931  5918 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 13:35:33.287   931  5919 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 13:35:33.288   931  5918 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 13:35:33.290   507   923 D CommandListener: Setting iface cfg
,10-05 13:35:33.295   931  2911 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 13:35:33.301   931  5918 D DhcpClient: Scheduling renewal in 86399s
,10-05 13:35:33.314   931  2911 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-05 13:35:33.316   931  2911 D WifiConfigStore: No blacklist allowed without epno enabled
10-05 13:35:33.318   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-05 13:35:33.320   931  2925 D ConnectivityService: Adding iface wlan0 to network 102
,10-05 13:35:33.330   931  2911 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 13:35:33.371   931  2925 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 13:35:33.371   931  2925 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-05 13:35:33.374   931  2925 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-05 13:35:33.380   931  2925 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-05 13:35:33.382   931  2925 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-05 13:35:33.390   931  2925 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:33.395   931  2925 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-05 13:35:33.395   931  2925 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-05 13:35:33.395   931  2925 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-05 13:35:33.395   931  2925 D ConnectivityService:    accepting network in place of null
10-05 13:35:33.395   931  2911 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 13:35:33.395   931  2911 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:35:33.396   931  2925 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-05 13:35:33.397   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307107, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_DELAY}
,10-05 13:35:33.420   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:35:33.443   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:35:33.446   931  2925 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-05 13:35:33.446   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:35:33.446  3676  3841 W QCNEJ   : |CORE| network available: 102
,10-05 13:35:33.447  3676  3841 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 13:35:33.447   931  2925 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:33.448   931   948 D Tethering: MasterInitialState.processMessage what=3
10-05 13:35:33.451  3676  3841 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-05 13:35:33.452  3676  3841 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:33.456  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:35:33.458  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:35:33.464  4984  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-05 13:35:33.464  4984  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:35:33.464  4984  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:33.465  5574  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:35:33.465  4984  5007 E SarControlService: no key has been found,reset the power
10-05 13:35:33.465  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:35:33.465  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:35:33.465  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:35:33.465  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:35:33.465  5009  5009 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 13:35:33.466  4984  5021 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:35:33.466  4984  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 13:35:33.466  4984  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:35:33.467  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:35:33.467  5009  5009 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:35:33.467  5574  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:33.468   931  5916 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:33.468  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:35:33.468  3907  3907 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-05 13:35:33.470  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:33.470  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:33.471  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68b33a8 removed from the list
10-05 13:35:33.471  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:33.471  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:33.471  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:33.471  3800  3800 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 13:35:33.474  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000f003000000000000ffffffff]
10-05 13:35:33.474  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:35:33.474  5009  5023 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-05 13:35:33.474  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-05 13:35:33.475  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-05 13:35:33.475  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:35:33.475  4984  4995 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 13:35:33.476  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b27881b Bundle[{}]
,10-05 13:35:33.476  3800  3800 D SystemUpdateService: onCreate
10-05 13:35:33.477  5574  5620 I io.jxcore.node.LifeCycleMonitor: start: OK
10-05 13:35:33.477  5574  5620 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-05 13:35:33.478  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-05 13:35:33.478  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-05 13:35:33.479  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-05 13:35:33.480  5574  5620 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-05 13:35:33.482  3800  3800 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-05 13:35:33.483  5574  5620 I System.out: Running OutgoingSocketThread
,10-05 13:35:33.484  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71b49ee HexData = [00000000f103000000000000ffffffff]
10-05 13:35:33.484  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:35:33.484  5009  5023 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-05 13:35:33.485  5574  5930 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
10-05 13:35:33.485  5574  5930 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
10-05 13:35:33.486  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:35:33.486  4984  4994 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 13:35:33.491  3800  3800 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 13:35:33.496  3800  5350 I iu.UploadsManager: num queued entries: 0
,10-05 13:35:33.496  3800  5350 I iu.UploadsManager: num updated entries: 0
,10-05 13:35:33.505  3800  3800 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 13:35:33.507  3800  3800 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-05 13:35:33.508  5709  5709 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:35:33.512  5709  5709 D SprintDMHelper: simOperator: 
,10-05 13:35:33.513  5709  5709 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-05 13:35:33.516  3800  5929 I SystemUpdateService: active receiver: enabled
,10-05 13:35:33.517  3800  5350 I iu.SyncManager: NEXT; no task
,10-05 13:35:33.528   931  5916 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 17:35:33 GMT], X-Android-Received-Millis=[1475688933527], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475688933506]}
,10-05 13:35:33.528   931  2925 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-05 13:35:33.528   931  2925 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-05 13:35:33.528   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-05 13:35:33.529   931  2925 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-05 13:35:33.535  3800  5929 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:35:33.547  3800  5929 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-05 13:35:33.547  3800  5929 I SystemUpdateService: now status is 0 (complete)
,10-05 13:35:33.547  3800  5929 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:35:33.547  3800  5929 I SystemUpdateService: file has been verified
10-05 13:35:33.547  3800  5929 I SystemUpdateService: OTA package size = 21989297
,10-05 13:35:33.554  3800  5929 I SystemUpdateService: showing system update notification
,10-05 13:35:33.563  3800  3800 D SystemUpdateService: onDestroy
,10-05 13:35:33.633  4958  5935 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 13:35:36.497  5574  5930 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,10-05 13:35:36.497  5574  5942 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
10-05 13:35:36.498  5574  5942 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,10-05 13:35:36.498  5574  5930 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,10-05 13:35:36.498  5574  5930 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 13:35:36.498  5574  5942 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 13:35:36.501  5574  5930 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 13:35:36.501  5574  5942 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 13:35:36.505  5574  5942 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,10-05 13:35:36.506  5574  5930 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-05 13:35:36.507  5574  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:35:36.507  5574  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:36.509  5574  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:35:36.509  5574  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 13:35:36.511  5574  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:35:36.511  5574  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 13:35:36.511  5574  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:35:36.511  5574  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:36.512  5574  5947 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:35:36.512  5574  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 13:35:36.513  5574  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:35:36.513  5574  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 13:35:36.513  5574  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:35:36.513  5574  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 13:35:36.513  5574  5947 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:35:36.513  5574  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:35:36.514  5574  5947 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 13:35:36.514  5574  5946 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:35:36.514  5574  5947 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:35:36.514  5574  5946 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:35:36.514  5574  5947 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-05 13:35:36.514  5574  5946 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-05 13:35:36.514  5574  5947 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:35:36.514  5574  5947 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-05 13:35:36.514  5574  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:35:36.514  5574  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-05 13:35:36.515  5574  5944 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 163, thread name: OutgoingSocketThread/Sender): Socket closed
10-05 13:35:36.515  5574  5945 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 162, thread name: IncomingSocketThread/Sender): Socket closed
10-05 13:35:36.515  5574  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 163, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:35:36.515  5574  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-05 13:35:36.515  5574  5945 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 162, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:35:36.515  5574  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-05 13:35:36.515  5574  5945 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 13:35:36.515  5574  5944 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 13:35:36.515  5574  5945 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 13:35:36.515  5574  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 13:35:36.515  5574  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:35:36.515  5574  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-05 13:35:36.515  5574  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:35:36.515  5574  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-05 13:35:39.494  5574  5620 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 174)
,10-05 13:35:39.495  5574  5620 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-05 13:35:39.496  5574  5620 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 175)
,10-05 13:35:39.501  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:35:39.501  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef25ec1 added. We now have 3 listener(s)
,10-05 13:35:39.505  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:35:39.505  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.505  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.506  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.506  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575666 added. We now have 4 listener(s)
10-05 13:35:39.506  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:35:39.507  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 13:35:39.513  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:39.520  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:35:39.522  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:35:39.523  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:35:39.523  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:35:39.523  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a33e254 added. We now have 4 listener(s)
,10-05 13:35:39.525  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:35:39.525  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 13:35:39.525  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.525  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.525  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80525fd added. We now have 5 listener(s)
10-05 13:35:39.525  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.526  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:35:39.526  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.526  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:35:39.526  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.526  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:39.526  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:35:39.526  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.526  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.526  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 13:35:39.526  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef25ec1 removed from the list
10-05 13:35:39.526  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.526  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575666 removed from the list
10-05 13:35:39.529  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.530  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:35:39.530  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.531  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:39.531  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.532  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.532  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:35:39.532  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.532  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575666 not in the list
10-05 13:35:39.532  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.532  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.534  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.534  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.534  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.534  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80525fd removed from the list
10-05 13:35:39.534  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.534  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:39.534  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.534  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.534  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.535  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a33e254 removed from the list
,10-05 13:35:39.535  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.535  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7272f2 added. We now have 3 listener(s)
10-05 13:35:39.537  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.537  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.537  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 13:35:39.538  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.538  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aecdd43 added. We now have 4 listener(s)
10-05 13:35:39.538  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.539  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 13:35:39.542  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:39.548  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:35:39.549  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.550  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 13:35:39.550  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:35:39.550  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68324f9 added. We now have 4 listener(s)
,10-05 13:35:39.551  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.552  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.552  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 13:35:39.552  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.552  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb0cc3e added. We now have 5 listener(s)
10-05 13:35:39.552  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.552  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:39.552  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:35:39.552  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:35:39.552  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:35:39.552  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:35:39.553  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:39.557  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:39.558  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-05 13:35:39.558  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:35:39.562  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:35:39.563  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-05 13:35:39.563  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:35:39.566  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:35:39.566  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:35:39.566  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:35:39.567  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:35:39.567  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:35:39.568  5574  5620 D BluetoothAdapter: STATE_ON
,10-05 13:35:39.571  5859  5896 D BtGatt.GattService: registerClient() - UUID=57f75e8b-2bec-416f-bda3-805f1c8495e7
10-05 13:35:39.572  5859  5875 D BtGatt.GattService: onClientRegistered() - UUID=57f75e8b-2bec-416f-bda3-805f1c8495e7, clientIf=5
,10-05 13:35:39.572  5574  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:35:39.573  5859  5889 D BtGatt.GattService: start scan with filters
,10-05 13:35:39.577  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-05 13:35:39.577  5859  5878 D BtGatt.ScanManager: handling starting scan
10-05 13:35:39.577  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:35:39.577  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:35:39.577  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:35:39.577  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-05 13:35:39.577  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:35:39.577  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:35:39.579  5859  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7cd00cc
,10-05 13:35:39.580  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 13:35:39.580  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:35:39.580  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:35:39.582  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:35:39.584  5574  5620 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-05 13:35:39.585  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.585  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 13:35:39.585  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.585  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:35:39.585  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:35:39.585  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:35:39.585  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:35:39.585  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:35:39.585  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:35:39.585  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:35:39.585  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-05 13:35:39.586  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:35:39.587  5859  5889 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:35:39.587  5859  5875 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:35:39.587  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.588  5859  5870 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-05 13:35:39.588  5859  5878 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:35:39.588  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:35:39.588  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:35:39.588  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:35:39.588  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:35:39.589  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:35:39.589  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:35:39.589  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-05 13:35:39.589  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:35:39.590  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:35:39.590  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:35:39.590  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:35:39.590  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:35:39.590  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:35:39.591  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:35:39.594  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:35:39.594  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:35:39.594  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:35:39.595  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:35:39.595  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.596  5859  5878 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:35:39.596  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:35:39.596  5859  5878 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:35:39.596  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.596  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:35:39.596  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.596  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.596  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:35:39.596  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.596  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.596  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7272f2 removed from the list
10-05 13:35:39.596  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.596  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aecdd43 removed from the list
10-05 13:35:39.597  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:39.597  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.597  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:39.597  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.599  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.599  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.599  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.599  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aecdd43 not in the list
10-05 13:35:39.599  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.599  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.601  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:35:39.601  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.601  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.601  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb0cc3e removed from the list
10-05 13:35:39.601  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.601  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.601  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.601  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.601  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.601  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68324f9 removed from the list
10-05 13:35:39.602  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.602  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e96e4a added. We now have 3 listener(s)
10-05 13:35:39.604  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.604  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.604  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.604  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 13:35:39.604  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3ab1bb added. We now have 4 listener(s)
10-05 13:35:39.604  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.605  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:35:39.607  5859  5875 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:35:39.607  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.608  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:39.612  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:35:39.612  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:35:39.613  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.613  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.614  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:35:39.614  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.614  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f7a31 added. We now have 4 listener(s)
10-05 13:35:39.615  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.615  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.615  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.615  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.616  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5582516 added. We now have 5 listener(s)
10-05 13:35:39.616  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.616  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:39.617  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:39.617  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:35:39.617  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:35:39.617  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:35:39.617  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:35:39.617  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.620  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:35:39.620  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.620  5859  5878 D BtGatt.ScanManager: stopping BLe Batch
10-05 13:35:39.620  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:35:39.620  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 13:35:39.621  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.624  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 13:35:39.625  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:35:39.625  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 13:35:39.625  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:35:39.625  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.625  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:35:39.629  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:35:39.630  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:35:39.630  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:35:39.630  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:35:39.630  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 13:35:39.631  5574  5620 D BluetoothAdapter: STATE_ON
,10-05 13:35:39.631  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 13:35:39.631  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.633  5859  5870 D BtGatt.GattService: registerClient() - UUID=18389abc-14f7-498b-845d-e3b02ea6168f
10-05 13:35:39.633  5859  5875 D BtGatt.GattService: onClientRegistered() - UUID=18389abc-14f7-498b-845d-e3b02ea6168f, clientIf=5
,10-05 13:35:39.634  5574  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:35:39.634  5859  5899 D BtGatt.GattService: start scan with filters
10-05 13:35:39.635  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:35:39.636  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:35:39.636  5859  5878 D BtGatt.ScanManager: handling starting scan
10-05 13:35:39.636  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-05 13:35:39.636  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:35:39.636  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:35:39.636  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:35:39.636  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:35:39.638  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 13:35:39.638  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:35:39.638  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:35:39.639  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:35:39.640  5859  5875 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:35:39.641  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.641  5859  5878 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:35:39.641  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:39.641  5574  5620 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-05 13:35:39.641  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:35:39.641  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.641  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:35:39.641  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.641  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.641  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-05 13:35:39.641  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.641  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.642  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e96e4a removed from the list
10-05 13:35:39.642  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.642  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3ab1bb removed from the list
10-05 13:35:39.642  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:39.642  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:35:39.642  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.642  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 13:35:39.642  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.642  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:35:39.643  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.643  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.643  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:35:39.643  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3ab1bb not in the list
10-05 13:35:39.643  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:35:39.643  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:35:39.643  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:35:39.643  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:35:39.643  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:35:39.644  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:35:39.644  5859  5870 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:35:39.645  5859  5899 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:35:39.645  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:35:39.645  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.645  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:35:39.645  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:35:39.645  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:35:39.645  5859  5878 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:35:39.645  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:35:39.645  5859  5878 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:35:39.645  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:35:39.646  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:35:39.646  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:35:39.646  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:35:39.647  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:35:39.647  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:35:39.647  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:35:39.647  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:35:39.647  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:35:39.647  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.648  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.648  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.648  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.648  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:35:39.648  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5582516 removed from the list
10-05 13:35:39.648  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:35:39.648  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.648  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:35:39.648  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:35:39.648  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.648  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.648  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.648  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f7a31 removed from the list
10-05 13:35:39.649  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.649  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e297ca2 added. We now have 3 listener(s)
10-05 13:35:39.650  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:35:39.651  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.651  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.651  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.651  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ef9d33 added. We now have 4 listener(s)
10-05 13:35:39.651  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.652  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 13:35:39.654  5859  5875 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 13:35:39.654  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.654  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:35:39.659  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 13:35:39.659  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:39.660  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:35:39.662  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:35:39.662  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:35:39.662  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.662  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa3e69 added. We now have 4 listener(s)
10-05 13:35:39.663  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.663  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.663  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.664  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.664  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c6c0ee added. We now have 5 listener(s)
10-05 13:35:39.664  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:35:39.664  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:39.664  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:35:39.664  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:35:39.664  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:35:39.664  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:35:39.664  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.664  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:35:39.664  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.664  5859  5878 D BtGatt.ScanManager: stopping BLe Batch
10-05 13:35:39.666  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:35:39.669  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 13:35:39.669  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.669  5574  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:35:39.669  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-05 13:35:39.669  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:35:39.672  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:35:39.672  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:35:39.672  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 13:35:39.673  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 13:35:39.673  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.675  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:35:39.675  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:35:39.675  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:35:39.675  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:35:39.675  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:35:39.676  5574  5620 D BluetoothAdapter: STATE_ON
,10-05 13:35:39.677  5859  5870 D BtGatt.GattService: registerClient() - UUID=8577616f-c8cc-471c-8e85-e12b42bc336a
,10-05 13:35:39.678  5859  5875 D BtGatt.GattService: onClientRegistered() - UUID=8577616f-c8cc-471c-8e85-e12b42bc336a, clientIf=5
,10-05 13:35:39.678  5574  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 13:35:39.678  5859  5869 D BtGatt.GattService: start scan with filters
10-05 13:35:39.680  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:35:39.680  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:35:39.680  5859  5878 D BtGatt.ScanManager: handling starting scan
10-05 13:35:39.680  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:35:39.680  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:35:39.680  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:35:39.680  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:35:39.680  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:35:39.682  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:35:39.682  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-05 13:35:39.682  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:35:39.683  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-05 13:35:39.685  5859  5875 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-05 13:35:39.685  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.686  5859  5878 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 13:35:39.687  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:35:39.687  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.687  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:35:39.687  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.687  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.687  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:35:39.687  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.687  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.687  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e297ca2 removed from the list
10-05 13:35:39.688  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.688  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ef9d33 removed from the list
10-05 13:35:39.688  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:39.688  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:35:39.688  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.688  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 13:35:39.688  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.688  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:35:39.689  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:35:39.690  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.690  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.690  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ef9d33 not in the list
10-05 13:35:39.690  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:35:39.690  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:35:39.690  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:35:39.690  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:35:39.690  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:35:39.690  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:35:39.691  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.691  5859  5878 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:35:39.691  5574  5620 D BluetoothAdapter: STATE_ON
10-05 13:35:39.691  5859  5878 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:35:39.691  5859  5889 D BtGatt.GattService: stopScan() - queue size =1
,10-05 13:35:39.692  5859  5899 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-05 13:35:39.692  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:35:39.692  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:35:39.693  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:35:39.693  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:35:39.693  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:35:39.693  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:35:39.693  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-05 13:35:39.693  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:35:39.694  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:35:39.694  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:35:39.694  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:35:39.694  5574  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:35:39.694  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:35:39.694  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.695  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.695  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.695  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.695  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 13:35:39.695  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c6c0ee removed from the list
10-05 13:35:39.695  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.695  5574  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:35:39.695  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.695  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.695  5574  5574 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:35:39.695  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.695  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.696  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa3e69 removed from the list
10-05 13:35:39.696  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.696  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e1fdfa added. We now have 3 listener(s)
,10-05 13:35:39.697  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.698  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.698  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.698  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 13:35:39.698  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f77fab added. We now have 4 listener(s)
10-05 13:35:39.698  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.698  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:35:39.699  5859  5875 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:35:39.699  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.701  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:35:39.704  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:35:39.704  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:35:39.706  5574  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:35:39.707  5574  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:35:39.708  5574  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:35:39.708  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:35:39.708  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6251a1 added. We now have 4 listener(s)
10-05 13:35:39.709  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:35:39.709  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:35:39.709  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:35:39.709  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:35:39.709  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41ffc6 added. We now have 5 listener(s)
10-05 13:35:39.709  5574  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:35:39.709  5574  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:35:39.709  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.710  5574  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:35:39.710  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:35:39.710  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:35:39.710  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.710  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.710  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.710  5859  5878 D BtGatt.ScanManager: stopping BLe Batch
10-05 13:35:39.710  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:35:39.710  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:35:39.710  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 13:35:39.710  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e1fdfa removed from the list
10-05 13:35:39.710  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.710  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f77fab removed from the list
10-05 13:35:39.712  5574  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:35:39.712  5574  5620 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:35:39.712  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.713  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.713  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.716  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:35:39.716  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:35:39.717  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.717  5574  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f77fab not in the list
10-05 13:35:39.717  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.717  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:35:39.717  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:35:39.717  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:35:39.718  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:35:39.718  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:35:39.718  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:35:39.718  5574  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:35:39.718  5574  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41ffc6 removed from the list
10-05 13:35:39.718  5574  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:35:39.718  5574  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:35:39.718  5574  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:35:39.718  5574  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:35:39.718  5574  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:35:39.718  5574  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6251a1 removed from the list
10-05 13:35:39.719  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,10-05 13:35:39.719  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-05 13:35:39.719  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-05 13:35:39.719  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:39.719  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-05 13:35:39.719  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:39.722  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-05 13:35:39.722  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:35:40.095  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:35:40.148  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:35:40.196  5574  5574 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:35:41.401   931  2925 D ConnectivityService: handlePromptUnvalidated 102
,10-05 13:35:41.914  5574  5948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 13:35:41.914  5574  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:42.728  5574  5948 W !!      : call onHalfStreamCopied
,10-05 13:35:42.728  5574  5948 I testCopyDataAndClose: closing input stream
,10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:35:43.503  5574  5948 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-05 13:35:43.504  5574  5948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 13:35:43.504  5574  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 13:35:44.356   931  2911 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,10-05 13:35:45.244   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:47.290  5574  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:47.290  5574  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:48.282   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:49.290  5574  5620 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186. Connection data: Peer properties: [null null].
10-05 13:35:49.290  5574  5620 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:49.290  5574  5620 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,10-05 13:35:49.423  5574  5949 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-05 13:35:49.423  5574  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:49.423  5574  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-05 13:35:49.443  5574  5950 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 13:35:49.443  5574  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:51.062  5574  5950 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 188, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 13:35:51.062  5574  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 13:35:51.063  5574  5950 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 13:35:51.309   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:54.330   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:35:54.793  5574  5951 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:54.793  5574  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 13:35:54.794  5574  5951 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:35:54.795  5574  5951 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:35:54.795  5574  5951 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:35:54.795  5574  5951 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:54.795  5574  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-05 13:35:54.797  5574  5620 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 13:35:54.799  5574  5952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:54.799  5574  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:35:54.799  5574  5952 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 194, thread name: My test thread name): Test exception.
10-05 13:35:54.800  5574  5952 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 194, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:54.800  5574  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-05 13:35:54.800  5574  5952 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-05 13:35:54.800  5574  5952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:35:54.800  5574  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-05 13:35:54.804  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Total number of executed tests:  83'
10-05 13:35:54.804  5574  5620 I jxcore-log: 
,10-05 13:35:54.804  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Number of passed tests:  83'
10-05 13:35:54.804  5574  5620 I jxcore-log: 
10-05 13:35:54.804  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-05 13:35:54.804  5574  5620 I jxcore-log: 
10-05 13:35:54.805  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-05 13:35:54.805  5574  5620 I jxcore-log: 
,10-05 13:35:54.805  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Total duration:  96863'
10-05 13:35:54.805  5574  5620 I jxcore-log: 
10-05 13:35:54.807  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-05 13:35:54.807  5574  5620 I jxcore-log: 
,10-05 13:35:54.811  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.811  5574  5620 I jxcore-log: 
,10-05 13:35:54.812  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.812  5574  5620 I jxcore-log: 
10-05 13:35:54.813  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.813  5574  5620 I jxcore-log: 
10-05 13:35:54.813  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.813  5574  5620 I jxcore-log: 
10-05 13:35:54.813  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 13:35:54.813  5574  5620 I jxcore-log: 
,10-05 13:35:54.814  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:35:54.814  5574  5620 I jxcore-log: 
10-05 13:35:54.814  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.814  5574  5620 I jxcore-log: 
10-05 13:35:54.814  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.814  5574  5620 I jxcore-log: 
10-05 13:35:54.815  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 13:35:54.815  5574  5620 I jxcore-log: 
10-05 13:35:54.815  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:35:54.815  5574  5620 I jxcore-log: 
10-05 13:35:54.815  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:35:54.815  5574  5620 I jxcore-log: 
10-05 13:35:54.815  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.815  5574  5620 I jxcore-log: 
,10-05 13:35:54.816  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.816  5574  5620 I jxcore-log: 
10-05 13:35:54.816  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.816  5574  5620 I jxcore-log: 
10-05 13:35:54.816  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.816  5574  5620 I jxcore-log: 
10-05 13:35:54.817  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.817  5574  5620 I jxcore-log: 
,10-05 13:35:54.817  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.817  5574  5620 I jxcore-log: 
10-05 13:35:54.817  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.817  5574  5620 I jxcore-log: 
10-05 13:35:54.818  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.818  5574  5620 I jxcore-log: 
10-05 13:35:54.818  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.818  5574  5620 I jxcore-log: 
10-05 13:35:54.818  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.818  5574  5620 I jxcore-log: 
,10-05 13:35:54.818  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.818  5574  5620 I jxcore-log: 
10-05 13:35:54.819  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.819  5574  5620 I jxcore-log: 
,10-05 13:35:54.821  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.821  5574  5620 I jxcore-log: 
10-05 13:35:54.821  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.821  5574  5620 I jxcore-log: 
10-05 13:35:54.821  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.821  5574  5620 I jxcore-log: 
,10-05 13:35:54.822  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.822  5574  5620 I jxcore-log: 
10-05 13:35:54.822  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.822  5574  5620 I jxcore-log: 
,10-05 13:35:54.822  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.822  5574  5620 I jxcore-log: 
10-05 13:35:54.822  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.822  5574  5620 I jxcore-log: 
10-05 13:35:54.823  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.823  5574  5620 I jxcore-log: 
10-05 13:35:54.823  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.823  5574  5620 I jxcore-log: 
10-05 13:35:54.823  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.823  5574  5620 I jxcore-log: 
10-05 13:35:54.823  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.823  5574  5620 I jxcore-log: 
,10-05 13:35:54.823  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.823  5574  5620 I jxcore-log: 
,10-05 13:35:54.824  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.824  5574  5620 I jxcore-log: 
10-05 13:35:54.824  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.824  5574  5620 I jxcore-log: 
10-05 13:35:54.824  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.824  5574  5620 I jxcore-log: 
10-05 13:35:54.824  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.824  5574  5620 I jxcore-log: 
10-05 13:35:54.825  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:35:54.825  5574  5620 I jxcore-log: 
10-05 13:35:54.825  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.825  5574  5620 I jxcore-log: 
,10-05 13:35:54.825  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 13:35:54.825  5574  5620 I jxcore-log: 
10-05 13:35:54.825  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.825  5574  5620 I jxcore-log: 
10-05 13:35:54.825  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.825  5574  5620 I jxcore-log: 
10-05 13:35:54.826  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.826  5574  5620 I jxcore-log: 
10-05 13:35:54.826  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.826  5574  5620 I jxcore-log: 
10-05 13:35:54.826  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.826  5574  5620 I jxcore-log: 
,10-05 13:35:54.826  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:35:54.826  5574  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-05 13:35:54.827  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.827  5574  5620 I jxcore-log: 
10-05 13:35:54.827  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.827  5574  5620 I jxcore-log: 
10-05 13:35:54.827  5574  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:35:54.827  5574  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-05 13:35:54.827  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:35:54.827  5574  5620 I jxcore-log: 
,10-05 13:35:54.827  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:35:54.827  5574  5620 I jxcore-log: 
10-05 13:35:54.828  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:35:54.828  5574  5620 I jxcore-log: 
10-05 13:35:54.828  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:35:54.828  5574  5620 I jxcore-log: 
,10-05 13:35:54.833  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-05 13:35:54.833  5574  5620 I jxcore-log: 
,10-05 13:35:54.833  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - WARN testUtils: 'myNameCallback not set!'
10-05 13:35:54.833  5574  5620 I jxcore-log: 
10-05 13:35:54.834  5574  5574 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-05 13:35:54.834  5574  5620 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-05 13:35:54.835  5574  5620 I jxcore-log: 2016-10-05 17:35:54 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-05 13:35:54.835  5574  5620 I jxcore-log: 
,10-05 13:35:55.285  5574  5620 I jxcore-log: 2016-10-05 17:35:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-05 13:35:55.285  5574  5620 I jxcore-log: 
,10-05 13:35:55.656  5574  5620 I jxcore-log: 2016-10-05 17:35:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-05 13:35:55.656  5574  5620 I jxcore-log: 
,10-05 13:35:55.672  5574  5620 I jxcore-log: 2016-10-05 17:35:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-05 13:35:55.672  5574  5620 I jxcore-log: 
,10-05 13:35:55.921   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 13:35:55.921   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-05 13:35:56.753  5574  5620 I jxcore-log: 2016-10-05 17:35:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-05 13:35:56.753  5574  5620 I jxcore-log: 
,10-05 13:35:56.913  5574  5620 I jxcore-log: 2016-10-05 17:35:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-05 13:35:56.913  5574  5620 I jxcore-log: 
,10-05 13:35:56.918  5574  5620 I jxcore-log: 2016-10-05 17:35:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-05 13:35:56.918  5574  5620 I jxcore-log: 
,10-05 13:35:56.922  5574  5620 I jxcore-log: 2016-10-05 17:35:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-05 13:35:56.922  5574  5620 I jxcore-log: 
,10-05 13:35:57.451  5574  5620 I jxcore-log: 2016-10-05 17:35:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-05 13:35:57.451  5574  5620 I jxcore-log: 
,10-05 13:35:57.502  5574  5620 I jxcore-log: 2016-10-05 17:35:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-05 13:35:57.502  5574  5620 I jxcore-log: 
,10-05 13:35:57.515  5574  5620 I jxcore-log: 2016-10-05 17:35:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-05 13:35:57.515  5574  5620 I jxcore-log: 
,10-05 13:35:57.519  5574  5620 I jxcore-log: 2016-10-05 17:35:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-05 13:35:57.519  5574  5620 I jxcore-log: 
,10-05 13:35:57.937  5574  5620 I jxcore-log: 2016-10-05 17:35:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-05 13:35:57.937  5574  5620 I jxcore-log: 
,10-05 13:35:58.059  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-05 13:35:58.059  5574  5620 I jxcore-log: 
,10-05 13:35:58.280  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-05 13:35:58.280  5574  5620 I jxcore-log: 
,10-05 13:35:58.290  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-05 13:35:58.290  5574  5620 I jxcore-log: 
,10-05 13:35:58.294  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-05 13:35:58.294  5574  5620 I jxcore-log: 
,10-05 13:35:58.298  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-05 13:35:58.298  5574  5620 I jxcore-log: 
,10-05 13:35:58.303  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-05 13:35:58.303  5574  5620 I jxcore-log: 
,10-05 13:35:58.329  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-05 13:35:58.329  5574  5620 I jxcore-log: 
,10-05 13:35:58.365  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-05 13:35:58.365  5574  5620 I jxcore-log: 
,10-05 13:35:58.372  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-05 13:35:58.372  5574  5620 I jxcore-log: 
,10-05 13:35:58.378  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-05 13:35:58.378  5574  5620 I jxcore-log: 
,10-05 13:35:58.393  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-05 13:35:58.393  5574  5620 I jxcore-log: 
,10-05 13:35:58.398  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-05 13:35:58.398  5574  5620 I jxcore-log: 
,10-05 13:35:58.404  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-05 13:35:58.404  5574  5620 I jxcore-log: 
,10-05 13:35:58.409  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-05 13:35:58.409  5574  5620 I jxcore-log: 
,10-05 13:35:58.422  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-05 13:35:58.422  5574  5620 I jxcore-log: 
,10-05 13:35:58.443  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-05 13:35:58.443  5574  5620 I jxcore-log: 
,10-05 13:35:58.452  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-05 13:35:58.452  5574  5620 I jxcore-log: 
,10-05 13:35:58.463  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-05 13:35:58.463  5574  5620 I jxcore-log: 
,10-05 13:35:58.472  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-05 13:35:58.472  5574  5620 I jxcore-log: 
,10-05 13:35:58.484  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-05 13:35:58.484  5574  5620 I jxcore-log: 
,10-05 13:35:58.494  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-05 13:35:58.494  5574  5620 I jxcore-log: 
,10-05 13:35:58.499  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-05 13:35:58.499  5574  5620 I jxcore-log: 
,10-05 13:35:58.519  5574  5620 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-05 13:35:58.521  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - INFO testUtils: 'BLE multiple advertisement supported'
10-05 13:35:58.521  5574  5620 I jxcore-log: 
,10-05 13:35:58.558  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - DEBUG ServerClient: 'connecting to '85.14.110.168:3000''
10-05 13:35:58.558  5574  5620 I jxcore-log: 
,10-05 13:35:58.571  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - DEBUG ServerClient: 'connected to '85.14.110.168:3000''
10-05 13:35:58.571  5574  5620 I jxcore-log: 
,10-05 13:35:58.572  5574  5620 I jxcore-log: 2016-10-05 17:35:58 - DEBUG CoordinatedClient: 'connected to the test server'
10-05 13:35:58.572  5574  5620 I jxcore-log: 
,10-05 13:36:03.408   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:09.473   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:10.923   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:11.924   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:12.925   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:13.376   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:36:13.927   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:14.928   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:15.929   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-05 13:36:20.931   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:21.594   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:21.932   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:22.934   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:23.935   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:24.626   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:24.937   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:25.938   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-05 13:36:27.653   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:30.683   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:33.061   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=366770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-05 13:36:33.702   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:35.939   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:36.717   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:36.941   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:37.942   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:38.943   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:39.945   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:40.946   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-05 13:36:51.862   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:53.382   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:36:55.947   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:56.948   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:57.921   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:36:57.949   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:58.951   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:36:59.952   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:37:00.953   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-05 13:37:10.020   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:37:11.888   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-05 13:37:13.059   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:37:13.382   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:37:20.955   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:37:21.956   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:37:22.958   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:37:23.959   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:37:24.961   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:37:25.962   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-05 13:37:40.309   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:37:46.362   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:37:46.447   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440156, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-05 13:37:50.963   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 13:37:50.963   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-05 13:37:53.388   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:37:58.485   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:01.519   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:10.964   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:11.966   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:12.967   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:13.391   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:38:13.968   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:14.970   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:15.971   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-05 13:38:16.652   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:19.683   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:20.972   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:21.974   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:22.975   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:23.976   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:24.977   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:25.978   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-05 13:38:31.796   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:33.393   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:38:35.980   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:36.981   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:37.859   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102],
,10-05 13:38:37.982   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:38.984   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:39.985   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:40.986   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-05 13:38:46.939   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:52.997   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:38:55.987   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:56.989   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:57.990   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:58.992   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:38:59.040  5574  5620 I jxcore-log: 2016-10-05 17:38:59 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-05 13:38:59.040  5574  5620 I jxcore-log: 
,10-05 13:38:59.275  5574  5620 I jxcore-log: 2016-10-05 17:38:59 - ERROR ServerClient: 'socket error: 'Error: connect ECONNREFUSED', stack: '$c@net.js:837:7
10-05 13:38:59.275  5574  5620 I jxcore-log: $09@net.js:829:13
10-05 13:38:59.275  5574  5620 I jxcore-log: ''
10-05 13:38:59.275  5574  5620 I jxcore-log: 
,10-05 13:38:59.282  5574  5620 I jxcore-log: 2016-10-05 17:38:59 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-05 13:38:59.282  5574  5620 I jxcore-log: 
,10-05 13:38:59.993   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:39:00.994   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-05 13:39:01.320  5574  5620 I jxcore-log: 2016-10-05 17:39:01 - ERROR ServerClient: 'socket error: 'Error: connect ECONNREFUSED', stack: '$c@net.js:837:7
10-05 13:39:01.320  5574  5620 I jxcore-log: $09@net.js:829:13
10-05 13:39:01.320  5574  5620 I jxcore-log: ''
10-05 13:39:01.320  5574  5620 I jxcore-log: 
,10-05 13:39:01.323  5574  5620 I jxcore-log: 2016-10-05 17:39:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-05 13:39:01.323  5574  5620 I jxcore-log: 
,10-05 13:39:03.301   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=517010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 13:39:05.094   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:39:11.152   931  2925 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:39:13.398   931  2911 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437

```
